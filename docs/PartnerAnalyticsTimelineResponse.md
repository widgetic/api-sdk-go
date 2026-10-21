# PartnerAnalyticsTimelineResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Always &#x60;true&#x60; on a success. | 
**Data** | [**PartnerAnalyticsTimeline**](PartnerAnalyticsTimeline.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewPartnerAnalyticsTimelineResponse

`func NewPartnerAnalyticsTimelineResponse(success bool, data PartnerAnalyticsTimeline, ) *PartnerAnalyticsTimelineResponse`

NewPartnerAnalyticsTimelineResponse instantiates a new PartnerAnalyticsTimelineResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerAnalyticsTimelineResponseWithDefaults

`func NewPartnerAnalyticsTimelineResponseWithDefaults() *PartnerAnalyticsTimelineResponse`

NewPartnerAnalyticsTimelineResponseWithDefaults instantiates a new PartnerAnalyticsTimelineResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *PartnerAnalyticsTimelineResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *PartnerAnalyticsTimelineResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *PartnerAnalyticsTimelineResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *PartnerAnalyticsTimelineResponse) GetData() PartnerAnalyticsTimeline`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *PartnerAnalyticsTimelineResponse) GetDataOk() (*PartnerAnalyticsTimeline, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *PartnerAnalyticsTimelineResponse) SetData(v PartnerAnalyticsTimeline)`

SetData sets Data field to given value.


### GetMeta

`func (o *PartnerAnalyticsTimelineResponse) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *PartnerAnalyticsTimelineResponse) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *PartnerAnalyticsTimelineResponse) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *PartnerAnalyticsTimelineResponse) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


