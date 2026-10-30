# WorkflowConditionTest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Field** | [**WorkflowFieldReference**](WorkflowFieldReference.md) |  | 
**Operator** | **string** | Text fields take is, isNot, contains, doesNotContain, startsWith, endsWith, isEmpty and isNotEmpty. Number fields take is, isNot, greaterThan, atLeast, lessThan, atMost, isEmpty and isNotEmpty. Yes/no fields take is and isNot.  | 
**Value** | Pointer to **interface{}** | What the field is compared with; not used by isEmpty and isNotEmpty. A text for a text field, a number for a number field, true or false for a yes/no field.  | [optional] 

## Methods

### NewWorkflowConditionTest

`func NewWorkflowConditionTest(field WorkflowFieldReference, operator string, ) *WorkflowConditionTest`

NewWorkflowConditionTest instantiates a new WorkflowConditionTest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowConditionTestWithDefaults

`func NewWorkflowConditionTestWithDefaults() *WorkflowConditionTest`

NewWorkflowConditionTestWithDefaults instantiates a new WorkflowConditionTest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetField

`func (o *WorkflowConditionTest) GetField() WorkflowFieldReference`

GetField returns the Field field if non-nil, zero value otherwise.

### GetFieldOk

`func (o *WorkflowConditionTest) GetFieldOk() (*WorkflowFieldReference, bool)`

GetFieldOk returns a tuple with the Field field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetField

`func (o *WorkflowConditionTest) SetField(v WorkflowFieldReference)`

SetField sets Field field to given value.


### GetOperator

`func (o *WorkflowConditionTest) GetOperator() string`

GetOperator returns the Operator field if non-nil, zero value otherwise.

### GetOperatorOk

`func (o *WorkflowConditionTest) GetOperatorOk() (*string, bool)`

GetOperatorOk returns a tuple with the Operator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperator

`func (o *WorkflowConditionTest) SetOperator(v string)`

SetOperator sets Operator field to given value.


### GetValue

`func (o *WorkflowConditionTest) GetValue() interface{}`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *WorkflowConditionTest) GetValueOk() (*interface{}, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *WorkflowConditionTest) SetValue(v interface{})`

SetValue sets Value field to given value.

### HasValue

`func (o *WorkflowConditionTest) HasValue() bool`

HasValue returns a boolean if a field has been set.

### SetValueNil

`func (o *WorkflowConditionTest) SetValueNil(b bool)`

 SetValueNil sets the value for Value to be an explicit nil

### UnsetValue
`func (o *WorkflowConditionTest) UnsetValue()`

UnsetValue ensures that no value is present for Value, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


