# WorkflowDetail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Name** | **string** |  | 
**ManagedUserId** | Pointer to **NullableString** | The customer of a partner (a managed user) this workflow was made for, or null when it is its workspace&#39;s own. A customer&#39;s editor session lists and opens only the workflows filed under that customer; the partner&#39;s own account sees every customer&#39;s and tells them apart by this. It is set when the workflow is made and never changes.  | [optional] 
**Status** | [**WorkflowStatus**](WorkflowStatus.md) |  | 
**Revision** | **int32** | Rises by one with every save. A save, a publish, a discard and a restore each name the revision they started from. | 
**UnpublishedChanges** | **bool** | Whether the draft differs from the live version. | 
**CompositionIds** | **[]string** |  | 
**BlockCount** | **int32** |  | 
**Timezone** | **string** | The zone date and time triggers are read in (stored as UTC). | 
**RunsCount** | **int32** | Visitors who started the workflow, over its whole life. | 
**LiveVersionId** | Pointer to **NullableString** |  | [optional] 
**CreatedAt** | **time.Time** |  | 
**UpdatedAt** | **time.Time** |  | 
**FirstPublishedAt** | Pointer to **NullableTime** |  | [optional] 
**LastPublishedAt** | Pointer to **NullableTime** |  | [optional] 
**PausedAt** | Pointer to **NullableTime** |  | [optional] 
**ArchivedAt** | Pointer to **NullableTime** |  | [optional] 
**Graph** | [**WorkflowGraph**](WorkflowGraph.md) |  | 
**LiveVersion** | Pointer to [**NullableWorkflowVersion**](WorkflowVersion.md) | The version visitors get, without its graph; null before the first publish. | [optional] 
**EverPublished** | **bool** | Whether it was ever published (it then has versions and counts, and visitors may have run it). | 
**LastEditedBy** | Pointer to [**NullableWorkflowDetailAllOfLastEditedBy**](WorkflowDetailAllOfLastEditedBy.md) |  | [optional] 
**LastEditedAt** | Pointer to **NullableTime** | When that latest change was made. Present whenever &#x60;lastEditedBy&#x60; is. | [optional] 

## Methods

### NewWorkflowDetail

`func NewWorkflowDetail(id string, name string, status WorkflowStatus, revision int32, unpublishedChanges bool, compositionIds []string, blockCount int32, timezone string, runsCount int32, createdAt time.Time, updatedAt time.Time, graph WorkflowGraph, everPublished bool, ) *WorkflowDetail`

NewWorkflowDetail instantiates a new WorkflowDetail object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowDetailWithDefaults

`func NewWorkflowDetailWithDefaults() *WorkflowDetail`

NewWorkflowDetailWithDefaults instantiates a new WorkflowDetail object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *WorkflowDetail) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WorkflowDetail) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WorkflowDetail) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *WorkflowDetail) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *WorkflowDetail) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *WorkflowDetail) SetName(v string)`

SetName sets Name field to given value.


### GetManagedUserId

`func (o *WorkflowDetail) GetManagedUserId() string`

GetManagedUserId returns the ManagedUserId field if non-nil, zero value otherwise.

### GetManagedUserIdOk

`func (o *WorkflowDetail) GetManagedUserIdOk() (*string, bool)`

GetManagedUserIdOk returns a tuple with the ManagedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUserId

`func (o *WorkflowDetail) SetManagedUserId(v string)`

SetManagedUserId sets ManagedUserId field to given value.

### HasManagedUserId

`func (o *WorkflowDetail) HasManagedUserId() bool`

HasManagedUserId returns a boolean if a field has been set.

### SetManagedUserIdNil

`func (o *WorkflowDetail) SetManagedUserIdNil(b bool)`

 SetManagedUserIdNil sets the value for ManagedUserId to be an explicit nil

### UnsetManagedUserId
`func (o *WorkflowDetail) UnsetManagedUserId()`

UnsetManagedUserId ensures that no value is present for ManagedUserId, not even an explicit nil
### GetStatus

`func (o *WorkflowDetail) GetStatus() WorkflowStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *WorkflowDetail) GetStatusOk() (*WorkflowStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *WorkflowDetail) SetStatus(v WorkflowStatus)`

SetStatus sets Status field to given value.


### GetRevision

`func (o *WorkflowDetail) GetRevision() int32`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *WorkflowDetail) GetRevisionOk() (*int32, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *WorkflowDetail) SetRevision(v int32)`

