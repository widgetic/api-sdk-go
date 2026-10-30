# CreateWorkspaceWorkflowRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**CompositionId** | Pointer to **NullableString** | A composition of this workspace to start with. | [optional] 
**Timezone** | Pointer to **NullableString** | An IANA time zone name; UTC when not given. | [optional] 

## Methods

### NewCreateWorkspaceWorkflowRequest

`func NewCreateWorkspaceWorkflowRequest(name string, ) *CreateWorkspaceWorkflowRequest`

NewCreateWorkspaceWorkflowRequest instantiates a new CreateWorkspaceWorkflowRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateWorkspaceWorkflowRequestWithDefaults

`func NewCreateWorkspaceWorkflowRequestWithDefaults() *CreateWorkspaceWorkflowRequest`

NewCreateWorkspaceWorkflowRequestWithDefaults instantiates a new CreateWorkspaceWorkflowRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateWorkspaceWorkflowRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateWorkspaceWorkflowRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateWorkspaceWorkflowRequest) SetName(v string)`

SetName sets Name field to given value.


### GetCompositionId

`func (o *CreateWorkspaceWorkflowRequest) GetCompositionId() string`

GetCompositionId returns the CompositionId field if non-nil, zero value otherwise.

### GetCompositionIdOk

`func (o *CreateWorkspaceWorkflowRequest) GetCompositionIdOk() (*string, bool)`

GetCompositionIdOk returns a tuple with the CompositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompositionId

`func (o *CreateWorkspaceWorkflowRequest) SetCompositionId(v string)`

SetCompositionId sets CompositionId field to given value.

### HasCompositionId

`func (o *CreateWorkspaceWorkflowRequest) HasCompositionId() bool`

HasCompositionId returns a boolean if a field has been set.

### SetCompositionIdNil

`func (o *CreateWorkspaceWorkflowRequest) SetCompositionIdNil(b bool)`

 SetCompositionIdNil sets the value for CompositionId to be an explicit nil

### UnsetCompositionId
`func (o *CreateWorkspaceWorkflowRequest) UnsetCompositionId()`

UnsetCompositionId ensures that no value is present for CompositionId, not even an explicit nil
### GetTimezone

`func (o *CreateWorkspaceWorkflowRequest) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *CreateWorkspaceWorkflowRequest) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *CreateWorkspaceWorkflowRequest) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *CreateWorkspaceWorkflowRequest) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.

### SetTimezoneNil

`func (o *CreateWorkspaceWorkflowRequest) SetTimezoneNil(b bool)`

 SetTimezoneNil sets the value for Timezone to be an explicit nil

### UnsetTimezone
`func (o *CreateWorkspaceWorkflowRequest) UnsetTimezone()`

UnsetTimezone ensures that no value is present for Timezone, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


