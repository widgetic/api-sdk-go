# WorkflowConditionCase

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The output port of the rule. &#x60;default&#x60; is reserved for the Default output. | 
**Label** | Pointer to **string** |  | [optional] 
**Match** | **string** | &#x60;all&#x60; - every comparison must hold; &#x60;any&#x60; - one is enough. | 
**Tests** | [**[]WorkflowConditionTest**](WorkflowConditionTest.md) |  | 

## Methods

### NewWorkflowConditionCase

`func NewWorkflowConditionCase(id string, match string, tests []WorkflowConditionTest, ) *WorkflowConditionCase`

NewWorkflowConditionCase instantiates a new WorkflowConditionCase object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowConditionCaseWithDefaults

`func NewWorkflowConditionCaseWithDefaults() *WorkflowConditionCase`

NewWorkflowConditionCaseWithDefaults instantiates a new WorkflowConditionCase object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *WorkflowConditionCase) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WorkflowConditionCase) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WorkflowConditionCase) SetId(v string)`

SetId sets Id field to given value.


### GetLabel

`func (o *WorkflowConditionCase) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *WorkflowConditionCase) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *WorkflowConditionCase) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *WorkflowConditionCase) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### GetMatch

`func (o *WorkflowConditionCase) GetMatch() string`

GetMatch returns the Match field if non-nil, zero value otherwise.

### GetMatchOk

`func (o *WorkflowConditionCase) GetMatchOk() (*string, bool)`

GetMatchOk returns a tuple with the Match field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatch

`func (o *WorkflowConditionCase) SetMatch(v string)`

SetMatch sets Match field to given value.


### GetTests

`func (o *WorkflowConditionCase) GetTests() []WorkflowConditionTest`

GetTests returns the Tests field if non-nil, zero value otherwise.

### GetTestsOk

`func (o *WorkflowConditionCase) GetTestsOk() (*[]WorkflowConditionTest, bool)`

GetTestsOk returns a tuple with the Tests field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTests

`func (o *WorkflowConditionCase) SetTests(v []WorkflowConditionTest)`

SetTests sets Tests field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


