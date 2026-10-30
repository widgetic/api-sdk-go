# CreateWidget201ResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Unique identifier for the widget. | [optional] 
**CreatorId** | Pointer to **string** | ID of the user who created the widget. | [optional] 
**Name** | Pointer to **string** | Name of the widget. | [optional] 
**Description** | Pointer to **NullableString** | Description of the widget&#39;s purpose and functionality. | [optional] 
**Type** | Pointer to **string** | Type of widget (e.g., chart, form, gallery). | [optional] 
**Content** | Pointer to **map[string]interface{}** | Content configuration for the widget. | [optional] 
**IsPublic** | Pointer to **bool** | Whether the widget is publicly available. | [optional] 
**IsDraft** | Pointer to **bool** | Whether the widget is a draft. | [optional] 
**ShareId** | Pointer to **NullableString** | Unique ID for sharing the widget publicly. | [optional] 
**CreatedAt** | Pointer to **time.Time** | When the widget was created. | [optional] 
**UpdatedAt** | Pointer to **time.Time** | When the widget was last updated. | [optional] 
**JsPath** | Pointer to **NullableString** | Path to the JavaScript file for this widget. | [optional] 
**CanvasId** | Pointer to **NullableString** | ID of the canvas associated with this widget. | [optional] 
**RepoId** | Pointer to **NullableString** | Repository identifier for source code. | [optional] 
**DatabaseId** | Pointer to **NullableString** | Legacy. The name of a Neon database that an earlier version made for this widget. A widget has no database now (what the visitors of a composition leave is kept in the tables of that composition), so widgets made now have none. | [optional] 
**Version** | Pointer to **NullableFloat32** | Version number of the widget. | [optional] 
**LastCommitSha** | Pointer to **NullableString** | Latest Git commit SHA of the widget&#39;s code repository. | [optional] 
**OrganizationId** | Pointer to **NullableString** | Organization ID if created in an organization workspace. | [optional] 
**ProjectFolder** | Pointer to **NullableString** | Project folder reference for organization widgets. | [optional] 
**WorkspaceType** | Pointer to **NullableString** | Workspace type when created. | [optional] 
**ManagedUserId** | Pointer to **NullableString** | The managed user the widget was made for, or null when it is your own. List one managed user&#39;s widgets with the &#x60;managedUserId&#x60; or &#x60;managedUserExternalId&#x60; query parameter of &#x60;getWidgets&#x60;. | [optional] 
**Warnings** | Pointer to **[]string** | What did not go through, when the widget was created without all of its parts (for example, the canvas it sits on could not be told that this is its main widget). Absent when everything did. | [optional] 

## Methods

### NewCreateWidget201ResponseData

`func NewCreateWidget201ResponseData() *CreateWidget201ResponseData`

NewCreateWidget201ResponseData instantiates a new CreateWidget201ResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateWidget201ResponseDataWithDefaults

`func NewCreateWidget201ResponseDataWithDefaults() *CreateWidget201ResponseData`

NewCreateWidget201ResponseDataWithDefaults instantiates a new CreateWidget201ResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateWidget201ResponseData) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateWidget201ResponseData) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateWidget201ResponseData) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CreateWidget201ResponseData) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreatorId

`func (o *CreateWidget201ResponseData) GetCreatorId() string`

GetCreatorId returns the CreatorId field if non-nil, zero value otherwise.

### GetCreatorIdOk

`func (o *CreateWidget201ResponseData) GetCreatorIdOk() (*string, bool)`

GetCreatorIdOk returns a tuple with the CreatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatorId

`func (o *CreateWidget201ResponseData) SetCreatorId(v string)`

SetCreatorId sets CreatorId field to given value.

### HasCreatorId

`func (o *CreateWidget201ResponseData) HasCreatorId() bool`

HasCreatorId returns a boolean if a field has been set.

### GetName

`func (o *CreateWidget201ResponseData) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateWidget201ResponseData) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateWidget201ResponseData) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CreateWidget201ResponseData) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *CreateWidget201ResponseData) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateWidget201ResponseData) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateWidget201ResponseData) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateWidget201ResponseData) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *CreateWidget201ResponseData) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *CreateWidget201ResponseData) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetType

`func (o *CreateWidget201ResponseData) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreateWidget201ResponseData) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreateWidget201ResponseData) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *CreateWidget201ResponseData) HasType() bool`

HasType returns a boolean if a field has been set.

### GetContent

`func (o *CreateWidget201ResponseData) GetContent() map[string]interface{}`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *CreateWidget201ResponseData) GetContentOk() (*map[string]interface{}, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *CreateWidget201ResponseData) SetContent(v map[string]interface{})`

