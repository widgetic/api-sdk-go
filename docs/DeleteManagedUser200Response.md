# DeleteManagedUser200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**ManagedUserRemoval**](ManagedUserRemoval.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewDeleteManagedUser200Response

`func NewDeleteManagedUser200Response(success bool, data ManagedUserRemoval, ) *DeleteManagedUser200Response`

NewDeleteManagedUser200Response instantiates a new DeleteManagedUser200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeleteManagedUser200ResponseWithDefaults

`func NewDeleteManagedUser200ResponseWithDefaults() *DeleteManagedUser200Response`

NewDeleteManagedUser200ResponseWithDefaults instantiates a new DeleteManagedUser200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *DeleteManagedUser200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *DeleteManagedUser200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *DeleteManagedUser200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *DeleteManagedUser200Response) GetData() ManagedUserRemoval`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *DeleteManagedUser200Response) GetDataOk() (*ManagedUserRemoval, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *DeleteManagedUser200Response) SetData(v ManagedUserRemoval)`

SetData sets Data field to given value.


### GetMeta

`func (o *DeleteManagedUser200Response) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *DeleteManagedUser200Response) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *DeleteManagedUser200Response) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *DeleteManagedUser200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


