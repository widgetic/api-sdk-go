# WorkflowCompositionOption

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Name** | **string** |  | 
**ThumbnailUrl** | Pointer to **NullableString** |  | [optional] 
**Published** | **bool** | Whether the composition can be shown at all (its widget has a published version). | 
**AllowedWebsites** | **[]string** | The websites the composition may be embedded on; empty means anywhere. | 
**Inputs** | [**WorkflowCompositionOptionInputs**](WorkflowCompositionOptionInputs.md) |  | 
**Actions** | [**WorkflowCompositionOptionActions**](WorkflowCompositionOptionActions.md) |  | 

## Methods

### NewWorkflowCompositionOption

`func NewWorkflowCompositionOption(id string, name string, published bool, allowedWebsites []string, inputs WorkflowCompositionOptionInputs, actions WorkflowCompositionOptionActions, ) *WorkflowCompositionOption`

NewWorkflowCompositionOption instantiates a new WorkflowCompositionOption object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowCompositionOptionWithDefaults

`func NewWorkflowCompositionOptionWithDefaults() *WorkflowCompositionOption`

NewWorkflowCompositionOptionWithDefaults instantiates a new WorkflowCompositionOption object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *WorkflowCompositionOption) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WorkflowCompositionOption) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WorkflowCompositionOption) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *WorkflowCompositionOption) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *WorkflowCompositionOption) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *WorkflowCompositionOption) SetName(v string)`

SetName sets Name field to given value.


### GetThumbnailUrl

`func (o *WorkflowCompositionOption) GetThumbnailUrl() string`

GetThumbnailUrl returns the ThumbnailUrl field if non-nil, zero value otherwise.

### GetThumbnailUrlOk

`func (o *WorkflowCompositionOption) GetThumbnailUrlOk() (*string, bool)`

GetThumbnailUrlOk returns a tuple with the ThumbnailUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThumbnailUrl

`func (o *WorkflowCompositionOption) SetThumbnailUrl(v string)`

SetThumbnailUrl sets ThumbnailUrl field to given value.

### HasThumbnailUrl

`func (o *WorkflowCompositionOption) HasThumbnailUrl() bool`

HasThumbnailUrl returns a boolean if a field has been set.

### SetThumbnailUrlNil

`func (o *WorkflowCompositionOption) SetThumbnailUrlNil(b bool)`

 SetThumbnailUrlNil sets the value for ThumbnailUrl to be an explicit nil

### UnsetThumbnailUrl
`func (o *WorkflowCompositionOption) UnsetThumbnailUrl()`

UnsetThumbnailUrl ensures that no value is present for ThumbnailUrl, not even an explicit nil
### GetPublished

`func (o *WorkflowCompositionOption) GetPublished() bool`

GetPublished returns the Published field if non-nil, zero value otherwise.

### GetPublishedOk

`func (o *WorkflowCompositionOption) GetPublishedOk() (*bool, bool)`

GetPublishedOk returns a tuple with the Published field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublished

`func (o *WorkflowCompositionOption) SetPublished(v bool)`

SetPublished sets Published field to given value.


### GetAllowedWebsites

`func (o *WorkflowCompositionOption) GetAllowedWebsites() []string`

GetAllowedWebsites returns the AllowedWebsites field if non-nil, zero value otherwise.

### GetAllowedWebsitesOk

`func (o *WorkflowCompositionOption) GetAllowedWebsitesOk() (*[]string, bool)`

GetAllowedWebsitesOk returns a tuple with the AllowedWebsites field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowedWebsites

`func (o *WorkflowCompositionOption) SetAllowedWebsites(v []string)`

SetAllowedWebsites sets AllowedWebsites field to given value.


### GetInputs

`func (o *WorkflowCompositionOption) GetInputs() WorkflowCompositionOptionInputs`

GetInputs returns the Inputs field if non-nil, zero value otherwise.

### GetInputsOk

`func (o *WorkflowCompositionOption) GetInputsOk() (*WorkflowCompositionOptionInputs, bool)`

GetInputsOk returns a tuple with the Inputs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputs

`func (o *WorkflowCompositionOption) SetInputs(v WorkflowCompositionOptionInputs)`

SetInputs sets Inputs field to given value.


### GetActions

`func (o *WorkflowCompositionOption) GetActions() WorkflowCompositionOptionActions`

GetActions returns the Actions field if non-nil, zero value otherwise.

### GetActionsOk

`func (o *WorkflowCompositionOption) GetActionsOk() (*WorkflowCompositionOptionActions, bool)`

GetActionsOk returns a tuple with the Actions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActions

`func (o *WorkflowCompositionOption) SetActions(v WorkflowCompositionOptionActions)`

SetActions sets Actions field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


