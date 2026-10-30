# ReportPublicWorkflowEvents200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**PublicWorkflowEventsAccepted**](PublicWorkflowEventsAccepted.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewReportPublicWorkflowEvents200Response

`func NewReportPublicWorkflowEvents200Response(success bool, data PublicWorkflowEventsAccepted, ) *ReportPublicWorkflowEvents200Response`

NewReportPublicWorkflowEvents200Response instantiates a new ReportPublicWorkflowEvents200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReportPublicWorkflowEvents200ResponseWithDefaults

`func NewReportPublicWorkflowEvents200ResponseWithDefaults() *ReportPublicWorkflowEvents200Response`

NewReportPublicWorkflowEvents200ResponseWithDefaults instantiates a new ReportPublicWorkflowEvents200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *ReportPublicWorkflowEvents200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ReportPublicWorkflowEvents200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ReportPublicWorkflowEvents200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *ReportPublicWorkflowEvents200Response) GetData() PublicWorkflowEventsAccepted`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ReportPublicWorkflowEvents200Response) GetDataOk() (*PublicWorkflowEventsAccepted, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ReportPublicWorkflowEvents200Response) SetData(v PublicWorkflowEventsAccepted)`

SetData sets Data field to given value.


### GetMeta

`func (o *ReportPublicWorkflowEvents200Response) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ReportPublicWorkflowEvents200Response) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ReportPublicWorkflowEvents200Response) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *ReportPublicWorkflowEvents200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


