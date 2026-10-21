# ManagedUserUsage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ManagedUserId** | **string** |  | 
**ManagedUserExternalId** | **string** | Your own identifier for the managed user | 
**From** | **time.Time** | Start of the period, included | 
**To** | **time.Time** | End of the period, not included | 
**Totals** | [**ManagedUserUsageTotals**](ManagedUserUsageTotals.md) |  | 
**Operations** | [**[]ManagedUserOperationUsage**](ManagedUserOperationUsage.md) | One entry for each operation that was paid for in the period, in alphabetical order | 

## Methods

### NewManagedUserUsage

`func NewManagedUserUsage(managedUserId string, managedUserExternalId string, from time.Time, to time.Time, totals ManagedUserUsageTotals, operations []ManagedUserOperationUsage, ) *ManagedUserUsage`

NewManagedUserUsage instantiates a new ManagedUserUsage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagedUserUsageWithDefaults

`func NewManagedUserUsageWithDefaults() *ManagedUserUsage`

NewManagedUserUsageWithDefaults instantiates a new ManagedUserUsage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetManagedUserId

`func (o *ManagedUserUsage) GetManagedUserId() string`

GetManagedUserId returns the ManagedUserId field if non-nil, zero value otherwise.

### GetManagedUserIdOk

`func (o *ManagedUserUsage) GetManagedUserIdOk() (*string, bool)`

GetManagedUserIdOk returns a tuple with the ManagedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUserId

`func (o *ManagedUserUsage) SetManagedUserId(v string)`

SetManagedUserId sets ManagedUserId field to given value.


### GetManagedUserExternalId

`func (o *ManagedUserUsage) GetManagedUserExternalId() string`

GetManagedUserExternalId returns the ManagedUserExternalId field if non-nil, zero value otherwise.

### GetManagedUserExternalIdOk

`func (o *ManagedUserUsage) GetManagedUserExternalIdOk() (*string, bool)`

GetManagedUserExternalIdOk returns a tuple with the ManagedUserExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUserExternalId

`func (o *ManagedUserUsage) SetManagedUserExternalId(v string)`

SetManagedUserExternalId sets ManagedUserExternalId field to given value.


### GetFrom

`func (o *ManagedUserUsage) GetFrom() time.Time`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *ManagedUserUsage) GetFromOk() (*time.Time, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *ManagedUserUsage) SetFrom(v time.Time)`

SetFrom sets From field to given value.


### GetTo

`func (o *ManagedUserUsage) GetTo() time.Time`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *ManagedUserUsage) GetToOk() (*time.Time, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *ManagedUserUsage) SetTo(v time.Time)`

SetTo sets To field to given value.


### GetTotals

`func (o *ManagedUserUsage) GetTotals() ManagedUserUsageTotals`

GetTotals returns the Totals field if non-nil, zero value otherwise.

### GetTotalsOk

`func (o *ManagedUserUsage) GetTotalsOk() (*ManagedUserUsageTotals, bool)`

GetTotalsOk returns a tuple with the Totals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotals

`func (o *ManagedUserUsage) SetTotals(v ManagedUserUsageTotals)`

SetTotals sets Totals field to given value.


### GetOperations

`func (o *ManagedUserUsage) GetOperations() []ManagedUserOperationUsage`

GetOperations returns the Operations field if non-nil, zero value otherwise.

### GetOperationsOk

`func (o *ManagedUserUsage) GetOperationsOk() (*[]ManagedUserOperationUsage, bool)`

GetOperationsOk returns a tuple with the Operations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperations

`func (o *ManagedUserUsage) SetOperations(v []ManagedUserOperationUsage)`

SetOperations sets Operations field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


