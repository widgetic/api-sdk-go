# PartnerEntryContextSecret

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Signing** | [**PartnerEntryContextSigning**](PartnerEntryContextSigning.md) |  | 
**Secret** | **string** | The secret: &#x60;ctxsec_&#x60; followed by the base64 of 32 random bytes. It is shown here, once, and cannot be read again. | 

## Methods

### NewPartnerEntryContextSecret

`func NewPartnerEntryContextSecret(signing PartnerEntryContextSigning, secret string, ) *PartnerEntryContextSecret`

NewPartnerEntryContextSecret instantiates a new PartnerEntryContextSecret object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerEntryContextSecretWithDefaults

`func NewPartnerEntryContextSecretWithDefaults() *PartnerEntryContextSecret`

NewPartnerEntryContextSecretWithDefaults instantiates a new PartnerEntryContextSecret object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSigning

`func (o *PartnerEntryContextSecret) GetSigning() PartnerEntryContextSigning`

GetSigning returns the Signing field if non-nil, zero value otherwise.

### GetSigningOk

`func (o *PartnerEntryContextSecret) GetSigningOk() (*PartnerEntryContextSigning, bool)`

GetSigningOk returns a tuple with the Signing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSigning

`func (o *PartnerEntryContextSecret) SetSigning(v PartnerEntryContextSigning)`

SetSigning sets Signing field to given value.


### GetSecret

`func (o *PartnerEntryContextSecret) GetSecret() string`

GetSecret returns the Secret field if non-nil, zero value otherwise.

### GetSecretOk

`func (o *PartnerEntryContextSecret) GetSecretOk() (*string, bool)`

GetSecretOk returns a tuple with the Secret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecret

`func (o *PartnerEntryContextSecret) SetSecret(v string)`

SetSecret sets Secret field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


