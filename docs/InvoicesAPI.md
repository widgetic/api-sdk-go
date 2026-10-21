# \InvoicesAPI

All URIs are relative to *https://api.widgetic.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetInvoicesByPartnerId_0**](InvoicesAPI.md#GetInvoicesByPartnerId_0) | **Get** /invoices/partner/{partnerId} | List a partner&#39;s invoices



## GetInvoicesByPartnerId_0

> GetInvoicesByPartnerId200Response GetInvoicesByPartnerId_0(ctx, partnerId).Status(status).Limit(limit).Offset(offset).Execute()

List a partner's invoices



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose invoices to list
	status := "status_example" // string | Only invoices with this status (optional)
	limit := int32(56) // int32 | Maximum number of invoices to return (optional) (default to 50)
	offset := int32(56) // int32 | Number of invoices to skip (optional) (default to 0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InvoicesAPI.GetInvoicesByPartnerId_0(context.Background(), partnerId).Status(status).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InvoicesAPI.GetInvoicesByPartnerId_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetInvoicesByPartnerId_0`: GetInvoicesByPartnerId200Response
	fmt.Fprintf(os.Stdout, "Response from `InvoicesAPI.GetInvoicesByPartnerId_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose invoices to list | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetInvoicesByPartnerIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **status** | **string** | Only invoices with this status | 
 **limit** | **int32** | Maximum number of invoices to return | [default to 50]
 **offset** | **int32** | Number of invoices to skip | [default to 0]

### Return type

[**GetInvoicesByPartnerId200Response**](GetInvoicesByPartnerId200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

