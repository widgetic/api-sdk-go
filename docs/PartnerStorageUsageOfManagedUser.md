# PartnerStorageUsageOfManagedUser

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ManagedUserId** | **NullableString** | Widgetic&#39;s id for the managed user. Null for the files that are not filed under one. | 
**ExternalId** | **NullableString** | Your own identifier for the managed user | 
**Name** | **NullableString** |  | 
**IsActive** | **NullableBool** | False when the managed user is switched off | 
**FileCount** | **int64** |  | 
**TotalBytes** | **int64** |  | 
**WidgeticStorageBytes** | **int64** |  | 
**PartnerStorageBytes** | **int64** |  | 
**LastUploadAt** | **NullableTime** | When the newest of these files was stored | 

## Methods

### NewPartnerStorageUsageOfManagedUser

`func NewPartnerStorageUsageOfManagedUser(managedUserId NullableString, externalId NullableString, name NullableString, isActive NullableBool, fileCount int64, totalBytes int64, widgeticStorageBytes int64, partnerStorageBytes int64, lastUploadAt NullableTime, ) *PartnerStorageUsageOfManagedUser`

NewPartnerStorageUsageOfManagedUser instantiates a new PartnerStorageUsageOfManagedUser object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerStorageUsageOfManagedUserWithDefaults

`func NewPartnerStorageUsageOfManagedUserWithDefaults() *PartnerStorageUsageOfManagedUser`

NewPartnerStorageUsageOfManagedUserWithDefaults instantiates a new PartnerStorageUsageOfManagedUser object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetManagedUserId

`func (o *PartnerStorageUsageOfManagedUser) GetManagedUserId() string`

GetManagedUserId returns the ManagedUserId field if non-nil, zero value otherwise.

### GetManagedUserIdOk

`func (o *PartnerStorageUsageOfManagedUser) GetManagedUserIdOk() (*string, bool)`

GetManagedUserIdOk returns a tuple with the ManagedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUserId

`func (o *PartnerStorageUsageOfManagedUser) SetManagedUserId(v string)`

SetManagedUserId sets ManagedUserId field to given value.


### SetManagedUserIdNil

`func (o *PartnerStorageUsageOfManagedUser) SetManagedUserIdNil(b bool)`

 SetManagedUserIdNil sets the value for ManagedUserId to be an explicit nil

### UnsetManagedUserId
`func (o *PartnerStorageUsageOfManagedUser) UnsetManagedUserId()`

UnsetManagedUserId ensures that no value is present for ManagedUserId, not even an explicit nil
### GetExternalId

`func (o *PartnerStorageUsageOfManagedUser) GetExternalId() string`

GetExternalId returns the ExternalId field if non-nil, zero value otherwise.

### GetExternalIdOk

`func (o *PartnerStorageUsageOfManagedUser) GetExternalIdOk() (*string, bool)`

GetExternalIdOk returns a tuple with the ExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalId

`func (o *PartnerStorageUsageOfManagedUser) SetExternalId(v string)`

SetExternalId sets ExternalId field to given value.


### SetExternalIdNil

`func (o *PartnerStorageUsageOfManagedUser) SetExternalIdNil(b bool)`

 SetExternalIdNil sets the value for ExternalId to be an explicit nil

### UnsetExternalId
`func (o *PartnerStorageUsageOfManagedUser) UnsetExternalId()`

UnsetExternalId ensures that no value is present for ExternalId, not even an explicit nil
### GetName

`func (o *PartnerStorageUsageOfManagedUser) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PartnerStorageUsageOfManagedUser) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PartnerStorageUsageOfManagedUser) SetName(v string)`

SetName sets Name field to given value.


### SetNameNil

`func (o *PartnerStorageUsageOfManagedUser) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *PartnerStorageUsageOfManagedUser) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetIsActive

`func (o *PartnerStorageUsageOfManagedUser) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *PartnerStorageUsageOfManagedUser) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *PartnerStorageUsageOfManagedUser) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.


