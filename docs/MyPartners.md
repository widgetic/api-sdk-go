# MyPartners

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Standing** | **string** | The standing of the account as a whole, the word every gate reads: &#x60;not_a_partner&#x60; when the account administers no partner; otherwise &#x60;active&#x60; when any of its partners is in force, else &#x60;payment_arrears&#x60; when the partners that are active each have a contract invoice that is past its due date and unpaid, else &#x60;suspended&#x60; when any is paused, else &#x60;inactive&#x60;. &#x60;payment_arrears&#x60; is not set by anybody: it stops the same things a pause stops (billing, invoices, credits and the other routes a partner needs to pay stay open) and ends by itself the moment the invoice is paid.  | 
**OverdueSince** | **NullableTime** | When the oldest overdue contract invoice was due; null unless &#x60;standing&#x60; is &#x60;payment_arrears&#x60;. Pay the invoices in the list of &#x60;GET /invoices/partner/{partnerId}&#x60; that are past their due date to end it.  | 
**Partners** | [**[]MyPartner**](MyPartner.md) | The partners the account administers (nearly always one), the oldest first | 

## Methods

### NewMyPartners

`func NewMyPartners(standing string, overdueSince NullableTime, partners []MyPartner, ) *MyPartners`

NewMyPartners instantiates a new MyPartners object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMyPartnersWithDefaults

`func NewMyPartnersWithDefaults() *MyPartners`

NewMyPartnersWithDefaults instantiates a new MyPartners object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStanding

`func (o *MyPartners) GetStanding() string`

GetStanding returns the Standing field if non-nil, zero value otherwise.

### GetStandingOk

`func (o *MyPartners) GetStandingOk() (*string, bool)`

GetStandingOk returns a tuple with the Standing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStanding

`func (o *MyPartners) SetStanding(v string)`

SetStanding sets Standing field to given value.


### GetOverdueSince

`func (o *MyPartners) GetOverdueSince() time.Time`

GetOverdueSince returns the OverdueSince field if non-nil, zero value otherwise.

### GetOverdueSinceOk

`func (o *MyPartners) GetOverdueSinceOk() (*time.Time, bool)`

GetOverdueSinceOk returns a tuple with the OverdueSince field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverdueSince

`func (o *MyPartners) SetOverdueSince(v time.Time)`

SetOverdueSince sets OverdueSince field to given value.


### SetOverdueSinceNil

`func (o *MyPartners) SetOverdueSinceNil(b bool)`

 SetOverdueSinceNil sets the value for OverdueSince to be an explicit nil

### UnsetOverdueSince
`func (o *MyPartners) UnsetOverdueSince()`

UnsetOverdueSince ensures that no value is present for OverdueSince, not even an explicit nil
### GetPartners

`func (o *MyPartners) GetPartners() []MyPartner`

GetPartners returns the Partners field if non-nil, zero value otherwise.

### GetPartnersOk

`func (o *MyPartners) GetPartnersOk() (*[]MyPartner, bool)`

GetPartnersOk returns a tuple with the Partners field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartners

`func (o *MyPartners) SetPartners(v []MyPartner)`

SetPartners sets Partners field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


