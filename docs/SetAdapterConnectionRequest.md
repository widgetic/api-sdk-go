# SetAdapterConnectionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Credential** | **string** | The key exactly as its provider gave it: one line of text, at most 2048 characters. It is stored encrypted and is never returned or logged. | 

## Methods

### NewSetAdapterConnectionRequest

`func NewSetAdapterConnectionRequest(credential string, ) *SetAdapterConnectionRequest`

NewSetAdapterConnectionRequest instantiates a new SetAdapterConnectionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSetAdapterConnectionRequestWithDefaults

`func NewSetAdapterConnectionRequestWithDefaults() *SetAdapterConnectionRequest`

NewSetAdapterConnectionRequestWithDefaults instantiates a new SetAdapterConnectionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCredential

`func (o *SetAdapterConnectionRequest) GetCredential() string`

GetCredential returns the Credential field if non-nil, zero value otherwise.

### GetCredentialOk

`func (o *SetAdapterConnectionRequest) GetCredentialOk() (*string, bool)`

GetCredentialOk returns a tuple with the Credential field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredential

`func (o *SetAdapterConnectionRequest) SetCredential(v string)`

SetCredential sets Credential field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