SetContent sets Content field to given value.

### HasContent

`func (o *CreateWidget201ResponseData) HasContent() bool`

HasContent returns a boolean if a field has been set.

### GetIsPublic

`func (o *CreateWidget201ResponseData) GetIsPublic() bool`

GetIsPublic returns the IsPublic field if non-nil, zero value otherwise.

### GetIsPublicOk

`func (o *CreateWidget201ResponseData) GetIsPublicOk() (*bool, bool)`

GetIsPublicOk returns a tuple with the IsPublic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPublic

`func (o *CreateWidget201ResponseData) SetIsPublic(v bool)`

SetIsPublic sets IsPublic field to given value.

### HasIsPublic

`func (o *CreateWidget201ResponseData) HasIsPublic() bool`

HasIsPublic returns a boolean if a field has been set.

### GetIsDraft

`func (o *CreateWidget201ResponseData) GetIsDraft() bool`

GetIsDraft returns the IsDraft field if non-nil, zero value otherwise.

### GetIsDraftOk

`func (o *CreateWidget201ResponseData) GetIsDraftOk() (*bool, bool)`

GetIsDraftOk returns a tuple with the IsDraft field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDraft

`func (o *CreateWidget201ResponseData) SetIsDraft(v bool)`

SetIsDraft sets IsDraft field to given value.

### HasIsDraft

`func (o *CreateWidget201ResponseData) HasIsDraft() bool`

HasIsDraft returns a boolean if a field has been set.

### GetShareId

`func (o *CreateWidget201ResponseData) GetShareId() string`

GetShareId returns the ShareId field if non-nil, zero value otherwise.

### GetShareIdOk

`func (o *CreateWidget201ResponseData) GetShareIdOk() (*string, bool)`

GetShareIdOk returns a tuple with the ShareId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShareId

`func (o *CreateWidget201ResponseData) SetShareId(v string)`

SetShareId sets ShareId field to given value.

### HasShareId

`func (o *CreateWidget201ResponseData) HasShareId() bool`

HasShareId returns a boolean if a field has been set.

### SetShareIdNil

`func (o *CreateWidget201ResponseData) SetShareIdNil(b bool)`

 SetShareIdNil sets the value for ShareId to be an explicit nil

### UnsetShareId
`func (o *CreateWidget201ResponseData) UnsetShareId()`

UnsetShareId ensures that no value is present for ShareId, not even an explicit nil
### GetCreatedAt