SetRevision sets Revision field to given value.


### GetUnpublishedChanges

`func (o *WorkflowDetail) GetUnpublishedChanges() bool`

GetUnpublishedChanges returns the UnpublishedChanges field if non-nil, zero value otherwise.

### GetUnpublishedChangesOk

`func (o *WorkflowDetail) GetUnpublishedChangesOk() (*bool, bool)`

GetUnpublishedChangesOk returns a tuple with the UnpublishedChanges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnpublishedChanges

`func (o *WorkflowDetail) SetUnpublishedChanges(v bool)`

SetUnpublishedChanges sets UnpublishedChanges field to given value.


### GetCompositionIds

`func (o *WorkflowDetail) GetCompositionIds() []string`

GetCompositionIds returns the CompositionIds field if non-nil, zero value otherwise.

### GetCompositionIdsOk

`func (o *WorkflowDetail) GetCompositionIdsOk() (*[]string, bool)`

GetCompositionIdsOk returns a tuple with the CompositionIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompositionIds

`func (o *WorkflowDetail) SetCompositionIds(v []string)`

SetCompositionIds sets CompositionIds field to given value.


### GetBlockCount

`func (o *WorkflowDetail) GetBlockCount() int32`

GetBlockCount returns the BlockCount field if non-nil, zero value otherwise.

### GetBlockCountOk

`func (o *WorkflowDetail) GetBlockCountOk() (*int32, bool)`

GetBlockCountOk returns a tuple with the BlockCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockCount

`func (o *WorkflowDetail) SetBlockCount(v int32)`

SetBlockCount sets BlockCount field to given value.


### GetTimezone

`func (o *WorkflowDetail) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *WorkflowDetail) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *WorkflowDetail) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.


### GetRunsCount

`func (o *WorkflowDetail) GetRunsCount() int32`

GetRunsCount returns the RunsCount field if non-nil, zero value otherwise.

### GetRunsCountOk

`func (o *WorkflowDetail) GetRunsCountOk() (*int32, bool)`

GetRunsCountOk returns a tuple with the RunsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunsCount

`func (o *WorkflowDetail) SetRunsCount(v int32)`

SetRunsCount sets RunsCount field to given value.


### GetLiveVersionId

`func (o *WorkflowDetail) GetLiveVersionId() string`

GetLiveVersionId returns the LiveVersionId field if non-nil, zero value otherwise.

### GetLiveVersionIdOk

`func (o *WorkflowDetail) GetLiveVersionIdOk() (*string, bool)`

GetLiveVersionIdOk returns a tuple with the LiveVersionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLiveVersionId

`func (o *WorkflowDetail) SetLiveVersionId(v string)`

SetLiveVersionId sets LiveVersionId field to given value.

### HasLiveVersionId

`func (o *WorkflowDetail) HasLiveVersionId() bool`

HasLiveVersionId returns a boolean if a field has been set.

### SetLiveVersionIdNil

`func (o *WorkflowDetail) SetLiveVersionIdNil(b bool)`

 SetLiveVersionIdNil sets the value for LiveVersionId to be an explicit nil

### UnsetLiveVersionId
`func (o *WorkflowDetail) UnsetLiveVersionId()`

UnsetLiveVersionId ensures that no value is present for LiveVersionId, not even an explicit nil
### GetCreatedAt

`func (o *WorkflowDetail) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *WorkflowDetail) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *WorkflowDetail) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *WorkflowDetail) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *WorkflowDetail) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *WorkflowDetail) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetFirstPublishedAt

`func (o *WorkflowDetail) GetFirstPublishedAt() time.Time`

GetFirstPublishedAt returns the FirstPublishedAt field if non-nil, zero value otherwise.

### GetFirstPublishedAtOk

`func (o *WorkflowDetail) GetFirstPublishedAtOk() (*time.Time, bool)`

