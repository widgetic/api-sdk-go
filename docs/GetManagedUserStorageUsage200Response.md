# GetManagedUserStorageUsage200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**GetManagedUserStorageUsage200ResponseData**](GetManagedUserStorageUsage200ResponseData.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewGetManagedUserStorageUsage200Response

`func NewGetManagedUserStorageUsage200Response(success bool, data GetManagedUserStorageUsage200ResponseData, ) *GetManagedUserStorageUsage200Response`

NewGetManagedUserStorageUsage200Response instantiates a new GetManagedUserStorageUsage200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetManagedUserStorageUsage200ResponseWithDefaults

`func NewGetManagedUserStorageUsage200ResponseWithDefaults() *GetManagedUserStorageUsage200Response`

NewGetManagedUserStorageUsage200ResponseWithDefaults instantiates a new GetManagedUserStorageUsage200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *GetManagedUserStorageUsage200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetManagedUserStorageUsage200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetManagedUserStorageUsage200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *GetManagedUserStorageUsage200Response) GetData() GetManagedUserStorageUsage200ResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetManagedUserStorageUsage200Response) GetDataOk() (*GetManagedUserStorageUsage200ResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetManagedUserStorageUsage200Response) SetData(v GetManagedUserStorageUsage200ResponseData)`

SetData sets Data field to given value.


### GetMeta

`func (o *GetManagedUserStorageUsage200Response) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetManagedUserStorageUsage200Response) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetManagedUserStorageUsage200Response) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetManagedUserStorageUsage200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


