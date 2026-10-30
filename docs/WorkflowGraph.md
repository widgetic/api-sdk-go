# WorkflowGraph

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SchemaVersion** | **int32** |  | 
**Nodes** | [**[]WorkflowNode**](WorkflowNode.md) |  | 
**Edges** | [**[]WorkflowEdge**](WorkflowEdge.md) |  | 

## Methods

### NewWorkflowGraph

`func NewWorkflowGraph(schemaVersion int32, nodes []WorkflowNode, edges []WorkflowEdge, ) *WorkflowGraph`

NewWorkflowGraph instantiates a new WorkflowGraph object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowGraphWithDefaults

`func NewWorkflowGraphWithDefaults() *WorkflowGraph`

NewWorkflowGraphWithDefaults instantiates a new WorkflowGraph object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSchemaVersion

`func (o *WorkflowGraph) GetSchemaVersion() int32`

GetSchemaVersion returns the SchemaVersion field if non-nil, zero value otherwise.

### GetSchemaVersionOk

`func (o *WorkflowGraph) GetSchemaVersionOk() (*int32, bool)`

GetSchemaVersionOk returns a tuple with the SchemaVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchemaVersion

`func (o *WorkflowGraph) SetSchemaVersion(v int32)`

SetSchemaVersion sets SchemaVersion field to given value.


### GetNodes

`func (o *WorkflowGraph) GetNodes() []WorkflowNode`

GetNodes returns the Nodes field if non-nil, zero value otherwise.

### GetNodesOk

`func (o *WorkflowGraph) GetNodesOk() (*[]WorkflowNode, bool)`

GetNodesOk returns a tuple with the Nodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodes

`func (o *WorkflowGraph) SetNodes(v []WorkflowNode)`

SetNodes sets Nodes field to given value.


### GetEdges

`func (o *WorkflowGraph) GetEdges() []WorkflowEdge`

GetEdges returns the Edges field if non-nil, zero value otherwise.

### GetEdgesOk

`func (o *WorkflowGraph) GetEdgesOk() (*[]WorkflowEdge, bool)`

GetEdgesOk returns a tuple with the Edges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdges

`func (o *WorkflowGraph) SetEdges(v []WorkflowEdge)`

SetEdges sets Edges field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


