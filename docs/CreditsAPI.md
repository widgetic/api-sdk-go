# \CreditsAPI

All URIs are relative to *https://api.widgetic.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetUserCreditBalance_0**](CreditsAPI.md#GetUserCreditBalance_0) | **Get** /credits/user/{userId}/balance | Get an account&#39;s credit balance
[**GetUserCreditTransactions_0**](CreditsAPI.md#GetUserCreditTransactions_0) | **Get** /credits/user/{userId}/transactions | List an account&#39;s credit ledger



## GetUserCreditBalance_0

> AccountCreditBalanceResponse GetUserCreditBalance_0(ctx, userId).Execute()

Get an account's credit balance



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
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The account whose balance to read

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CreditsAPI.GetUserCreditBalance_0(context.Background(), userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CreditsAPI.GetUserCreditBalance_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserCreditBalance_0`: AccountCreditBalanceResponse
	fmt.Fprintf(os.Stdout, "Response from `CreditsAPI.GetUserCreditBalance_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** | The account whose balance to read | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetUserCreditBalanceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AccountCreditBalanceResponse**](AccountCreditBalanceResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUserCreditTransactions_0

> GetPartnerCreditTransactions200Response GetUserCreditTransactions_0(ctx, userId).TransactionType(transactionType).Limit(limit).Offset(offset).Execute()

List an account's credit ledger



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
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The account whose ledger to read
	transactionType := "transactionType_example" // string | Only entries of this type, for instance `debit` for the credits spent. The types are listed on `AccountCreditTransaction`.  (optional)
	limit := int32(56) // int32 | Maximum number of entries to return (optional) (default to 100)
	offset := int32(56) // int32 | Number of entries to skip (optional) (default to 0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CreditsAPI.GetUserCreditTransactions_0(context.Background(), userId).TransactionType(transactionType).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CreditsAPI.GetUserCreditTransactions_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserCreditTransactions_0`: GetPartnerCreditTransactions200Response
	fmt.Fprintf(os.Stdout, "Response from `CreditsAPI.GetUserCreditTransactions_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userId** | **string** | The account whose ledger to read | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetUserCreditTransactionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **transactionType** | **string** | Only entries of this type, for instance &#x60;debit&#x60; for the credits spent. The types are listed on &#x60;AccountCreditTransaction&#x60;.  | 
 **limit** | **int32** | Maximum number of entries to return | [default to 100]
 **offset** | **int32** | Number of entries to skip | [default to 0]

### Return type

[**GetPartnerCreditTransactions200Response**](GetPartnerCreditTransactions200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

