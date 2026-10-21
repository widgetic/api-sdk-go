# GetPartnerEntitlementsResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PartnerId** | Pointer to **string** |  | [optional] 
**Entitlements** | Pointer to [**[]Entitlement**](Entitlement.md) |  | [optional] 

## Methods

### NewGetPartnerEntitlementsResponseData

`func NewGetPartnerEntitlementsResponseData() *GetPartnerEntitlementsResponseData`

NewGetPartnerEntitlementsResponseData instantiates a new GetPartnerEntitlementsResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetPartnerEntitlementsResponseDataWithDefaults

`func NewGetPartnerEntitlementsResponseDataWithDefaults() *GetPartnerEntitlementsResponseData`

NewGetPartnerEntitlementsResponseDataWithDefaults instantiates a new GetPartnerEntitlementsResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPartnerId

`func (o *GetPartnerEntitlementsResponseData) GetPartnerId() string`

GetPartnerId returns the PartnerId field if non-nil, zero value otherwise.

### GetPartnerIdOk

`func (o *GetPartnerEntitlementsResponseData) GetPartnerIdOk() (*string, bool)`

GetPartnerIdOk returns a tuple with the PartnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartnerId

`func (o *GetPartnerEntitlementsResponseData) SetPartnerId(v string)`

SetPartnerId sets PartnerId field to given value.

### HasPartnerId

`func (o *GetPartnerEntitlementsResponseData) HasPartnerId() bool`

HasPartnerId returns a boolean if a field has been set.

### GetEntitlements

`func (o *GetPartnerEntitlementsResponseData) GetEntitlements() []Entitlement`

GetEntitlements returns the Entitlements field if non-nil, zero value otherwise.

### GetEntitlementsOk

`func (o *GetPartnerEntitlementsResponseData) GetEntitlementsOk() (*[]Entitlement, bool)`

GetEntitlementsOk returns a tuple with the Entitlements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntitlements

`func (o *GetPartnerEntitlementsResponseData) SetEntitlements(v []Entitlement)`

SetEntitlements sets Entitlements field to given value.

### HasEntitlements

`func (o *GetPartnerEntitlementsResponseData) HasEntitlements() bool`

HasEntitlements returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


