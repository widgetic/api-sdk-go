# ManagedUserLimits

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MonthlyCredits** | **NullableInt32** | The cap, or null when there is no monthly cap | 
**CreditsUsedThisMonth** | **int32** |  | 
**CreditsLeftThisMonth** | **NullableInt32** |  | 
**ResetsAt** | **time.Time** | First instant of the next UTC calendar month | 

## Methods

### NewManagedUserLimits

`func NewManagedUserLimits(monthlyCredits NullableInt32, creditsUsedThisMonth int32, creditsLeftThisMonth NullableInt32, resetsAt time.Time, ) *ManagedUserLimits`

NewManagedUserLimits instantiates a new ManagedUserLimits object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagedUserLimitsWithDefaults

`func NewManagedUserLimitsWithDefaults() *ManagedUserLimits`

NewManagedUserLimitsWithDefaults instantiates a new ManagedUserLimits object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMonthlyCredits

`func (o *ManagedUserLimits) GetMonthlyCredits() int32`

GetMonthlyCredits returns the MonthlyCredits field if non-nil, zero value otherwise.

### GetMonthlyCreditsOk

`func (o *ManagedUserLimits) GetMonthlyCreditsOk() (*int32, bool)`

GetMonthlyCreditsOk returns a tuple with the MonthlyCredits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthlyCredits

`func (o *ManagedUserLimits) SetMonthlyCredits(v int32)`

SetMonthlyCredits sets MonthlyCredits field to given value.


### SetMonthlyCreditsNil

`func (o *ManagedUserLimits) SetMonthlyCreditsNil(b bool)`

 SetMonthlyCreditsNil sets the value for MonthlyCredits to be an explicit nil

### UnsetMonthlyCredits
`func (o *ManagedUserLimits) UnsetMonthlyCredits()`

UnsetMonthlyCredits ensures that no value is present for MonthlyCredits, not even an explicit nil
### GetCreditsUsedThisMonth

`func (o *ManagedUserLimits) GetCreditsUsedThisMonth() int32`

GetCreditsUsedThisMonth returns the CreditsUsedThisMonth field if non-nil, zero value otherwise.

### GetCreditsUsedThisMonthOk

`func (o *ManagedUserLimits) GetCreditsUsedThisMonthOk() (*int32, bool)`

GetCreditsUsedThisMonthOk returns a tuple with the CreditsUsedThisMonth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsUsedThisMonth

`func (o *ManagedUserLimits) SetCreditsUsedThisMonth(v int32)`

SetCreditsUsedThisMonth sets CreditsUsedThisMonth field to given value.


### GetCreditsLeftThisMonth

`func (o *ManagedUserLimits) GetCreditsLeftThisMonth() int32`

GetCreditsLeftThisMonth returns the CreditsLeftThisMonth field if non-nil, zero value otherwise.

### GetCreditsLeftThisMonthOk

`func (o *ManagedUserLimits) GetCreditsLeftThisMonthOk() (*int32, bool)`

GetCreditsLeftThisMonthOk returns a tuple with the CreditsLeftThisMonth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsLeftThisMonth

`func (o *ManagedUserLimits) SetCreditsLeftThisMonth(v int32)`

SetCreditsLeftThisMonth sets CreditsLeftThisMonth field to given value.


### SetCreditsLeftThisMonthNil

`func (o *ManagedUserLimits) SetCreditsLeftThisMonthNil(b bool)`

 SetCreditsLeftThisMonthNil sets the value for CreditsLeftThisMonth to be an explicit nil

### UnsetCreditsLeftThisMonth
`func (o *ManagedUserLimits) UnsetCreditsLeftThisMonth()`

UnsetCreditsLeftThisMonth ensures that no value is present for CreditsLeftThisMonth, not even an explicit nil
### GetResetsAt

`func (o *ManagedUserLimits) GetResetsAt() time.Time`

GetResetsAt returns the ResetsAt field if non-nil, zero value otherwise.

### GetResetsAtOk

`func (o *ManagedUserLimits) GetResetsAtOk() (*time.Time, bool)`

GetResetsAtOk returns a tuple with the ResetsAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResetsAt

`func (o *ManagedUserLimits) SetResetsAt(v time.Time)`

SetResetsAt sets ResetsAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


