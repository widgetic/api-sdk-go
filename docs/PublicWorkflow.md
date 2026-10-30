# PublicWorkflow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**WorkflowId** | **string** |  | 
**Status** | **string** |  | 
**VersionId** | Pointer to **string** | The published version this answer is for. A visitor who starts on it finishes on it. | [optional] 
**VersionNumber** | Pointer to **int32** |  | [optional] 
**PublishedAt** | Pointer to **time.Time** |  | [optional] 
**StartCompositionId** | Pointer to **string** | The composition a new visitor starts on, so the page can show it while the graph is still being read. | [optional] 
**Timezone** | Pointer to **string** | The zone date and time triggers are read in. | [optional] 
**Graph** | Pointer to [**WorkflowGraph**](WorkflowGraph.md) |  | [optional] 
**Translations** | Pointer to [**map[string]PublicWorkflowTranslation**](PublicWorkflowTranslation.md) | The languages the compositions of the graph can be shown in, by composition id: only the compositions that have an active translation with a language besides their own, so the field is absent when none has. The browser shows the copy in the visitor&#39;s language in place of the composition, at the first step and at every move, with the rules &#x60;&lt;widgetic-translations&gt;&#x60; follows (the visitor&#39;s language, then its language family, then the language the composition was written in). It is read when the answer is made, not when the version was published, so a language added to a translation reaches visitors without a new publish. Ids, counts and the visitor&#39;s place keep naming the composition of the graph, never its copy.  | [optional] 
**EventToken** | Pointer to **string** | What lets the browser report counts for this version, valid for 24 hours. Absent when this server cannot sign one, and the browser then reports nothing.  | [optional] 

## Methods

### NewPublicWorkflow

`func NewPublicWorkflow(workflowId string, status string, ) *PublicWorkflow`

NewPublicWorkflow instantiates a new PublicWorkflow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublicWorkflowWithDefaults

`func NewPublicWorkflowWithDefaults() *PublicWorkflow`

NewPublicWorkflowWithDefaults instantiates a new PublicWorkflow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWorkflowId

`func (o *PublicWorkflow) GetWorkflowId() string`

GetWorkflowId returns the WorkflowId field if non-nil, zero value otherwise.

### GetWorkflowIdOk

`func (o *PublicWorkflow) GetWorkflowIdOk() (*string, bool)`

GetWorkflowIdOk returns a tuple with the WorkflowId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowId

`func (o *PublicWorkflow) SetWorkflowId(v string)`

SetWorkflowId sets WorkflowId field to given value.


### GetStatus

`func (o *PublicWorkflow) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PublicWorkflow) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PublicWorkflow) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetVersionId

`func (o *PublicWorkflow) GetVersionId() string`

GetVersionId returns the VersionId field if non-nil, zero value otherwise.

### GetVersionIdOk

`func (o *PublicWorkflow) GetVersionIdOk() (*string, bool)`

GetVersionIdOk returns a tuple with the VersionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersionId

`func (o *PublicWorkflow) SetVersionId(v string)`

SetVersionId sets VersionId field to given value.

### HasVersionId

`func (o *PublicWorkflow) HasVersionId() bool`

HasVersionId returns a boolean if a field has been set.

### GetVersionNumber

`func (o *PublicWorkflow) GetVersionNumber() int32`

GetVersionNumber returns the VersionNumber field if non-nil, zero value otherwise.

### GetVersionNumberOk

`func (o *PublicWorkflow) GetVersionNumberOk() (*int32, bool)`

GetVersionNumberOk returns a tuple with the VersionNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersionNumber

`func (o *PublicWorkflow) SetVersionNumber(v int32)`

SetVersionNumber sets VersionNumber field to given value.

### HasVersionNumber

`func (o *PublicWorkflow) HasVersionNumber() bool`

HasVersionNumber returns a boolean if a field has been set.

### GetPublishedAt

`func (o *PublicWorkflow) GetPublishedAt() time.Time`

GetPublishedAt returns the PublishedAt field if non-nil, zero value otherwise.

### GetPublishedAtOk

`func (o *PublicWorkflow) GetPublishedAtOk() (*time.Time, bool)`

GetPublishedAtOk returns a tuple with the PublishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishedAt

`func (o *PublicWorkflow) SetPublishedAt(v time.Time)`

SetPublishedAt sets PublishedAt field to given value.

### HasPublishedAt

`func (o *PublicWorkflow) HasPublishedAt() bool`

HasPublishedAt returns a boolean if a field has been set.

### GetStartCompositionId

`func (o *PublicWorkflow) GetStartCompositionId() string`

GetStartCompositionId returns the StartCompositionId field if non-nil, zero value otherwise.

### GetStartCompositionIdOk

`func (o *PublicWorkflow) GetStartCompositionIdOk() (*string, bool)`

GetStartCompositionIdOk returns a tuple with the StartCompositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartCompositionId

`func (o *PublicWorkflow) SetStartCompositionId(v string)`

SetStartCompositionId sets StartCompositionId field to given value.

### HasStartCompositionId

`func (o *PublicWorkflow) HasStartCompositionId() bool`

HasStartCompositionId returns a boolean if a field has been set.

### GetTimezone

`func (o *PublicWorkflow) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *PublicWorkflow) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *PublicWorkflow) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *PublicWorkflow) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.

### GetGraph

`func (o *PublicWorkflow) GetGraph() WorkflowGraph`

GetGraph returns the Graph field if non-nil, zero value otherwise.

### GetGraphOk

`func (o *PublicWorkflow) GetGraphOk() (*WorkflowGraph, bool)`

GetGraphOk returns a tuple with the Graph field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGraph

`func (o *PublicWorkflow) SetGraph(v WorkflowGraph)`

SetGraph sets Graph field to given value.

### HasGraph

`func (o *PublicWorkflow) HasGraph() bool`

HasGraph returns a boolean if a field has been set.

### GetTranslations

`func (o *PublicWorkflow) GetTranslations() map[string]PublicWorkflowTranslation`

GetTranslations returns the Translations field if non-nil, zero value otherwise.

### GetTranslationsOk

`func (o *PublicWorkflow) GetTranslationsOk() (*map[string]PublicWorkflowTranslation, bool)`

GetTranslationsOk returns a tuple with the Translations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTranslations

`func (o *PublicWorkflow) SetTranslations(v map[string]PublicWorkflowTranslation)`

SetTranslations sets Translations field to given value.

### HasTranslations

`func (o *PublicWorkflow) HasTranslations() bool`

HasTranslations returns a boolean if a field has been set.

### GetEventToken

`func (o *PublicWorkflow) GetEventToken() string`

GetEventToken returns the EventToken field if non-nil, zero value otherwise.

### GetEventTokenOk

`func (o *PublicWorkflow) GetEventTokenOk() (*string, bool)`

GetEventTokenOk returns a tuple with the EventToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventToken

`func (o *PublicWorkflow) SetEventToken(v string)`

SetEventToken sets EventToken field to given value.

### HasEventToken

`func (o *PublicWorkflow) HasEventToken() bool`

HasEventToken returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


