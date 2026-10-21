# RemoveAiAnswersKnowledgeDocument200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**AiAnswersKnowledgeRemoval**](AiAnswersKnowledgeRemoval.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewRemoveAiAnswersKnowledgeDocument200Response

`func NewRemoveAiAnswersKnowledgeDocument200Response(success bool, data AiAnswersKnowledgeRemoval, ) *RemoveAiAnswersKnowledgeDocument200Response`

NewRemoveAiAnswersKnowledgeDocument200Response instantiates a new RemoveAiAnswersKnowledgeDocument200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRemoveAiAnswersKnowledgeDocument200ResponseWithDefaults

`func NewRemoveAiAnswersKnowledgeDocument200ResponseWithDefaults() *RemoveAiAnswersKnowledgeDocument200Response`

NewRemoveAiAnswersKnowledgeDocument200ResponseWithDefaults instantiates a new RemoveAiAnswersKnowledgeDocument200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *RemoveAiAnswersKnowledgeDocument200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *RemoveAiAnswersKnowledgeDocument200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *RemoveAiAnswersKnowledgeDocument200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *RemoveAiAnswersKnowledgeDocument200Response) GetData() AiAnswersKnowledgeRemoval`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *RemoveAiAnswersKnowledgeDocument200Response) GetDataOk() (*AiAnswersKnowledgeRemoval, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *RemoveAiAnswersKnowledgeDocument200Response) SetData(v AiAnswersKnowledgeRemoval)`

SetData sets Data field to given value.


### GetMeta

`func (o *RemoveAiAnswersKnowledgeDocument200Response) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *RemoveAiAnswersKnowledgeDocument200Response) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *RemoveAiAnswersKnowledgeDocument200Response) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *RemoveAiAnswersKnowledgeDocument200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


