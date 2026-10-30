# SaveWorkspaceWorkflowRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Revision** | **int32** | The revision the editor read. | 
**Name** | Pointer to **string** |  | [optional] 
**Timezone** | Pointer to **string** |  | [optional] 
**Graph** | Pointer to [**WorkflowGraph**](WorkflowGraph.md) |  | [optional] 

## Methods

### NewSaveWorkspaceWorkflowRequest

`func NewSaveWorkspaceWorkflowRequest(revision int32, ) *SaveWorkspaceWorkflowRequest`

NewSaveWorkspaceWorkflowRequest instantiates a new SaveWorkspaceWorkflowRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSaveWorkspaceWorkflowRequestWithDefaults

`func NewSaveWorkspaceWorkflowRequestWithDefaults() *SaveWorkspaceWorkflowRequest`

NewSaveWorkspaceWorkflowRequestWithDefaults instantiates a new SaveWorkspaceWorkflowRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRevision

`func (o *SaveWorkspaceWorkflowRequest) GetRevision() int32`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *SaveWorkspaceWorkflowRequest) GetRevisionOk() (*int32, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *SaveWorkspaceWorkflowRequest) SetRevision(v int32)`

SetRevision sets Revision field to given value.


### GetName

`func (o *SaveWorkspaceWorkflowRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SaveWorkspaceWorkflowRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SaveWorkspaceWorkflowRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *SaveWorkspaceWorkflowRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetTimezone

`func (o *SaveWorkspaceWorkflowRequest) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *SaveWorkspaceWorkflowRequest) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *SaveWorkspaceWorkflowRequest) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *SaveWorkspaceWorkflowRequest) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.

### GetGraph

`func (o *SaveWorkspaceWorkflowRequest) GetGraph() WorkflowGraph`

GetGraph returns the Graph field if non-nil, zero value otherwise.

### GetGraphOk

`func (o *SaveWorkspaceWorkflowRequest) GetGraphOk() (*WorkflowGraph, bool)`

GetGraphOk returns a tuple with the Graph field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGraph

`func (o *SaveWorkspaceWorkflowRequest) SetGraph(v WorkflowGraph)`

SetGraph sets Graph field to given value.

### HasGraph

`func (o *SaveWorkspaceWorkflowRequest) HasGraph() bool`

HasGraph returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


