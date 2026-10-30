# \PublicEmbedAPI

All URIs are relative to *https://api.widgetic.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CallPublicCompositionAdapter_0**](PublicEmbedAPI.md#CallPublicCompositionAdapter_0) | **Post** /embed/compositions/{compositionId}/adapters/{adapterId}/{operation} | Call a gateway operation of an adapter a published widget uses
[**CreatePublicCompositionEntry_0**](PublicEmbedAPI.md#CreatePublicCompositionEntry_0) | **Post** /embed/compositions/{compositionId}/entries/{table} | Append a visitor entry through the gateway
[**GetPublicCompositionEmbed_0**](PublicEmbedAPI.md#GetPublicCompositionEmbed_0) | **Get** /embed/compositions/{compositionId} | Resolve a composition UUID to a published widget URL
[**GetPublicCompositionIframe_0**](PublicEmbedAPI.md#GetPublicCompositionIframe_0) | **Get** /embed/compositions/{compositionId}/frame | Embed a published composition with its saved values
[**GetPublicWorkflowFrame_0**](PublicEmbedAPI.md#GetPublicWorkflowFrame_0) | **Get** /embed/workflows/{workflowId}/frame | Show a published Workflow in a page of its own
[**GetPublicWorkflowVersion_0**](PublicEmbedAPI.md#GetPublicWorkflowVersion_0) | **Get** /embed/workflows/{workflowId}/versions/{versionId} | Read one published version of a Workflow
[**GetPublicWorkflow_0**](PublicEmbedAPI.md#GetPublicWorkflow_0) | **Get** /embed/workflows/{workflowId} | Read the published Workflow of an embed
[**PostPublicCompositionEmbedStatus_0**](PublicEmbedAPI.md#PostPublicCompositionEmbedStatus_0) | **Post** /embed/compositions/status | Batch-check whether compositions are currently served for embed
[**ReportPublicWorkflowEvents_0**](PublicEmbedAPI.md#ReportPublicWorkflowEvents_0) | **Post** /embed/workflows/{workflowId}/events | Report what visitors did in a Workflow, as counts
[**UploadPublicCompositionAdapterFile_0**](PublicEmbedAPI.md#UploadPublicCompositionAdapterFile_0) | **Put** /embed/compositions/{compositionId}/adapters/upload/files/{ticket} | Send the file a visitor chose through the upload adapter of a published widget



## CallPublicCompositionAdapter_0

> PublicAdapterCallResult CallPublicCompositionAdapter_0(ctx, compositionId, adapterId, operation).PublicAdapterCallRequest(publicAdapterCallRequest).Execute()

Call a gateway operation of an adapter a published widget uses



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
	compositionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	adapterId := "adapterId_example" // string | The id of the adapter, the name its module is known by, for example `upload`.
	operation := "operation_example" // string | The name of one operation of the adapter, as its documentation gives it.
	publicAdapterCallRequest := *openapiclient.NewPublicAdapterCallRequest("RequestId_example") // PublicAdapterCallRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicEmbedAPI.CallPublicCompositionAdapter_0(context.Background(), compositionId, adapterId, operation).PublicAdapterCallRequest(publicAdapterCallRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicEmbedAPI.CallPublicCompositionAdapter_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CallPublicCompositionAdapter_0`: PublicAdapterCallResult
	fmt.Fprintf(os.Stdout, "Response from `PublicEmbedAPI.CallPublicCompositionAdapter_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**compositionId** | **string** |  | 
**adapterId** | **string** | The id of the adapter, the name its module is known by, for example &#x60;upload&#x60;. | 
**operation** | **string** | The name of one operation of the adapter, as its documentation gives it. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCallPublicCompositionAdapterRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **publicAdapterCallRequest** | [**PublicAdapterCallRequest**](PublicAdapterCallRequest.md) |  | 

### Return type

[**PublicAdapterCallResult**](PublicAdapterCallResult.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreatePublicCompositionEntry_0

> PublicCompositionEntryCreated CreatePublicCompositionEntry_0(ctx, compositionId, table).PublicCompositionEntryRequest(publicCompositionEntryRequest).XWidgeticWriteToken(xWidgeticWriteToken).XWidgeticVisitorId(xWidgeticVisitorId).Execute()

Append a visitor entry through the gateway



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
	compositionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	table := "table_example" // string | 
	publicCompositionEntryRequest := *openapiclient.NewPublicCompositionEntryRequest(map[string]interface{}{"key": interface{}(123)}) // PublicCompositionEntryRequest | 
	xWidgeticWriteToken := "xWidgeticWriteToken_example" // string | Signed per-composition write token handed to the widget in `widgetic:host` as `entries.writeToken` (and returned by `GET /embed/compositions/{compositionId}` as `entryWriteToken`). Required when the request comes from the shared Widgetic artifact origin; verified whenever present. (optional)
	xWidgeticVisitorId := "xWidgeticVisitorId_example" // string | A random id the widget's browser makes once and keeps (16 to 64 characters of `A-Za-z0-9_-`), sent so a table's per-visitor `limit` (declared in the widget database file) can count this browser. Not an identity and not a secret. Without it, or with a malformed value, the limit counts only by network address. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicEmbedAPI.CreatePublicCompositionEntry_0(context.Background(), compositionId, table).PublicCompositionEntryRequest(publicCompositionEntryRequest).XWidgeticWriteToken(xWidgeticWriteToken).XWidgeticVisitorId(xWidgeticVisitorId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicEmbedAPI.CreatePublicCompositionEntry_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreatePublicCompositionEntry_0`: PublicCompositionEntryCreated
	fmt.Fprintf(os.Stdout, "Response from `PublicEmbedAPI.CreatePublicCompositionEntry_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**compositionId** | **string** |  | 
**table** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreatePublicCompositionEntryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **publicCompositionEntryRequest** | [**PublicCompositionEntryRequest**](PublicCompositionEntryRequest.md) |  | 
 **xWidgeticWriteToken** | **string** | Signed per-composition write token handed to the widget in &#x60;widgetic:host&#x60; as &#x60;entries.writeToken&#x60; (and returned by &#x60;GET /embed/compositions/{compositionId}&#x60; as &#x60;entryWriteToken&#x60;). Required when the request comes from the shared Widgetic artifact origin; verified whenever present. | 
 **xWidgeticVisitorId** | **string** | A random id the widget&#39;s browser makes once and keeps (16 to 64 characters of &#x60;A-Za-z0-9_-&#x60;), sent so a table&#39;s per-visitor &#x60;limit&#x60; (declared in the widget database file) can count this browser. Not an identity and not a secret. Without it, or with a malformed value, the limit counts only by network address. | 

### Return type

[**PublicCompositionEntryCreated**](PublicCompositionEntryCreated.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPublicCompositionEmbed_0

> GetPublicCompositionEmbed200Response GetPublicCompositionEmbed_0(ctx, compositionId).Execute()

Resolve a composition UUID to a published widget URL



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
	compositionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicEmbedAPI.GetPublicCompositionEmbed_0(context.Background(), compositionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicEmbedAPI.GetPublicCompositionEmbed_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPublicCompositionEmbed_0`: GetPublicCompositionEmbed200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicEmbedAPI.GetPublicCompositionEmbed_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**compositionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPublicCompositionEmbedRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetPublicCompositionEmbed200Response**](GetPublicCompositionEmbed200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPublicCompositionIframe_0

> string GetPublicCompositionIframe_0(ctx, compositionId).Execute()

Embed a published composition with its saved values



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
	compositionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicEmbedAPI.GetPublicCompositionIframe_0(context.Background(), compositionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicEmbedAPI.GetPublicCompositionIframe_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPublicCompositionIframe_0`: string
	fmt.Fprintf(os.Stdout, "Response from `PublicEmbedAPI.GetPublicCompositionIframe_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**compositionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPublicCompositionIframeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/html, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPublicWorkflowFrame_0

> string GetPublicWorkflowFrame_0(ctx, workflowId).Execute()

Show a published Workflow in a page of its own



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
	workflowId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicEmbedAPI.GetPublicWorkflowFrame_0(context.Background(), workflowId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicEmbedAPI.GetPublicWorkflowFrame_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPublicWorkflowFrame_0`: string
	fmt.Fprintf(os.Stdout, "Response from `PublicEmbedAPI.GetPublicWorkflowFrame_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workflowId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPublicWorkflowFrameRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/html, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPublicWorkflowVersion_0

> GetPublicWorkflow200Response GetPublicWorkflowVersion_0(ctx, workflowId, versionId).Execute()

Read one published version of a Workflow



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
	workflowId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	versionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicEmbedAPI.GetPublicWorkflowVersion_0(context.Background(), workflowId, versionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicEmbedAPI.GetPublicWorkflowVersion_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPublicWorkflowVersion_0`: GetPublicWorkflow200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicEmbedAPI.GetPublicWorkflowVersion_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workflowId** | **string** |  | 
**versionId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPublicWorkflowVersionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**GetPublicWorkflow200Response**](GetPublicWorkflow200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPublicWorkflow_0

> GetPublicWorkflow200Response GetPublicWorkflow_0(ctx, workflowId).Execute()

Read the published Workflow of an embed



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
	workflowId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicEmbedAPI.GetPublicWorkflow_0(context.Background(), workflowId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicEmbedAPI.GetPublicWorkflow_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPublicWorkflow_0`: GetPublicWorkflow200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicEmbedAPI.GetPublicWorkflow_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workflowId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPublicWorkflowRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetPublicWorkflow200Response**](GetPublicWorkflow200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostPublicCompositionEmbedStatus_0

> PostPublicCompositionEmbedStatus200Response PostPublicCompositionEmbedStatus_0(ctx).PostPublicCompositionEmbedStatusRequest(postPublicCompositionEmbedStatusRequest).Execute()

Batch-check whether compositions are currently served for embed



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
	postPublicCompositionEmbedStatusRequest := *openapiclient.NewPostPublicCompositionEmbedStatusRequest([]string{"Ids_example"}) // PostPublicCompositionEmbedStatusRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicEmbedAPI.PostPublicCompositionEmbedStatus_0(context.Background()).PostPublicCompositionEmbedStatusRequest(postPublicCompositionEmbedStatusRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicEmbedAPI.PostPublicCompositionEmbedStatus_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostPublicCompositionEmbedStatus_0`: PostPublicCompositionEmbedStatus200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicEmbedAPI.PostPublicCompositionEmbedStatus_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostPublicCompositionEmbedStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **postPublicCompositionEmbedStatusRequest** | [**PostPublicCompositionEmbedStatusRequest**](PostPublicCompositionEmbedStatusRequest.md) |  | 

### Return type

[**PostPublicCompositionEmbedStatus200Response**](PostPublicCompositionEmbedStatus200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReportPublicWorkflowEvents_0

> ReportPublicWorkflowEvents200Response ReportPublicWorkflowEvents_0(ctx, workflowId).PublicWorkflowEventsRequest(publicWorkflowEventsRequest).Execute()

Report what visitors did in a Workflow, as counts



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
	workflowId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	publicWorkflowEventsRequest := *openapiclient.NewPublicWorkflowEventsRequest("VersionId_example", "Token_example") // PublicWorkflowEventsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicEmbedAPI.ReportPublicWorkflowEvents_0(context.Background(), workflowId).PublicWorkflowEventsRequest(publicWorkflowEventsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicEmbedAPI.ReportPublicWorkflowEvents_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReportPublicWorkflowEvents_0`: ReportPublicWorkflowEvents200Response
	fmt.Fprintf(os.Stdout, "Response from `PublicEmbedAPI.ReportPublicWorkflowEvents_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workflowId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiReportPublicWorkflowEventsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **publicWorkflowEventsRequest** | [**PublicWorkflowEventsRequest**](PublicWorkflowEventsRequest.md) |  | 

### Return type

[**ReportPublicWorkflowEvents200Response**](ReportPublicWorkflowEvents200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/plain
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UploadPublicCompositionAdapterFile_0

> PublicAdapterFileResult UploadPublicCompositionAdapterFile_0(ctx, compositionId, ticket).Body(body).Execute()

Send the file a visitor chose through the upload adapter of a published widget



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
	compositionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	ticket := "ticket_example" // string | The ticket the `begin-upload` operation answered with.
	body := os.NewFile(1234, "some_file") // *os.File | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PublicEmbedAPI.UploadPublicCompositionAdapterFile_0(context.Background(), compositionId, ticket).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PublicEmbedAPI.UploadPublicCompositionAdapterFile_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadPublicCompositionAdapterFile_0`: PublicAdapterFileResult
	fmt.Fprintf(os.Stdout, "Response from `PublicEmbedAPI.UploadPublicCompositionAdapterFile_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**compositionId** | **string** |  | 
**ticket** | **string** | The ticket the &#x60;begin-upload&#x60; operation answered with. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUploadPublicCompositionAdapterFileRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **body** | ***os.File** |  | 

### Return type

[**PublicAdapterFileResult**](PublicAdapterFileResult.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/pdf, audio/aac, audio/flac, audio/mp4, audio/mpeg, audio/ogg, audio/wav, audio/webm, image/gif, image/heic, image/heif, image/jpeg, image/png, image/webp, video/mp4, video/quicktime, video/webm
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

