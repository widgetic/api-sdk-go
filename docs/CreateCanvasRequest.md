# CreateCanvasRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PersistenceKey** | **string** | Key used for persistent storage and reference | 
**CanvasContent** | Pointer to **map[string]interface{}** | JSON content of the canvas, containing layout and configuration | [optional] 
**PrimaryWidgetId** | Pointer to **NullableString** | Optional primary widget id (usually set after widget create) | [optional] 
**ManagedUserId** | Pointer to **NullableString** | Make the canvas for this managed user (Widgetic&#39;s id for the user). Send this or &#x60;managedUserExternalId&#x60;, not both. The tag is set here and does not change afterwards. | [optional] 
**ManagedUserExternalId** | Pointer to **NullableString** | Make the canvas for the managed user you registered with this &#x60;externalId&#x60; (your own identifier for the user). Send this or &#x60;managedUserId&#x60;, not both. | [optional] 
**ProjectId** | Pointer to **NullableString** | Project this canvas belongs to. Empty canvases show on that project&#39;s list. | [optional] 

## Methods

### NewCreateCanvasRequest

`func NewCreateCanvasRequest(persistenceKey string, ) *CreateCanvasRequest`

NewCreateCanvasRequest instantiates a new CreateCanvasRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateCanvasRequestWithDefaults

`func NewCreateCanvasRequestWithDefaults() *CreateCanvasRequest`

NewCreateCanvasRequestWithDefaults instantiates a new CreateCanvasRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPersistenceKey

`func (o *CreateCanvasRequest) GetPersistenceKey() string`

GetPersistenceKey returns the PersistenceKey field if non-nil, zero value otherwise.

### GetPersistenceKeyOk

`func (o *CreateCanvasRequest) GetPersistenceKeyOk() (*string, bool)`

GetPersistenceKeyOk returns a tuple with the PersistenceKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersistenceKey

`func (o *CreateCanvasRequest) SetPersistenceKey(v string)`

SetPersistenceKey sets PersistenceKey field to given value.


### GetCanvasContent

`func (o *CreateCanvasRequest) GetCanvasContent() map[string]interface{}`

GetCanvasContent returns the CanvasContent field if non-nil, zero value otherwise.

### GetCanvasContentOk

`func (o *CreateCanvasRequest) GetCanvasContentOk() (*map[string]interface{}, bool)`

GetCanvasContentOk returns a tuple with the CanvasContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanvasContent

`func (o *CreateCanvasRequest) SetCanvasContent(v map[string]interface{})`

SetCanvasContent sets CanvasContent field to given value.

### HasCanvasContent

`func (o *CreateCanvasRequest) HasCanvasContent() bool`

HasCanvasContent returns a boolean if a field has been set.

### GetPrimaryWidgetId

`func (o *CreateCanvasRequest) GetPrimaryWidgetId() string`

GetPrimaryWidgetId returns the PrimaryWidgetId field if non-nil, zero value otherwise.

### GetPrimaryWidgetIdOk

`func (o *CreateCanvasRequest) GetPrimaryWidgetIdOk() (*string, bool)`

GetPrimaryWidgetIdOk returns a tuple with the PrimaryWidgetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryWidgetId

`func (o *CreateCanvasRequest) SetPrimaryWidgetId(v string)`

SetPrimaryWidgetId sets PrimaryWidgetId field to given value.

### HasPrimaryWidgetId

`func (o *CreateCanvasRequest) HasPrimaryWidgetId() bool`

HasPrimaryWidgetId returns a boolean if a field has been set.

### SetPrimaryWidgetIdNil

`func (o *CreateCanvasRequest) SetPrimaryWidgetIdNil(b bool)`

 SetPrimaryWidgetIdNil sets the value for PrimaryWidgetId to be an explicit nil

### UnsetPrimaryWidgetId
`func (o *CreateCanvasRequest) UnsetPrimaryWidgetId()`

UnsetPrimaryWidgetId ensures that no value is present for PrimaryWidgetId, not even an explicit nil
### GetManagedUserId

`func (o *CreateCanvasRequest) GetManagedUserId() string`

GetManagedUserId returns the ManagedUserId field if non-nil, zero value otherwise.

### GetManagedUserIdOk

`func (o *CreateCanvasRequest) GetManagedUserIdOk() (*string, bool)`

GetManagedUserIdOk returns a tuple with the ManagedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUserId

`func (o *CreateCanvasRequest) SetManagedUserId(v string)`

SetManagedUserId sets ManagedUserId field to given value.

### HasManagedUserId

`func (o *CreateCanvasRequest) HasManagedUserId() bool`

HasManagedUserId returns a boolean if a field has been set.

### SetManagedUserIdNil

`func (o *CreateCanvasRequest) SetManagedUserIdNil(b bool)`

 SetManagedUserIdNil sets the value for ManagedUserId to be an explicit nil

### UnsetManagedUserId
`func (o *CreateCanvasRequest) UnsetManagedUserId()`

UnsetManagedUserId ensures that no value is present for ManagedUserId, not even an explicit nil
### GetManagedUserExternalId

`func (o *CreateCanvasRequest) GetManagedUserExternalId() string`

GetManagedUserExternalId returns the ManagedUserExternalId field if non-nil, zero value otherwise.

### GetManagedUserExternalIdOk

`func (o *CreateCanvasRequest) GetManagedUserExternalIdOk() (*string, bool)`

GetManagedUserExternalIdOk returns a tuple with the ManagedUserExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUserExternalId

`func (o *CreateCanvasRequest) SetManagedUserExternalId(v string)`

SetManagedUserExternalId sets ManagedUserExternalId field to given value.

### HasManagedUserExternalId

`func (o *CreateCanvasRequest) HasManagedUserExternalId() bool`

HasManagedUserExternalId returns a boolean if a field has been set.

### SetManagedUserExternalIdNil

`func (o *CreateCanvasRequest) SetManagedUserExternalIdNil(b bool)`

 SetManagedUserExternalIdNil sets the value for ManagedUserExternalId to be an explicit nil

### UnsetManagedUserExternalId
`func (o *CreateCanvasRequest) UnsetManagedUserExternalId()`

UnsetManagedUserExternalId ensures that no value is present for ManagedUserExternalId, not even an explicit nil
### GetProjectId

`func (o *CreateCanvasRequest) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CreateCanvasRequest) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CreateCanvasRequest) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *CreateCanvasRequest) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### SetProjectIdNil

`func (o *CreateCanvasRequest) SetProjectIdNil(b bool)`

 SetProjectIdNil sets the value for ProjectId to be an explicit nil

### UnsetProjectId
`func (o *CreateCanvasRequest) UnsetProjectId()`

UnsetProjectId ensures that no value is present for ProjectId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


