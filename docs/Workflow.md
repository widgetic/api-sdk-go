# Workflow

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

## Methods

### NewWorkflow

`func NewWorkflow(id string, name string, status WorkflowStatus, revision int32, unpublishedChanges bool, compositionIds []string, blockCount int32, timezone string, runsCount int32, createdAt time.Time, updatedAt time.Time, ) *Workflow`

NewWorkflow instantiates a new Workflow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowWithDefaults

`func NewWorkflowWithDefaults() *Workflow`

NewWorkflowWithDefaults instantiates a new Workflow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Workflow) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Workflow) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Workflow) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *Workflow) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Workflow) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Workflow) SetName(v string)`

SetName sets Name field to given value.


### GetManagedUserId

`func (o *Workflow) GetManagedUserId() string`

GetManagedUserId returns the ManagedUserId field if non-nil, zero value otherwise.

### GetManagedUserIdOk

`func (o *Workflow) GetManagedUserIdOk() (*string, bool)`

GetManagedUserIdOk returns a tuple with the ManagedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUserId

`func (o *Workflow) SetManagedUserId(v string)`

SetManagedUserId sets ManagedUserId field to given value.

### HasManagedUserId

`func (o *Workflow) HasManagedUserId() bool`

HasManagedUserId returns a boolean if a field has been set.

### SetManagedUserIdNil

`func (o *Workflow) SetManagedUserIdNil(b bool)`

 SetManagedUserIdNil sets the value for ManagedUserId to be an explicit nil

### UnsetManagedUserId
`func (o *Workflow) UnsetManagedUserId()`

UnsetManagedUserId ensures that no value is present for ManagedUserId, not even an explicit nil
### GetStatus

`func (o *Workflow) GetStatus() WorkflowStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Workflow) GetStatusOk() (*WorkflowStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Workflow) SetStatus(v WorkflowStatus)`

SetStatus sets Status field to given value.


### GetRevision

`func (o *Workflow) GetRevision() int32`

GetRevision returns the Revision field if non-nil, zero value otherwise.

### GetRevisionOk

`func (o *Workflow) GetRevisionOk() (*int32, bool)`

GetRevisionOk returns a tuple with the Revision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevision

`func (o *Workflow) SetRevision(v int32)`

SetRevision sets Revision field to given value.


### GetUnpublishedChanges

`func (o *Workflow) GetUnpublishedChanges() bool`

GetUnpublishedChanges returns the UnpublishedChanges field if non-nil, zero value otherwise.

### GetUnpublishedChangesOk

`func (o *Workflow) GetUnpublishedChangesOk() (*bool, bool)`

GetUnpublishedChangesOk returns a tuple with the UnpublishedChanges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnpublishedChanges

`func (o *Workflow) SetUnpublishedChanges(v bool)`

SetUnpublishedChanges sets UnpublishedChanges field to given value.


### GetCompositionIds

`func (o *Workflow) GetCompositionIds() []string`

GetCompositionIds returns the CompositionIds field if non-nil, zero value otherwise.

### GetCompositionIdsOk

`func (o *Workflow) GetCompositionIdsOk() (*[]string, bool)`

GetCompositionIdsOk returns a tuple with the CompositionIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompositionIds

`func (o *Workflow) SetCompositionIds(v []string)`

SetCompositionIds sets CompositionIds field to given value.


### GetBlockCount

`func (o *Workflow) GetBlockCount() int32`

GetBlockCount returns the BlockCount field if non-nil, zero value otherwise.

### GetBlockCountOk

`func (o *Workflow) GetBlockCountOk() (*int32, bool)`

GetBlockCountOk returns a tuple with the BlockCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlockCount

`func (o *Workflow) SetBlockCount(v int32)`

SetBlockCount sets BlockCount field to given value.


### GetTimezone

`func (o *Workflow) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *Workflow) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *Workflow) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.


### GetRunsCount

`func (o *Workflow) GetRunsCount() int32`

GetRunsCount returns the RunsCount field if non-nil, zero value otherwise.

### GetRunsCountOk

`func (o *Workflow) GetRunsCountOk() (*int32, bool)`

GetRunsCountOk returns a tuple with the RunsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunsCount

`func (o *Workflow) SetRunsCount(v int32)`

SetRunsCount sets RunsCount field to given value.


### GetLiveVersionId

`func (o *Workflow) GetLiveVersionId() string`

GetLiveVersionId returns the LiveVersionId field if non-nil, zero value otherwise.

### GetLiveVersionIdOk

`func (o *Workflow) GetLiveVersionIdOk() (*string, bool)`

GetLiveVersionIdOk returns a tuple with the LiveVersionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLiveVersionId

`func (o *Workflow) SetLiveVersionId(v string)`

SetLiveVersionId sets LiveVersionId field to given value.

