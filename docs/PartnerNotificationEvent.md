# PartnerNotificationEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | [**PartnerNotificationEventType**](PartnerNotificationEventType.md) |  | 
**Group** | **string** |  | 
**Label** | **string** |  | 
**Description** | **string** | One sentence that says when it happens | 
**AlwaysEmailed** | **bool** | True for money and standing: you are emailed whatever you chose, and can narrow only what your own system receives. | 
**Delivery** | **string** | &#x60;all&#x60;: email (when chosen), dashboard inbox and webhook. &#x60;webhook&#x60;: signed call only — no email and not listed in the dashboard inbox. | 

## Methods

### NewPartnerNotificationEvent

`func NewPartnerNotificationEvent(type_ PartnerNotificationEventType, group string, label string, description string, alwaysEmailed bool, delivery string, ) *PartnerNotificationEvent`

NewPartnerNotificationEvent instantiates a new PartnerNotificationEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerNotificationEventWithDefaults

`func NewPartnerNotificationEventWithDefaults() *PartnerNotificationEvent`

NewPartnerNotificationEventWithDefaults instantiates a new PartnerNotificationEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *PartnerNotificationEvent) GetType() PartnerNotificationEventType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PartnerNotificationEvent) GetTypeOk() (*PartnerNotificationEventType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PartnerNotificationEvent) SetType(v PartnerNotificationEventType)`

SetType sets Type field to given value.


### GetGroup

`func (o *PartnerNotificationEvent) GetGroup() string`

GetGroup returns the Group field if non-nil, zero value otherwise.

### GetGroupOk

`func (o *PartnerNotificationEvent) GetGroupOk() (*string, bool)`

GetGroupOk returns a tuple with the Group field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroup

`func (o *PartnerNotificationEvent) SetGroup(v string)`

SetGroup sets Group field to given value.


### GetLabel

`func (o *PartnerNotificationEvent) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *PartnerNotificationEvent) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *PartnerNotificationEvent) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetDescription

`func (o *PartnerNotificationEvent) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PartnerNotificationEvent) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PartnerNotificationEvent) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetAlwaysEmailed

`func (o *PartnerNotificationEvent) GetAlwaysEmailed() bool`

GetAlwaysEmailed returns the AlwaysEmailed field if non-nil, zero value otherwise.

### GetAlwaysEmailedOk

`func (o *PartnerNotificationEvent) GetAlwaysEmailedOk() (*bool, bool)`

GetAlwaysEmailedOk returns a tuple with the AlwaysEmailed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlwaysEmailed

`func (o *PartnerNotificationEvent) SetAlwaysEmailed(v bool)`

SetAlwaysEmailed sets AlwaysEmailed field to given value.


### GetDelivery

`func (o *PartnerNotificationEvent) GetDelivery() string`

GetDelivery returns the Delivery field if non-nil, zero value otherwise.

### GetDeliveryOk

`func (o *PartnerNotificationEvent) GetDeliveryOk() (*string, bool)`

GetDeliveryOk returns a tuple with the Delivery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelivery

`func (o *PartnerNotificationEvent) SetDelivery(v string)`

SetDelivery sets Delivery field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


