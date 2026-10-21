# GetWidgetsBatchResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Always &#x60;true&#x60; on a success. | 
**Data** | [**GetWidgetsBatchResponseData**](GetWidgetsBatchResponseData.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewGetWidgetsBatchResponse

`func NewGetWidgetsBatchResponse(success bool, data GetWidgetsBatchResponseData, ) *GetWidgetsBatchResponse`

NewGetWidgetsBatchResponse instantiates a new GetWidgetsBatchResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetWidgetsBatchResponseWithDefaults

`func NewGetWidgetsBatchResponseWithDefaults() *GetWidgetsBatchResponse`

NewGetWidgetsBatchResponseWithDefaults instantiates a new GetWidgetsBatchResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *GetWidgetsBatchResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetWidgetsBatchResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetWidgetsBatchResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *GetWidgetsBatchResponse) GetData() GetWidgetsBatchResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetWidgetsBatchResponse) GetDataOk() (*GetWidgetsBatchResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetWidgetsBatchResponse) SetData(v GetWidgetsBatchResponseData)`

SetData sets Data field to given value.


### GetMeta

`func (o *GetWidgetsBatchResponse) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetWidgetsBatchResponse) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetWidgetsBatchResponse) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetWidgetsBatchResponse) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


