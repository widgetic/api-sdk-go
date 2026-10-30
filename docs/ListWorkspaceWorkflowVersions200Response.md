# ListWorkspaceWorkflowVersions200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**WorkflowVersionList**](WorkflowVersionList.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewListWorkspaceWorkflowVersions200Response

`func NewListWorkspaceWorkflowVersions200Response(success bool, data WorkflowVersionList, ) *ListWorkspaceWorkflowVersions200Response`

NewListWorkspaceWorkflowVersions200Response instantiates a new ListWorkspaceWorkflowVersions200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListWorkspaceWorkflowVersions200ResponseWithDefaults

`func NewListWorkspaceWorkflowVersions200ResponseWithDefaults() *ListWorkspaceWorkflowVersions200Response`

NewListWorkspaceWorkflowVersions200ResponseWithDefaults instantiates a new ListWorkspaceWorkflowVersions200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *ListWorkspaceWorkflowVersions200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ListWorkspaceWorkflowVersions200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ListWorkspaceWorkflowVersions200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *ListWorkspaceWorkflowVersions200Response) GetData() WorkflowVersionList`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ListWorkspaceWorkflowVersions200Response) GetDataOk() (*WorkflowVersionList, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ListWorkspaceWorkflowVersions200Response) SetData(v WorkflowVersionList)`

SetData sets Data field to given value.


### GetMeta

`func (o *ListWorkspaceWorkflowVersions200Response) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ListWorkspaceWorkflowVersions200Response) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ListWorkspaceWorkflowVersions200Response) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *ListWorkspaceWorkflowVersions200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


