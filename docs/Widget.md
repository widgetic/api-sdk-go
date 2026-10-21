# Widget

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
**CpgSchemaId** | Pointer to **NullableString** | ID linking to the widget&#39;s code graph schema. | [optional] 
**LastCpgCommitSha** | Pointer to **NullableString** | Last Git commit SHA analyzed for code graph. | [optional] 
**OrganizationId** | Pointer to **NullableString** | Organization ID if created in an organization workspace. | [optional] 
**ProjectFolder** | Pointer to **NullableString** | Project folder reference for organization widgets. | [optional] 
**WorkspaceType** | Pointer to **NullableString** | Workspace type when created. | [optional] 
**ManagedUserId** | Pointer to **NullableString** | The managed user the widget was made for, or null when it is your own. List one managed user&#39;s widgets with the &#x60;managedUserId&#x60; or &#x60;managedUserExternalId&#x60; query parameter of &#x60;getWidgets&#x60;. | [optional] 

## Methods

### NewWidget

`func NewWidget() *Widget`

NewWidget instantiates a new Widget object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWidgetWithDefaults

`func NewWidgetWithDefaults() *Widget`

NewWidgetWithDefaults instantiates a new Widget object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Widget) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Widget) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Widget) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *Widget) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreatorId

`func (o *Widget) GetCreatorId() string`

GetCreatorId returns the CreatorId field if non-nil, zero value otherwise.

### GetCreatorIdOk

`func (o *Widget) GetCreatorIdOk() (*string, bool)`

GetCreatorIdOk returns a tuple with the CreatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatorId

`func (o *Widget) SetCreatorId(v string)`

SetCreatorId sets CreatorId field to given value.

### HasCreatorId

`func (o *Widget) HasCreatorId() bool`

HasCreatorId returns a boolean if a field has been set.

### GetName

`func (o *Widget) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Widget) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Widget) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *Widget) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *Widget) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Widget) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Widget) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *Widget) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *Widget) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *Widget) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetType

`func (o *Widget) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Widget) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Widget) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *Widget) HasType() bool`

HasType returns a boolean if a field has been set.

### GetContent

`func (o *Widget) GetContent() map[string]interface{}`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *Widget) GetContentOk() (*map[string]interface{}, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *Widget) SetContent(v map[string]interface{})`

SetContent sets Content field to given value.

### HasContent

`func (o *Widget) HasContent() bool`

HasContent returns a boolean if a field has been set.

### GetIsPublic

`func (o *Widget) GetIsPublic() bool`

GetIsPublic returns the IsPublic field if non-nil, zero value otherwise.

### GetIsPublicOk

`func (o *Widget) GetIsPublicOk() (*bool, bool)`

GetIsPublicOk returns a tuple with the IsPublic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPublic

`func (o *Widget) SetIsPublic(v bool)`

SetIsPublic sets IsPublic field to given value.

### HasIsPublic

`func (o *Widget) HasIsPublic() bool`

HasIsPublic returns a boolean if a field has been set.

### GetIsDraft

`func (o *Widget) GetIsDraft() bool`

GetIsDraft returns the IsDraft field if non-nil, zero value otherwise.

### GetIsDraftOk

`func (o *Widget) GetIsDraftOk() (*bool, bool)`

GetIsDraftOk returns a tuple with the IsDraft field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDraft

`func (o *Widget) SetIsDraft(v bool)`

SetIsDraft sets IsDraft field to given value.

### HasIsDraft

`func (o *Widget) HasIsDraft() bool`

HasIsDraft returns a boolean if a field has been set.

### GetShareId

`func (o *Widget) GetShareId() string`

GetShareId returns the ShareId field if non-nil, zero value otherwise.

### GetShareIdOk

`func (o *Widget) GetShareIdOk() (*string, bool)`

GetShareIdOk returns a tuple with the ShareId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShareId

`func (o *Widget) SetShareId(v string)`

SetShareId sets ShareId field to given value.

### HasShareId

`func (o *Widget) HasShareId() bool`

HasShareId returns a boolean if a field has been set.

### SetShareIdNil

`func (o *Widget) SetShareIdNil(b bool)`

 SetShareIdNil sets the value for ShareId to be an explicit nil

### UnsetShareId
`func (o *Widget) UnsetShareId()`

UnsetShareId ensures that no value is present for ShareId, not even an explicit nil
### GetCreatedAt

