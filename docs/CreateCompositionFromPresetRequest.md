# CreateCompositionFromPresetRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Content** | Pointer to **map[string]interface{}** |  | [optional] 
**Design** | Pointer to **map[string]interface{}** |  | [optional] 
**EmbedSettings** | Pointer to **map[string]interface{}** |  | [optional] 
**Locale** | Pointer to **string** | BCP-47 language tag stored on embed settings for the widget runtime | [optional] 

## Methods

### NewCreateCompositionFromPresetRequest

`func NewCreateCompositionFromPresetRequest(name string, ) *CreateCompositionFromPresetRequest`

NewCreateCompositionFromPresetRequest instantiates a new CreateCompositionFromPresetRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateCompositionFromPresetRequestWithDefaults

`func NewCreateCompositionFromPresetRequestWithDefaults() *CreateCompositionFromPresetRequest`

NewCreateCompositionFromPresetRequestWithDefaults instantiates a new CreateCompositionFromPresetRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateCompositionFromPresetRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateCompositionFromPresetRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateCompositionFromPresetRequest) SetName(v string)`

SetName sets Name field to given value.


### GetContent

`func (o *CreateCompositionFromPresetRequest) GetContent() map[string]interface{}`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *CreateCompositionFromPresetRequest) GetContentOk() (*map[string]interface{}, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *CreateCompositionFromPresetRequest) SetContent(v map[string]interface{})`

SetContent sets Content field to given value.

### HasContent

`func (o *CreateCompositionFromPresetRequest) HasContent() bool`

HasContent returns a boolean if a field has been set.

### GetDesign

`func (o *CreateCompositionFromPresetRequest) GetDesign() map[string]interface{}`

GetDesign returns the Design field if non-nil, zero value otherwise.

### GetDesignOk

`func (o *CreateCompositionFromPresetRequest) GetDesignOk() (*map[string]interface{}, bool)`

GetDesignOk returns a tuple with the Design field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesign

`func (o *CreateCompositionFromPresetRequest) SetDesign(v map[string]interface{})`

SetDesign sets Design field to given value.

### HasDesign

`func (o *CreateCompositionFromPresetRequest) HasDesign() bool`

HasDesign returns a boolean if a field has been set.

### SetDesignNil

`func (o *CreateCompositionFromPresetRequest) SetDesignNil(b bool)`

 SetDesignNil sets the value for Design to be an explicit nil

### UnsetDesign
`func (o *CreateCompositionFromPresetRequest) UnsetDesign()`

UnsetDesign ensures that no value is present for Design, not even an explicit nil
### GetEmbedSettings

`func (o *CreateCompositionFromPresetRequest) GetEmbedSettings() map[string]interface{}`

GetEmbedSettings returns the EmbedSettings field if non-nil, zero value otherwise.

### GetEmbedSettingsOk

`func (o *CreateCompositionFromPresetRequest) GetEmbedSettingsOk() (*map[string]interface{}, bool)`

GetEmbedSettingsOk returns a tuple with the EmbedSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmbedSettings

`func (o *CreateCompositionFromPresetRequest) SetEmbedSettings(v map[string]interface{})`

SetEmbedSettings sets EmbedSettings field to given value.

### HasEmbedSettings

`func (o *CreateCompositionFromPresetRequest) HasEmbedSettings() bool`

HasEmbedSettings returns a boolean if a field has been set.

### GetLocale

`func (o *CreateCompositionFromPresetRequest) GetLocale() string`

GetLocale returns the Locale field if non-nil, zero value otherwise.

### GetLocaleOk

`func (o *CreateCompositionFromPresetRequest) GetLocaleOk() (*string, bool)`

GetLocaleOk returns a tuple with the Locale field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocale

`func (o *CreateCompositionFromPresetRequest) SetLocale(v string)`

SetLocale sets Locale field to given value.

### HasLocale

`func (o *CreateCompositionFromPresetRequest) HasLocale() bool`

HasLocale returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


