# PartnerNotificationDeliveryLogResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Always &#x60;true&#x60; on a success. | 
**Data** | [**PartnerNotificationDeliveryLog**](PartnerNotificationDeliveryLog.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewPartnerNotificationDeliveryLogResponse

`func NewPartnerNotificationDeliveryLogResponse(success bool, data PartnerNotificationDeliveryLog, ) *PartnerNotificationDeliveryLogResponse`

NewPartnerNotificationDeliveryLogResponse instantiates a new PartnerNotificationDeliveryLogResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerNotificationDeliveryLogResponseWithDefaults

`func NewPartnerNotificationDeliveryLogResponseWithDefaults() *PartnerNotificationDeliveryLogResponse`

NewPartnerNotificationDeliveryLogResponseWithDefaults instantiates a new PartnerNotificationDeliveryLogResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *PartnerNotificationDeliveryLogResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *PartnerNotificationDeliveryLogResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *PartnerNotificationDeliveryLogResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *PartnerNotificationDeliveryLogResponse) GetData() PartnerNotificationDeliveryLog`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *PartnerNotificationDeliveryLogResponse) GetDataOk() (*PartnerNotificationDeliveryLog, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *PartnerNotificationDeliveryLogResponse) SetData(v PartnerNotificationDeliveryLog)`

SetData sets Data field to given value.


### GetMeta

`func (o *PartnerNotificationDeliveryLogResponse) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *PartnerNotificationDeliveryLogResponse) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *PartnerNotificationDeliveryLogResponse) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *PartnerNotificationDeliveryLogResponse) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


