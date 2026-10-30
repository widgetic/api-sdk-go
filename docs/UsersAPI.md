# \UsersAPI

All URIs are relative to *https://api.widgetic.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddPersonalWorkspaceDomain_0**](UsersAPI.md#AddPersonalWorkspaceDomain_0) | **Post** /users/{id}/workspace/domains | Allow a website to show your widgets
[**ConfirmUserAdapterConnection_0**](UsersAPI.md#ConfirmUserAdapterConnection_0) | **Post** /users/{userId}/adapter-connections/{adapterId}/{credentialKey}/confirm | Confirm an adapter address with the code that was emailed to it
[**CreateUserApiKey_0**](UsersAPI.md#CreateUserApiKey_0) | **Post** /users/{id}/keys | Create an API key
[**DeletePersonalWorkspaceDomain_0**](UsersAPI.md#DeletePersonalWorkspaceDomain_0) | **Delete** /users/{id}/workspace/domains/{domainId} | Stop allowing a website to show your widgets
[**DeleteUserApiKey_0**](UsersAPI.md#DeleteUserApiKey_0) | **Delete** /users/{id}/keys/{keyId} | Delete an API key
[**GetPersonalWorkspaceDomains_0**](UsersAPI.md#GetPersonalWorkspaceDomains_0) | **Get** /users/{id}/workspace/domains | List the websites allowed to show your widgets
[**GetUserAdapterConnections_0**](UsersAPI.md#GetUserAdapterConnections_0) | **Get** /users/{userId}/adapter-connections | See which adapter keys an account has connected
[**GetUserApiKeyUsageLogs_0**](UsersAPI.md#GetUserApiKeyUsageLogs_0) | **Get** /users/{id}/api-keys/{keyId}/logs | Read what an API key was used for
[**GetUserApiKeys_0**](UsersAPI.md#GetUserApiKeys_0) | **Get** /users/{id}/keys | List the API keys of an account
[**RemoveUserAdapterConnection_0**](UsersAPI.md#RemoveUserAdapterConnection_0) | **Delete** /users/{userId}/adapter-connections/{adapterId}/{credentialKey} | Remove an adapter key from an account
[**SetUserAdapterConnection_0**](UsersAPI.md#SetUserAdapterConnection_0) | **Put** /users/{userId}/adapter-connections/{adapterId}/{credentialKey} | Connect an adapter key to an account
[**UpdatePersonalWorkspaceDomain_0**](UsersAPI.md#UpdatePersonalWorkspaceDomain_0) | **Put** /users/{id}/workspace/domains/{domainId} | Change a website on your list
[**UpdateUserApiKey_0**](UsersAPI.md#UpdateUserApiKey_0) | **Put** /users/{id}/keys/{keyId} | Rename an API key, or switch it off or on



## AddPersonalWorkspaceDomain_0

> PersonalWorkspaceDomainResultResponse AddPersonalWorkspaceDomain_0(ctx, id).AddDomainRequest(addDomainRequest).Execute()

Allow a website to show your widgets



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The account the list belongs to. For your own, your own user id
	addDomainRequest := *openapiclient.NewAddDomainRequest("example.com") // AddDomainRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.AddPersonalWorkspaceDomain_0(context.Background(), id).AddDomainRequest(addDomainRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.AddPersonalWorkspaceDomain_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AddPersonalWorkspaceDomain_0`: PersonalWorkspaceDomainResultResponse
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.AddPersonalWorkspaceDomain_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The account the list belongs to. For your own, your own user id | 

### Other Parameters

Other parameters are passed through a pointer to a apiAddPersonalWorkspaceDomainRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **addDomainRequest** | [**AddDomainRequest**](AddDomainRequest.md) |  | 

### Return type

[**PersonalWorkspaceDomainResultResponse**](PersonalWorkspaceDomainResultResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ConfirmUserAdapterConnection_0

> SetUserAdapterConnection200Response ConfirmUserAdapterConnection_0(ctx, userId, adapterId, credentialKey).ConfirmAdapterConnectionRequest(confirmAdapterConnectionRequest).Execute()

Confirm an adapter address with the code that was emailed to it



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
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The account that keeps the address. For your own, your own user id
	adapterId := "adapterId_example" // string | The adapter the address is for
	credentialKey := "credentialKey_example" // string | The credential's name within the adapter
	confirmAdapterConnectionRequest := *openapiclient.NewConfirmAdapterConnectionRequest("123456") // ConfirmAdapterConnectionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.ConfirmUserAdapterConnection_0(context.Background(), userId, adapterId, credentialKey).ConfirmAdapterConnectionRequest(confirmAdapterConnectionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.ConfirmUserAdapterConnection_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ConfirmUserAdapterConnection_0`: SetUserAdapterConnection200Response
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.ConfirmUserAdapterConnection_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** | The account that keeps the address. For your own, your own user id | 
**adapterId** | **string** | The adapter the address is for | 
**credentialKey** | **string** | The credential&#39;s name within the adapter | 

### Other Parameters

Other parameters are passed through a pointer to a apiConfirmUserAdapterConnectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **confirmAdapterConnectionRequest** | [**ConfirmAdapterConnectionRequest**](ConfirmAdapterConnectionRequest.md) |  | 

### Return type

[**SetUserAdapterConnection200Response**](SetUserAdapterConnection200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateUserApiKey_0

> CreatedUserApiKeyResponse CreateUserApiKey_0(ctx, id).IdempotencyKey(idempotencyKey).CreateUserApiKeyRequest(createUserApiKeyRequest).Execute()

Create an API key



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The account the key is for. For your own, your own user id
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	createUserApiKeyRequest := *openapiclient.NewCreateUserApiKeyRequest("Production") // CreateUserApiKeyRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.CreateUserApiKey_0(context.Background(), id).IdempotencyKey(idempotencyKey).CreateUserApiKeyRequest(createUserApiKeyRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.CreateUserApiKey_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateUserApiKey_0`: CreatedUserApiKeyResponse
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.CreateUserApiKey_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The account the key is for. For your own, your own user id | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateUserApiKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **createUserApiKeyRequest** | [**CreateUserApiKeyRequest**](CreateUserApiKeyRequest.md) |  | 

### Return type

[**CreatedUserApiKeyResponse**](CreatedUserApiKeyResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeletePersonalWorkspaceDomain_0

> DeletePersonalWorkspaceDomainResponse DeletePersonalWorkspaceDomain_0(ctx, id, domainId).Execute()

Stop allowing a website to show your widgets



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The account the list belongs to. For your own, your own user id
	domainId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The `id` of the entry, as the list shows it

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.DeletePersonalWorkspaceDomain_0(context.Background(), id, domainId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.DeletePersonalWorkspaceDomain_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeletePersonalWorkspaceDomain_0`: DeletePersonalWorkspaceDomainResponse
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.DeletePersonalWorkspaceDomain_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The account the list belongs to. For your own, your own user id | 
**domainId** | **string** | The &#x60;id&#x60; of the entry, as the list shows it | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeletePersonalWorkspaceDomainRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**DeletePersonalWorkspaceDomainResponse**](DeletePersonalWorkspaceDomainResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteUserApiKey_0

> DeleteUserApiKeyResponse DeleteUserApiKey_0(ctx, id, keyId).Execute()

Delete an API key



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The account the key belongs to
	keyId := "keyId_example" // string | The `keyId` of the key, as the list shows it

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.DeleteUserApiKey_0(context.Background(), id, keyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.DeleteUserApiKey_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteUserApiKey_0`: DeleteUserApiKeyResponse
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.DeleteUserApiKey_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The account the key belongs to | 
**keyId** | **string** | The &#x60;keyId&#x60; of the key, as the list shows it | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteUserApiKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**DeleteUserApiKeyResponse**](DeleteUserApiKeyResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPersonalWorkspaceDomains_0

> GetPersonalWorkspaceDomains200Response GetPersonalWorkspaceDomains_0(ctx, id).Execute()

List the websites allowed to show your widgets



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The account the list belongs to. For your own, your own user id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.GetPersonalWorkspaceDomains_0(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.GetPersonalWorkspaceDomains_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPersonalWorkspaceDomains_0`: GetPersonalWorkspaceDomains200Response
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.GetPersonalWorkspaceDomains_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The account the list belongs to. For your own, your own user id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPersonalWorkspaceDomainsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetPersonalWorkspaceDomains200Response**](GetPersonalWorkspaceDomains200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUserAdapterConnections_0

> GetUserAdapterConnections200Response GetUserAdapterConnections_0(ctx, userId).Execute()

See which adapter keys an account has connected



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
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The account whose adapter keys to list. For your own, your own user id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.GetUserAdapterConnections_0(context.Background(), userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.GetUserAdapterConnections_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserAdapterConnections_0`: GetUserAdapterConnections200Response
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.GetUserAdapterConnections_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** | The account whose adapter keys to list. For your own, your own user id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetUserAdapterConnectionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetUserAdapterConnections200Response**](GetUserAdapterConnections200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUserApiKeyUsageLogs_0

> GetUserApiKeyUsageLogsResponse GetUserApiKeyUsageLogs_0(ctx, id, keyId).Limit(limit).Execute()

Read what an API key was used for



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The account the key belongs to
	keyId := "keyId_example" // string | The `keyId` of the key, as the list shows it
	limit := int32(56) // int32 | How many calls to return, newest first (optional) (default to 500)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.GetUserApiKeyUsageLogs_0(context.Background(), id, keyId).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.GetUserApiKeyUsageLogs_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserApiKeyUsageLogs_0`: GetUserApiKeyUsageLogsResponse
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.GetUserApiKeyUsageLogs_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The account the key belongs to | 
**keyId** | **string** | The &#x60;keyId&#x60; of the key, as the list shows it | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetUserApiKeyUsageLogsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **limit** | **int32** | How many calls to return, newest first | [default to 500]

### Return type

[**GetUserApiKeyUsageLogsResponse**](GetUserApiKeyUsageLogsResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUserApiKeys_0

> GetUserApiKeys200Response GetUserApiKeys_0(ctx, id).Execute()

List the API keys of an account



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The account the keys belong to. For your own keys, your own user id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.GetUserApiKeys_0(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.GetUserApiKeys_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserApiKeys_0`: GetUserApiKeys200Response
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.GetUserApiKeys_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The account the keys belong to. For your own keys, your own user id | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetUserApiKeysRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetUserApiKeys200Response**](GetUserApiKeys200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemoveUserAdapterConnection_0

> RemoveUserAdapterConnection200Response RemoveUserAdapterConnection_0(ctx, userId, adapterId, credentialKey).Execute()

Remove an adapter key from an account



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
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The account that keeps the key. For your own, your own user id
	adapterId := "adapterId_example" // string | The adapter the key is for
	credentialKey := "credentialKey_example" // string | The key's name within the adapter

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.RemoveUserAdapterConnection_0(context.Background(), userId, adapterId, credentialKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.RemoveUserAdapterConnection_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemoveUserAdapterConnection_0`: RemoveUserAdapterConnection200Response
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.RemoveUserAdapterConnection_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** | The account that keeps the key. For your own, your own user id | 
**adapterId** | **string** | The adapter the key is for | 
**credentialKey** | **string** | The key&#39;s name within the adapter | 

### Other Parameters

Other parameters are passed through a pointer to a apiRemoveUserAdapterConnectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------




### Return type

[**RemoveUserAdapterConnection200Response**](RemoveUserAdapterConnection200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetUserAdapterConnection_0

> SetUserAdapterConnection200Response SetUserAdapterConnection_0(ctx, userId, adapterId, credentialKey).SetAdapterConnectionRequest(setAdapterConnectionRequest).Execute()

Connect an adapter key to an account



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
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The account that keeps the key. For your own, your own user id
	adapterId := "adapterId_example" // string | The adapter the key is for
	credentialKey := "credentialKey_example" // string | The key's name within the adapter
	setAdapterConnectionRequest := *openapiclient.NewSetAdapterConnectionRequest("YOUR_PROVIDER_KEY") // SetAdapterConnectionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.SetUserAdapterConnection_0(context.Background(), userId, adapterId, credentialKey).SetAdapterConnectionRequest(setAdapterConnectionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.SetUserAdapterConnection_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetUserAdapterConnection_0`: SetUserAdapterConnection200Response
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.SetUserAdapterConnection_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** | The account that keeps the key. For your own, your own user id | 
**adapterId** | **string** | The adapter the key is for | 
**credentialKey** | **string** | The key&#39;s name within the adapter | 

### Other Parameters

Other parameters are passed through a pointer to a apiSetUserAdapterConnectionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **setAdapterConnectionRequest** | [**SetAdapterConnectionRequest**](SetAdapterConnectionRequest.md) |  | 

### Return type

[**SetUserAdapterConnection200Response**](SetUserAdapterConnection200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdatePersonalWorkspaceDomain_0

> PersonalWorkspaceDomainResultResponse UpdatePersonalWorkspaceDomain_0(ctx, id, domainId).UpdateDomainRequest(updateDomainRequest).Execute()

Change a website on your list



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The account the list belongs to. For your own, your own user id
	domainId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The `id` of the entry, as the list shows it
	updateDomainRequest := *openapiclient.NewUpdateDomainRequest("example.com") // UpdateDomainRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.UpdatePersonalWorkspaceDomain_0(context.Background(), id, domainId).UpdateDomainRequest(updateDomainRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.UpdatePersonalWorkspaceDomain_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdatePersonalWorkspaceDomain_0`: PersonalWorkspaceDomainResultResponse
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.UpdatePersonalWorkspaceDomain_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The account the list belongs to. For your own, your own user id | 
**domainId** | **string** | The &#x60;id&#x60; of the entry, as the list shows it | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdatePersonalWorkspaceDomainRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateDomainRequest** | [**UpdateDomainRequest**](UpdateDomainRequest.md) |  | 

### Return type

[**PersonalWorkspaceDomainResultResponse**](PersonalWorkspaceDomainResultResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateUserApiKey_0

> UserApiKeyResponse UpdateUserApiKey_0(ctx, id, keyId).UpdateUserApiKeyRequest(updateUserApiKeyRequest).Execute()

Rename an API key, or switch it off or on



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The account the key belongs to
	keyId := "keyId_example" // string | The `keyId` of the key, as the list shows it
	updateUserApiKeyRequest := *openapiclient.NewUpdateUserApiKeyRequest() // UpdateUserApiKeyRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.UpdateUserApiKey_0(context.Background(), id, keyId).UpdateUserApiKeyRequest(updateUserApiKeyRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.UpdateUserApiKey_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateUserApiKey_0`: UserApiKeyResponse
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.UpdateUserApiKey_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The account the key belongs to | 
**keyId** | **string** | The &#x60;keyId&#x60; of the key, as the list shows it | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateUserApiKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateUserApiKeyRequest** | [**UpdateUserApiKeyRequest**](UpdateUserApiKeyRequest.md) |  | 

### Return type

[**UserApiKeyResponse**](UserApiKeyResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

