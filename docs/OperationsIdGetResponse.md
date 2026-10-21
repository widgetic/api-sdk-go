# OperationsIdGetResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Always &#x60;true&#x60; on a success. | 
**Data** | [**OperationsIdGetResponseData**](OperationsIdGetResponseData.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewOperationsIdGetResponse

`func NewOperationsIdGetResponse(success bool, data OperationsIdGetResponseData, ) *OperationsIdGetResponse`

NewOperationsIdGetResponse instantiates a new OperationsIdGetResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperationsIdGetResponseWithDefaults

`func NewOperationsIdGetResponseWithDefaults() *OperationsIdGetResponse`

NewOperationsIdGetResponseWithDefaults instantiates a new OperationsIdGetResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *OperationsIdGetResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *OperationsIdGetResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *OperationsIdGetResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *OperationsIdGetResponse) GetData() OperationsIdGetResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *OperationsIdGetResponse) GetDataOk() (*OperationsIdGetResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *OperationsIdGetResponse) SetData(v OperationsIdGetResponseData)`

SetData sets Data field to given value.


### GetMeta

`func (o *OperationsIdGetResponse) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *OperationsIdGetResponse) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *OperationsIdGetResponse) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *OperationsIdGetResponse) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


