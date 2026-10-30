# CreateWorkspaceWorkflowFromPresetRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | **string** | The starting point, as &#x60;listWorkspaceWorkflowPresets&#x60; gives it. | 
**Name** | Pointer to **NullableString** | The new workflow&#39;s name. The starting point&#39;s title when left out. | [optional] 

## Methods

### NewCreateWorkspaceWorkflowFromPresetRequest

`func NewCreateWorkspaceWorkflowFromPresetRequest(key string, ) *CreateWorkspaceWorkflowFromPresetRequest`

NewCreateWorkspaceWorkflowFromPresetRequest instantiates a new CreateWorkspaceWorkflowFromPresetRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateWorkspaceWorkflowFromPresetRequestWithDefaults

`func NewCreateWorkspaceWorkflowFromPresetRequestWithDefaults() *CreateWorkspaceWorkflowFromPresetRequest`

NewCreateWorkspaceWorkflowFromPresetRequestWithDefaults instantiates a new CreateWorkspaceWorkflowFromPresetRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *CreateWorkspaceWorkflowFromPresetRequest) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *CreateWorkspaceWorkflowFromPresetRequest) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *CreateWorkspaceWorkflowFromPresetRequest) SetKey(v string)`

SetKey sets Key field to given value.


### GetName

`func (o *CreateWorkspaceWorkflowFromPresetRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateWorkspaceWorkflowFromPresetRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateWorkspaceWorkflowFromPresetRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CreateWorkspaceWorkflowFromPresetRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *CreateWorkspaceWorkflowFromPresetRequest) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *CreateWorkspaceWorkflowFromPresetRequest) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


