# PartnerNotificationDelivery

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeliveryId** | **string** |  | 
**NotificationId** | **string** |  | 
**EventType** | **NullableString** | What the notification was about. Null when the notification has been removed. | 
**Title** | **NullableString** |  | 
**Channel** | **string** |  | 
**Target** | **string** | The email address, or the host of your webhook (never the whole address, which may hold a token) | 
**Status** | **string** |  | 
**AttemptCount** | **int32** |  | 
**NextAttemptAt** | **NullableTime** | When the next attempt is made. Null once the delivery has ended. | 
**LastAttemptAt** | **NullableTime** |  | 
**DeliveredAt** | **NullableTime** |  | 
**LastStatusCode** | **NullableInt32** | The HTTP status your webhook answered with at the last attempt, when it answered | 
**LastError** | **NullableString** | Why the last attempt failed, in a few words. Never what your endpoint replied. | 
**CreatedAt** | **time.Time** |  | 
**ReplayOfDeliveryId** | **NullableString** | When this row is a manual replay, the earlier delivery it sent again | 

## Methods

### NewPartnerNotificationDelivery

`func NewPartnerNotificationDelivery(deliveryId string, notificationId string, eventType NullableString, title NullableString, channel string, target string, status string, attemptCount int32, nextAttemptAt NullableTime, lastAttemptAt NullableTime, deliveredAt NullableTime, lastStatusCode NullableInt32, lastError NullableString, createdAt time.Time, replayOfDeliveryId NullableString, ) *PartnerNotificationDelivery`

NewPartnerNotificationDelivery instantiates a new PartnerNotificationDelivery object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerNotificationDeliveryWithDefaults

`func NewPartnerNotificationDeliveryWithDefaults() *PartnerNotificationDelivery`

NewPartnerNotificationDeliveryWithDefaults instantiates a new PartnerNotificationDelivery object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeliveryId

`func (o *PartnerNotificationDelivery) GetDeliveryId() string`

GetDeliveryId returns the DeliveryId field if non-nil, zero value otherwise.

### GetDeliveryIdOk

`func (o *PartnerNotificationDelivery) GetDeliveryIdOk() (*string, bool)`

GetDeliveryIdOk returns a tuple with the DeliveryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryId

`func (o *PartnerNotificationDelivery) SetDeliveryId(v string)`

SetDeliveryId sets DeliveryId field to given value.


### GetNotificationId

`func (o *PartnerNotificationDelivery) GetNotificationId() string`

GetNotificationId returns the NotificationId field if non-nil, zero value otherwise.

### GetNotificationIdOk

`func (o *PartnerNotificationDelivery) GetNotificationIdOk() (*string, bool)`

GetNotificationIdOk returns a tuple with the NotificationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotificationId

`func (o *PartnerNotificationDelivery) SetNotificationId(v string)`

SetNotificationId sets NotificationId field to given value.


### GetEventType

`func (o *PartnerNotificationDelivery) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *PartnerNotificationDelivery) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *PartnerNotificationDelivery) SetEventType(v string)`

SetEventType sets EventType field to given value.


### SetEventTypeNil

`func (o *PartnerNotificationDelivery) SetEventTypeNil(b bool)`

 SetEventTypeNil sets the value for EventType to be an explicit nil

### UnsetEventType
`func (o *PartnerNotificationDelivery) UnsetEventType()`

UnsetEventType ensures that no value is present for EventType, not even an explicit nil
### GetTitle

`func (o *PartnerNotificationDelivery) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *PartnerNotificationDelivery) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *PartnerNotificationDelivery) SetTitle(v string)`

SetTitle sets Title field to given value.


### SetTitleNil

`func (o *PartnerNotificationDelivery) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *PartnerNotificationDelivery) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetChannel

`func (o *PartnerNotificationDelivery) GetChannel() string`

GetChannel returns the Channel field if non-nil, zero value otherwise.

### GetChannelOk

`func (o *PartnerNotificationDelivery) GetChannelOk() (*string, bool)`

GetChannelOk returns a tuple with the Channel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannel

`func (o *PartnerNotificationDelivery) SetChannel(v string)`

SetChannel sets Channel field to given value.


### GetTarget

`func (o *PartnerNotificationDelivery) GetTarget() string`

GetTarget returns the Target field if non-nil, zero value otherwise.

### GetTargetOk

`func (o *PartnerNotificationDelivery) GetTargetOk() (*string, bool)`

GetTargetOk returns a tuple with the Target field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTarget

`func (o *PartnerNotificationDelivery) SetTarget(v string)`

SetTarget sets Target field to given value.


### GetStatus

`func (o *PartnerNotificationDelivery) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PartnerNotificationDelivery) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PartnerNotificationDelivery) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetAttemptCount

`func (o *PartnerNotificationDelivery) GetAttemptCount() int32`

GetAttemptCount returns the AttemptCount field if non-nil, zero value otherwise.

### GetAttemptCountOk

`func (o *PartnerNotificationDelivery) GetAttemptCountOk() (*int32, bool)`

GetAttemptCountOk returns a tuple with the AttemptCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttemptCount

`func (o *PartnerNotificationDelivery) SetAttemptCount(v int32)`

SetAttemptCount sets AttemptCount field to given value.


### GetNextAttemptAt

`func (o *PartnerNotificationDelivery) GetNextAttemptAt() time.Time`

GetNextAttemptAt returns the NextAttemptAt field if non-nil, zero value otherwise.

### GetNextAttemptAtOk

`func (o *PartnerNotificationDelivery) GetNextAttemptAtOk() (*time.Time, bool)`

GetNextAttemptAtOk returns a tuple with the NextAttemptAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextAttemptAt

