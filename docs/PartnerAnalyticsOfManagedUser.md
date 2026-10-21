# PartnerAnalyticsOfManagedUser

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ManagedUserId** | **string** |  | 
**ExternalId** | **NullableString** | Your own identifier for the managed user | 
**Name** | **NullableString** |  | 
**IsActive** | **NullableBool** |  | 
**WidgetsMade** | **int64** | How many widgets are filed under the managed user (all time, not only in the period) | 
**CompositionsMade** | **int64** | How many compositions are filed under the managed user (all time, not only in the period) | 
**Views** | **int64** |  | 
**Interactions** | **int64** |  | 
**Visitors** | **int64** |  | 
**LastEventAt** | **NullableTime** | When the newest counted view or interaction happened. Null when there was none in the period. | 

## Methods

### NewPartnerAnalyticsOfManagedUser

`func NewPartnerAnalyticsOfManagedUser(managedUserId string, externalId NullableString, name NullableString, isActive NullableBool, widgetsMade int64, compositionsMade int64, views int64, interactions int64, visitors int64, lastEventAt NullableTime, ) *PartnerAnalyticsOfManagedUser`

NewPartnerAnalyticsOfManagedUser instantiates a new PartnerAnalyticsOfManagedUser object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerAnalyticsOfManagedUserWithDefaults

`func NewPartnerAnalyticsOfManagedUserWithDefaults() *PartnerAnalyticsOfManagedUser`

NewPartnerAnalyticsOfManagedUserWithDefaults instantiates a new PartnerAnalyticsOfManagedUser object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetManagedUserId

`func (o *PartnerAnalyticsOfManagedUser) GetManagedUserId() string`

GetManagedUserId returns the ManagedUserId field if non-nil, zero value otherwise.

### GetManagedUserIdOk

`func (o *PartnerAnalyticsOfManagedUser) GetManagedUserIdOk() (*string, bool)`

GetManagedUserIdOk returns a tuple with the ManagedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUserId

`func (o *PartnerAnalyticsOfManagedUser) SetManagedUserId(v string)`

SetManagedUserId sets ManagedUserId field to given value.


### GetExternalId

`func (o *PartnerAnalyticsOfManagedUser) GetExternalId() string`

GetExternalId returns the ExternalId field if non-nil, zero value otherwise.

### GetExternalIdOk

`func (o *PartnerAnalyticsOfManagedUser) GetExternalIdOk() (*string, bool)`

GetExternalIdOk returns a tuple with the ExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalId

`func (o *PartnerAnalyticsOfManagedUser) SetExternalId(v string)`

SetExternalId sets ExternalId field to given value.


### SetExternalIdNil

`func (o *PartnerAnalyticsOfManagedUser) SetExternalIdNil(b bool)`

 SetExternalIdNil sets the value for ExternalId to be an explicit nil

### UnsetExternalId
`func (o *PartnerAnalyticsOfManagedUser) UnsetExternalId()`

UnsetExternalId ensures that no value is present for ExternalId, not even an explicit nil
### GetName

`func (o *PartnerAnalyticsOfManagedUser) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PartnerAnalyticsOfManagedUser) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PartnerAnalyticsOfManagedUser) SetName(v string)`

SetName sets Name field to given value.


### SetNameNil

`func (o *PartnerAnalyticsOfManagedUser) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *PartnerAnalyticsOfManagedUser) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetIsActive

`func (o *PartnerAnalyticsOfManagedUser) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *PartnerAnalyticsOfManagedUser) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *PartnerAnalyticsOfManagedUser) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.


### SetIsActiveNil

`func (o *PartnerAnalyticsOfManagedUser) SetIsActiveNil(b bool)`

 SetIsActiveNil sets the value for IsActive to be an explicit nil

### UnsetIsActive
`func (o *PartnerAnalyticsOfManagedUser) UnsetIsActive()`

UnsetIsActive ensures that no value is present for IsActive, not even an explicit nil
### GetWidgetsMade

`func (o *PartnerAnalyticsOfManagedUser) GetWidgetsMade() int64`

GetWidgetsMade returns the WidgetsMade field if non-nil, zero value otherwise.

### GetWidgetsMadeOk

`func (o *PartnerAnalyticsOfManagedUser) GetWidgetsMadeOk() (*int64, bool)`

GetWidgetsMadeOk returns a tuple with the WidgetsMade field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidgetsMade

`func (o *PartnerAnalyticsOfManagedUser) SetWidgetsMade(v int64)`

SetWidgetsMade sets WidgetsMade field to given value.


### GetCompositionsMade

`func (o *PartnerAnalyticsOfManagedUser) GetCompositionsMade() int64`

GetCompositionsMade returns the CompositionsMade field if non-nil, zero value otherwise.

### GetCompositionsMadeOk

`func (o *PartnerAnalyticsOfManagedUser) GetCompositionsMadeOk() (*int64, bool)`

GetCompositionsMadeOk returns a tuple with the CompositionsMade field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompositionsMade

`func (o *PartnerAnalyticsOfManagedUser) SetCompositionsMade(v int64)`

SetCompositionsMade sets CompositionsMade field to given value.


### GetViews

`func (o *PartnerAnalyticsOfManagedUser) GetViews() int64`

GetViews returns the Views field if non-nil, zero value otherwise.

### GetViewsOk

`func (o *PartnerAnalyticsOfManagedUser) GetViewsOk() (*int64, bool)`

GetViewsOk returns a tuple with the Views field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetViews

`func (o *PartnerAnalyticsOfManagedUser) SetViews(v int64)`

SetViews sets Views field to given value.


### GetInteractions

`func (o *PartnerAnalyticsOfManagedUser) GetInteractions() int64`

GetInteractions returns the Interactions field if non-nil, zero value otherwise.

### GetInteractionsOk

`func (o *PartnerAnalyticsOfManagedUser) GetInteractionsOk() (*int64, bool)`

GetInteractionsOk returns a tuple with the Interactions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInteractions

`func (o *PartnerAnalyticsOfManagedUser) SetInteractions(v int64)`

SetInteractions sets Interactions field to given value.


### GetVisitors

`func (o *PartnerAnalyticsOfManagedUser) GetVisitors() int64`

GetVisitors returns the Visitors field if non-nil, zero value otherwise.

### GetVisitorsOk

`func (o *PartnerAnalyticsOfManagedUser) GetVisitorsOk() (*int64, bool)`

GetVisitorsOk returns a tuple with the Visitors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisitors

`func (o *PartnerAnalyticsOfManagedUser) SetVisitors(v int64)`

SetVisitors sets Visitors field to given value.


### GetLastEventAt

`func (o *PartnerAnalyticsOfManagedUser) GetLastEventAt() time.Time`

GetLastEventAt returns the LastEventAt field if non-nil, zero value otherwise.

### GetLastEventAtOk

`func (o *PartnerAnalyticsOfManagedUser) GetLastEventAtOk() (*time.Time, bool)`

GetLastEventAtOk returns a tuple with the LastEventAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastEventAt

`func (o *PartnerAnalyticsOfManagedUser) SetLastEventAt(v time.Time)`

SetLastEventAt sets LastEventAt field to given value.


### SetLastEventAtNil

`func (o *PartnerAnalyticsOfManagedUser) SetLastEventAtNil(b bool)`

 SetLastEventAtNil sets the value for LastEventAt to be an explicit nil

### UnsetLastEventAt
`func (o *PartnerAnalyticsOfManagedUser) UnsetLastEventAt()`

UnsetLastEventAt ensures that no value is present for LastEventAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


