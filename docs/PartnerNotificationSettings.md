# PartnerNotificationSettings

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PartnerId** | **string** |  | 
**EmailRecipients** | **[]string** | The addresses the emails go to. Empty means the defaults. | 
**DefaultEmailRecipients** | [**PartnerNotificationDefaultRecipients**](PartnerNotificationDefaultRecipients.md) |  | 
**EmailEvents** | [**[]PartnerNotificationEventType**](PartnerNotificationEventType.md) | The events you want by email. Null means every event. The events marked &#x60;alwaysEmailed&#x60; are emailed whatever it says. | 
**WebhookUrl** | **NullableString** | Where Widgetic sends a signed call for each event. Null while the webhook is switched off. | 
**WebhookEvents** | [**[]PartnerNotificationEventType**](PartnerNotificationEventType.md) | The events sent to your webhook. Null means every event. | 
**WebhookSecretSet** | **bool** | Whether a signing secret exists. Calls are made only when it does. | 
**WebhookSecretRotatedAt** | **NullableTime** | When the current secret was made | 
**WebhookSigningAvailable** | **bool** | False when this server cannot sign webhooks, in which case a webhook cannot be set up yet | 
**Events** | [**[]PartnerNotificationEvent**](PartnerNotificationEvent.md) | Every event there is, for a settings screen to list | 

## Methods

### NewPartnerNotificationSettings

`func NewPartnerNotificationSettings(partnerId string, emailRecipients []string, defaultEmailRecipients PartnerNotificationDefaultRecipients, emailEvents []PartnerNotificationEventType, webhookUrl NullableString, webhookEvents []PartnerNotificationEventType, webhookSecretSet bool, webhookSecretRotatedAt NullableTime, webhookSigningAvailable bool, events []PartnerNotificationEvent, ) *PartnerNotificationSettings`

NewPartnerNotificationSettings instantiates a new PartnerNotificationSettings object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerNotificationSettingsWithDefaults

`func NewPartnerNotificationSettingsWithDefaults() *PartnerNotificationSettings`

NewPartnerNotificationSettingsWithDefaults instantiates a new PartnerNotificationSettings object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPartnerId

`func (o *PartnerNotificationSettings) GetPartnerId() string`

GetPartnerId returns the PartnerId field if non-nil, zero value otherwise.

### GetPartnerIdOk

`func (o *PartnerNotificationSettings) GetPartnerIdOk() (*string, bool)`

GetPartnerIdOk returns a tuple with the PartnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartnerId

`func (o *PartnerNotificationSettings) SetPartnerId(v string)`

SetPartnerId sets PartnerId field to given value.


### GetEmailRecipients

`func (o *PartnerNotificationSettings) GetEmailRecipients() []string`

GetEmailRecipients returns the EmailRecipients field if non-nil, zero value otherwise.

### GetEmailRecipientsOk

`func (o *PartnerNotificationSettings) GetEmailRecipientsOk() (*[]string, bool)`

GetEmailRecipientsOk returns a tuple with the EmailRecipients field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailRecipients

`func (o *PartnerNotificationSettings) SetEmailRecipients(v []string)`

SetEmailRecipients sets EmailRecipients field to given value.


### GetDefaultEmailRecipients

`func (o *PartnerNotificationSettings) GetDefaultEmailRecipients() PartnerNotificationDefaultRecipients`

GetDefaultEmailRecipients returns the DefaultEmailRecipients field if non-nil, zero value otherwise.

### GetDefaultEmailRecipientsOk

`func (o *PartnerNotificationSettings) GetDefaultEmailRecipientsOk() (*PartnerNotificationDefaultRecipients, bool)`

GetDefaultEmailRecipientsOk returns a tuple with the DefaultEmailRecipients field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultEmailRecipients

`func (o *PartnerNotificationSettings) SetDefaultEmailRecipients(v PartnerNotificationDefaultRecipients)`

SetDefaultEmailRecipients sets DefaultEmailRecipients field to given value.


### GetEmailEvents

`func (o *PartnerNotificationSettings) GetEmailEvents() []PartnerNotificationEventType`

GetEmailEvents returns the EmailEvents field if non-nil, zero value otherwise.

### GetEmailEventsOk

`func (o *PartnerNotificationSettings) GetEmailEventsOk() (*[]PartnerNotificationEventType, bool)`

GetEmailEventsOk returns a tuple with the EmailEvents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailEvents

`func (o *PartnerNotificationSettings) SetEmailEvents(v []PartnerNotificationEventType)`

SetEmailEvents sets EmailEvents field to given value.


### SetEmailEventsNil

`func (o *PartnerNotificationSettings) SetEmailEventsNil(b bool)`

 SetEmailEventsNil sets the value for EmailEvents to be an explicit nil

### UnsetEmailEvents
`func (o *PartnerNotificationSettings) UnsetEmailEvents()`

