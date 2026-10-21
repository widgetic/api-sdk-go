# PartnerReportPage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Limit** | **int32** | How many rows the page can hold at most | 
**Offset** | **int32** | How many rows were skipped before this page | 
**HasMore** | **bool** | True when more rows follow this page. Ask again with &#x60;offset&#x60; raised by &#x60;limit&#x60;. | 

## Methods

### NewPartnerReportPage

`func NewPartnerReportPage(limit int32, offset int32, hasMore bool, ) *PartnerReportPage`

NewPartnerReportPage instantiates a new PartnerReportPage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerReportPageWithDefaults

`func NewPartnerReportPageWithDefaults() *PartnerReportPage`

NewPartnerReportPageWithDefaults instantiates a new PartnerReportPage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLimit

`func (o *PartnerReportPage) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *PartnerReportPage) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *PartnerReportPage) SetLimit(v int32)`

SetLimit sets Limit field to given value.


### GetOffset

`func (o *PartnerReportPage) GetOffset() int32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *PartnerReportPage) GetOffsetOk() (*int32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *PartnerReportPage) SetOffset(v int32)`

SetOffset sets Offset field to given value.


### GetHasMore

`func (o *PartnerReportPage) GetHasMore() bool`

GetHasMore returns the HasMore field if non-nil, zero value otherwise.

### GetHasMoreOk

`func (o *PartnerReportPage) GetHasMoreOk() (*bool, bool)`

GetHasMoreOk returns a tuple with the HasMore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasMore

`func (o *PartnerReportPage) SetHasMore(v bool)`

SetHasMore sets HasMore field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