`func (o *CreateWidget201ResponseData) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CreateWidget201ResponseData) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CreateWidget201ResponseData) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *CreateWidget201ResponseData) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *CreateWidget201ResponseData) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CreateWidget201ResponseData) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CreateWidget201ResponseData) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *CreateWidget201ResponseData) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetJsPath

`func (o *CreateWidget201ResponseData) GetJsPath() string`

GetJsPath returns the JsPath field if non-nil, zero value otherwise.

### GetJsPathOk

`func (o *CreateWidget201ResponseData) GetJsPathOk() (*string, bool)`

GetJsPathOk returns a tuple with the JsPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJsPath

`func (o *CreateWidget201ResponseData) SetJsPath(v string)`

SetJsPath sets JsPath field to given value.

### HasJsPath

`func (o *CreateWidget201ResponseData) HasJsPath() bool`

HasJsPath returns a boolean if a field has been set.

### SetJsPathNil

`func (o *CreateWidget201ResponseData) SetJsPathNil(b bool)`

 SetJsPathNil sets the value for JsPath to be an explicit nil

### UnsetJsPath
`func (o *CreateWidget201ResponseData) UnsetJsPath()`

UnsetJsPath ensures that no value is present for JsPath, not even an explicit nil
### GetCanvasId

`func (o *CreateWidget201ResponseData) GetCanvasId() string`

GetCanvasId returns the CanvasId field if non-nil, zero value otherwise.

### GetCanvasIdOk

`func (o *CreateWidget201ResponseData) GetCanvasIdOk() (*string, bool)`

GetCanvasIdOk returns a tuple with the CanvasId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanvasId

`func (o *CreateWidget201ResponseData) SetCanvasId(v string)`

SetCanvasId sets CanvasId field to given value.

### HasCanvasId

`func (o *CreateWidget201ResponseData) HasCanvasId() bool`

HasCanvasId returns a boolean if a field has been set.

### SetCanvasIdNil

`func (o *CreateWidget201ResponseData) SetCanvasIdNil(b bool)`

 SetCanvasIdNil sets the value for CanvasId to be an explicit nil

### UnsetCanvasId
`func (o *CreateWidget201ResponseData) UnsetCanvasId()`

UnsetCanvasId ensures that no value is present for CanvasId, not even an explicit nil
### GetRepoId

`func (o *CreateWidget201ResponseData) GetRepoId() string`

GetRepoId returns the RepoId field if non-nil, zero value otherwise.

### GetRepoIdOk

`func (o *CreateWidget201ResponseData) GetRepoIdOk() (*string, bool)`

GetRepoIdOk returns a tuple with the RepoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepoId

`func (o *CreateWidget201ResponseData) SetRepoId(v string)`

SetRepoId sets RepoId field to given value.

### HasRepoId

`func (o *CreateWidget201ResponseData) HasRepoId() bool`

HasRepoId returns a boolean if a field has been set.

### SetRepoIdNil

`func (o *CreateWidget201ResponseData) SetRepoIdNil(b bool)`

 SetRepoIdNil sets the value for RepoId to be an explicit nil

### UnsetRepoId
`func (o *CreateWidget201ResponseData) UnsetRepoId()`

UnsetRepoId ensures that no value is present for RepoId, not even an explicit nil
### GetDatabaseId

`func (o *CreateWidget201ResponseData) GetDatabaseId() string`

GetDatabaseId returns the DatabaseId field if non-nil, zero value otherwise.

### GetDatabaseIdOk

`func (o *CreateWidget201ResponseData) GetDatabaseIdOk() (*string, bool)`

GetDatabaseIdOk returns a tuple with the DatabaseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatabaseId

`func (o *CreateWidget201ResponseData) SetDatabaseId(v string)`

SetDatabaseId sets DatabaseId field to given value.

### HasDatabaseId

`func (o *CreateWidget201ResponseData) HasDatabaseId() bool`

HasDatabaseId returns a boolean if a field has been set.

### SetDatabaseIdNil

`func (o *CreateWidget201ResponseData) SetDatabaseIdNil(b bool)`

 SetDatabaseIdNil sets the value for DatabaseId to be an explicit nil

### UnsetDatabaseId
`func (o *CreateWidget201ResponseData) UnsetDatabaseId()`

UnsetDatabaseId ensures that no value is present for DatabaseId, not even an explicit nil
### GetVersion

`func (o *CreateWidget201ResponseData) GetVersion() float32`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *CreateWidget201ResponseData) GetVersionOk() (*float32, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *CreateWidget201ResponseData) SetVersion(v float32)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *CreateWidget201ResponseData) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### SetVersionNil

`func (o *CreateWidget201ResponseData) SetVersionNil(b bool)`

 SetVersionNil sets the value for Version to be an explicit nil

### UnsetVersion
`func (o *CreateWidget201ResponseData) UnsetVersion()`

UnsetVersion ensures that no value is present for Version, not even an explicit nil
### GetLastCommitSha

`func (o *CreateWidget201ResponseData) GetLastCommitSha() string`

GetLastCommitSha returns the LastCommitSha field if non-nil, zero value otherwise.

### GetLastCommitShaOk

`func (o *CreateWidget201ResponseData) GetLastCommitShaOk() (*string, bool)`

GetLastCommitShaOk returns a tuple with the LastCommitSha field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastCommitSha

`func (o *CreateWidget201ResponseData) SetLastCommitSha(v string)`

SetLastCommitSha sets LastCommitSha field to given value.

### HasLastCommitSha

`func (o *CreateWidget201ResponseData) HasLastCommitSha() bool`

HasLastCommitSha returns a boolean if a field has been set.

### SetLastCommitShaNil

`func (o *CreateWidget201ResponseData) SetLastCommitShaNil(b bool)`

 SetLastCommitShaNil sets the value for LastCommitSha to be an explicit nil

### UnsetLastCommitSha
`func (o *CreateWidget201ResponseData) UnsetLastCommitSha()`

UnsetLastCommitSha ensures that no value is present for LastCommitSha, not even an explicit nil
### GetOrganizationId

`func (o *CreateWidget201ResponseData) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *CreateWidget201ResponseData) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *CreateWidget201ResponseData) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.

