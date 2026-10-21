# GetUserApiKeyUsageLogsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Always &#x60;true&#x60; on a success. | 
**Data** | [**GetUserApiKeyUsageLogsResponseData**](GetUserApiKeyUsageLogsResponseData.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewGetUserApiKeyUsageLogsResponse

`func NewGetUserApiKeyUsageLogsResponse(success bool, data GetUserApiKeyUsageLogsResponseData, ) *GetUserApiKeyUsageLogsResponse`

NewGetUserApiKeyUsageLogsResponse instantiates a new GetUserApiKeyUsageLogsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetUserApiKeyUsageLogsResponseWithDefaults

`func NewGetUserApiKeyUsageLogsResponseWithDefaults() *GetUserApiKeyUsageLogsResponse`

NewGetUserApiKeyUsageLogsResponseWithDefaults instantiates a new GetUserApiKeyUsageLogsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *GetUserApiKeyUsageLogsResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetUserApiKeyUsageLogsResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetUserApiKeyUsageLogsResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *GetUserApiKeyUsageLogsResponse) GetData() GetUserApiKeyUsageLogsResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetUserApiKeyUsageLogsResponse) GetDataOk() (*GetUserApiKeyUsageLogsResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetUserApiKeyUsageLogsResponse) SetData(v GetUserApiKeyUsageLogsResponseData)`

SetData sets Data field to given value.


### GetMeta

`func (o *GetUserApiKeyUsageLogsResponse) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetUserApiKeyUsageLogsResponse) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetUserApiKeyUsageLogsResponse) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetUserApiKeyUsageLogsResponse) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