`func (o *Widget) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Widget) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Widget) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Widget) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *Widget) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Widget) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Widget) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Widget) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetJsPath

`func (o *Widget) GetJsPath() string`

GetJsPath returns the JsPath field if non-nil, zero value otherwise.

### GetJsPathOk

`func (o *Widget) GetJsPathOk() (*string, bool)`

GetJsPathOk returns a tuple with the JsPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJsPath

`func (o *Widget) SetJsPath(v string)`

SetJsPath sets JsPath field to given value.

### HasJsPath

`func (o *Widget) HasJsPath() bool`

HasJsPath returns a boolean if a field has been set.

### SetJsPathNil

`func (o *Widget) SetJsPathNil(b bool)`

 SetJsPathNil sets the value for JsPath to be an explicit nil

### UnsetJsPath
`func (o *Widget) UnsetJsPath()`

UnsetJsPath ensures that no value is present for JsPath, not even an explicit nil
### GetCanvasId

`func (o *Widget) GetCanvasId() string`

GetCanvasId returns the CanvasId field if non-nil, zero value otherwise.

### GetCanvasIdOk

`func (o *Widget) GetCanvasIdOk() (*string, bool)`

GetCanvasIdOk returns a tuple with the CanvasId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanvasId

`func (o *Widget) SetCanvasId(v string)`

SetCanvasId sets CanvasId field to given value.

### HasCanvasId

`func (o *Widget) HasCanvasId() bool`

HasCanvasId returns a boolean if a field has been set.

### SetCanvasIdNil

`func (o *Widget) SetCanvasIdNil(b bool)`

 SetCanvasIdNil sets the value for CanvasId to be an explicit nil

### UnsetCanvasId
`func (o *Widget) UnsetCanvasId()`

UnsetCanvasId ensures that no value is present for CanvasId, not even an explicit nil
### GetRepoId

`func (o *Widget) GetRepoId() string`

GetRepoId returns the RepoId field if non-nil, zero value otherwise.

### GetRepoIdOk

`func (o *Widget) GetRepoIdOk() (*string, bool)`

GetRepoIdOk returns a tuple with the RepoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepoId

`func (o *Widget) SetRepoId(v string)`

SetRepoId sets RepoId field to given value.

### HasRepoId

`func (o *Widget) HasRepoId() bool`

HasRepoId returns a boolean if a field has been set.

### SetRepoIdNil

`func (o *Widget) SetRepoIdNil(b bool)`

 SetRepoIdNil sets the value for RepoId to be an explicit nil

### UnsetRepoId
`func (o *Widget) UnsetRepoId()`

UnsetRepoId ensures that no value is present for RepoId, not even an explicit nil
### GetDatabaseId

`func (o *Widget) GetDatabaseId() string`

GetDatabaseId returns the DatabaseId field if non-nil, zero value otherwise.

### GetDatabaseIdOk

`func (o *Widget) GetDatabaseIdOk() (*string, bool)`

GetDatabaseIdOk returns a tuple with the DatabaseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatabaseId

`func (o *Widget) SetDatabaseId(v string)`

SetDatabaseId sets DatabaseId field to given value.

### HasDatabaseId

`func (o *Widget) HasDatabaseId() bool`

HasDatabaseId returns a boolean if a field has been set.

### SetDatabaseIdNil

`func (o *Widget) SetDatabaseIdNil(b bool)`

 SetDatabaseIdNil sets the value for DatabaseId to be an explicit nil

### UnsetDatabaseId
`func (o *Widget) UnsetDatabaseId()`

UnsetDatabaseId ensures that no value is present for DatabaseId, not even an explicit nil
### GetVersion

`func (o *Widget) GetVersion() float32`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *Widget) GetVersionOk() (*float32, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *Widget) SetVersion(v float32)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *Widget) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### SetVersionNil

`func (o *Widget) SetVersionNil(b bool)`

 SetVersionNil sets the value for Version to be an explicit nil

### UnsetVersion
`func (o *Widget) UnsetVersion()`

UnsetVersion ensures that no value is present for Version, not even an explicit nil
### GetCpgSchemaId

`func (o *Widget) GetCpgSchemaId() string`

GetCpgSchemaId returns the CpgSchemaId field if non-nil, zero value otherwise.

### GetCpgSchemaIdOk

`func (o *Widget) GetCpgSchemaIdOk() (*string, bool)`

GetCpgSchemaIdOk returns a tuple with the CpgSchemaId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpgSchemaId

`func (o *Widget) SetCpgSchemaId(v string)`

SetCpgSchemaId sets CpgSchemaId field to given value.

### HasCpgSchemaId

`func (o *Widget) HasCpgSchemaId() bool`

HasCpgSchemaId returns a boolean if a field has been set.

### SetCpgSchemaIdNil

`func (o *Widget) SetCpgSchemaIdNil(b bool)`

 SetCpgSchemaIdNil sets the value for CpgSchemaId to be an explicit nil

### UnsetCpgSchemaId
`func (o *Widget) UnsetCpgSchemaId()`

UnsetCpgSchemaId ensures that no value is present for CpgSchemaId, not even an explicit nil
### GetLastCpgCommitSha

`func (o *Widget) GetLastCpgCommitSha() string`

GetLastCpgCommitSha returns the LastCpgCommitSha field if non-nil, zero value otherwise.

### GetLastCpgCommitShaOk

`func (o *Widget) GetLastCpgCommitShaOk() (*string, bool)`

GetLastCpgCommitShaOk returns a tuple with the LastCpgCommitSha field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastCpgCommitSha

`func (o *Widget) SetLastCpgCommitSha(v string)`

SetLastCpgCommitSha sets LastCpgCommitSha field to given value.

### HasLastCpgCommitSha

`func (o *Widget) HasLastCpgCommitSha() bool`

HasLastCpgCommitSha returns a boolean if a field has been set.

### SetLastCpgCommitShaNil

`func (o *Widget) SetLastCpgCommitShaNil(b bool)`

 SetLastCpgCommitShaNil sets the value for LastCpgCommitSha to be an explicit nil

### UnsetLastCpgCommitSha
`func (o *Widget) UnsetLastCpgCommitSha()`

UnsetLastCpgCommitSha ensures that no value is present for LastCpgCommitSha, not even an explicit nil
### GetOrganizationId

`func (o *Widget) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *Widget) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *Widget) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.

