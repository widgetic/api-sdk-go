# CompositionEntryItemsMeta

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NextCursor** | **NullableString** | Pass it as &#x60;cursor&#x60; to get the next page. &#x60;null&#x60; on the last page, and for a table that cannot be paged (see &#x60;paging&#x60;).  | 
**Total** | **int32** | How many entries match the filters and the &#x60;since&#x60; / &#x60;until&#x60; window, over all pages and not only this one.  | 
**Paging** | Pointer to **string** | Present, as &#x60;unavailable&#x60;, when the table cannot be paged: it has a time column but no id column to tell two entries of the same instant apart, or it has no time column and no id column that can be paged on. The answer is one page only, and &#x60;nextCursor&#x60; stays &#x60;null&#x60; even when &#x60;total&#x60; is larger than the page.  | [optional] 

## Methods

### NewCompositionEntryItemsMeta

`func NewCompositionEntryItemsMeta(nextCursor NullableString, total int32, ) *CompositionEntryItemsMeta`

NewCompositionEntryItemsMeta instantiates a new CompositionEntryItemsMeta object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompositionEntryItemsMetaWithDefaults

`func NewCompositionEntryItemsMetaWithDefaults() *CompositionEntryItemsMeta`

NewCompositionEntryItemsMetaWithDefaults instantiates a new CompositionEntryItemsMeta object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNextCursor

`func (o *CompositionEntryItemsMeta) GetNextCursor() string`

GetNextCursor returns the NextCursor field if non-nil, zero value otherwise.

### GetNextCursorOk

`func (o *CompositionEntryItemsMeta) GetNextCursorOk() (*string, bool)`

GetNextCursorOk returns a tuple with the NextCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCursor

`func (o *CompositionEntryItemsMeta) SetNextCursor(v string)`

SetNextCursor sets NextCursor field to given value.


### SetNextCursorNil

`func (o *CompositionEntryItemsMeta) SetNextCursorNil(b bool)`

 SetNextCursorNil sets the value for NextCursor to be an explicit nil

### UnsetNextCursor
`func (o *CompositionEntryItemsMeta) UnsetNextCursor()`

UnsetNextCursor ensures that no value is present for NextCursor, not even an explicit nil
### GetTotal

`func (o *CompositionEntryItemsMeta) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *CompositionEntryItemsMeta) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *CompositionEntryItemsMeta) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetPaging

`func (o *CompositionEntryItemsMeta) GetPaging() string`

GetPaging returns the Paging field if non-nil, zero value otherwise.

### GetPagingOk

`func (o *CompositionEntryItemsMeta) GetPagingOk() (*string, bool)`

GetPagingOk returns a tuple with the Paging field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaging

`func (o *CompositionEntryItemsMeta) SetPaging(v string)`

SetPaging sets Paging field to given value.

### HasPaging

`func (o *CompositionEntryItemsMeta) HasPaging() bool`

HasPaging returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


