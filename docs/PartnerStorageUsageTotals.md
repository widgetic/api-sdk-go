# PartnerStorageUsageTotals

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FileCount** | **int64** |  | 
**TotalBytes** | **int64** | The size of all the files together, in bytes | 
**WidgeticStorageBytes** | **int64** | The part of &#x60;totalBytes&#x60; that is kept in Widgetic&#39;s storage | 
**PartnerStorageBytes** | **int64** | The part of &#x60;totalBytes&#x60; that is kept in your own storage destination | 

## Methods

### NewPartnerStorageUsageTotals

`func NewPartnerStorageUsageTotals(fileCount int64, totalBytes int64, widgeticStorageBytes int64, partnerStorageBytes int64, ) *PartnerStorageUsageTotals`

NewPartnerStorageUsageTotals instantiates a new PartnerStorageUsageTotals object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerStorageUsageTotalsWithDefaults

`func NewPartnerStorageUsageTotalsWithDefaults() *PartnerStorageUsageTotals`

NewPartnerStorageUsageTotalsWithDefaults instantiates a new PartnerStorageUsageTotals object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFileCount

`func (o *PartnerStorageUsageTotals) GetFileCount() int64`

GetFileCount returns the FileCount field if non-nil, zero value otherwise.

### GetFileCountOk

`func (o *PartnerStorageUsageTotals) GetFileCountOk() (*int64, bool)`

GetFileCountOk returns a tuple with the FileCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileCount

`func (o *PartnerStorageUsageTotals) SetFileCount(v int64)`

SetFileCount sets FileCount field to given value.


### GetTotalBytes

`func (o *PartnerStorageUsageTotals) GetTotalBytes() int64`

GetTotalBytes returns the TotalBytes field if non-nil, zero value otherwise.

### GetTotalBytesOk

`func (o *PartnerStorageUsageTotals) GetTotalBytesOk() (*int64, bool)`

GetTotalBytesOk returns a tuple with the TotalBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalBytes

`func (o *PartnerStorageUsageTotals) SetTotalBytes(v int64)`

SetTotalBytes sets TotalBytes field to given value.


### GetWidgeticStorageBytes

`func (o *PartnerStorageUsageTotals) GetWidgeticStorageBytes() int64`

GetWidgeticStorageBytes returns the WidgeticStorageBytes field if non-nil, zero value otherwise.

### GetWidgeticStorageBytesOk

`func (o *PartnerStorageUsageTotals) GetWidgeticStorageBytesOk() (*int64, bool)`

GetWidgeticStorageBytesOk returns a tuple with the WidgeticStorageBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidgeticStorageBytes

`func (o *PartnerStorageUsageTotals) SetWidgeticStorageBytes(v int64)`

SetWidgeticStorageBytes sets WidgeticStorageBytes field to given value.


### GetPartnerStorageBytes

`func (o *PartnerStorageUsageTotals) GetPartnerStorageBytes() int64`

GetPartnerStorageBytes returns the PartnerStorageBytes field if non-nil, zero value otherwise.

### GetPartnerStorageBytesOk

`func (o *PartnerStorageUsageTotals) GetPartnerStorageBytesOk() (*int64, bool)`

GetPartnerStorageBytesOk returns a tuple with the PartnerStorageBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartnerStorageBytes

`func (o *PartnerStorageUsageTotals) SetPartnerStorageBytes(v int64)`

SetPartnerStorageBytes sets PartnerStorageBytes field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


