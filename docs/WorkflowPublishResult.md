# WorkflowPublishResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Workflow** | [**WorkflowDetail**](WorkflowDetail.md) |  | 
**Version** | [**WorkflowVersion**](WorkflowVersion.md) |  | 
**Warnings** | [**[]WorkflowIssue**](WorkflowIssue.md) | Advice that does not stop publishing, such as a block nothing leads to. | 

## Methods

### NewWorkflowPublishResult

`func NewWorkflowPublishResult(workflow WorkflowDetail, version WorkflowVersion, warnings []WorkflowIssue, ) *WorkflowPublishResult`

NewWorkflowPublishResult instantiates a new WorkflowPublishResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowPublishResultWithDefaults

`func NewWorkflowPublishResultWithDefaults() *WorkflowPublishResult`

NewWorkflowPublishResultWithDefaults instantiates a new WorkflowPublishResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWorkflow

`func (o *WorkflowPublishResult) GetWorkflow() WorkflowDetail`

GetWorkflow returns the Workflow field if non-nil, zero value otherwise.

### GetWorkflowOk

`func (o *WorkflowPublishResult) GetWorkflowOk() (*WorkflowDetail, bool)`

GetWorkflowOk returns a tuple with the Workflow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflow

`func (o *WorkflowPublishResult) SetWorkflow(v WorkflowDetail)`

SetWorkflow sets Workflow field to given value.


### GetVersion

`func (o *WorkflowPublishResult) GetVersion() WorkflowVersion`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *WorkflowPublishResult) GetVersionOk() (*WorkflowVersion, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *WorkflowPublishResult) SetVersion(v WorkflowVersion)`

SetVersion sets Version field to given value.


### GetWarnings

`func (o *WorkflowPublishResult) GetWarnings() []WorkflowIssue`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *WorkflowPublishResult) GetWarningsOk() (*[]WorkflowIssue, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *WorkflowPublishResult) SetWarnings(v []WorkflowIssue)`

SetWarnings sets Warnings field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


