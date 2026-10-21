# PartnerAnalyticsSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PartnerId** | **string** |  | 
**Period** | [**PartnerReportPeriod**](PartnerReportPeriod.md) |  | 
**ManagedUserId** | **NullableString** | The managed user the report is narrowed to. Null for the whole account. | 
**Views** | **int64** | How many times a composition was shown to a visitor | 
**Interactions** | **int64** | How many times a visitor did something with a composition | 
**Visitors** | **int64** | How many different visitors viewed. A visitor is a browsing session; an event that carries no session is counted for the signed-in user instead. An event that carries neither is a view and no visitor.  | 
**CompositionsViewed** | **int64** | How many different compositions were viewed | 
**ManagedUsersViewed** | **int64** | How many different managed users had a composition viewed | 

## Methods

### NewPartnerAnalyticsSummary

`func NewPartnerAnalyticsSummary(partnerId string, period PartnerReportPeriod, managedUserId NullableString, views int64, interactions int64, visitors int64, compositionsViewed int64, managedUsersViewed int64, ) *PartnerAnalyticsSummary`

NewPartnerAnalyticsSummary instantiates a new PartnerAnalyticsSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerAnalyticsSummaryWithDefaults

`func NewPartnerAnalyticsSummaryWithDefaults() *PartnerAnalyticsSummary`

NewPartnerAnalyticsSummaryWithDefaults instantiates a new PartnerAnalyticsSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPartnerId

`func (o *PartnerAnalyticsSummary) GetPartnerId() string`

GetPartnerId returns the PartnerId field if non-nil, zero value otherwise.

### GetPartnerIdOk

`func (o *PartnerAnalyticsSummary) GetPartnerIdOk() (*string, bool)`

GetPartnerIdOk returns a tuple with the PartnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartnerId

`func (o *PartnerAnalyticsSummary) SetPartnerId(v string)`

SetPartnerId sets PartnerId field to given value.


### GetPeriod

`func (o *PartnerAnalyticsSummary) GetPeriod() PartnerReportPeriod`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *PartnerAnalyticsSummary) GetPeriodOk() (*PartnerReportPeriod, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *PartnerAnalyticsSummary) SetPeriod(v PartnerReportPeriod)`

SetPeriod sets Period field to given value.


### GetManagedUserId

`func (o *PartnerAnalyticsSummary) GetManagedUserId() string`

GetManagedUserId returns the ManagedUserId field if non-nil, zero value otherwise.

### GetManagedUserIdOk

`func (o *PartnerAnalyticsSummary) GetManagedUserIdOk() (*string, bool)`

GetManagedUserIdOk returns a tuple with the ManagedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUserId

`func (o *PartnerAnalyticsSummary) SetManagedUserId(v string)`

SetManagedUserId sets ManagedUserId field to given value.


### SetManagedUserIdNil

`func (o *PartnerAnalyticsSummary) SetManagedUserIdNil(b bool)`

 SetManagedUserIdNil sets the value for ManagedUserId to be an explicit nil

### UnsetManagedUserId
`func (o *PartnerAnalyticsSummary) UnsetManagedUserId()`

UnsetManagedUserId ensures that no value is present for ManagedUserId, not even an explicit nil
### GetViews

`func (o *PartnerAnalyticsSummary) GetViews() int64`

GetViews returns the Views field if non-nil, zero value otherwise.

### GetViewsOk

`func (o *PartnerAnalyticsSummary) GetViewsOk() (*int64, bool)`

GetViewsOk returns a tuple with the Views field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetViews

`func (o *PartnerAnalyticsSummary) SetViews(v int64)`

SetViews sets Views field to given value.


### GetInteractions

`func (o *PartnerAnalyticsSummary) GetInteractions() int64`

GetInteractions returns the Interactions field if non-nil, zero value otherwise.

### GetInteractionsOk

`func (o *PartnerAnalyticsSummary) GetInteractionsOk() (*int64, bool)`

GetInteractionsOk returns a tuple with the Interactions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInteractions

`func (o *PartnerAnalyticsSummary) SetInteractions(v int64)`

SetInteractions sets Interactions field to given value.


### GetVisitors

`func (o *PartnerAnalyticsSummary) GetVisitors() int64`

GetVisitors returns the Visitors field if non-nil, zero value otherwise.

### GetVisitorsOk

`func (o *PartnerAnalyticsSummary) GetVisitorsOk() (*int64, bool)`

GetVisitorsOk returns a tuple with the Visitors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisitors

`func (o *PartnerAnalyticsSummary) SetVisitors(v int64)`

SetVisitors sets Visitors field to given value.


### GetCompositionsViewed

`func (o *PartnerAnalyticsSummary) GetCompositionsViewed() int64`

GetCompositionsViewed returns the CompositionsViewed field if non-nil, zero value otherwise.

### GetCompositionsViewedOk

`func (o *PartnerAnalyticsSummary) GetCompositionsViewedOk() (*int64, bool)`

GetCompositionsViewedOk returns a tuple with the CompositionsViewed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompositionsViewed

`func (o *PartnerAnalyticsSummary) SetCompositionsViewed(v int64)`

SetCompositionsViewed sets CompositionsViewed field to given value.


### GetManagedUsersViewed

`func (o *PartnerAnalyticsSummary) GetManagedUsersViewed() int64`

GetManagedUsersViewed returns the ManagedUsersViewed field if non-nil, zero value otherwise.

### GetManagedUsersViewedOk

`func (o *PartnerAnalyticsSummary) GetManagedUsersViewedOk() (*int64, bool)`

GetManagedUsersViewedOk returns a tuple with the ManagedUsersViewed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUsersViewed

`func (o *PartnerAnalyticsSummary) SetManagedUsersViewed(v int64)`

SetManagedUsersViewed sets ManagedUsersViewed field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


