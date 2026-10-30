# Composition

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Unique identifier for the composition | 
**CreatorId** | **string** | ID of the user who created the composition | 
**WidgetId** | **string** | ID of the widget this composition is based on | 
**Name** | **string** | Name of the composition | 
**Content** | **map[string]interface{}** | Content data for the composition | 
**ContentVersion** | Pointer to **int32** | Monotonic content version when the content_version migration is applied | [optional] 
**Status** | **string** | Current status of the composition | 
**CreatedAt** | **time.Time** | When the composition was created | 
**UpdatedAt** | **time.Time** | When the composition was last updated | 
**EmbedSettings** | Pointer to **map[string]interface{}** | Settings for embedding the composition | [optional] 
**Design** | Pointer to **map[string]interface{}** | Design settings for the composition | [optional] 
**DatabaseId** | Pointer to **string** | Legacy. The id of a Neon database that an earlier version made for this composition. A composition now keeps its tables in a schema of its own (named &#x60;comp_&#x60; followed by its id) in a database shared with other compositions, so new compositions have none. | [optional] 
**ProjectId** | Pointer to **string** | ID of the project this composition belongs to | [optional] 
**ManagedUserId** | Pointer to **NullableString** | The managed user the composition was made for, or null when it is your own. List one managed user&#39;s compositions with the &#x60;managedUserId&#x60; or &#x60;managedUserExternalId&#x60; query parameter of &#x60;getAllCompositions&#x60;. | [optional] 
**Direct** | Pointer to **NullableBool** | Whether the widget the composition is made from is drawn straight into the page, without a frame (&#x60;true&#x60;), or inside a frame (&#x60;false&#x60;). &#x60;null&#x60; when the widget has no published version yet. It is a fact about the widget&#39;s published version, so every composition of one widget answers the same, and it changes when you publish another version. It cannot be set. Only &#x60;getCompositionById&#x60; returns it: the other calls that return a composition leave it out, and so does that one on the rare occasion the answer could not be worked out just then (ask again).  | [optional] 
**LastEditedBy** | Pointer to [**NullableCompositionLastEditedBy**](CompositionLastEditedBy.md) |  | [optional] 
**LastEditedAt** | Pointer to **NullableTime** | When that latest change was made. Present whenever &#x60;lastEditedBy&#x60; is. | [optional] 

## Methods

### NewComposition

`func NewComposition(id string, creatorId string, widgetId string, name string, content map[string]interface{}, status string, createdAt time.Time, updatedAt time.Time, ) *Composition`

NewComposition instantiates a new Composition object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompositionWithDefaults

`func NewCompositionWithDefaults() *Composition`

NewCompositionWithDefaults instantiates a new Composition object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Composition) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Composition) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Composition) SetId(v string)`

SetId sets Id field to given value.


### GetCreatorId

`func (o *Composition) GetCreatorId() string`

GetCreatorId returns the CreatorId field if non-nil, zero value otherwise.

### GetCreatorIdOk

`func (o *Composition) GetCreatorIdOk() (*string, bool)`

GetCreatorIdOk returns a tuple with the CreatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatorId

`func (o *Composition) SetCreatorId(v string)`

SetCreatorId sets CreatorId field to given value.


### GetWidgetId

`func (o *Composition) GetWidgetId() string`

GetWidgetId returns the WidgetId field if non-nil, zero value otherwise.

### GetWidgetIdOk

`func (o *Composition) GetWidgetIdOk() (*string, bool)`

GetWidgetIdOk returns a tuple with the WidgetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidgetId

`func (o *Composition) SetWidgetId(v string)`

SetWidgetId sets WidgetId field to given value.


### GetName

`func (o *Composition) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Composition) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Composition) SetName(v string)`

SetName sets Name field to given value.


### GetContent

`func (o *Composition) GetContent() map[string]interface{}`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *Composition) GetContentOk() (*map[string]interface{}, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *Composition) SetContent(v map[string]interface{})`

SetContent sets Content field to given value.


### GetContentVersion

`func (o *Composition) GetContentVersion() int32`

GetContentVersion returns the ContentVersion field if non-nil, zero value otherwise.

### GetContentVersionOk

`func (o *Composition) GetContentVersionOk() (*int32, bool)`

GetContentVersionOk returns a tuple with the ContentVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentVersion

`func (o *Composition) SetContentVersion(v int32)`

SetContentVersion sets ContentVersion field to given value.

### HasContentVersion

`func (o *Composition) HasContentVersion() bool`

HasContentVersion returns a boolean if a field has been set.

### GetStatus

`func (o *Composition) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Composition) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Composition) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetCreatedAt

`func (o *Composition) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Composition) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Composition) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *Composition) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Composition) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Composition) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetEmbedSettings

`func (o *Composition) GetEmbedSettings() map[string]interface{}`

GetEmbedSettings returns the EmbedSettings field if non-nil, zero value otherwise.

### GetEmbedSettingsOk

`func (o *Composition) GetEmbedSettingsOk() (*map[string]interface{}, bool)`

GetEmbedSettingsOk returns a tuple with the EmbedSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmbedSettings

`func (o *Composition) SetEmbedSettings(v map[string]interface{})`

