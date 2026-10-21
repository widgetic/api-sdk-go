# PartnerEntryContextSigningResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Always &#x60;true&#x60; on a success. | 
**Data** | [**PartnerEntryContextSigning**](PartnerEntryContextSigning.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewPartnerEntryContextSigningResponse

`func NewPartnerEntryContextSigningResponse(success bool, data PartnerEntryContextSigning, ) *PartnerEntryContextSigningResponse`

NewPartnerEntryContextSigningResponse instantiates a new PartnerEntryContextSigningResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerEntryContextSigningResponseWithDefaults

`func NewPartnerEntryContextSigningResponseWithDefaults() *PartnerEntryContextSigningResponse`

NewPartnerEntryContextSigningResponseWithDefaults instantiates a new PartnerEntryContextSigningResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *PartnerEntryContextSigningResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *PartnerEntryContextSigningResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *PartnerEntryContextSigningResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *PartnerEntryContextSigningResponse) GetData() PartnerEntryContextSigning`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *PartnerEntryContextSigningResponse) GetDataOk() (*PartnerEntryContextSigning, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *PartnerEntryContextSigningResponse) SetData(v PartnerEntryContextSigning)`

SetData sets Data field to given value.


### GetMeta

`func (o *PartnerEntryContextSigningResponse) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *PartnerEntryContextSigningResponse) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *PartnerEntryContextSigningResponse) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *PartnerEntryContextSigningResponse) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


