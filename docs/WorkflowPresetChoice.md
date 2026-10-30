# WorkflowPresetChoice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | **string** | What &#x60;createWorkspaceWorkflowFromPreset&#x60; takes to say which starting point. | 
**Title** | **string** | The title the offerer gave it, or the name of the workflow it is made from. | 
**Description** | **NullableString** |  | 
**BlockCount** | **int32** | How many blocks it has (compositions, triggers and conditions). | 
**Widgets** | [**[]WorkflowPresetWidget**](WorkflowPresetWidget.md) | The widgets it shows, once each, in the order they first appear. | 

## Methods

### NewWorkflowPresetChoice

`func NewWorkflowPresetChoice(key string, title string, description NullableString, blockCount int32, widgets []WorkflowPresetWidget, ) *WorkflowPresetChoice`

NewWorkflowPresetChoice instantiates a new WorkflowPresetChoice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowPresetChoiceWithDefaults

`func NewWorkflowPresetChoiceWithDefaults() *WorkflowPresetChoice`

NewWorkflowPresetChoiceWithDefaults instantiates a new WorkflowPresetChoice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *WorkflowPresetChoice) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *WorkflowPresetChoice) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *WorkflowPresetChoice) SetKey(v string)`

SetKey sets Key field to given value.


### GetTitle

`func (o *WorkflowPresetChoice) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *WorkflowPresetChoice) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *WorkflowPresetChoice) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetDescription

`func (o *WorkflowPresetChoice) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *WorkflowPresetChoice) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *WorkflowPresetChoice) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *WorkflowPresetChoice) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *WorkflowPresetChoice) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetBlockCount

`func (o *WorkflowPresetChoice) GetBlockCount() int32`

GetBlockCount returns the BlockCount field if non-nil, zero value otherwise.

### GetBlockCountOk

`func (o *WorkflowPresetChoice) GetBlockCountOk() (*int32, bool)`

GetBlockCountOk returns a tuple with the BlockCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockCount

`func (o *WorkflowPresetChoice) SetBlockCount(v int32)`

SetBlockCount sets BlockCount field to given value.


### GetWidgets

`func (o *WorkflowPresetChoice) GetWidgets() []WorkflowPresetWidget`

GetWidgets returns the Widgets field if non-nil, zero value otherwise.

### GetWidgetsOk

`func (o *WorkflowPresetChoice) GetWidgetsOk() (*[]WorkflowPresetWidget, bool)`

GetWidgetsOk returns a tuple with the Widgets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidgets

`func (o *WorkflowPresetChoice) SetWidgets(v []WorkflowPresetWidget)`

SetWidgets sets Widgets field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


