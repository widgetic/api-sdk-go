# CreatedUserApiKey

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | **string** | The secret. Send it as a bearer token, in the &#x60;Authorization&#x60; header. Shown once | 
**KeyId** | **string** | The id of the key | 
**KeyPreview** | **string** |  | 
**Name** | **string** |  | 
**CreatedAt** | **time.Time** |  | 
**ExpiresAt** | Pointer to **NullableTime** |  | [optional] 
**IsActive** | **bool** |  | 
**Scopes** | [**[]ApiKeyScope**](ApiKeyScope.md) | What the key may do. A key made without scopes holds every scope | 
**Preset** | **string** | The name the scopes amount to | 

## Methods

### NewCreatedUserApiKey

`func NewCreatedUserApiKey(key string, keyId string, keyPreview string, name string, createdAt time.Time, isActive bool, scopes []ApiKeyScope, preset string, ) *CreatedUserApiKey`

NewCreatedUserApiKey instantiates a new CreatedUserApiKey object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreatedUserApiKeyWithDefaults

`func NewCreatedUserApiKeyWithDefaults() *CreatedUserApiKey`

NewCreatedUserApiKeyWithDefaults instantiates a new CreatedUserApiKey object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *CreatedUserApiKey) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *CreatedUserApiKey) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *CreatedUserApiKey) SetKey(v string)`

SetKey sets Key field to given value.


### GetKeyId

`func (o *CreatedUserApiKey) GetKeyId() string`

GetKeyId returns the KeyId field if non-nil, zero value otherwise.

### GetKeyIdOk

`func (o *CreatedUserApiKey) GetKeyIdOk() (*string, bool)`

GetKeyIdOk returns a tuple with the KeyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyId

`func (o *CreatedUserApiKey) SetKeyId(v string)`

SetKeyId sets KeyId field to given value.


### GetKeyPreview

`func (o *CreatedUserApiKey) GetKeyPreview() string`

GetKeyPreview returns the KeyPreview field if non-nil, zero value otherwise.

### GetKeyPreviewOk

`func (o *CreatedUserApiKey) GetKeyPreviewOk() (*string, bool)`

GetKeyPreviewOk returns a tuple with the KeyPreview field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyPreview

`func (o *CreatedUserApiKey) SetKeyPreview(v string)`

SetKeyPreview sets KeyPreview field to given value.


### GetName

`func (o *CreatedUserApiKey) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreatedUserApiKey) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreatedUserApiKey) SetName(v string)`

SetName sets Name field to given value.


### GetCreatedAt

`func (o *CreatedUserApiKey) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CreatedUserApiKey) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CreatedUserApiKey) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetExpiresAt

`func (o *CreatedUserApiKey) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *CreatedUserApiKey) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *CreatedUserApiKey) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *CreatedUserApiKey) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### SetExpiresAtNil

`func (o *CreatedUserApiKey) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *CreatedUserApiKey) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil
### GetIsActive

`func (o *CreatedUserApiKey) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *CreatedUserApiKey) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *CreatedUserApiKey) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.


### GetScopes

`func (o *CreatedUserApiKey) GetScopes() []ApiKeyScope`

GetScopes returns the Scopes field if non-nil, zero value otherwise.

### GetScopesOk

`func (o *CreatedUserApiKey) GetScopesOk() (*[]ApiKeyScope, bool)`

GetScopesOk returns a tuple with the Scopes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopes

`func (o *CreatedUserApiKey) SetScopes(v []ApiKeyScope)`

SetScopes sets Scopes field to given value.


### GetPreset

`func (o *CreatedUserApiKey) GetPreset() string`

GetPreset returns the Preset field if non-nil, zero value otherwise.

### GetPresetOk

`func (o *CreatedUserApiKey) GetPresetOk() (*string, bool)`

GetPresetOk returns a tuple with the Preset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreset

`func (o *CreatedUserApiKey) SetPreset(v string)`

SetPreset sets Preset field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


