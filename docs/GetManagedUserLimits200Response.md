# GetManagedUserLimits200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**ManagedUserLimits**](ManagedUserLimits.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewGetManagedUserLimits200Response

`func NewGetManagedUserLimits200Response(success bool, data ManagedUserLimits, ) *GetManagedUserLimits200Response`

NewGetManagedUserLimits200Response instantiates a new GetManagedUserLimits200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetManagedUserLimits200ResponseWithDefaults

`func NewGetManagedUserLimits200ResponseWithDefaults() *GetManagedUserLimits200Response`

NewGetManagedUserLimits200ResponseWithDefaults instantiates a new GetManagedUserLimits200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *GetManagedUserLimits200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetManagedUserLimits200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetManagedUserLimits200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *GetManagedUserLimits200Response) GetData() ManagedUserLimits`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetManagedUserLimits200Response) GetDataOk() (*ManagedUserLimits, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetManagedUserLimits200Response) SetData(v ManagedUserLimits)`

SetData sets Data field to given value.


### GetMeta

`func (o *GetManagedUserLimits200Response) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetManagedUserLimits200Response) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetManagedUserLimits200Response) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetManagedUserLimits200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


