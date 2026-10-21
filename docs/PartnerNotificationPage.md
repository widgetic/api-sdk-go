# PartnerNotificationPage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Notifications** | [**[]PartnerNotification**](PartnerNotification.md) |  | 
**NextBefore** | **NullableTime** | Send as &#x60;before&#x60; to get the next, older page. Null when there is none. | 

## Methods

### NewPartnerNotificationPage

`func NewPartnerNotificationPage(notifications []PartnerNotification, nextBefore NullableTime, ) *PartnerNotificationPage`

NewPartnerNotificationPage instantiates a new PartnerNotificationPage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerNotificationPageWithDefaults

`func NewPartnerNotificationPageWithDefaults() *PartnerNotificationPage`

NewPartnerNotificationPageWithDefaults instantiates a new PartnerNotificationPage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNotifications

`func (o *PartnerNotificationPage) GetNotifications() []PartnerNotification`

GetNotifications returns the Notifications field if non-nil, zero value otherwise.

### GetNotificationsOk

`func (o *PartnerNotificationPage) GetNotificationsOk() (*[]PartnerNotification, bool)`

GetNotificationsOk returns a tuple with the Notifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifications

`func (o *PartnerNotificationPage) SetNotifications(v []PartnerNotification)`

SetNotifications sets Notifications field to given value.


### GetNextBefore

`func (o *PartnerNotificationPage) GetNextBefore() time.Time`

GetNextBefore returns the NextBefore field if non-nil, zero value otherwise.

### GetNextBeforeOk

`func (o *PartnerNotificationPage) GetNextBeforeOk() (*time.Time, bool)`

GetNextBeforeOk returns a tuple with the NextBefore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextBefore

`func (o *PartnerNotificationPage) SetNextBefore(v time.Time)`

SetNextBefore sets NextBefore field to given value.


### SetNextBeforeNil

`func (o *PartnerNotificationPage) SetNextBeforeNil(b bool)`

 SetNextBeforeNil sets the value for NextBefore to be an explicit nil

### UnsetNextBefore
`func (o *PartnerNotificationPage) UnsetNextBefore()`

UnsetNextBefore ensures that no value is present for NextBefore, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


