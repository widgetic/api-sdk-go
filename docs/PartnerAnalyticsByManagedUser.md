# PartnerAnalyticsByManagedUser

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PartnerId** | **string** |  | 
**Period** | [**PartnerReportPeriod**](PartnerReportPeriod.md) |  | 
**ManagedUsers** | [**[]PartnerAnalyticsOfManagedUser**](PartnerAnalyticsOfManagedUser.md) |  | 
**Page** | [**PartnerReportPage**](PartnerReportPage.md) |  | 

## Methods

### NewPartnerAnalyticsByManagedUser

`func NewPartnerAnalyticsByManagedUser(partnerId string, period PartnerReportPeriod, managedUsers []PartnerAnalyticsOfManagedUser, page PartnerReportPage, ) *PartnerAnalyticsByManagedUser`

NewPartnerAnalyticsByManagedUser instantiates a new PartnerAnalyticsByManagedUser object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerAnalyticsByManagedUserWithDefaults

`func NewPartnerAnalyticsByManagedUserWithDefaults() *PartnerAnalyticsByManagedUser`

NewPartnerAnalyticsByManagedUserWithDefaults instantiates a new PartnerAnalyticsByManagedUser object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPartnerId

`func (o *PartnerAnalyticsByManagedUser) GetPartnerId() string`

GetPartnerId returns the PartnerId field if non-nil, zero value otherwise.

### GetPartnerIdOk

`func (o *PartnerAnalyticsByManagedUser) GetPartnerIdOk() (*string, bool)`

GetPartnerIdOk returns a tuple with the PartnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartnerId

`func (o *PartnerAnalyticsByManagedUser) SetPartnerId(v string)`

SetPartnerId sets PartnerId field to given value.


### GetPeriod

`func (o *PartnerAnalyticsByManagedUser) GetPeriod() PartnerReportPeriod`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *PartnerAnalyticsByManagedUser) GetPeriodOk() (*PartnerReportPeriod, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *PartnerAnalyticsByManagedUser) SetPeriod(v PartnerReportPeriod)`

SetPeriod sets Period field to given value.


### GetManagedUsers

`func (o *PartnerAnalyticsByManagedUser) GetManagedUsers() []PartnerAnalyticsOfManagedUser`

GetManagedUsers returns the ManagedUsers field if non-nil, zero value otherwise.

### GetManagedUsersOk

`func (o *PartnerAnalyticsByManagedUser) GetManagedUsersOk() (*[]PartnerAnalyticsOfManagedUser, bool)`

GetManagedUsersOk returns a tuple with the ManagedUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUsers

`func (o *PartnerAnalyticsByManagedUser) SetManagedUsers(v []PartnerAnalyticsOfManagedUser)`

SetManagedUsers sets ManagedUsers field to given value.


### GetPage

`func (o *PartnerAnalyticsByManagedUser) GetPage() PartnerReportPage`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *PartnerAnalyticsByManagedUser) GetPageOk() (*PartnerReportPage, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *PartnerAnalyticsByManagedUser) SetPage(v PartnerReportPage)`

SetPage sets Page field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


