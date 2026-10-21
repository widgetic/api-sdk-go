# RemoveUserAdapterConnection200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**AdapterConnectionRemoval**](AdapterConnectionRemoval.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewRemoveUserAdapterConnection200Response

`func NewRemoveUserAdapterConnection200Response(success bool, data AdapterConnectionRemoval, ) *RemoveUserAdapterConnection200Response`

NewRemoveUserAdapterConnection200Response instantiates a new RemoveUserAdapterConnection200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRemoveUserAdapterConnection200ResponseWithDefaults

`func NewRemoveUserAdapterConnection200ResponseWithDefaults() *RemoveUserAdapterConnection200Response`

NewRemoveUserAdapterConnection200ResponseWithDefaults instantiates a new RemoveUserAdapterConnection200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *RemoveUserAdapterConnection200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *RemoveUserAdapterConnection200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *RemoveUserAdapterConnection200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *RemoveUserAdapterConnection200Response) GetData() AdapterConnectionRemoval`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *RemoveUserAdapterConnection200Response) GetDataOk() (*AdapterConnectionRemoval, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *RemoveUserAdapterConnection200Response) SetData(v AdapterConnectionRemoval)`

SetData sets Data field to given value.


### GetMeta

`func (o *RemoveUserAdapterConnection200Response) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *RemoveUserAdapterConnection200Response) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *RemoveUserAdapterConnection200Response) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *RemoveUserAdapterConnection200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