### HasOrganizationId

`func (o *CreateWidget201ResponseData) HasOrganizationId() bool`

HasOrganizationId returns a boolean if a field has been set.

### SetOrganizationIdNil

`func (o *CreateWidget201ResponseData) SetOrganizationIdNil(b bool)`

 SetOrganizationIdNil sets the value for OrganizationId to be an explicit nil

### UnsetOrganizationId
`func (o *CreateWidget201ResponseData) UnsetOrganizationId()`

UnsetOrganizationId ensures that no value is present for OrganizationId, not even an explicit nil
### GetProjectFolder

`func (o *CreateWidget201ResponseData) GetProjectFolder() string`

GetProjectFolder returns the ProjectFolder field if non-nil, zero value otherwise.

### GetProjectFolderOk

`func (o *CreateWidget201ResponseData) GetProjectFolderOk() (*string, bool)`

GetProjectFolderOk returns a tuple with the ProjectFolder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectFolder

`func (o *CreateWidget201ResponseData) SetProjectFolder(v string)`

SetProjectFolder sets ProjectFolder field to given value.

### HasProjectFolder

`func (o *CreateWidget201ResponseData) HasProjectFolder() bool`

HasProjectFolder returns a boolean if a field has been set.

### SetProjectFolderNil

`func (o *CreateWidget201ResponseData) SetProjectFolderNil(b bool)`

 SetProjectFolderNil sets the value for ProjectFolder to be an explicit nil

### UnsetProjectFolder
`func (o *CreateWidget201ResponseData) UnsetProjectFolder()`

UnsetProjectFolder ensures that no value is present for ProjectFolder, not even an explicit nil
### GetWorkspaceType

`func (o *CreateWidget201ResponseData) GetWorkspaceType() string`

GetWorkspaceType returns the WorkspaceType field if non-nil, zero value otherwise.

### GetWorkspaceTypeOk

`func (o *CreateWidget201ResponseData) GetWorkspaceTypeOk() (*string, bool)`

GetWorkspaceTypeOk returns a tuple with the WorkspaceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkspaceType

`func (o *CreateWidget201ResponseData) SetWorkspaceType(v string)`

SetWorkspaceType sets WorkspaceType field to given value.

### HasWorkspaceType

`func (o *CreateWidget201ResponseData) HasWorkspaceType() bool`

HasWorkspaceType returns a boolean if a field has been set.

### SetWorkspaceTypeNil

`func (o *CreateWidget201ResponseData) SetWorkspaceTypeNil(b bool)`

 SetWorkspaceTypeNil sets the value for WorkspaceType to be an explicit nil

### UnsetWorkspaceType
`func (o *CreateWidget201ResponseData) UnsetWorkspaceType()`

UnsetWorkspaceType ensures that no value is present for WorkspaceType, not even an explicit nil
### GetManagedUserId

`func (o *CreateWidget201ResponseData) GetManagedUserId() string`

GetManagedUserId returns the ManagedUserId field if non-nil, zero value otherwise.

### GetManagedUserIdOk

`func (o *CreateWidget201ResponseData) GetManagedUserIdOk() (*string, bool)`

GetManagedUserIdOk returns a tuple with the ManagedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUserId

`func (o *CreateWidget201ResponseData) SetManagedUserId(v string)`

SetManagedUserId sets ManagedUserId field to given value.

### HasManagedUserId

`func (o *CreateWidget201ResponseData) HasManagedUserId() bool`

HasManagedUserId returns a boolean if a field has been set.

### SetManagedUserIdNil

`func (o *CreateWidget201ResponseData) SetManagedUserIdNil(b bool)`

 SetManagedUserIdNil sets the value for ManagedUserId to be an explicit nil

### UnsetManagedUserId
`func (o *CreateWidget201ResponseData) UnsetManagedUserId()`

UnsetManagedUserId ensures that no value is present for ManagedUserId, not even an explicit nil
### GetWarnings

`func (o *CreateWidget201ResponseData) GetWarnings() []string`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *CreateWidget201ResponseData) GetWarningsOk() (*[]string, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *CreateWidget201ResponseData) SetWarnings(v []string)`

SetWarnings sets Warnings field to given value.

### HasWarnings

`func (o *CreateWidget201ResponseData) HasWarnings() bool`

HasWarnings returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