### HasLiveVersionId

`func (o *Workflow) HasLiveVersionId() bool`

HasLiveVersionId returns a boolean if a field has been set.

### SetLiveVersionIdNil

`func (o *Workflow) SetLiveVersionIdNil(b bool)`

 SetLiveVersionIdNil sets the value for LiveVersionId to be an explicit nil

### UnsetLiveVersionId
`func (o *Workflow) UnsetLiveVersionId()`

UnsetLiveVersionId ensures that no value is present for LiveVersionId, not even an explicit nil
### GetCreatedAt

`func (o *Workflow) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Workflow) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Workflow) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *Workflow) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Workflow) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Workflow) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetFirstPublishedAt

`func (o *Workflow) GetFirstPublishedAt() time.Time`

GetFirstPublishedAt returns the FirstPublishedAt field if non-nil, zero value otherwise.

### GetFirstPublishedAtOk

`func (o *Workflow) GetFirstPublishedAtOk() (*time.Time, bool)`

GetFirstPublishedAtOk returns a tuple with the FirstPublishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstPublishedAt

`func (o *Workflow) SetFirstPublishedAt(v time.Time)`

SetFirstPublishedAt sets FirstPublishedAt field to given value.

### HasFirstPublishedAt

`func (o *Workflow) HasFirstPublishedAt() bool`

HasFirstPublishedAt returns a boolean if a field has been set.

### SetFirstPublishedAtNil

`func (o *Workflow) SetFirstPublishedAtNil(b bool)`

 SetFirstPublishedAtNil sets the value for FirstPublishedAt to be an explicit nil

### UnsetFirstPublishedAt
`func (o *Workflow) UnsetFirstPublishedAt()`

UnsetFirstPublishedAt ensures that no value is present for FirstPublishedAt, not even an explicit nil
### GetLastPublishedAt

`func (o *Workflow) GetLastPublishedAt() time.Time`

GetLastPublishedAt returns the LastPublishedAt field if non-nil, zero value otherwise.

### GetLastPublishedAtOk

`func (o *Workflow) GetLastPublishedAtOk() (*time.Time, bool)`

GetLastPublishedAtOk returns a tuple with the LastPublishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastPublishedAt

`func (o *Workflow) SetLastPublishedAt(v time.Time)`

SetLastPublishedAt sets LastPublishedAt field to given value.

### HasLastPublishedAt

`func (o *Workflow) HasLastPublishedAt() bool`

HasLastPublishedAt returns a boolean if a field has been set.

### SetLastPublishedAtNil

`func (o *Workflow) SetLastPublishedAtNil(b bool)`

 SetLastPublishedAtNil sets the value for LastPublishedAt to be an explicit nil

### UnsetLastPublishedAt
`func (o *Workflow) UnsetLastPublishedAt()`

UnsetLastPublishedAt ensures that no value is present for LastPublishedAt, not even an explicit nil
### GetPausedAt

`func (o *Workflow) GetPausedAt() time.Time`

GetPausedAt returns the PausedAt field if non-nil, zero value otherwise.

### GetPausedAtOk

`func (o *Workflow) GetPausedAtOk() (*time.Time, bool)`

GetPausedAtOk returns a tuple with the PausedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPausedAt

`func (o *Workflow) SetPausedAt(v time.Time)`

SetPausedAt sets PausedAt field to given value.

### HasPausedAt

`func (o *Workflow) HasPausedAt() bool`

HasPausedAt returns a boolean if a field has been set.

### SetPausedAtNil

`func (o *Workflow) SetPausedAtNil(b bool)`

 SetPausedAtNil sets the value for PausedAt to be an explicit nil

### UnsetPausedAt
`func (o *Workflow) UnsetPausedAt()`

UnsetPausedAt ensures that no value is present for PausedAt, not even an explicit nil
### GetArchivedAt

`func (o *Workflow) GetArchivedAt() time.Time`

GetArchivedAt returns the ArchivedAt field if non-nil, zero value otherwise.

### GetArchivedAtOk

`func (o *Workflow) GetArchivedAtOk() (*time.Time, bool)`

GetArchivedAtOk returns a tuple with the ArchivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchivedAt

`func (o *Workflow) SetArchivedAt(v time.Time)`

SetArchivedAt sets ArchivedAt field to given value.

### HasArchivedAt

`func (o *Workflow) HasArchivedAt() bool`

HasArchivedAt returns a boolean if a field has been set.

### SetArchivedAtNil

`func (o *Workflow) SetArchivedAtNil(b bool)`

 SetArchivedAtNil sets the value for ArchivedAt to be an explicit nil

### UnsetArchivedAt
`func (o *Workflow) UnsetArchivedAt()`

UnsetArchivedAt ensures that no value is present for ArchivedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


