# GetPartnerCreditTransactions200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**[]AccountCreditTransaction**](AccountCreditTransaction.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewGetPartnerCreditTransactions200Response

`func NewGetPartnerCreditTransactions200Response(success bool, data []AccountCreditTransaction, ) *GetPartnerCreditTransactions200Response`

NewGetPartnerCreditTransactions200Response instantiates a new GetPartnerCreditTransactions200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetPartnerCreditTransactions200ResponseWithDefaults

`func NewGetPartnerCreditTransactions200ResponseWithDefaults() *GetPartnerCreditTransactions200Response`

NewGetPartnerCreditTransactions200ResponseWithDefaults instantiates a new GetPartnerCreditTransactions200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *GetPartnerCreditTransactions200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetPartnerCreditTransactions200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetPartnerCreditTransactions200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *GetPartnerCreditTransactions200Response) GetData() []AccountCreditTransaction`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetPartnerCreditTransactions200Response) GetDataOk() (*[]AccountCreditTransaction, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetPartnerCreditTransactions200Response) SetData(v []AccountCreditTransaction)`

SetData sets Data field to given value.


### GetMeta

`func (o *GetPartnerCreditTransactions200Response) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetPartnerCreditTransactions200Response) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetPartnerCreditTransactions200Response) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetPartnerCreditTransactions200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


