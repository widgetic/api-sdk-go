# CreateWidgetRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Name of the widget. | 
**Type** | **string** | What kind of widget this is, as a label of your choosing (for example chart, form, gallery). | 
**Content** | **map[string]interface{}** | Starting content for the widget. An empty object is fine. | 
**IsPublic** | Pointer to **bool** | Whether the widget is public. | [optional] [default to false]
**IsDraft** | Pointer to **bool** | Whether the widget starts as a draft. A widget created without this is a draft. | [optional] [default to true]
**CanvasId** | Pointer to **string** | Put the widget on this existing canvas instead of a new one. You must own the canvas. | [optional] 
**ProjectId** | Pointer to **string** | Project to file the widget in. You must be able to edit the project. | [optional] 
**OrganizationId** | Pointer to **string** | Organization the widget belongs to. You must be a member who may create widgets there. | [optional] 
**WorkspaceType** | Pointer to **string** | Whether the widget lives in your personal workspace or in an organization&#39;s. | [optional] 
**ManagedUserId** | Pointer to **string** | Make the widget for one of your managed users, by Widgetic&#39;s id for the user. Send this or &#x60;managedUserExternalId&#x60;, not both. The managed user must be yours and active. The widget stays in your account; the tag lets you list one user&#39;s widgets and keeps it out of the others&#39; lists. It is set here and does not change afterwards. | [optional] 
**ManagedUserExternalId** | Pointer to **string** | The same, by your own identifier for the user, the &#x60;externalId&#x60; you gave when you created the managed user (answers show it as &#x60;externalId&#x60;). Send this or &#x60;managedUserId&#x60;, not both. | [optional] 

## Methods

### NewCreateWidgetRequest

`func NewCreateWidgetRequest(name string, type_ string, content map[string]interface{}, ) *CreateWidgetRequest`

NewCreateWidgetRequest instantiates a new CreateWidgetRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateWidgetRequestWithDefaults

`func NewCreateWidgetRequestWithDefaults() *CreateWidgetRequest`

NewCreateWidgetRequestWithDefaults instantiates a new CreateWidgetRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateWidgetRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateWidgetRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateWidgetRequest) SetName(v string)`

SetName sets Name field to given value.


### GetType

`func (o *CreateWidgetRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreateWidgetRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreateWidgetRequest) SetType(v string)`

SetType sets Type field to given value.


### GetContent

`func (o *CreateWidgetRequest) GetContent() map[string]interface{}`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *CreateWidgetRequest) GetContentOk() (*map[string]interface{}, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *CreateWidgetRequest) SetContent(v map[string]interface{})`

SetContent sets Content field to given value.


### GetIsPublic

`func (o *CreateWidgetRequest) GetIsPublic() bool`

GetIsPublic returns the IsPublic field if non-nil, zero value otherwise.

### GetIsPublicOk

`func (o *CreateWidgetRequest) GetIsPublicOk() (*bool, bool)`

GetIsPublicOk returns a tuple with the IsPublic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPublic

`func (o *CreateWidgetRequest) SetIsPublic(v bool)`

SetIsPublic sets IsPublic field to given value.

### HasIsPublic

`func (o *CreateWidgetRequest) HasIsPublic() bool`

HasIsPublic returns a boolean if a field has been set.

### GetIsDraft

`func (o *CreateWidgetRequest) GetIsDraft() bool`

GetIsDraft returns the IsDraft field if non-nil, zero value otherwise.

### GetIsDraftOk

`func (o *CreateWidgetRequest) GetIsDraftOk() (*bool, bool)`

GetIsDraftOk returns a tuple with the IsDraft field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDraft

`func (o *CreateWidgetRequest) SetIsDraft(v bool)`

SetIsDraft sets IsDraft field to given value.

### HasIsDraft

`func (o *CreateWidgetRequest) HasIsDraft() bool`

HasIsDraft returns a boolean if a field has been set.

### GetCanvasId

`func (o *CreateWidgetRequest) GetCanvasId() string`

GetCanvasId returns the CanvasId field if non-nil, zero value otherwise.

### GetCanvasIdOk

`func (o *CreateWidgetRequest) GetCanvasIdOk() (*string, bool)`

GetCanvasIdOk returns a tuple with the CanvasId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanvasId

`func (o *CreateWidgetRequest) SetCanvasId(v string)`

SetCanvasId sets CanvasId field to given value.

### HasCanvasId

`func (o *CreateWidgetRequest) HasCanvasId() bool`

HasCanvasId returns a boolean if a field has been set.

### GetProjectId

`func (o *CreateWidgetRequest) GetProjectId() string`

GetProjectId returns the ProjectId field if non-nil, zero value otherwise.

### GetProjectIdOk

`func (o *CreateWidgetRequest) GetProjectIdOk() (*string, bool)`

GetProjectIdOk returns a tuple with the ProjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectId

`func (o *CreateWidgetRequest) SetProjectId(v string)`

SetProjectId sets ProjectId field to given value.

### HasProjectId

`func (o *CreateWidgetRequest) HasProjectId() bool`

HasProjectId returns a boolean if a field has been set.

### GetOrganizationId

`func (o *CreateWidgetRequest) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *CreateWidgetRequest) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *CreateWidgetRequest) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.

### HasOrganizationId

`func (o *CreateWidgetRequest) HasOrganizationId() bool`

HasOrganizationId returns a boolean if a field has been set.

### GetWorkspaceType

`func (o *CreateWidgetRequest) GetWorkspaceType() string`

GetWorkspaceType returns the WorkspaceType field if non-nil, zero value otherwise.

### GetWorkspaceTypeOk

`func (o *CreateWidgetRequest) GetWorkspaceTypeOk() (*string, bool)`

GetWorkspaceTypeOk returns a tuple with the WorkspaceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkspaceType

`func (o *CreateWidgetRequest) SetWorkspaceType(v string)`

SetWorkspaceType sets WorkspaceType field to given value.

### HasWorkspaceType

`func (o *CreateWidgetRequest) HasWorkspaceType() bool`

HasWorkspaceType returns a boolean if a field has been set.

### GetManagedUserId

`func (o *CreateWidgetRequest) GetManagedUserId() string`

GetManagedUserId returns the ManagedUserId field if non-nil, zero value otherwise.

### GetManagedUserIdOk

`func (o *CreateWidgetRequest) GetManagedUserIdOk() (*string, bool)`

GetManagedUserIdOk returns a tuple with the ManagedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUserId

`func (o *CreateWidgetRequest) SetManagedUserId(v string)`

SetManagedUserId sets ManagedUserId field to given value.

### HasManagedUserId

`func (o *CreateWidgetRequest) HasManagedUserId() bool`

HasManagedUserId returns a boolean if a field has been set.

### GetManagedUserExternalId

`func (o *CreateWidgetRequest) GetManagedUserExternalId() string`

GetManagedUserExternalId returns the ManagedUserExternalId field if non-nil, zero value otherwise.

### GetManagedUserExternalIdOk

`func (o *CreateWidgetRequest) GetManagedUserExternalIdOk() (*string, bool)`

GetManagedUserExternalIdOk returns a tuple with the ManagedUserExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUserExternalId

`func (o *CreateWidgetRequest) SetManagedUserExternalId(v string)`

SetManagedUserExternalId sets ManagedUserExternalId field to given value.

### HasManagedUserExternalId

`func (o *CreateWidgetRequest) HasManagedUserExternalId() bool`

HasManagedUserExternalId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


