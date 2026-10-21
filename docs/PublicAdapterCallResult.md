# PublicAdapterCallResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**PublicAdapterCallResultData**](PublicAdapterCallResultData.md) |  | 

## Methods

### NewPublicAdapterCallResult

`func NewPublicAdapterCallResult(success bool, data PublicAdapterCallResultData, ) *PublicAdapterCallResult`

NewPublicAdapterCallResult instantiates a new PublicAdapterCallResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublicAdapterCallResultWithDefaults

`func NewPublicAdapterCallResultWithDefaults() *PublicAdapterCallResult`

NewPublicAdapterCallResultWithDefaults instantiates a new PublicAdapterCallResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *PublicAdapterCallResult) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *PublicAdapterCallResult) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *PublicAdapterCallResult) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *PublicAdapterCallResult) GetData() PublicAdapterCallResultData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *PublicAdapterCallResult) GetDataOk() (*PublicAdapterCallResultData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *PublicAdapterCallResult) SetData(v PublicAdapterCallResultData)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


