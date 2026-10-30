# PublicWorkflowEventsRequestHeightsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CompositionId** | **string** | The composition the step shows. | 
**Height** | **int32** | The height the step settled at, in pixels. One under 100 is not kept, one over 2000 is kept as 2000. | 

## Methods

### NewPublicWorkflowEventsRequestHeightsInner

`func NewPublicWorkflowEventsRequestHeightsInner(compositionId string, height int32, ) *PublicWorkflowEventsRequestHeightsInner`

NewPublicWorkflowEventsRequestHeightsInner instantiates a new PublicWorkflowEventsRequestHeightsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublicWorkflowEventsRequestHeightsInnerWithDefaults

`func NewPublicWorkflowEventsRequestHeightsInnerWithDefaults() *PublicWorkflowEventsRequestHeightsInner`

NewPublicWorkflowEventsRequestHeightsInnerWithDefaults instantiates a new PublicWorkflowEventsRequestHeightsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompositionId

`func (o *PublicWorkflowEventsRequestHeightsInner) GetCompositionId() string`

GetCompositionId returns the CompositionId field if non-nil, zero value otherwise.

### GetCompositionIdOk

`func (o *PublicWorkflowEventsRequestHeightsInner) GetCompositionIdOk() (*string, bool)`

GetCompositionIdOk returns a tuple with the CompositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompositionId

`func (o *PublicWorkflowEventsRequestHeightsInner) SetCompositionId(v string)`

SetCompositionId sets CompositionId field to given value.


### GetHeight

`func (o *PublicWorkflowEventsRequestHeightsInner) GetHeight() int32`

GetHeight returns the Height field if non-nil, zero value otherwise.

### GetHeightOk

`func (o *PublicWorkflowEventsRequestHeightsInner) GetHeightOk() (*int32, bool)`

GetHeightOk returns a tuple with the Height field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeight

`func (o *PublicWorkflowEventsRequestHeightsInner) SetHeight(v int32)`

SetHeight sets Height field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


