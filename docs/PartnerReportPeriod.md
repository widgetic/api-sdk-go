# PartnerReportPeriod

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**From** | **time.Time** | Start of the period, included | 
**To** | **time.Time** | End of the period, not included | 

## Methods

### NewPartnerReportPeriod

`func NewPartnerReportPeriod(from time.Time, to time.Time, ) *PartnerReportPeriod`

NewPartnerReportPeriod instantiates a new PartnerReportPeriod object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerReportPeriodWithDefaults

`func NewPartnerReportPeriodWithDefaults() *PartnerReportPeriod`

NewPartnerReportPeriodWithDefaults instantiates a new PartnerReportPeriod object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFrom

`func (o *PartnerReportPeriod) GetFrom() time.Time`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *PartnerReportPeriod) GetFromOk() (*time.Time, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *PartnerReportPeriod) SetFrom(v time.Time)`

SetFrom sets From field to given value.


### GetTo

`func (o *PartnerReportPeriod) GetTo() time.Time`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *PartnerReportPeriod) GetToOk() (*time.Time, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *PartnerReportPeriod) SetTo(v time.Time)`

SetTo sets To field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


