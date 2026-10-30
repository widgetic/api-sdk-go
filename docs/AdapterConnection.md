# AdapterConnection

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdapterId** | **string** | The adapter the key is for (its id in the adapter catalog) | 
**AdapterLabel** | **string** | What the adapter is called to its owner | 
**CredentialKey** | **string** | The name of the key within the adapter. Use it, with the adapter id, to connect or remove the key | 
**Label** | **string** | What the key is called to its owner | 
**Scope** | **string** | Who may keep this key. &#x60;owner&#x60; is the person who made the widget, in their own account. &#x60;partner&#x60; is a partner, for the widgets of the customers it manages. &#x60;owner_or_partner&#x60; is either; for a widget of a managed customer the partner&#39;s key is used. | 
**Connected** | **bool** | Whether this account has connected the key | 
**UpdatedAt** | **NullableTime** | When the key was last set. Null when it is not connected | 
**Confirmation** | **NullableString** | How this credential is proved before it is used. &#x60;email_code&#x60; means it is an email address: saving it emails a code to it, and it is used only after the code is given back (&#x60;confirmUserAdapterConnection&#x60;, &#x60;confirmPartnerAdapterConnection&#x60;). Null for a credential that is used as soon as it is saved | 
**AwaitingConfirmation** | **bool** | True when the credential is connected but has not been confirmed yet, so no adapter uses it. Always false when &#x60;confirmation&#x60; is null or the credential is not connected | 
**ConfirmedAt** | **NullableTime** | When the credential was confirmed. Null when it is not connected, is awaiting its code, or needs no confirmation | 

## Methods

### NewAdapterConnection

`func NewAdapterConnection(adapterId string, adapterLabel string, credentialKey string, label string, scope string, connected bool, updatedAt NullableTime, confirmation NullableString, awaitingConfirmation bool, confirmedAt NullableTime, ) *AdapterConnection`

NewAdapterConnection instantiates a new AdapterConnection object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAdapterConnectionWithDefaults

`func NewAdapterConnectionWithDefaults() *AdapterConnection`

NewAdapterConnectionWithDefaults instantiates a new AdapterConnection object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdapterId

`func (o *AdapterConnection) GetAdapterId() string`

GetAdapterId returns the AdapterId field if non-nil, zero value otherwise.

### GetAdapterIdOk

`func (o *AdapterConnection) GetAdapterIdOk() (*string, bool)`

GetAdapterIdOk returns a tuple with the AdapterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdapterId

`func (o *AdapterConnection) SetAdapterId(v string)`

SetAdapterId sets AdapterId field to given value.


### GetAdapterLabel

`func (o *AdapterConnection) GetAdapterLabel() string`

GetAdapterLabel returns the AdapterLabel field if non-nil, zero value otherwise.

### GetAdapterLabelOk

`func (o *AdapterConnection) GetAdapterLabelOk() (*string, bool)`

GetAdapterLabelOk returns a tuple with the AdapterLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdapterLabel

`func (o *AdapterConnection) SetAdapterLabel(v string)`

SetAdapterLabel sets AdapterLabel field to given value.


### GetCredentialKey

`func (o *AdapterConnection) GetCredentialKey() string`

GetCredentialKey returns the CredentialKey field if non-nil, zero value otherwise.

### GetCredentialKeyOk

`func (o *AdapterConnection) GetCredentialKeyOk() (*string, bool)`

GetCredentialKeyOk returns a tuple with the CredentialKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredentialKey

`func (o *AdapterConnection) SetCredentialKey(v string)`

SetCredentialKey sets CredentialKey field to given value.


### GetLabel

`func (o *AdapterConnection) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *AdapterConnection) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *AdapterConnection) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetScope

`func (o *AdapterConnection) GetScope() string`

GetScope returns the Scope field if non-nil, zero value otherwise.

### GetScopeOk

`func (o *AdapterConnection) GetScopeOk() (*string, bool)`

GetScopeOk returns a tuple with the Scope field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScope

`func (o *AdapterConnection) SetScope(v string)`

SetScope sets Scope field to given value.


### GetConnected

`func (o *AdapterConnection) GetConnected() bool`

GetConnected returns the Connected field if non-nil, zero value otherwise.

### GetConnectedOk

`func (o *AdapterConnection) GetConnectedOk() (*bool, bool)`

GetConnectedOk returns a tuple with the Connected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnected

`func (o *AdapterConnection) SetConnected(v bool)`

SetConnected sets Connected field to given value.


### GetUpdatedAt

`func (o *AdapterConnection) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *AdapterConnection) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *AdapterConnection) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### SetUpdatedAtNil

`func (o *AdapterConnection) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *AdapterConnection) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil
### GetConfirmation

`func (o *AdapterConnection) GetConfirmation() string`

GetConfirmation returns the Confirmation field if non-nil, zero value otherwise.

### GetConfirmationOk

`func (o *AdapterConnection) GetConfirmationOk() (*string, bool)`

GetConfirmationOk returns a tuple with the Confirmation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfirmation

`func (o *AdapterConnection) SetConfirmation(v string)`

SetConfirmation sets Confirmation field to given value.


### SetConfirmationNil

`func (o *AdapterConnection) SetConfirmationNil(b bool)`

 SetConfirmationNil sets the value for Confirmation to be an explicit nil

### UnsetConfirmation
`func (o *AdapterConnection) UnsetConfirmation()`

UnsetConfirmation ensures that no value is present for Confirmation, not even an explicit nil
### GetAwaitingConfirmation

`func (o *AdapterConnection) GetAwaitingConfirmation() bool`

GetAwaitingConfirmation returns the AwaitingConfirmation field if non-nil, zero value otherwise.

### GetAwaitingConfirmationOk

`func (o *AdapterConnection) GetAwaitingConfirmationOk() (*bool, bool)`

GetAwaitingConfirmationOk returns a tuple with the AwaitingConfirmation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAwaitingConfirmation

`func (o *AdapterConnection) SetAwaitingConfirmation(v bool)`

SetAwaitingConfirmation sets AwaitingConfirmation field to given value.


### GetConfirmedAt

`func (o *AdapterConnection) GetConfirmedAt() time.Time`

GetConfirmedAt returns the ConfirmedAt field if non-nil, zero value otherwise.

### GetConfirmedAtOk

`func (o *AdapterConnection) GetConfirmedAtOk() (*time.Time, bool)`

GetConfirmedAtOk returns a tuple with the ConfirmedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfirmedAt

`func (o *AdapterConnection) SetConfirmedAt(v time.Time)`

SetConfirmedAt sets ConfirmedAt field to given value.


### SetConfirmedAtNil

`func (o *AdapterConnection) SetConfirmedAtNil(b bool)`

 SetConfirmedAtNil sets the value for ConfirmedAt to be an explicit nil

### UnsetConfirmedAt
`func (o *AdapterConnection) UnsetConfirmedAt()`

UnsetConfirmedAt ensures that no value is present for ConfirmedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


