# PublicWorkflowEventsAccepted

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Recorded** | **bool** | False when nothing was counted or kept (the workflow is not live any more, or the ids are not in that version). | 
**Counters** | Pointer to **int32** | How many counters were raised (0 for a report of heights alone). | [optional] 
**Reason** | Pointer to **string** | Why nothing was counted or kept, when &#x60;recorded&#x60; is false. | [optional] 

## Methods

### NewPublicWorkflowEventsAccepted

`func NewPublicWorkflowEventsAccepted(recorded bool, ) *PublicWorkflowEventsAccepted`

NewPublicWorkflowEventsAccepted instantiates a new PublicWorkflowEventsAccepted object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublicWorkflowEventsAcceptedWithDefaults

`func NewPublicWorkflowEventsAcceptedWithDefaults() *PublicWorkflowEventsAccepted`

NewPublicWorkflowEventsAcceptedWithDefaults instantiates a new PublicWorkflowEventsAccepted object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRecorded

`func (o *PublicWorkflowEventsAccepted) GetRecorded() bool`

GetRecorded returns the Recorded field if non-nil, zero value otherwise.

### GetRecordedOk

`func (o *PublicWorkflowEventsAccepted) GetRecordedOk() (*bool, bool)`

GetRecordedOk returns a tuple with the Recorded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecorded

`func (o *PublicWorkflowEventsAccepted) SetRecorded(v bool)`

SetRecorded sets Recorded field to given value.


### GetCounters

`func (o *PublicWorkflowEventsAccepted) GetCounters() int32`

GetCounters returns the Counters field if non-nil, zero value otherwise.

### GetCountersOk

`func (o *PublicWorkflowEventsAccepted) GetCountersOk() (*int32, bool)`

GetCountersOk returns a tuple with the Counters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCounters

`func (o *PublicWorkflowEventsAccepted) SetCounters(v int32)`

SetCounters sets Counters field to given value.

### HasCounters

`func (o *PublicWorkflowEventsAccepted) HasCounters() bool`

HasCounters returns a boolean if a field has been set.

### GetReason

`func (o *PublicWorkflowEventsAccepted) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *PublicWorkflowEventsAccepted) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *PublicWorkflowEventsAccepted) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *PublicWorkflowEventsAccepted) HasReason() bool`

HasReason returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


