# WorkflowTrigger

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Kind** | **string** |  | 
**Table** | Pointer to **string** |  | [optional] 
**ActionId** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Values** | Pointer to [**[]WorkflowTriggerValuesInner**](WorkflowTriggerValuesInner.md) |  | [optional] 
**Schedule** | Pointer to [**WorkflowSchedule**](WorkflowSchedule.md) |  | [optional] 

## Methods

### NewWorkflowTrigger

`func NewWorkflowTrigger(kind string, ) *WorkflowTrigger`

NewWorkflowTrigger instantiates a new WorkflowTrigger object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowTriggerWithDefaults

`func NewWorkflowTriggerWithDefaults() *WorkflowTrigger`

NewWorkflowTriggerWithDefaults instantiates a new WorkflowTrigger object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKind

`func (o *WorkflowTrigger) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *WorkflowTrigger) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *WorkflowTrigger) SetKind(v string)`

SetKind sets Kind field to given value.


### GetTable

`func (o *WorkflowTrigger) GetTable() string`

GetTable returns the Table field if non-nil, zero value otherwise.

### GetTableOk

`func (o *WorkflowTrigger) GetTableOk() (*string, bool)`

GetTableOk returns a tuple with the Table field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTable

`func (o *WorkflowTrigger) SetTable(v string)`

SetTable sets Table field to given value.

### HasTable

`func (o *WorkflowTrigger) HasTable() bool`

HasTable returns a boolean if a field has been set.

### GetActionId

`func (o *WorkflowTrigger) GetActionId() string`

GetActionId returns the ActionId field if non-nil, zero value otherwise.

### GetActionIdOk

`func (o *WorkflowTrigger) GetActionIdOk() (*string, bool)`

GetActionIdOk returns a tuple with the ActionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActionId

`func (o *WorkflowTrigger) SetActionId(v string)`

SetActionId sets ActionId field to given value.

### HasActionId

`func (o *WorkflowTrigger) HasActionId() bool`

HasActionId returns a boolean if a field has been set.

### GetName

`func (o *WorkflowTrigger) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *WorkflowTrigger) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *WorkflowTrigger) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *WorkflowTrigger) HasName() bool`

HasName returns a boolean if a field has been set.

### GetValues

`func (o *WorkflowTrigger) GetValues() []WorkflowTriggerValuesInner`

GetValues returns the Values field if non-nil, zero value otherwise.

### GetValuesOk

`func (o *WorkflowTrigger) GetValuesOk() (*[]WorkflowTriggerValuesInner, bool)`

GetValuesOk returns a tuple with the Values field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValues

`func (o *WorkflowTrigger) SetValues(v []WorkflowTriggerValuesInner)`

SetValues sets Values field to given value.

### HasValues

`func (o *WorkflowTrigger) HasValues() bool`

HasValues returns a boolean if a field has been set.

### GetSchedule

`func (o *WorkflowTrigger) GetSchedule() WorkflowSchedule`

GetSchedule returns the Schedule field if non-nil, zero value otherwise.

### GetScheduleOk

`func (o *WorkflowTrigger) GetScheduleOk() (*WorkflowSchedule, bool)`

GetScheduleOk returns a tuple with the Schedule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchedule

`func (o *WorkflowTrigger) SetSchedule(v WorkflowSchedule)`

SetSchedule sets Schedule field to given value.

### HasSchedule

`func (o *WorkflowTrigger) HasSchedule() bool`

HasSchedule returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


