# CreateCompositionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Name of the composition | 
**WidgetId** | **string** | ID of the widget this composition is based on | 
**CreatorId** | Pointer to **string** | ID of the user creating the composition | [optional] 
**Content** | Pointer to **map[string]interface{}** | Content data for the composition | [optional] 
**Status** | Pointer to **string** | Initial status of the composition | [optional] [default to "draft"]
**EmbedSettings** | Pointer to **map[string]interface{}** | Settings for embedding the composition | [optional] 
**Design** | Pointer to **map[string]interface{}** | Design settings for the composition | [optional] 
**DatabaseSchema** | Pointer to **map[string]interface{}** | The tables this composition keeps what visitors send it in (votes, ratings, answers). They are made when the composition is created, in a schema of their own that no other composition can reach: in Widgetic&#39;s database, or in your own Neon database when you have set one with &#x60;setPartnerDataDatabase&#x60;. They are deleted with the composition.  The shape is &#x60;{ \&quot;tables\&quot;: [ ... ] }&#x60;. A table has a &#x60;name&#x60;, a list of &#x60;columns&#x60; and, optionally, a list of &#x60;indexes&#x60;, and optionally &#x60;countable&#x60;. A column has a &#x60;name&#x60; and a &#x60;type&#x60;, and optionally &#x60;primaryKey&#x60;, &#x60;notNull&#x60;, &#x60;unique&#x60;, &#x60;default&#x60; and &#x60;readable&#x60;. An index has a &#x60;name&#x60; and the &#x60;columns&#x60; it covers (1 to 8), and optionally &#x60;unique&#x60;. Any other key is refused, except &#x60;source&#x60; (see below).  &#x60;countable&#x60; and &#x60;readable&#x60; are the read policy of the composition&#39;s own page: nothing the visitors sent can be read back by the page until you say so. &#x60;countable: true&#x60; on a table lets the widget show how many rows it has; &#x60;readable: true&#x60; on a column lets it show or total that column&#39;s values (a tally of votes, an average rating). Mark only what is safe to show to anyone who opens the page. A column whose name holds &#x60;email&#x60;, &#x60;phone&#x60;, &#x60;address&#x60;, &#x60;token&#x60;, &#x60;password&#x60;, &#x60;secret&#x60;, &#x60;ip&#x60; or the like, and a &#x60;json&#x60;, &#x60;jsonb&#x60; or &#x60;uuid&#x60; column, cannot be &#x60;readable&#x60;.  - Names (tables, columns, indexes) use lower-case letters, digits and underscores, start with a letter and   are at most 63 characters long. A name that starts with &#x60;_&#x60; or &#x60;pg_&#x60; is reserved. - &#x60;type&#x60; is one of &#x60;text&#x60;, &#x60;smallint&#x60;, &#x60;integer&#x60; (or &#x60;int&#x60;), &#x60;bigint&#x60;, &#x60;numeric&#x60;, &#x60;real&#x60;,   &#x60;double precision&#x60;, &#x60;boolean&#x60; (or &#x60;bool&#x60;), &#x60;date&#x60;, &#x60;timestamp&#x60;, &#x60;timestamptz&#x60; (or   &#x60;timestamp with time zone&#x60;), &#x60;uuid&#x60;, &#x60;json&#x60;, &#x60;jsonb&#x60;, &#x60;serial&#x60;, &#x60;bigserial&#x60;. - &#x60;default&#x60; is a number, &#x60;true&#x60; or &#x60;false&#x60;, a text of at most 500 characters (no backslash), a JSON value   for a &#x60;json&#x60; or &#x60;jsonb&#x60; column, or one of &#x60;now()&#x60;, &#x60;current_timestamp&#x60; and &#x60;current_date&#x60; (date and   timestamp columns) and &#x60;gen_random_uuid()&#x60; (a &#x60;uuid&#x60; column). A &#x60;serial&#x60; column numbers itself and has   no default. - A composition declares at most 20 tables, with at most 64 columns and 10 indexes each.  A declaration that cannot be used is refused with &#x60;400&#x60; and &#x60;INVALID_DATABASE_SCHEMA&#x60;; &#x60;error.details.problems&#x60; lists what to change. Tables that already exist are never changed or dropped: sending more tables later, when you update the composition, adds the ones that are missing. When the composition is saved but its tables cannot be made just now, the answer says so in &#x60;meta.warnings&#x60;: send the same &#x60;databaseSchema&#x60; again to retry.  Leave it out and the composition gets the tables its widget declares in its own source (&#x60;src/lib/meta/database.json&#x60;), if any. Send &#x60;{ \&quot;tables\&quot;: [] }&#x60; to give the composition no tables and keep it from getting its widget&#39;s.  A composition whose tables were made from its widget&#39;s own file reads back with &#x60;\&quot;source\&quot;: \&quot;widget\&quot;&#x60; next to &#x60;tables&#x60;. When the widget is published again, a table, a field or an index its file gained is added to them; nothing that exists is changed or dropped, and what a page may read does not change. Send &#x60;source&#x60; back as it was and it stays. Leave it out and the tables are yours: no widget&#39;s file adds anything to them. It is the only value &#x60;source&#x60; can have.  | [optional] 
**ProjectId** | Pointer to **string** | ID of the project this composition belongs to | [optional] 
**ManagedUserId** | Pointer to **string** | Make the composition for one of your managed users, by Widgetic&#39;s id for the user. Send this or &#x60;managedUserExternalId&#x60;, not both. The managed user must be yours and active. The composition stays in your account; the tag lets you list one user&#39;s compositions and keeps it out of the others&#39; lists. It is set here and does not change afterwards. | [optional] 
**ManagedUserExternalId** | Pointer to **string** | The same, by your own identifier for the user, the &#x60;externalId&#x60; you gave when you created the managed user (answers show it as &#x60;externalId&#x60;). Send this or &#x60;managedUserId&#x60;, not both. | [optional] 

