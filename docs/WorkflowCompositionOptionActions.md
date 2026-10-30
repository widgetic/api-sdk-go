# WorkflowCompositionOptionActions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | **bool** |  | 
**Reason** | Pointer to **NullableString** | Why Action in the widget is not available. widget_reports_no_actions means the published widget declares no goals; widget_not_published means the widget has no published version.  | [optional] 
**Items** | [**[]WorkflowCompositionAction**](WorkflowCompositionAction.md) |  | 

## Methods

### NewWorkflowCompositionOptionActions

`func NewWorkflowCompositionOptionActions(enabled bool, items []WorkflowCompositionAction, ) *WorkflowCompositionOptionActions`

NewWorkflowCompositionOptionActions instantiates a new WorkflowCompositionOptionActions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowCompositionOptionActionsWithDefaults

`func NewWorkflowCompositionOptionActionsWithDefaults() *WorkflowCompositionOptionActions`

NewWorkflowCompositionOptionActionsWithDefaults instantiates a new WorkflowCompositionOptionActions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *WorkflowCompositionOptionActions) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *WorkflowCompositionOptionActions) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *WorkflowCompositionOptionActions) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetReason

`func (o *WorkflowCompositionOptionActions) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *WorkflowCompositionOptionActions) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *WorkflowCompositionOptionActions) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *WorkflowCompositionOptionActions) HasReason() bool`

HasReason returns a boolean if a field has been set.

### SetReasonNil

`func (o *WorkflowCompositionOptionActions) SetReasonNil(b bool)`

 SetReasonNil sets the value for Reason to be an explicit nil

### UnsetReason
`func (o *WorkflowCompositionOptionActions) UnsetReason()`

UnsetReason ensures that no value is present for Reason, not even an explicit nil
### GetItems

`func (o *WorkflowCompositionOptionActions) GetItems() []WorkflowCompositionAction`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *WorkflowCompositionOptionActions) GetItemsOk() (*[]WorkflowCompositionAction, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *WorkflowCompositionOptionActions) SetItems(v []WorkflowCompositionAction)`

SetItems sets Items field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


