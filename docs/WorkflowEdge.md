# WorkflowEdge

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Source** | **string** |  | 
**SourcePort** | **string** | &#x60;out&#x60; for compositions and triggers; a rule&#39;s id, or &#x60;default&#x60;, for conditions. | 
**Target** | **string** |  | 

## Methods

### NewWorkflowEdge

`func NewWorkflowEdge(id string, source string, sourcePort string, target string, ) *WorkflowEdge`

NewWorkflowEdge instantiates a new WorkflowEdge object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowEdgeWithDefaults

`func NewWorkflowEdgeWithDefaults() *WorkflowEdge`

NewWorkflowEdgeWithDefaults instantiates a new WorkflowEdge object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *WorkflowEdge) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WorkflowEdge) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WorkflowEdge) SetId(v string)`

SetId sets Id field to given value.


### GetSource

`func (o *WorkflowEdge) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *WorkflowEdge) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *WorkflowEdge) SetSource(v string)`

SetSource sets Source field to given value.


### GetSourcePort

`func (o *WorkflowEdge) GetSourcePort() string`

GetSourcePort returns the SourcePort field if non-nil, zero value otherwise.

### GetSourcePortOk

`func (o *WorkflowEdge) GetSourcePortOk() (*string, bool)`

GetSourcePortOk returns a tuple with the SourcePort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourcePort

`func (o *WorkflowEdge) SetSourcePort(v string)`

SetSourcePort sets SourcePort field to given value.


### GetTarget

`func (o *WorkflowEdge) GetTarget() string`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *WorkflowEdge) GetTargetOk() (*string, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *WorkflowEdge) SetTarget(v string)`

SetTarget sets Target field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


