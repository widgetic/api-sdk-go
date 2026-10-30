# PublicWorkflowTranslation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RootLanguage** | **string** | The language the composition was written in. A visitor whose language matches nothing else is shown the composition itself. | 
**Compositions** | **map[string]string** | Language code (lower case) to the composition that shows it. The root language is listed too, and is the composition itself. | 

## Methods

### NewPublicWorkflowTranslation

`func NewPublicWorkflowTranslation(rootLanguage string, compositions map[string]string, ) *PublicWorkflowTranslation`

NewPublicWorkflowTranslation instantiates a new PublicWorkflowTranslation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublicWorkflowTranslationWithDefaults

`func NewPublicWorkflowTranslationWithDefaults() *PublicWorkflowTranslation`

NewPublicWorkflowTranslationWithDefaults instantiates a new PublicWorkflowTranslation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRootLanguage

`func (o *PublicWorkflowTranslation) GetRootLanguage() string`

GetRootLanguage returns the RootLanguage field if non-nil, zero value otherwise.

### GetRootLanguageOk

`func (o *PublicWorkflowTranslation) GetRootLanguageOk() (*string, bool)`

GetRootLanguageOk returns a tuple with the RootLanguage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRootLanguage

`func (o *PublicWorkflowTranslation) SetRootLanguage(v string)`

SetRootLanguage sets RootLanguage field to given value.


### GetCompositions

`func (o *PublicWorkflowTranslation) GetCompositions() map[string]string`

GetCompositions returns the Compositions field if non-nil, zero value otherwise.

### GetCompositionsOk

`func (o *PublicWorkflowTranslation) GetCompositionsOk() (*map[string]string, bool)`

GetCompositionsOk returns a tuple with the Compositions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompositions

`func (o *PublicWorkflowTranslation) SetCompositions(v map[string]string)`

SetCompositions sets Compositions field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


