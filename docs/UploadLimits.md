# UploadLimits

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MultipartMaxBytes** | Pointer to **int32** | The largest file &#x60;uploadsPost&#x60; takes in one request, in bytes. The same for every account. | [optional] 
**MultipartMimeTypes** | Pointer to **[]string** | The file types &#x60;uploadsPost&#x60; takes for media (&#x60;content-property&#x60; uploads) | [optional] 
**TusEnabled** | Pointer to **bool** | Whether resumable uploads are switched on. They need a signed-in session; an API key uses &#x60;uploadsPost&#x60;. | [optional] 
**TusMaxBytes** | Pointer to **int32** | The largest file a resumable upload takes, in bytes (250 MB by default). The same for every account, whatever its plan. A file over &#x60;multipart_max_bytes&#x60; goes through a resumable upload. | [optional] 
**TusChunkSizeBytes** | Pointer to **int32** | The chunk size resumable uploads are tuned for, in bytes. A client may send smaller or larger chunks. | [optional] 
**TusMimeTypes** | Pointer to **[]string** |  | [optional] 

## Methods

### NewUploadLimits

`func NewUploadLimits() *UploadLimits`

NewUploadLimits instantiates a new UploadLimits object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUploadLimitsWithDefaults

`func NewUploadLimitsWithDefaults() *UploadLimits`

NewUploadLimitsWithDefaults instantiates a new UploadLimits object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMultipartMaxBytes

`func (o *UploadLimits) GetMultipartMaxBytes() int32`

GetMultipartMaxBytes returns the MultipartMaxBytes field if non-nil, zero value otherwise.

### GetMultipartMaxBytesOk

`func (o *UploadLimits) GetMultipartMaxBytesOk() (*int32, bool)`

GetMultipartMaxBytesOk returns a tuple with the MultipartMaxBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMultipartMaxBytes

`func (o *UploadLimits) SetMultipartMaxBytes(v int32)`

SetMultipartMaxBytes sets MultipartMaxBytes field to given value.

### HasMultipartMaxBytes

`func (o *UploadLimits) HasMultipartMaxBytes() bool`

HasMultipartMaxBytes returns a boolean if a field has been set.

### GetMultipartMimeTypes

`func (o *UploadLimits) GetMultipartMimeTypes() []string`

GetMultipartMimeTypes returns the MultipartMimeTypes field if non-nil, zero value otherwise.

### GetMultipartMimeTypesOk

`func (o *UploadLimits) GetMultipartMimeTypesOk() (*[]string, bool)`

GetMultipartMimeTypesOk returns a tuple with the MultipartMimeTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMultipartMimeTypes

`func (o *UploadLimits) SetMultipartMimeTypes(v []string)`

SetMultipartMimeTypes sets MultipartMimeTypes field to given value.

### HasMultipartMimeTypes

`func (o *UploadLimits) HasMultipartMimeTypes() bool`

HasMultipartMimeTypes returns a boolean if a field has been set.

### GetTusEnabled

`func (o *UploadLimits) GetTusEnabled() bool`

GetTusEnabled returns the TusEnabled field if non-nil, zero value otherwise.

### GetTusEnabledOk

`func (o *UploadLimits) GetTusEnabledOk() (*bool, bool)`

GetTusEnabledOk returns a tuple with the TusEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTusEnabled

`func (o *UploadLimits) SetTusEnabled(v bool)`

SetTusEnabled sets TusEnabled field to given value.

### HasTusEnabled

`func (o *UploadLimits) HasTusEnabled() bool`

HasTusEnabled returns a boolean if a field has been set.

### GetTusMaxBytes

`func (o *UploadLimits) GetTusMaxBytes() int32`

GetTusMaxBytes returns the TusMaxBytes field if non-nil, zero value otherwise.

### GetTusMaxBytesOk

`func (o *UploadLimits) GetTusMaxBytesOk() (*int32, bool)`

GetTusMaxBytesOk returns a tuple with the TusMaxBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTusMaxBytes

`func (o *UploadLimits) SetTusMaxBytes(v int32)`

SetTusMaxBytes sets TusMaxBytes field to given value.

### HasTusMaxBytes

`func (o *UploadLimits) HasTusMaxBytes() bool`

HasTusMaxBytes returns a boolean if a field has been set.

### GetTusChunkSizeBytes

`func (o *UploadLimits) GetTusChunkSizeBytes() int32`

GetTusChunkSizeBytes returns the TusChunkSizeBytes field if non-nil, zero value otherwise.

### GetTusChunkSizeBytesOk

`func (o *UploadLimits) GetTusChunkSizeBytesOk() (*int32, bool)`

GetTusChunkSizeBytesOk returns a tuple with the TusChunkSizeBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTusChunkSizeBytes

`func (o *UploadLimits) SetTusChunkSizeBytes(v int32)`

SetTusChunkSizeBytes sets TusChunkSizeBytes field to given value.

### HasTusChunkSizeBytes

`func (o *UploadLimits) HasTusChunkSizeBytes() bool`

HasTusChunkSizeBytes returns a boolean if a field has been set.

### GetTusMimeTypes

`func (o *UploadLimits) GetTusMimeTypes() []string`

GetTusMimeTypes returns the TusMimeTypes field if non-nil, zero value otherwise.

### GetTusMimeTypesOk

`func (o *UploadLimits) GetTusMimeTypesOk() (*[]string, bool)`

GetTusMimeTypesOk returns a tuple with the TusMimeTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTusMimeTypes

`func (o *UploadLimits) SetTusMimeTypes(v []string)`

SetTusMimeTypes sets TusMimeTypes field to given value.

### HasTusMimeTypes

`func (o *UploadLimits) HasTusMimeTypes() bool`

HasTusMimeTypes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


