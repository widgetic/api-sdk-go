# PostPublicCompositionEmbedStatus200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**PostPublicCompositionEmbedStatus200ResponseData**](PostPublicCompositionEmbedStatus200ResponseData.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewPostPublicCompositionEmbedStatus200Response

`func NewPostPublicCompositionEmbedStatus200Response(success bool, data PostPublicCompositionEmbedStatus200ResponseData, ) *PostPublicCompositionEmbedStatus200Response`

NewPostPublicCompositionEmbedStatus200Response instantiates a new PostPublicCompositionEmbedStatus200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPostPublicCompositionEmbedStatus200ResponseWithDefaults

`func NewPostPublicCompositionEmbedStatus200ResponseWithDefaults() *PostPublicCompositionEmbedStatus200Response`

NewPostPublicCompositionEmbedStatus200ResponseWithDefaults instantiates a new PostPublicCompositionEmbedStatus200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *PostPublicCompositionEmbedStatus200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *PostPublicCompositionEmbedStatus200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *PostPublicCompositionEmbedStatus200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *PostPublicCompositionEmbedStatus200Response) GetData() PostPublicCompositionEmbedStatus200ResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *PostPublicCompositionEmbedStatus200Response) GetDataOk() (*PostPublicCompositionEmbedStatus200ResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *PostPublicCompositionEmbedStatus200Response) SetData(v PostPublicCompositionEmbedStatus200ResponseData)`

SetData sets Data field to given value.


### GetMeta

`func (o *PostPublicCompositionEmbedStatus200Response) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *PostPublicCompositionEmbedStatus200Response) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *PostPublicCompositionEmbedStatus200Response) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *PostPublicCompositionEmbedStatus200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


