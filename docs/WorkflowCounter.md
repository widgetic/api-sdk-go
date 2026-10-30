# WorkflowCounter

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The block or connection counted. | 
**Total** | **int32** |  | 

## Methods

### NewWorkflowCounter

`func NewWorkflowCounter(id string, total int32, ) *WorkflowCounter`

NewWorkflowCounter instantiates a new WorkflowCounter object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowCounterWithDefaults

`func NewWorkflowCounterWithDefaults() *WorkflowCounter`

NewWorkflowCounterWithDefaults instantiates a new WorkflowCounter object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *WorkflowCounter) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WorkflowCounter) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WorkflowCounter) SetId(v string)`

SetId sets Id field to given value.


### GetTotal

`func (o *WorkflowCounter) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *WorkflowCounter) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *WorkflowCounter) SetTotal(v int32)`

SetTotal sets Total field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


