# CompositionEntryAggregatesBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Column** | **string** | The numeric column &#x60;avg&#x60;, &#x60;min&#x60;, &#x60;max&#x60; and &#x60;sum&#x60; were computed over. An empty text when only &#x60;count&#x60; was asked for.  | 
**Tallies** | [**[]CompositionEntryAggregateTally**](CompositionEntryAggregateTally.md) | One tally per value of &#x60;groupBy&#x60;, in the order of that column (a number as a number, &#x60;null&#x60; last), up to 200 groups; or ONE tally for the whole selection when no &#x60;groupBy&#x60; was asked for. Empty when &#x60;groupBy&#x60; was asked for and no entry matched.  | 
**Truncated** | Pointer to **bool** | True when more than 200 groups matched, so &#x60;tallies&#x60; lists the first 200 in that order. Absent otherwise. (Not to be mixed up with &#x60;moreGroups&#x60; on the reading, which is about the plain &#x60;tallies&#x60; of the whole table: those are 20 groups, largest first.)  | [optional] 

## Methods

### NewCompositionEntryAggregatesBlock

`func NewCompositionEntryAggregatesBlock(column string, tallies []CompositionEntryAggregateTally, ) *CompositionEntryAggregatesBlock`

NewCompositionEntryAggregatesBlock instantiates a new CompositionEntryAggregatesBlock object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompositionEntryAggregatesBlockWithDefaults

`func NewCompositionEntryAggregatesBlockWithDefaults() *CompositionEntryAggregatesBlock`

NewCompositionEntryAggregatesBlockWithDefaults instantiates a new CompositionEntryAggregatesBlock object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetColumn

`func (o *CompositionEntryAggregatesBlock) GetColumn() string`

GetColumn returns the Column field if non-nil, zero value otherwise.

### GetColumnOk

`func (o *CompositionEntryAggregatesBlock) GetColumnOk() (*string, bool)`

GetColumnOk returns a tuple with the Column field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColumn

`func (o *CompositionEntryAggregatesBlock) SetColumn(v string)`

SetColumn sets Column field to given value.


### GetTallies

`func (o *CompositionEntryAggregatesBlock) GetTallies() []CompositionEntryAggregateTally`

GetTallies returns the Tallies field if non-nil, zero value otherwise.

### GetTalliesOk

`func (o *CompositionEntryAggregatesBlock) GetTalliesOk() (*[]CompositionEntryAggregateTally, bool)`

GetTalliesOk returns a tuple with the Tallies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTallies

`func (o *CompositionEntryAggregatesBlock) SetTallies(v []CompositionEntryAggregateTally)`

SetTallies sets Tallies field to given value.


### GetTruncated

`func (o *CompositionEntryAggregatesBlock) GetTruncated() bool`

GetTruncated returns the Truncated field if non-nil, zero value otherwise.

### GetTruncatedOk

`func (o *CompositionEntryAggregatesBlock) GetTruncatedOk() (*bool, bool)`

GetTruncatedOk returns a tuple with the Truncated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruncated

`func (o *CompositionEntryAggregatesBlock) SetTruncated(v bool)`

SetTruncated sets Truncated field to given value.

### HasTruncated

`func (o *CompositionEntryAggregatesBlock) HasTruncated() bool`

HasTruncated returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


