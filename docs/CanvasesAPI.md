# \CanvasesAPI

All URIs are relative to *https://api.widgetic.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateCanvas_0**](CanvasesAPI.md#CreateCanvas_0) | **Post** /canvases | Create Canvas
[**DeleteCanvas_0**](CanvasesAPI.md#DeleteCanvas_0) | **Delete** /canvases/{id} | Delete Canvas
[**GetAllCanvases_0**](CanvasesAPI.md#GetAllCanvases_0) | **Get** /canvases | Get All Canvases
[**GetCanvas_0**](CanvasesAPI.md#GetCanvas_0) | **Get** /canvases/{id} | Get Canvas
[**UpdateCanvas_0**](CanvasesAPI.md#UpdateCanvas_0) | **Put** /canvases/{id} | Update Canvas



## CreateCanvas_0

> CanvasResponse CreateCanvas_0(ctx).CreateCanvasRequest(createCanvasRequest).Execute()

Create Canvas



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
	createCanvasRequest := *openapiclient.NewCreateCanvasRequest("canvas_xyz123") // CreateCanvasRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CanvasesAPI.CreateCanvas_0(context.Background()).CreateCanvasRequest(createCanvasRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CanvasesAPI.CreateCanvas_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateCanvas_0`: CanvasResponse
	fmt.Fprintf(os.Stdout, "Response from `CanvasesAPI.CreateCanvas_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateCanvasRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createCanvasRequest** | [**CreateCanvasRequest**](CreateCanvasRequest.md) |  | 

### Return type

[**CanvasResponse**](CanvasResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteCanvas_0

> CanvasResponse DeleteCanvas_0(ctx, id).Execute()

Delete Canvas



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the canvas

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CanvasesAPI.DeleteCanvas_0(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CanvasesAPI.DeleteCanvas_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteCanvas_0`: CanvasResponse
	fmt.Fprintf(os.Stdout, "Response from `CanvasesAPI.DeleteCanvas_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the canvas | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteCanvasRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CanvasResponse**](CanvasResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAllCanvases_0

> GetAllCanvasesResponse GetAllCanvases_0(ctx).Page(page).Size(size).Sort(sort).CreatedAfter(createdAfter).CreatedBefore(createdBefore).UpdatedAfter(updatedAfter).UpdatedBefore(updatedBefore).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Execute()

Get All Canvases



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/widgetic/api-sdk-go"
)

func main() {
	page := int32(56) // int32 | Page number for pagination (optional) (default to 1)
	size := int32(56) // int32 | Number of items per page (optional) (default to 20)
	sort := "sort_example" // string | Sort field and direction (e.g., \"created_at:desc\") (optional) (default to "created_at:desc")
	createdAfter := time.Now() // time.Time | Filter canvases created after the specified date (ISO 8601 format) (optional)
	createdBefore := time.Now() // time.Time | Filter canvases created before the specified date (ISO 8601 format) (optional)
	updatedAfter := time.Now() // time.Time | Filter canvases updated after the specified date (ISO 8601 format) (optional)
	updatedBefore := time.Now() // time.Time | Filter canvases updated before the specified date (ISO 8601 format) (optional)
	managedUserId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | List only the canvases made for this managed user (Widgetic's id for the user). Send this or `managedUserExternalId`, not both. (optional)
	managedUserExternalId := "managedUserExternalId_example" // string | List only the canvases made for the managed user you registered with this `externalId` (your own identifier for the user). Send this or `managedUserId`, not both. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CanvasesAPI.GetAllCanvases_0(context.Background()).Page(page).Size(size).Sort(sort).CreatedAfter(createdAfter).CreatedBefore(createdBefore).UpdatedAfter(updatedAfter).UpdatedBefore(updatedBefore).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CanvasesAPI.GetAllCanvases_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAllCanvases_0`: GetAllCanvasesResponse
	fmt.Fprintf(os.Stdout, "Response from `CanvasesAPI.GetAllCanvases_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAllCanvasesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** | Page number for pagination | [default to 1]
 **size** | **int32** | Number of items per page | [default to 20]
 **sort** | **string** | Sort field and direction (e.g., \&quot;created_at:desc\&quot;) | [default to &quot;created_at:desc&quot;]
 **createdAfter** | **time.Time** | Filter canvases created after the specified date (ISO 8601 format) | 
 **createdBefore** | **time.Time** | Filter canvases created before the specified date (ISO 8601 format) | 
 **updatedAfter** | **time.Time** | Filter canvases updated after the specified date (ISO 8601 format) | 
 **updatedBefore** | **time.Time** | Filter canvases updated before the specified date (ISO 8601 format) | 
 **managedUserId** | **string** | List only the canvases made for this managed user (Widgetic&#39;s id for the user). Send this or &#x60;managedUserExternalId&#x60;, not both. | 
 **managedUserExternalId** | **string** | List only the canvases made for the managed user you registered with this &#x60;externalId&#x60; (your own identifier for the user). Send this or &#x60;managedUserId&#x60;, not both. | 

### Return type

[**GetAllCanvasesResponse**](GetAllCanvasesResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCanvas_0

> CanvasResponse GetCanvas_0(ctx, id).Execute()

Get Canvas



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the canvas

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CanvasesAPI.GetCanvas_0(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CanvasesAPI.GetCanvas_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCanvas_0`: CanvasResponse
	fmt.Fprintf(os.Stdout, "Response from `CanvasesAPI.GetCanvas_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the canvas | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCanvasRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CanvasResponse**](CanvasResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateCanvas_0

> CanvasResponse UpdateCanvas_0(ctx, id).UpdateCanvasRequest(updateCanvasRequest).Execute()

Update Canvas



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the canvas to update
	updateCanvasRequest := *openapiclient.NewUpdateCanvasRequest() // UpdateCanvasRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CanvasesAPI.UpdateCanvas_0(context.Background(), id).UpdateCanvasRequest(updateCanvasRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CanvasesAPI.UpdateCanvas_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateCanvas_0`: CanvasResponse
	fmt.Fprintf(os.Stdout, "Response from `CanvasesAPI.UpdateCanvas_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the canvas to update | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateCanvasRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateCanvasRequest** | [**UpdateCanvasRequest**](UpdateCanvasRequest.md) |  | 

### Return type

[**CanvasResponse**](CanvasResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

