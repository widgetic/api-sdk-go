# UpdatePartnerEntryContextSigningRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Required** | **bool** | True to refuse every entry whose context carries no valid signature. False to check the signature of the entries that carry one and accept the others, as before. | 

## Methods

### NewUpdatePartnerEntryContextSigningRequest

`func NewUpdatePartnerEntryContextSigningRequest(required bool, ) *UpdatePartnerEntryContextSigningRequest`

NewUpdatePartnerEntryContextSigningRequest instantiates a new UpdatePartnerEntryContextSigningRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdatePartnerEntryContextSigningRequestWithDefaults

`func NewUpdatePartnerEntryContextSigningRequestWithDefaults() *UpdatePartnerEntryContextSigningRequest`

NewUpdatePartnerEntryContextSigningRequestWithDefaults instantiates a new UpdatePartnerEntryContextSigningRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRequired

`func (o *UpdatePartnerEntryContextSigningRequest) GetRequired() bool`

GetRequired returns the Required field if non-nil, zero value otherwise.

### GetRequiredOk

`func (o *UpdatePartnerEntryContextSigningRequest) GetRequiredOk() (*bool, bool)`

GetRequiredOk returns a tuple with the Required field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequired

`func (o *UpdatePartnerEntryContextSigningRequest) SetRequired(v bool)`

SetRequired sets Required field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


