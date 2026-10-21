# \UploadsAPI

All URIs are relative to *https://api.widgetic.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**UploadsGet_0**](UploadsAPI.md#UploadsGet_0) | **Get** /uploads | List the account&#39;s uploads
[**UploadsIdDelete_0**](UploadsAPI.md#UploadsIdDelete_0) | **Delete** /uploads/{id} | Delete an upload
[**UploadsIdGet_0**](UploadsAPI.md#UploadsIdGet_0) | **Get** /uploads/{id} | Get an upload by id
[**UploadsLimitsGet_0**](UploadsAPI.md#UploadsLimitsGet_0) | **Get** /uploads/limits | Upload size limits and accepted file types
[**UploadsPost_0**](UploadsAPI.md#UploadsPost_0) | **Post** /uploads | Upload a file



## UploadsGet_0

> UploadsGet200Response UploadsGet_0(ctx).Limit(limit).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Execute()

List the account's uploads



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
	limit := int32(56) // int32 | Maximum number of files to return (optional) (default to 50)
	managedUserId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | List only the files uploaded for this managed user (Widgetic's id for the user). Send this or `managedUserExternalId`, not both. (optional)
	managedUserExternalId := "managedUserExternalId_example" // string | List only the files uploaded for the managed user you registered with this `externalId` (your own identifier for the user). Send this or `managedUserId`, not both. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UploadsAPI.UploadsGet_0(context.Background()).Limit(limit).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UploadsAPI.UploadsGet_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadsGet_0`: UploadsGet200Response
	fmt.Fprintf(os.Stdout, "Response from `UploadsAPI.UploadsGet_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUploadsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** | Maximum number of files to return | [default to 50]
 **managedUserId** | **string** | List only the files uploaded for this managed user (Widgetic&#39;s id for the user). Send this or &#x60;managedUserExternalId&#x60;, not both. | 
 **managedUserExternalId** | **string** | List only the files uploaded for the managed user you registered with this &#x60;externalId&#x60; (your own identifier for the user). Send this or &#x60;managedUserId&#x60;, not both. | 

### Return type

[**UploadsGet200Response**](UploadsGet200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UploadsIdDelete_0

> UploadsIdDelete200Response UploadsIdDelete_0(ctx, id).Execute()

Delete an upload



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
	resp, r, err := apiClient.UploadsAPI.UploadsIdDelete_0(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UploadsAPI.UploadsIdDelete_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadsIdDelete_0`: UploadsIdDelete200Response
	fmt.Fprintf(os.Stdout, "Response from `UploadsAPI.UploadsIdDelete_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUploadsIdDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**UploadsIdDelete200Response**](UploadsIdDelete200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UploadsIdGet_0

> UploadResponse UploadsIdGet_0(ctx, id).Execute()

Get an upload by id



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The upload to read

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UploadsAPI.UploadsIdGet_0(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UploadsAPI.UploadsIdGet_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadsIdGet_0`: UploadResponse
	fmt.Fprintf(os.Stdout, "Response from `UploadsAPI.UploadsIdGet_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The upload to read | 

### Other Parameters

Other parameters are passed through a pointer to a apiUploadsIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**UploadResponse**](UploadResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UploadsLimitsGet_0

> UploadLimitsResponse UploadsLimitsGet_0(ctx).Execute()

Upload size limits and accepted file types



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UploadsAPI.UploadsLimitsGet_0(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UploadsAPI.UploadsLimitsGet_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadsLimitsGet_0`: UploadLimitsResponse
	fmt.Fprintf(os.Stdout, "Response from `UploadsAPI.UploadsLimitsGet_0`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiUploadsLimitsGetRequest struct via the builder pattern


### Return type

[**UploadLimitsResponse**](UploadLimitsResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UploadsPost_0

> UploadResponse UploadsPost_0(ctx).File(file).ContextType(contextType).Source(source).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Purpose(purpose).Execute()

Upload a file



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
	file := os.NewFile(1234, "some_file") // *os.File | The file to store
	contextType := "contextType_example" // string | What the file is for. Send `content-property` for media that becomes widget content (images, video and PDF); the other values are used by Widgetic's own editor.  (optional) (default to "content-property")
	source := "source_example" // string | Which part of the product, or which client, the file comes from (optional) (default to "file-browser-upload")
	managedUserId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Upload the file for one of your managed users, by Widgetic's id for the user. Send this or `managedUserExternalId`, not both. (optional)
	managedUserExternalId := "managedUserExternalId_example" // string | The same, by your own identifier for the user, the `externalId` you gave when you created the managed user. Send this or `managedUserId`, not both. (optional)
	purpose := "purpose_example" // string | Where in your product you use the file. It is kept with the file, so that a customer's storage can be counted by purpose (`getManagedUserStorageUsage`). Optional; any other value is refused with 400 and `UPLOAD_INVALID_PURPOSE`. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UploadsAPI.UploadsPost_0(context.Background()).File(file).ContextType(contextType).Source(source).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Purpose(purpose).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UploadsAPI.UploadsPost_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadsPost_0`: UploadResponse
	fmt.Fprintf(os.Stdout, "Response from `UploadsAPI.UploadsPost_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUploadsPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **file** | ***os.File** | The file to store | 
 **contextType** | **string** | What the file is for. Send &#x60;content-property&#x60; for media that becomes widget content (images, video and PDF); the other values are used by Widgetic&#39;s own editor.  | [default to &quot;content-property&quot;]
 **source** | **string** | Which part of the product, or which client, the file comes from | [default to &quot;file-browser-upload&quot;]
 **managedUserId** | **string** | Upload the file for one of your managed users, by Widgetic&#39;s id for the user. Send this or &#x60;managedUserExternalId&#x60;, not both. | 
 **managedUserExternalId** | **string** | The same, by your own identifier for the user, the &#x60;externalId&#x60; you gave when you created the managed user. Send this or &#x60;managedUserId&#x60;, not both. | 
 **purpose** | **string** | Where in your product you use the file. It is kept with the file, so that a customer&#39;s storage can be counted by purpose (&#x60;getManagedUserStorageUsage&#x60;). Optional; any other value is refused with 400 and &#x60;UPLOAD_INVALID_PURPOSE&#x60;. | 

### Return type

[**UploadResponse**](UploadResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

