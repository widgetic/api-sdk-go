# CreateWorkspaceWorkflowFromPreset201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**WorkflowDetail**](WorkflowDetail.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewCreateWorkspaceWorkflowFromPreset201Response

`func NewCreateWorkspaceWorkflowFromPreset201Response(success bool, data WorkflowDetail, ) *CreateWorkspaceWorkflowFromPreset201Response`

NewCreateWorkspaceWorkflowFromPreset201Response instantiates a new CreateWorkspaceWorkflowFromPreset201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateWorkspaceWorkflowFromPreset201ResponseWithDefaults

`func NewCreateWorkspaceWorkflowFromPreset201ResponseWithDefaults() *CreateWorkspaceWorkflowFromPreset201Response`

NewCreateWorkspaceWorkflowFromPreset201ResponseWithDefaults instantiates a new CreateWorkspaceWorkflowFromPreset201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *CreateWorkspaceWorkflowFromPreset201Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *CreateWorkspaceWorkflowFromPreset201Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *CreateWorkspaceWorkflowFromPreset201Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *CreateWorkspaceWorkflowFromPreset201Response) GetData() WorkflowDetail`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *CreateWorkspaceWorkflowFromPreset201Response) GetDataOk() (*WorkflowDetail, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *CreateWorkspaceWorkflowFromPreset201Response) SetData(v WorkflowDetail)`

SetData sets Data field to given value.


### GetMeta

`func (o *CreateWorkspaceWorkflowFromPreset201Response) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *CreateWorkspaceWorkflowFromPreset201Response) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *CreateWorkspaceWorkflowFromPreset201Response) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *CreateWorkspaceWorkflowFromPreset201Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


