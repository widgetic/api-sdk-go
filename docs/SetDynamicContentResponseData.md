# SetDynamicContentResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | Pointer to **bool** |  | [optional] 
**ContentVersion** | Pointer to **int32** | Monotonic content version after the write | [optional] 
**ValidationResult** | Pointer to [**SetDynamicContentResponseDataValidationResult**](SetDynamicContentResponseDataValidationResult.md) |  | [optional] 
**CompositionUpdated** | Pointer to **bool** |  | [optional] 
**RealtimeUpdateSent** | Pointer to **bool** |  | [optional] 

## Methods

### NewSetDynamicContentResponseData

`func NewSetDynamicContentResponseData() *SetDynamicContentResponseData`

NewSetDynamicContentResponseData instantiates a new SetDynamicContentResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSetDynamicContentResponseDataWithDefaults

`func NewSetDynamicContentResponseDataWithDefaults() *SetDynamicContentResponseData`

NewSetDynamicContentResponseDataWithDefaults instantiates a new SetDynamicContentResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *SetDynamicContentResponseData) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *SetDynamicContentResponseData) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *SetDynamicContentResponseData) SetSuccess(v bool)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *SetDynamicContentResponseData) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### GetContentVersion

`func (o *SetDynamicContentResponseData) GetContentVersion() int32`

GetContentVersion returns the ContentVersion field if non-nil, zero value otherwise.

### GetContentVersionOk

`func (o *SetDynamicContentResponseData) GetContentVersionOk() (*int32, bool)`

GetContentVersionOk returns a tuple with the ContentVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentVersion

`func (o *SetDynamicContentResponseData) SetContentVersion(v int32)`

SetContentVersion sets ContentVersion field to given value.

### HasContentVersion

`func (o *SetDynamicContentResponseData) HasContentVersion() bool`

HasContentVersion returns a boolean if a field has been set.

### GetValidationResult

`func (o *SetDynamicContentResponseData) GetValidationResult() SetDynamicContentResponseDataValidationResult`

GetValidationResult returns the ValidationResult field if non-nil, zero value otherwise.

### GetValidationResultOk

`func (o *SetDynamicContentResponseData) GetValidationResultOk() (*SetDynamicContentResponseDataValidationResult, bool)`

GetValidationResultOk returns a tuple with the ValidationResult field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidationResult

`func (o *SetDynamicContentResponseData) SetValidationResult(v SetDynamicContentResponseDataValidationResult)`

SetValidationResult sets ValidationResult field to given value.

### HasValidationResult

`func (o *SetDynamicContentResponseData) HasValidationResult() bool`

HasValidationResult returns a boolean if a field has been set.

### GetCompositionUpdated

`func (o *SetDynamicContentResponseData) GetCompositionUpdated() bool`

GetCompositionUpdated returns the CompositionUpdated field if non-nil, zero value otherwise.

### GetCompositionUpdatedOk

`func (o *SetDynamicContentResponseData) GetCompositionUpdatedOk() (*bool, bool)`

GetCompositionUpdatedOk returns a tuple with the CompositionUpdated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompositionUpdated

`func (o *SetDynamicContentResponseData) SetCompositionUpdated(v bool)`

SetCompositionUpdated sets CompositionUpdated field to given value.

### HasCompositionUpdated

`func (o *SetDynamicContentResponseData) HasCompositionUpdated() bool`

HasCompositionUpdated returns a boolean if a field has been set.

### GetRealtimeUpdateSent

`func (o *SetDynamicContentResponseData) GetRealtimeUpdateSent() bool`

GetRealtimeUpdateSent returns the RealtimeUpdateSent field if non-nil, zero value otherwise.

### GetRealtimeUpdateSentOk

`func (o *SetDynamicContentResponseData) GetRealtimeUpdateSentOk() (*bool, bool)`

GetRealtimeUpdateSentOk returns a tuple with the RealtimeUpdateSent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRealtimeUpdateSent

`func (o *SetDynamicContentResponseData) SetRealtimeUpdateSent(v bool)`

SetRealtimeUpdateSent sets RealtimeUpdateSent field to given value.

### HasRealtimeUpdateSent

`func (o *SetDynamicContentResponseData) HasRealtimeUpdateSent() bool`

HasRealtimeUpdateSent returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


