# CompositionEntriesReading

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CompositionId** | **string** | The composition whose entries these are | 
**Table** | **string** | The table that was read | 
**TotalRows** | **int32** | How many entries the table holds in all. Not narrowed by &#x60;since&#x60;, &#x60;until&#x60; or a filter: only &#x60;aggregates&#x60; is.  | 
**Tallies** | [**[]CompositionEntryTally**](CompositionEntryTally.md) | How many entries have each value of the &#x60;groupBy&#x60; column, largest group first (up to 20 groups), over the whole table. &#x60;null&#x60; when no &#x60;groupBy&#x60; was asked for. For the groups of a selection (a time window, a &#x60;context&#x60; filter) or for more than 20 groups, ask for &#x60;aggregate&#x60;: &#x60;aggregates.tallies&#x60; holds up to 200 groups.  | 
**MoreGroups** | **bool** | True when the &#x60;groupBy&#x60; column has more than the 20 groups &#x60;tallies&#x60; lists. It speaks of &#x60;tallies&#x60; only: &#x60;aggregates.truncated&#x60; is the same signal for &#x60;aggregates&#x60; (200 groups).  | 
**Columns** | **[]string** | The name of each value of an entry in &#x60;rows&#x60;, in order, exactly as the database spells it (and as &#x60;describeCompositionEntries&#x60; lists it: &#x60;created_at&#x60; stays &#x60;created_at&#x60;). Empty when no entries were asked for, or the table has none.  | 
**Rows** | **[][]*interface{}** | The newest entries, newest first (up to 25). &#x60;null&#x60; when no entries were asked for. Each entry is a list of values in the order of &#x60;columns&#x60;. A value is text (cut to 200 characters), a number, a boolean or &#x60;null&#x60;.  | 
**MoreRows** | **bool** | True when the table holds more entries than &#x60;rows&#x60; lists | 
**Aggregates** | Pointer to [**CompositionEntryAggregatesBlock**](CompositionEntryAggregatesBlock.md) | Only present when the read asked for &#x60;aggregate&#x60;. Unlike &#x60;totalRows&#x60;, &#x60;tallies&#x60; and &#x60;rows&#x60;, it is narrowed by &#x60;since&#x60;, &#x60;until&#x60; and the &#x60;context&#x60; and column filters of the same call: it answers \&quot;the average rating this week\&quot; where &#x60;tallies&#x60; answer \&quot;how many of each rating, ever\&quot;.  | [optional] 

## Methods

### NewCompositionEntriesReading

`func NewCompositionEntriesReading(compositionId string, table string, totalRows int32, tallies []CompositionEntryTally, moreGroups bool, columns []string, rows [][]*interface{}, moreRows bool, ) *CompositionEntriesReading`

NewCompositionEntriesReading instantiates a new CompositionEntriesReading object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompositionEntriesReadingWithDefaults

`func NewCompositionEntriesReadingWithDefaults() *CompositionEntriesReading`

NewCompositionEntriesReadingWithDefaults instantiates a new CompositionEntriesReading object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompositionId

`func (o *CompositionEntriesReading) GetCompositionId() string`

GetCompositionId returns the CompositionId field if non-nil, zero value otherwise.

### GetCompositionIdOk

`func (o *CompositionEntriesReading) GetCompositionIdOk() (*string, bool)`

GetCompositionIdOk returns a tuple with the CompositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompositionId

`func (o *CompositionEntriesReading) SetCompositionId(v string)`

SetCompositionId sets CompositionId field to given value.


### GetTable

`func (o *CompositionEntriesReading) GetTable() string`

GetTable returns the Table field if non-nil, zero value otherwise.

### GetTableOk

`func (o *CompositionEntriesReading) GetTableOk() (*string, bool)`

GetTableOk returns a tuple with the Table field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTable

`func (o *CompositionEntriesReading) SetTable(v string)`

SetTable sets Table field to given value.


### GetTotalRows

`func (o *CompositionEntriesReading) GetTotalRows() int32`

GetTotalRows returns the TotalRows field if non-nil, zero value otherwise.

