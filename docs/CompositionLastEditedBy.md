# CompositionLastEditedBy

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The account that made the latest change | [optional] 
**Name** | Pointer to **NullableString** | The name on that account, or &#x60;null&#x60; when it has none or it could not be read just then. Never an email address. | [optional] 

## Methods

### NewCompositionLastEditedBy

`func NewCompositionLastEditedBy() *CompositionLastEditedBy`

NewCompositionLastEditedBy instantiates a new CompositionLastEditedBy object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompositionLastEditedByWithDefaults

`func NewCompositionLastEditedByWithDefaults() *CompositionLastEditedBy`

NewCompositionLastEditedByWithDefaults instantiates a new CompositionLastEditedBy object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CompositionLastEditedBy) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CompositionLastEditedBy) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CompositionLastEditedBy) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CompositionLastEditedBy) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *CompositionLastEditedBy) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CompositionLastEditedBy) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CompositionLastEditedBy) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CompositionLastEditedBy) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *CompositionLastEditedBy) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *CompositionLastEditedBy) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


