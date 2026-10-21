# PartnerNotificationTestEventResultResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Always &#x60;true&#x60; on a success. | 
**Data** | [**PartnerNotificationTestEventResult**](PartnerNotificationTestEventResult.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewPartnerNotificationTestEventResultResponse

`func NewPartnerNotificationTestEventResultResponse(success bool, data PartnerNotificationTestEventResult, ) *PartnerNotificationTestEventResultResponse`

NewPartnerNotificationTestEventResultResponse instantiates a new PartnerNotificationTestEventResultResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerNotificationTestEventResultResponseWithDefaults

`func NewPartnerNotificationTestEventResultResponseWithDefaults() *PartnerNotificationTestEventResultResponse`

NewPartnerNotificationTestEventResultResponseWithDefaults instantiates a new PartnerNotificationTestEventResultResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *PartnerNotificationTestEventResultResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *PartnerNotificationTestEventResultResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *PartnerNotificationTestEventResultResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *PartnerNotificationTestEventResultResponse) GetData() PartnerNotificationTestEventResult`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *PartnerNotificationTestEventResultResponse) GetDataOk() (*PartnerNotificationTestEventResult, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *PartnerNotificationTestEventResultResponse) SetData(v PartnerNotificationTestEventResult)`

SetData sets Data field to given value.


### GetMeta

`func (o *PartnerNotificationTestEventResultResponse) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *PartnerNotificationTestEventResultResponse) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *PartnerNotificationTestEventResultResponse) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *PartnerNotificationTestEventResultResponse) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


