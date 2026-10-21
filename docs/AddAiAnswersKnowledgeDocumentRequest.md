# AddAiAnswersKnowledgeDocumentRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Title** | **string** | What the document is called, on one line. Visitors see it as the source of an answer. Line breaks and invisible characters are removed | 
**Text** | **string** | The text of the document, as plain text. It is cleaned (line endings are made the same, invisible characters and surplus blank lines are removed) and then counted: up to 100000 characters. Markup is not interpreted, so paste the words, not a web page | 

## Methods

### NewAddAiAnswersKnowledgeDocumentRequest

`func NewAddAiAnswersKnowledgeDocumentRequest(title string, text string, ) *AddAiAnswersKnowledgeDocumentRequest`

NewAddAiAnswersKnowledgeDocumentRequest instantiates a new AddAiAnswersKnowledgeDocumentRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAddAiAnswersKnowledgeDocumentRequestWithDefaults

`func NewAddAiAnswersKnowledgeDocumentRequestWithDefaults() *AddAiAnswersKnowledgeDocumentRequest`

NewAddAiAnswersKnowledgeDocumentRequestWithDefaults instantiates a new AddAiAnswersKnowledgeDocumentRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTitle

`func (o *AddAiAnswersKnowledgeDocumentRequest) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *AddAiAnswersKnowledgeDocumentRequest) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *AddAiAnswersKnowledgeDocumentRequest) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetText

`func (o *AddAiAnswersKnowledgeDocumentRequest) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *AddAiAnswersKnowledgeDocumentRequest) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *AddAiAnswersKnowledgeDocumentRequest) SetText(v string)`

SetText sets Text field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