GetFirstPublishedAtOk returns a tuple with the FirstPublishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstPublishedAt

`func (o *WorkflowDetail) SetFirstPublishedAt(v time.Time)`

SetFirstPublishedAt sets FirstPublishedAt field to given value.

### HasFirstPublishedAt

`func (o *WorkflowDetail) HasFirstPublishedAt() bool`

HasFirstPublishedAt returns a boolean if a field has been set.

### SetFirstPublishedAtNil

`func (o *WorkflowDetail) SetFirstPublishedAtNil(b bool)`

 SetFirstPublishedAtNil sets the value for FirstPublishedAt to be an explicit nil

### UnsetFirstPublishedAt
`func (o *WorkflowDetail) UnsetFirstPublishedAt()`

UnsetFirstPublishedAt ensures that no value is present for FirstPublishedAt, not even an explicit nil
### GetLastPublishedAt

`func (o *WorkflowDetail) GetLastPublishedAt() time.Time`

GetLastPublishedAt returns the LastPublishedAt field if non-nil, zero value otherwise.

### GetLastPublishedAtOk

`func (o *WorkflowDetail) GetLastPublishedAtOk() (*time.Time, bool)`

GetLastPublishedAtOk returns a tuple with the LastPublishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastPublishedAt

`func (o *WorkflowDetail) SetLastPublishedAt(v time.Time)`

SetLastPublishedAt sets LastPublishedAt field to given value.

### HasLastPublishedAt

`func (o *WorkflowDetail) HasLastPublishedAt() bool`

HasLastPublishedAt returns a boolean if a field has been set.

### SetLastPublishedAtNil

`func (o *WorkflowDetail) SetLastPublishedAtNil(b bool)`

 SetLastPublishedAtNil sets the value for LastPublishedAt to be an explicit nil

### UnsetLastPublishedAt
`func (o *WorkflowDetail) UnsetLastPublishedAt()`

UnsetLastPublishedAt ensures that no value is present for LastPublishedAt, not even an explicit nil
### GetPausedAt

`func (o *WorkflowDetail) GetPausedAt() time.Time`

GetPausedAt returns the PausedAt field if non-nil, zero value otherwise.

### GetPausedAtOk

`func (o *WorkflowDetail) GetPausedAtOk() (*time.Time, bool)`

GetPausedAtOk returns a tuple with the PausedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPausedAt

`func (o *WorkflowDetail) SetPausedAt(v time.Time)`

SetPausedAt sets PausedAt field to given value.

### HasPausedAt

`func (o *WorkflowDetail) HasPausedAt() bool`

HasPausedAt returns a boolean if a field has been set.

### SetPausedAtNil

`func (o *WorkflowDetail) SetPausedAtNil(b bool)`

 SetPausedAtNil sets the value for PausedAt to be an explicit nil

### UnsetPausedAt
`func (o *WorkflowDetail) UnsetPausedAt()`

UnsetPausedAt ensures that no value is present for PausedAt, not even an explicit nil
### GetArchivedAt

`func (o *WorkflowDetail) GetArchivedAt() time.Time`

GetArchivedAt returns the ArchivedAt field if non-nil, zero value otherwise.

### GetArchivedAtOk

`func (o *WorkflowDetail) GetArchivedAtOk() (*time.Time, bool)`

GetArchivedAtOk returns a tuple with the ArchivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchivedAt

`func (o *WorkflowDetail) SetArchivedAt(v time.Time)`

SetArchivedAt sets ArchivedAt field to given value.

### HasArchivedAt

`func (o *WorkflowDetail) HasArchivedAt() bool`

HasArchivedAt returns a boolean if a field has been set.

### SetArchivedAtNil

`func (o *WorkflowDetail) SetArchivedAtNil(b bool)`

 SetArchivedAtNil sets the value for ArchivedAt to be an explicit nil

### UnsetArchivedAt
`func (o *WorkflowDetail) UnsetArchivedAt()`

UnsetArchivedAt ensures that no value is present for ArchivedAt, not even an explicit nil
### GetGraph

`func (o *WorkflowDetail) GetGraph() WorkflowGraph`

