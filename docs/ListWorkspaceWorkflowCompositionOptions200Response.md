# ListWorkspaceWorkflowCompositionOptions200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**WorkflowCompositionOptions**](WorkflowCompositionOptions.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewListWorkspaceWorkflowCompositionOptions200Response

`func NewListWorkspaceWorkflowCompositionOptions200Response(success bool, data WorkflowCompositionOptions, ) *ListWorkspaceWorkflowCompositionOptions200Response`

NewListWorkspaceWorkflowCompositionOptions200Response instantiates a new ListWorkspaceWorkflowCompositionOptions200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListWorkspaceWorkflowCompositionOptions200ResponseWithDefaults

`func NewListWorkspaceWorkflowCompositionOptions200ResponseWithDefaults() *ListWorkspaceWorkflowCompositionOptions200Response`

NewListWorkspaceWorkflowCompositionOptions200ResponseWithDefaults instantiates a new ListWorkspaceWorkflowCompositionOptions200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *ListWorkspaceWorkflowCompositionOptions200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ListWorkspaceWorkflowCompositionOptions200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ListWorkspaceWorkflowCompositionOptions200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *ListWorkspaceWorkflowCompositionOptions200Response) GetData() WorkflowCompositionOptions`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ListWorkspaceWorkflowCompositionOptions200Response) GetDataOk() (*WorkflowCompositionOptions, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ListWorkspaceWorkflowCompositionOptions200Response) SetData(v WorkflowCompositionOptions)`

SetData sets Data field to given value.


### GetMeta

`func (o *ListWorkspaceWorkflowCompositionOptions200Response) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ListWorkspaceWorkflowCompositionOptions200Response) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ListWorkspaceWorkflowCompositionOptions200Response) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *ListWorkspaceWorkflowCompositionOptions200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


