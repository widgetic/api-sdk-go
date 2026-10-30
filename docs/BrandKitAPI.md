# \BrandKitAPI

All URIs are relative to *https://api.widgetic.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DeleteBrandKitAsset_0**](BrandKitAPI.md#DeleteBrandKitAsset_0) | **Delete** /brand-kit/assets/{assetId} | Remove a font or icon from the Brand Kit
[**DeleteBrandKit_0**](BrandKitAPI.md#DeleteBrandKit_0) | **Delete** /brand-kit | Reset the Brand Kit to the default
[**GetBrandKit_0**](BrandKitAPI.md#GetBrandKit_0) | **Get** /brand-kit | The Brand Kit of the current workspace
[**PatchBrandKitAsset_0**](BrandKitAPI.md#PatchBrandKitAsset_0) | **Patch** /brand-kit/assets/{assetId} | Rename an icon or relabel a font variant
[**PatchBrandKit_0**](BrandKitAPI.md#PatchBrandKit_0) | **Patch** /brand-kit | Change part of the Brand Kit
[**PostBrandKitFont_0**](BrandKitAPI.md#PostBrandKitFont_0) | **Post** /brand-kit/fonts | Upload a font file to the Brand Kit
[**PostBrandKitIcon_0**](BrandKitAPI.md#PostBrandKitIcon_0) | **Post** /brand-kit/icons | Add a named SVG icon to the Brand Kit
[**PutBrandKit_0**](BrandKitAPI.md#PutBrandKit_0) | **Put** /brand-kit | Save Brand Kit tokens



## DeleteBrandKitAsset_0

> BrandKitViewResponse DeleteBrandKitAsset_0(ctx, assetId).OrganizationId(organizationId).Execute()

Remove a font or icon from the Brand Kit

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
	assetId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandKitAPI.DeleteBrandKitAsset_0(context.Background(), assetId).OrganizationId(organizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandKitAPI.DeleteBrandKitAsset_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteBrandKitAsset_0`: BrandKitViewResponse
	fmt.Fprintf(os.Stdout, "Response from `BrandKitAPI.DeleteBrandKitAsset_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**assetId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteBrandKitAssetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **organizationId** | **string** |  | 

### Return type

[**BrandKitViewResponse**](BrandKitViewResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteBrandKit_0

> BrandKitViewResponse DeleteBrandKit_0(ctx).OrganizationId(organizationId).Execute()

Reset the Brand Kit to the default

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
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandKitAPI.DeleteBrandKit_0(context.Background()).OrganizationId(organizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandKitAPI.DeleteBrandKit_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteBrandKit_0`: BrandKitViewResponse
	fmt.Fprintf(os.Stdout, "Response from `BrandKitAPI.DeleteBrandKit_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDeleteBrandKitRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **organizationId** | **string** |  | 

### Return type

[**BrandKitViewResponse**](BrandKitViewResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetBrandKit_0

> BrandKitViewResponse GetBrandKit_0(ctx).OrganizationId(organizationId).Execute()

The Brand Kit of the current workspace



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
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | An organisation's kit; omit for the caller's current workspace. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandKitAPI.GetBrandKit_0(context.Background()).OrganizationId(organizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandKitAPI.GetBrandKit_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetBrandKit_0`: BrandKitViewResponse
	fmt.Fprintf(os.Stdout, "Response from `BrandKitAPI.GetBrandKit_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetBrandKitRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **organizationId** | **string** | An organisation&#39;s kit; omit for the caller&#39;s current workspace. | 

### Return type

[**BrandKitViewResponse**](BrandKitViewResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PatchBrandKitAsset_0

> BrandKitViewResponse PatchBrandKitAsset_0(ctx, assetId).PatchBrandKitAssetRequest(patchBrandKitAssetRequest).OrganizationId(organizationId).Execute()

Rename an icon or relabel a font variant

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
	assetId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	patchBrandKitAssetRequest := *openapiclient.NewPatchBrandKitAssetRequest() // PatchBrandKitAssetRequest | 
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandKitAPI.PatchBrandKitAsset_0(context.Background(), assetId).PatchBrandKitAssetRequest(patchBrandKitAssetRequest).OrganizationId(organizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandKitAPI.PatchBrandKitAsset_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PatchBrandKitAsset_0`: BrandKitViewResponse
	fmt.Fprintf(os.Stdout, "Response from `BrandKitAPI.PatchBrandKitAsset_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**assetId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPatchBrandKitAssetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **patchBrandKitAssetRequest** | [**PatchBrandKitAssetRequest**](PatchBrandKitAssetRequest.md) |  | 
 **organizationId** | **string** |  | 

### Return type

[**BrandKitViewResponse**](BrandKitViewResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PatchBrandKit_0

> BrandKitViewResponse PatchBrandKit_0(ctx).PatchBrandKitRequest(patchBrandKitRequest).OrganizationId(organizationId).Execute()

Change part of the Brand Kit



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
	patchBrandKitRequest := *openapiclient.NewPatchBrandKitRequest() // PatchBrandKitRequest | 
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandKitAPI.PatchBrandKit_0(context.Background()).PatchBrandKitRequest(patchBrandKitRequest).OrganizationId(organizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandKitAPI.PatchBrandKit_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PatchBrandKit_0`: BrandKitViewResponse
	fmt.Fprintf(os.Stdout, "Response from `BrandKitAPI.PatchBrandKit_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPatchBrandKitRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **patchBrandKitRequest** | [**PatchBrandKitRequest**](PatchBrandKitRequest.md) |  | 
 **organizationId** | **string** |  | 

### Return type

[**BrandKitViewResponse**](BrandKitViewResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostBrandKitFont_0

> BrandKitViewResponse PostBrandKitFont_0(ctx).File(file).Family(family).Weight(weight).OrganizationId(organizationId).Style(style).Execute()

Upload a font file to the Brand Kit

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
	file := os.NewFile(1234, "some_file") // *os.File | 
	family := "family_example" // string | 
	weight := int32(56) // int32 | 
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	style := "style_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandKitAPI.PostBrandKitFont_0(context.Background()).File(file).Family(family).Weight(weight).OrganizationId(organizationId).Style(style).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandKitAPI.PostBrandKitFont_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostBrandKitFont_0`: BrandKitViewResponse
	fmt.Fprintf(os.Stdout, "Response from `BrandKitAPI.PostBrandKitFont_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostBrandKitFontRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **file** | ***os.File** |  | 
 **family** | **string** |  | 
 **weight** | **int32** |  | 
 **organizationId** | **string** |  | 
 **style** | **string** |  | 

### Return type

[**BrandKitViewResponse**](BrandKitViewResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostBrandKitIcon_0

> BrandKitViewResponse PostBrandKitIcon_0(ctx).PostBrandKitIconRequest(postBrandKitIconRequest).OrganizationId(organizationId).Execute()

Add a named SVG icon to the Brand Kit

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
	postBrandKitIconRequest := *openapiclient.NewPostBrandKitIconRequest("Name_example", "Svg_example") // PostBrandKitIconRequest | 
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandKitAPI.PostBrandKitIcon_0(context.Background()).PostBrandKitIconRequest(postBrandKitIconRequest).OrganizationId(organizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandKitAPI.PostBrandKitIcon_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostBrandKitIcon_0`: BrandKitViewResponse
	fmt.Fprintf(os.Stdout, "Response from `BrandKitAPI.PostBrandKitIcon_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostBrandKitIconRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **postBrandKitIconRequest** | [**PostBrandKitIconRequest**](PostBrandKitIconRequest.md) |  | 
 **organizationId** | **string** |  | 

### Return type

[**BrandKitViewResponse**](BrandKitViewResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PutBrandKit_0

> BrandKitViewResponse PutBrandKit_0(ctx).PutBrandKitRequest(putBrandKitRequest).OrganizationId(organizationId).Execute()

Save Brand Kit tokens



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
	putBrandKitRequest := *openapiclient.NewPutBrandKitRequest(*openapiclient.NewBrandKitTokens([]openapiclient.BrandColor{*openapiclient.NewBrandColor("Name_example", "Hex_example")}, *openapiclient.NewBrandKitTokensFonts(), *openapiclient.NewBrandSpacing(int32(123), int32(123), int32(123), int32(123), int32(123), int32(123), int32(123), int32(123)))) // PutBrandKitRequest | 
	organizationId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BrandKitAPI.PutBrandKit_0(context.Background()).PutBrandKitRequest(putBrandKitRequest).OrganizationId(organizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BrandKitAPI.PutBrandKit_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PutBrandKit_0`: BrandKitViewResponse
	fmt.Fprintf(os.Stdout, "Response from `BrandKitAPI.PutBrandKit_0`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPutBrandKitRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **putBrandKitRequest** | [**PutBrandKitRequest**](PutBrandKitRequest.md) |  | 
 **organizationId** | **string** |  | 

### Return type

[**BrandKitViewResponse**](BrandKitViewResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

