# GetManagedUserStorageUsage200ResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TotalBytes** | **int32** |  | 
**FileCount** | **int32** |  | 
**ByPurpose** | [**GetManagedUserStorageUsage200ResponseDataByPurpose**](GetManagedUserStorageUsage200ResponseDataByPurpose.md) |  | 

## Methods

### NewGetManagedUserStorageUsage200ResponseData

`func NewGetManagedUserStorageUsage200ResponseData(totalBytes int32, fileCount int32, byPurpose GetManagedUserStorageUsage200ResponseDataByPurpose, ) *GetManagedUserStorageUsage200ResponseData`

NewGetManagedUserStorageUsage200ResponseData instantiates a new GetManagedUserStorageUsage200ResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetManagedUserStorageUsage200ResponseDataWithDefaults

`func NewGetManagedUserStorageUsage200ResponseDataWithDefaults() *GetManagedUserStorageUsage200ResponseData`

NewGetManagedUserStorageUsage200ResponseDataWithDefaults instantiates a new GetManagedUserStorageUsage200ResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotalBytes

`func (o *GetManagedUserStorageUsage200ResponseData) GetTotalBytes() int32`

GetTotalBytes returns the TotalBytes field if non-nil, zero value otherwise.

### GetTotalBytesOk

`func (o *GetManagedUserStorageUsage200ResponseData) GetTotalBytesOk() (*int32, bool)`

GetTotalBytesOk returns a tuple with the TotalBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalBytes

`func (o *GetManagedUserStorageUsage200ResponseData) SetTotalBytes(v int32)`

SetTotalBytes sets TotalBytes field to given value.


### GetFileCount

`func (o *GetManagedUserStorageUsage200ResponseData) GetFileCount() int32`

GetFileCount returns the FileCount field if non-nil, zero value otherwise.

### GetFileCountOk

`func (o *GetManagedUserStorageUsage200ResponseData) GetFileCountOk() (*int32, bool)`

GetFileCountOk returns a tuple with the FileCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileCount

`func (o *GetManagedUserStorageUsage200ResponseData) SetFileCount(v int32)`

SetFileCount sets FileCount field to given value.


### GetByPurpose

`func (o *GetManagedUserStorageUsage200ResponseData) GetByPurpose() GetManagedUserStorageUsage200ResponseDataByPurpose`

GetByPurpose returns the ByPurpose field if non-nil, zero value otherwise.

### GetByPurposeOk

`func (o *GetManagedUserStorageUsage200ResponseData) GetByPurposeOk() (*GetManagedUserStorageUsage200ResponseDataByPurpose, bool)`

GetByPurposeOk returns a tuple with the ByPurpose field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetByPurpose

`func (o *GetManagedUserStorageUsage200ResponseData) SetByPurpose(v GetManagedUserStorageUsage200ResponseDataByPurpose)`

SetByPurpose sets ByPurpose field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


