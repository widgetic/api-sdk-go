# GetPartnerEntitlementsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Always &#x60;true&#x60; on a success. | 
**Data** | [**GetPartnerEntitlementsResponseData**](GetPartnerEntitlementsResponseData.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewGetPartnerEntitlementsResponse

`func NewGetPartnerEntitlementsResponse(success bool, data GetPartnerEntitlementsResponseData, ) *GetPartnerEntitlementsResponse`

NewGetPartnerEntitlementsResponse instantiates a new GetPartnerEntitlementsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetPartnerEntitlementsResponseWithDefaults

`func NewGetPartnerEntitlementsResponseWithDefaults() *GetPartnerEntitlementsResponse`

NewGetPartnerEntitlementsResponseWithDefaults instantiates a new GetPartnerEntitlementsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *GetPartnerEntitlementsResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetPartnerEntitlementsResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetPartnerEntitlementsResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *GetPartnerEntitlementsResponse) GetData() GetPartnerEntitlementsResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetPartnerEntitlementsResponse) GetDataOk() (*GetPartnerEntitlementsResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetPartnerEntitlementsResponse) SetData(v GetPartnerEntitlementsResponseData)`

SetData sets Data field to given value.


### GetMeta

`func (o *GetPartnerEntitlementsResponse) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetPartnerEntitlementsResponse) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetPartnerEntitlementsResponse) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetPartnerEntitlementsResponse) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


