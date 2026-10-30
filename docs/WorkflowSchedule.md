# WorkflowSchedule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Mode** | **string** |  | 
**Amount** | Pointer to **float32** | How long to wait (mode &#x60;after&#x60;). | [optional] 
**Unit** | Pointer to **string** | The unit of &#x60;amount&#x60; (mode &#x60;after&#x60;). | [optional] 
**At** | Pointer to **time.Time** | The moment to fire at, as an ISO time in UTC (mode &#x60;at&#x60;). | [optional] 

## Methods

### NewWorkflowSchedule

`func NewWorkflowSchedule(mode string, ) *WorkflowSchedule`

NewWorkflowSchedule instantiates a new WorkflowSchedule object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowScheduleWithDefaults

`func NewWorkflowScheduleWithDefaults() *WorkflowSchedule`

NewWorkflowScheduleWithDefaults instantiates a new WorkflowSchedule object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMode

`func (o *WorkflowSchedule) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *WorkflowSchedule) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *WorkflowSchedule) SetMode(v string)`

SetMode sets Mode field to given value.


### GetAmount

`func (o *WorkflowSchedule) GetAmount() float32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *WorkflowSchedule) GetAmountOk() (*float32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *WorkflowSchedule) SetAmount(v float32)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *WorkflowSchedule) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetUnit

`func (o *WorkflowSchedule) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *WorkflowSchedule) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *WorkflowSchedule) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *WorkflowSchedule) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetAt

`func (o *WorkflowSchedule) GetAt() time.Time`

GetAt returns the At field if non-nil, zero value otherwise.

### GetAtOk

`func (o *WorkflowSchedule) GetAtOk() (*time.Time, bool)`

GetAtOk returns a tuple with the At field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAt

`func (o *WorkflowSchedule) SetAt(v time.Time)`

SetAt sets At field to given value.

### HasAt

`func (o *WorkflowSchedule) HasAt() bool`

HasAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


