# RemovePartnerWorkflowPreset200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**WorkflowPresetRemoval**](WorkflowPresetRemoval.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewRemovePartnerWorkflowPreset200Response

`func NewRemovePartnerWorkflowPreset200Response(success bool, data WorkflowPresetRemoval, ) *RemovePartnerWorkflowPreset200Response`

NewRemovePartnerWorkflowPreset200Response instantiates a new RemovePartnerWorkflowPreset200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRemovePartnerWorkflowPreset200ResponseWithDefaults

`func NewRemovePartnerWorkflowPreset200ResponseWithDefaults() *RemovePartnerWorkflowPreset200Response`

NewRemovePartnerWorkflowPreset200ResponseWithDefaults instantiates a new RemovePartnerWorkflowPreset200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *RemovePartnerWorkflowPreset200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *RemovePartnerWorkflowPreset200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *RemovePartnerWorkflowPreset200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *RemovePartnerWorkflowPreset200Response) GetData() WorkflowPresetRemoval`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *RemovePartnerWorkflowPreset200Response) GetDataOk() (*WorkflowPresetRemoval, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *RemovePartnerWorkflowPreset200Response) SetData(v WorkflowPresetRemoval)`

SetData sets Data field to given value.


### GetMeta

`func (o *RemovePartnerWorkflowPreset200Response) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *RemovePartnerWorkflowPreset200Response) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *RemovePartnerWorkflowPreset200Response) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *RemovePartnerWorkflowPreset200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


