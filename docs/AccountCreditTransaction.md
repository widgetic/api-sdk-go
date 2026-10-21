# AccountCreditTransaction

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**TransactionType** | Pointer to **NullableString** | What the entry did to the balance. &#x60;debit&#x60; is credits spent (this is how consumption shows), &#x60;credit&#x60; and &#x60;subscription&#x60; are credits added, &#x60;refund&#x60; returns credits that were spent, &#x60;reserve&#x60; and &#x60;release&#x60; move credits in and out of the reserved amount, and &#x60;adjustment&#x60;, &#x60;expiration&#x60;, &#x60;transfer_out&#x60; and &#x60;transfer_in&#x60; are the remaining ways a balance changes. The list can grow, so treat an unknown type as an entry you do not need to interpret.  | [optional] 
**Amount** | Pointer to **float32** | Always positive. The &#x60;transactionType&#x60; says whether the credits were added or taken. | [optional] 
**BalanceAfter** | Pointer to **NullableFloat32** | The balance once this entry was applied | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**ReferenceId** | Pointer to **NullableString** | The event the entry belongs to. An entry is recorded once per reference. | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewAccountCreditTransaction

`func NewAccountCreditTransaction() *AccountCreditTransaction`

NewAccountCreditTransaction instantiates a new AccountCreditTransaction object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountCreditTransactionWithDefaults

`func NewAccountCreditTransactionWithDefaults() *AccountCreditTransaction`

NewAccountCreditTransactionWithDefaults instantiates a new AccountCreditTransaction object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AccountCreditTransaction) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AccountCreditTransaction) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AccountCreditTransaction) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AccountCreditTransaction) HasId() bool`

HasId returns a boolean if a field has been set.

### GetTransactionType

`func (o *AccountCreditTransaction) GetTransactionType() string`

GetTransactionType returns the TransactionType field if non-nil, zero value otherwise.

### GetTransactionTypeOk

`func (o *AccountCreditTransaction) GetTransactionTypeOk() (*string, bool)`

GetTransactionTypeOk returns a tuple with the TransactionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionType

`func (o *AccountCreditTransaction) SetTransactionType(v string)`

SetTransactionType sets TransactionType field to given value.

### HasTransactionType

`func (o *AccountCreditTransaction) HasTransactionType() bool`

HasTransactionType returns a boolean if a field has been set.

### SetTransactionTypeNil

`func (o *AccountCreditTransaction) SetTransactionTypeNil(b bool)`

 SetTransactionTypeNil sets the value for TransactionType to be an explicit nil

### UnsetTransactionType
`func (o *AccountCreditTransaction) UnsetTransactionType()`

UnsetTransactionType ensures that no value is present for TransactionType, not even an explicit nil
### GetAmount

`func (o *AccountCreditTransaction) GetAmount() float32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *AccountCreditTransaction) GetAmountOk() (*float32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *AccountCreditTransaction) SetAmount(v float32)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *AccountCreditTransaction) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetBalanceAfter

`func (o *AccountCreditTransaction) GetBalanceAfter() float32`

GetBalanceAfter returns the BalanceAfter field if non-nil, zero value otherwise.

### GetBalanceAfterOk

`func (o *AccountCreditTransaction) GetBalanceAfterOk() (*float32, bool)`

GetBalanceAfterOk returns a tuple with the BalanceAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBalanceAfter

`func (o *AccountCreditTransaction) SetBalanceAfter(v float32)`

SetBalanceAfter sets BalanceAfter field to given value.

### HasBalanceAfter

`func (o *AccountCreditTransaction) HasBalanceAfter() bool`

HasBalanceAfter returns a boolean if a field has been set.

### SetBalanceAfterNil

`func (o *AccountCreditTransaction) SetBalanceAfterNil(b bool)`

 SetBalanceAfterNil sets the value for BalanceAfter to be an explicit nil

### UnsetBalanceAfter
`func (o *AccountCreditTransaction) UnsetBalanceAfter()`

UnsetBalanceAfter ensures that no value is present for BalanceAfter, not even an explicit nil
### GetDescription

`func (o *AccountCreditTransaction) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *AccountCreditTransaction) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *AccountCreditTransaction) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *AccountCreditTransaction) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *AccountCreditTransaction) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *AccountCreditTransaction) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetReferenceId

`func (o *AccountCreditTransaction) GetReferenceId() string`

GetReferenceId returns the ReferenceId field if non-nil, zero value otherwise.

### GetReferenceIdOk

`func (o *AccountCreditTransaction) GetReferenceIdOk() (*string, bool)`

GetReferenceIdOk returns a tuple with the ReferenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceId

`func (o *AccountCreditTransaction) SetReferenceId(v string)`

SetReferenceId sets ReferenceId field to given value.

### HasReferenceId

`func (o *AccountCreditTransaction) HasReferenceId() bool`

HasReferenceId returns a boolean if a field has been set.

### SetReferenceIdNil

`func (o *AccountCreditTransaction) SetReferenceIdNil(b bool)`

 SetReferenceIdNil sets the value for ReferenceId to be an explicit nil

### UnsetReferenceId
`func (o *AccountCreditTransaction) UnsetReferenceId()`

UnsetReferenceId ensures that no value is present for ReferenceId, not even an explicit nil
### GetCreatedAt

`func (o *AccountCreditTransaction) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AccountCreditTransaction) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AccountCreditTransaction) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *AccountCreditTransaction) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


