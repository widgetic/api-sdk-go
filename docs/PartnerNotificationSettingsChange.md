# PartnerNotificationSettingsChange

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Settings** | [**PartnerNotificationSettings**](PartnerNotificationSettings.md) |  | 
**WebhookSecret** | **NullableString** | The secret that signs your webhook, in the form your receiver is configured with (&#x60;whsec_...&#x60;). It is in this answer ONLY: keep it now, it cannot be read again. Null when the change made no secret. | 

## Methods

### NewPartnerNotificationSettingsChange

`func NewPartnerNotificationSettingsChange(settings PartnerNotificationSettings, webhookSecret NullableString, ) *PartnerNotificationSettingsChange`

NewPartnerNotificationSettingsChange instantiates a new PartnerNotificationSettingsChange object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerNotificationSettingsChangeWithDefaults

`func NewPartnerNotificationSettingsChangeWithDefaults() *PartnerNotificationSettingsChange`

NewPartnerNotificationSettingsChangeWithDefaults instantiates a new PartnerNotificationSettingsChange object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSettings

`func (o *PartnerNotificationSettingsChange) GetSettings() PartnerNotificationSettings`

GetSettings returns the Settings field if non-nil, zero value otherwise.

### GetSettingsOk

`func (o *PartnerNotificationSettingsChange) GetSettingsOk() (*PartnerNotificationSettings, bool)`

GetSettingsOk returns a tuple with the Settings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettings

`func (o *PartnerNotificationSettingsChange) SetSettings(v PartnerNotificationSettings)`

SetSettings sets Settings field to given value.


### GetWebhookSecret

`func (o *PartnerNotificationSettingsChange) GetWebhookSecret() string`

GetWebhookSecret returns the WebhookSecret field if non-nil, zero value otherwise.

### GetWebhookSecretOk

`func (o *PartnerNotificationSettingsChange) GetWebhookSecretOk() (*string, bool)`

GetWebhookSecretOk returns a tuple with the WebhookSecret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhookSecret

`func (o *PartnerNotificationSettingsChange) SetWebhookSecret(v string)`

SetWebhookSecret sets WebhookSecret field to given value.


### SetWebhookSecretNil

`func (o *PartnerNotificationSettingsChange) SetWebhookSecretNil(b bool)`

 SetWebhookSecretNil sets the value for WebhookSecret to be an explicit nil

### UnsetWebhookSecret
`func (o *PartnerNotificationSettingsChange) UnsetWebhookSecret()`

UnsetWebhookSecret ensures that no value is present for WebhookSecret, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


