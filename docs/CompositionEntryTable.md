# CompositionEntryTable

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | The table&#39;s name exactly as the database spells it. Pass it as &#x60;table&#x60; to read it. | 
**Columns** | [**[]CompositionEntryColumn**](CompositionEntryColumn.md) | The table&#39;s columns, in table order (up to 40) | 
**Rows** | **NullableInt32** | How many entries the table holds. &#x60;null&#x60; when they could not be counted, which is not zero. | 

## Methods

### NewCompositionEntryTable

`func NewCompositionEntryTable(name string, columns []CompositionEntryColumn, rows NullableInt32, ) *CompositionEntryTable`

NewCompositionEntryTable instantiates a new CompositionEntryTable object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompositionEntryTableWithDefaults

`func NewCompositionEntryTableWithDefaults() *CompositionEntryTable`

NewCompositionEntryTableWithDefaults instantiates a new CompositionEntryTable object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CompositionEntryTable) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CompositionEntryTable) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CompositionEntryTable) SetName(v string)`

SetName sets Name field to given value.


### GetColumns

`func (o *CompositionEntryTable) GetColumns() []CompositionEntryColumn`

GetColumns returns the Columns field if non-nil, zero value otherwise.

### GetColumnsOk

`func (o *CompositionEntryTable) GetColumnsOk() (*[]CompositionEntryColumn, bool)`

GetColumnsOk returns a tuple with the Columns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColumns

`func (o *CompositionEntryTable) SetColumns(v []CompositionEntryColumn)`

SetColumns sets Columns field to given value.


### GetRows

`func (o *CompositionEntryTable) GetRows() int32`

GetRows returns the Rows field if non-nil, zero value otherwise.

### GetRowsOk

`func (o *CompositionEntryTable) GetRowsOk() (*int32, bool)`

GetRowsOk returns a tuple with the Rows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRows

`func (o *CompositionEntryTable) SetRows(v int32)`

SetRows sets Rows field to given value.


### SetRowsNil

`func (o *CompositionEntryTable) SetRowsNil(b bool)`

 SetRowsNil sets the value for Rows to be an explicit nil

### UnsetRows
`func (o *CompositionEntryTable) UnsetRows()`

UnsetRows ensures that no value is present for Rows, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


