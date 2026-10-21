# UpdateComposition

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | Updated name of the composition | [optional] 
**WidgetId** | Pointer to **string** | Updated widget ID | [optional] 
**Content** | Pointer to **map[string]interface{}** | Updated content data | [optional] 
**Status** | Pointer to **string** | Updated status | [optional] 
**EmbedSettings** | Pointer to **map[string]interface{}** | Updated embed settings | [optional] 
**Design** | Pointer to **map[string]interface{}** | Updated design settings | [optional] 
**DatabaseSchema** | Pointer to **map[string]interface{}** | Tables to make for the composition, in the shape &#x60;createComposition&#x60; takes (&#x60;{ \&quot;tables\&quot;: [ ... ] }&#x60;, with the same names, types, defaults and limits). Only the tables that are missing are made. A table that already exists is never changed or dropped: it keeps its columns, so a column added to the declaration is not added to it. A declaration that cannot be used is refused with &#x60;400&#x60; and &#x60;INVALID_DATABASE_SCHEMA&#x60;. When the composition is saved but its tables cannot be made just now, &#x60;meta.warnings&#x60; says so: send the same &#x60;databaseSchema&#x60; again to retry.  | [optional] 
**ProjectId** | Pointer to **string** | Updated project ID | [optional] 

## Methods

### NewUpdateComposition

`func NewUpdateComposition() *UpdateComposition`

NewUpdateComposition instantiates a new UpdateComposition object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateCompositionWithDefaults

`func NewUpdateCompositionWithDefaults() *UpdateComposition`

NewUpdateCompositionWithDefaults instantiates a new UpdateComposition object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateComposition) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateComposition) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateComposition) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateComposition) HasName() bool`

HasName returns a boolean if a field has been set.

### GetWidgetId

`func (o *UpdateComposition) GetWidgetId() string`

GetWidgetId returns the WidgetId field if non-nil, zero value otherwise.

### GetWidgetIdOk

`func (o *UpdateComposition) GetWidgetIdOk() (*string, bool)`

GetWidgetIdOk returns a tuple with the WidgetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidgetId

`func (o *UpdateComposition) SetWidgetId(v string)`

SetWidgetId sets WidgetId field to given value.

### HasWidgetId

`func (o *UpdateComposition) HasWidgetId() bool`

HasWidgetId returns a boolean if a field has been set.

### GetContent

`func (o *UpdateComposition) GetContent() map[string]interface{}`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *UpdateComposition) GetContentOk() (*map[string]interface{}, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *UpdateComposition) SetContent(v map[string]interface{})`

SetContent sets Content field to given value.

### HasContent

`func (o *UpdateComposition) HasContent() bool`

HasContent returns a boolean if a field has been set.

### GetStatus

`func (o *UpdateComposition) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *UpdateComposition) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *UpdateComposition) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *UpdateComposition) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetEmbedSettings

`func (o *UpdateComposition) GetEmbedSettings() map[string]interface{}`

GetEmbedSettings returns the EmbedSettings field if non-nil, zero value otherwise.

### GetEmbedSettingsOk

`func (o *UpdateComposition) GetEmbedSettingsOk() (*map[string]interface{}, bool)`

GetEmbedSettingsOk returns a tuple with the EmbedSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmbedSettings

`func (o *UpdateComposition) SetEmbedSettings(v map[string]interface{})`

SetEmbedSettings sets EmbedSettings field to given value.

### HasEmbedSettings

`func (o *UpdateComposition) HasEmbedSettings() bool`

HasEmbedSettings returns a boolean if a field has been set.

### GetDesign

`func (o *UpdateComposition) GetDesign() map[string]interface{}`

GetDesign returns the Design field if non-nil, zero value otherwise.

### GetDesignOk

`func (o *UpdateComposition) GetDesignOk() (*map[string]interface{}, bool)`

GetDesignOk returns a tuple with the Design field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesign

`func (o *UpdateComposition) SetDesign(v map[string]interface{})`

SetDesign sets Design field to given value.

### HasDesign

`func (o *UpdateComposition) HasDesign() bool`

HasDesign returns a boolean if a field has been set.

### GetDatabaseSchema

`func (o *UpdateComposition) GetDatabaseSchema() map[string]interface{}`

GetDatabaseSchema returns the DatabaseSchema field if non-nil, zero value otherwise.

### GetDatabaseSchemaOk

`func (o *UpdateComposition) GetDatabaseSchemaOk() (*map[string]interface{}, bool)`

GetDatabaseSchemaOk returns a tuple with the DatabaseSchema field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatabaseSchema

`func (o *UpdateComposition) SetDatabaseSchema(v map[string]interface{})`

SetDatabaseSchema sets DatabaseSchema field to given value.

### HasDatabaseSchema

`func (o *UpdateComposition) HasDatabaseSchema() bool`

HasDatabaseSchema returns a boolean if a field has been set.

### GetProjectId

`func (o *UpdateComposition) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *UpdateComposition) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *UpdateComposition) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *UpdateComposition) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


