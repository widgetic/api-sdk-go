# CheckCompositionAccessResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CanAccess** | Pointer to **bool** | Whether the user can access the composition | [optional] 
**Reason** | Pointer to **string** | Reason for access decision | [optional] 

## Methods

### NewCheckCompositionAccessResponseData

`func NewCheckCompositionAccessResponseData() *CheckCompositionAccessResponseData`

NewCheckCompositionAccessResponseData instantiates a new CheckCompositionAccessResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCheckCompositionAccessResponseDataWithDefaults

`func NewCheckCompositionAccessResponseDataWithDefaults() *CheckCompositionAccessResponseData`

NewCheckCompositionAccessResponseDataWithDefaults instantiates a new CheckCompositionAccessResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCanAccess

`func (o *CheckCompositionAccessResponseData) GetCanAccess() bool`

GetCanAccess returns the CanAccess field if non-nil, zero value otherwise.

### GetCanAccessOk

`func (o *CheckCompositionAccessResponseData) GetCanAccessOk() (*bool, bool)`

GetCanAccessOk returns a tuple with the CanAccess field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanAccess

`func (o *CheckCompositionAccessResponseData) SetCanAccess(v bool)`

SetCanAccess sets CanAccess field to given value.

### HasCanAccess

`func (o *CheckCompositionAccessResponseData) HasCanAccess() bool`

HasCanAccess returns a boolean if a field has been set.

### GetReason

`func (o *CheckCompositionAccessResponseData) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *CheckCompositionAccessResponseData) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *CheckCompositionAccessResponseData) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *CheckCompositionAccessResponseData) HasReason() bool`

HasReason returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


