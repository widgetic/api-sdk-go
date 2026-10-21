# CompositionVersion

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Unique identifier for the version | [optional] 
**CompositionId** | Pointer to **string** | ID of the associated composition | [optional] 
**Version** | Pointer to **int32** | Version number | [optional] 
**Content** | Pointer to **map[string]interface{}** | Content for this version | [optional] 
**CreatedAt** | Pointer to **time.Time** | When this version was created | [optional] 

## Methods

### NewCompositionVersion

`func NewCompositionVersion() *CompositionVersion`

NewCompositionVersion instantiates a new CompositionVersion object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompositionVersionWithDefaults

`func NewCompositionVersionWithDefaults() *CompositionVersion`

NewCompositionVersionWithDefaults instantiates a new CompositionVersion object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CompositionVersion) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CompositionVersion) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CompositionVersion) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CompositionVersion) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCompositionId

`func (o *CompositionVersion) GetCompositionId() string`

GetCompositionId returns the CompositionId field if non-nil, zero value otherwise.

### GetCompositionIdOk

`func (o *CompositionVersion) GetCompositionIdOk() (*string, bool)`

GetCompositionIdOk returns a tuple with the CompositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompositionId

`func (o *CompositionVersion) SetCompositionId(v string)`

SetCompositionId sets CompositionId field to given value.

### HasCompositionId

`func (o *CompositionVersion) HasCompositionId() bool`

HasCompositionId returns a boolean if a field has been set.

### GetVersion

`func (o *CompositionVersion) GetVersion() int32`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *CompositionVersion) GetVersionOk() (*int32, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *CompositionVersion) SetVersion(v int32)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *CompositionVersion) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### GetContent

`func (o *CompositionVersion) GetContent() map[string]interface{}`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *CompositionVersion) GetContentOk() (*map[string]interface{}, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *CompositionVersion) SetContent(v map[string]interface{})`

SetContent sets Content field to given value.

### HasContent

`func (o *CompositionVersion) HasContent() bool`

HasContent returns a boolean if a field has been set.

### GetCreatedAt

`func (o *CompositionVersion) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CompositionVersion) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CompositionVersion) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *CompositionVersion) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


