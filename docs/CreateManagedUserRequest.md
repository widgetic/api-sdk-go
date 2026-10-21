# CreateManagedUserRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExternalId** | **string** | Your own identifier for the managed user. Must be unique among the managed users you manage (409 otherwise); another partner using the same value does not matter. | 
**ManagerId** | Pointer to **string** | ID of the user who will manage this managed user. Defaults to your own user ID; a partner can only use their own ID (403 otherwise), only an admin can name another manager. | [optional] 
**Metadata** | Pointer to **map[string]interface{}** | Additional metadata for the managed user | [optional] 

## Methods

### NewCreateManagedUserRequest

`func NewCreateManagedUserRequest(externalId string, ) *CreateManagedUserRequest`

NewCreateManagedUserRequest instantiates a new CreateManagedUserRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateManagedUserRequestWithDefaults

`func NewCreateManagedUserRequestWithDefaults() *CreateManagedUserRequest`

NewCreateManagedUserRequestWithDefaults instantiates a new CreateManagedUserRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExternalId

`func (o *CreateManagedUserRequest) GetExternalId() string`

GetExternalId returns the ExternalId field if non-nil, zero value otherwise.

### GetExternalIdOk

`func (o *CreateManagedUserRequest) GetExternalIdOk() (*string, bool)`

GetExternalIdOk returns a tuple with the ExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalId

`func (o *CreateManagedUserRequest) SetExternalId(v string)`

SetExternalId sets ExternalId field to given value.


### GetManagerId

`func (o *CreateManagedUserRequest) GetManagerId() string`

GetManagerId returns the ManagerId field if non-nil, zero value otherwise.

### GetManagerIdOk

`func (o *CreateManagedUserRequest) GetManagerIdOk() (*string, bool)`

GetManagerIdOk returns a tuple with the ManagerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagerId

`func (o *CreateManagedUserRequest) SetManagerId(v string)`

SetManagerId sets ManagerId field to given value.

### HasManagerId

`func (o *CreateManagedUserRequest) HasManagerId() bool`

HasManagerId returns a boolean if a field has been set.

### GetMetadata

`func (o *CreateManagedUserRequest) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *CreateManagedUserRequest) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *CreateManagedUserRequest) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *CreateManagedUserRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


