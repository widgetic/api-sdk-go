# ResponseMeta

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Page** | Pointer to **int32** | The page that was read, counting from 1. | [optional] 
**Size** | Pointer to **int32** | How many items one page holds. | [optional] 
**Total** | Pointer to **int32** | How many items the whole list has. | [optional] 
**Limit** | Pointer to **int32** | The same as &#x60;size&#x60;. | [optional] 
**Offset** | Pointer to **int32** | How many items come before this page. | [optional] 
**HasNextPage** | Pointer to **bool** |  | [optional] 
**HasPreviousPage** | Pointer to **bool** |  | [optional] 
**NextCursor** | Pointer to **NullableString** | Pass this as &#x60;cursor&#x60; to read the next page of a list that is read by cursor. &#x60;null&#x60; on the last page. | [optional] 
**Warnings** | Pointer to **[]string** | Things the call did not do, though it succeeded (for example a table that could not be created just now). | [optional] 

## Methods

### NewResponseMeta

`func NewResponseMeta() *ResponseMeta`

NewResponseMeta instantiates a new ResponseMeta object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResponseMetaWithDefaults

`func NewResponseMetaWithDefaults() *ResponseMeta`

NewResponseMetaWithDefaults instantiates a new ResponseMeta object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPage

`func (o *ResponseMeta) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *ResponseMeta) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *ResponseMeta) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *ResponseMeta) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetSize

`func (o *ResponseMeta) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *ResponseMeta) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *ResponseMeta) SetSize(v int32)`

SetSize sets Size field to given value.

### HasSize

`func (o *ResponseMeta) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetTotal

`func (o *ResponseMeta) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ResponseMeta) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ResponseMeta) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *ResponseMeta) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetLimit

`func (o *ResponseMeta) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *ResponseMeta) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *ResponseMeta) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *ResponseMeta) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### GetOffset

`func (o *ResponseMeta) GetOffset() int32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *ResponseMeta) GetOffsetOk() (*int32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *ResponseMeta) SetOffset(v int32)`

SetOffset sets Offset field to given value.

### HasOffset

`func (o *ResponseMeta) HasOffset() bool`

HasOffset returns a boolean if a field has been set.

### GetHasNextPage

`func (o *ResponseMeta) GetHasNextPage() bool`

GetHasNextPage returns the HasNextPage field if non-nil, zero value otherwise.

### GetHasNextPageOk

`func (o *ResponseMeta) GetHasNextPageOk() (*bool, bool)`

GetHasNextPageOk returns a tuple with the HasNextPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasNextPage

`func (o *ResponseMeta) SetHasNextPage(v bool)`

SetHasNextPage sets HasNextPage field to given value.

### HasHasNextPage

`func (o *ResponseMeta) HasHasNextPage() bool`

HasHasNextPage returns a boolean if a field has been set.

### GetHasPreviousPage

`func (o *ResponseMeta) GetHasPreviousPage() bool`

GetHasPreviousPage returns the HasPreviousPage field if non-nil, zero value otherwise.

### GetHasPreviousPageOk

`func (o *ResponseMeta) GetHasPreviousPageOk() (*bool, bool)`

GetHasPreviousPageOk returns a tuple with the HasPreviousPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasPreviousPage

`func (o *ResponseMeta) SetHasPreviousPage(v bool)`

SetHasPreviousPage sets HasPreviousPage field to given value.

### HasHasPreviousPage

`func (o *ResponseMeta) HasHasPreviousPage() bool`

HasHasPreviousPage returns a boolean if a field has been set.

### GetNextCursor

`func (o *ResponseMeta) GetNextCursor() string`

GetNextCursor returns the NextCursor field if non-nil, zero value otherwise.

### GetNextCursorOk

`func (o *ResponseMeta) GetNextCursorOk() (*string, bool)`

GetNextCursorOk returns a tuple with the NextCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCursor

`func (o *ResponseMeta) SetNextCursor(v string)`

SetNextCursor sets NextCursor field to given value.

### HasNextCursor

`func (o *ResponseMeta) HasNextCursor() bool`

HasNextCursor returns a boolean if a field has been set.

### SetNextCursorNil

`func (o *ResponseMeta) SetNextCursorNil(b bool)`

 SetNextCursorNil sets the value for NextCursor to be an explicit nil

### UnsetNextCursor
`func (o *ResponseMeta) UnsetNextCursor()`

UnsetNextCursor ensures that no value is present for NextCursor, not even an explicit nil
### GetWarnings

`func (o *ResponseMeta) GetWarnings() []string`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *ResponseMeta) GetWarningsOk() (*[]string, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *ResponseMeta) SetWarnings(v []string)`

SetWarnings sets Warnings field to given value.

### HasWarnings

`func (o *ResponseMeta) HasWarnings() bool`

HasWarnings returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