UnsetEmailEvents ensures that no value is present for EmailEvents, not even an explicit nil
### GetWebhookUrl

`func (o *PartnerNotificationSettings) GetWebhookUrl() string`

GetWebhookUrl returns the WebhookUrl field if non-nil, zero value otherwise.

### GetWebhookUrlOk

`func (o *PartnerNotificationSettings) GetWebhookUrlOk() (*string, bool)`

GetWebhookUrlOk returns a tuple with the WebhookUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhookUrl

`func (o *PartnerNotificationSettings) SetWebhookUrl(v string)`

SetWebhookUrl sets WebhookUrl field to given value.


### SetWebhookUrlNil

`func (o *PartnerNotificationSettings) SetWebhookUrlNil(b bool)`

 SetWebhookUrlNil sets the value for WebhookUrl to be an explicit nil

### UnsetWebhookUrl
`func (o *PartnerNotificationSettings) UnsetWebhookUrl()`

UnsetWebhookUrl ensures that no value is present for WebhookUrl, not even an explicit nil
### GetWebhookEvents

`func (o *PartnerNotificationSettings) GetWebhookEvents() []PartnerNotificationEventType`

GetWebhookEvents returns the WebhookEvents field if non-nil, zero value otherwise.

### GetWebhookEventsOk

`func (o *PartnerNotificationSettings) GetWebhookEventsOk() (*[]PartnerNotificationEventType, bool)`

GetWebhookEventsOk returns a tuple with the WebhookEvents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhookEvents

`func (o *PartnerNotificationSettings) SetWebhookEvents(v []PartnerNotificationEventType)`

SetWebhookEvents sets WebhookEvents field to given value.


### SetWebhookEventsNil

`func (o *PartnerNotificationSettings) SetWebhookEventsNil(b bool)`

 SetWebhookEventsNil sets the value for WebhookEvents to be an explicit nil

### UnsetWebhookEvents
`func (o *PartnerNotificationSettings) UnsetWebhookEvents()`

UnsetWebhookEvents ensures that no value is present for WebhookEvents, not even an explicit nil
### GetWebhookSecretSet

`func (o *PartnerNotificationSettings) GetWebhookSecretSet() bool`

GetWebhookSecretSet returns the WebhookSecretSet field if non-nil, zero value otherwise.

### GetWebhookSecretSetOk

`func (o *PartnerNotificationSettings) GetWebhookSecretSetOk() (*bool, bool)`

GetWebhookSecretSetOk returns a tuple with the WebhookSecretSet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhookSecretSet

`func (o *PartnerNotificationSettings) SetWebhookSecretSet(v bool)`

SetWebhookSecretSet sets WebhookSecretSet field to given value.


### GetWebhookSecretRotatedAt

`func (o *PartnerNotificationSettings) GetWebhookSecretRotatedAt() time.Time`

GetWebhookSecretRotatedAt returns the WebhookSecretRotatedAt field if non-nil, zero value otherwise.

### GetWebhookSecretRotatedAtOk

`func (o *PartnerNotificationSettings) GetWebhookSecretRotatedAtOk() (*time.Time, bool)`

GetWebhookSecretRotatedAtOk returns a tuple with the WebhookSecretRotatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhookSecretRotatedAt

`func (o *PartnerNotificationSettings) SetWebhookSecretRotatedAt(v time.Time)`

SetWebhookSecretRotatedAt sets WebhookSecretRotatedAt field to given value.


### SetWebhookSecretRotatedAtNil

`func (o *PartnerNotificationSettings) SetWebhookSecretRotatedAtNil(b bool)`

 SetWebhookSecretRotatedAtNil sets the value for WebhookSecretRotatedAt to be an explicit nil

### UnsetWebhookSecretRotatedAt
`func (o *PartnerNotificationSettings) UnsetWebhookSecretRotatedAt()`

UnsetWebhookSecretRotatedAt ensures that no value is present for WebhookSecretRotatedAt, not even an explicit nil
### GetWebhookSigningAvailable

`func (o *PartnerNotificationSettings) GetWebhookSigningAvailable() bool`

GetWebhookSigningAvailable returns the WebhookSigningAvailable field if non-nil, zero value otherwise.

### GetWebhookSigningAvailableOk

`func (o *PartnerNotificationSettings) GetWebhookSigningAvailableOk() (*bool, bool)`

GetWebhookSigningAvailableOk returns a tuple with the WebhookSigningAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhookSigningAvailable

`func (o *PartnerNotificationSettings) SetWebhookSigningAvailable(v bool)`

SetWebhookSigningAvailable sets WebhookSigningAvailable field to given value.


### GetEvents

`func (o *PartnerNotificationSettings) GetEvents() []PartnerNotificationEvent`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *PartnerNotificationSettings) GetEventsOk() (*[]PartnerNotificationEvent, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *PartnerNotificationSettings) SetEvents(v []PartnerNotificationEvent)`

SetEvents sets Events field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


