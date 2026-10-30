# WorkflowStats

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**WorkflowId** | **string** |  | 
**VersionId** | Pointer to **NullableString** | The version counted, or null when all versions are. | [optional] 
**From** | **string** | First UTC day counted (YYYY-MM-DD). | 
**To** | **string** | Last UTC day counted (YYYY-MM-DD). | 
**Started** | Pointer to **NullableInt32** | Visitors who started the workflow in the range; null when all versions are counted. | [optional] 
**Nodes** | [**[]WorkflowCounter**](WorkflowCounter.md) | Visitors who reached each block. | 
**Edges** | [**[]WorkflowCounter**](WorkflowCounter.md) | Visitors who took each connection. | 
**Failed** | [**[]WorkflowCounter**](WorkflowCounter.md) | Times moving on to a block failed (it did not load in time) and the visitor stayed. | 

## Methods

### NewWorkflowStats

`func NewWorkflowStats(workflowId string, from string, to string, nodes []WorkflowCounter, edges []WorkflowCounter, failed []WorkflowCounter, ) *WorkflowStats`

NewWorkflowStats instantiates a new WorkflowStats object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowStatsWithDefaults

`func NewWorkflowStatsWithDefaults() *WorkflowStats`

NewWorkflowStatsWithDefaults instantiates a new WorkflowStats object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWorkflowId

`func (o *WorkflowStats) GetWorkflowId() string`

GetWorkflowId returns the WorkflowId field if non-nil, zero value otherwise.

### GetWorkflowIdOk

`func (o *WorkflowStats) GetWorkflowIdOk() (*string, bool)`

GetWorkflowIdOk returns a tuple with the WorkflowId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowId

`func (o *WorkflowStats) SetWorkflowId(v string)`

SetWorkflowId sets WorkflowId field to given value.


### GetVersionId

`func (o *WorkflowStats) GetVersionId() string`

GetVersionId returns the VersionId field if non-nil, zero value otherwise.

### GetVersionIdOk

`func (o *WorkflowStats) GetVersionIdOk() (*string, bool)`

GetVersionIdOk returns a tuple with the VersionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersionId

`func (o *WorkflowStats) SetVersionId(v string)`

SetVersionId sets VersionId field to given value.

### HasVersionId

`func (o *WorkflowStats) HasVersionId() bool`

HasVersionId returns a boolean if a field has been set.

### SetVersionIdNil

`func (o *WorkflowStats) SetVersionIdNil(b bool)`

 SetVersionIdNil sets the value for VersionId to be an explicit nil

### UnsetVersionId
`func (o *WorkflowStats) UnsetVersionId()`

UnsetVersionId ensures that no value is present for VersionId, not even an explicit nil
### GetFrom

`func (o *WorkflowStats) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *WorkflowStats) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *WorkflowStats) SetFrom(v string)`

SetFrom sets From field to given value.


### GetTo

`func (o *WorkflowStats) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *WorkflowStats) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *WorkflowStats) SetTo(v string)`

SetTo sets To field to given value.


### GetStarted

`func (o *WorkflowStats) GetStarted() int32`

GetStarted returns the Started field if non-nil, zero value otherwise.

### GetStartedOk

`func (o *WorkflowStats) GetStartedOk() (*int32, bool)`

GetStartedOk returns a tuple with the Started field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStarted

`func (o *WorkflowStats) SetStarted(v int32)`

SetStarted sets Started field to given value.

### HasStarted

`func (o *WorkflowStats) HasStarted() bool`

HasStarted returns a boolean if a field has been set.

### SetStartedNil

`func (o *WorkflowStats) SetStartedNil(b bool)`

 SetStartedNil sets the value for Started to be an explicit nil

### UnsetStarted
`func (o *WorkflowStats) UnsetStarted()`

UnsetStarted ensures that no value is present for Started, not even an explicit nil
### GetNodes

`func (o *WorkflowStats) GetNodes() []WorkflowCounter`

GetNodes returns the Nodes field if non-nil, zero value otherwise.

### GetNodesOk

`func (o *WorkflowStats) GetNodesOk() (*[]WorkflowCounter, bool)`

GetNodesOk returns a tuple with the Nodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodes

`func (o *WorkflowStats) SetNodes(v []WorkflowCounter)`

SetNodes sets Nodes field to given value.


### GetEdges

`func (o *WorkflowStats) GetEdges() []WorkflowCounter`

GetEdges returns the Edges field if non-nil, zero value otherwise.

### GetEdgesOk

`func (o *WorkflowStats) GetEdgesOk() (*[]WorkflowCounter, bool)`

GetEdgesOk returns a tuple with the Edges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdges

`func (o *WorkflowStats) SetEdges(v []WorkflowCounter)`

SetEdges sets Edges field to given value.


### GetFailed

`func (o *WorkflowStats) GetFailed() []WorkflowCounter`

GetFailed returns the Failed field if non-nil, zero value otherwise.

### GetFailedOk

`func (o *WorkflowStats) GetFailedOk() (*[]WorkflowCounter, bool)`

GetFailedOk returns a tuple with the Failed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailed

`func (o *WorkflowStats) SetFailed(v []WorkflowCounter)`

SetFailed sets Failed field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


