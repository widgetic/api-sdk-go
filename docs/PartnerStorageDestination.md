# PartnerStorageDestination

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PartnerId** | **string** |  | 
**Endpoint** | **string** | The HTTPS address of the S3-compatible service, scheme and host only | 
**Region** | **string** |  | 
**Bucket** | **string** |  | 
**KeyPrefix** | **string** | The folder inside the bucket every file is written under. Empty, or folders each followed by a slash. | 
**PublicBaseUrl** | **string** | Where the stored files are served from. A file&#39;s url is this address, a slash and the file&#39;s key. | 
**ForcePathStyle** | **bool** | Whether the bucket name goes in the path of a request (true) or in the host name (false) | 
**AccessKeyHint** | **string** | The last four characters of the access key id, to tell which key is set. Not enough to use it. | 
**VerifiedAt** | **time.Time** | When the destination last passed the check | 
**LastVerificationError** | Pointer to **NullableString** | Why the most recent re-check failed. Null while the last check passed. | [optional] 
**LastVerificationFailedAt** | Pointer to **NullableTime** |  | [optional] 
**UpdatedAt** | **time.Time** |  | 

## Methods

### NewPartnerStorageDestination

`func NewPartnerStorageDestination(partnerId string, endpoint string, region string, bucket string, keyPrefix string, publicBaseUrl string, forcePathStyle bool, accessKeyHint string, verifiedAt time.Time, updatedAt time.Time, ) *PartnerStorageDestination`

NewPartnerStorageDestination instantiates a new PartnerStorageDestination object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerStorageDestinationWithDefaults

`func NewPartnerStorageDestinationWithDefaults() *PartnerStorageDestination`

NewPartnerStorageDestinationWithDefaults instantiates a new PartnerStorageDestination object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPartnerId

`func (o *PartnerStorageDestination) GetPartnerId() string`

GetPartnerId returns the PartnerId field if non-nil, zero value otherwise.

### GetPartnerIdOk

`func (o *PartnerStorageDestination) GetPartnerIdOk() (*string, bool)`

GetPartnerIdOk returns a tuple with the PartnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartnerId

`func (o *PartnerStorageDestination) SetPartnerId(v string)`

SetPartnerId sets PartnerId field to given value.


### GetEndpoint

`func (o *PartnerStorageDestination) GetEndpoint() string`

GetEndpoint returns the Endpoint field if non-nil, zero value otherwise.

### GetEndpointOk

`func (o *PartnerStorageDestination) GetEndpointOk() (*string, bool)`

GetEndpointOk returns a tuple with the Endpoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndpoint

`func (o *PartnerStorageDestination) SetEndpoint(v string)`

SetEndpoint sets Endpoint field to given value.


### GetRegion

