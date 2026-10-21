# SetManagedUserLimitsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MonthlyCredits** | **NullableInt32** |  | 

## Methods

### NewSetManagedUserLimitsRequest

`func NewSetManagedUserLimitsRequest(monthlyCredits NullableInt32, ) *SetManagedUserLimitsRequest`

NewSetManagedUserLimitsRequest instantiates a new SetManagedUserLimitsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSetManagedUserLimitsRequestWithDefaults

`func NewSetManagedUserLimitsRequestWithDefaults() *SetManagedUserLimitsRequest`

NewSetManagedUserLimitsRequestWithDefaults instantiates a new SetManagedUserLimitsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMonthlyCredits

`func (o *SetManagedUserLimitsRequest) GetMonthlyCredits() int32`

GetMonthlyCredits returns the MonthlyCredits field if non-nil, zero value otherwise.

### GetMonthlyCreditsOk

`func (o *SetManagedUserLimitsRequest) GetMonthlyCreditsOk() (*int32, bool)`

GetMonthlyCreditsOk returns a tuple with the MonthlyCredits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthlyCredits

`func (o *SetManagedUserLimitsRequest) SetMonthlyCredits(v int32)`

SetMonthlyCredits sets MonthlyCredits field to given value.


### SetMonthlyCreditsNil

`func (o *SetManagedUserLimitsRequest) SetMonthlyCreditsNil(b bool)`

 SetMonthlyCreditsNil sets the value for MonthlyCredits to be an explicit nil

### UnsetMonthlyCredits
`func (o *SetManagedUserLimitsRequest) UnsetMonthlyCredits()`

UnsetMonthlyCredits ensures that no value is present for MonthlyCredits, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


