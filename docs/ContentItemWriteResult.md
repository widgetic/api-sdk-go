# ContentItemWriteResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | Pointer to **bool** | Repeats the envelope&#39;s &#x60;success&#x60;. | [optional] 
**ContentVersion** | Pointer to **int32** | The content&#39;s version after the write. Send it as &#x60;If-Match&#x60; on the next write to refuse a stale one. | [optional] 
**ValidationResult** | Pointer to [**ContentItemWriteResultValidationResult**](ContentItemWriteResultValidationResult.md) |  | [optional] 
**CompositionUpdated** | Pointer to **bool** |  | [optional] 
**RealtimeUpdateSent** | Pointer to **bool** | Whether the open frames were told to reload the content. | [optional] 
**Item** | Pointer to **map[string]interface{}** | The item as stored, with the &#x60;id&#x60; the list gave it. | [optional] 

## Methods

### NewContentItemWriteResult

`func NewContentItemWriteResult() *ContentItemWriteResult`

NewContentItemWriteResult instantiates a new ContentItemWriteResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContentItemWriteResultWithDefaults

`func NewContentItemWriteResultWithDefaults() *ContentItemWriteResult`

NewContentItemWriteResultWithDefaults instantiates a new ContentItemWriteResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *ContentItemWriteResult) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ContentItemWriteResult) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ContentItemWriteResult) SetSuccess(v bool)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *ContentItemWriteResult) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### GetContentVersion

`func (o *ContentItemWriteResult) GetContentVersion() int32`

GetContentVersion returns the ContentVersion field if non-nil, zero value otherwise.

### GetContentVersionOk

`func (o *ContentItemWriteResult) GetContentVersionOk() (*int32, bool)`

GetContentVersionOk returns a tuple with the ContentVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentVersion

`func (o *ContentItemWriteResult) SetContentVersion(v int32)`

SetContentVersion sets ContentVersion field to given value.

### HasContentVersion

`func (o *ContentItemWriteResult) HasContentVersion() bool`

HasContentVersion returns a boolean if a field has been set.

### GetValidationResult

`func (o *ContentItemWriteResult) GetValidationResult() ContentItemWriteResultValidationResult`

GetValidationResult returns the ValidationResult field if non-nil, zero value otherwise.

### GetValidationResultOk

`func (o *ContentItemWriteResult) GetValidationResultOk() (*ContentItemWriteResultValidationResult, bool)`

GetValidationResultOk returns a tuple with the ValidationResult field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidationResult

`func (o *ContentItemWriteResult) SetValidationResult(v ContentItemWriteResultValidationResult)`

SetValidationResult sets ValidationResult field to given value.

### HasValidationResult

`func (o *ContentItemWriteResult) HasValidationResult() bool`

HasValidationResult returns a boolean if a field has been set.

### GetCompositionUpdated

`func (o *ContentItemWriteResult) GetCompositionUpdated() bool`

GetCompositionUpdated returns the CompositionUpdated field if non-nil, zero value otherwise.

### GetCompositionUpdatedOk

`func (o *ContentItemWriteResult) GetCompositionUpdatedOk() (*bool, bool)`

GetCompositionUpdatedOk returns a tuple with the CompositionUpdated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompositionUpdated

`func (o *ContentItemWriteResult) SetCompositionUpdated(v bool)`

SetCompositionUpdated sets CompositionUpdated field to given value.

### HasCompositionUpdated

`func (o *ContentItemWriteResult) HasCompositionUpdated() bool`

HasCompositionUpdated returns a boolean if a field has been set.

### GetRealtimeUpdateSent

`func (o *ContentItemWriteResult) GetRealtimeUpdateSent() bool`

GetRealtimeUpdateSent returns the RealtimeUpdateSent field if non-nil, zero value otherwise.

### GetRealtimeUpdateSentOk

`func (o *ContentItemWriteResult) GetRealtimeUpdateSentOk() (*bool, bool)`

GetRealtimeUpdateSentOk returns a tuple with the RealtimeUpdateSent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRealtimeUpdateSent

`func (o *ContentItemWriteResult) SetRealtimeUpdateSent(v bool)`

SetRealtimeUpdateSent sets RealtimeUpdateSent field to given value.

### HasRealtimeUpdateSent

`func (o *ContentItemWriteResult) HasRealtimeUpdateSent() bool`

HasRealtimeUpdateSent returns a boolean if a field has been set.

### GetItem

`func (o *ContentItemWriteResult) GetItem() map[string]interface{}`

GetItem returns the Item field if non-nil, zero value otherwise.

### GetItemOk

`func (o *ContentItemWriteResult) GetItemOk() (*map[string]interface{}, bool)`

GetItemOk returns a tuple with the Item field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItem

`func (o *ContentItemWriteResult) SetItem(v map[string]interface{})`

SetItem sets Item field to given value.

### HasItem

`func (o *ContentItemWriteResult) HasItem() bool`

HasItem returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


