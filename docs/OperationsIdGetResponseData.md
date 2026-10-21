# OperationsIdGetResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The operation&#39;s identifier, the &#x60;operationId&#x60; the call that started it returned | [optional] 
**Type** | Pointer to **string** | What the operation does | [optional] 
**Status** | Pointer to **string** | Where the operation stands. &#x60;completed&#x60;, &#x60;failed&#x60; and &#x60;cancelled&#x60; are final | [optional] 
**Progress** | Pointer to **int32** | How far the operation has got, in percent | [optional] 
**Metadata** | Pointer to **map[string]interface{}** | What the operation tells about its work. A finished composition duplication names the new composition in &#x60;newCompositionId&#x60;, and lists any problem with its database in &#x60;warnings&#x60; (absent when there is none).  | [optional] 
**Error** | Pointer to **string** | Why a &#x60;failed&#x60; operation failed (absent otherwise) | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewOperationsIdGetResponseData

`func NewOperationsIdGetResponseData() *OperationsIdGetResponseData`

NewOperationsIdGetResponseData instantiates a new OperationsIdGetResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOperationsIdGetResponseDataWithDefaults

`func NewOperationsIdGetResponseDataWithDefaults() *OperationsIdGetResponseData`

NewOperationsIdGetResponseDataWithDefaults instantiates a new OperationsIdGetResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *OperationsIdGetResponseData) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *OperationsIdGetResponseData) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *OperationsIdGetResponseData) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *OperationsIdGetResponseData) HasId() bool`

HasId returns a boolean if a field has been set.

### GetType

`func (o *OperationsIdGetResponseData) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *OperationsIdGetResponseData) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *OperationsIdGetResponseData) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *OperationsIdGetResponseData) HasType() bool`

HasType returns a boolean if a field has been set.

### GetStatus

`func (o *OperationsIdGetResponseData) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *OperationsIdGetResponseData) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *OperationsIdGetResponseData) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *OperationsIdGetResponseData) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetProgress

`func (o *OperationsIdGetResponseData) GetProgress() int32`

GetProgress returns the Progress field if non-nil, zero value otherwise.

### GetProgressOk

`func (o *OperationsIdGetResponseData) GetProgressOk() (*int32, bool)`

GetProgressOk returns a tuple with the Progress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgress

`func (o *OperationsIdGetResponseData) SetProgress(v int32)`

SetProgress sets Progress field to given value.

### HasProgress

`func (o *OperationsIdGetResponseData) HasProgress() bool`

HasProgress returns a boolean if a field has been set.

### GetMetadata

`func (o *OperationsIdGetResponseData) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *OperationsIdGetResponseData) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *OperationsIdGetResponseData) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *OperationsIdGetResponseData) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetError

`func (o *OperationsIdGetResponseData) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *OperationsIdGetResponseData) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *OperationsIdGetResponseData) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *OperationsIdGetResponseData) HasError() bool`

HasError returns a boolean if a field has been set.

### GetCreatedAt

`func (o *OperationsIdGetResponseData) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *OperationsIdGetResponseData) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *OperationsIdGetResponseData) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *OperationsIdGetResponseData) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *OperationsIdGetResponseData) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *OperationsIdGetResponseData) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *OperationsIdGetResponseData) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *OperationsIdGetResponseData) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