### SetIsActiveNil

`func (o *PartnerStorageUsageOfManagedUser) SetIsActiveNil(b bool)`

 SetIsActiveNil sets the value for IsActive to be an explicit nil

### UnsetIsActive
`func (o *PartnerStorageUsageOfManagedUser) UnsetIsActive()`

UnsetIsActive ensures that no value is present for IsActive, not even an explicit nil
### GetFileCount

`func (o *PartnerStorageUsageOfManagedUser) GetFileCount() int64`

GetFileCount returns the FileCount field if non-nil, zero value otherwise.

### GetFileCountOk

`func (o *PartnerStorageUsageOfManagedUser) GetFileCountOk() (*int64, bool)`

GetFileCountOk returns a tuple with the FileCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileCount

`func (o *PartnerStorageUsageOfManagedUser) SetFileCount(v int64)`

SetFileCount sets FileCount field to given value.


### GetTotalBytes

`func (o *PartnerStorageUsageOfManagedUser) GetTotalBytes() int64`

GetTotalBytes returns the TotalBytes field if non-nil, zero value otherwise.

### GetTotalBytesOk

`func (o *PartnerStorageUsageOfManagedUser) GetTotalBytesOk() (*int64, bool)`

GetTotalBytesOk returns a tuple with the TotalBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalBytes

`func (o *PartnerStorageUsageOfManagedUser) SetTotalBytes(v int64)`

SetTotalBytes sets TotalBytes field to given value.


### GetWidgeticStorageBytes

`func (o *PartnerStorageUsageOfManagedUser) GetWidgeticStorageBytes() int64`

GetWidgeticStorageBytes returns the WidgeticStorageBytes field if non-nil, zero value otherwise.

### GetWidgeticStorageBytesOk

`func (o *PartnerStorageUsageOfManagedUser) GetWidgeticStorageBytesOk() (*int64, bool)`

GetWidgeticStorageBytesOk returns a tuple with the WidgeticStorageBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidgeticStorageBytes

`func (o *PartnerStorageUsageOfManagedUser) SetWidgeticStorageBytes(v int64)`

SetWidgeticStorageBytes sets WidgeticStorageBytes field to given value.


### GetPartnerStorageBytes

`func (o *PartnerStorageUsageOfManagedUser) GetPartnerStorageBytes() int64`

GetPartnerStorageBytes returns the PartnerStorageBytes field if non-nil, zero value otherwise.

### GetPartnerStorageBytesOk

`func (o *PartnerStorageUsageOfManagedUser) GetPartnerStorageBytesOk() (*int64, bool)`

GetPartnerStorageBytesOk returns a tuple with the PartnerStorageBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartnerStorageBytes

`func (o *PartnerStorageUsageOfManagedUser) SetPartnerStorageBytes(v int64)`

SetPartnerStorageBytes sets PartnerStorageBytes field to given value.


### GetLastUploadAt

`func (o *PartnerStorageUsageOfManagedUser) GetLastUploadAt() time.Time`

GetLastUploadAt returns the LastUploadAt field if non-nil, zero value otherwise.

### GetLastUploadAtOk

`func (o *PartnerStorageUsageOfManagedUser) GetLastUploadAtOk() (*time.Time, bool)`

GetLastUploadAtOk returns a tuple with the LastUploadAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUploadAt

`func (o *PartnerStorageUsageOfManagedUser) SetLastUploadAt(v time.Time)`

SetLastUploadAt sets LastUploadAt field to given value.


### SetLastUploadAtNil

`func (o *PartnerStorageUsageOfManagedUser) SetLastUploadAtNil(b bool)`

 SetLastUploadAtNil sets the value for LastUploadAt to be an explicit nil

### UnsetLastUploadAt
`func (o *PartnerStorageUsageOfManagedUser) UnsetLastUploadAt()`

UnsetLastUploadAt ensures that no value is present for LastUploadAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


