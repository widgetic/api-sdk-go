# PartnerStorageUsage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PartnerId** | **string** |  | 
**Totals** | [**PartnerStorageUsageTotals**](PartnerStorageUsageTotals.md) |  | 
**ManagedUsers** | [**[]PartnerStorageUsageOfManagedUser**](PartnerStorageUsageOfManagedUser.md) |  | 
**Page** | [**PartnerReportPage**](PartnerReportPage.md) |  | 

## Methods

### NewPartnerStorageUsage

`func NewPartnerStorageUsage(partnerId string, totals PartnerStorageUsageTotals, managedUsers []PartnerStorageUsageOfManagedUser, page PartnerReportPage, ) *PartnerStorageUsage`

NewPartnerStorageUsage instantiates a new PartnerStorageUsage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerStorageUsageWithDefaults

`func NewPartnerStorageUsageWithDefaults() *PartnerStorageUsage`

NewPartnerStorageUsageWithDefaults instantiates a new PartnerStorageUsage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPartnerId

`func (o *PartnerStorageUsage) GetPartnerId() string`

GetPartnerId returns the PartnerId field if non-nil, zero value otherwise.

### GetPartnerIdOk

`func (o *PartnerStorageUsage) GetPartnerIdOk() (*string, bool)`

GetPartnerIdOk returns a tuple with the PartnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartnerId

`func (o *PartnerStorageUsage) SetPartnerId(v string)`

SetPartnerId sets PartnerId field to given value.


### GetTotals

`func (o *PartnerStorageUsage) GetTotals() PartnerStorageUsageTotals`

GetTotals returns the Totals field if non-nil, zero value otherwise.

### GetTotalsOk

`func (o *PartnerStorageUsage) GetTotalsOk() (*PartnerStorageUsageTotals, bool)`

GetTotalsOk returns a tuple with the Totals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotals

`func (o *PartnerStorageUsage) SetTotals(v PartnerStorageUsageTotals)`

SetTotals sets Totals field to given value.


### GetManagedUsers

`func (o *PartnerStorageUsage) GetManagedUsers() []PartnerStorageUsageOfManagedUser`

GetManagedUsers returns the ManagedUsers field if non-nil, zero value otherwise.

### GetManagedUsersOk

`func (o *PartnerStorageUsage) GetManagedUsersOk() (*[]PartnerStorageUsageOfManagedUser, bool)`

GetManagedUsersOk returns a tuple with the ManagedUsers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUsers

`func (o *PartnerStorageUsage) SetManagedUsers(v []PartnerStorageUsageOfManagedUser)`

SetManagedUsers sets ManagedUsers field to given value.


### GetPage

`func (o *PartnerStorageUsage) GetPage() PartnerReportPage`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *PartnerStorageUsage) GetPageOk() (*PartnerReportPage, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *PartnerStorageUsage) SetPage(v PartnerReportPage)`

SetPage sets Page field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


