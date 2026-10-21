# PartnerEntryContextSigning

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PartnerId** | **string** |  | 
**Required** | **bool** | True: an entry whose context carries no valid signature is refused (403 &#x60;CONTEXT_SIGNATURE_REQUIRED&#x60;). False: an entry that carries a signature is checked, and one that carries none is accepted as before. | 
**SecretSet** | **bool** | Whether you have a signing secret. Until you have, no signature is checked and none can be required. | 
**SecretRotatedAt** | **NullableTime** | When the current secret was made. Null while there is none. | 
**PreviousSecretValidUntil** | **NullableTime** | While you switch to a new secret, when the secret it replaced stops being accepted. Null when there is none to wait for. | 
**SigningAvailable** | **bool** | False when this server cannot keep secrets, in which case none can be made yet. | 

## Methods

### NewPartnerEntryContextSigning

`func NewPartnerEntryContextSigning(partnerId string, required bool, secretSet bool, secretRotatedAt NullableTime, previousSecretValidUntil NullableTime, signingAvailable bool, ) *PartnerEntryContextSigning`

NewPartnerEntryContextSigning instantiates a new PartnerEntryContextSigning object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerEntryContextSigningWithDefaults

`func NewPartnerEntryContextSigningWithDefaults() *PartnerEntryContextSigning`

NewPartnerEntryContextSigningWithDefaults instantiates a new PartnerEntryContextSigning object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPartnerId

`func (o *PartnerEntryContextSigning) GetPartnerId() string`

GetPartnerId returns the PartnerId field if non-nil, zero value otherwise.

### GetPartnerIdOk

`func (o *PartnerEntryContextSigning) GetPartnerIdOk() (*string, bool)`

GetPartnerIdOk returns a tuple with the PartnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartnerId

`func (o *PartnerEntryContextSigning) SetPartnerId(v string)`

SetPartnerId sets PartnerId field to given value.


### GetRequired

`func (o *PartnerEntryContextSigning) GetRequired() bool`

GetRequired returns the Required field if non-nil, zero value otherwise.

### GetRequiredOk

`func (o *PartnerEntryContextSigning) GetRequiredOk() (*bool, bool)`

GetRequiredOk returns a tuple with the Required field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequired

`func (o *PartnerEntryContextSigning) SetRequired(v bool)`

SetRequired sets Required field to given value.


### GetSecretSet

`func (o *PartnerEntryContextSigning) GetSecretSet() bool`

GetSecretSet returns the SecretSet field if non-nil, zero value otherwise.

### GetSecretSetOk

`func (o *PartnerEntryContextSigning) GetSecretSetOk() (*bool, bool)`

GetSecretSetOk returns a tuple with the SecretSet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecretSet

`func (o *PartnerEntryContextSigning) SetSecretSet(v bool)`

SetSecretSet sets SecretSet field to given value.


### GetSecretRotatedAt

`func (o *PartnerEntryContextSigning) GetSecretRotatedAt() time.Time`

GetSecretRotatedAt returns the SecretRotatedAt field if non-nil, zero value otherwise.

### GetSecretRotatedAtOk

`func (o *PartnerEntryContextSigning) GetSecretRotatedAtOk() (*time.Time, bool)`

GetSecretRotatedAtOk returns a tuple with the SecretRotatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecretRotatedAt

`func (o *PartnerEntryContextSigning) SetSecretRotatedAt(v time.Time)`

SetSecretRotatedAt sets SecretRotatedAt field to given value.


### SetSecretRotatedAtNil

`func (o *PartnerEntryContextSigning) SetSecretRotatedAtNil(b bool)`

 SetSecretRotatedAtNil sets the value for SecretRotatedAt to be an explicit nil

### UnsetSecretRotatedAt
`func (o *PartnerEntryContextSigning) UnsetSecretRotatedAt()`

UnsetSecretRotatedAt ensures that no value is present for SecretRotatedAt, not even an explicit nil
### GetPreviousSecretValidUntil

`func (o *PartnerEntryContextSigning) GetPreviousSecretValidUntil() time.Time`

GetPreviousSecretValidUntil returns the PreviousSecretValidUntil field if non-nil, zero value otherwise.

### GetPreviousSecretValidUntilOk

`func (o *PartnerEntryContextSigning) GetPreviousSecretValidUntilOk() (*time.Time, bool)`

GetPreviousSecretValidUntilOk returns a tuple with the PreviousSecretValidUntil field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviousSecretValidUntil

`func (o *PartnerEntryContextSigning) SetPreviousSecretValidUntil(v time.Time)`

SetPreviousSecretValidUntil sets PreviousSecretValidUntil field to given value.


### SetPreviousSecretValidUntilNil

`func (o *PartnerEntryContextSigning) SetPreviousSecretValidUntilNil(b bool)`

 SetPreviousSecretValidUntilNil sets the value for PreviousSecretValidUntil to be an explicit nil

### UnsetPreviousSecretValidUntil
`func (o *PartnerEntryContextSigning) UnsetPreviousSecretValidUntil()`

UnsetPreviousSecretValidUntil ensures that no value is present for PreviousSecretValidUntil, not even an explicit nil
### GetSigningAvailable

`func (o *PartnerEntryContextSigning) GetSigningAvailable() bool`

GetSigningAvailable returns the SigningAvailable field if non-nil, zero value otherwise.

### GetSigningAvailableOk

`func (o *PartnerEntryContextSigning) GetSigningAvailableOk() (*bool, bool)`

GetSigningAvailableOk returns a tuple with the SigningAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSigningAvailable

`func (o *PartnerEntryContextSigning) SetSigningAvailable(v bool)`

SetSigningAvailable sets SigningAvailable field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


