# SetDynamicContentRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Content** | **map[string]interface{}** | Content data to set | 
**Validate** | Pointer to **bool** | Whether to validate content against widget schema | [optional] [default to true]
**Partial** | Pointer to **bool** | Whether to merge with existing content (true) or replace entirely (false) | [optional] [default to false]
**Version** | Pointer to **string** | Optional version identifier for the content | [optional] 
**Source** | Pointer to **string** | Source of the update for tracking purposes | [optional] 

## Methods

### NewSetDynamicContentRequest

`func NewSetDynamicContentRequest(content map[string]interface{}, ) *SetDynamicContentRequest`

NewSetDynamicContentRequest instantiates a new SetDynamicContentRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSetDynamicContentRequestWithDefaults

`func NewSetDynamicContentRequestWithDefaults() *SetDynamicContentRequest`

NewSetDynamicContentRequestWithDefaults instantiates a new SetDynamicContentRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContent

`func (o *SetDynamicContentRequest) GetContent() map[string]interface{}`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *SetDynamicContentRequest) GetContentOk() (*map[string]interface{}, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *SetDynamicContentRequest) SetContent(v map[string]interface{})`

SetContent sets Content field to given value.


### GetValidate

`func (o *SetDynamicContentRequest) GetValidate() bool`

GetValidate returns the Validate field if non-nil, zero value otherwise.

### GetValidateOk

`func (o *SetDynamicContentRequest) GetValidateOk() (*bool, bool)`

GetValidateOk returns a tuple with the Validate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidate

`func (o *SetDynamicContentRequest) SetValidate(v bool)`

SetValidate sets Validate field to given value.

### HasValidate

`func (o *SetDynamicContentRequest) HasValidate() bool`

HasValidate returns a boolean if a field has been set.

### GetPartial

`func (o *SetDynamicContentRequest) GetPartial() bool`

GetPartial returns the Partial field if non-nil, zero value otherwise.

### GetPartialOk

`func (o *SetDynamicContentRequest) GetPartialOk() (*bool, bool)`

GetPartialOk returns a tuple with the Partial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartial

`func (o *SetDynamicContentRequest) SetPartial(v bool)`

SetPartial sets Partial field to given value.

### HasPartial

`func (o *SetDynamicContentRequest) HasPartial() bool`

HasPartial returns a boolean if a field has been set.

### GetVersion

`func (o *SetDynamicContentRequest) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *SetDynamicContentRequest) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *SetDynamicContentRequest) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *SetDynamicContentRequest) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### GetSource

`func (o *SetDynamicContentRequest) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *SetDynamicContentRequest) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *SetDynamicContentRequest) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *SetDynamicContentRequest) HasSource() bool`

HasSource returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


