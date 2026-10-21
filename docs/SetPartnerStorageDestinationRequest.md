# SetPartnerStorageDestinationRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Endpoint** | **string** | The HTTPS address of the S3-compatible service, scheme and host only (no path, port or credentials). It must be a host name, not an IP address, and must resolve to the public internet.  | 
**Region** | **string** | The region the service signs requests for. Use auto where the service says so (such as Cloudflare R2). | 
**Bucket** | **string** |  | 
**KeyPrefix** | Pointer to **string** | A folder inside the bucket to write every file under, for example widgetic/uploads. Folders are made of letters, digits, dots, hyphens and underscores. Leave it out to write at the root of the bucket.  | [optional] [default to ""]
**PublicBaseUrl** | **string** | Where the stored files are served from: the bucket&#39;s public address, or a CDN in front of it. The address of a file is this value, a slash and the file&#39;s key in the bucket, which starts with the key prefix. A path is allowed (https://media.example.com/files/acme-widget-media).  | 
**ForcePathStyle** | Pointer to **bool** | Put the bucket name in the path of a request. Every S3-compatible service supports this; set it to false only for a service that needs the bucket name in the host name.  | [optional] [default to true]
**AccessKeyId** | **string** | The id of an access key that may put objects into the bucket | 
**SecretAccessKey** | **string** | The secret of that access key. It is stored encrypted and is never returned. | 

## Methods

### NewSetPartnerStorageDestinationRequest

`func NewSetPartnerStorageDestinationRequest(endpoint string, region string, bucket string, publicBaseUrl string, accessKeyId string, secretAccessKey string, ) *SetPartnerStorageDestinationRequest`

NewSetPartnerStorageDestinationRequest instantiates a new SetPartnerStorageDestinationRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSetPartnerStorageDestinationRequestWithDefaults

`func NewSetPartnerStorageDestinationRequestWithDefaults() *SetPartnerStorageDestinationRequest`

NewSetPartnerStorageDestinationRequestWithDefaults instantiates a new SetPartnerStorageDestinationRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEndpoint

`func (o *SetPartnerStorageDestinationRequest) GetEndpoint() string`

GetEndpoint returns the Endpoint field if non-nil, zero value otherwise.

### GetEndpointOk

`func (o *SetPartnerStorageDestinationRequest) GetEndpointOk() (*string, bool)`

GetEndpointOk returns a tuple with the Endpoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndpoint

`func (o *SetPartnerStorageDestinationRequest) SetEndpoint(v string)`

SetEndpoint sets Endpoint field to given value.


### GetRegion

`func (o *SetPartnerStorageDestinationRequest) GetRegion() string`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *SetPartnerStorageDestinationRequest) GetRegionOk() (*string, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *SetPartnerStorageDestinationRequest) SetRegion(v string)`

SetRegion sets Region field to given value.


### GetBucket

`func (o *SetPartnerStorageDestinationRequest) GetBucket() string`

GetBucket returns the Bucket field if non-nil, zero value otherwise.

### GetBucketOk

`func (o *SetPartnerStorageDestinationRequest) GetBucketOk() (*string, bool)`

GetBucketOk returns a tuple with the Bucket field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBucket

`func (o *SetPartnerStorageDestinationRequest) SetBucket(v string)`

SetBucket sets Bucket field to given value.


### GetKeyPrefix

`func (o *SetPartnerStorageDestinationRequest) GetKeyPrefix() string`

GetKeyPrefix returns the KeyPrefix field if non-nil, zero value otherwise.

### GetKeyPrefixOk

`func (o *SetPartnerStorageDestinationRequest) GetKeyPrefixOk() (*string, bool)`

GetKeyPrefixOk returns a tuple with the KeyPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyPrefix

`func (o *SetPartnerStorageDestinationRequest) SetKeyPrefix(v string)`

SetKeyPrefix sets KeyPrefix field to given value.

### HasKeyPrefix

`func (o *SetPartnerStorageDestinationRequest) HasKeyPrefix() bool`

HasKeyPrefix returns a boolean if a field has been set.

### GetPublicBaseUrl

`func (o *SetPartnerStorageDestinationRequest) GetPublicBaseUrl() string`

GetPublicBaseUrl returns the PublicBaseUrl field if non-nil, zero value otherwise.

### GetPublicBaseUrlOk

`func (o *SetPartnerStorageDestinationRequest) GetPublicBaseUrlOk() (*string, bool)`

GetPublicBaseUrlOk returns a tuple with the PublicBaseUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicBaseUrl

`func (o *SetPartnerStorageDestinationRequest) SetPublicBaseUrl(v string)`

SetPublicBaseUrl sets PublicBaseUrl field to given value.


### GetForcePathStyle

`func (o *SetPartnerStorageDestinationRequest) GetForcePathStyle() bool`

GetForcePathStyle returns the ForcePathStyle field if non-nil, zero value otherwise.

### GetForcePathStyleOk

`func (o *SetPartnerStorageDestinationRequest) GetForcePathStyleOk() (*bool, bool)`

GetForcePathStyleOk returns a tuple with the ForcePathStyle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForcePathStyle

`func (o *SetPartnerStorageDestinationRequest) SetForcePathStyle(v bool)`

SetForcePathStyle sets ForcePathStyle field to given value.

### HasForcePathStyle

`func (o *SetPartnerStorageDestinationRequest) HasForcePathStyle() bool`

HasForcePathStyle returns a boolean if a field has been set.

### GetAccessKeyId

`func (o *SetPartnerStorageDestinationRequest) GetAccessKeyId() string`

GetAccessKeyId returns the AccessKeyId field if non-nil, zero value otherwise.

### GetAccessKeyIdOk

`func (o *SetPartnerStorageDestinationRequest) GetAccessKeyIdOk() (*string, bool)`

GetAccessKeyIdOk returns a tuple with the AccessKeyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessKeyId

`func (o *SetPartnerStorageDestinationRequest) SetAccessKeyId(v string)`

SetAccessKeyId sets AccessKeyId field to given value.


### GetSecretAccessKey

`func (o *SetPartnerStorageDestinationRequest) GetSecretAccessKey() string`

GetSecretAccessKey returns the SecretAccessKey field if non-nil, zero value otherwise.

### GetSecretAccessKeyOk

`func (o *SetPartnerStorageDestinationRequest) GetSecretAccessKeyOk() (*string, bool)`

GetSecretAccessKeyOk returns a tuple with the SecretAccessKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecretAccessKey

`func (o *SetPartnerStorageDestinationRequest) SetSecretAccessKey(v string)`

SetSecretAccessKey sets SecretAccessKey field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


