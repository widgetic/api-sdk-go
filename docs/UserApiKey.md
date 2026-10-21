# UserApiKey

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**KeyId** | **string** | The id of the key. Use it to rename, switch off, delete or read the usage of the key | 
**KeyPreview** | **string** | The first characters of the key, to tell keys apart. Not enough to use it | 
**Name** | **string** | The name given to the key | 
**CreatedAt** | **time.Time** |  | 
**ExpiresAt** | Pointer to **NullableTime** | When the key stops working. Absent or null when it does not expire | [optional] 
**LastUsedAt** | Pointer to **NullableTime** | When the key was last used. Absent or null when it never was | [optional] 
**IsActive** | **bool** | Whether the key works. A key that is switched off is refused until it is switched on again | 
**Scopes** | [**[]ApiKeyScope**](ApiKeyScope.md) | What the key may do. A key with full access holds every scope. The scopes of a key are fixed when it is made | 
**Preset** | **string** | The name the scopes amount to. &#x60;full_access&#x60; is a key that is not limited, &#x60;read_only&#x60; and &#x60;content&#x60; are the ready-made lists, and &#x60;custom&#x60; is any other list | 

## Methods

### NewUserApiKey

`func NewUserApiKey(keyId string, keyPreview string, name string, createdAt time.Time, isActive bool, scopes []ApiKeyScope, preset string, ) *UserApiKey`

NewUserApiKey instantiates a new UserApiKey object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserApiKeyWithDefaults

`func NewUserApiKeyWithDefaults() *UserApiKey`

NewUserApiKeyWithDefaults instantiates a new UserApiKey object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKeyId

`func (o *UserApiKey) GetKeyId() string`

GetKeyId returns the KeyId field if non-nil, zero value otherwise.

### GetKeyIdOk

`func (o *UserApiKey) GetKeyIdOk() (*string, bool)`

GetKeyIdOk returns a tuple with the KeyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyId

`func (o *UserApiKey) SetKeyId(v string)`

SetKeyId sets KeyId field to given value.


### GetKeyPreview

`func (o *UserApiKey) GetKeyPreview() string`

GetKeyPreview returns the KeyPreview field if non-nil, zero value otherwise.

### GetKeyPreviewOk

`func (o *UserApiKey) GetKeyPreviewOk() (*string, bool)`

GetKeyPreviewOk returns a tuple with the KeyPreview field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyPreview

`func (o *UserApiKey) SetKeyPreview(v string)`

SetKeyPreview sets KeyPreview field to given value.


### GetName

`func (o *UserApiKey) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UserApiKey) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UserApiKey) SetName(v string)`

SetName sets Name field to given value.


### GetCreatedAt

`func (o *UserApiKey) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *UserApiKey) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *UserApiKey) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetExpiresAt

`func (o *UserApiKey) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *UserApiKey) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *UserApiKey) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *UserApiKey) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### SetExpiresAtNil

`func (o *UserApiKey) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *UserApiKey) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil
### GetLastUsedAt

`func (o *UserApiKey) GetLastUsedAt() time.Time`

GetLastUsedAt returns the LastUsedAt field if non-nil, zero value otherwise.

### GetLastUsedAtOk

`func (o *UserApiKey) GetLastUsedAtOk() (*time.Time, bool)`

GetLastUsedAtOk returns a tuple with the LastUsedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUsedAt

`func (o *UserApiKey) SetLastUsedAt(v time.Time)`

SetLastUsedAt sets LastUsedAt field to given value.

### HasLastUsedAt

`func (o *UserApiKey) HasLastUsedAt() bool`

HasLastUsedAt returns a boolean if a field has been set.

### SetLastUsedAtNil

`func (o *UserApiKey) SetLastUsedAtNil(b bool)`

 SetLastUsedAtNil sets the value for LastUsedAt to be an explicit nil

### UnsetLastUsedAt
`func (o *UserApiKey) UnsetLastUsedAt()`

UnsetLastUsedAt ensures that no value is present for LastUsedAt, not even an explicit nil
### GetIsActive

`func (o *UserApiKey) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *UserApiKey) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *UserApiKey) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.


### GetScopes

`func (o *UserApiKey) GetScopes() []ApiKeyScope`

GetScopes returns the Scopes field if non-nil, zero value otherwise.

### GetScopesOk

`func (o *UserApiKey) GetScopesOk() (*[]ApiKeyScope, bool)`

GetScopesOk returns a tuple with the Scopes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopes

`func (o *UserApiKey) SetScopes(v []ApiKeyScope)`

SetScopes sets Scopes field to given value.


### GetPreset

`func (o *UserApiKey) GetPreset() string`

GetPreset returns the Preset field if non-nil, zero value otherwise.

### GetPresetOk

`func (o *UserApiKey) GetPresetOk() (*string, bool)`

GetPresetOk returns a tuple with the Preset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreset

`func (o *UserApiKey) SetPreset(v string)`

SetPreset sets Preset field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


