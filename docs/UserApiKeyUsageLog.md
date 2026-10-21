# UserApiKeyUsageLog

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**KeyId** | **string** | The key the call was made with | 
**Timestamp** | **time.Time** |  | 
**Path** | **string** |  | 
**Method** | **string** |  | 
**Status** | **int32** | The HTTP status the call ended with | 
**Kind** | Pointer to **NullableString** |  | [optional] 
**Details** | Pointer to **map[string]interface{}** | What was recorded about the call | [optional] 

## Methods

### NewUserApiKeyUsageLog

`func NewUserApiKeyUsageLog(id string, keyId string, timestamp time.Time, path string, method string, status int32, ) *UserApiKeyUsageLog`

NewUserApiKeyUsageLog instantiates a new UserApiKeyUsageLog object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserApiKeyUsageLogWithDefaults

`func NewUserApiKeyUsageLogWithDefaults() *UserApiKeyUsageLog`

NewUserApiKeyUsageLogWithDefaults instantiates a new UserApiKeyUsageLog object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *UserApiKeyUsageLog) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *UserApiKeyUsageLog) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *UserApiKeyUsageLog) SetId(v string)`

SetId sets Id field to given value.


### GetKeyId

`func (o *UserApiKeyUsageLog) GetKeyId() string`

GetKeyId returns the KeyId field if non-nil, zero value otherwise.

### GetKeyIdOk

`func (o *UserApiKeyUsageLog) GetKeyIdOk() (*string, bool)`

GetKeyIdOk returns a tuple with the KeyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyId

`func (o *UserApiKeyUsageLog) SetKeyId(v string)`

SetKeyId sets KeyId field to given value.


### GetTimestamp

`func (o *UserApiKeyUsageLog) GetTimestamp() time.Time`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *UserApiKeyUsageLog) GetTimestampOk() (*time.Time, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *UserApiKeyUsageLog) SetTimestamp(v time.Time)`

SetTimestamp sets Timestamp field to given value.


### GetPath

`func (o *UserApiKeyUsageLog) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *UserApiKeyUsageLog) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *UserApiKeyUsageLog) SetPath(v string)`

SetPath sets Path field to given value.


### GetMethod

`func (o *UserApiKeyUsageLog) GetMethod() string`

GetMethod returns the Method field if non-nil, zero value otherwise.

### GetMethodOk

`func (o *UserApiKeyUsageLog) GetMethodOk() (*string, bool)`

GetMethodOk returns a tuple with the Method field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethod

`func (o *UserApiKeyUsageLog) SetMethod(v string)`

SetMethod sets Method field to given value.


### GetStatus

`func (o *UserApiKeyUsageLog) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *UserApiKeyUsageLog) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *UserApiKeyUsageLog) SetStatus(v int32)`

SetStatus sets Status field to given value.


### GetKind

`func (o *UserApiKeyUsageLog) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *UserApiKeyUsageLog) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *UserApiKeyUsageLog) SetKind(v string)`

SetKind sets Kind field to given value.

### HasKind

`func (o *UserApiKeyUsageLog) HasKind() bool`

HasKind returns a boolean if a field has been set.

### SetKindNil

`func (o *UserApiKeyUsageLog) SetKindNil(b bool)`

 SetKindNil sets the value for Kind to be an explicit nil

### UnsetKind
`func (o *UserApiKeyUsageLog) UnsetKind()`

UnsetKind ensures that no value is present for Kind, not even an explicit nil
### GetDetails

`func (o *UserApiKeyUsageLog) GetDetails() map[string]interface{}`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *UserApiKeyUsageLog) GetDetailsOk() (*map[string]interface{}, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *UserApiKeyUsageLog) SetDetails(v map[string]interface{})`

SetDetails sets Details field to given value.

### HasDetails

`func (o *UserApiKeyUsageLog) HasDetails() bool`

HasDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


