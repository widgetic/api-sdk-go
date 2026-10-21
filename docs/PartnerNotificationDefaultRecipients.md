# PartnerNotificationDefaultRecipients

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Payments** | **[]string** | For the invoice events, the billing emails of your billing profile, or your contact email when there are none | 
**Other** | **[]string** | For every other event, your contact email | 

## Methods

### NewPartnerNotificationDefaultRecipients

`func NewPartnerNotificationDefaultRecipients(payments []string, other []string, ) *PartnerNotificationDefaultRecipients`

NewPartnerNotificationDefaultRecipients instantiates a new PartnerNotificationDefaultRecipients object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerNotificationDefaultRecipientsWithDefaults

`func NewPartnerNotificationDefaultRecipientsWithDefaults() *PartnerNotificationDefaultRecipients`

NewPartnerNotificationDefaultRecipientsWithDefaults instantiates a new PartnerNotificationDefaultRecipients object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPayments

`func (o *PartnerNotificationDefaultRecipients) GetPayments() []string`

GetPayments returns the Payments field if non-nil, zero value otherwise.

### GetPaymentsOk

`func (o *PartnerNotificationDefaultRecipients) GetPaymentsOk() (*[]string, bool)`

GetPaymentsOk returns a tuple with the Payments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayments

`func (o *PartnerNotificationDefaultRecipients) SetPayments(v []string)`

SetPayments sets Payments field to given value.


### GetOther

`func (o *PartnerNotificationDefaultRecipients) GetOther() []string`

GetOther returns the Other field if non-nil, zero value otherwise.

### GetOtherOk

`func (o *PartnerNotificationDefaultRecipients) GetOtherOk() (*[]string, bool)`

GetOtherOk returns a tuple with the Other field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOther

`func (o *PartnerNotificationDefaultRecipients) SetOther(v []string)`

SetOther sets Other field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


