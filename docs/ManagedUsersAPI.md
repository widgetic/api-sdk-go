# \ManagedUsersAPI

All URIs are relative to *https://api.widgetic.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CopyPresetForManagedUser_0**](ManagedUsersAPI.md#CopyPresetForManagedUser_0) | **Post** /managed-users/{id}/presets/{key}/copy | Give a managed user a copy of one of your presets
[**CreateCompositionFromPreset_0**](ManagedUsersAPI.md#CreateCompositionFromPreset_0) | **Post** /managed-users/{id}/presets/{key}/composition | Create a composition from one of your presets in one call
[**CreateManagedUserEditorSession_0**](ManagedUsersAPI.md#CreateManagedUserEditorSession_0) | **Post** /managed-users/{id}/editor-sessions | Create an editor session for a managed user
[**CreateManagedUser_0**](ManagedUsersAPI.md#CreateManagedUser_0) | **Post** /managed-users | Create Managed User
[**DeleteManagedUser_0**](ManagedUsersAPI.md#DeleteManagedUser_0) | **Delete** /managed-users/{id} | Delete Managed User
[**GetAllManagedUsers_0**](ManagedUsersAPI.md#GetAllManagedUsers_0) | **Get** /managed-users | Get Managed Users
[**GetManagedUserById_0**](ManagedUsersAPI.md#GetManagedUserById_0) | **Get** /managed-users/{id} | Get Managed User By ID
[**GetManagedUserDesignDefaults_0**](ManagedUsersAPI.md#GetManagedUserDesignDefaults_0) | **Get** /managed-users/{id}/design-defaults | Read design defaults for one managed user
[**GetManagedUserLimits_0**](ManagedUsersAPI.md#GetManagedUserLimits_0) | **Get** /managed-users/{id}/limits | Read monthly credit cap and usage for one managed user
[**GetManagedUserStorageUsage_0**](ManagedUsersAPI.md#GetManagedUserStorageUsage_0) | **Get** /managed-users/{id}/storage-usage | Storage used by one managed user&#39;s uploads
[**GetManagedUserUsage_0**](ManagedUsersAPI.md#GetManagedUserUsage_0) | **Get** /managed-users/{id}/usage | What a managed user&#39;s editor sessions spent
[**GetManagedUsersByManagerId_0**](ManagedUsersAPI.md#GetManagedUsersByManagerId_0) | **Get** /users/{managerId}/managed-users | Get Managed Users By Manager
[**RevokeManagedUserEditorSession_0**](ManagedUsersAPI.md#RevokeManagedUserEditorSession_0) | **Delete** /managed-users/{id}/editor-sessions/{sessionId} | End one editor session of a managed user
[**RevokeManagedUserEditorSessions_0**](ManagedUsersAPI.md#RevokeManagedUserEditorSessions_0) | **Delete** /managed-users/{id}/editor-sessions | End every editor session of a managed user
[**SetManagedUserDesignDefaults_0**](ManagedUsersAPI.md#SetManagedUserDesignDefaults_0) | **Put** /managed-users/{id}/design-defaults | Set or clear design defaults for one managed user
[**SetManagedUserLimits_0**](ManagedUsersAPI.md#SetManagedUserLimits_0) | **Put** /managed-users/{id}/limits | Set or clear the monthly credit cap for one managed user
[**UpdateManagedUser_0**](ManagedUsersAPI.md#UpdateManagedUser_0) | **Put** /managed-users/{id} | Update Managed User



## CopyPresetForManagedUser_0

> PartnerPresetCopyResponse CopyPresetForManagedUser_0(ctx, id, key).IdempotencyKey(idempotencyKey).CopyPartnerPresetRequest(copyPartnerPresetRequest).Execute()

Give a managed user a copy of one of your presets



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The managed user to give the copy to (Widgetic's id for the user)
	key := "key_example" // string | The key of the preset to copy
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	copyPartnerPresetRequest := *openapiclient.NewCopyPartnerPresetRequest() // CopyPartnerPresetRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagedUsersAPI.CopyPresetForManagedUser_0(context.Background(), id, key).IdempotencyKey(idempotencyKey).CopyPartnerPresetRequest(copyPartnerPresetRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagedUsersAPI.CopyPresetForManagedUser_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CopyPresetForManagedUser_0`: PartnerPresetCopyResponse
	fmt.Fprintf(os.Stdout, "Response from `ManagedUsersAPI.CopyPresetForManagedUser_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The managed user to give the copy to (Widgetic&#39;s id for the user) | 
**key** | **string** | The key of the preset to copy | 

### Other Parameters

Other parameters are passed through a pointer to a apiCopyPresetForManagedUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **copyPartnerPresetRequest** | [**CopyPartnerPresetRequest**](CopyPartnerPresetRequest.md) |  | 

### Return type

[**PartnerPresetCopyResponse**](PartnerPresetCopyResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateCompositionFromPreset_0

> CreateCompositionFromWidget201Response CreateCompositionFromPreset_0(ctx, id, key).IdempotencyKey(idempotencyKey).CreateCompositionFromPresetRequest(createCompositionFromPresetRequest).Execute()

Create a composition from one of your presets in one call



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	key := "key_example" // string | 
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	createCompositionFromPresetRequest := *openapiclient.NewCreateCompositionFromPresetRequest("Name_example") // CreateCompositionFromPresetRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagedUsersAPI.CreateCompositionFromPreset_0(context.Background(), id, key).IdempotencyKey(idempotencyKey).CreateCompositionFromPresetRequest(createCompositionFromPresetRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagedUsersAPI.CreateCompositionFromPreset_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateCompositionFromPreset_0`: CreateCompositionFromWidget201Response
	fmt.Fprintf(os.Stdout, "Response from `ManagedUsersAPI.CreateCompositionFromPreset_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**key** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateCompositionFromPresetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **createCompositionFromPresetRequest** | [**CreateCompositionFromPresetRequest**](CreateCompositionFromPresetRequest.md) |  | 

### Return type

[**CreateCompositionFromWidget201Response**](CreateCompositionFromWidget201Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateManagedUserEditorSession_0

> EditorSessionResponse CreateManagedUserEditorSession_0(ctx, id).CreateEditorSessionRequest(createEditorSessionRequest).Execute()

Create an editor session for a managed user



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The managed user the session is for (Widgetic's id for the user)
	createEditorSessionRequest := *openapiclient.NewCreateEditorSessionRequest([]string{"Surfaces_example"}) // CreateEditorSessionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagedUsersAPI.CreateManagedUserEditorSession_0(context.Background(), id).CreateEditorSessionRequest(createEditorSessionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagedUsersAPI.CreateManagedUserEditorSession_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateManagedUserEditorSession_0`: EditorSessionResponse
	fmt.Fprintf(os.Stdout, "Response from `ManagedUsersAPI.CreateManagedUserEditorSession_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The managed user the session is for (Widgetic&#39;s id for the user) | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateManagedUserEditorSessionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createEditorSessionRequest** | [**CreateEditorSessionRequest**](CreateEditorSessionRequest.md) |  | 

### Return type

[**EditorSessionResponse**](EditorSessionResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateManagedUser_0

> ManagedUserResponse CreateManagedUser_0(ctx).IdempotencyKey(idempotencyKey).CreateManagedUserRequest(createManagedUserRequest).Execute()

Create Managed User



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
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	createManagedUserRequest := *openapiclient.NewCreateManagedUserRequest("external-user-123") // CreateManagedUserRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagedUsersAPI.CreateManagedUser_0(context.Background()).IdempotencyKey(idempotencyKey).CreateManagedUserRequest(createManagedUserRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagedUsersAPI.CreateManagedUser_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateManagedUser_0`: ManagedUserResponse
	fmt.Fprintf(os.Stdout, "Response from `ManagedUsersAPI.CreateManagedUser_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateManagedUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **createManagedUserRequest** | [**CreateManagedUserRequest**](CreateManagedUserRequest.md) |  | 

### Return type

[**ManagedUserResponse**](ManagedUserResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteManagedUser_0

> DeleteManagedUser200Response DeleteManagedUser_0(ctx, id).Execute()

Delete Managed User



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the managed user to delete

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagedUsersAPI.DeleteManagedUser_0(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagedUsersAPI.DeleteManagedUser_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteManagedUser_0`: DeleteManagedUser200Response
	fmt.Fprintf(os.Stdout, "Response from `ManagedUsersAPI.DeleteManagedUser_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the managed user to delete | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteManagedUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DeleteManagedUser200Response**](DeleteManagedUser200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAllManagedUsers_0

> GetAllManagedUsers200Response GetAllManagedUsers_0(ctx).Page(page).Size(size).Sort(sort).Execute()

Get Managed Users



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
	page := int32(56) // int32 | Page number for pagination (optional) (default to 1)
	size := int32(56) // int32 | Number of items per page (optional) (default to 10)
	sort := "sort_example" // string | Sort field and direction, `<field>:<asc|desc>`. The field is `createdAt`, `updatedAt` or `externalId` (the snake_case spellings `created_at`, `updated_at` and `external_id` work too); `asc` or `desc` alone sorts by `createdAt`. Any other field is a 400. (optional) (default to "createdAt:desc")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagedUsersAPI.GetAllManagedUsers_0(context.Background()).Page(page).Size(size).Sort(sort).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagedUsersAPI.GetAllManagedUsers_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAllManagedUsers_0`: GetAllManagedUsers200Response
	fmt.Fprintf(os.Stdout, "Response from `ManagedUsersAPI.GetAllManagedUsers_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAllManagedUsersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** | Page number for pagination | [default to 1]
 **size** | **int32** | Number of items per page | [default to 10]
 **sort** | **string** | Sort field and direction, &#x60;&lt;field&gt;:&lt;asc|desc&gt;&#x60;. The field is &#x60;createdAt&#x60;, &#x60;updatedAt&#x60; or &#x60;externalId&#x60; (the snake_case spellings &#x60;created_at&#x60;, &#x60;updated_at&#x60; and &#x60;external_id&#x60; work too); &#x60;asc&#x60; or &#x60;desc&#x60; alone sorts by &#x60;createdAt&#x60;. Any other field is a 400. | [default to &quot;createdAt:desc&quot;]

### Return type

[**GetAllManagedUsers200Response**](GetAllManagedUsers200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetManagedUserById_0

> ManagedUserResponse GetManagedUserById_0(ctx, id).Execute()

Get Managed User By ID



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the managed user to retrieve

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagedUsersAPI.GetManagedUserById_0(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagedUsersAPI.GetManagedUserById_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetManagedUserById_0`: ManagedUserResponse
	fmt.Fprintf(os.Stdout, "Response from `ManagedUsersAPI.GetManagedUserById_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the managed user to retrieve | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetManagedUserByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ManagedUserResponse**](ManagedUserResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetManagedUserDesignDefaults_0

> GetPartnerDesignDefaults200Response GetManagedUserDesignDefaults_0(ctx, id).Execute()

Read design defaults for one managed user

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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagedUsersAPI.GetManagedUserDesignDefaults_0(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagedUsersAPI.GetManagedUserDesignDefaults_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetManagedUserDesignDefaults_0`: GetPartnerDesignDefaults200Response
	fmt.Fprintf(os.Stdout, "Response from `ManagedUsersAPI.GetManagedUserDesignDefaults_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetManagedUserDesignDefaultsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetPartnerDesignDefaults200Response**](GetPartnerDesignDefaults200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetManagedUserLimits_0

> GetManagedUserLimits200Response GetManagedUserLimits_0(ctx, id).Execute()

Read monthly credit cap and usage for one managed user

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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagedUsersAPI.GetManagedUserLimits_0(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagedUsersAPI.GetManagedUserLimits_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetManagedUserLimits_0`: GetManagedUserLimits200Response
	fmt.Fprintf(os.Stdout, "Response from `ManagedUsersAPI.GetManagedUserLimits_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetManagedUserLimitsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetManagedUserLimits200Response**](GetManagedUserLimits200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetManagedUserStorageUsage_0

> GetManagedUserStorageUsage200Response GetManagedUserStorageUsage_0(ctx, id).Execute()

Storage used by one managed user's uploads

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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagedUsersAPI.GetManagedUserStorageUsage_0(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagedUsersAPI.GetManagedUserStorageUsage_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetManagedUserStorageUsage_0`: GetManagedUserStorageUsage200Response
	fmt.Fprintf(os.Stdout, "Response from `ManagedUsersAPI.GetManagedUserStorageUsage_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetManagedUserStorageUsageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetManagedUserStorageUsage200Response**](GetManagedUserStorageUsage200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetManagedUserUsage_0

> ManagedUserUsageResponse GetManagedUserUsage_0(ctx, id).StartDate(startDate).EndDate(endDate).Execute()

What a managed user's editor sessions spent



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The managed user whose usage you want (Widgetic's id for the user)
	startDate := "startDate_example" // string | Start of the period, included: an ISO 8601 date (`2026-10-01`) or date-time with its offset (`2026-10-01T08:00:00Z`). Default: 30 days before `endDate`.  (optional)
	endDate := "endDate_example" // string | End of the period, not included, in the same forms. Default: now. It must be after `startDate`, by at most 366 days.  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagedUsersAPI.GetManagedUserUsage_0(context.Background(), id).StartDate(startDate).EndDate(endDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagedUsersAPI.GetManagedUserUsage_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetManagedUserUsage_0`: ManagedUserUsageResponse
	fmt.Fprintf(os.Stdout, "Response from `ManagedUsersAPI.GetManagedUserUsage_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The managed user whose usage you want (Widgetic&#39;s id for the user) | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetManagedUserUsageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **startDate** | **string** | Start of the period, included: an ISO 8601 date (&#x60;2026-10-01&#x60;) or date-time with its offset (&#x60;2026-10-01T08:00:00Z&#x60;). Default: 30 days before &#x60;endDate&#x60;.  | 
 **endDate** | **string** | End of the period, not included, in the same forms. Default: now. It must be after &#x60;startDate&#x60;, by at most 366 days.  | 

### Return type

[**ManagedUserUsageResponse**](ManagedUserUsageResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetManagedUsersByManagerId_0

> GetManagedUsersByManagerIdResponse GetManagedUsersByManagerId_0(ctx, managerId).Page(page).Size(size).Sort(sort).Execute()

Get Managed Users By Manager



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
	managerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the manager
	page := int32(56) // int32 | Page number for pagination (optional) (default to 1)
	size := int32(56) // int32 | Number of items per page (optional) (default to 10)
	sort := "sort_example" // string | Sort field and direction, `<field>:<asc|desc>`. The field is `createdAt`, `updatedAt` or `externalId` (the snake_case spellings `created_at`, `updated_at` and `external_id` work too); `asc` or `desc` alone sorts by `createdAt`. Any other field is a 400. (optional) (default to "createdAt:desc")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagedUsersAPI.GetManagedUsersByManagerId_0(context.Background(), managerId).Page(page).Size(size).Sort(sort).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagedUsersAPI.GetManagedUsersByManagerId_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetManagedUsersByManagerId_0`: GetManagedUsersByManagerIdResponse
	fmt.Fprintf(os.Stdout, "Response from `ManagedUsersAPI.GetManagedUsersByManagerId_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**managerId** | **string** | ID of the manager | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetManagedUsersByManagerIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **page** | **int32** | Page number for pagination | [default to 1]
 **size** | **int32** | Number of items per page | [default to 10]
 **sort** | **string** | Sort field and direction, &#x60;&lt;field&gt;:&lt;asc|desc&gt;&#x60;. The field is &#x60;createdAt&#x60;, &#x60;updatedAt&#x60; or &#x60;externalId&#x60; (the snake_case spellings &#x60;created_at&#x60;, &#x60;updated_at&#x60; and &#x60;external_id&#x60; work too); &#x60;asc&#x60; or &#x60;desc&#x60; alone sorts by &#x60;createdAt&#x60;. Any other field is a 400. | [default to &quot;createdAt:desc&quot;]

### Return type

[**GetManagedUsersByManagerIdResponse**](GetManagedUsersByManagerIdResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RevokeManagedUserEditorSession_0

> DeleteManagedUser200Response RevokeManagedUserEditorSession_0(ctx, id, sessionId).Execute()

End one editor session of a managed user



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The managed user the session is for
	sessionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The `sessionId` of the session, from `createManagedUserEditorSession`

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagedUsersAPI.RevokeManagedUserEditorSession_0(context.Background(), id, sessionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagedUsersAPI.RevokeManagedUserEditorSession_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RevokeManagedUserEditorSession_0`: DeleteManagedUser200Response
	fmt.Fprintf(os.Stdout, "Response from `ManagedUsersAPI.RevokeManagedUserEditorSession_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The managed user the session is for | 
**sessionId** | **string** | The &#x60;sessionId&#x60; of the session, from &#x60;createManagedUserEditorSession&#x60; | 

### Other Parameters

Other parameters are passed through a pointer to a apiRevokeManagedUserEditorSessionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**DeleteManagedUser200Response**](DeleteManagedUser200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RevokeManagedUserEditorSessions_0

> RevokeManagedUserEditorSessionsResponse RevokeManagedUserEditorSessions_0(ctx, id).Execute()

End every editor session of a managed user



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The managed user whose sessions end

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagedUsersAPI.RevokeManagedUserEditorSessions_0(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagedUsersAPI.RevokeManagedUserEditorSessions_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RevokeManagedUserEditorSessions_0`: RevokeManagedUserEditorSessionsResponse
	fmt.Fprintf(os.Stdout, "Response from `ManagedUsersAPI.RevokeManagedUserEditorSessions_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The managed user whose sessions end | 

### Other Parameters

Other parameters are passed through a pointer to a apiRevokeManagedUserEditorSessionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RevokeManagedUserEditorSessionsResponse**](RevokeManagedUserEditorSessionsResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetManagedUserDesignDefaults_0

> GetPartnerDesignDefaults200Response SetManagedUserDesignDefaults_0(ctx, id).SetPartnerDesignDefaultsRequest(setPartnerDesignDefaultsRequest).Execute()

Set or clear design defaults for one managed user



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	setPartnerDesignDefaultsRequest := *openapiclient.NewSetPartnerDesignDefaultsRequest(map[string]interface{}(123)) // SetPartnerDesignDefaultsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagedUsersAPI.SetManagedUserDesignDefaults_0(context.Background(), id).SetPartnerDesignDefaultsRequest(setPartnerDesignDefaultsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagedUsersAPI.SetManagedUserDesignDefaults_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetManagedUserDesignDefaults_0`: GetPartnerDesignDefaults200Response
	fmt.Fprintf(os.Stdout, "Response from `ManagedUsersAPI.SetManagedUserDesignDefaults_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSetManagedUserDesignDefaultsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **setPartnerDesignDefaultsRequest** | [**SetPartnerDesignDefaultsRequest**](SetPartnerDesignDefaultsRequest.md) |  | 

### Return type

[**GetPartnerDesignDefaults200Response**](GetPartnerDesignDefaults200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetManagedUserLimits_0

> GetManagedUserLimits200Response SetManagedUserLimits_0(ctx, id).SetManagedUserLimitsRequest(setManagedUserLimitsRequest).Execute()

Set or clear the monthly credit cap for one managed user



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	setManagedUserLimitsRequest := *openapiclient.NewSetManagedUserLimitsRequest(NullableInt32(123)) // SetManagedUserLimitsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagedUsersAPI.SetManagedUserLimits_0(context.Background(), id).SetManagedUserLimitsRequest(setManagedUserLimitsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagedUsersAPI.SetManagedUserLimits_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetManagedUserLimits_0`: GetManagedUserLimits200Response
	fmt.Fprintf(os.Stdout, "Response from `ManagedUsersAPI.SetManagedUserLimits_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSetManagedUserLimitsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **setManagedUserLimitsRequest** | [**SetManagedUserLimitsRequest**](SetManagedUserLimitsRequest.md) |  | 

### Return type

[**GetManagedUserLimits200Response**](GetManagedUserLimits200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateManagedUser_0

> ManagedUserResponse UpdateManagedUser_0(ctx, id).IdempotencyKey(idempotencyKey).UpdateManagedUser(updateManagedUser).Execute()

Update Managed User



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the managed user to update
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	updateManagedUser := *openapiclient.NewUpdateManagedUser() // UpdateManagedUser | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManagedUsersAPI.UpdateManagedUser_0(context.Background(), id).IdempotencyKey(idempotencyKey).UpdateManagedUser(updateManagedUser).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManagedUsersAPI.UpdateManagedUser_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateManagedUser_0`: ManagedUserResponse
	fmt.Fprintf(os.Stdout, "Response from `ManagedUsersAPI.UpdateManagedUser_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the managed user to update | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateManagedUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **updateManagedUser** | [**UpdateManagedUser**](UpdateManagedUser.md) |  | 

### Return type

[**ManagedUserResponse**](ManagedUserResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