## Methods

### NewCreateCompositionRequest

`func NewCreateCompositionRequest(name string, widgetId string, ) *CreateCompositionRequest`

NewCreateCompositionRequest instantiates a new CreateCompositionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateCompositionRequestWithDefaults

`func NewCreateCompositionRequestWithDefaults() *CreateCompositionRequest`

NewCreateCompositionRequestWithDefaults instantiates a new CreateCompositionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateCompositionRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateCompositionRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateCompositionRequest) SetName(v string)`

SetName sets Name field to given value.


### GetWidgetId

`func (o *CreateCompositionRequest) GetWidgetId() string`

GetWidgetId returns the WidgetId field if non-nil, zero value otherwise.

### GetWidgetIdOk

`func (o *CreateCompositionRequest) GetWidgetIdOk() (*string, bool)`

GetWidgetIdOk returns a tuple with the WidgetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidgetId

`func (o *CreateCompositionRequest) SetWidgetId(v string)`

SetWidgetId sets WidgetId field to given value.


### GetCreatorId

`func (o *CreateCompositionRequest) GetCreatorId() string`

GetCreatorId returns the CreatorId field if non-nil, zero value otherwise.

### GetCreatorIdOk

`func (o *CreateCompositionRequest) GetCreatorIdOk() (*string, bool)`

GetCreatorIdOk returns a tuple with the CreatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatorId

`func (o *CreateCompositionRequest) SetCreatorId(v string)`

SetCreatorId sets CreatorId field to given value.

### HasCreatorId

`func (o *CreateCompositionRequest) HasCreatorId() bool`

HasCreatorId returns a boolean if a field has been set.

### GetContent

`func (o *CreateCompositionRequest) GetContent() map[string]interface{}`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *CreateCompositionRequest) GetContentOk() (*map[string]interface{}, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *CreateCompositionRequest) SetContent(v map[string]interface{})`

SetContent sets Content field to given value.

### HasContent

