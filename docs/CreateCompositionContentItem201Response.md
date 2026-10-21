# CreateCompositionContentItem201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**ContentItemWriteResult**](ContentItemWriteResult.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewCreateCompositionContentItem201Response

`func NewCreateCompositionContentItem201Response(success bool, data ContentItemWriteResult, ) *CreateCompositionContentItem201Response`

NewCreateCompositionContentItem201Response instantiates a new CreateCompositionContentItem201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateCompositionContentItem201ResponseWithDefaults

`func NewCreateCompositionContentItem201ResponseWithDefaults() *CreateCompositionContentItem201Response`

NewCreateCompositionContentItem201ResponseWithDefaults instantiates a new CreateCompositionContentItem201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *CreateCompositionContentItem201Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *CreateCompositionContentItem201Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *CreateCompositionContentItem201Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *CreateCompositionContentItem201Response) GetData() ContentItemWriteResult`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *CreateCompositionContentItem201Response) GetDataOk() (*ContentItemWriteResult, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *CreateCompositionContentItem201Response) SetData(v ContentItemWriteResult)`

SetData sets Data field to given value.


### GetMeta

`func (o *CreateCompositionContentItem201Response) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *CreateCompositionContentItem201Response) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *CreateCompositionContentItem201Response) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *CreateCompositionContentItem201Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


