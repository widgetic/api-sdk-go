# PartnerDataDatabaseResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Always &#x60;true&#x60; on a success. | 
**Data** | [**PartnerDataDatabase**](PartnerDataDatabase.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewPartnerDataDatabaseResponse

`func NewPartnerDataDatabaseResponse(success bool, data PartnerDataDatabase, ) *PartnerDataDatabaseResponse`

NewPartnerDataDatabaseResponse instantiates a new PartnerDataDatabaseResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerDataDatabaseResponseWithDefaults

`func NewPartnerDataDatabaseResponseWithDefaults() *PartnerDataDatabaseResponse`

NewPartnerDataDatabaseResponseWithDefaults instantiates a new PartnerDataDatabaseResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *PartnerDataDatabaseResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *PartnerDataDatabaseResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *PartnerDataDatabaseResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *PartnerDataDatabaseResponse) GetData() PartnerDataDatabase`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *PartnerDataDatabaseResponse) GetDataOk() (*PartnerDataDatabase, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *PartnerDataDatabaseResponse) SetData(v PartnerDataDatabase)`

SetData sets Data field to given value.


### GetMeta

`func (o *PartnerDataDatabaseResponse) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *PartnerDataDatabaseResponse) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *PartnerDataDatabaseResponse) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *PartnerDataDatabaseResponse) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


