# PublicEmbedFailureError

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | **string** |  | 
**Message** | **string** |  | 
**Details** | Pointer to **map[string]interface{}** |  | [optional] 
**CorrelationId** | Pointer to **string** |  | [optional] 
**RetryAfter** | Pointer to **int32** | Seconds to wait before asking again, for a rate-limit refusal. | [optional] 
**Timestamp** | **time.Time** |  | 

## Methods

### NewPublicEmbedFailureError

`func NewPublicEmbedFailureError(code string, message string, timestamp time.Time, ) *PublicEmbedFailureError`

NewPublicEmbedFailureError instantiates a new PublicEmbedFailureError object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublicEmbedFailureErrorWithDefaults

`func NewPublicEmbedFailureErrorWithDefaults() *PublicEmbedFailureError`

NewPublicEmbedFailureErrorWithDefaults instantiates a new PublicEmbedFailureError object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *PublicEmbedFailureError) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *PublicEmbedFailureError) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *PublicEmbedFailureError) SetCode(v string)`

SetCode sets Code field to given value.


### GetMessage

`func (o *PublicEmbedFailureError) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *PublicEmbedFailureError) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *PublicEmbedFailureError) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetDetails

`func (o *PublicEmbedFailureError) GetDetails() map[string]interface{}`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *PublicEmbedFailureError) GetDetailsOk() (*map[string]interface{}, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *PublicEmbedFailureError) SetDetails(v map[string]interface{})`

SetDetails sets Details field to given value.

### HasDetails

`func (o *PublicEmbedFailureError) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### GetCorrelationId

`func (o *PublicEmbedFailureError) GetCorrelationId() string`

GetCorrelationId returns the CorrelationId field if non-nil, zero value otherwise.

### GetCorrelationIdOk

`func (o *PublicEmbedFailureError) GetCorrelationIdOk() (*string, bool)`

GetCorrelationIdOk returns a tuple with the CorrelationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelationId

`func (o *PublicEmbedFailureError) SetCorrelationId(v string)`

SetCorrelationId sets CorrelationId field to given value.

### HasCorrelationId

`func (o *PublicEmbedFailureError) HasCorrelationId() bool`

HasCorrelationId returns a boolean if a field has been set.

### GetRetryAfter

`func (o *PublicEmbedFailureError) GetRetryAfter() int32`

GetRetryAfter returns the RetryAfter field if non-nil, zero value otherwise.

### GetRetryAfterOk

`func (o *PublicEmbedFailureError) GetRetryAfterOk() (*int32, bool)`

GetRetryAfterOk returns a tuple with the RetryAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetryAfter

`func (o *PublicEmbedFailureError) SetRetryAfter(v int32)`

SetRetryAfter sets RetryAfter field to given value.

### HasRetryAfter

`func (o *PublicEmbedFailureError) HasRetryAfter() bool`

HasRetryAfter returns a boolean if a field has been set.

### GetTimestamp

`func (o *PublicEmbedFailureError) GetTimestamp() time.Time`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *PublicEmbedFailureError) GetTimestampOk() (*time.Time, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *PublicEmbedFailureError) SetTimestamp(v time.Time)`

SetTimestamp sets Timestamp field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


