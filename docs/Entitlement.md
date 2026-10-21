# Entitlement

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Unique identifier for the entitlement | [optional] 
**UserId** | Pointer to **string** | ID of the user (if user-level entitlement) | [optional] 
**PartnerId** | Pointer to **string** | ID of the partner (if partner-level entitlement) | [optional] 
**ManagedUserId** | Pointer to **string** | ID of the managed user (if managed user-level entitlement) | [optional] 
**Feature** | Pointer to **string** | Feature identifier that this entitlement grants access to | [optional] 
**Value** | Pointer to **string** | Value or limit for this feature | [optional] 
**ExpiresAt** | Pointer to **time.Time** | When this entitlement expires (null for permanent) | [optional] 
**Source** | Pointer to **string** | Source of the entitlement | [optional] 
**SourceId** | Pointer to **string** | ID of the source object that granted this entitlement | [optional] 
**CreatedAt** | Pointer to **time.Time** | When the entitlement was created | [optional] 
**UpdatedAt** | Pointer to **time.Time** | When the entitlement was last updated | [optional] 

## Methods

### NewEntitlement

`func NewEntitlement() *Entitlement`

NewEntitlement instantiates a new Entitlement object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEntitlementWithDefaults

`func NewEntitlementWithDefaults() *Entitlement`

NewEntitlementWithDefaults instantiates a new Entitlement object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Entitlement) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Entitlement) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Entitlement) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *Entitlement) HasId() bool`

HasId returns a boolean if a field has been set.

### GetUserId

`func (o *Entitlement) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *Entitlement) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *Entitlement) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *Entitlement) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetPartnerId

`func (o *Entitlement) GetPartnerId() string`

GetPartnerId returns the PartnerId field if non-nil, zero value otherwise.

### GetPartnerIdOk

`func (o *Entitlement) GetPartnerIdOk() (*string, bool)`

GetPartnerIdOk returns a tuple with the PartnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartnerId

`func (o *Entitlement) SetPartnerId(v string)`

SetPartnerId sets PartnerId field to given value.

### HasPartnerId

`func (o *Entitlement) HasPartnerId() bool`

HasPartnerId returns a boolean if a field has been set.

### GetManagedUserId

`func (o *Entitlement) GetManagedUserId() string`

GetManagedUserId returns the ManagedUserId field if non-nil, zero value otherwise.

### GetManagedUserIdOk

`func (o *Entitlement) GetManagedUserIdOk() (*string, bool)`

GetManagedUserIdOk returns a tuple with the ManagedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUserId

`func (o *Entitlement) SetManagedUserId(v string)`

SetManagedUserId sets ManagedUserId field to given value.

### HasManagedUserId

`func (o *Entitlement) HasManagedUserId() bool`

HasManagedUserId returns a boolean if a field has been set.

### GetFeature

`func (o *Entitlement) GetFeature() string`

GetFeature returns the Feature field if non-nil, zero value otherwise.

### GetFeatureOk

`func (o *Entitlement) GetFeatureOk() (*string, bool)`

GetFeatureOk returns a tuple with the Feature field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeature

`func (o *Entitlement) SetFeature(v string)`

SetFeature sets Feature field to given value.

### HasFeature

`func (o *Entitlement) HasFeature() bool`

HasFeature returns a boolean if a field has been set.

### GetValue

`func (o *Entitlement) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *Entitlement) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *Entitlement) SetValue(v string)`

SetValue sets Value field to given value.

### HasValue

`func (o *Entitlement) HasValue() bool`

HasValue returns a boolean if a field has been set.

### GetExpiresAt

`func (o *Entitlement) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *Entitlement) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *Entitlement) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *Entitlement) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### GetSource

`func (o *Entitlement) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *Entitlement) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *Entitlement) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *Entitlement) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetSourceId

`func (o *Entitlement) GetSourceId() string`

GetSourceId returns the SourceId field if non-nil, zero value otherwise.

### GetSourceIdOk

`func (o *Entitlement) GetSourceIdOk() (*string, bool)`

GetSourceIdOk returns a tuple with the SourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceId

`func (o *Entitlement) SetSourceId(v string)`

SetSourceId sets SourceId field to given value.

### HasSourceId

`func (o *Entitlement) HasSourceId() bool`

HasSourceId returns a boolean if a field has been set.

### GetCreatedAt

`func (o *Entitlement) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Entitlement) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Entitlement) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Entitlement) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *Entitlement) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Entitlement) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Entitlement) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Entitlement) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


