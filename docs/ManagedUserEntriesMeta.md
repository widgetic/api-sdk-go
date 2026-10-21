# ManagedUserEntriesMeta

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NextCursor** | **NullableString** |  | 
**Total** | **int32** |  | 
**CompositionsConsidered** | **int32** |  | 
**MoreCompositions** | **bool** |  | 
**Partial** | Pointer to **bool** |  | [optional] 

## Methods

### NewManagedUserEntriesMeta

`func NewManagedUserEntriesMeta(nextCursor NullableString, total int32, compositionsConsidered int32, moreCompositions bool, ) *ManagedUserEntriesMeta`

NewManagedUserEntriesMeta instantiates a new ManagedUserEntriesMeta object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagedUserEntriesMetaWithDefaults

`func NewManagedUserEntriesMetaWithDefaults() *ManagedUserEntriesMeta`

NewManagedUserEntriesMetaWithDefaults instantiates a new ManagedUserEntriesMeta object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNextCursor

`func (o *ManagedUserEntriesMeta) GetNextCursor() string`

GetNextCursor returns the NextCursor field if non-nil, zero value otherwise.

### GetNextCursorOk

`func (o *ManagedUserEntriesMeta) GetNextCursorOk() (*string, bool)`

GetNextCursorOk returns a tuple with the NextCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCursor

`func (o *ManagedUserEntriesMeta) SetNextCursor(v string)`

SetNextCursor sets NextCursor field to given value.


### SetNextCursorNil

`func (o *ManagedUserEntriesMeta) SetNextCursorNil(b bool)`

 SetNextCursorNil sets the value for NextCursor to be an explicit nil

### UnsetNextCursor
`func (o *ManagedUserEntriesMeta) UnsetNextCursor()`

UnsetNextCursor ensures that no value is present for NextCursor, not even an explicit nil
### GetTotal

`func (o *ManagedUserEntriesMeta) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ManagedUserEntriesMeta) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ManagedUserEntriesMeta) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetCompositionsConsidered

`func (o *ManagedUserEntriesMeta) GetCompositionsConsidered() int32`

GetCompositionsConsidered returns the CompositionsConsidered field if non-nil, zero value otherwise.

### GetCompositionsConsideredOk

`func (o *ManagedUserEntriesMeta) GetCompositionsConsideredOk() (*int32, bool)`

GetCompositionsConsideredOk returns a tuple with the CompositionsConsidered field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompositionsConsidered

`func (o *ManagedUserEntriesMeta) SetCompositionsConsidered(v int32)`

SetCompositionsConsidered sets CompositionsConsidered field to given value.


### GetMoreCompositions

`func (o *ManagedUserEntriesMeta) GetMoreCompositions() bool`

GetMoreCompositions returns the MoreCompositions field if non-nil, zero value otherwise.

### GetMoreCompositionsOk

`func (o *ManagedUserEntriesMeta) GetMoreCompositionsOk() (*bool, bool)`

GetMoreCompositionsOk returns a tuple with the MoreCompositions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMoreCompositions

`func (o *ManagedUserEntriesMeta) SetMoreCompositions(v bool)`

SetMoreCompositions sets MoreCompositions field to given value.


### GetPartial

`func (o *ManagedUserEntriesMeta) GetPartial() bool`

GetPartial returns the Partial field if non-nil, zero value otherwise.

### GetPartialOk

`func (o *ManagedUserEntriesMeta) GetPartialOk() (*bool, bool)`

GetPartialOk returns a tuple with the Partial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartial

`func (o *ManagedUserEntriesMeta) SetPartial(v bool)`

SetPartial sets Partial field to given value.

### HasPartial

`func (o *ManagedUserEntriesMeta) HasPartial() bool`

HasPartial returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


