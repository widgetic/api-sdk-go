# GetAllCanvasesResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Always &#x60;true&#x60; on a success. | 
**Data** | [**GetAllCanvasesResponseData**](GetAllCanvasesResponseData.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewGetAllCanvasesResponse

`func NewGetAllCanvasesResponse(success bool, data GetAllCanvasesResponseData, ) *GetAllCanvasesResponse`

NewGetAllCanvasesResponse instantiates a new GetAllCanvasesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetAllCanvasesResponseWithDefaults

`func NewGetAllCanvasesResponseWithDefaults() *GetAllCanvasesResponse`

NewGetAllCanvasesResponseWithDefaults instantiates a new GetAllCanvasesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *GetAllCanvasesResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetAllCanvasesResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetAllCanvasesResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *GetAllCanvasesResponse) GetData() GetAllCanvasesResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetAllCanvasesResponse) GetDataOk() (*GetAllCanvasesResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetAllCanvasesResponse) SetData(v GetAllCanvasesResponseData)`

SetData sets Data field to given value.


### GetMeta

`func (o *GetAllCanvasesResponse) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetAllCanvasesResponse) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetAllCanvasesResponse) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetAllCanvasesResponse) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


