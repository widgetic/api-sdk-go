# UpdateCanvasRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PersistenceKey** | Pointer to **string** | Updated key used for persistent storage and reference | [optional] 
**CanvasContent** | Pointer to **map[string]interface{}** | Updated JSON content of the canvas | [optional] 
**PrimaryWidgetId** | Pointer to **NullableString** | Primary widget for list/deep-link; omit to leave unchanged | [optional] 

## Methods

### NewUpdateCanvasRequest

`func NewUpdateCanvasRequest() *UpdateCanvasRequest`

NewUpdateCanvasRequest instantiates a new UpdateCanvasRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateCanvasRequestWithDefaults

`func NewUpdateCanvasRequestWithDefaults() *UpdateCanvasRequest`

NewUpdateCanvasRequestWithDefaults instantiates a new UpdateCanvasRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPersistenceKey

`func (o *UpdateCanvasRequest) GetPersistenceKey() string`

GetPersistenceKey returns the PersistenceKey field if non-nil, zero value otherwise.

### GetPersistenceKeyOk

`func (o *UpdateCanvasRequest) GetPersistenceKeyOk() (*string, bool)`

GetPersistenceKeyOk returns a tuple with the PersistenceKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersistenceKey

`func (o *UpdateCanvasRequest) SetPersistenceKey(v string)`

SetPersistenceKey sets PersistenceKey field to given value.

### HasPersistenceKey

`func (o *UpdateCanvasRequest) HasPersistenceKey() bool`

HasPersistenceKey returns a boolean if a field has been set.

### GetCanvasContent

`func (o *UpdateCanvasRequest) GetCanvasContent() map[string]interface{}`

GetCanvasContent returns the CanvasContent field if non-nil, zero value otherwise.

### GetCanvasContentOk

`func (o *UpdateCanvasRequest) GetCanvasContentOk() (*map[string]interface{}, bool)`

GetCanvasContentOk returns a tuple with the CanvasContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanvasContent

`func (o *UpdateCanvasRequest) SetCanvasContent(v map[string]interface{})`

SetCanvasContent sets CanvasContent field to given value.

### HasCanvasContent

`func (o *UpdateCanvasRequest) HasCanvasContent() bool`

HasCanvasContent returns a boolean if a field has been set.

### GetPrimaryWidgetId

`func (o *UpdateCanvasRequest) GetPrimaryWidgetId() string`

GetPrimaryWidgetId returns the PrimaryWidgetId field if non-nil, zero value otherwise.

### GetPrimaryWidgetIdOk

`func (o *UpdateCanvasRequest) GetPrimaryWidgetIdOk() (*string, bool)`

GetPrimaryWidgetIdOk returns a tuple with the PrimaryWidgetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryWidgetId

`func (o *UpdateCanvasRequest) SetPrimaryWidgetId(v string)`

SetPrimaryWidgetId sets PrimaryWidgetId field to given value.

### HasPrimaryWidgetId

`func (o *UpdateCanvasRequest) HasPrimaryWidgetId() bool`

HasPrimaryWidgetId returns a boolean if a field has been set.

### SetPrimaryWidgetIdNil

`func (o *UpdateCanvasRequest) SetPrimaryWidgetIdNil(b bool)`

 SetPrimaryWidgetIdNil sets the value for PrimaryWidgetId to be an explicit nil

### UnsetPrimaryWidgetId
`func (o *UpdateCanvasRequest) UnsetPrimaryWidgetId()`

UnsetPrimaryWidgetId ensures that no value is present for PrimaryWidgetId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


