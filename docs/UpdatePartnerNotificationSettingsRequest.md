# UpdatePartnerNotificationSettingsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EmailRecipients** | Pointer to **[]string** | The addresses the emails go to, at most five. An empty list goes back to the defaults. | [optional] 
**EmailEvents** | Pointer to [**[]PartnerNotificationEventType**](PartnerNotificationEventType.md) | The events you want by email. Null for every event. | [optional] 
**WebhookEvents** | Pointer to [**[]PartnerNotificationEventType**](PartnerNotificationEventType.md) | The events to send to your webhook. Null for every event. | [optional] 
**WebhookUrl** | Pointer to **NullableString** | Where to send the signed calls. It must be an https address on the standard port, on a public site, and it must not redirect. Null or an empty text switches the webhook off. Setting an address when you have no secret yet makes one. | [optional] 

## Methods

### NewUpdatePartnerNotificationSettingsRequest

`func NewUpdatePartnerNotificationSettingsRequest() *UpdatePartnerNotificationSettingsRequest`

NewUpdatePartnerNotificationSettingsRequest instantiates a new UpdatePartnerNotificationSettingsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdatePartnerNotificationSettingsRequestWithDefaults

`func NewUpdatePartnerNotificationSettingsRequestWithDefaults() *UpdatePartnerNotificationSettingsRequest`

NewUpdatePartnerNotificationSettingsRequestWithDefaults instantiates a new UpdatePartnerNotificationSettingsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmailRecipients

`func (o *UpdatePartnerNotificationSettingsRequest) GetEmailRecipients() []string`

GetEmailRecipients returns the EmailRecipients field if non-nil, zero value otherwise.

### GetEmailRecipientsOk

`func (o *UpdatePartnerNotificationSettingsRequest) GetEmailRecipientsOk() (*[]string, bool)`

GetEmailRecipientsOk returns a tuple with the EmailRecipients field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailRecipients

`func (o *UpdatePartnerNotificationSettingsRequest) SetEmailRecipients(v []string)`

SetEmailRecipients sets EmailRecipients field to given value.

### HasEmailRecipients

`func (o *UpdatePartnerNotificationSettingsRequest) HasEmailRecipients() bool`

HasEmailRecipients returns a boolean if a field has been set.

### GetEmailEvents

`func (o *UpdatePartnerNotificationSettingsRequest) GetEmailEvents() []PartnerNotificationEventType`

GetEmailEvents returns the EmailEvents field if non-nil, zero value otherwise.

### GetEmailEventsOk

`func (o *UpdatePartnerNotificationSettingsRequest) GetEmailEventsOk() (*[]PartnerNotificationEventType, bool)`

GetEmailEventsOk returns a tuple with the EmailEvents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailEvents

`func (o *UpdatePartnerNotificationSettingsRequest) SetEmailEvents(v []PartnerNotificationEventType)`

SetEmailEvents sets EmailEvents field to given value.

### HasEmailEvents

`func (o *UpdatePartnerNotificationSettingsRequest) HasEmailEvents() bool`

HasEmailEvents returns a boolean if a field has been set.

### SetEmailEventsNil

`func (o *UpdatePartnerNotificationSettingsRequest) SetEmailEventsNil(b bool)`

 SetEmailEventsNil sets the value for EmailEvents to be an explicit nil

### UnsetEmailEvents
`func (o *UpdatePartnerNotificationSettingsRequest) UnsetEmailEvents()`

UnsetEmailEvents ensures that no value is present for EmailEvents, not even an explicit nil
### GetWebhookEvents

`func (o *UpdatePartnerNotificationSettingsRequest) GetWebhookEvents() []PartnerNotificationEventType`

GetWebhookEvents returns the WebhookEvents field if non-nil, zero value otherwise.

### GetWebhookEventsOk

`func (o *UpdatePartnerNotificationSettingsRequest) GetWebhookEventsOk() (*[]PartnerNotificationEventType, bool)`

GetWebhookEventsOk returns a tuple with the WebhookEvents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhookEvents

`func (o *UpdatePartnerNotificationSettingsRequest) SetWebhookEvents(v []PartnerNotificationEventType)`

SetWebhookEvents sets WebhookEvents field to given value.

### HasWebhookEvents

`func (o *UpdatePartnerNotificationSettingsRequest) HasWebhookEvents() bool`

HasWebhookEvents returns a boolean if a field has been set.

### SetWebhookEventsNil

`func (o *UpdatePartnerNotificationSettingsRequest) SetWebhookEventsNil(b bool)`

 SetWebhookEventsNil sets the value for WebhookEvents to be an explicit nil

### UnsetWebhookEvents
`func (o *UpdatePartnerNotificationSettingsRequest) UnsetWebhookEvents()`

UnsetWebhookEvents ensures that no value is present for WebhookEvents, not even an explicit nil
### GetWebhookUrl

`func (o *UpdatePartnerNotificationSettingsRequest) GetWebhookUrl() string`

GetWebhookUrl returns the WebhookUrl field if non-nil, zero value otherwise.

### GetWebhookUrlOk

`func (o *UpdatePartnerNotificationSettingsRequest) GetWebhookUrlOk() (*string, bool)`

GetWebhookUrlOk returns a tuple with the WebhookUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhookUrl

`func (o *UpdatePartnerNotificationSettingsRequest) SetWebhookUrl(v string)`

SetWebhookUrl sets WebhookUrl field to given value.

### HasWebhookUrl

`func (o *UpdatePartnerNotificationSettingsRequest) HasWebhookUrl() bool`

HasWebhookUrl returns a boolean if a field has been set.

### SetWebhookUrlNil

`func (o *UpdatePartnerNotificationSettingsRequest) SetWebhookUrlNil(b bool)`

 SetWebhookUrlNil sets the value for WebhookUrl to be an explicit nil

### UnsetWebhookUrl
`func (o *UpdatePartnerNotificationSettingsRequest) UnsetWebhookUrl()`

UnsetWebhookUrl ensures that no value is present for WebhookUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


