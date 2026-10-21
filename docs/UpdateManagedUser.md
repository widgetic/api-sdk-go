# UpdateManagedUser

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExternalId** | Pointer to **string** | Updated external identifier for the managed user. Must be unique among the managed users you manage (409 otherwise). | [optional] 
**Metadata** | Pointer to **map[string]interface{}** | Updated additional metadata for the managed user | [optional] 
**IsActive** | Pointer to **bool** | Switch the managed user off (&#x60;false&#x60;) or back on (&#x60;true&#x60;). A managed user that is off keeps everything already filed under it, and that content can still be listed, but nothing new can be filed under it (&#x60;409 MANAGED_USER_INACTIVE&#x60;). Send a real boolean, not the text \&quot;false\&quot;. Switching a managed user off also ends all of its editor sessions.  | [optional] 

## Methods

### NewUpdateManagedUser

`func NewUpdateManagedUser() *UpdateManagedUser`

NewUpdateManagedUser instantiates a new UpdateManagedUser object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateManagedUserWithDefaults

`func NewUpdateManagedUserWithDefaults() *UpdateManagedUser`

NewUpdateManagedUserWithDefaults instantiates a new UpdateManagedUser object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExternalId

`func (o *UpdateManagedUser) GetExternalId() string`

GetExternalId returns the ExternalId field if non-nil, zero value otherwise.

### GetExternalIdOk

`func (o *UpdateManagedUser) GetExternalIdOk() (*string, bool)`

GetExternalIdOk returns a tuple with the ExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalId

`func (o *UpdateManagedUser) SetExternalId(v string)`

SetExternalId sets ExternalId field to given value.

### HasExternalId

`func (o *UpdateManagedUser) HasExternalId() bool`

HasExternalId returns a boolean if a field has been set.

### GetMetadata

`func (o *UpdateManagedUser) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *UpdateManagedUser) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *UpdateManagedUser) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *UpdateManagedUser) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetIsActive

`func (o *UpdateManagedUser) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *UpdateManagedUser) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *UpdateManagedUser) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *UpdateManagedUser) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


