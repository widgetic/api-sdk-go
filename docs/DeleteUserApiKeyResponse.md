# DeleteUserApiKeyResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Always &#x60;true&#x60; on a success. | 
**Data** | [**DeleteUserApiKeyResponseData**](DeleteUserApiKeyResponseData.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewDeleteUserApiKeyResponse

`func NewDeleteUserApiKeyResponse(success bool, data DeleteUserApiKeyResponseData, ) *DeleteUserApiKeyResponse`

NewDeleteUserApiKeyResponse instantiates a new DeleteUserApiKeyResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeleteUserApiKeyResponseWithDefaults

`func NewDeleteUserApiKeyResponseWithDefaults() *DeleteUserApiKeyResponse`

NewDeleteUserApiKeyResponseWithDefaults instantiates a new DeleteUserApiKeyResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *DeleteUserApiKeyResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *DeleteUserApiKeyResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *DeleteUserApiKeyResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *DeleteUserApiKeyResponse) GetData() DeleteUserApiKeyResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *DeleteUserApiKeyResponse) GetDataOk() (*DeleteUserApiKeyResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *DeleteUserApiKeyResponse) SetData(v DeleteUserApiKeyResponseData)`

SetData sets Data field to given value.


### GetMeta

`func (o *DeleteUserApiKeyResponse) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *DeleteUserApiKeyResponse) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *DeleteUserApiKeyResponse) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *DeleteUserApiKeyResponse) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


