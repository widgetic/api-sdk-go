# PublicEmbedFailure

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Message** | **string** | What happened, for a person. | 
**Code** | **string** | The short code a page branches on: &#x60;DOMAIN_NOT_ALLOWED&#x60;, &#x60;UNPUBLISHED&#x60;, &#x60;SUSPENDED&#x60;, &#x60;NOT_FOUND&#x60;, &#x60;RATE_LIMITED&#x60;, and for the entry route the codes listed with its answers. | 
**Details** | Pointer to [**PublicEmbedFailureDetails**](PublicEmbedFailureDetails.md) |  | [optional] 
**CorrelationId** | Pointer to **string** | The id of the request, for the routes that carry it. | [optional] 
**Error** | [**PublicEmbedFailureError**](PublicEmbedFailureError.md) |  | 

## Methods

### NewPublicEmbedFailure

`func NewPublicEmbedFailure(success bool, message string, code string, error_ PublicEmbedFailureError, ) *PublicEmbedFailure`

NewPublicEmbedFailure instantiates a new PublicEmbedFailure object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublicEmbedFailureWithDefaults

`func NewPublicEmbedFailureWithDefaults() *PublicEmbedFailure`

NewPublicEmbedFailureWithDefaults instantiates a new PublicEmbedFailure object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *PublicEmbedFailure) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *PublicEmbedFailure) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *PublicEmbedFailure) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetMessage

`func (o *PublicEmbedFailure) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *PublicEmbedFailure) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *PublicEmbedFailure) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetCode

`func (o *PublicEmbedFailure) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *PublicEmbedFailure) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *PublicEmbedFailure) SetCode(v string)`

SetCode sets Code field to given value.


### GetDetails

`func (o *PublicEmbedFailure) GetDetails() PublicEmbedFailureDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *PublicEmbedFailure) GetDetailsOk() (*PublicEmbedFailureDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *PublicEmbedFailure) SetDetails(v PublicEmbedFailureDetails)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *PublicEmbedFailure) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### GetCorrelationId

`func (o *PublicEmbedFailure) GetCorrelationId() string`

GetCorrelationId returns the CorrelationId field if non-nil, zero value otherwise.

### GetCorrelationIdOk

`func (o *PublicEmbedFailure) GetCorrelationIdOk() (*string, bool)`

GetCorrelationIdOk returns a tuple with the CorrelationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelationId

`func (o *PublicEmbedFailure) SetCorrelationId(v string)`

SetCorrelationId sets CorrelationId field to given value.

### HasCorrelationId

`func (o *PublicEmbedFailure) HasCorrelationId() bool`

HasCorrelationId returns a boolean if a field has been set.

### GetError

`func (o *PublicEmbedFailure) GetError() PublicEmbedFailureError`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *PublicEmbedFailure) GetErrorOk() (*PublicEmbedFailureError, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *PublicEmbedFailure) SetError(v PublicEmbedFailureError)`

SetError sets Error field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


