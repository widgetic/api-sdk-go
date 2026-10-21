# AiAnswersKnowledgeDocument

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Use it to remove the document | 
**Title** | **string** | What the document is called. Visitors see it as the source of an answer, so write it for them | 
**Status** | **string** | &#x60;ready&#x60; documents are used to answer questions. A &#x60;processing&#x60; document is not: it is being added, or an add was interrupted. Remove one that stays in this state and add it again | 
**CharCount** | **int32** | How many characters of text the document holds, after it was cleaned | 
**ChunkCount** | **int32** | Into how many passages the text was cut. Zero until the document is ready | 
**CreatedAt** | **time.Time** |  | 
**ReadyAt** | **NullableTime** | When the document became ready. Null while it is not | 

## Methods

### NewAiAnswersKnowledgeDocument

`func NewAiAnswersKnowledgeDocument(id string, title string, status string, charCount int32, chunkCount int32, createdAt time.Time, readyAt NullableTime, ) *AiAnswersKnowledgeDocument`

NewAiAnswersKnowledgeDocument instantiates a new AiAnswersKnowledgeDocument object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiAnswersKnowledgeDocumentWithDefaults

`func NewAiAnswersKnowledgeDocumentWithDefaults() *AiAnswersKnowledgeDocument`

NewAiAnswersKnowledgeDocumentWithDefaults instantiates a new AiAnswersKnowledgeDocument object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AiAnswersKnowledgeDocument) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AiAnswersKnowledgeDocument) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AiAnswersKnowledgeDocument) SetId(v string)`

SetId sets Id field to given value.


### GetTitle

`func (o *AiAnswersKnowledgeDocument) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *AiAnswersKnowledgeDocument) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *AiAnswersKnowledgeDocument) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetStatus

`func (o *AiAnswersKnowledgeDocument) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AiAnswersKnowledgeDocument) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AiAnswersKnowledgeDocument) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetCharCount

`func (o *AiAnswersKnowledgeDocument) GetCharCount() int32`

GetCharCount returns the CharCount field if non-nil, zero value otherwise.

### GetCharCountOk

`func (o *AiAnswersKnowledgeDocument) GetCharCountOk() (*int32, bool)`

GetCharCountOk returns a tuple with the CharCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharCount

`func (o *AiAnswersKnowledgeDocument) SetCharCount(v int32)`

SetCharCount sets CharCount field to given value.


### GetChunkCount

`func (o *AiAnswersKnowledgeDocument) GetChunkCount() int32`

GetChunkCount returns the ChunkCount field if non-nil, zero value otherwise.

### GetChunkCountOk

`func (o *AiAnswersKnowledgeDocument) GetChunkCountOk() (*int32, bool)`

GetChunkCountOk returns a tuple with the ChunkCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChunkCount

`func (o *AiAnswersKnowledgeDocument) SetChunkCount(v int32)`

SetChunkCount sets ChunkCount field to given value.


### GetCreatedAt

`func (o *AiAnswersKnowledgeDocument) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AiAnswersKnowledgeDocument) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AiAnswersKnowledgeDocument) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetReadyAt

`func (o *AiAnswersKnowledgeDocument) GetReadyAt() time.Time`

GetReadyAt returns the ReadyAt field if non-nil, zero value otherwise.

### GetReadyAtOk

`func (o *AiAnswersKnowledgeDocument) GetReadyAtOk() (*time.Time, bool)`

GetReadyAtOk returns a tuple with the ReadyAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReadyAt

`func (o *AiAnswersKnowledgeDocument) SetReadyAt(v time.Time)`

SetReadyAt sets ReadyAt field to given value.


### SetReadyAtNil

`func (o *AiAnswersKnowledgeDocument) SetReadyAtNil(b bool)`

 SetReadyAtNil sets the value for ReadyAt to be an explicit nil

### UnsetReadyAt
`func (o *AiAnswersKnowledgeDocument) UnsetReadyAt()`

UnsetReadyAt ensures that no value is present for ReadyAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


