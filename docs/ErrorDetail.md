# ErrorDetail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | **string** | Machine-readable error code. | 
**Message** | **string** | Human-readable explanation. | 
**Param** | Pointer to **string** | The field that caused the error, when one did. | [optional] 
**DocUrl** | Pointer to **string** | Where this error is explained. | [optional] 
**SuggestedAction** | Pointer to **string** | What to do about it. | [optional] 
**RetryAfter** | Pointer to **int32** | Seconds to wait before trying again (rate limits). The same number is in the &#x60;Retry-After&#x60; header. | [optional] 
**Details** | Pointer to **map[string]interface{}** | More about the error: the fields that failed, a limit that was reached. | [optional] 
**CorrelationId** | Pointer to **string** | Quote this when you ask support about the call. | [optional] 
**Timestamp** | **time.Time** |  | 

## Methods

### NewErrorDetail

`func NewErrorDetail(code string, message string, timestamp time.Time, ) *ErrorDetail`

NewErrorDetail instantiates a new ErrorDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewErrorDetailWithDefaults

`func NewErrorDetailWithDefaults() *ErrorDetail`

NewErrorDetailWithDefaults instantiates a new ErrorDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *ErrorDetail) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *ErrorDetail) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *ErrorDetail) SetCode(v string)`

SetCode sets Code field to given value.


### GetMessage

`func (o *ErrorDetail) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *ErrorDetail) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *ErrorDetail) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetParam

`func (o *ErrorDetail) GetParam() string`

GetParam returns the Param field if non-nil, zero value otherwise.

### GetParamOk

`func (o *ErrorDetail) GetParamOk() (*string, bool)`

GetParamOk returns a tuple with the Param field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParam

`func (o *ErrorDetail) SetParam(v string)`

SetParam sets Param field to given value.

### HasParam

`func (o *ErrorDetail) HasParam() bool`

HasParam returns a boolean if a field has been set.

### GetDocUrl

`func (o *ErrorDetail) GetDocUrl() string`

GetDocUrl returns the DocUrl field if non-nil, zero value otherwise.

### GetDocUrlOk

`func (o *ErrorDetail) GetDocUrlOk() (*string, bool)`

GetDocUrlOk returns a tuple with the DocUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocUrl

`func (o *ErrorDetail) SetDocUrl(v string)`

SetDocUrl sets DocUrl field to given value.

### HasDocUrl

`func (o *ErrorDetail) HasDocUrl() bool`

HasDocUrl returns a boolean if a field has been set.

### GetSuggestedAction

`func (o *ErrorDetail) GetSuggestedAction() string`

GetSuggestedAction returns the SuggestedAction field if non-nil, zero value otherwise.

### GetSuggestedActionOk

`func (o *ErrorDetail) GetSuggestedActionOk() (*string, bool)`

GetSuggestedActionOk returns a tuple with the SuggestedAction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuggestedAction

`func (o *ErrorDetail) SetSuggestedAction(v string)`

SetSuggestedAction sets SuggestedAction field to given value.

### HasSuggestedAction

`func (o *ErrorDetail) HasSuggestedAction() bool`

HasSuggestedAction returns a boolean if a field has been set.

### GetRetryAfter

`func (o *ErrorDetail) GetRetryAfter() int32`

GetRetryAfter returns the RetryAfter field if non-nil, zero value otherwise.

### GetRetryAfterOk

`func (o *ErrorDetail) GetRetryAfterOk() (*int32, bool)`

GetRetryAfterOk returns a tuple with the RetryAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetryAfter

`func (o *ErrorDetail) SetRetryAfter(v int32)`

SetRetryAfter sets RetryAfter field to given value.

### HasRetryAfter

`func (o *ErrorDetail) HasRetryAfter() bool`

HasRetryAfter returns a boolean if a field has been set.

### GetDetails

`func (o *ErrorDetail) GetDetails() map[string]interface{}`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *ErrorDetail) GetDetailsOk() (*map[string]interface{}, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *ErrorDetail) SetDetails(v map[string]interface{})`

SetDetails sets Details field to given value.

### HasDetails

`func (o *ErrorDetail) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### GetCorrelationId

`func (o *ErrorDetail) GetCorrelationId() string`

GetCorrelationId returns the CorrelationId field if non-nil, zero value otherwise.

### GetCorrelationIdOk

`func (o *ErrorDetail) GetCorrelationIdOk() (*string, bool)`

GetCorrelationIdOk returns a tuple with the CorrelationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelationId

`func (o *ErrorDetail) SetCorrelationId(v string)`

SetCorrelationId sets CorrelationId field to given value.

### HasCorrelationId

`func (o *ErrorDetail) HasCorrelationId() bool`

HasCorrelationId returns a boolean if a field has been set.

### GetTimestamp

`func (o *ErrorDetail) GetTimestamp() time.Time`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *ErrorDetail) GetTimestampOk() (*time.Time, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *ErrorDetail) SetTimestamp(v time.Time)`

SetTimestamp sets Timestamp field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


