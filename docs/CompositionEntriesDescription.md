# CompositionEntriesDescription

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CompositionId** | **string** | The composition whose entries these are | 
**HasData** | **bool** | False when the composition keeps no entries of its own: its widget only shows content (it has no database), or nothing was set up in the database yet. That is not an error.  | 
**Tables** | [**[]CompositionEntryTable**](CompositionEntryTable.md) | The tables entries are kept in (up to 20) | 

## Methods

### NewCompositionEntriesDescription

`func NewCompositionEntriesDescription(compositionId string, hasData bool, tables []CompositionEntryTable, ) *CompositionEntriesDescription`

NewCompositionEntriesDescription instantiates a new CompositionEntriesDescription object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompositionEntriesDescriptionWithDefaults

`func NewCompositionEntriesDescriptionWithDefaults() *CompositionEntriesDescription`

NewCompositionEntriesDescriptionWithDefaults instantiates a new CompositionEntriesDescription object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompositionId

`func (o *CompositionEntriesDescription) GetCompositionId() string`

GetCompositionId returns the CompositionId field if non-nil, zero value otherwise.

### GetCompositionIdOk

`func (o *CompositionEntriesDescription) GetCompositionIdOk() (*string, bool)`

GetCompositionIdOk returns a tuple with the CompositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompositionId

`func (o *CompositionEntriesDescription) SetCompositionId(v string)`

SetCompositionId sets CompositionId field to given value.


### GetHasData

`func (o *CompositionEntriesDescription) GetHasData() bool`

GetHasData returns the HasData field if non-nil, zero value otherwise.

### GetHasDataOk

`func (o *CompositionEntriesDescription) GetHasDataOk() (*bool, bool)`

GetHasDataOk returns a tuple with the HasData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasData

`func (o *CompositionEntriesDescription) SetHasData(v bool)`

SetHasData sets HasData field to given value.


### GetTables

`func (o *CompositionEntriesDescription) GetTables() []CompositionEntryTable`

GetTables returns the Tables field if non-nil, zero value otherwise.

### GetTablesOk

`func (o *CompositionEntriesDescription) GetTablesOk() (*[]CompositionEntryTable, bool)`

GetTablesOk returns a tuple with the Tables field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTables

`func (o *CompositionEntriesDescription) SetTables(v []CompositionEntryTable)`

SetTables sets Tables field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


