# GetManagedUserEntitlementsResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ManagedUserId** | Pointer to **string** |  | [optional] 
**Entitlements** | Pointer to [**[]Entitlement**](Entitlement.md) |  | [optional] 

## Methods

### NewGetManagedUserEntitlementsResponseData

`func NewGetManagedUserEntitlementsResponseData() *GetManagedUserEntitlementsResponseData`

NewGetManagedUserEntitlementsResponseData instantiates a new GetManagedUserEntitlementsResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetManagedUserEntitlementsResponseDataWithDefaults

`func NewGetManagedUserEntitlementsResponseDataWithDefaults() *GetManagedUserEntitlementsResponseData`

NewGetManagedUserEntitlementsResponseDataWithDefaults instantiates a new GetManagedUserEntitlementsResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetManagedUserId

`func (o *GetManagedUserEntitlementsResponseData) GetManagedUserId() string`

GetManagedUserId returns the ManagedUserId field if non-nil, zero value otherwise.

### GetManagedUserIdOk

`func (o *GetManagedUserEntitlementsResponseData) GetManagedUserIdOk() (*string, bool)`

GetManagedUserIdOk returns a tuple with the ManagedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUserId

`func (o *GetManagedUserEntitlementsResponseData) SetManagedUserId(v string)`

SetManagedUserId sets ManagedUserId field to given value.

### HasManagedUserId

`func (o *GetManagedUserEntitlementsResponseData) HasManagedUserId() bool`

HasManagedUserId returns a boolean if a field has been set.

### GetEntitlements

`func (o *GetManagedUserEntitlementsResponseData) GetEntitlements() []Entitlement`

GetEntitlements returns the Entitlements field if non-nil, zero value otherwise.

### GetEntitlementsOk

`func (o *GetManagedUserEntitlementsResponseData) GetEntitlementsOk() (*[]Entitlement, bool)`

GetEntitlementsOk returns a tuple with the Entitlements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntitlements

`func (o *GetManagedUserEntitlementsResponseData) SetEntitlements(v []Entitlement)`

SetEntitlements sets Entitlements field to given value.

### HasEntitlements

`func (o *GetManagedUserEntitlementsResponseData) HasEntitlements() bool`

HasEntitlements returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


