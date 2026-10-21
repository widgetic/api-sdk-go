# CreateUserApiKeyRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | A name for the key, to tell it from the account&#39;s other keys | 
**ExpiresAt** | Pointer to **time.Time** | When the key stops working, as a date and time in the future with a zone. Omit it for a key that does not expire | [optional] 
**Preset** | Pointer to **string** | A ready-made list of scopes. &#x60;read_only&#x60; looks at everything the account holds and changes nothing. &#x60;content&#x60; builds and manages widgets and compositions and runs the AI, and touches no billing, no people and no partners. &#x60;full_access&#x60; is the same as sending neither &#x60;preset&#x60; nor &#x60;scopes&#x60;. Send either &#x60;preset&#x60; or &#x60;scopes&#x60;, not both | [optional] 
**Scopes** | Pointer to [**[]ApiKeyScope**](ApiKeyScope.md) | What the key may do, when a preset is not enough. Naming a write scope includes its read scope, and a list that holds every scope is a key with full access. Send either &#x60;scopes&#x60; or &#x60;preset&#x60;, not both | [optional] 

## Methods

### NewCreateUserApiKeyRequest

`func NewCreateUserApiKeyRequest(name string, ) *CreateUserApiKeyRequest`

NewCreateUserApiKeyRequest instantiates a new CreateUserApiKeyRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateUserApiKeyRequestWithDefaults

`func NewCreateUserApiKeyRequestWithDefaults() *CreateUserApiKeyRequest`

NewCreateUserApiKeyRequestWithDefaults instantiates a new CreateUserApiKeyRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateUserApiKeyRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateUserApiKeyRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateUserApiKeyRequest) SetName(v string)`

SetName sets Name field to given value.


### GetExpiresAt

`func (o *CreateUserApiKeyRequest) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *CreateUserApiKeyRequest) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *CreateUserApiKeyRequest) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *CreateUserApiKeyRequest) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### GetPreset

`func (o *CreateUserApiKeyRequest) GetPreset() string`

GetPreset returns the Preset field if non-nil, zero value otherwise.

### GetPresetOk

`func (o *CreateUserApiKeyRequest) GetPresetOk() (*string, bool)`

GetPresetOk returns a tuple with the Preset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreset

`func (o *CreateUserApiKeyRequest) SetPreset(v string)`

SetPreset sets Preset field to given value.

### HasPreset

`func (o *CreateUserApiKeyRequest) HasPreset() bool`

HasPreset returns a boolean if a field has been set.

### GetScopes

`func (o *CreateUserApiKeyRequest) GetScopes() []ApiKeyScope`

GetScopes returns the Scopes field if non-nil, zero value otherwise.

### GetScopesOk

`func (o *CreateUserApiKeyRequest) GetScopesOk() (*[]ApiKeyScope, bool)`

GetScopesOk returns a tuple with the Scopes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopes

`func (o *CreateUserApiKeyRequest) SetScopes(v []ApiKeyScope)`

SetScopes sets Scopes field to given value.

### HasScopes

`func (o *CreateUserApiKeyRequest) HasScopes() bool`

HasScopes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


