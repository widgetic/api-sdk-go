# PublicAdapterCallError

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Error** | **string** | A sentence a visitor may read. It never says why a feature is unavailable: not that its owner is out of credits, not what a balance is, not which limit was reached beyond the word &#x60;RATE_LIMITED&#x60; or &#x60;WIDGET_LIMIT_REACHED&#x60;. (On a 429 the standard rate-limit envelope is sent instead: &#x60;error&#x60; is then an object, and &#x60;code&#x60; beside it is the flat code.) | 
**Code** | **string** | What a module switches on. The codes of the gateway itself are &#x60;ADAPTER_BODY_INVALID&#x60;, &#x60;CAPTCHA_REQUIRED&#x60;, &#x60;ADAPTER_NOT_AVAILABLE&#x60;, &#x60;REQUEST_ALREADY_USED&#x60;, &#x60;RATE_LIMITED&#x60;, &#x60;WIDGET_LIMIT_REACHED&#x60;, &#x60;ADAPTER_FAILED&#x60;, &#x60;ADAPTER_UNAVAILABLE&#x60; and &#x60;ADAPTER_TIMEOUT&#x60;, with &#x60;ORIGIN_NOT_ALLOWED&#x60;, &#x60;PAYLOAD_TOO_LARGE&#x60;, &#x60;UNSUPPORTED_MEDIA_TYPE&#x60;, &#x60;CONTEXT_SIGNATURE_REQUIRED&#x60;, &#x60;CONTEXT_SIGNATURE_INVALID&#x60;, &#x60;CONTEXT_SIGNATURE_EXPIRED&#x60;, &#x60;CONTEXT_SIGNATURE_UNAVAILABLE&#x60; and the codes of the serving gate (&#x60;NOT_FOUND&#x60;, &#x60;UNPUBLISHED&#x60;, &#x60;SUSPENDED&#x60;) it shares with the other public embed routes. An operation may add codes of its own (capital letters and &#x60;_&#x60;) for an input it refused. | 
**CorrelationId** | Pointer to **string** | Quote it when asking for help with a call. | [optional] 

## Methods

### NewPublicAdapterCallError

`func NewPublicAdapterCallError(success bool, error_ string, code string, ) *PublicAdapterCallError`

NewPublicAdapterCallError instantiates a new PublicAdapterCallError object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublicAdapterCallErrorWithDefaults

`func NewPublicAdapterCallErrorWithDefaults() *PublicAdapterCallError`

NewPublicAdapterCallErrorWithDefaults instantiates a new PublicAdapterCallError object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *PublicAdapterCallError) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *PublicAdapterCallError) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *PublicAdapterCallError) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetError

`func (o *PublicAdapterCallError) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *PublicAdapterCallError) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *PublicAdapterCallError) SetError(v string)`

SetError sets Error field to given value.


### GetCode

`func (o *PublicAdapterCallError) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *PublicAdapterCallError) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *PublicAdapterCallError) SetCode(v string)`

SetCode sets Code field to given value.


### GetCorrelationId

`func (o *PublicAdapterCallError) GetCorrelationId() string`

GetCorrelationId returns the CorrelationId field if non-nil, zero value otherwise.

### GetCorrelationIdOk

`func (o *PublicAdapterCallError) GetCorrelationIdOk() (*string, bool)`

GetCorrelationIdOk returns a tuple with the CorrelationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCorrelationId

`func (o *PublicAdapterCallError) SetCorrelationId(v string)`

SetCorrelationId sets CorrelationId field to given value.

### HasCorrelationId

`func (o *PublicAdapterCallError) HasCorrelationId() bool`

HasCorrelationId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


