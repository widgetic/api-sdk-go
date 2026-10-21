# PartnerBillingOverviewOperationalCredits

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Balance** | **float32** | Credits the account holds | 
**ReservedBalance** | **float32** | Credits committed to an operation that is still running. Not spendable. | 
**AvailableBalance** | **float32** | What a new operation can use (&#x60;balance&#x60; minus &#x60;reservedBalance&#x60;, never below 0) | 
**RecentTransactions** | [**[]AccountCreditTransaction**](AccountCreditTransaction.md) | The ten newest ledger entries, newest first | 

## Methods

### NewPartnerBillingOverviewOperationalCredits

`func NewPartnerBillingOverviewOperationalCredits(balance float32, reservedBalance float32, availableBalance float32, recentTransactions []AccountCreditTransaction, ) *PartnerBillingOverviewOperationalCredits`

NewPartnerBillingOverviewOperationalCredits instantiates a new PartnerBillingOverviewOperationalCredits object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerBillingOverviewOperationalCreditsWithDefaults

`func NewPartnerBillingOverviewOperationalCreditsWithDefaults() *PartnerBillingOverviewOperationalCredits`

NewPartnerBillingOverviewOperationalCreditsWithDefaults instantiates a new PartnerBillingOverviewOperationalCredits object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBalance

`func (o *PartnerBillingOverviewOperationalCredits) GetBalance() float32`

GetBalance returns the Balance field if non-nil, zero value otherwise.

### GetBalanceOk

`func (o *PartnerBillingOverviewOperationalCredits) GetBalanceOk() (*float32, bool)`

GetBalanceOk returns a tuple with the Balance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBalance

`func (o *PartnerBillingOverviewOperationalCredits) SetBalance(v float32)`

SetBalance sets Balance field to given value.


### GetReservedBalance

`func (o *PartnerBillingOverviewOperationalCredits) GetReservedBalance() float32`

GetReservedBalance returns the ReservedBalance field if non-nil, zero value otherwise.

### GetReservedBalanceOk

`func (o *PartnerBillingOverviewOperationalCredits) GetReservedBalanceOk() (*float32, bool)`

GetReservedBalanceOk returns a tuple with the ReservedBalance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReservedBalance

`func (o *PartnerBillingOverviewOperationalCredits) SetReservedBalance(v float32)`

SetReservedBalance sets ReservedBalance field to given value.


### GetAvailableBalance

`func (o *PartnerBillingOverviewOperationalCredits) GetAvailableBalance() float32`

GetAvailableBalance returns the AvailableBalance field if non-nil, zero value otherwise.

### GetAvailableBalanceOk

`func (o *PartnerBillingOverviewOperationalCredits) GetAvailableBalanceOk() (*float32, bool)`

GetAvailableBalanceOk returns a tuple with the AvailableBalance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailableBalance

`func (o *PartnerBillingOverviewOperationalCredits) SetAvailableBalance(v float32)`

SetAvailableBalance sets AvailableBalance field to given value.


### GetRecentTransactions

`func (o *PartnerBillingOverviewOperationalCredits) GetRecentTransactions() []AccountCreditTransaction`

GetRecentTransactions returns the RecentTransactions field if non-nil, zero value otherwise.

### GetRecentTransactionsOk

`func (o *PartnerBillingOverviewOperationalCredits) GetRecentTransactionsOk() (*[]AccountCreditTransaction, bool)`

GetRecentTransactionsOk returns a tuple with the RecentTransactions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecentTransactions

`func (o *PartnerBillingOverviewOperationalCredits) SetRecentTransactions(v []AccountCreditTransaction)`

SetRecentTransactions sets RecentTransactions field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


