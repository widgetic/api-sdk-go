# PartnerAnalyticsTopWidgets

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PartnerId** | **string** |  | 
**Period** | [**PartnerReportPeriod**](PartnerReportPeriod.md) |  | 
**ManagedUserId** | **NullableString** | The managed user the report is narrowed to. Null for the whole account. | 
**Widgets** | [**[]PartnerAnalyticsOfWidget**](PartnerAnalyticsOfWidget.md) |  | 

## Methods

### NewPartnerAnalyticsTopWidgets

`func NewPartnerAnalyticsTopWidgets(partnerId string, period PartnerReportPeriod, managedUserId NullableString, widgets []PartnerAnalyticsOfWidget, ) *PartnerAnalyticsTopWidgets`

NewPartnerAnalyticsTopWidgets instantiates a new PartnerAnalyticsTopWidgets object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerAnalyticsTopWidgetsWithDefaults

`func NewPartnerAnalyticsTopWidgetsWithDefaults() *PartnerAnalyticsTopWidgets`

NewPartnerAnalyticsTopWidgetsWithDefaults instantiates a new PartnerAnalyticsTopWidgets object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPartnerId

`func (o *PartnerAnalyticsTopWidgets) GetPartnerId() string`

GetPartnerId returns the PartnerId field if non-nil, zero value otherwise.

### GetPartnerIdOk

`func (o *PartnerAnalyticsTopWidgets) GetPartnerIdOk() (*string, bool)`

GetPartnerIdOk returns a tuple with the PartnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartnerId

`func (o *PartnerAnalyticsTopWidgets) SetPartnerId(v string)`

SetPartnerId sets PartnerId field to given value.


### GetPeriod

`func (o *PartnerAnalyticsTopWidgets) GetPeriod() PartnerReportPeriod`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *PartnerAnalyticsTopWidgets) GetPeriodOk() (*PartnerReportPeriod, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *PartnerAnalyticsTopWidgets) SetPeriod(v PartnerReportPeriod)`

SetPeriod sets Period field to given value.


### GetManagedUserId

`func (o *PartnerAnalyticsTopWidgets) GetManagedUserId() string`

GetManagedUserId returns the ManagedUserId field if non-nil, zero value otherwise.

### GetManagedUserIdOk

`func (o *PartnerAnalyticsTopWidgets) GetManagedUserIdOk() (*string, bool)`

GetManagedUserIdOk returns a tuple with the ManagedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUserId

`func (o *PartnerAnalyticsTopWidgets) SetManagedUserId(v string)`

SetManagedUserId sets ManagedUserId field to given value.


### SetManagedUserIdNil

`func (o *PartnerAnalyticsTopWidgets) SetManagedUserIdNil(b bool)`

 SetManagedUserIdNil sets the value for ManagedUserId to be an explicit nil

### UnsetManagedUserId
`func (o *PartnerAnalyticsTopWidgets) UnsetManagedUserId()`

UnsetManagedUserId ensures that no value is present for ManagedUserId, not even an explicit nil
### GetWidgets

`func (o *PartnerAnalyticsTopWidgets) GetWidgets() []PartnerAnalyticsOfWidget`

GetWidgets returns the Widgets field if non-nil, zero value otherwise.

### GetWidgetsOk

`func (o *PartnerAnalyticsTopWidgets) GetWidgetsOk() (*[]PartnerAnalyticsOfWidget, bool)`

GetWidgetsOk returns a tuple with the Widgets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidgets

`func (o *PartnerAnalyticsTopWidgets) SetWidgets(v []PartnerAnalyticsOfWidget)`

SetWidgets sets Widgets field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


