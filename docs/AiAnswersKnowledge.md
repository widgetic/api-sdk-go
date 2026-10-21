# AiAnswersKnowledge

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Documents** | [**[]AiAnswersKnowledgeDocument**](AiAnswersKnowledgeDocument.md) | Oldest first | 
**Totals** | [**AiAnswersKnowledgeTotals**](AiAnswersKnowledgeTotals.md) |  | 

## Methods

### NewAiAnswersKnowledge

`func NewAiAnswersKnowledge(documents []AiAnswersKnowledgeDocument, totals AiAnswersKnowledgeTotals, ) *AiAnswersKnowledge`

NewAiAnswersKnowledge instantiates a new AiAnswersKnowledge object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiAnswersKnowledgeWithDefaults

`func NewAiAnswersKnowledgeWithDefaults() *AiAnswersKnowledge`

NewAiAnswersKnowledgeWithDefaults instantiates a new AiAnswersKnowledge object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDocuments

`func (o *AiAnswersKnowledge) GetDocuments() []AiAnswersKnowledgeDocument`

GetDocuments returns the Documents field if non-nil, zero value otherwise.

### GetDocumentsOk

`func (o *AiAnswersKnowledge) GetDocumentsOk() (*[]AiAnswersKnowledgeDocument, bool)`

GetDocumentsOk returns a tuple with the Documents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocuments

`func (o *AiAnswersKnowledge) SetDocuments(v []AiAnswersKnowledgeDocument)`

SetDocuments sets Documents field to given value.


### GetTotals

`func (o *AiAnswersKnowledge) GetTotals() AiAnswersKnowledgeTotals`

GetTotals returns the Totals field if non-nil, zero value otherwise.

### GetTotalsOk

`func (o *AiAnswersKnowledge) GetTotalsOk() (*AiAnswersKnowledgeTotals, bool)`

GetTotalsOk returns a tuple with the Totals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotals

`func (o *AiAnswersKnowledge) SetTotals(v AiAnswersKnowledgeTotals)`

SetTotals sets Totals field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


