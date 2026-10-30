# WorkflowCompositionAction

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | What the trigger stores to say which action it waits for. It is the goal, and the element when the goal names one (clicks, or clicks@.buy-now).  | 
**Metric** | **string** | The goal&#39;s metric (clicks, submissions or plays). | 
**Label** | **string** |  | 
**Selector** | Pointer to **NullableString** | The element the goal is about, when it names one. | [optional] 

## Methods

### NewWorkflowCompositionAction

`func NewWorkflowCompositionAction(id string, metric string, label string, ) *WorkflowCompositionAction`

NewWorkflowCompositionAction instantiates a new WorkflowCompositionAction object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowCompositionActionWithDefaults

`func NewWorkflowCompositionActionWithDefaults() *WorkflowCompositionAction`

NewWorkflowCompositionActionWithDefaults instantiates a new WorkflowCompositionAction object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *WorkflowCompositionAction) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WorkflowCompositionAction) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WorkflowCompositionAction) SetId(v string)`

SetId sets Id field to given value.


### GetMetric

`func (o *WorkflowCompositionAction) GetMetric() string`

GetMetric returns the Metric field if non-nil, zero value otherwise.

### GetMetricOk

`func (o *WorkflowCompositionAction) GetMetricOk() (*string, bool)`

GetMetricOk returns a tuple with the Metric field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetric

`func (o *WorkflowCompositionAction) SetMetric(v string)`

SetMetric sets Metric field to given value.


### GetLabel

`func (o *WorkflowCompositionAction) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *WorkflowCompositionAction) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *WorkflowCompositionAction) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetSelector

`func (o *WorkflowCompositionAction) GetSelector() string`

GetSelector returns the Selector field if non-nil, zero value otherwise.

### GetSelectorOk

`func (o *WorkflowCompositionAction) GetSelectorOk() (*string, bool)`

GetSelectorOk returns a tuple with the Selector field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelector

`func (o *WorkflowCompositionAction) SetSelector(v string)`

SetSelector sets Selector field to given value.

### HasSelector

`func (o *WorkflowCompositionAction) HasSelector() bool`

HasSelector returns a boolean if a field has been set.

### SetSelectorNil

`func (o *WorkflowCompositionAction) SetSelectorNil(b bool)`

 SetSelectorNil sets the value for Selector to be an explicit nil

### UnsetSelector
`func (o *WorkflowCompositionAction) UnsetSelector()`

UnsetSelector ensures that no value is present for Selector, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


