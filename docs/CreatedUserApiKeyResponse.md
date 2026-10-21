# CreatedUserApiKeyResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Always &#x60;true&#x60; on a success. | 
**Data** | [**CreatedUserApiKey**](CreatedUserApiKey.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewCreatedUserApiKeyResponse

`func NewCreatedUserApiKeyResponse(success bool, data CreatedUserApiKey, ) *CreatedUserApiKeyResponse`

NewCreatedUserApiKeyResponse instantiates a new CreatedUserApiKeyResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreatedUserApiKeyResponseWithDefaults

`func NewCreatedUserApiKeyResponseWithDefaults() *CreatedUserApiKeyResponse`

NewCreatedUserApiKeyResponseWithDefaults instantiates a new CreatedUserApiKeyResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *CreatedUserApiKeyResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *CreatedUserApiKeyResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *CreatedUserApiKeyResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *CreatedUserApiKeyResponse) GetData() CreatedUserApiKey`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *CreatedUserApiKeyResponse) GetDataOk() (*CreatedUserApiKey, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *CreatedUserApiKeyResponse) SetData(v CreatedUserApiKey)`

SetData sets Data field to given value.


### GetMeta

`func (o *CreatedUserApiKeyResponse) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *CreatedUserApiKeyResponse) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *CreatedUserApiKeyResponse) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *CreatedUserApiKeyResponse) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