`func (o *PartnerStorageDestination) GetRegion() string`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *PartnerStorageDestination) GetRegionOk() (*string, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *PartnerStorageDestination) SetRegion(v string)`

SetRegion sets Region field to given value.


### GetBucket

`func (o *PartnerStorageDestination) GetBucket() string`

GetBucket returns the Bucket field if non-nil, zero value otherwise.

### GetBucketOk

`func (o *PartnerStorageDestination) GetBucketOk() (*string, bool)`

GetBucketOk returns a tuple with the Bucket field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBucket

`func (o *PartnerStorageDestination) SetBucket(v string)`

SetBucket sets Bucket field to given value.


### GetKeyPrefix

`func (o *PartnerStorageDestination) GetKeyPrefix() string`

GetKeyPrefix returns the KeyPrefix field if non-nil, zero value otherwise.

### GetKeyPrefixOk

`func (o *PartnerStorageDestination) GetKeyPrefixOk() (*string, bool)`

GetKeyPrefixOk returns a tuple with the KeyPrefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyPrefix

`func (o *PartnerStorageDestination) SetKeyPrefix(v string)`

SetKeyPrefix sets KeyPrefix field to given value.


### GetPublicBaseUrl

`func (o *PartnerStorageDestination) GetPublicBaseUrl() string`

GetPublicBaseUrl returns the PublicBaseUrl field if non-nil, zero value otherwise.

### GetPublicBaseUrlOk

`func (o *PartnerStorageDestination) GetPublicBaseUrlOk() (*string, bool)`

GetPublicBaseUrlOk returns a tuple with the PublicBaseUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicBaseUrl

`func (o *PartnerStorageDestination) SetPublicBaseUrl(v string)`

SetPublicBaseUrl sets PublicBaseUrl field to given value.


### GetForcePathStyle

`func (o *PartnerStorageDestination) GetForcePathStyle() bool`

GetForcePathStyle returns the ForcePathStyle field if non-nil, zero value otherwise.

### GetForcePathStyleOk

`func (o *PartnerStorageDestination) GetForcePathStyleOk() (*bool, bool)`

GetForcePathStyleOk returns a tuple with the ForcePathStyle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForcePathStyle

`func (o *PartnerStorageDestination) SetForcePathStyle(v bool)`

SetForcePathStyle sets ForcePathStyle field to given value.


### GetAccessKeyHint

`func (o *PartnerStorageDestination) GetAccessKeyHint() string`

GetAccessKeyHint returns the AccessKeyHint field if non-nil, zero value otherwise.

### GetAccessKeyHintOk

`func (o *PartnerStorageDestination) GetAccessKeyHintOk() (*string, bool)`

GetAccessKeyHintOk returns a tuple with the AccessKeyHint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessKeyHint

`func (o *PartnerStorageDestination) SetAccessKeyHint(v string)`

SetAccessKeyHint sets AccessKeyHint field to given value.


### GetVerifiedAt

`func (o *PartnerStorageDestination) GetVerifiedAt() time.Time`

GetVerifiedAt returns the VerifiedAt field if non-nil, zero value otherwise.

### GetVerifiedAtOk

`func (o *PartnerStorageDestination) GetVerifiedAtOk() (*time.Time, bool)`

GetVerifiedAtOk returns a tuple with the VerifiedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerifiedAt

`func (o *PartnerStorageDestination) SetVerifiedAt(v time.Time)`

SetVerifiedAt sets VerifiedAt field to given value.


### GetLastVerificationError

`func (o *PartnerStorageDestination) GetLastVerificationError() string`

GetLastVerificationError returns the LastVerificationError field if non-nil, zero value otherwise.

### GetLastVerificationErrorOk

`func (o *PartnerStorageDestination) GetLastVerificationErrorOk() (*string, bool)`

GetLastVerificationErrorOk returns a tuple with the LastVerificationError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastVerificationError

`func (o *PartnerStorageDestination) SetLastVerificationError(v string)`

SetLastVerificationError sets LastVerificationError field to given value.

### HasLastVerificationError

`func (o *PartnerStorageDestination) HasLastVerificationError() bool`

HasLastVerificationError returns a boolean if a field has been set.

### SetLastVerificationErrorNil

`func (o *PartnerStorageDestination) SetLastVerificationErrorNil(b bool)`

 SetLastVerificationErrorNil sets the value for LastVerificationError to be an explicit nil

### UnsetLastVerificationError
`func (o *PartnerStorageDestination) UnsetLastVerificationError()`

UnsetLastVerificationError ensures that no value is present for LastVerificationError, not even an explicit nil
### GetLastVerificationFailedAt

`func (o *PartnerStorageDestination) GetLastVerificationFailedAt() time.Time`

GetLastVerificationFailedAt returns the LastVerificationFailedAt field if non-nil, zero value otherwise.

### GetLastVerificationFailedAtOk

`func (o *PartnerStorageDestination) GetLastVerificationFailedAtOk() (*time.Time, bool)`

GetLastVerificationFailedAtOk returns a tuple with the LastVerificationFailedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastVerificationFailedAt

`func (o *PartnerStorageDestination) SetLastVerificationFailedAt(v time.Time)`

SetLastVerificationFailedAt sets LastVerificationFailedAt field to given value.

### HasLastVerificationFailedAt

`func (o *PartnerStorageDestination) HasLastVerificationFailedAt() bool`

HasLastVerificationFailedAt returns a boolean if a field has been set.

### SetLastVerificationFailedAtNil

`func (o *PartnerStorageDestination) SetLastVerificationFailedAtNil(b bool)`

 SetLastVerificationFailedAtNil sets the value for LastVerificationFailedAt to be an explicit nil

### UnsetLastVerificationFailedAt
`func (o *PartnerStorageDestination) UnsetLastVerificationFailedAt()`

UnsetLastVerificationFailedAt ensures that no value is present for LastVerificationFailedAt, not even an explicit nil
### GetUpdatedAt

`func (o *PartnerStorageDestination) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *PartnerStorageDestination) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *PartnerStorageDestination) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


