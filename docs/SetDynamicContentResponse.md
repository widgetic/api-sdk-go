# SetDynamicContentResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Always &#x60;true&#x60; on a success. | 
**Data** | [**SetDynamicContentResponseData**](SetDynamicContentResponseData.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewSetDynamicContentResponse

`func NewSetDynamicContentResponse(success bool, data SetDynamicContentResponseData, ) *SetDynamicContentResponse`

NewSetDynamicContentResponse instantiates a new SetDynamicContentResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSetDynamicContentResponseWithDefaults

`func NewSetDynamicContentResponseWithDefaults() *SetDynamicContentResponse`

NewSetDynamicContentResponseWithDefaults instantiates a new SetDynamicContentResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *SetDynamicContentResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *SetDynamicContentResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *SetDynamicContentResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *SetDynamicContentResponse) GetData() SetDynamicContentResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *SetDynamicContentResponse) GetDataOk() (*SetDynamicContentResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *SetDynamicContentResponse) SetData(v SetDynamicContentResponseData)`

SetData sets Data field to given value.


### GetMeta

`func (o *SetDynamicContentResponse) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *SetDynamicContentResponse) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *SetDynamicContentResponse) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *SetDynamicContentResponse) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


