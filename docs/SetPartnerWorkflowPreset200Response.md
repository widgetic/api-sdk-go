# SetPartnerWorkflowPreset200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**OfferedWorkflowPreset**](OfferedWorkflowPreset.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewSetPartnerWorkflowPreset200Response

`func NewSetPartnerWorkflowPreset200Response(success bool, data OfferedWorkflowPreset, ) *SetPartnerWorkflowPreset200Response`

NewSetPartnerWorkflowPreset200Response instantiates a new SetPartnerWorkflowPreset200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSetPartnerWorkflowPreset200ResponseWithDefaults

`func NewSetPartnerWorkflowPreset200ResponseWithDefaults() *SetPartnerWorkflowPreset200Response`

NewSetPartnerWorkflowPreset200ResponseWithDefaults instantiates a new SetPartnerWorkflowPreset200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *SetPartnerWorkflowPreset200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *SetPartnerWorkflowPreset200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *SetPartnerWorkflowPreset200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *SetPartnerWorkflowPreset200Response) GetData() OfferedWorkflowPreset`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *SetPartnerWorkflowPreset200Response) GetDataOk() (*OfferedWorkflowPreset, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *SetPartnerWorkflowPreset200Response) SetData(v OfferedWorkflowPreset)`

SetData sets Data field to given value.


### GetMeta

`func (o *SetPartnerWorkflowPreset200Response) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *SetPartnerWorkflowPreset200Response) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *SetPartnerWorkflowPreset200Response) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *SetPartnerWorkflowPreset200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