### HasOrganizationId

`func (o *Widget) HasOrganizationId() bool`

HasOrganizationId returns a boolean if a field has been set.

### SetOrganizationIdNil

`func (o *Widget) SetOrganizationIdNil(b bool)`

 SetOrganizationIdNil sets the value for OrganizationId to be an explicit nil

### UnsetOrganizationId
`func (o *Widget) UnsetOrganizationId()`

UnsetOrganizationId ensures that no value is present for OrganizationId, not even an explicit nil
### GetProjectFolder

`func (o *Widget) GetProjectFolder() string`

GetProjectFolder returns the ProjectFolder field if non-nil, zero value otherwise.

### GetProjectFolderOk

`func (o *Widget) GetProjectFolderOk() (*string, bool)`

GetProjectFolderOk returns a tuple with the ProjectFolder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectFolder

`func (o *Widget) SetProjectFolder(v string)`

SetProjectFolder sets ProjectFolder field to given value.

### HasProjectFolder

`func (o *Widget) HasProjectFolder() bool`

HasProjectFolder returns a boolean if a field has been set.

### SetProjectFolderNil

`func (o *Widget) SetProjectFolderNil(b bool)`

 SetProjectFolderNil sets the value for ProjectFolder to be an explicit nil

### UnsetProjectFolder
`func (o *Widget) UnsetProjectFolder()`

UnsetProjectFolder ensures that no value is present for ProjectFolder, not even an explicit nil
### GetWorkspaceType

`func (o *Widget) GetWorkspaceType() string`

GetWorkspaceType returns the WorkspaceType field if non-nil, zero value otherwise.

### GetWorkspaceTypeOk

`func (o *Widget) GetWorkspaceTypeOk() (*string, bool)`

GetWorkspaceTypeOk returns a tuple with the WorkspaceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkspaceType

`func (o *Widget) SetWorkspaceType(v string)`

SetWorkspaceType sets WorkspaceType field to given value.

### HasWorkspaceType

`func (o *Widget) HasWorkspaceType() bool`

HasWorkspaceType returns a boolean if a field has been set.

### SetWorkspaceTypeNil

`func (o *Widget) SetWorkspaceTypeNil(b bool)`

 SetWorkspaceTypeNil sets the value for WorkspaceType to be an explicit nil

### UnsetWorkspaceType
`func (o *Widget) UnsetWorkspaceType()`

UnsetWorkspaceType ensures that no value is present for WorkspaceType, not even an explicit nil
### GetManagedUserId

`func (o *Widget) GetManagedUserId() string`

GetManagedUserId returns the ManagedUserId field if non-nil, zero value otherwise.

### GetManagedUserIdOk

`func (o *Widget) GetManagedUserIdOk() (*string, bool)`

GetManagedUserIdOk returns a tuple with the ManagedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUserId

`func (o *Widget) SetManagedUserId(v string)`

SetManagedUserId sets ManagedUserId field to given value.

### HasManagedUserId

`func (o *Widget) HasManagedUserId() bool`

HasManagedUserId returns a boolean if a field has been set.

### SetManagedUserIdNil

`func (o *Widget) SetManagedUserIdNil(b bool)`

 SetManagedUserIdNil sets the value for ManagedUserId to be an explicit nil

### UnsetManagedUserId
`func (o *Widget) UnsetManagedUserId()`

UnsetManagedUserId ensures that no value is present for ManagedUserId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


