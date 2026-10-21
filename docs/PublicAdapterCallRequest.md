# PublicAdapterCallRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RequestId** | **string** | Names this attempt: 8 to 64 characters, letters, digits, &#x60;_&#x60; and &#x60;-&#x60;, the first a letter or a digit (a UUID fits). A module makes a new one for each action of the visitor. An operation that costs credits is charged once for each &#x60;requestId&#x60;, so a repeat of one that was charged and not given back is refused (409 &#x60;REQUEST_ALREADY_USED&#x60;) and does no work. | 
**Version** | Pointer to **int32** | The version of the adapter the widget&#39;s code was built against (the &#x60;vN&#x60; of its import). When it is left out, the newest version the widget&#39;s live manifest lists. | [optional] 
**Input** | Pointer to **map[string]interface{}** | What the operation is asked to do. Each operation says what it accepts and answers 400, 413 or 422 with a code of its own for what it cannot use. Defaults to an empty object. | [optional] 
**Context** | Pointer to **map[string]interface{}** | The host context the embedding page gave the widget, as the entry route takes it (see the description of &#x60;createPublicCompositionEntry&#x60;, with its **Signed context**). It is not authenticated unless the partner signs it. At most 4096 bytes of JSON, the two signature keys included. | [optional] 
**CaptchaToken** | Pointer to **NullableString** | The visitor&#39;s CAPTCHA token, for an operation that asks for one (the answer &#x60;CAPTCHA_REQUIRED&#x60; says so). | [optional] 

## Methods

### NewPublicAdapterCallRequest

`func NewPublicAdapterCallRequest(requestId string, ) *PublicAdapterCallRequest`

NewPublicAdapterCallRequest instantiates a new PublicAdapterCallRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublicAdapterCallRequestWithDefaults

`func NewPublicAdapterCallRequestWithDefaults() *PublicAdapterCallRequest`

NewPublicAdapterCallRequestWithDefaults instantiates a new PublicAdapterCallRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRequestId

`func (o *PublicAdapterCallRequest) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *PublicAdapterCallRequest) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *PublicAdapterCallRequest) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.


### GetVersion

`func (o *PublicAdapterCallRequest) GetVersion() int32`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *PublicAdapterCallRequest) GetVersionOk() (*int32, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *PublicAdapterCallRequest) SetVersion(v int32)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *PublicAdapterCallRequest) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### GetInput

`func (o *PublicAdapterCallRequest) GetInput() map[string]interface{}`

GetInput returns the Input field if non-nil, zero value otherwise.

### GetInputOk

`func (o *PublicAdapterCallRequest) GetInputOk() (*map[string]interface{}, bool)`

GetInputOk returns a tuple with the Input field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInput

`func (o *PublicAdapterCallRequest) SetInput(v map[string]interface{})`

SetInput sets Input field to given value.

### HasInput

`func (o *PublicAdapterCallRequest) HasInput() bool`

HasInput returns a boolean if a field has been set.

### GetContext

`func (o *PublicAdapterCallRequest) GetContext() map[string]interface{}`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *PublicAdapterCallRequest) GetContextOk() (*map[string]interface{}, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *PublicAdapterCallRequest) SetContext(v map[string]interface{})`

SetContext sets Context field to given value.

### HasContext

`func (o *PublicAdapterCallRequest) HasContext() bool`

HasContext returns a boolean if a field has been set.

### SetContextNil

`func (o *PublicAdapterCallRequest) SetContextNil(b bool)`

 SetContextNil sets the value for Context to be an explicit nil

### UnsetContext
`func (o *PublicAdapterCallRequest) UnsetContext()`

UnsetContext ensures that no value is present for Context, not even an explicit nil
### GetCaptchaToken

`func (o *PublicAdapterCallRequest) GetCaptchaToken() string`

GetCaptchaToken returns the CaptchaToken field if non-nil, zero value otherwise.

### GetCaptchaTokenOk

`func (o *PublicAdapterCallRequest) GetCaptchaTokenOk() (*string, bool)`

GetCaptchaTokenOk returns a tuple with the CaptchaToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCaptchaToken

`func (o *PublicAdapterCallRequest) SetCaptchaToken(v string)`

SetCaptchaToken sets CaptchaToken field to given value.

### HasCaptchaToken

`func (o *PublicAdapterCallRequest) HasCaptchaToken() bool`

HasCaptchaToken returns a boolean if a field has been set.

### SetCaptchaTokenNil

`func (o *PublicAdapterCallRequest) SetCaptchaTokenNil(b bool)`

 SetCaptchaTokenNil sets the value for CaptchaToken to be an explicit nil

### UnsetCaptchaToken
`func (o *PublicAdapterCallRequest) UnsetCaptchaToken()`

UnsetCaptchaToken ensures that no value is present for CaptchaToken, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


