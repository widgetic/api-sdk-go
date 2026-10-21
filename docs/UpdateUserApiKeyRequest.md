# UpdateUserApiKeyRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | A new name. It cannot be one that another key of the account already has | [optional] 
**IsActive** | Pointer to **bool** | false switches the key off, true switches it on again. A key that is switched off stops working within a minute at the latest, and at once on the server that took the request | [optional] 

## Methods

### NewUpdateUserApiKeyRequest

`func NewUpdateUserApiKeyRequest() *UpdateUserApiKeyRequest`

NewUpdateUserApiKeyRequest instantiates a new UpdateUserApiKeyRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateUserApiKeyRequestWithDefaults

`func NewUpdateUserApiKeyRequestWithDefaults() *UpdateUserApiKeyRequest`

NewUpdateUserApiKeyRequestWithDefaults instantiates a new UpdateUserApiKeyRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateUserApiKeyRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateUserApiKeyRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateUserApiKeyRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateUserApiKeyRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetIsActive

`func (o *UpdateUserApiKeyRequest) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *UpdateUserApiKeyRequest) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *UpdateUserApiKeyRequest) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *UpdateUserApiKeyRequest) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


