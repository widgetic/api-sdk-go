# ValidateCompositionContentResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Always &#x60;true&#x60; on a success. | 
**Data** | [**ValidateCompositionContentResponseData**](ValidateCompositionContentResponseData.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewValidateCompositionContentResponse

`func NewValidateCompositionContentResponse(success bool, data ValidateCompositionContentResponseData, ) *ValidateCompositionContentResponse`

NewValidateCompositionContentResponse instantiates a new ValidateCompositionContentResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewValidateCompositionContentResponseWithDefaults

`func NewValidateCompositionContentResponseWithDefaults() *ValidateCompositionContentResponse`

NewValidateCompositionContentResponseWithDefaults instantiates a new ValidateCompositionContentResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *ValidateCompositionContentResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ValidateCompositionContentResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ValidateCompositionContentResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *ValidateCompositionContentResponse) GetData() ValidateCompositionContentResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ValidateCompositionContentResponse) GetDataOk() (*ValidateCompositionContentResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ValidateCompositionContentResponse) SetData(v ValidateCompositionContentResponseData)`

SetData sets Data field to given value.


### GetMeta

`func (o *ValidateCompositionContentResponse) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ValidateCompositionContentResponse) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ValidateCompositionContentResponse) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *ValidateCompositionContentResponse) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


