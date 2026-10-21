# PartnerAnalyticsTimeline

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PartnerId** | **string** |  | 
**Period** | [**PartnerReportPeriod**](PartnerReportPeriod.md) |  | 
**ManagedUserId** | **NullableString** | The managed user the report is narrowed to. Null for the whole account. | 
**Days** | [**[]PartnerAnalyticsOfDay**](PartnerAnalyticsOfDay.md) | One entry for every day of the period, oldest first. A day nothing happened on is all zeros. | 

## Methods

### NewPartnerAnalyticsTimeline

`func NewPartnerAnalyticsTimeline(partnerId string, period PartnerReportPeriod, managedUserId NullableString, days []PartnerAnalyticsOfDay, ) *PartnerAnalyticsTimeline`

NewPartnerAnalyticsTimeline instantiates a new PartnerAnalyticsTimeline object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerAnalyticsTimelineWithDefaults

`func NewPartnerAnalyticsTimelineWithDefaults() *PartnerAnalyticsTimeline`

NewPartnerAnalyticsTimelineWithDefaults instantiates a new PartnerAnalyticsTimeline object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPartnerId

`func (o *PartnerAnalyticsTimeline) GetPartnerId() string`

GetPartnerId returns the PartnerId field if non-nil, zero value otherwise.

### GetPartnerIdOk

`func (o *PartnerAnalyticsTimeline) GetPartnerIdOk() (*string, bool)`

GetPartnerIdOk returns a tuple with the PartnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartnerId

`func (o *PartnerAnalyticsTimeline) SetPartnerId(v string)`

SetPartnerId sets PartnerId field to given value.


### GetPeriod

`func (o *PartnerAnalyticsTimeline) GetPeriod() PartnerReportPeriod`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *PartnerAnalyticsTimeline) GetPeriodOk() (*PartnerReportPeriod, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *PartnerAnalyticsTimeline) SetPeriod(v PartnerReportPeriod)`

SetPeriod sets Period field to given value.


### GetManagedUserId

`func (o *PartnerAnalyticsTimeline) GetManagedUserId() string`

GetManagedUserId returns the ManagedUserId field if non-nil, zero value otherwise.

### GetManagedUserIdOk

`func (o *PartnerAnalyticsTimeline) GetManagedUserIdOk() (*string, bool)`

GetManagedUserIdOk returns a tuple with the ManagedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUserId

`func (o *PartnerAnalyticsTimeline) SetManagedUserId(v string)`

SetManagedUserId sets ManagedUserId field to given value.


### SetManagedUserIdNil

`func (o *PartnerAnalyticsTimeline) SetManagedUserIdNil(b bool)`

 SetManagedUserIdNil sets the value for ManagedUserId to be an explicit nil

### UnsetManagedUserId
`func (o *PartnerAnalyticsTimeline) UnsetManagedUserId()`

UnsetManagedUserId ensures that no value is present for ManagedUserId, not even an explicit nil
### GetDays

`func (o *PartnerAnalyticsTimeline) GetDays() []PartnerAnalyticsOfDay`

GetDays returns the Days field if non-nil, zero value otherwise.

### GetDaysOk

`func (o *PartnerAnalyticsTimeline) GetDaysOk() (*[]PartnerAnalyticsOfDay, bool)`

GetDaysOk returns a tuple with the Days field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDays

`func (o *PartnerAnalyticsTimeline) SetDays(v []PartnerAnalyticsOfDay)`

SetDays sets Days field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


