# CompositionEntryAggregateTally

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Group** | Pointer to **NullableString** | The value of the &#x60;groupBy&#x60; column, as text (a number is &#x60;\&quot;5\&quot;&#x60;); &#x60;null&#x60; groups the entries that left it empty. Absent when no &#x60;groupBy&#x60; was asked for.  | [optional] 
**Count** | Pointer to **int32** | How many entries are in the group (or in the selection) | [optional] 
**Avg** | Pointer to **NullableFloat32** | The average of the numeric &#x60;column&#x60;, rounded to 4 decimals. &#x60;null&#x60; when no entry matched: there is no average of nothing, and it is not 0.  | [optional] 
**Min** | Pointer to **NullableFloat32** | The smallest value of the numeric &#x60;column&#x60;. &#x60;null&#x60; when no entry matched. | [optional] 
**Max** | Pointer to **NullableFloat32** | The largest value of the numeric &#x60;column&#x60;. &#x60;null&#x60; when no entry matched. | [optional] 
**Sum** | Pointer to **NullableFloat32** | The sum of the numeric &#x60;column&#x60;. &#x60;null&#x60; when no entry matched. | [optional] 

## Methods

### NewCompositionEntryAggregateTally

`func NewCompositionEntryAggregateTally() *CompositionEntryAggregateTally`

NewCompositionEntryAggregateTally instantiates a new CompositionEntryAggregateTally object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompositionEntryAggregateTallyWithDefaults

`func NewCompositionEntryAggregateTallyWithDefaults() *CompositionEntryAggregateTally`

NewCompositionEntryAggregateTallyWithDefaults instantiates a new CompositionEntryAggregateTally object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGroup

`func (o *CompositionEntryAggregateTally) GetGroup() string`

GetGroup returns the Group field if non-nil, zero value otherwise.

### GetGroupOk

`func (o *CompositionEntryAggregateTally) GetGroupOk() (*string, bool)`

GetGroupOk returns a tuple with the Group field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroup

`func (o *CompositionEntryAggregateTally) SetGroup(v string)`

SetGroup sets Group field to given value.

### HasGroup

`func (o *CompositionEntryAggregateTally) HasGroup() bool`

HasGroup returns a boolean if a field has been set.

### SetGroupNil

`func (o *CompositionEntryAggregateTally) SetGroupNil(b bool)`

 SetGroupNil sets the value for Group to be an explicit nil

### UnsetGroup
`func (o *CompositionEntryAggregateTally) UnsetGroup()`

UnsetGroup ensures that no value is present for Group, not even an explicit nil
### GetCount

`func (o *CompositionEntryAggregateTally) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *CompositionEntryAggregateTally) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *CompositionEntryAggregateTally) SetCount(v int32)`

SetCount sets Count field to given value.

### HasCount

`func (o *CompositionEntryAggregateTally) HasCount() bool`

HasCount returns a boolean if a field has been set.

### GetAvg

`func (o *CompositionEntryAggregateTally) GetAvg() float32`

GetAvg returns the Avg field if non-nil, zero value otherwise.

### GetAvgOk

`func (o *CompositionEntryAggregateTally) GetAvgOk() (*float32, bool)`

GetAvgOk returns a tuple with the Avg field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvg

`func (o *CompositionEntryAggregateTally) SetAvg(v float32)`

SetAvg sets Avg field to given value.

### HasAvg

`func (o *CompositionEntryAggregateTally) HasAvg() bool`

HasAvg returns a boolean if a field has been set.

### SetAvgNil

`func (o *CompositionEntryAggregateTally) SetAvgNil(b bool)`

 SetAvgNil sets the value for Avg to be an explicit nil

### UnsetAvg
`func (o *CompositionEntryAggregateTally) UnsetAvg()`

UnsetAvg ensures that no value is present for Avg, not even an explicit nil
### GetMin

`func (o *CompositionEntryAggregateTally) GetMin() float32`

GetMin returns the Min field if non-nil, zero value otherwise.

### GetMinOk

`func (o *CompositionEntryAggregateTally) GetMinOk() (*float32, bool)`

GetMinOk returns a tuple with the Min field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMin

`func (o *CompositionEntryAggregateTally) SetMin(v float32)`

SetMin sets Min field to given value.

### HasMin

`func (o *CompositionEntryAggregateTally) HasMin() bool`

HasMin returns a boolean if a field has been set.

### SetMinNil

`func (o *CompositionEntryAggregateTally) SetMinNil(b bool)`

 SetMinNil sets the value for Min to be an explicit nil

### UnsetMin
`func (o *CompositionEntryAggregateTally) UnsetMin()`

UnsetMin ensures that no value is present for Min, not even an explicit nil
### GetMax

`func (o *CompositionEntryAggregateTally) GetMax() float32`

GetMax returns the Max field if non-nil, zero value otherwise.

### GetMaxOk

`func (o *CompositionEntryAggregateTally) GetMaxOk() (*float32, bool)`

GetMaxOk returns a tuple with the Max field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMax

`func (o *CompositionEntryAggregateTally) SetMax(v float32)`

SetMax sets Max field to given value.

### HasMax

`func (o *CompositionEntryAggregateTally) HasMax() bool`

HasMax returns a boolean if a field has been set.

### SetMaxNil

`func (o *CompositionEntryAggregateTally) SetMaxNil(b bool)`

 SetMaxNil sets the value for Max to be an explicit nil

### UnsetMax
`func (o *CompositionEntryAggregateTally) UnsetMax()`

UnsetMax ensures that no value is present for Max, not even an explicit nil
### GetSum

`func (o *CompositionEntryAggregateTally) GetSum() float32`

GetSum returns the Sum field if non-nil, zero value otherwise.

### GetSumOk

`func (o *CompositionEntryAggregateTally) GetSumOk() (*float32, bool)`

GetSumOk returns a tuple with the Sum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSum

`func (o *CompositionEntryAggregateTally) SetSum(v float32)`

SetSum sets Sum field to given value.

### HasSum

`func (o *CompositionEntryAggregateTally) HasSum() bool`

HasSum returns a boolean if a field has been set.

### SetSumNil

`func (o *CompositionEntryAggregateTally) SetSumNil(b bool)`

 SetSumNil sets the value for Sum to be an explicit nil

### UnsetSum
`func (o *CompositionEntryAggregateTally) UnsetSum()`

UnsetSum ensures that no value is present for Sum, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


