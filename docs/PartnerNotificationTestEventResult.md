# PartnerNotificationTestEventResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Delivered** | **bool** | True when your receiver answered with a 2xx status. | 
**StatusCode** | **NullableInt32** | The HTTP status your receiver answered with. Null when it did not answer (refused, unreachable or too slow). | 
**DurationMs** | **int32** | How long the call took, in milliseconds. A call is given up after ten seconds. | 
**Error** | Pointer to **string** | Why the call did not arrive, in a few words (&#x60;timeout&#x60;, &#x60;status 500&#x60;, &#x60;unreachable&#x60;, a redirect). Never what your receiver replied. Left out when it arrived. | [optional] 

## Methods

### NewPartnerNotificationTestEventResult

`func NewPartnerNotificationTestEventResult(delivered bool, statusCode NullableInt32, durationMs int32, ) *PartnerNotificationTestEventResult`

NewPartnerNotificationTestEventResult instantiates a new PartnerNotificationTestEventResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerNotificationTestEventResultWithDefaults

`func NewPartnerNotificationTestEventResultWithDefaults() *PartnerNotificationTestEventResult`

NewPartnerNotificationTestEventResultWithDefaults instantiates a new PartnerNotificationTestEventResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDelivered

`func (o *PartnerNotificationTestEventResult) GetDelivered() bool`

GetDelivered returns the Delivered field if non-nil, zero value otherwise.

### GetDeliveredOk

`func (o *PartnerNotificationTestEventResult) GetDeliveredOk() (*bool, bool)`

GetDeliveredOk returns a tuple with the Delivered field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelivered

`func (o *PartnerNotificationTestEventResult) SetDelivered(v bool)`

SetDelivered sets Delivered field to given value.


### GetStatusCode

`func (o *PartnerNotificationTestEventResult) GetStatusCode() int32`

GetStatusCode returns the StatusCode field if non-nil, zero value otherwise.

### GetStatusCodeOk

`func (o *PartnerNotificationTestEventResult) GetStatusCodeOk() (*int32, bool)`

GetStatusCodeOk returns a tuple with the StatusCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusCode

`func (o *PartnerNotificationTestEventResult) SetStatusCode(v int32)`

SetStatusCode sets StatusCode field to given value.


### SetStatusCodeNil

`func (o *PartnerNotificationTestEventResult) SetStatusCodeNil(b bool)`

 SetStatusCodeNil sets the value for StatusCode to be an explicit nil

### UnsetStatusCode
`func (o *PartnerNotificationTestEventResult) UnsetStatusCode()`

UnsetStatusCode ensures that no value is present for StatusCode, not even an explicit nil
### GetDurationMs

`func (o *PartnerNotificationTestEventResult) GetDurationMs() int32`

GetDurationMs returns the DurationMs field if non-nil, zero value otherwise.

### GetDurationMsOk

`func (o *PartnerNotificationTestEventResult) GetDurationMsOk() (*int32, bool)`

GetDurationMsOk returns a tuple with the DurationMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationMs

`func (o *PartnerNotificationTestEventResult) SetDurationMs(v int32)`

SetDurationMs sets DurationMs field to given value.


### GetError

`func (o *PartnerNotificationTestEventResult) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *PartnerNotificationTestEventResult) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *PartnerNotificationTestEventResult) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *PartnerNotificationTestEventResult) HasError() bool`

HasError returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


