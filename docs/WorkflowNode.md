# WorkflowNode

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Type** | **string** |  | 
**Position** | Pointer to [**WorkflowNodePosition**](WorkflowNodePosition.md) |  | [optional] 
**CompositionId** | Pointer to **string** | The composition a &#x60;composition&#x60; block shows. | [optional] 
**StartsHere** | Pointer to **bool** | Set on the one composition block a visitor starts at. | [optional] 
**Trigger** | Pointer to [**WorkflowTrigger**](WorkflowTrigger.md) |  | [optional] 
**Cases** | Pointer to [**[]WorkflowConditionCase**](WorkflowConditionCase.md) | The rules of a &#x60;condition&#x60; block, in the order they are read. | [optional] 

## Methods

### NewWorkflowNode

`func NewWorkflowNode(id string, type_ string, ) *WorkflowNode`

NewWorkflowNode instantiates a new WorkflowNode object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowNodeWithDefaults

`func NewWorkflowNodeWithDefaults() *WorkflowNode`

NewWorkflowNodeWithDefaults instantiates a new WorkflowNode object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *WorkflowNode) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WorkflowNode) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WorkflowNode) SetId(v string)`

SetId sets Id field to given value.


### GetType

`func (o *WorkflowNode) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *WorkflowNode) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *WorkflowNode) SetType(v string)`

SetType sets Type field to given value.


### GetPosition

`func (o *WorkflowNode) GetPosition() WorkflowNodePosition`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *WorkflowNode) GetPositionOk() (*WorkflowNodePosition, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *WorkflowNode) SetPosition(v WorkflowNodePosition)`

SetPosition sets Position field to given value.

### HasPosition

`func (o *WorkflowNode) HasPosition() bool`

HasPosition returns a boolean if a field has been set.

### GetCompositionId

`func (o *WorkflowNode) GetCompositionId() string`

GetCompositionId returns the CompositionId field if non-nil, zero value otherwise.

### GetCompositionIdOk

`func (o *WorkflowNode) GetCompositionIdOk() (*string, bool)`

GetCompositionIdOk returns a tuple with the CompositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompositionId

`func (o *WorkflowNode) SetCompositionId(v string)`

SetCompositionId sets CompositionId field to given value.

### HasCompositionId

`func (o *WorkflowNode) HasCompositionId() bool`

HasCompositionId returns a boolean if a field has been set.

### GetStartsHere

`func (o *WorkflowNode) GetStartsHere() bool`

GetStartsHere returns the StartsHere field if non-nil, zero value otherwise.

### GetStartsHereOk

`func (o *WorkflowNode) GetStartsHereOk() (*bool, bool)`

GetStartsHereOk returns a tuple with the StartsHere field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartsHere

`func (o *WorkflowNode) SetStartsHere(v bool)`

SetStartsHere sets StartsHere field to given value.

### HasStartsHere

`func (o *WorkflowNode) HasStartsHere() bool`

HasStartsHere returns a boolean if a field has been set.

### GetTrigger

`func (o *WorkflowNode) GetTrigger() WorkflowTrigger`

GetTrigger returns the Trigger field if non-nil, zero value otherwise.

### GetTriggerOk

`func (o *WorkflowNode) GetTriggerOk() (*WorkflowTrigger, bool)`

GetTriggerOk returns a tuple with the Trigger field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrigger

`func (o *WorkflowNode) SetTrigger(v WorkflowTrigger)`

SetTrigger sets Trigger field to given value.

### HasTrigger

`func (o *WorkflowNode) HasTrigger() bool`

HasTrigger returns a boolean if a field has been set.

### GetCases

`func (o *WorkflowNode) GetCases() []WorkflowConditionCase`

GetCases returns the Cases field if non-nil, zero value otherwise.

### GetCasesOk

`func (o *WorkflowNode) GetCasesOk() (*[]WorkflowConditionCase, bool)`

GetCasesOk returns a tuple with the Cases field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCases

`func (o *WorkflowNode) SetCases(v []WorkflowConditionCase)`

SetCases sets Cases field to given value.

### HasCases

`func (o *WorkflowNode) HasCases() bool`

HasCases returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


