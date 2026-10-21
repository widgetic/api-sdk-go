# \WidgetsAPI

All URIs are relative to *https://api.widgetic.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateCompositionFromWidget_0**](WidgetsAPI.md#CreateCompositionFromWidget_0) | **Post** /widgets/{id}/composition | Create a composition for a widget in one call
[**CreateWidget_0**](WidgetsAPI.md#CreateWidget_0) | **Post** /widgets | Create Widget
[**GetWidgetsBatch_0**](WidgetsAPI.md#GetWidgetsBatch_0) | **Post** /widgets/batch | Get Widgets Batch
[**GetWidgets_0**](WidgetsAPI.md#GetWidgets_0) | **Get** /widgets | List Widgets



## CreateCompositionFromWidget_0

> CreateCompositionFromWidget201Response CreateCompositionFromWidget_0(ctx, id).IdempotencyKey(idempotencyKey).CreateCompositionFromWidgetRequest(createCompositionFromWidgetRequest).Execute()

Create a composition for a widget in one call



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The widget id
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	createCompositionFromWidgetRequest := *openapiclient.NewCreateCompositionFromWidgetRequest("Name_example") // CreateCompositionFromWidgetRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WidgetsAPI.CreateCompositionFromWidget_0(context.Background(), id).IdempotencyKey(idempotencyKey).CreateCompositionFromWidgetRequest(createCompositionFromWidgetRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WidgetsAPI.CreateCompositionFromWidget_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateCompositionFromWidget_0`: CreateCompositionFromWidget201Response
	fmt.Fprintf(os.Stdout, "Response from `WidgetsAPI.CreateCompositionFromWidget_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The widget id | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateCompositionFromWidgetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **createCompositionFromWidgetRequest** | [**CreateCompositionFromWidgetRequest**](CreateCompositionFromWidgetRequest.md) |  | 

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


## CreateWidget_0

> CreateWidget201Response CreateWidget_0(ctx).IdempotencyKey(idempotencyKey).CreateWidgetRequest(createWidgetRequest).Execute()

Create Widget



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
	idempotencyKey := "idempotencyKey_example" // string | A unique value (a UUID is fine) that makes a retry of this request safe.
	createWidgetRequest := *openapiclient.NewCreateWidgetRequest("New Chart Widget", "chart", map[string]interface{}{"key": interface{}(123)}) // CreateWidgetRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WidgetsAPI.CreateWidget_0(context.Background()).IdempotencyKey(idempotencyKey).CreateWidgetRequest(createWidgetRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WidgetsAPI.CreateWidget_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateWidget_0`: CreateWidget201Response
	fmt.Fprintf(os.Stdout, "Response from `WidgetsAPI.CreateWidget_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateWidgetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **idempotencyKey** | **string** | A unique value (a UUID is fine) that makes a retry of this request safe. | 
 **createWidgetRequest** | [**CreateWidgetRequest**](CreateWidgetRequest.md) |  | 

### Return type

[**CreateWidget201Response**](CreateWidget201Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetWidgetsBatch_0

> GetWidgetsBatchResponse GetWidgetsBatch_0(ctx).GetWidgetsBatchRequest(getWidgetsBatchRequest).Execute()

Get Widgets Batch



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
	getWidgetsBatchRequest := *openapiclient.NewGetWidgetsBatchRequest([]string{"WidgetIds_example"}) // GetWidgetsBatchRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WidgetsAPI.GetWidgetsBatch_0(context.Background()).GetWidgetsBatchRequest(getWidgetsBatchRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WidgetsAPI.GetWidgetsBatch_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetWidgetsBatch_0`: GetWidgetsBatchResponse
	fmt.Fprintf(os.Stdout, "Response from `WidgetsAPI.GetWidgetsBatch_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetWidgetsBatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **getWidgetsBatchRequest** | [**GetWidgetsBatchRequest**](GetWidgetsBatchRequest.md) |  | 

### Return type

[**GetWidgetsBatchResponse**](GetWidgetsBatchResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetWidgets_0

> GetWidgets200Response GetWidgets_0(ctx).Page(page).Size(size).CanvasId(canvasId).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Execute()

List Widgets



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
	page := int32(56) // int32 | Page to return, counting from 1. Giving `page` or `size` turns paging on. (optional)
	size := int32(56) // int32 | How many widgets a page holds (20 when `page` is given without it). Giving `page` or `size` turns paging on. (optional)
	canvasId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | List only the widgets on this canvas. The list is returned whole. (optional)
	managedUserId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | List only the widgets made for this managed user (Widgetic's id for the user). Send this or `managedUserExternalId`, not both. (optional)
	managedUserExternalId := "managedUserExternalId_example" // string | List only the widgets made for the managed user you registered with this `externalId` (your own identifier for the user). Send this or `managedUserId`, not both. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WidgetsAPI.GetWidgets_0(context.Background()).Page(page).Size(size).CanvasId(canvasId).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WidgetsAPI.GetWidgets_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetWidgets_0`: GetWidgets200Response
	fmt.Fprintf(os.Stdout, "Response from `WidgetsAPI.GetWidgets_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetWidgetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** | Page to return, counting from 1. Giving &#x60;page&#x60; or &#x60;size&#x60; turns paging on. | 
 **size** | **int32** | How many widgets a page holds (20 when &#x60;page&#x60; is given without it). Giving &#x60;page&#x60; or &#x60;size&#x60; turns paging on. | 
 **canvasId** | **string** | List only the widgets on this canvas. The list is returned whole. | 
 **managedUserId** | **string** | List only the widgets made for this managed user (Widgetic&#39;s id for the user). Send this or &#x60;managedUserExternalId&#x60;, not both. | 
 **managedUserExternalId** | **string** | List only the widgets made for the managed user you registered with this &#x60;externalId&#x60; (your own identifier for the user). Send this or &#x60;managedUserId&#x60;, not both. | 

### Return type

[**GetWidgets200Response**](GetWidgets200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