SetEmbedSettings sets EmbedSettings field to given value.

### HasEmbedSettings

`func (o *Composition) HasEmbedSettings() bool`

HasEmbedSettings returns a boolean if a field has been set.

### GetDesign

`func (o *Composition) GetDesign() map[string]interface{}`

GetDesign returns the Design field if non-nil, zero value otherwise.

### GetDesignOk

`func (o *Composition) GetDesignOk() (*map[string]interface{}, bool)`

GetDesignOk returns a tuple with the Design field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesign

`func (o *Composition) SetDesign(v map[string]interface{})`

SetDesign sets Design field to given value.

### HasDesign

`func (o *Composition) HasDesign() bool`

HasDesign returns a boolean if a field has been set.

### GetDatabaseId

`func (o *Composition) GetDatabaseId() string`

GetDatabaseId returns the DatabaseId field if non-nil, zero value otherwise.

### GetDatabaseIdOk

`func (o *Composition) GetDatabaseIdOk() (*string, bool)`

GetDatabaseIdOk returns a tuple with the DatabaseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatabaseId

`func (o *Composition) SetDatabaseId(v string)`

SetDatabaseId sets DatabaseId field to given value.

### HasDatabaseId

`func (o *Composition) HasDatabaseId() bool`

HasDatabaseId returns a boolean if a field has been set.

### GetProjectId

`func (o *Composition) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *Composition) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *Composition) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *Composition) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetManagedUserId

`func (o *Composition) GetManagedUserId() string`

GetManagedUserId returns the ManagedUserId field if non-nil, zero value otherwise.

### GetManagedUserIdOk

`func (o *Composition) GetManagedUserIdOk() (*string, bool)`

GetManagedUserIdOk returns a tuple with the ManagedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUserId

`func (o *Composition) SetManagedUserId(v string)`

SetManagedUserId sets ManagedUserId field to given value.

### HasManagedUserId

`func (o *Composition) HasManagedUserId() bool`

HasManagedUserId returns a boolean if a field has been set.

### SetManagedUserIdNil

`func (o *Composition) SetManagedUserIdNil(b bool)`

 SetManagedUserIdNil sets the value for ManagedUserId to be an explicit nil

### UnsetManagedUserId
`func (o *Composition) UnsetManagedUserId()`

UnsetManagedUserId ensures that no value is present for ManagedUserId, not even an explicit nil
### GetDirect

`func (o *Composition) GetDirect() bool`

GetDirect returns the Direct field if non-nil, zero value otherwise.

### GetDirectOk

`func (o *Composition) GetDirectOk() (*bool, bool)`

GetDirectOk returns a tuple with the Direct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirect

`func (o *Composition) SetDirect(v bool)`

SetDirect sets Direct field to given value.

### HasDirect

`func (o *Composition) HasDirect() bool`

HasDirect returns a boolean if a field has been set.

### SetDirectNil

`func (o *Composition) SetDirectNil(b bool)`

 SetDirectNil sets the value for Direct to be an explicit nil

### UnsetDirect
`func (o *Composition) UnsetDirect()`

UnsetDirect ensures that no value is present for Direct, not even an explicit nil
### GetLastEditedBy

`func (o *Composition) GetLastEditedBy() CompositionLastEditedBy`

GetLastEditedBy returns the LastEditedBy field if non-nil, zero value otherwise.

### GetLastEditedByOk

`func (o *Composition) GetLastEditedByOk() (*CompositionLastEditedBy, bool)`

GetLastEditedByOk returns a tuple with the LastEditedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastEditedBy

`func (o *Composition) SetLastEditedBy(v CompositionLastEditedBy)`

SetLastEditedBy sets LastEditedBy field to given value.

### HasLastEditedBy

`func (o *Composition) HasLastEditedBy() bool`

HasLastEditedBy returns a boolean if a field has been set.

### SetLastEditedByNil

`func (o *Composition) SetLastEditedByNil(b bool)`

 SetLastEditedByNil sets the value for LastEditedBy to be an explicit nil

### UnsetLastEditedBy
`func (o *Composition) UnsetLastEditedBy()`

UnsetLastEditedBy ensures that no value is present for LastEditedBy, not even an explicit nil
### GetLastEditedAt

`func (o *Composition) GetLastEditedAt() time.Time`

GetLastEditedAt returns the LastEditedAt field if non-nil, zero value otherwise.

### GetLastEditedAtOk

`func (o *Composition) GetLastEditedAtOk() (*time.Time, bool)`

GetLastEditedAtOk returns a tuple with the LastEditedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastEditedAt

`func (o *Composition) SetLastEditedAt(v time.Time)`

SetLastEditedAt sets LastEditedAt field to given value.

### HasLastEditedAt

`func (o *Composition) HasLastEditedAt() bool`

HasLastEditedAt returns a boolean if a field has been set.

### SetLastEditedAtNil

`func (o *Composition) SetLastEditedAtNil(b bool)`

 SetLastEditedAtNil sets the value for LastEditedAt to be an explicit nil

### UnsetLastEditedAt
`func (o *Composition) UnsetLastEditedAt()`

UnsetLastEditedAt ensures that no value is present for LastEditedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


