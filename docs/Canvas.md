# Canvas

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Unique identifier for the canvas | 
**PersistenceKey** | **string** | Key used for persistent storage and reference | 
**CanvasContent** | Pointer to **map[string]interface{}** | JSON content of the canvas, containing layout and configuration | [optional] 
**CreatorId** | Pointer to **string** | UUID of the user who created the canvas | [optional] 
**PrimaryWidgetId** | Pointer to **NullableString** | Primary widget for My widgets list and canvas-only deep-link (Convert per shape may add secondary widgets on the same canvas) | [optional] 
**ManagedUserId** | Pointer to **NullableString** | The managed user the canvas was made for (Widgetic&#39;s id for the user); null for a canvas that is the account&#39;s own. | [optional] 
**CreatedAt** | **time.Time** | Timestamp when the canvas was created | 
**UpdatedAt** | **time.Time** | Timestamp when the canvas was last updated | 

## Methods

### NewCanvas

`func NewCanvas(id string, persistenceKey string, createdAt time.Time, updatedAt time.Time, ) *Canvas`

NewCanvas instantiates a new Canvas object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCanvasWithDefaults

`func NewCanvasWithDefaults() *Canvas`

NewCanvasWithDefaults instantiates a new Canvas object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Canvas) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Canvas) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Canvas) SetId(v string)`

SetId sets Id field to given value.


### GetPersistenceKey

`func (o *Canvas) GetPersistenceKey() string`

GetPersistenceKey returns the PersistenceKey field if non-nil, zero value otherwise.

### GetPersistenceKeyOk

`func (o *Canvas) GetPersistenceKeyOk() (*string, bool)`

GetPersistenceKeyOk returns a tuple with the PersistenceKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersistenceKey

`func (o *Canvas) SetPersistenceKey(v string)`

SetPersistenceKey sets PersistenceKey field to given value.


### GetCanvasContent

`func (o *Canvas) GetCanvasContent() map[string]interface{}`

GetCanvasContent returns the CanvasContent field if non-nil, zero value otherwise.

### GetCanvasContentOk

`func (o *Canvas) GetCanvasContentOk() (*map[string]interface{}, bool)`

GetCanvasContentOk returns a tuple with the CanvasContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanvasContent

`func (o *Canvas) SetCanvasContent(v map[string]interface{})`

SetCanvasContent sets CanvasContent field to given value.

### HasCanvasContent

`func (o *Canvas) HasCanvasContent() bool`

HasCanvasContent returns a boolean if a field has been set.

### GetCreatorId

`func (o *Canvas) GetCreatorId() string`

GetCreatorId returns the CreatorId field if non-nil, zero value otherwise.

### GetCreatorIdOk

`func (o *Canvas) GetCreatorIdOk() (*string, bool)`

GetCreatorIdOk returns a tuple with the CreatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatorId

`func (o *Canvas) SetCreatorId(v string)`

SetCreatorId sets CreatorId field to given value.

### HasCreatorId

`func (o *Canvas) HasCreatorId() bool`

HasCreatorId returns a boolean if a field has been set.

### GetPrimaryWidgetId

`func (o *Canvas) GetPrimaryWidgetId() string`

GetPrimaryWidgetId returns the PrimaryWidgetId field if non-nil, zero value otherwise.

### GetPrimaryWidgetIdOk

`func (o *Canvas) GetPrimaryWidgetIdOk() (*string, bool)`

GetPrimaryWidgetIdOk returns a tuple with the PrimaryWidgetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryWidgetId

`func (o *Canvas) SetPrimaryWidgetId(v string)`

SetPrimaryWidgetId sets PrimaryWidgetId field to given value.

### HasPrimaryWidgetId

`func (o *Canvas) HasPrimaryWidgetId() bool`

HasPrimaryWidgetId returns a boolean if a field has been set.

### SetPrimaryWidgetIdNil

`func (o *Canvas) SetPrimaryWidgetIdNil(b bool)`

 SetPrimaryWidgetIdNil sets the value for PrimaryWidgetId to be an explicit nil

### UnsetPrimaryWidgetId
`func (o *Canvas) UnsetPrimaryWidgetId()`

UnsetPrimaryWidgetId ensures that no value is present for PrimaryWidgetId, not even an explicit nil
### GetManagedUserId

`func (o *Canvas) GetManagedUserId() string`

GetManagedUserId returns the ManagedUserId field if non-nil, zero value otherwise.

### GetManagedUserIdOk

`func (o *Canvas) GetManagedUserIdOk() (*string, bool)`

GetManagedUserIdOk returns a tuple with the ManagedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUserId

`func (o *Canvas) SetManagedUserId(v string)`

SetManagedUserId sets ManagedUserId field to given value.

### HasManagedUserId

`func (o *Canvas) HasManagedUserId() bool`

HasManagedUserId returns a boolean if a field has been set.

### SetManagedUserIdNil

`func (o *Canvas) SetManagedUserIdNil(b bool)`

 SetManagedUserIdNil sets the value for ManagedUserId to be an explicit nil

### UnsetManagedUserId
`func (o *Canvas) UnsetManagedUserId()`

UnsetManagedUserId ensures that no value is present for ManagedUserId, not even an explicit nil
### GetCreatedAt

`func (o *Canvas) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Canvas) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Canvas) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *Canvas) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Canvas) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Canvas) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


