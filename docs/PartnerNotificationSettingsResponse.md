# PartnerNotificationSettingsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Always &#x60;true&#x60; on a success. | 
**Data** | [**PartnerNotificationSettings**](PartnerNotificationSettings.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewPartnerNotificationSettingsResponse

`func NewPartnerNotificationSettingsResponse(success bool, data PartnerNotificationSettings, ) *PartnerNotificationSettingsResponse`

NewPartnerNotificationSettingsResponse instantiates a new PartnerNotificationSettingsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerNotificationSettingsResponseWithDefaults

`func NewPartnerNotificationSettingsResponseWithDefaults() *PartnerNotificationSettingsResponse`

NewPartnerNotificationSettingsResponseWithDefaults instantiates a new PartnerNotificationSettingsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *PartnerNotificationSettingsResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *PartnerNotificationSettingsResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *PartnerNotificationSettingsResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *PartnerNotificationSettingsResponse) GetData() PartnerNotificationSettings`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *PartnerNotificationSettingsResponse) GetDataOk() (*PartnerNotificationSettings, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *PartnerNotificationSettingsResponse) SetData(v PartnerNotificationSettings)`

SetData sets Data field to given value.


### GetMeta

`func (o *PartnerNotificationSettingsResponse) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *PartnerNotificationSettingsResponse) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *PartnerNotificationSettingsResponse) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *PartnerNotificationSettingsResponse) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


