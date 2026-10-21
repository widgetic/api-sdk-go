# GetManagedUserEntitlementsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Always &#x60;true&#x60; on a success. | 
**Data** | [**GetManagedUserEntitlementsResponseData**](GetManagedUserEntitlementsResponseData.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewGetManagedUserEntitlementsResponse

`func NewGetManagedUserEntitlementsResponse(success bool, data GetManagedUserEntitlementsResponseData, ) *GetManagedUserEntitlementsResponse`

NewGetManagedUserEntitlementsResponse instantiates a new GetManagedUserEntitlementsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetManagedUserEntitlementsResponseWithDefaults

`func NewGetManagedUserEntitlementsResponseWithDefaults() *GetManagedUserEntitlementsResponse`

NewGetManagedUserEntitlementsResponseWithDefaults instantiates a new GetManagedUserEntitlementsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *GetManagedUserEntitlementsResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetManagedUserEntitlementsResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetManagedUserEntitlementsResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *GetManagedUserEntitlementsResponse) GetData() GetManagedUserEntitlementsResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetManagedUserEntitlementsResponse) GetDataOk() (*GetManagedUserEntitlementsResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetManagedUserEntitlementsResponse) SetData(v GetManagedUserEntitlementsResponseData)`

SetData sets Data field to given value.


### GetMeta

`func (o *GetManagedUserEntitlementsResponse) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetManagedUserEntitlementsResponse) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetManagedUserEntitlementsResponse) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetManagedUserEntitlementsResponse) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


