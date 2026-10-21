# DeleteCompositionContentItemResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Always &#x60;true&#x60; on a success. | 
**Data** | [**DeleteCompositionContentItemResponseData**](DeleteCompositionContentItemResponseData.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewDeleteCompositionContentItemResponse

`func NewDeleteCompositionContentItemResponse(success bool, data DeleteCompositionContentItemResponseData, ) *DeleteCompositionContentItemResponse`

NewDeleteCompositionContentItemResponse instantiates a new DeleteCompositionContentItemResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeleteCompositionContentItemResponseWithDefaults

`func NewDeleteCompositionContentItemResponseWithDefaults() *DeleteCompositionContentItemResponse`

NewDeleteCompositionContentItemResponseWithDefaults instantiates a new DeleteCompositionContentItemResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *DeleteCompositionContentItemResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *DeleteCompositionContentItemResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *DeleteCompositionContentItemResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *DeleteCompositionContentItemResponse) GetData() DeleteCompositionContentItemResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *DeleteCompositionContentItemResponse) GetDataOk() (*DeleteCompositionContentItemResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *DeleteCompositionContentItemResponse) SetData(v DeleteCompositionContentItemResponseData)`

SetData sets Data field to given value.


### GetMeta

`func (o *DeleteCompositionContentItemResponse) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *DeleteCompositionContentItemResponse) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *DeleteCompositionContentItemResponse) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *DeleteCompositionContentItemResponse) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


