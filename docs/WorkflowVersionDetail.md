# WorkflowVersionDetail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**VersionNumber** | **int32** |  | 
**PublishedAt** | **time.Time** |  | 
**PublishedBy** | Pointer to [**NullableWorkflowVersionPublishedBy**](WorkflowVersionPublishedBy.md) |  | [optional] 
**Timezone** | **string** |  | 
**IsLive** | **bool** | Whether this is the version visitors who are new to the workflow get. | 
**StartNodeId** | **string** |  | 
**Graph** | [**WorkflowGraph**](WorkflowGraph.md) |  | 

## Methods

### NewWorkflowVersionDetail

`func NewWorkflowVersionDetail(id string, versionNumber int32, publishedAt time.Time, timezone string, isLive bool, startNodeId string, graph WorkflowGraph, ) *WorkflowVersionDetail`

NewWorkflowVersionDetail instantiates a new WorkflowVersionDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowVersionDetailWithDefaults

`func NewWorkflowVersionDetailWithDefaults() *WorkflowVersionDetail`

NewWorkflowVersionDetailWithDefaults instantiates a new WorkflowVersionDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *WorkflowVersionDetail) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WorkflowVersionDetail) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WorkflowVersionDetail) SetId(v string)`

SetId sets Id field to given value.


### GetVersionNumber

`func (o *WorkflowVersionDetail) GetVersionNumber() int32`

GetVersionNumber returns the VersionNumber field if non-nil, zero value otherwise.

### GetVersionNumberOk

`func (o *WorkflowVersionDetail) GetVersionNumberOk() (*int32, bool)`

GetVersionNumberOk returns a tuple with the VersionNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersionNumber

`func (o *WorkflowVersionDetail) SetVersionNumber(v int32)`

SetVersionNumber sets VersionNumber field to given value.


### GetPublishedAt

`func (o *WorkflowVersionDetail) GetPublishedAt() time.Time`

GetPublishedAt returns the PublishedAt field if non-nil, zero value otherwise.

### GetPublishedAtOk

`func (o *WorkflowVersionDetail) GetPublishedAtOk() (*time.Time, bool)`

GetPublishedAtOk returns a tuple with the PublishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishedAt

`func (o *WorkflowVersionDetail) SetPublishedAt(v time.Time)`

SetPublishedAt sets PublishedAt field to given value.


### GetPublishedBy

`func (o *WorkflowVersionDetail) GetPublishedBy() WorkflowVersionPublishedBy`

GetPublishedBy returns the PublishedBy field if non-nil, zero value otherwise.

### GetPublishedByOk

`func (o *WorkflowVersionDetail) GetPublishedByOk() (*WorkflowVersionPublishedBy, bool)`

GetPublishedByOk returns a tuple with the PublishedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishedBy

`func (o *WorkflowVersionDetail) SetPublishedBy(v WorkflowVersionPublishedBy)`

SetPublishedBy sets PublishedBy field to given value.

### HasPublishedBy

`func (o *WorkflowVersionDetail) HasPublishedBy() bool`

HasPublishedBy returns a boolean if a field has been set.

### SetPublishedByNil

`func (o *WorkflowVersionDetail) SetPublishedByNil(b bool)`

 SetPublishedByNil sets the value for PublishedBy to be an explicit nil

### UnsetPublishedBy
`func (o *WorkflowVersionDetail) UnsetPublishedBy()`

UnsetPublishedBy ensures that no value is present for PublishedBy, not even an explicit nil
### GetTimezone

`func (o *WorkflowVersionDetail) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *WorkflowVersionDetail) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *WorkflowVersionDetail) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.


### GetIsLive

`func (o *WorkflowVersionDetail) GetIsLive() bool`

GetIsLive returns the IsLive field if non-nil, zero value otherwise.

### GetIsLiveOk

`func (o *WorkflowVersionDetail) GetIsLiveOk() (*bool, bool)`

GetIsLiveOk returns a tuple with the IsLive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsLive

`func (o *WorkflowVersionDetail) SetIsLive(v bool)`

SetIsLive sets IsLive field to given value.


### GetStartNodeId

`func (o *WorkflowVersionDetail) GetStartNodeId() string`

GetStartNodeId returns the StartNodeId field if non-nil, zero value otherwise.

### GetStartNodeIdOk

`func (o *WorkflowVersionDetail) GetStartNodeIdOk() (*string, bool)`

GetStartNodeIdOk returns a tuple with the StartNodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartNodeId

`func (o *WorkflowVersionDetail) SetStartNodeId(v string)`

SetStartNodeId sets StartNodeId field to given value.


### GetGraph

`func (o *WorkflowVersionDetail) GetGraph() WorkflowGraph`

GetGraph returns the Graph field if non-nil, zero value otherwise.

### GetGraphOk

`func (o *WorkflowVersionDetail) GetGraphOk() (*WorkflowGraph, bool)`

GetGraphOk returns a tuple with the Graph field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGraph

`func (o *WorkflowVersionDetail) SetGraph(v WorkflowGraph)`

SetGraph sets Graph field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


