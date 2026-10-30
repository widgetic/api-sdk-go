# OfferedWorkflowPreset

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | **string** | The name your code and the picker use for the starting point. | 
**WorkflowId** | **string** | The workflow it is made from. What people get is its live version as it is when they start. | 
**Title** | **NullableString** | What the picker shows. Null means show the workflow&#39;s name. | 
**Description** | **NullableString** |  | 
**Position** | **int32** | The list is ordered by this, smallest first, then by key. | 
**Available** | **bool** | Whether people can start from it now. A starting point that is not available is not shown to anyone, and says why. | 
**UnavailableReason** | **NullableString** | Why it is not available. &#x60;workflow_missing&#x60;: the workflow was deleted. &#x60;workflow_not_own&#x60;: it is no longer a workflow of your own. &#x60;workflow_archived&#x60;: unarchive it. &#x60;workflow_not_published&#x60;: it has no live version. &#x60;workflow_empty&#x60;: it shows no composition. &#x60;composition_not_own&#x60;: a block shows a composition made for a customer or a team. &#x60;too_many_widgets&#x60;: it chains more than 10 widgets. &#x60;widget_not_preset&#x60;: a widget it chains is no longer offered as a preset.  | 
**WorkflowName** | **NullableString** | The workflow&#39;s name. Null when the workflow is gone. | 
**BlockCount** | **NullableInt32** | How many blocks its live version has. Null when it is not available. | 
**Widgets** | [**[]OfferedWorkflowPresetWidget**](OfferedWorkflowPresetWidget.md) | The widgets it chains, once each, in the order they first appear. Empty when it is not available. | 
**CreatedAt** | **time.Time** |  | 
**UpdatedAt** | **time.Time** |  | 

## Methods

### NewOfferedWorkflowPreset

`func NewOfferedWorkflowPreset(key string, workflowId string, title NullableString, description NullableString, position int32, available bool, unavailableReason NullableString, workflowName NullableString, blockCount NullableInt32, widgets []OfferedWorkflowPresetWidget, createdAt time.Time, updatedAt time.Time, ) *OfferedWorkflowPreset`

NewOfferedWorkflowPreset instantiates a new OfferedWorkflowPreset object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOfferedWorkflowPresetWithDefaults

`func NewOfferedWorkflowPresetWithDefaults() *OfferedWorkflowPreset`

NewOfferedWorkflowPresetWithDefaults instantiates a new OfferedWorkflowPreset object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *OfferedWorkflowPreset) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *OfferedWorkflowPreset) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *OfferedWorkflowPreset) SetKey(v string)`

SetKey sets Key field to given value.


### GetWorkflowId

`func (o *OfferedWorkflowPreset) GetWorkflowId() string`

GetWorkflowId returns the WorkflowId field if non-nil, zero value otherwise.

### GetWorkflowIdOk

`func (o *OfferedWorkflowPreset) GetWorkflowIdOk() (*string, bool)`

GetWorkflowIdOk returns a tuple with the WorkflowId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowId

`func (o *OfferedWorkflowPreset) SetWorkflowId(v string)`

SetWorkflowId sets WorkflowId field to given value.


### GetTitle

`func (o *OfferedWorkflowPreset) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *OfferedWorkflowPreset) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *OfferedWorkflowPreset) SetTitle(v string)`

SetTitle sets Title field to given value.


### SetTitleNil

`func (o *OfferedWorkflowPreset) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *OfferedWorkflowPreset) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetDescription

`func (o *OfferedWorkflowPreset) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *OfferedWorkflowPreset) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *OfferedWorkflowPreset) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *OfferedWorkflowPreset) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *OfferedWorkflowPreset) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetPosition

`func (o *OfferedWorkflowPreset) GetPosition() int32`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *OfferedWorkflowPreset) GetPositionOk() (*int32, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *OfferedWorkflowPreset) SetPosition(v int32)`

SetPosition sets Position field to given value.


### GetAvailable

`func (o *OfferedWorkflowPreset) GetAvailable() bool`