GetGraph returns the Graph field if non-nil, zero value otherwise.

### GetGraphOk

`func (o *WorkflowDetail) GetGraphOk() (*WorkflowGraph, bool)`

GetGraphOk returns a tuple with the Graph field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGraph

`func (o *WorkflowDetail) SetGraph(v WorkflowGraph)`

SetGraph sets Graph field to given value.


### GetLiveVersion

`func (o *WorkflowDetail) GetLiveVersion() WorkflowVersion`

GetLiveVersion returns the LiveVersion field if non-nil, zero value otherwise.

### GetLiveVersionOk

`func (o *WorkflowDetail) GetLiveVersionOk() (*WorkflowVersion, bool)`

GetLiveVersionOk returns a tuple with the LiveVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLiveVersion

`func (o *WorkflowDetail) SetLiveVersion(v WorkflowVersion)`

SetLiveVersion sets LiveVersion field to given value.

### HasLiveVersion

`func (o *WorkflowDetail) HasLiveVersion() bool`

HasLiveVersion returns a boolean if a field has been set.

### SetLiveVersionNil

`func (o *WorkflowDetail) SetLiveVersionNil(b bool)`

 SetLiveVersionNil sets the value for LiveVersion to be an explicit nil

### UnsetLiveVersion
`func (o *WorkflowDetail) UnsetLiveVersion()`

UnsetLiveVersion ensures that no value is present for LiveVersion, not even an explicit nil
### GetEverPublished

`func (o *WorkflowDetail) GetEverPublished() bool`

GetEverPublished returns the EverPublished field if non-nil, zero value otherwise.

### GetEverPublishedOk

`func (o *WorkflowDetail) GetEverPublishedOk() (*bool, bool)`

GetEverPublishedOk returns a tuple with the EverPublished field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEverPublished

`func (o *WorkflowDetail) SetEverPublished(v bool)`

SetEverPublished sets EverPublished field to given value.


### GetLastEditedBy

`func (o *WorkflowDetail) GetLastEditedBy() WorkflowDetailAllOfLastEditedBy`

GetLastEditedBy returns the LastEditedBy field if non-nil, zero value otherwise.

### GetLastEditedByOk

`func (o *WorkflowDetail) GetLastEditedByOk() (*WorkflowDetailAllOfLastEditedBy, bool)`

GetLastEditedByOk returns a tuple with the LastEditedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastEditedBy

`func (o *WorkflowDetail) SetLastEditedBy(v WorkflowDetailAllOfLastEditedBy)`

SetLastEditedBy sets LastEditedBy field to given value.

### HasLastEditedBy

`func (o *WorkflowDetail) HasLastEditedBy() bool`

HasLastEditedBy returns a boolean if a field has been set.

### SetLastEditedByNil

`func (o *WorkflowDetail) SetLastEditedByNil(b bool)`

 SetLastEditedByNil sets the value for LastEditedBy to be an explicit nil

### UnsetLastEditedBy
`func (o *WorkflowDetail) UnsetLastEditedBy()`

UnsetLastEditedBy ensures that no value is present for LastEditedBy, not even an explicit nil
### GetLastEditedAt

`func (o *WorkflowDetail) GetLastEditedAt() time.Time`

GetLastEditedAt returns the LastEditedAt field if non-nil, zero value otherwise.

### GetLastEditedAtOk

`func (o *WorkflowDetail) GetLastEditedAtOk() (*time.Time, bool)`

GetLastEditedAtOk returns a tuple with the LastEditedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastEditedAt

`func (o *WorkflowDetail) SetLastEditedAt(v time.Time)`

SetLastEditedAt sets LastEditedAt field to given value.

### HasLastEditedAt

`func (o *WorkflowDetail) HasLastEditedAt() bool`

HasLastEditedAt returns a boolean if a field has been set.

### SetLastEditedAtNil

`func (o *WorkflowDetail) SetLastEditedAtNil(b bool)`

 SetLastEditedAtNil sets the value for LastEditedAt to be an explicit nil

### UnsetLastEditedAt
`func (o *WorkflowDetail) UnsetLastEditedAt()`

UnsetLastEditedAt ensures that no value is present for LastEditedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


