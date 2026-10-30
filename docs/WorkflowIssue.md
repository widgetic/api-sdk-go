# WorkflowIssue

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | **string** |  | 
**Severity** | **string** |  | 
**NodeId** | Pointer to **string** |  | [optional] 
**EdgeId** | Pointer to **string** |  | [optional] 
**CaseId** | Pointer to **string** |  | [optional] 
**Detail** | Pointer to **string** | A short machine-readable detail such as a column or a table name. Never a sentence. | [optional] 

## Methods

### NewWorkflowIssue

`func NewWorkflowIssue(code string, severity string, ) *WorkflowIssue`

NewWorkflowIssue instantiates a new WorkflowIssue object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowIssueWithDefaults

`func NewWorkflowIssueWithDefaults() *WorkflowIssue`

NewWorkflowIssueWithDefaults instantiates a new WorkflowIssue object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *WorkflowIssue) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *WorkflowIssue) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *WorkflowIssue) SetCode(v string)`

SetCode sets Code field to given value.


### GetSeverity

`func (o *WorkflowIssue) GetSeverity() string`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *WorkflowIssue) GetSeverityOk() (*string, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *WorkflowIssue) SetSeverity(v string)`

SetSeverity sets Severity field to given value.


### GetNodeId

`func (o *WorkflowIssue) GetNodeId() string`

GetNodeId returns the NodeId field if non-nil, zero value otherwise.

### GetNodeIdOk

`func (o *WorkflowIssue) GetNodeIdOk() (*string, bool)`

GetNodeIdOk returns a tuple with the NodeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodeId

`func (o *WorkflowIssue) SetNodeId(v string)`

SetNodeId sets NodeId field to given value.

### HasNodeId

`func (o *WorkflowIssue) HasNodeId() bool`

HasNodeId returns a boolean if a field has been set.

### GetEdgeId

`func (o *WorkflowIssue) GetEdgeId() string`

GetEdgeId returns the EdgeId field if non-nil, zero value otherwise.

### GetEdgeIdOk

`func (o *WorkflowIssue) GetEdgeIdOk() (*string, bool)`

GetEdgeIdOk returns a tuple with the EdgeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdgeId

`func (o *WorkflowIssue) SetEdgeId(v string)`

SetEdgeId sets EdgeId field to given value.

### HasEdgeId

`func (o *WorkflowIssue) HasEdgeId() bool`

HasEdgeId returns a boolean if a field has been set.

### GetCaseId

`func (o *WorkflowIssue) GetCaseId() string`

GetCaseId returns the CaseId field if non-nil, zero value otherwise.

### GetCaseIdOk

`func (o *WorkflowIssue) GetCaseIdOk() (*string, bool)`

GetCaseIdOk returns a tuple with the CaseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCaseId

`func (o *WorkflowIssue) SetCaseId(v string)`

SetCaseId sets CaseId field to given value.

### HasCaseId

`func (o *WorkflowIssue) HasCaseId() bool`

HasCaseId returns a boolean if a field has been set.

### GetDetail

`func (o *WorkflowIssue) GetDetail() string`

GetDetail returns the Detail field if non-nil, zero value otherwise.

### GetDetailOk

`func (o *WorkflowIssue) GetDetailOk() (*string, bool)`

GetDetailOk returns a tuple with the Detail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetail

`func (o *WorkflowIssue) SetDetail(v string)`

SetDetail sets Detail field to given value.

### HasDetail

`func (o *WorkflowIssue) HasDetail() bool`

HasDetail returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


