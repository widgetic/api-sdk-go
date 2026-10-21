# AccountCreditBalance

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**UserId** | Pointer to **string** |  | [optional] 
**Balance** | Pointer to **float32** | Credits the account holds | [optional] 
**ReservedBalance** | Pointer to **float32** | Credits committed to an operation that is still running. They cannot be spent, so what a new operation can use is &#x60;balance - reservedBalance&#x60;.  | [optional] 
**LastUpdated** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewAccountCreditBalance

`func NewAccountCreditBalance() *AccountCreditBalance`

NewAccountCreditBalance instantiates a new AccountCreditBalance object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountCreditBalanceWithDefaults

`func NewAccountCreditBalanceWithDefaults() *AccountCreditBalance`

NewAccountCreditBalanceWithDefaults instantiates a new AccountCreditBalance object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AccountCreditBalance) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AccountCreditBalance) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AccountCreditBalance) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AccountCreditBalance) HasId() bool`

HasId returns a boolean if a field has been set.

### GetUserId

`func (o *AccountCreditBalance) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *AccountCreditBalance) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *AccountCreditBalance) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *AccountCreditBalance) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetBalance

`func (o *AccountCreditBalance) GetBalance() float32`

GetBalance returns the Balance field if non-nil, zero value otherwise.

### GetBalanceOk

`func (o *AccountCreditBalance) GetBalanceOk() (*float32, bool)`

GetBalanceOk returns a tuple with the Balance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBalance

`func (o *AccountCreditBalance) SetBalance(v float32)`

SetBalance sets Balance field to given value.

### HasBalance

`func (o *AccountCreditBalance) HasBalance() bool`

HasBalance returns a boolean if a field has been set.

### GetReservedBalance

`func (o *AccountCreditBalance) GetReservedBalance() float32`

GetReservedBalance returns the ReservedBalance field if non-nil, zero value otherwise.

### GetReservedBalanceOk

`func (o *AccountCreditBalance) GetReservedBalanceOk() (*float32, bool)`

GetReservedBalanceOk returns a tuple with the ReservedBalance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReservedBalance

`func (o *AccountCreditBalance) SetReservedBalance(v float32)`

SetReservedBalance sets ReservedBalance field to given value.

### HasReservedBalance

`func (o *AccountCreditBalance) HasReservedBalance() bool`

HasReservedBalance returns a boolean if a field has been set.

### GetLastUpdated

`func (o *AccountCreditBalance) GetLastUpdated() time.Time`

GetLastUpdated returns the LastUpdated field if non-nil, zero value otherwise.

### GetLastUpdatedOk

`func (o *AccountCreditBalance) GetLastUpdatedOk() (*time.Time, bool)`

GetLastUpdatedOk returns a tuple with the LastUpdated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUpdated

`func (o *AccountCreditBalance) SetLastUpdated(v time.Time)`

SetLastUpdated sets LastUpdated field to given value.

### HasLastUpdated

`func (o *AccountCreditBalance) HasLastUpdated() bool`

HasLastUpdated returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


