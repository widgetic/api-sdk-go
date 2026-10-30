# \WorkspacesAPI

All URIs are relative to *https://api.widgetic.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ArchiveWorkspaceWorkflow_1**](WorkspacesAPI.md#ArchiveWorkspaceWorkflow_1) | **Post** /workspaces/{workspaceId}/workflows/{workflowId}/archive | Archive a Workflow
[**CreateWorkspaceWorkflowFromPreset_1**](WorkspacesAPI.md#CreateWorkspaceWorkflowFromPreset_1) | **Post** /workspaces/{workspaceId}/workflows/from-preset | Start a Workflow from a starting point
[**CreateWorkspaceWorkflow_1**](WorkspacesAPI.md#CreateWorkspaceWorkflow_1) | **Post** /workspaces/{workspaceId}/workflows | Create a Workflow
[**DeleteWorkspaceWorkflow_1**](WorkspacesAPI.md#DeleteWorkspaceWorkflow_1) | **Delete** /workspaces/{workspaceId}/workflows/{workflowId} | Delete a Workflow
[**DiscardWorkspaceWorkflowChanges_1**](WorkspacesAPI.md#DiscardWorkspaceWorkflowChanges_1) | **Post** /workspaces/{workspaceId}/workflows/{workflowId}/discard | Discard the Unpublished Changes of a Workflow
[**DuplicateWorkspaceWorkflow_1**](WorkspacesAPI.md#DuplicateWorkspaceWorkflow_1) | **Post** /workspaces/{workspaceId}/workflows/{workflowId}/duplicate | Duplicate a Workflow
[**GetWorkspaceWorkflowStats_1**](WorkspacesAPI.md#GetWorkspaceWorkflowStats_1) | **Get** /workspaces/{workspaceId}/workflows/{workflowId}/stats | Get what Visitors Did in a Workflow
[**GetWorkspaceWorkflowVersion_1**](WorkspacesAPI.md#GetWorkspaceWorkflowVersion_1) | **Get** /workspaces/{workspaceId}/workflows/{workflowId}/versions/{versionId} | Get a Published Version of a Workflow
[**GetWorkspaceWorkflow_1**](WorkspacesAPI.md#GetWorkspaceWorkflow_1) | **Get** /workspaces/{workspaceId}/workflows/{workflowId} | Get a Workflow
[**ListWorkspaceWorkflowCompositionOptions_1**](WorkspacesAPI.md#ListWorkspaceWorkflowCompositionOptions_1) | **Get** /workspaces/{workspaceId}/workflows/composition-options | List the compositions a workflow can show, and what each can do
[**ListWorkspaceWorkflowPresets_1**](WorkspacesAPI.md#ListWorkspaceWorkflowPresets_1) | **Get** /workspaces/{workspaceId}/workflows/presets | List the starting points for a new Workflow
[**ListWorkspaceWorkflowVersions_1**](WorkspacesAPI.md#ListWorkspaceWorkflowVersions_1) | **Get** /workspaces/{workspaceId}/workflows/{workflowId}/versions | List the Published Versions of a Workflow
[**ListWorkspaceWorkflows_1**](WorkspacesAPI.md#ListWorkspaceWorkflows_1) | **Get** /workspaces/{workspaceId}/workflows | List the Workflows of a Workspace
[**PauseWorkspaceWorkflow_1**](WorkspacesAPI.md#PauseWorkspaceWorkflow_1) | **Post** /workspaces/{workspaceId}/workflows/{workflowId}/pause | Pause a Workflow
[**PublishWorkspaceWorkflow_1**](WorkspacesAPI.md#PublishWorkspaceWorkflow_1) | **Post** /workspaces/{workspaceId}/workflows/{workflowId}/publish | Publish the Draft of a Workflow
[**RestoreWorkspaceWorkflowVersion_1**](WorkspacesAPI.md#RestoreWorkspaceWorkflowVersion_1) | **Post** /workspaces/{workspaceId}/workflows/{workflowId}/versions/{versionId}/restore | Restore a Version of a Workflow into the Draft
[**ResumeWorkspaceWorkflow_1**](WorkspacesAPI.md#ResumeWorkspaceWorkflow_1) | **Post** /workspaces/{workspaceId}/workflows/{workflowId}/resume | Resume a Paused Workflow
[**SaveWorkspaceWorkflow_1**](WorkspacesAPI.md#SaveWorkspaceWorkflow_1) | **Put** /workspaces/{workspaceId}/workflows/{workflowId} | Save the Draft of a Workflow
[**UnarchiveWorkspaceWorkflow_1**](WorkspacesAPI.md#UnarchiveWorkspaceWorkflow_1) | **Post** /workspaces/{workspaceId}/workflows/{workflowId}/unarchive | Unarchive a Workflow



## ArchiveWorkspaceWorkflow_1

> SaveWorkspaceWorkflow200Response ArchiveWorkspaceWorkflow_1(ctx, workspaceId, workflowId).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Archive a Workflow



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/widgetic/api-sdk-go"
)

func main() {
	workspaceId := "personal" // string | The workspace: 'personal' for your own workspace, or the UUID of an organization. A call made for one of your managed users (`X-Managed-User-Id`) always uses 'personal': a managed user has no other workspace, and a call that names an organization is refused with 403. 
	workflowId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The workflow's id
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.ArchiveWorkspaceWorkflow_1(context.Background(), workspaceId, workflowId).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.ArchiveWorkspaceWorkflow_1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ArchiveWorkspaceWorkflow_1`: SaveWorkspaceWorkflow200Response
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.ArchiveWorkspaceWorkflow_1`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceId** | **string** | The workspace: &#39;personal&#39; for your own workspace, or the UUID of an organization. A call made for one of your managed users (&#x60;X-Managed-User-Id&#x60;) always uses &#39;personal&#39;: a managed user has no other workspace, and a call that names an organization is refused with 403.  | 
**workflowId** | **string** | The workflow&#39;s id | 

### Other Parameters

Other parameters are passed through a pointer to a apiArchiveWorkspaceWorkflowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**SaveWorkspaceWorkflow200Response**](SaveWorkspaceWorkflow200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateWorkspaceWorkflowFromPreset_1

> CreateWorkspaceWorkflowFromPreset201Response CreateWorkspaceWorkflowFromPreset_1(ctx, workspaceId).IdempotencyKey(idempotencyKey).CreateWorkspaceWorkflowFromPresetRequest(createWorkspaceWorkflowFromPresetRequest).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Start a Workflow from a starting point



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/widgetic/api-sdk-go"
)

func main() {
	workspaceId := "personal" // string | The workspace: 'personal' for your own workspace, or the UUID of an organization. A call made for one of your managed users (`X-Managed-User-Id`) always uses 'personal': a managed user has no other workspace, and a call that names an organization is refused with 403. 
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	createWorkspaceWorkflowFromPresetRequest := *openapiclient.NewCreateWorkspaceWorkflowFromPresetRequest("welcome-then-offer") // CreateWorkspaceWorkflowFromPresetRequest | 
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.CreateWorkspaceWorkflowFromPreset_1(context.Background(), workspaceId).IdempotencyKey(idempotencyKey).CreateWorkspaceWorkflowFromPresetRequest(createWorkspaceWorkflowFromPresetRequest).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.CreateWorkspaceWorkflowFromPreset_1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateWorkspaceWorkflowFromPreset_1`: CreateWorkspaceWorkflowFromPreset201Response
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.CreateWorkspaceWorkflowFromPreset_1`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceId** | **string** | The workspace: &#39;personal&#39; for your own workspace, or the UUID of an organization. A call made for one of your managed users (&#x60;X-Managed-User-Id&#x60;) always uses &#39;personal&#39;: a managed user has no other workspace, and a call that names an organization is refused with 403.  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateWorkspaceWorkflowFromPresetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **createWorkspaceWorkflowFromPresetRequest** | [**CreateWorkspaceWorkflowFromPresetRequest**](CreateWorkspaceWorkflowFromPresetRequest.md) |  | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**CreateWorkspaceWorkflowFromPreset201Response**](CreateWorkspaceWorkflowFromPreset201Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateWorkspaceWorkflow_1

> CreateWorkspaceWorkflowFromPreset201Response CreateWorkspaceWorkflow_1(ctx, workspaceId).IdempotencyKey(idempotencyKey).CreateWorkspaceWorkflowRequest(createWorkspaceWorkflowRequest).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Create a Workflow



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/widgetic/api-sdk-go"
)

func main() {
	workspaceId := "personal" // string | The workspace: 'personal' for your own workspace, or the UUID of an organization. A call made for one of your managed users (`X-Managed-User-Id`) always uses 'personal': a managed user has no other workspace, and a call that names an organization is refused with 403. 
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	createWorkspaceWorkflowRequest := *openapiclient.NewCreateWorkspaceWorkflowRequest("Welcome journey") // CreateWorkspaceWorkflowRequest | 
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.CreateWorkspaceWorkflow_1(context.Background(), workspaceId).IdempotencyKey(idempotencyKey).CreateWorkspaceWorkflowRequest(createWorkspaceWorkflowRequest).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.CreateWorkspaceWorkflow_1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateWorkspaceWorkflow_1`: CreateWorkspaceWorkflowFromPreset201Response
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.CreateWorkspaceWorkflow_1`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceId** | **string** | The workspace: &#39;personal&#39; for your own workspace, or the UUID of an organization. A call made for one of your managed users (&#x60;X-Managed-User-Id&#x60;) always uses &#39;personal&#39;: a managed user has no other workspace, and a call that names an organization is refused with 403.  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateWorkspaceWorkflowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **createWorkspaceWorkflowRequest** | [**CreateWorkspaceWorkflowRequest**](CreateWorkspaceWorkflowRequest.md) |  | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**CreateWorkspaceWorkflowFromPreset201Response**](CreateWorkspaceWorkflowFromPreset201Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteWorkspaceWorkflow_1

> DeleteWorkspaceWorkflow200Response DeleteWorkspaceWorkflow_1(ctx, workspaceId, workflowId).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Delete a Workflow



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/widgetic/api-sdk-go"
)

func main() {
	workspaceId := "personal" // string | The workspace: 'personal' for your own workspace, or the UUID of an organization. A call made for one of your managed users (`X-Managed-User-Id`) always uses 'personal': a managed user has no other workspace, and a call that names an organization is refused with 403. 
	workflowId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The workflow's id
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.DeleteWorkspaceWorkflow_1(context.Background(), workspaceId, workflowId).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.DeleteWorkspaceWorkflow_1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteWorkspaceWorkflow_1`: DeleteWorkspaceWorkflow200Response
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.DeleteWorkspaceWorkflow_1`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceId** | **string** | The workspace: &#39;personal&#39; for your own workspace, or the UUID of an organization. A call made for one of your managed users (&#x60;X-Managed-User-Id&#x60;) always uses &#39;personal&#39;: a managed user has no other workspace, and a call that names an organization is refused with 403.  | 
**workflowId** | **string** | The workflow&#39;s id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteWorkspaceWorkflowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**DeleteWorkspaceWorkflow200Response**](DeleteWorkspaceWorkflow200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DiscardWorkspaceWorkflowChanges_1

> CreateWorkspaceWorkflowFromPreset201Response DiscardWorkspaceWorkflowChanges_1(ctx, workspaceId, workflowId).PublishWorkspaceWorkflowRequest(publishWorkspaceWorkflowRequest).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Discard the Unpublished Changes of a Workflow



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/widgetic/api-sdk-go"
)

func main() {
	workspaceId := "personal" // string | The workspace: 'personal' for your own workspace, or the UUID of an organization. A call made for one of your managed users (`X-Managed-User-Id`) always uses 'personal': a managed user has no other workspace, and a call that names an organization is refused with 403. 
	workflowId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The workflow's id
	publishWorkspaceWorkflowRequest := *openapiclient.NewPublishWorkspaceWorkflowRequest(int32(123)) // PublishWorkspaceWorkflowRequest | 
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.DiscardWorkspaceWorkflowChanges_1(context.Background(), workspaceId, workflowId).PublishWorkspaceWorkflowRequest(publishWorkspaceWorkflowRequest).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.DiscardWorkspaceWorkflowChanges_1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DiscardWorkspaceWorkflowChanges_1`: CreateWorkspaceWorkflowFromPreset201Response
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.DiscardWorkspaceWorkflowChanges_1`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceId** | **string** | The workspace: &#39;personal&#39; for your own workspace, or the UUID of an organization. A call made for one of your managed users (&#x60;X-Managed-User-Id&#x60;) always uses &#39;personal&#39;: a managed user has no other workspace, and a call that names an organization is refused with 403.  | 
**workflowId** | **string** | The workflow&#39;s id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDiscardWorkspaceWorkflowChangesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **publishWorkspaceWorkflowRequest** | [**PublishWorkspaceWorkflowRequest**](PublishWorkspaceWorkflowRequest.md) |  | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**CreateWorkspaceWorkflowFromPreset201Response**](CreateWorkspaceWorkflowFromPreset201Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DuplicateWorkspaceWorkflow_1

> CreateWorkspaceWorkflowFromPreset201Response DuplicateWorkspaceWorkflow_1(ctx, workspaceId, workflowId).IdempotencyKey(idempotencyKey).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Duplicate a Workflow



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/widgetic/api-sdk-go"
)

func main() {
	workspaceId := "personal" // string | The workspace: 'personal' for your own workspace, or the UUID of an organization. A call made for one of your managed users (`X-Managed-User-Id`) always uses 'personal': a managed user has no other workspace, and a call that names an organization is refused with 403. 
	workflowId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The workflow's id
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.DuplicateWorkspaceWorkflow_1(context.Background(), workspaceId, workflowId).IdempotencyKey(idempotencyKey).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.DuplicateWorkspaceWorkflow_1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DuplicateWorkspaceWorkflow_1`: CreateWorkspaceWorkflowFromPreset201Response
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.DuplicateWorkspaceWorkflow_1`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceId** | **string** | The workspace: &#39;personal&#39; for your own workspace, or the UUID of an organization. A call made for one of your managed users (&#x60;X-Managed-User-Id&#x60;) always uses &#39;personal&#39;: a managed user has no other workspace, and a call that names an organization is refused with 403.  | 
**workflowId** | **string** | The workflow&#39;s id | 

### Other Parameters

Other parameters are passed through a pointer to a apiDuplicateWorkspaceWorkflowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**CreateWorkspaceWorkflowFromPreset201Response**](CreateWorkspaceWorkflowFromPreset201Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetWorkspaceWorkflowStats_1

> GetWorkspaceWorkflowStats200Response GetWorkspaceWorkflowStats_1(ctx, workspaceId, workflowId).VersionId(versionId).From(from).To(to).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Get what Visitors Did in a Workflow



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/widgetic/api-sdk-go"
)

func main() {
	workspaceId := "personal" // string | The workspace: 'personal' for your own workspace, or the UUID of an organization. A call made for one of your managed users (`X-Managed-User-Id`) always uses 'personal': a managed user has no other workspace, and a call that names an organization is refused with 403. 
	workflowId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The workflow's id
	versionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Count one version only (optional)
	from := "2026-10-01" // string | First UTC day (YYYY-MM-DD) (optional)
	to := "2026-10-27" // string | Last UTC day (YYYY-MM-DD) (optional)
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.GetWorkspaceWorkflowStats_1(context.Background(), workspaceId, workflowId).VersionId(versionId).From(from).To(to).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.GetWorkspaceWorkflowStats_1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetWorkspaceWorkflowStats_1`: GetWorkspaceWorkflowStats200Response
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.GetWorkspaceWorkflowStats_1`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceId** | **string** | The workspace: &#39;personal&#39; for your own workspace, or the UUID of an organization. A call made for one of your managed users (&#x60;X-Managed-User-Id&#x60;) always uses &#39;personal&#39;: a managed user has no other workspace, and a call that names an organization is refused with 403.  | 
**workflowId** | **string** | The workflow&#39;s id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetWorkspaceWorkflowStatsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **versionId** | **string** | Count one version only | 
 **from** | **string** | First UTC day (YYYY-MM-DD) | 
 **to** | **string** | Last UTC day (YYYY-MM-DD) | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**GetWorkspaceWorkflowStats200Response**](GetWorkspaceWorkflowStats200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetWorkspaceWorkflowVersion_1

> GetWorkspaceWorkflowVersion200Response GetWorkspaceWorkflowVersion_1(ctx, workspaceId, workflowId, versionId).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Get a Published Version of a Workflow



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/widgetic/api-sdk-go"
)

func main() {
	workspaceId := "personal" // string | The workspace: 'personal' for your own workspace, or the UUID of an organization. A call made for one of your managed users (`X-Managed-User-Id`) always uses 'personal': a managed user has no other workspace, and a call that names an organization is refused with 403. 
	workflowId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The workflow's id
	versionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The id of a published version of the workflow
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.GetWorkspaceWorkflowVersion_1(context.Background(), workspaceId, workflowId, versionId).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.GetWorkspaceWorkflowVersion_1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetWorkspaceWorkflowVersion_1`: GetWorkspaceWorkflowVersion200Response
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.GetWorkspaceWorkflowVersion_1`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceId** | **string** | The workspace: &#39;personal&#39; for your own workspace, or the UUID of an organization. A call made for one of your managed users (&#x60;X-Managed-User-Id&#x60;) always uses &#39;personal&#39;: a managed user has no other workspace, and a call that names an organization is refused with 403.  | 
**workflowId** | **string** | The workflow&#39;s id | 
**versionId** | **string** | The id of a published version of the workflow | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetWorkspaceWorkflowVersionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**GetWorkspaceWorkflowVersion200Response**](GetWorkspaceWorkflowVersion200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetWorkspaceWorkflow_1

> CreateWorkspaceWorkflowFromPreset201Response GetWorkspaceWorkflow_1(ctx, workspaceId, workflowId).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Get a Workflow



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/widgetic/api-sdk-go"
)

func main() {
	workspaceId := "personal" // string | The workspace: 'personal' for your own workspace, or the UUID of an organization. A call made for one of your managed users (`X-Managed-User-Id`) always uses 'personal': a managed user has no other workspace, and a call that names an organization is refused with 403. 
	workflowId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The workflow's id
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.GetWorkspaceWorkflow_1(context.Background(), workspaceId, workflowId).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.GetWorkspaceWorkflow_1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetWorkspaceWorkflow_1`: CreateWorkspaceWorkflowFromPreset201Response
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.GetWorkspaceWorkflow_1`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceId** | **string** | The workspace: &#39;personal&#39; for your own workspace, or the UUID of an organization. A call made for one of your managed users (&#x60;X-Managed-User-Id&#x60;) always uses &#39;personal&#39;: a managed user has no other workspace, and a call that names an organization is refused with 403.  | 
**workflowId** | **string** | The workflow&#39;s id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetWorkspaceWorkflowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**CreateWorkspaceWorkflowFromPreset201Response**](CreateWorkspaceWorkflowFromPreset201Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListWorkspaceWorkflowCompositionOptions_1

> ListWorkspaceWorkflowCompositionOptions200Response ListWorkspaceWorkflowCompositionOptions_1(ctx, workspaceId).Search(search).Ids(ids).Limit(limit).Offset(offset).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

List the compositions a workflow can show, and what each can do



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/widgetic/api-sdk-go"
)

func main() {
	workspaceId := "personal" // string | The workspace: 'personal' for your own workspace, or the UUID of an organization. A call made for one of your managed users (`X-Managed-User-Id`) always uses 'personal': a managed user has no other workspace, and a call that names an organization is refused with 403. 
	search := "search_example" // string | Text the composition's name must contain (optional)
	ids := "ids_example" // string | Only these compositions (comma-separated ids, at most 50), those of them you may see. Ask for the compositions a workflow shows with this, so each is found whatever page it would be on. An id you may not see is left out, as one that does not exist is.  (optional)
	limit := int32(56) // int32 | Page size (1-100, 50 when not given) (optional)
	offset := int32(56) // int32 | How many to skip (0 when not given) (optional)
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.ListWorkspaceWorkflowCompositionOptions_1(context.Background(), workspaceId).Search(search).Ids(ids).Limit(limit).Offset(offset).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.ListWorkspaceWorkflowCompositionOptions_1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListWorkspaceWorkflowCompositionOptions_1`: ListWorkspaceWorkflowCompositionOptions200Response
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.ListWorkspaceWorkflowCompositionOptions_1`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceId** | **string** | The workspace: &#39;personal&#39; for your own workspace, or the UUID of an organization. A call made for one of your managed users (&#x60;X-Managed-User-Id&#x60;) always uses &#39;personal&#39;: a managed user has no other workspace, and a call that names an organization is refused with 403.  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListWorkspaceWorkflowCompositionOptionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **search** | **string** | Text the composition&#39;s name must contain | 
 **ids** | **string** | Only these compositions (comma-separated ids, at most 50), those of them you may see. Ask for the compositions a workflow shows with this, so each is found whatever page it would be on. An id you may not see is left out, as one that does not exist is.  | 
 **limit** | **int32** | Page size (1-100, 50 when not given) | 
 **offset** | **int32** | How many to skip (0 when not given) | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**ListWorkspaceWorkflowCompositionOptions200Response**](ListWorkspaceWorkflowCompositionOptions200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListWorkspaceWorkflowPresets_1

> ListWorkspaceWorkflowPresets200Response ListWorkspaceWorkflowPresets_1(ctx, workspaceId).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

List the starting points for a new Workflow



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/widgetic/api-sdk-go"
)

func main() {
	workspaceId := "personal" // string | The workspace: 'personal' for your own workspace, or the UUID of an organization. A call made for one of your managed users (`X-Managed-User-Id`) always uses 'personal': a managed user has no other workspace, and a call that names an organization is refused with 403. 
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.ListWorkspaceWorkflowPresets_1(context.Background(), workspaceId).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.ListWorkspaceWorkflowPresets_1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListWorkspaceWorkflowPresets_1`: ListWorkspaceWorkflowPresets200Response
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.ListWorkspaceWorkflowPresets_1`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceId** | **string** | The workspace: &#39;personal&#39; for your own workspace, or the UUID of an organization. A call made for one of your managed users (&#x60;X-Managed-User-Id&#x60;) always uses &#39;personal&#39;: a managed user has no other workspace, and a call that names an organization is refused with 403.  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListWorkspaceWorkflowPresetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**ListWorkspaceWorkflowPresets200Response**](ListWorkspaceWorkflowPresets200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListWorkspaceWorkflowVersions_1

> ListWorkspaceWorkflowVersions200Response ListWorkspaceWorkflowVersions_1(ctx, workspaceId, workflowId).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

List the Published Versions of a Workflow



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/widgetic/api-sdk-go"
)

func main() {
	workspaceId := "personal" // string | The workspace: 'personal' for your own workspace, or the UUID of an organization. A call made for one of your managed users (`X-Managed-User-Id`) always uses 'personal': a managed user has no other workspace, and a call that names an organization is refused with 403. 
	workflowId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The workflow's id
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.ListWorkspaceWorkflowVersions_1(context.Background(), workspaceId, workflowId).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.ListWorkspaceWorkflowVersions_1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListWorkspaceWorkflowVersions_1`: ListWorkspaceWorkflowVersions200Response
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.ListWorkspaceWorkflowVersions_1`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceId** | **string** | The workspace: &#39;personal&#39; for your own workspace, or the UUID of an organization. A call made for one of your managed users (&#x60;X-Managed-User-Id&#x60;) always uses &#39;personal&#39;: a managed user has no other workspace, and a call that names an organization is refused with 403.  | 
**workflowId** | **string** | The workflow&#39;s id | 

### Other Parameters

Other parameters are passed through a pointer to a apiListWorkspaceWorkflowVersionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**ListWorkspaceWorkflowVersions200Response**](ListWorkspaceWorkflowVersions200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListWorkspaceWorkflows_1

> ListWorkspaceWorkflows200Response ListWorkspaceWorkflows_1(ctx, workspaceId).Search(search).Status(status).Sort(sort).Limit(limit).Offset(offset).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

List the Workflows of a Workspace



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/widgetic/api-sdk-go"
)

func main() {
	workspaceId := "personal" // string | The workspace: 'personal' for your own workspace, or the UUID of an organization. A call made for one of your managed users (`X-Managed-User-Id`) always uses 'personal': a managed user has no other workspace, and a call that names an organization is refused with 403. 
	search := "search_example" // string | Text the workflow's name must contain (optional)
	status := "status_example" // string | One state to list (`draft`, `live`, `paused`, `archived`), or `all` for every state. Without it, the ones in use (draft, live and paused). (optional)
	sort := "runsCount:desc" // string | `<field>:<asc|desc>` where field is createdAt, lastPublishedAt, runsCount or name (or just asc / desc for createdAt). Newest first when not given. (optional)
	limit := int32(56) // int32 | Page size (1-100, 50 when not given) (optional)
	offset := int32(56) // int32 | How many to skip (0 when not given) (optional)
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.ListWorkspaceWorkflows_1(context.Background(), workspaceId).Search(search).Status(status).Sort(sort).Limit(limit).Offset(offset).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.ListWorkspaceWorkflows_1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListWorkspaceWorkflows_1`: ListWorkspaceWorkflows200Response
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.ListWorkspaceWorkflows_1`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceId** | **string** | The workspace: &#39;personal&#39; for your own workspace, or the UUID of an organization. A call made for one of your managed users (&#x60;X-Managed-User-Id&#x60;) always uses &#39;personal&#39;: a managed user has no other workspace, and a call that names an organization is refused with 403.  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListWorkspaceWorkflowsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **search** | **string** | Text the workflow&#39;s name must contain | 
 **status** | **string** | One state to list (&#x60;draft&#x60;, &#x60;live&#x60;, &#x60;paused&#x60;, &#x60;archived&#x60;), or &#x60;all&#x60; for every state. Without it, the ones in use (draft, live and paused). | 
 **sort** | **string** | &#x60;&lt;field&gt;:&lt;asc|desc&gt;&#x60; where field is createdAt, lastPublishedAt, runsCount or name (or just asc / desc for createdAt). Newest first when not given. | 
 **limit** | **int32** | Page size (1-100, 50 when not given) | 
 **offset** | **int32** | How many to skip (0 when not given) | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**ListWorkspaceWorkflows200Response**](ListWorkspaceWorkflows200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PauseWorkspaceWorkflow_1

> SaveWorkspaceWorkflow200Response PauseWorkspaceWorkflow_1(ctx, workspaceId, workflowId).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Pause a Workflow



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/widgetic/api-sdk-go"
)

func main() {
	workspaceId := "personal" // string | The workspace: 'personal' for your own workspace, or the UUID of an organization. A call made for one of your managed users (`X-Managed-User-Id`) always uses 'personal': a managed user has no other workspace, and a call that names an organization is refused with 403. 
	workflowId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The workflow's id
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.PauseWorkspaceWorkflow_1(context.Background(), workspaceId, workflowId).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.PauseWorkspaceWorkflow_1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PauseWorkspaceWorkflow_1`: SaveWorkspaceWorkflow200Response
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.PauseWorkspaceWorkflow_1`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceId** | **string** | The workspace: &#39;personal&#39; for your own workspace, or the UUID of an organization. A call made for one of your managed users (&#x60;X-Managed-User-Id&#x60;) always uses &#39;personal&#39;: a managed user has no other workspace, and a call that names an organization is refused with 403.  | 
**workflowId** | **string** | The workflow&#39;s id | 

### Other Parameters

Other parameters are passed through a pointer to a apiPauseWorkspaceWorkflowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**SaveWorkspaceWorkflow200Response**](SaveWorkspaceWorkflow200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PublishWorkspaceWorkflow_1

> PublishWorkspaceWorkflow200Response PublishWorkspaceWorkflow_1(ctx, workspaceId, workflowId).IdempotencyKey(idempotencyKey).PublishWorkspaceWorkflowRequest(publishWorkspaceWorkflowRequest).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Publish the Draft of a Workflow



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/widgetic/api-sdk-go"
)

func main() {
	workspaceId := "personal" // string | The workspace: 'personal' for your own workspace, or the UUID of an organization. A call made for one of your managed users (`X-Managed-User-Id`) always uses 'personal': a managed user has no other workspace, and a call that names an organization is refused with 403. 
	workflowId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The workflow's id
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	publishWorkspaceWorkflowRequest := *openapiclient.NewPublishWorkspaceWorkflowRequest(int32(123)) // PublishWorkspaceWorkflowRequest | 
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.PublishWorkspaceWorkflow_1(context.Background(), workspaceId, workflowId).IdempotencyKey(idempotencyKey).PublishWorkspaceWorkflowRequest(publishWorkspaceWorkflowRequest).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.PublishWorkspaceWorkflow_1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PublishWorkspaceWorkflow_1`: PublishWorkspaceWorkflow200Response
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.PublishWorkspaceWorkflow_1`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceId** | **string** | The workspace: &#39;personal&#39; for your own workspace, or the UUID of an organization. A call made for one of your managed users (&#x60;X-Managed-User-Id&#x60;) always uses &#39;personal&#39;: a managed user has no other workspace, and a call that names an organization is refused with 403.  | 
**workflowId** | **string** | The workflow&#39;s id | 

### Other Parameters

Other parameters are passed through a pointer to a apiPublishWorkspaceWorkflowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **publishWorkspaceWorkflowRequest** | [**PublishWorkspaceWorkflowRequest**](PublishWorkspaceWorkflowRequest.md) |  | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**PublishWorkspaceWorkflow200Response**](PublishWorkspaceWorkflow200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RestoreWorkspaceWorkflowVersion_1

> CreateWorkspaceWorkflowFromPreset201Response RestoreWorkspaceWorkflowVersion_1(ctx, workspaceId, workflowId, versionId).PublishWorkspaceWorkflowRequest(publishWorkspaceWorkflowRequest).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Restore a Version of a Workflow into the Draft



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/widgetic/api-sdk-go"
)

func main() {
	workspaceId := "personal" // string | The workspace: 'personal' for your own workspace, or the UUID of an organization. A call made for one of your managed users (`X-Managed-User-Id`) always uses 'personal': a managed user has no other workspace, and a call that names an organization is refused with 403. 
	workflowId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The workflow's id
	versionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The id of a published version of the workflow
	publishWorkspaceWorkflowRequest := *openapiclient.NewPublishWorkspaceWorkflowRequest(int32(123)) // PublishWorkspaceWorkflowRequest | 
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.RestoreWorkspaceWorkflowVersion_1(context.Background(), workspaceId, workflowId, versionId).PublishWorkspaceWorkflowRequest(publishWorkspaceWorkflowRequest).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.RestoreWorkspaceWorkflowVersion_1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RestoreWorkspaceWorkflowVersion_1`: CreateWorkspaceWorkflowFromPreset201Response
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.RestoreWorkspaceWorkflowVersion_1`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceId** | **string** | The workspace: &#39;personal&#39; for your own workspace, or the UUID of an organization. A call made for one of your managed users (&#x60;X-Managed-User-Id&#x60;) always uses &#39;personal&#39;: a managed user has no other workspace, and a call that names an organization is refused with 403.  | 
**workflowId** | **string** | The workflow&#39;s id | 
**versionId** | **string** | The id of a published version of the workflow | 

### Other Parameters

Other parameters are passed through a pointer to a apiRestoreWorkspaceWorkflowVersionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **publishWorkspaceWorkflowRequest** | [**PublishWorkspaceWorkflowRequest**](PublishWorkspaceWorkflowRequest.md) |  | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**CreateWorkspaceWorkflowFromPreset201Response**](CreateWorkspaceWorkflowFromPreset201Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ResumeWorkspaceWorkflow_1

> SaveWorkspaceWorkflow200Response ResumeWorkspaceWorkflow_1(ctx, workspaceId, workflowId).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Resume a Paused Workflow



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/widgetic/api-sdk-go"
)

func main() {
	workspaceId := "personal" // string | The workspace: 'personal' for your own workspace, or the UUID of an organization. A call made for one of your managed users (`X-Managed-User-Id`) always uses 'personal': a managed user has no other workspace, and a call that names an organization is refused with 403. 
	workflowId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The workflow's id
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.ResumeWorkspaceWorkflow_1(context.Background(), workspaceId, workflowId).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.ResumeWorkspaceWorkflow_1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ResumeWorkspaceWorkflow_1`: SaveWorkspaceWorkflow200Response
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.ResumeWorkspaceWorkflow_1`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceId** | **string** | The workspace: &#39;personal&#39; for your own workspace, or the UUID of an organization. A call made for one of your managed users (&#x60;X-Managed-User-Id&#x60;) always uses &#39;personal&#39;: a managed user has no other workspace, and a call that names an organization is refused with 403.  | 
**workflowId** | **string** | The workflow&#39;s id | 

### Other Parameters

Other parameters are passed through a pointer to a apiResumeWorkspaceWorkflowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**SaveWorkspaceWorkflow200Response**](SaveWorkspaceWorkflow200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SaveWorkspaceWorkflow_1

> SaveWorkspaceWorkflow200Response SaveWorkspaceWorkflow_1(ctx, workspaceId, workflowId).SaveWorkspaceWorkflowRequest(saveWorkspaceWorkflowRequest).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Save the Draft of a Workflow



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/widgetic/api-sdk-go"
)

func main() {
	workspaceId := "personal" // string | The workspace: 'personal' for your own workspace, or the UUID of an organization. A call made for one of your managed users (`X-Managed-User-Id`) always uses 'personal': a managed user has no other workspace, and a call that names an organization is refused with 403. 
	workflowId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The workflow's id
	saveWorkspaceWorkflowRequest := *openapiclient.NewSaveWorkspaceWorkflowRequest(int32(123)) // SaveWorkspaceWorkflowRequest | 
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.SaveWorkspaceWorkflow_1(context.Background(), workspaceId, workflowId).SaveWorkspaceWorkflowRequest(saveWorkspaceWorkflowRequest).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.SaveWorkspaceWorkflow_1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SaveWorkspaceWorkflow_1`: SaveWorkspaceWorkflow200Response
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.SaveWorkspaceWorkflow_1`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceId** | **string** | The workspace: &#39;personal&#39; for your own workspace, or the UUID of an organization. A call made for one of your managed users (&#x60;X-Managed-User-Id&#x60;) always uses &#39;personal&#39;: a managed user has no other workspace, and a call that names an organization is refused with 403.  | 
**workflowId** | **string** | The workflow&#39;s id | 

### Other Parameters

Other parameters are passed through a pointer to a apiSaveWorkspaceWorkflowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **saveWorkspaceWorkflowRequest** | [**SaveWorkspaceWorkflowRequest**](SaveWorkspaceWorkflowRequest.md) |  | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**SaveWorkspaceWorkflow200Response**](SaveWorkspaceWorkflow200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UnarchiveWorkspaceWorkflow_1

> SaveWorkspaceWorkflow200Response UnarchiveWorkspaceWorkflow_1(ctx, workspaceId, workflowId).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Unarchive a Workflow



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/widgetic/api-sdk-go"
)

func main() {
	workspaceId := "personal" // string | The workspace: 'personal' for your own workspace, or the UUID of an organization. A call made for one of your managed users (`X-Managed-User-Id`) always uses 'personal': a managed user has no other workspace, and a call that names an organization is refused with 403. 
	workflowId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The workflow's id
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.UnarchiveWorkspaceWorkflow_1(context.Background(), workspaceId, workflowId).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.UnarchiveWorkspaceWorkflow_1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UnarchiveWorkspaceWorkflow_1`: SaveWorkspaceWorkflow200Response
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.UnarchiveWorkspaceWorkflow_1`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceId** | **string** | The workspace: &#39;personal&#39; for your own workspace, or the UUID of an organization. A call made for one of your managed users (&#x60;X-Managed-User-Id&#x60;) always uses &#39;personal&#39;: a managed user has no other workspace, and a call that names an organization is refused with 403.  | 
**workflowId** | **string** | The workflow&#39;s id | 

### Other Parameters

Other parameters are passed through a pointer to a apiUnarchiveWorkspaceWorkflowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions and workflows: a list shows only theirs, a composition or a workflow the call makes is filed under them, and one of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**SaveWorkspaceWorkflow200Response**](SaveWorkspaceWorkflow200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

