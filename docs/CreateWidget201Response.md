# CreateWidget201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**CreateWidget201ResponseData**](CreateWidget201ResponseData.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewCreateWidget201Response

`func NewCreateWidget201Response(success bool, data CreateWidget201ResponseData, ) *CreateWidget201Response`

NewCreateWidget201Response instantiates a new CreateWidget201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateWidget201ResponseWithDefaults

`func NewCreateWidget201ResponseWithDefaults() *CreateWidget201Response`

NewCreateWidget201ResponseWithDefaults instantiates a new CreateWidget201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *CreateWidget201Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *CreateWidget201Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *CreateWidget201Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *CreateWidget201Response) GetData() CreateWidget201ResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *CreateWidget201Response) GetDataOk() (*CreateWidget201ResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *CreateWidget201Response) SetData(v CreateWidget201ResponseData)`

SetData sets Data field to given value.


### GetMeta

`func (o *CreateWidget201Response) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *CreateWidget201Response) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *CreateWidget201Response) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *CreateWidget201Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