### GetTotalRowsOk

`func (o *CompositionEntriesReading) GetTotalRowsOk() (*int32, bool)`

GetTotalRowsOk returns a tuple with the TotalRows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalRows

`func (o *CompositionEntriesReading) SetTotalRows(v int32)`

SetTotalRows sets TotalRows field to given value.


### GetTallies

`func (o *CompositionEntriesReading) GetTallies() []CompositionEntryTally`

GetTallies returns the Tallies field if non-nil, zero value otherwise.

### GetTalliesOk

`func (o *CompositionEntriesReading) GetTalliesOk() (*[]CompositionEntryTally, bool)`

GetTalliesOk returns a tuple with the Tallies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTallies

`func (o *CompositionEntriesReading) SetTallies(v []CompositionEntryTally)`

SetTallies sets Tallies field to given value.


### SetTalliesNil

`func (o *CompositionEntriesReading) SetTalliesNil(b bool)`

 SetTalliesNil sets the value for Tallies to be an explicit nil

### UnsetTallies
`func (o *CompositionEntriesReading) UnsetTallies()`

UnsetTallies ensures that no value is present for Tallies, not even an explicit nil
### GetMoreGroups

`func (o *CompositionEntriesReading) GetMoreGroups() bool`

GetMoreGroups returns the MoreGroups field if non-nil, zero value otherwise.

### GetMoreGroupsOk

`func (o *CompositionEntriesReading) GetMoreGroupsOk() (*bool, bool)`

GetMoreGroupsOk returns a tuple with the MoreGroups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMoreGroups

`func (o *CompositionEntriesReading) SetMoreGroups(v bool)`

SetMoreGroups sets MoreGroups field to given value.


### GetColumns

`func (o *CompositionEntriesReading) GetColumns() []string`

GetColumns returns the Columns field if non-nil, zero value otherwise.

### GetColumnsOk

`func (o *CompositionEntriesReading) GetColumnsOk() (*[]string, bool)`

GetColumnsOk returns a tuple with the Columns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColumns

`func (o *CompositionEntriesReading) SetColumns(v []string)`

SetColumns sets Columns field to given value.


### GetRows

`func (o *CompositionEntriesReading) GetRows() [][]*interface{}`

GetRows returns the Rows field if non-nil, zero value otherwise.

### GetRowsOk

`func (o *CompositionEntriesReading) GetRowsOk() (*[][]*interface{}, bool)`

GetRowsOk returns a tuple with the Rows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRows

`func (o *CompositionEntriesReading) SetRows(v [][]*interface{})`

SetRows sets Rows field to given value.


### SetRowsNil

`func (o *CompositionEntriesReading) SetRowsNil(b bool)`

 SetRowsNil sets the value for Rows to be an explicit nil

### UnsetRows
`func (o *CompositionEntriesReading) UnsetRows()`

UnsetRows ensures that no value is present for Rows, not even an explicit nil
### GetMoreRows

`func (o *CompositionEntriesReading) GetMoreRows() bool`

GetMoreRows returns the MoreRows field if non-nil, zero value otherwise.

### GetMoreRowsOk

`func (o *CompositionEntriesReading) GetMoreRowsOk() (*bool, bool)`

GetMoreRowsOk returns a tuple with the MoreRows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMoreRows

`func (o *CompositionEntriesReading) SetMoreRows(v bool)`

SetMoreRows sets MoreRows field to given value.


### GetAggregates

`func (o *CompositionEntriesReading) GetAggregates() CompositionEntryAggregatesBlock`

GetAggregates returns the Aggregates field if non-nil, zero value otherwise.

### GetAggregatesOk

`func (o *CompositionEntriesReading) GetAggregatesOk() (*CompositionEntryAggregatesBlock, bool)`

GetAggregatesOk returns a tuple with the Aggregates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAggregates

`func (o *CompositionEntriesReading) SetAggregates(v CompositionEntryAggregatesBlock)`

SetAggregates sets Aggregates field to given value.

### HasAggregates

`func (o *CompositionEntriesReading) HasAggregates() bool`

HasAggregates returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