`func (o *PartnerNotificationDelivery) SetNextAttemptAt(v time.Time)`

SetNextAttemptAt sets NextAttemptAt field to given value.


### SetNextAttemptAtNil

`func (o *PartnerNotificationDelivery) SetNextAttemptAtNil(b bool)`

 SetNextAttemptAtNil sets the value for NextAttemptAt to be an explicit nil

### UnsetNextAttemptAt
`func (o *PartnerNotificationDelivery) UnsetNextAttemptAt()`

UnsetNextAttemptAt ensures that no value is present for NextAttemptAt, not even an explicit nil
### GetLastAttemptAt

`func (o *PartnerNotificationDelivery) GetLastAttemptAt() time.Time`

GetLastAttemptAt returns the LastAttemptAt field if non-nil, zero value otherwise.

### GetLastAttemptAtOk

`func (o *PartnerNotificationDelivery) GetLastAttemptAtOk() (*time.Time, bool)`

GetLastAttemptAtOk returns a tuple with the LastAttemptAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastAttemptAt

`func (o *PartnerNotificationDelivery) SetLastAttemptAt(v time.Time)`

SetLastAttemptAt sets LastAttemptAt field to given value.


### SetLastAttemptAtNil

`func (o *PartnerNotificationDelivery) SetLastAttemptAtNil(b bool)`

 SetLastAttemptAtNil sets the value for LastAttemptAt to be an explicit nil

### UnsetLastAttemptAt
`func (o *PartnerNotificationDelivery) UnsetLastAttemptAt()`

UnsetLastAttemptAt ensures that no value is present for LastAttemptAt, not even an explicit nil
### GetDeliveredAt

`func (o *PartnerNotificationDelivery) GetDeliveredAt() time.Time`

GetDeliveredAt returns the DeliveredAt field if non-nil, zero value otherwise.

### GetDeliveredAtOk

`func (o *PartnerNotificationDelivery) GetDeliveredAtOk() (*time.Time, bool)`

GetDeliveredAtOk returns a tuple with the DeliveredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveredAt

`func (o *PartnerNotificationDelivery) SetDeliveredAt(v time.Time)`

SetDeliveredAt sets DeliveredAt field to given value.


### SetDeliveredAtNil

`func (o *PartnerNotificationDelivery) SetDeliveredAtNil(b bool)`

 SetDeliveredAtNil sets the value for DeliveredAt to be an explicit nil

### UnsetDeliveredAt
`func (o *PartnerNotificationDelivery) UnsetDeliveredAt()`

UnsetDeliveredAt ensures that no value is present for DeliveredAt, not even an explicit nil
### GetLastStatusCode

`func (o *PartnerNotificationDelivery) GetLastStatusCode() int32`

GetLastStatusCode returns the LastStatusCode field if non-nil, zero value otherwise.

### GetLastStatusCodeOk

`func (o *PartnerNotificationDelivery) GetLastStatusCodeOk() (*int32, bool)`

GetLastStatusCodeOk returns a tuple with the LastStatusCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastStatusCode

`func (o *PartnerNotificationDelivery) SetLastStatusCode(v int32)`

SetLastStatusCode sets LastStatusCode field to given value.


### SetLastStatusCodeNil

`func (o *PartnerNotificationDelivery) SetLastStatusCodeNil(b bool)`

 SetLastStatusCodeNil sets the value for LastStatusCode to be an explicit nil

### UnsetLastStatusCode
`func (o *PartnerNotificationDelivery) UnsetLastStatusCode()`

UnsetLastStatusCode ensures that no value is present for LastStatusCode, not even an explicit nil
### GetLastError

`func (o *PartnerNotificationDelivery) GetLastError() string`

GetLastError returns the LastError field if non-nil, zero value otherwise.

### GetLastErrorOk

`func (o *PartnerNotificationDelivery) GetLastErrorOk() (*string, bool)`

GetLastErrorOk returns a tuple with the LastError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastError

`func (o *PartnerNotificationDelivery) SetLastError(v string)`

SetLastError sets LastError field to given value.


### SetLastErrorNil

`func (o *PartnerNotificationDelivery) SetLastErrorNil(b bool)`

 SetLastErrorNil sets the value for LastError to be an explicit nil

### UnsetLastError
`func (o *PartnerNotificationDelivery) UnsetLastError()`

UnsetLastError ensures that no value is present for LastError, not even an explicit nil
### GetCreatedAt

`func (o *PartnerNotificationDelivery) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *PartnerNotificationDelivery) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *PartnerNotificationDelivery) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetReplayOfDeliveryId

`func (o *PartnerNotificationDelivery) GetReplayOfDeliveryId() string`

GetReplayOfDeliveryId returns the ReplayOfDeliveryId field if non-nil, zero value otherwise.

### GetReplayOfDeliveryIdOk

`func (o *PartnerNotificationDelivery) GetReplayOfDeliveryIdOk() (*string, bool)`

GetReplayOfDeliveryIdOk returns a tuple with the ReplayOfDeliveryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplayOfDeliveryId

`func (o *PartnerNotificationDelivery) SetReplayOfDeliveryId(v string)`

SetReplayOfDeliveryId sets ReplayOfDeliveryId field to given value.


### SetReplayOfDeliveryIdNil

`func (o *PartnerNotificationDelivery) SetReplayOfDeliveryIdNil(b bool)`

 SetReplayOfDeliveryIdNil sets the value for ReplayOfDeliveryId to be an explicit nil

### UnsetReplayOfDeliveryId
`func (o *PartnerNotificationDelivery) UnsetReplayOfDeliveryId()`

UnsetReplayOfDeliveryId ensures that no value is present for ReplayOfDeliveryId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