`func (o *CreateCompositionRequest) HasContent() bool`

HasContent returns a boolean if a field has been set.

### GetStatus

`func (o *CreateCompositionRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CreateCompositionRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CreateCompositionRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CreateCompositionRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetEmbedSettings

`func (o *CreateCompositionRequest) GetEmbedSettings() map[string]interface{}`

GetEmbedSettings returns the EmbedSettings field if non-nil, zero value otherwise.

### GetEmbedSettingsOk

`func (o *CreateCompositionRequest) GetEmbedSettingsOk() (*map[string]interface{}, bool)`

GetEmbedSettingsOk returns a tuple with the EmbedSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmbedSettings

`func (o *CreateCompositionRequest) SetEmbedSettings(v map[string]interface{})`

SetEmbedSettings sets EmbedSettings field to given value.

### HasEmbedSettings

`func (o *CreateCompositionRequest) HasEmbedSettings() bool`

HasEmbedSettings returns a boolean if a field has been set.

### GetDesign

`func (o *CreateCompositionRequest) GetDesign() map[string]interface{}`

GetDesign returns the Design field if non-nil, zero value otherwise.

### GetDesignOk

`func (o *CreateCompositionRequest) GetDesignOk() (*map[string]interface{}, bool)`

GetDesignOk returns a tuple with the Design field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesign

`func (o *CreateCompositionRequest) SetDesign(v map[string]interface{})`

SetDesign sets Design field to given value.

### HasDesign

`func (o *CreateCompositionRequest) HasDesign() bool`

HasDesign returns a boolean if a field has been set.

### GetDatabaseSchema

`func (o *CreateCompositionRequest) GetDatabaseSchema() map[string]interface{}`

GetDatabaseSchema returns the DatabaseSchema field if non-nil, zero value otherwise.

### GetDatabaseSchemaOk

`func (o *CreateCompositionRequest) GetDatabaseSchemaOk() (*map[string]interface{}, bool)`

GetDatabaseSchemaOk returns a tuple with the DatabaseSchema field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatabaseSchema

`func (o *CreateCompositionRequest) SetDatabaseSchema(v map[string]interface{})`

SetDatabaseSchema sets DatabaseSchema field to given value.

### HasDatabaseSchema

`func (o *CreateCompositionRequest) HasDatabaseSchema() bool`

HasDatabaseSchema returns a boolean if a field has been set.

### GetProjectId

`func (o *CreateCompositionRequest) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CreateCompositionRequest) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CreateCompositionRequest) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *CreateCompositionRequest) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetManagedUserId

`func (o *CreateCompositionRequest) GetManagedUserId() string`

GetManagedUserId returns the ManagedUserId field if non-nil, zero value otherwise.

### GetManagedUserIdOk

`func (o *CreateCompositionRequest) GetManagedUserIdOk() (*string, bool)`

GetManagedUserIdOk returns a tuple with the ManagedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUserId

`func (o *CreateCompositionRequest) SetManagedUserId(v string)`

SetManagedUserId sets ManagedUserId field to given value.

### HasManagedUserId

`func (o *CreateCompositionRequest) HasManagedUserId() bool`

HasManagedUserId returns a boolean if a field has been set.

### GetManagedUserExternalId

`func (o *CreateCompositionRequest) GetManagedUserExternalId() string`

GetManagedUserExternalId returns the ManagedUserExternalId field if non-nil, zero value otherwise.

### GetManagedUserExternalIdOk

`func (o *CreateCompositionRequest) GetManagedUserExternalIdOk() (*string, bool)`

GetManagedUserExternalIdOk returns a tuple with the ManagedUserExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUserExternalId

`func (o *CreateCompositionRequest) SetManagedUserExternalId(v string)`

SetManagedUserExternalId sets ManagedUserExternalId field to given value.

### HasManagedUserExternalId

`func (o *CreateCompositionRequest) HasManagedUserExternalId() bool`

HasManagedUserExternalId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


