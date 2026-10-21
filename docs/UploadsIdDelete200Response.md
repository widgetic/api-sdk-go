# UploadsIdDelete200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**UploadsIdDelete200ResponseData**](UploadsIdDelete200ResponseData.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewUploadsIdDelete200Response

`func NewUploadsIdDelete200Response(success bool, data UploadsIdDelete200ResponseData, ) *UploadsIdDelete200Response`

NewUploadsIdDelete200Response instantiates a new UploadsIdDelete200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUploadsIdDelete200ResponseWithDefaults

`func NewUploadsIdDelete200ResponseWithDefaults() *UploadsIdDelete200Response`

NewUploadsIdDelete200ResponseWithDefaults instantiates a new UploadsIdDelete200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *UploadsIdDelete200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *UploadsIdDelete200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *UploadsIdDelete200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *UploadsIdDelete200Response) GetData() UploadsIdDelete200ResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *UploadsIdDelete200Response) GetDataOk() (*UploadsIdDelete200ResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *UploadsIdDelete200Response) SetData(v UploadsIdDelete200ResponseData)`

SetData sets Data field to given value.


### GetMeta

`func (o *UploadsIdDelete200Response) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *UploadsIdDelete200Response) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *UploadsIdDelete200Response) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *UploadsIdDelete200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