GetAvailable returns the Available field if non-nil, zero value otherwise.

### GetAvailableOk

`func (o *OfferedWorkflowPreset) GetAvailableOk() (*bool, bool)`

GetAvailableOk returns a tuple with the Available field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailable

`func (o *OfferedWorkflowPreset) SetAvailable(v bool)`

SetAvailable sets Available field to given value.


### GetUnavailableReason

`func (o *OfferedWorkflowPreset) GetUnavailableReason() string`

GetUnavailableReason returns the UnavailableReason field if non-nil, zero value otherwise.

### GetUnavailableReasonOk

`func (o *OfferedWorkflowPreset) GetUnavailableReasonOk() (*string, bool)`

GetUnavailableReasonOk returns a tuple with the UnavailableReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnavailableReason

`func (o *OfferedWorkflowPreset) SetUnavailableReason(v string)`

SetUnavailableReason sets UnavailableReason field to given value.


### SetUnavailableReasonNil

`func (o *OfferedWorkflowPreset) SetUnavailableReasonNil(b bool)`

 SetUnavailableReasonNil sets the value for UnavailableReason to be an explicit nil

### UnsetUnavailableReason
`func (o *OfferedWorkflowPreset) UnsetUnavailableReason()`

UnsetUnavailableReason ensures that no value is present for UnavailableReason, not even an explicit nil
### GetWorkflowName

`func (o *OfferedWorkflowPreset) GetWorkflowName() string`

GetWorkflowName returns the WorkflowName field if non-nil, zero value otherwise.

### GetWorkflowNameOk

`func (o *OfferedWorkflowPreset) GetWorkflowNameOk() (*string, bool)`

GetWorkflowNameOk returns a tuple with the WorkflowName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowName

`func (o *OfferedWorkflowPreset) SetWorkflowName(v string)`

SetWorkflowName sets WorkflowName field to given value.


### SetWorkflowNameNil

`func (o *OfferedWorkflowPreset) SetWorkflowNameNil(b bool)`

 SetWorkflowNameNil sets the value for WorkflowName to be an explicit nil

### UnsetWorkflowName
`func (o *OfferedWorkflowPreset) UnsetWorkflowName()`

UnsetWorkflowName ensures that no value is present for WorkflowName, not even an explicit nil
### GetBlockCount

`func (o *OfferedWorkflowPreset) GetBlockCount() int32`

GetBlockCount returns the BlockCount field if non-nil, zero value otherwise.

### GetBlockCountOk

`func (o *OfferedWorkflowPreset) GetBlockCountOk() (*int32, bool)`

GetBlockCountOk returns a tuple with the BlockCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockCount

`func (o *OfferedWorkflowPreset) SetBlockCount(v int32)`

SetBlockCount sets BlockCount field to given value.


### SetBlockCountNil

`func (o *OfferedWorkflowPreset) SetBlockCountNil(b bool)`

 SetBlockCountNil sets the value for BlockCount to be an explicit nil

### UnsetBlockCount
`func (o *OfferedWorkflowPreset) UnsetBlockCount()`

UnsetBlockCount ensures that no value is present for BlockCount, not even an explicit nil
### GetWidgets

`func (o *OfferedWorkflowPreset) GetWidgets() []OfferedWorkflowPresetWidget`

GetWidgets returns the Widgets field if non-nil, zero value otherwise.

### GetWidgetsOk

`func (o *OfferedWorkflowPreset) GetWidgetsOk() (*[]OfferedWorkflowPresetWidget, bool)`

GetWidgetsOk returns a tuple with the Widgets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidgets

`func (o *OfferedWorkflowPreset) SetWidgets(v []OfferedWorkflowPresetWidget)`

SetWidgets sets Widgets field to given value.


### GetCreatedAt

`func (o *OfferedWorkflowPreset) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *OfferedWorkflowPreset) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *OfferedWorkflowPreset) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *OfferedWorkflowPreset) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *OfferedWorkflowPreset) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *OfferedWorkflowPreset) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


