# WorkflowCompositionOptionInputs

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | **bool** |  | 
**Reason** | Pointer to **NullableString** | Why Input added is not available. widget_keeps_no_data means the composition declares no table a visitor&#39;s entries are written to; widget_not_published means the widget has no published version.  | [optional] 
**Tables** | **[]string** | Every table a visitor&#39;s entries are written to, including one with no field a rule may read. | 
**Fields** | [**[]WorkflowCompositionField**](WorkflowCompositionField.md) | The columns of those tables a rule may read. Not offered are id and created_at, columns that are not text, a number or yes/no, and columns whose name says they hold a person&#39;s private details (an email, a phone number), because a value a rule reads is handed to the visitor&#39;s page.  | 

## Methods

### NewWorkflowCompositionOptionInputs

`func NewWorkflowCompositionOptionInputs(enabled bool, tables []string, fields []WorkflowCompositionField, ) *WorkflowCompositionOptionInputs`

NewWorkflowCompositionOptionInputs instantiates a new WorkflowCompositionOptionInputs object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowCompositionOptionInputsWithDefaults

`func NewWorkflowCompositionOptionInputsWithDefaults() *WorkflowCompositionOptionInputs`

NewWorkflowCompositionOptionInputsWithDefaults instantiates a new WorkflowCompositionOptionInputs object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *WorkflowCompositionOptionInputs) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *WorkflowCompositionOptionInputs) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *WorkflowCompositionOptionInputs) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetReason

`func (o *WorkflowCompositionOptionInputs) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *WorkflowCompositionOptionInputs) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *WorkflowCompositionOptionInputs) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *WorkflowCompositionOptionInputs) HasReason() bool`

HasReason returns a boolean if a field has been set.

### SetReasonNil

`func (o *WorkflowCompositionOptionInputs) SetReasonNil(b bool)`

 SetReasonNil sets the value for Reason to be an explicit nil

### UnsetReason
`func (o *WorkflowCompositionOptionInputs) UnsetReason()`

UnsetReason ensures that no value is present for Reason, not even an explicit nil
### GetTables

`func (o *WorkflowCompositionOptionInputs) GetTables() []string`

GetTables returns the Tables field if non-nil, zero value otherwise.

### GetTablesOk

`func (o *WorkflowCompositionOptionInputs) GetTablesOk() (*[]string, bool)`

GetTablesOk returns a tuple with the Tables field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTables

`func (o *WorkflowCompositionOptionInputs) SetTables(v []string)`

SetTables sets Tables field to given value.


### GetFields

`func (o *WorkflowCompositionOptionInputs) GetFields() []WorkflowCompositionField`

GetFields returns the Fields field if non-nil, zero value otherwise.

### GetFieldsOk

`func (o *WorkflowCompositionOptionInputs) GetFieldsOk() (*[]WorkflowCompositionField, bool)`

GetFieldsOk returns a tuple with the Fields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFields

`func (o *WorkflowCompositionOptionInputs) SetFields(v []WorkflowCompositionField)`

SetFields sets Fields field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


