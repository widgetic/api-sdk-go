# GetUserApiKeys200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**[]UserApiKey**](UserApiKey.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewGetUserApiKeys200Response

`func NewGetUserApiKeys200Response(success bool, data []UserApiKey, ) *GetUserApiKeys200Response`

NewGetUserApiKeys200Response instantiates a new GetUserApiKeys200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetUserApiKeys200ResponseWithDefaults

`func NewGetUserApiKeys200ResponseWithDefaults() *GetUserApiKeys200Response`

NewGetUserApiKeys200ResponseWithDefaults instantiates a new GetUserApiKeys200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *GetUserApiKeys200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetUserApiKeys200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetUserApiKeys200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *GetUserApiKeys200Response) GetData() []UserApiKey`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetUserApiKeys200Response) GetDataOk() (*[]UserApiKey, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetUserApiKeys200Response) SetData(v []UserApiKey)`

SetData sets Data field to given value.


### GetMeta

`func (o *GetUserApiKeys200Response) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetUserApiKeys200Response) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetUserApiKeys200Response) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetUserApiKeys200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


