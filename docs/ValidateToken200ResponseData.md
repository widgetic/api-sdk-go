# ValidateToken200ResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Valid** | Pointer to **bool** |  | [optional] 
**TokenType** | Pointer to **string** |  | [optional] 
**Scopes** | Pointer to **[]string** |  | [optional] 
**UserId** | Pointer to **string** |  | [optional] 
**ExpiresAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewValidateToken200ResponseData

`func NewValidateToken200ResponseData() *ValidateToken200ResponseData`

NewValidateToken200ResponseData instantiates a new ValidateToken200ResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewValidateToken200ResponseDataWithDefaults

`func NewValidateToken200ResponseDataWithDefaults() *ValidateToken200ResponseData`

NewValidateToken200ResponseDataWithDefaults instantiates a new ValidateToken200ResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetValid

`func (o *ValidateToken200ResponseData) GetValid() bool`

GetValid returns the Valid field if non-nil, zero value otherwise.

### GetValidOk

`func (o *ValidateToken200ResponseData) GetValidOk() (*bool, bool)`

GetValidOk returns a tuple with the Valid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValid

`func (o *ValidateToken200ResponseData) SetValid(v bool)`

SetValid sets Valid field to given value.

### HasValid

`func (o *ValidateToken200ResponseData) HasValid() bool`

HasValid returns a boolean if a field has been set.

### GetTokenType

`func (o *ValidateToken200ResponseData) GetTokenType() string`

GetTokenType returns the TokenType field if non-nil, zero value otherwise.

### GetTokenTypeOk

`func (o *ValidateToken200ResponseData) GetTokenTypeOk() (*string, bool)`

GetTokenTypeOk returns a tuple with the TokenType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokenType

`func (o *ValidateToken200ResponseData) SetTokenType(v string)`

SetTokenType sets TokenType field to given value.

### HasTokenType

`func (o *ValidateToken200ResponseData) HasTokenType() bool`

HasTokenType returns a boolean if a field has been set.

### GetScopes

`func (o *ValidateToken200ResponseData) GetScopes() []string`

GetScopes returns the Scopes field if non-nil, zero value otherwise.

### GetScopesOk

`func (o *ValidateToken200ResponseData) GetScopesOk() (*[]string, bool)`

GetScopesOk returns a tuple with the Scopes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopes

`func (o *ValidateToken200ResponseData) SetScopes(v []string)`

SetScopes sets Scopes field to given value.

### HasScopes

`func (o *ValidateToken200ResponseData) HasScopes() bool`

HasScopes returns a boolean if a field has been set.

### GetUserId

`func (o *ValidateToken200ResponseData) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *ValidateToken200ResponseData) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *ValidateToken200ResponseData) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *ValidateToken200ResponseData) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetExpiresAt

`func (o *ValidateToken200ResponseData) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *ValidateToken200ResponseData) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *ValidateToken200ResponseData) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *ValidateToken200ResponseData) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


