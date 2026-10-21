# ValidateCompositionContentResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Valid** | **bool** | False when there is at least one error. Warnings do not change it. | 
**Errors** | Pointer to [**[]ContentCheckFinding**](ContentCheckFinding.md) | What is wrong, at most 100. Absent when &#x60;valid&#x60; is true. | [optional] 
**Warnings** | Pointer to [**[]ContentCheckFinding**](ContentCheckFinding.md) | What is worth a look but does not stop the content from being saved, at most 100. | [optional] 
**SanitizedContent** | Pointer to **map[string]interface{}** | The body as it was sent; nothing is changed. | [optional] 

## Methods

### NewValidateCompositionContentResponseData

`func NewValidateCompositionContentResponseData(valid bool, ) *ValidateCompositionContentResponseData`

NewValidateCompositionContentResponseData instantiates a new ValidateCompositionContentResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewValidateCompositionContentResponseDataWithDefaults

`func NewValidateCompositionContentResponseDataWithDefaults() *ValidateCompositionContentResponseData`

NewValidateCompositionContentResponseDataWithDefaults instantiates a new ValidateCompositionContentResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetValid

`func (o *ValidateCompositionContentResponseData) GetValid() bool`

GetValid returns the Valid field if non-nil, zero value otherwise.

### GetValidOk

`func (o *ValidateCompositionContentResponseData) GetValidOk() (*bool, bool)`

GetValidOk returns a tuple with the Valid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValid

`func (o *ValidateCompositionContentResponseData) SetValid(v bool)`

SetValid sets Valid field to given value.


### GetErrors

`func (o *ValidateCompositionContentResponseData) GetErrors() []ContentCheckFinding`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *ValidateCompositionContentResponseData) GetErrorsOk() (*[]ContentCheckFinding, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *ValidateCompositionContentResponseData) SetErrors(v []ContentCheckFinding)`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *ValidateCompositionContentResponseData) HasErrors() bool`

HasErrors returns a boolean if a field has been set.

### GetWarnings

`func (o *ValidateCompositionContentResponseData) GetWarnings() []ContentCheckFinding`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *ValidateCompositionContentResponseData) GetWarningsOk() (*[]ContentCheckFinding, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *ValidateCompositionContentResponseData) SetWarnings(v []ContentCheckFinding)`

SetWarnings sets Warnings field to given value.

### HasWarnings

`func (o *ValidateCompositionContentResponseData) HasWarnings() bool`

HasWarnings returns a boolean if a field has been set.

### GetSanitizedContent

`func (o *ValidateCompositionContentResponseData) GetSanitizedContent() map[string]interface{}`

GetSanitizedContent returns the SanitizedContent field if non-nil, zero value otherwise.

### GetSanitizedContentOk

`func (o *ValidateCompositionContentResponseData) GetSanitizedContentOk() (*map[string]interface{}, bool)`

GetSanitizedContentOk returns a tuple with the SanitizedContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSanitizedContent

`func (o *ValidateCompositionContentResponseData) SetSanitizedContent(v map[string]interface{})`

SetSanitizedContent sets SanitizedContent field to given value.

### HasSanitizedContent

`func (o *ValidateCompositionContentResponseData) HasSanitizedContent() bool`

HasSanitizedContent returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


