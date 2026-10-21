# \EntitlementsAPI

All URIs are relative to *https://api.widgetic.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetManagedUserEntitlements_0**](EntitlementsAPI.md#GetManagedUserEntitlements_0) | **Get** /entitlements/managed-users/{managedUserId} | Get managed user entitlements
[**GetPartnerEntitlements_0**](EntitlementsAPI.md#GetPartnerEntitlements_0) | **Get** /entitlements/partners/{partnerId} | Get partner entitlements



## GetManagedUserEntitlements_0

> GetManagedUserEntitlementsResponse GetManagedUserEntitlements_0(ctx, managedUserId).IncludeExpired(includeExpired).Feature(feature).Source(source).Execute()

Get managed user entitlements



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
	managedUserId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Managed user ID
	includeExpired := true // bool | Include expired entitlements in results (optional)
	feature := "feature_example" // string | Filter by specific feature (optional)
	source := "source_example" // string | Filter by entitlement source (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EntitlementsAPI.GetManagedUserEntitlements_0(context.Background(), managedUserId).IncludeExpired(includeExpired).Feature(feature).Source(source).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EntitlementsAPI.GetManagedUserEntitlements_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetManagedUserEntitlements_0`: GetManagedUserEntitlementsResponse
	fmt.Fprintf(os.Stdout, "Response from `EntitlementsAPI.GetManagedUserEntitlements_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**managedUserId** | **string** | Managed user ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetManagedUserEntitlementsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **includeExpired** | **bool** | Include expired entitlements in results | 
 **feature** | **string** | Filter by specific feature | 
 **source** | **string** | Filter by entitlement source | 

### Return type

[**GetManagedUserEntitlementsResponse**](GetManagedUserEntitlementsResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPartnerEntitlements_0

> GetPartnerEntitlementsResponse GetPartnerEntitlements_0(ctx, partnerId).IncludeExpired(includeExpired).Feature(feature).Source(source).Execute()

Get partner entitlements



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Partner ID
	includeExpired := true // bool | Include expired entitlements in results (optional)
	feature := "feature_example" // string | Filter by specific feature (optional)
	source := "source_example" // string | Filter by entitlement source (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EntitlementsAPI.GetPartnerEntitlements_0(context.Background(), partnerId).IncludeExpired(includeExpired).Feature(feature).Source(source).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EntitlementsAPI.GetPartnerEntitlements_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerEntitlements_0`: GetPartnerEntitlementsResponse
	fmt.Fprintf(os.Stdout, "Response from `EntitlementsAPI.GetPartnerEntitlements_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | Partner ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPartnerEntitlementsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **includeExpired** | **bool** | Include expired entitlements in results | 
 **feature** | **string** | Filter by specific feature | 
 **source** | **string** | Filter by entitlement source | 

### Return type

[**GetPartnerEntitlementsResponse**](GetPartnerEntitlementsResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

