# ListWorkspaceWorkflowPresets200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**WorkflowPresetChoices**](WorkflowPresetChoices.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewListWorkspaceWorkflowPresets200Response

`func NewListWorkspaceWorkflowPresets200Response(success bool, data WorkflowPresetChoices, ) *ListWorkspaceWorkflowPresets200Response`

NewListWorkspaceWorkflowPresets200Response instantiates a new ListWorkspaceWorkflowPresets200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListWorkspaceWorkflowPresets200ResponseWithDefaults

`func NewListWorkspaceWorkflowPresets200ResponseWithDefaults() *ListWorkspaceWorkflowPresets200Response`

NewListWorkspaceWorkflowPresets200ResponseWithDefaults instantiates a new ListWorkspaceWorkflowPresets200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *ListWorkspaceWorkflowPresets200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ListWorkspaceWorkflowPresets200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ListWorkspaceWorkflowPresets200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *ListWorkspaceWorkflowPresets200Response) GetData() WorkflowPresetChoices`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ListWorkspaceWorkflowPresets200Response) GetDataOk() (*WorkflowPresetChoices, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ListWorkspaceWorkflowPresets200Response) SetData(v WorkflowPresetChoices)`

SetData sets Data field to given value.


### GetMeta

`func (o *ListWorkspaceWorkflowPresets200Response) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ListWorkspaceWorkflowPresets200Response) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ListWorkspaceWorkflowPresets200Response) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *ListWorkspaceWorkflowPresets200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


