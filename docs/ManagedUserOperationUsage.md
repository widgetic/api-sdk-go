# ManagedUserOperationUsage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Operation** | **string** | The metered operation, as the credit ledger names it | 
**Calls** | **int32** | How many runs of the operation were paid for and kept (a run that was refunded is not one) | 
**Credits** | **int32** | The credits those runs took from your account | 
**RefundedCalls** | **int32** | How many runs were refunded (a generation that failed), and so are not in &#x60;calls&#x60; | 
**RefundedCredits** | **int32** | The credits the refunded runs took, which went back to your account | 

## Methods

### NewManagedUserOperationUsage

`func NewManagedUserOperationUsage(operation string, calls int32, credits int32, refundedCalls int32, refundedCredits int32, ) *ManagedUserOperationUsage`

NewManagedUserOperationUsage instantiates a new ManagedUserOperationUsage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagedUserOperationUsageWithDefaults

`func NewManagedUserOperationUsageWithDefaults() *ManagedUserOperationUsage`

NewManagedUserOperationUsageWithDefaults instantiates a new ManagedUserOperationUsage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOperation

`func (o *ManagedUserOperationUsage) GetOperation() string`

GetOperation returns the Operation field if non-nil, zero value otherwise.

### GetOperationOk

`func (o *ManagedUserOperationUsage) GetOperationOk() (*string, bool)`

GetOperationOk returns a tuple with the Operation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperation

`func (o *ManagedUserOperationUsage) SetOperation(v string)`

SetOperation sets Operation field to given value.


### GetCalls

`func (o *ManagedUserOperationUsage) GetCalls() int32`

GetCalls returns the Calls field if non-nil, zero value otherwise.

### GetCallsOk

`func (o *ManagedUserOperationUsage) GetCallsOk() (*int32, bool)`

GetCallsOk returns a tuple with the Calls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCalls

`func (o *ManagedUserOperationUsage) SetCalls(v int32)`

SetCalls sets Calls field to given value.


### GetCredits

`func (o *ManagedUserOperationUsage) GetCredits() int32`

GetCredits returns the Credits field if non-nil, zero value otherwise.

### GetCreditsOk

`func (o *ManagedUserOperationUsage) GetCreditsOk() (*int32, bool)`

GetCreditsOk returns a tuple with the Credits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredits

`func (o *ManagedUserOperationUsage) SetCredits(v int32)`

SetCredits sets Credits field to given value.


### GetRefundedCalls

`func (o *ManagedUserOperationUsage) GetRefundedCalls() int32`

GetRefundedCalls returns the RefundedCalls field if non-nil, zero value otherwise.

### GetRefundedCallsOk

`func (o *ManagedUserOperationUsage) GetRefundedCallsOk() (*int32, bool)`

GetRefundedCallsOk returns a tuple with the RefundedCalls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefundedCalls

`func (o *ManagedUserOperationUsage) SetRefundedCalls(v int32)`

SetRefundedCalls sets RefundedCalls field to given value.


### GetRefundedCredits

`func (o *ManagedUserOperationUsage) GetRefundedCredits() int32`

GetRefundedCredits returns the RefundedCredits field if non-nil, zero value otherwise.

### GetRefundedCreditsOk

`func (o *ManagedUserOperationUsage) GetRefundedCreditsOk() (*int32, bool)`

GetRefundedCreditsOk returns a tuple with the RefundedCredits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefundedCredits

`func (o *ManagedUserOperationUsage) SetRefundedCredits(v int32)`

SetRefundedCredits sets RefundedCredits field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


