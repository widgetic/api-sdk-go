# EditorSession

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Token** | **string** | The credential the browser sends as &#x60;Authorization: Bearer &lt;token&gt;&#x60;. It starts with &#x60;wgt_ses_&#x60;. It works only for the calls of the session&#39;s surfaces, only for this managed user&#39;s content, and only until &#x60;expiresAt&#x60;.  | 
**SessionId** | **string** | Identifies the session, so you can end it (&#x60;revokeManagedUserEditorSession&#x60;). It is not a credential. | 
**ManagedUserId** | **string** |  | 
**ManagedUserExternalId** | **string** | Your own identifier for the managed user | 
**Surfaces** | **[]string** |  | 
**AllowedOrigin** | Pointer to **NullableString** | The web page origin the session is bound to, or null when it is not bound | [optional] 
**MaxCredits** | Pointer to **NullableInt32** | The most credits the session may spend on Widgetic&#39;s AI (&#x60;max_credits&#x60;), or null when it has no limit of its own | [optional] 
**ExpiresAt** | **time.Time** |  | 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewEditorSession

`func NewEditorSession(token string, sessionId string, managedUserId string, managedUserExternalId string, surfaces []string, expiresAt time.Time, createdAt time.Time, ) *EditorSession`

NewEditorSession instantiates a new EditorSession object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEditorSessionWithDefaults

`func NewEditorSessionWithDefaults() *EditorSession`

NewEditorSessionWithDefaults instantiates a new EditorSession object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetToken

`func (o *EditorSession) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *EditorSession) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *EditorSession) SetToken(v string)`

SetToken sets Token field to given value.


### GetSessionId

`func (o *EditorSession) GetSessionId() string`

GetSessionId returns the SessionId field if non-nil, zero value otherwise.

### GetSessionIdOk

`func (o *EditorSession) GetSessionIdOk() (*string, bool)`

GetSessionIdOk returns a tuple with the SessionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionId

`func (o *EditorSession) SetSessionId(v string)`

SetSessionId sets SessionId field to given value.


### GetManagedUserId

`func (o *EditorSession) GetManagedUserId() string`

GetManagedUserId returns the ManagedUserId field if non-nil, zero value otherwise.

### GetManagedUserIdOk

`func (o *EditorSession) GetManagedUserIdOk() (*string, bool)`

GetManagedUserIdOk returns a tuple with the ManagedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUserId

`func (o *EditorSession) SetManagedUserId(v string)`

SetManagedUserId sets ManagedUserId field to given value.


### GetManagedUserExternalId

`func (o *EditorSession) GetManagedUserExternalId() string`

GetManagedUserExternalId returns the ManagedUserExternalId field if non-nil, zero value otherwise.

### GetManagedUserExternalIdOk

`func (o *EditorSession) GetManagedUserExternalIdOk() (*string, bool)`

GetManagedUserExternalIdOk returns a tuple with the ManagedUserExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUserExternalId

`func (o *EditorSession) SetManagedUserExternalId(v string)`

SetManagedUserExternalId sets ManagedUserExternalId field to given value.


### GetSurfaces

`func (o *EditorSession) GetSurfaces() []string`

GetSurfaces returns the Surfaces field if non-nil, zero value otherwise.

### GetSurfacesOk

`func (o *EditorSession) GetSurfacesOk() (*[]string, bool)`

GetSurfacesOk returns a tuple with the Surfaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSurfaces

`func (o *EditorSession) SetSurfaces(v []string)`

SetSurfaces sets Surfaces field to given value.


### GetAllowedOrigin

`func (o *EditorSession) GetAllowedOrigin() string`

GetAllowedOrigin returns the AllowedOrigin field if non-nil, zero value otherwise.

### GetAllowedOriginOk

`func (o *EditorSession) GetAllowedOriginOk() (*string, bool)`

GetAllowedOriginOk returns a tuple with the AllowedOrigin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowedOrigin

`func (o *EditorSession) SetAllowedOrigin(v string)`

SetAllowedOrigin sets AllowedOrigin field to given value.

### HasAllowedOrigin

`func (o *EditorSession) HasAllowedOrigin() bool`

HasAllowedOrigin returns a boolean if a field has been set.

### SetAllowedOriginNil

`func (o *EditorSession) SetAllowedOriginNil(b bool)`

 SetAllowedOriginNil sets the value for AllowedOrigin to be an explicit nil

### UnsetAllowedOrigin
`func (o *EditorSession) UnsetAllowedOrigin()`

UnsetAllowedOrigin ensures that no value is present for AllowedOrigin, not even an explicit nil
### GetMaxCredits

`func (o *EditorSession) GetMaxCredits() int32`

GetMaxCredits returns the MaxCredits field if non-nil, zero value otherwise.

### GetMaxCreditsOk

`func (o *EditorSession) GetMaxCreditsOk() (*int32, bool)`

GetMaxCreditsOk returns a tuple with the MaxCredits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxCredits

`func (o *EditorSession) SetMaxCredits(v int32)`

SetMaxCredits sets MaxCredits field to given value.

### HasMaxCredits

`func (o *EditorSession) HasMaxCredits() bool`

HasMaxCredits returns a boolean if a field has been set.

### SetMaxCreditsNil

`func (o *EditorSession) SetMaxCreditsNil(b bool)`

 SetMaxCreditsNil sets the value for MaxCredits to be an explicit nil

### UnsetMaxCredits
`func (o *EditorSession) UnsetMaxCredits()`

UnsetMaxCredits ensures that no value is present for MaxCredits, not even an explicit nil
### GetExpiresAt

`func (o *EditorSession) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *EditorSession) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *EditorSession) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.


### GetCreatedAt

`func (o *EditorSession) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *EditorSession) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *EditorSession) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


