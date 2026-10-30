# WorkflowVersion

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**VersionNumber** | **int32** |  | 
**PublishedAt** | **time.Time** |  | 
**PublishedBy** | Pointer to [**NullableWorkflowVersionPublishedBy**](WorkflowVersionPublishedBy.md) |  | [optional] 
**Timezone** | **string** |  | 
**IsLive** | **bool** | Whether this is the version visitors who are new to the workflow get. | 

## Methods

### NewWorkflowVersion

`func NewWorkflowVersion(id string, versionNumber int32, publishedAt time.Time, timezone string, isLive bool, ) *WorkflowVersion`

NewWorkflowVersion instantiates a new WorkflowVersion object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowVersionWithDefaults

`func NewWorkflowVersionWithDefaults() *WorkflowVersion`

NewWorkflowVersionWithDefaults instantiates a new WorkflowVersion object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *WorkflowVersion) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WorkflowVersion) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WorkflowVersion) SetId(v string)`

SetId sets Id field to given value.


### GetVersionNumber

`func (o *WorkflowVersion) GetVersionNumber() int32`

GetVersionNumber returns the VersionNumber field if non-nil, zero value otherwise.

### GetVersionNumberOk

`func (o *WorkflowVersion) GetVersionNumberOk() (*int32, bool)`

GetVersionNumberOk returns a tuple with the VersionNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersionNumber

`func (o *WorkflowVersion) SetVersionNumber(v int32)`

SetVersionNumber sets VersionNumber field to given value.


### GetPublishedAt

`func (o *WorkflowVersion) GetPublishedAt() time.Time`

GetPublishedAt returns the PublishedAt field if non-nil, zero value otherwise.

### GetPublishedAtOk

`func (o *WorkflowVersion) GetPublishedAtOk() (*time.Time, bool)`

GetPublishedAtOk returns a tuple with the PublishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishedAt

`func (o *WorkflowVersion) SetPublishedAt(v time.Time)`

SetPublishedAt sets PublishedAt field to given value.


### GetPublishedBy

`func (o *WorkflowVersion) GetPublishedBy() WorkflowVersionPublishedBy`

GetPublishedBy returns the PublishedBy field if non-nil, zero value otherwise.

### GetPublishedByOk

`func (o *WorkflowVersion) GetPublishedByOk() (*WorkflowVersionPublishedBy, bool)`

GetPublishedByOk returns a tuple with the PublishedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishedBy

`func (o *WorkflowVersion) SetPublishedBy(v WorkflowVersionPublishedBy)`

SetPublishedBy sets PublishedBy field to given value.

### HasPublishedBy

`func (o *WorkflowVersion) HasPublishedBy() bool`

HasPublishedBy returns a boolean if a field has been set.

### SetPublishedByNil

`func (o *WorkflowVersion) SetPublishedByNil(b bool)`

 SetPublishedByNil sets the value for PublishedBy to be an explicit nil

### UnsetPublishedBy
`func (o *WorkflowVersion) UnsetPublishedBy()`

UnsetPublishedBy ensures that no value is present for PublishedBy, not even an explicit nil
### GetTimezone

`func (o *WorkflowVersion) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *WorkflowVersion) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *WorkflowVersion) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.


### GetIsLive

`func (o *WorkflowVersion) GetIsLive() bool`

GetIsLive returns the IsLive field if non-nil, zero value otherwise.

### GetIsLiveOk

`func (o *WorkflowVersion) GetIsLiveOk() (*bool, bool)`

GetIsLiveOk returns a tuple with the IsLive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsLive

`func (o *WorkflowVersion) SetIsLive(v bool)`

SetIsLive sets IsLive field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


