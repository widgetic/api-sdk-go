# GetCompositionsBatchResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Always &#x60;true&#x60; on a success. | 
**Data** | [**GetCompositionsBatchResponseData**](GetCompositionsBatchResponseData.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewGetCompositionsBatchResponse

`func NewGetCompositionsBatchResponse(success bool, data GetCompositionsBatchResponseData, ) *GetCompositionsBatchResponse`

NewGetCompositionsBatchResponse instantiates a new GetCompositionsBatchResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetCompositionsBatchResponseWithDefaults

`func NewGetCompositionsBatchResponseWithDefaults() *GetCompositionsBatchResponse`

NewGetCompositionsBatchResponseWithDefaults instantiates a new GetCompositionsBatchResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *GetCompositionsBatchResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetCompositionsBatchResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetCompositionsBatchResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *GetCompositionsBatchResponse) GetData() GetCompositionsBatchResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetCompositionsBatchResponse) GetDataOk() (*GetCompositionsBatchResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetCompositionsBatchResponse) SetData(v GetCompositionsBatchResponseData)`

SetData sets Data field to given value.


### GetMeta

`func (o *GetCompositionsBatchResponse) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetCompositionsBatchResponse) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetCompositionsBatchResponse) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetCompositionsBatchResponse) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


