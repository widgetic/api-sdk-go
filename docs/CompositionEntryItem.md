# CompositionEntryItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **NullableString** |  | 
**Values** | **map[string]interface{}** |  | 
**Context** | **map[string]interface{}** | The host context the entry was stored with: what the embedding page passed in, without the two keys of a signature (&#x60;widgetic_exp&#x60; and &#x60;widgetic_sig&#x60;), which are checked when the entry comes in and are never stored. | 
**CreatedAt** | **NullableTime** |  | 
**TruncatedColumns** | Pointer to **[]string** | The columns whose value was cut: a value longer than 20,000 characters is cut there (a JSON value is cut as text, so it comes back as a string and no longer as an object), and its column is named here. Absent when nothing was cut.  | [optional] 

## Methods

### NewCompositionEntryItem

`func NewCompositionEntryItem(id NullableString, values map[string]interface{}, context map[string]interface{}, createdAt NullableTime, ) *CompositionEntryItem`

NewCompositionEntryItem instantiates a new CompositionEntryItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompositionEntryItemWithDefaults

`func NewCompositionEntryItemWithDefaults() *CompositionEntryItem`

NewCompositionEntryItemWithDefaults instantiates a new CompositionEntryItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CompositionEntryItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CompositionEntryItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CompositionEntryItem) SetId(v string)`

SetId sets Id field to given value.


### SetIdNil

`func (o *CompositionEntryItem) SetIdNil(b bool)`

 SetIdNil sets the value for Id to be an explicit nil

### UnsetId
`func (o *CompositionEntryItem) UnsetId()`

UnsetId ensures that no value is present for Id, not even an explicit nil
### GetValues

`func (o *CompositionEntryItem) GetValues() map[string]interface{}`

GetValues returns the Values field if non-nil, zero value otherwise.

### GetValuesOk

`func (o *CompositionEntryItem) GetValuesOk() (*map[string]interface{}, bool)`

GetValuesOk returns a tuple with the Values field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValues

`func (o *CompositionEntryItem) SetValues(v map[string]interface{})`

SetValues sets Values field to given value.


### GetContext

`func (o *CompositionEntryItem) GetContext() map[string]interface{}`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *CompositionEntryItem) GetContextOk() (*map[string]interface{}, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *CompositionEntryItem) SetContext(v map[string]interface{})`

SetContext sets Context field to given value.


### SetContextNil

`func (o *CompositionEntryItem) SetContextNil(b bool)`

 SetContextNil sets the value for Context to be an explicit nil

### UnsetContext
`func (o *CompositionEntryItem) UnsetContext()`

UnsetContext ensures that no value is present for Context, not even an explicit nil
### GetCreatedAt

`func (o *CompositionEntryItem) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CompositionEntryItem) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CompositionEntryItem) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### SetCreatedAtNil

`func (o *CompositionEntryItem) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *CompositionEntryItem) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetTruncatedColumns

`func (o *CompositionEntryItem) GetTruncatedColumns() []string`

GetTruncatedColumns returns the TruncatedColumns field if non-nil, zero value otherwise.

### GetTruncatedColumnsOk

`func (o *CompositionEntryItem) GetTruncatedColumnsOk() (*[]string, bool)`

GetTruncatedColumnsOk returns a tuple with the TruncatedColumns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruncatedColumns

`func (o *CompositionEntryItem) SetTruncatedColumns(v []string)`

SetTruncatedColumns sets TruncatedColumns field to given value.

### HasTruncatedColumns

`func (o *CompositionEntryItem) HasTruncatedColumns() bool`

HasTruncatedColumns returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


