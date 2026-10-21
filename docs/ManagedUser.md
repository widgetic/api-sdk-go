# ManagedUser

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Unique identifier for the managed user | 
**ManagerId** | **string** | ID of the user who manages this managed user | 
**ExternalId** | **string** | Your own identifier for the managed user. Unique among the managed users you manage (two different partners may use the same value). | 
**Metadata** | Pointer to **map[string]interface{}** | Additional metadata for the managed user | [optional] 
**IsActive** | Pointer to **NullableBool** | Whether new compositions, widgets and uploads can be filed under this managed user. &#x60;false&#x60; means it has been switched off (&#x60;updateManagedUser&#x60; with &#x60;is_active: false&#x60;): what it already has stays, and filing anything new under it answers &#x60;409 MANAGED_USER_INACTIVE&#x60;. A record from before the switch existed may answer &#x60;null&#x60;, which counts as on.  | [optional] 
**CreatedAt** | **time.Time** | Timestamp when the managed user was created | 
**UpdatedAt** | **time.Time** | Timestamp when the managed user was last updated | 

## Methods

### NewManagedUser

`func NewManagedUser(id string, managerId string, externalId string, createdAt time.Time, updatedAt time.Time, ) *ManagedUser`

NewManagedUser instantiates a new ManagedUser object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManagedUserWithDefaults

`func NewManagedUserWithDefaults() *ManagedUser`

NewManagedUserWithDefaults instantiates a new ManagedUser object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ManagedUser) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManagedUser) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManagedUser) SetId(v string)`

SetId sets Id field to given value.


### GetManagerId

`func (o *ManagedUser) GetManagerId() string`

GetManagerId returns the ManagerId field if non-nil, zero value otherwise.

### GetManagerIdOk

`func (o *ManagedUser) GetManagerIdOk() (*string, bool)`

GetManagerIdOk returns a tuple with the ManagerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagerId

`func (o *ManagedUser) SetManagerId(v string)`

SetManagerId sets ManagerId field to given value.


### GetExternalId

`func (o *ManagedUser) GetExternalId() string`

GetExternalId returns the ExternalId field if non-nil, zero value otherwise.

### GetExternalIdOk

`func (o *ManagedUser) GetExternalIdOk() (*string, bool)`

GetExternalIdOk returns a tuple with the ExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalId

`func (o *ManagedUser) SetExternalId(v string)`

SetExternalId sets ExternalId field to given value.


### GetMetadata

`func (o *ManagedUser) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *ManagedUser) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *ManagedUser) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *ManagedUser) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetIsActive

`func (o *ManagedUser) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *ManagedUser) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *ManagedUser) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *ManagedUser) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### SetIsActiveNil

`func (o *ManagedUser) SetIsActiveNil(b bool)`

 SetIsActiveNil sets the value for IsActive to be an explicit nil

### UnsetIsActive
`func (o *ManagedUser) UnsetIsActive()`

UnsetIsActive ensures that no value is present for IsActive, not even an explicit nil
### GetCreatedAt

`func (o *ManagedUser) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ManagedUser) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ManagedUser) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *ManagedUser) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ManagedUser) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ManagedUser) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


