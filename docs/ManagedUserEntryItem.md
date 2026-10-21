# ManagedUserEntryItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **NullableString** |  | 
**Values** | **map[string]interface{}** |  | 
**Context** | **map[string]interface{}** | The host context the entry was stored with: what the embedding page passed in, without the two keys of a signature (&#x60;widgetic_exp&#x60; and &#x60;widgetic_sig&#x60;), which are checked when the entry comes in and are never stored. | 
**CreatedAt** | **NullableTime** |  | 
**TruncatedColumns** | Pointer to **[]string** | The columns whose value was cut: a value longer than 20,000 characters is cut there (a JSON value is cut as text, so it comes back as a string and no longer as an object), and its column is named here. Absent when nothing was cut.  | [optional] 
**CompositionId** | **string** |  | 
**Table** | **string** |  | 

## Methods

### NewManagedUserEntryItem

`func NewManagedUserEntryItem(id NullableString, values map[string]interface{}, context map[string]interface{}, createdAt NullableTime, compositionId string, table string, ) *ManagedUserEntryItem`

NewManagedUserEntryItem instantiates a new ManagedUserEntryItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagedUserEntryItemWithDefaults

`func NewManagedUserEntryItemWithDefaults() *ManagedUserEntryItem`

NewManagedUserEntryItemWithDefaults instantiates a new ManagedUserEntryItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ManagedUserEntryItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManagedUserEntryItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManagedUserEntryItem) SetId(v string)`

SetId sets Id field to given value.


### SetIdNil

`func (o *ManagedUserEntryItem) SetIdNil(b bool)`

 SetIdNil sets the value for Id to be an explicit nil

### UnsetId
`func (o *ManagedUserEntryItem) UnsetId()`

UnsetId ensures that no value is present for Id, not even an explicit nil
### GetValues

`func (o *ManagedUserEntryItem) GetValues() map[string]interface{}`

GetValues returns the Values field if non-nil, zero value otherwise.

### GetValuesOk

`func (o *ManagedUserEntryItem) GetValuesOk() (*map[string]interface{}, bool)`

GetValuesOk returns a tuple with the Values field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValues

`func (o *ManagedUserEntryItem) SetValues(v map[string]interface{})`

SetValues sets Values field to given value.


### GetContext

`func (o *ManagedUserEntryItem) GetContext() map[string]interface{}`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *ManagedUserEntryItem) GetContextOk() (*map[string]interface{}, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *ManagedUserEntryItem) SetContext(v map[string]interface{})`

SetContext sets Context field to given value.


### SetContextNil

`func (o *ManagedUserEntryItem) SetContextNil(b bool)`

 SetContextNil sets the value for Context to be an explicit nil

### UnsetContext
`func (o *ManagedUserEntryItem) UnsetContext()`

UnsetContext ensures that no value is present for Context, not even an explicit nil
### GetCreatedAt

`func (o *ManagedUserEntryItem) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ManagedUserEntryItem) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ManagedUserEntryItem) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### SetCreatedAtNil

`func (o *ManagedUserEntryItem) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *ManagedUserEntryItem) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetTruncatedColumns

`func (o *ManagedUserEntryItem) GetTruncatedColumns() []string`

GetTruncatedColumns returns the TruncatedColumns field if non-nil, zero value otherwise.

### GetTruncatedColumnsOk

`func (o *ManagedUserEntryItem) GetTruncatedColumnsOk() (*[]string, bool)`

GetTruncatedColumnsOk returns a tuple with the TruncatedColumns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruncatedColumns

`func (o *ManagedUserEntryItem) SetTruncatedColumns(v []string)`

SetTruncatedColumns sets TruncatedColumns field to given value.

### HasTruncatedColumns

`func (o *ManagedUserEntryItem) HasTruncatedColumns() bool`

HasTruncatedColumns returns a boolean if a field has been set.

### GetCompositionId

`func (o *ManagedUserEntryItem) GetCompositionId() string`

GetCompositionId returns the CompositionId field if non-nil, zero value otherwise.

### GetCompositionIdOk

`func (o *ManagedUserEntryItem) GetCompositionIdOk() (*string, bool)`

GetCompositionIdOk returns a tuple with the CompositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompositionId

`func (o *ManagedUserEntryItem) SetCompositionId(v string)`

SetCompositionId sets CompositionId field to given value.


### GetTable

`func (o *ManagedUserEntryItem) GetTable() string`

GetTable returns the Table field if non-nil, zero value otherwise.

### GetTableOk

`func (o *ManagedUserEntryItem) GetTableOk() (*string, bool)`

GetTableOk returns a tuple with the Table field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTable

`func (o *ManagedUserEntryItem) SetTable(v string)`

SetTable sets Table field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


