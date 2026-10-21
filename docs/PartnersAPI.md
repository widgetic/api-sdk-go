# \PartnersAPI

All URIs are relative to *https://api.widgetic.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreatePartnerExtraCreditsInvoice_0**](PartnersAPI.md#CreatePartnerExtraCreditsInvoice_0) | **Post** /partners/{partnerId}/credits/extra-invoice | Buy extra credits for a partner
[**GetMyPartners_0**](PartnersAPI.md#GetMyPartners_0) | **Get** /partners/mine | Find the partner you administer
[**GetPartnerAdapterConnections_0**](PartnersAPI.md#GetPartnerAdapterConnections_0) | **Get** /partners/{partnerId}/adapter-connections | See which adapter keys a partner has connected
[**GetPartnerAnalyticsByManagedUser_0**](PartnersAPI.md#GetPartnerAnalyticsByManagedUser_0) | **Get** /partners/{partnerId}/analytics/managed-users | What each managed user&#39;s widgets did
[**GetPartnerAnalyticsSummary_0**](PartnersAPI.md#GetPartnerAnalyticsSummary_0) | **Get** /partners/{partnerId}/analytics/summary | What was done with a partner&#39;s published widgets
[**GetPartnerAnalyticsTimeline_0**](PartnersAPI.md#GetPartnerAnalyticsTimeline_0) | **Get** /partners/{partnerId}/analytics/timeline | What was done with a partner&#39;s widgets, day by day
[**GetPartnerAnalyticsTopWidgets_0**](PartnersAPI.md#GetPartnerAnalyticsTopWidgets_0) | **Get** /partners/{partnerId}/analytics/top-widgets | Which widgets were viewed the most
[**GetPartnerBillingOverview_0**](PartnersAPI.md#GetPartnerBillingOverview_0) | **Get** /partners/{partnerId}/billing-overview | Get comprehensive partner billing overview
[**GetPartnerContract_0**](PartnersAPI.md#GetPartnerContract_0) | **Get** /partners/{partnerId}/contract | Get a partner&#39;s contract
[**GetPartnerCreditBalance_0**](PartnersAPI.md#GetPartnerCreditBalance_0) | **Get** /partners/{partnerId}/credits/balance | Get partner credit balance
[**GetPartnerCreditTransactions_0**](PartnersAPI.md#GetPartnerCreditTransactions_0) | **Get** /partners/{partnerId}/credits/transactions | Get partner credit transaction history
[**GetPartnerDataDatabase_0**](PartnersAPI.md#GetPartnerDataDatabase_0) | **Get** /partners/{partnerId}/data-database | See the Neon database a partner keeps the data of its compositions in
[**GetPartnerDesignDefaults_0**](PartnersAPI.md#GetPartnerDesignDefaults_0) | **Get** /partners/{partnerId}/design-defaults | Read partner-wide design defaults
[**GetPartnerEntryContextSigning_0**](PartnersAPI.md#GetPartnerEntryContextSigning_0) | **Get** /partners/{partnerId}/entry-context-signing | See how the context of your embeds is signed
[**GetPartnerNotificationSettings_0**](PartnersAPI.md#GetPartnerNotificationSettings_0) | **Get** /partners/{partnerId}/notifications/settings | Where your notifications go
[**GetPartnerStorageDestination_0**](PartnersAPI.md#GetPartnerStorageDestination_0) | **Get** /partners/{partnerId}/storage | Get where a partner&#39;s uploaded files are stored
[**GetPartnerStorageUsage_0**](PartnersAPI.md#GetPartnerStorageUsage_0) | **Get** /partners/{partnerId}/storage/usage | What a partner&#39;s customers store
[**ListPartnerNotificationDeliveries_0**](PartnersAPI.md#ListPartnerNotificationDeliveries_0) | **Get** /partners/{partnerId}/notifications/deliveries | How your notifications reached you
[**ListPartnerNotifications_0**](PartnersAPI.md#ListPartnerNotifications_0) | **Get** /partners/{partnerId}/notifications | What your partner account was told
[**ListPartnerPresets_0**](PartnersAPI.md#ListPartnerPresets_0) | **Get** /partners/{partnerId}/presets | List the widgets a partner offers as presets
[**RemovePartnerAdapterConnection_0**](PartnersAPI.md#RemovePartnerAdapterConnection_0) | **Delete** /partners/{partnerId}/adapter-connections/{adapterId}/{credentialKey} | Remove an adapter key from a partner
[**RemovePartnerDataDatabase_0**](PartnersAPI.md#RemovePartnerDataDatabase_0) | **Delete** /partners/{partnerId}/data-database | Stop keeping the data of a partner&#39;s compositions in its own database
[**RemovePartnerPreset_0**](PartnersAPI.md#RemovePartnerPreset_0) | **Delete** /partners/{partnerId}/presets/{key} | Take a widget off the partner&#39;s presets
[**RemovePartnerStorageDestination_0**](PartnersAPI.md#RemovePartnerStorageDestination_0) | **Delete** /partners/{partnerId}/storage | Stop storing a partner&#39;s uploaded files in its own bucket
[**ReplayPartnerNotificationDelivery_0**](PartnersAPI.md#ReplayPartnerNotificationDelivery_0) | **Post** /partners/{partnerId}/notifications/deliveries/{deliveryId}/replay | Send a webhook delivery again
[**RotatePartnerEntryContextSecret_0**](PartnersAPI.md#RotatePartnerEntryContextSecret_0) | **Post** /partners/{partnerId}/entry-context-signing/secret | Make a secret to sign the context of your embeds
[**RotatePartnerWebhookSecret_0**](PartnersAPI.md#RotatePartnerWebhookSecret_0) | **Post** /partners/{partnerId}/notifications/webhook-secret | Make a new secret for your webhook
[**SendPartnerNotificationTestEvent_0**](PartnersAPI.md#SendPartnerNotificationTestEvent_0) | **Post** /partners/{partnerId}/notifications/test-event | Send a test event to your webhook
[**SetPartnerAdapterConnection_0**](PartnersAPI.md#SetPartnerAdapterConnection_0) | **Put** /partners/{partnerId}/adapter-connections/{adapterId}/{credentialKey} | Connect an adapter key to a partner
[**SetPartnerDataDatabase_0**](PartnersAPI.md#SetPartnerDataDatabase_0) | **Put** /partners/{partnerId}/data-database | Keep the data of a partner&#39;s compositions in a Neon database of its own
[**SetPartnerDesignDefaults_0**](PartnersAPI.md#SetPartnerDesignDefaults_0) | **Put** /partners/{partnerId}/design-defaults | Set or clear partner-wide design defaults
[**SetPartnerPreset_0**](PartnersAPI.md#SetPartnerPreset_0) | **Put** /partners/{partnerId}/presets/{key} | Make a widget a preset, or replace a preset
[**SetPartnerStorageDestination_0**](PartnersAPI.md#SetPartnerStorageDestination_0) | **Put** /partners/{partnerId}/storage | Set where a partner&#39;s uploaded files are stored
[**UpdatePartnerEntryContextSigning_0**](PartnersAPI.md#UpdatePartnerEntryContextSigning_0) | **Put** /partners/{partnerId}/entry-context-signing | Require a signed context, or stop requiring it
[**UpdatePartnerNotificationSettings_0**](PartnersAPI.md#UpdatePartnerNotificationSettings_0) | **Put** /partners/{partnerId}/notifications/settings | Choose where your notifications go
[**VerifyPartnerDataDatabase_0**](PartnersAPI.md#VerifyPartnerDataDatabase_0) | **Post** /partners/{partnerId}/data-database/verify | Check that a partner&#39;s own database still works
[**VerifyPartnerStorageDestination_0**](PartnersAPI.md#VerifyPartnerStorageDestination_0) | **Post** /partners/{partnerId}/storage/verify | Check that a partner&#39;s storage destination still works



## CreatePartnerExtraCreditsInvoice_0

> PartnerExtraCreditsInvoiceResponse CreatePartnerExtraCreditsInvoice_0(ctx, partnerId).IdempotencyKey(idempotencyKey).RequestExtraCredits(requestExtraCredits).Execute()

Buy extra credits for a partner



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
	idempotencyKey := "idempotencyKey_example" // string | A key of your own for this purchase, so that a retry cannot make a second invoice
	requestExtraCredits := *openapiclient.NewRequestExtraCredits(float32(250)) // RequestExtraCredits | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.CreatePartnerExtraCreditsInvoice_0(context.Background(), partnerId).IdempotencyKey(idempotencyKey).RequestExtraCredits(requestExtraCredits).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.CreatePartnerExtraCreditsInvoice_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreatePartnerExtraCreditsInvoice_0`: PartnerExtraCreditsInvoiceResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.CreatePartnerExtraCreditsInvoice_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | Partner ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreatePartnerExtraCreditsInvoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | A key of your own for this purchase, so that a retry cannot make a second invoice | 
 **requestExtraCredits** | [**RequestExtraCredits**](RequestExtraCredits.md) |  | 

### Return type

[**PartnerExtraCreditsInvoiceResponse**](PartnerExtraCreditsInvoiceResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetMyPartners_0

> MyPartnersResponse GetMyPartners_0(ctx).Execute()

Find the partner you administer



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
	resp, r, err := apiClient.PartnersAPI.GetMyPartners_0(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.GetMyPartners_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMyPartners_0`: MyPartnersResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.GetMyPartners_0`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetMyPartnersRequest struct via the builder pattern


### Return type

[**MyPartnersResponse**](MyPartnersResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPartnerAdapterConnections_0

> GetUserAdapterConnections200Response GetPartnerAdapterConnections_0(ctx, partnerId).Execute()

See which adapter keys a partner has connected



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose adapter keys to list

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.GetPartnerAdapterConnections_0(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.GetPartnerAdapterConnections_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerAdapterConnections_0`: GetUserAdapterConnections200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.GetPartnerAdapterConnections_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose adapter keys to list | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPartnerAdapterConnectionsRequest struct via the builder pattern


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


## GetPartnerAnalyticsByManagedUser_0

> PartnerAnalyticsByManagedUserResponse GetPartnerAnalyticsByManagedUser_0(ctx, partnerId).StartDate(startDate).EndDate(endDate).Limit(limit).Offset(offset).Execute()

What each managed user's widgets did



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose managed users to report on
	startDate := "startDate_example" // string | Start of the period, included. An ISO 8601 date (`2026-10-01`) or date-time with its offset. Default 30 days before `endDate`.  (optional)
	endDate := "endDate_example" // string | End of the period, not included, in the same forms. Default now. At most 366 days after `startDate`. (optional)
	limit := int32(56) // int32 | How many managed users to list at most (optional) (default to 50)
	offset := int32(56) // int32 | How many managed users to skip (optional) (default to 0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.GetPartnerAnalyticsByManagedUser_0(context.Background(), partnerId).StartDate(startDate).EndDate(endDate).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.GetPartnerAnalyticsByManagedUser_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerAnalyticsByManagedUser_0`: PartnerAnalyticsByManagedUserResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.GetPartnerAnalyticsByManagedUser_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose managed users to report on | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPartnerAnalyticsByManagedUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **startDate** | **string** | Start of the period, included. An ISO 8601 date (&#x60;2026-10-01&#x60;) or date-time with its offset. Default 30 days before &#x60;endDate&#x60;.  | 
 **endDate** | **string** | End of the period, not included, in the same forms. Default now. At most 366 days after &#x60;startDate&#x60;. | 
 **limit** | **int32** | How many managed users to list at most | [default to 50]
 **offset** | **int32** | How many managed users to skip | [default to 0]

### Return type

[**PartnerAnalyticsByManagedUserResponse**](PartnerAnalyticsByManagedUserResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPartnerAnalyticsSummary_0

> PartnerAnalyticsSummaryResponse GetPartnerAnalyticsSummary_0(ctx, partnerId).StartDate(startDate).EndDate(endDate).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Execute()

What was done with a partner's published widgets



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose widgets to report on
	startDate := "startDate_example" // string | Start of the period, included. An ISO 8601 date (`2026-10-01`) or date-time with its offset (`2026-10-01T08:00:00Z`). Default 30 days before `endDate`.  (optional)
	endDate := "endDate_example" // string | End of the period, not included, in the same forms. Default now. It must be after `startDate`, by at most 366 days.  (optional)
	managedUserId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Report only on this managed user (Widgetic's id for the user). Send this or `managedUserExternalId`, not both. (optional)
	managedUserExternalId := "managedUserExternalId_example" // string | Report only on the managed user you registered with this `externalId` (your own identifier for the user). Send this or `managedUserId`, not both. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.GetPartnerAnalyticsSummary_0(context.Background(), partnerId).StartDate(startDate).EndDate(endDate).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.GetPartnerAnalyticsSummary_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerAnalyticsSummary_0`: PartnerAnalyticsSummaryResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.GetPartnerAnalyticsSummary_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose widgets to report on | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPartnerAnalyticsSummaryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **startDate** | **string** | Start of the period, included. An ISO 8601 date (&#x60;2026-10-01&#x60;) or date-time with its offset (&#x60;2026-10-01T08:00:00Z&#x60;). Default 30 days before &#x60;endDate&#x60;.  | 
 **endDate** | **string** | End of the period, not included, in the same forms. Default now. It must be after &#x60;startDate&#x60;, by at most 366 days.  | 
 **managedUserId** | **string** | Report only on this managed user (Widgetic&#39;s id for the user). Send this or &#x60;managedUserExternalId&#x60;, not both. | 
 **managedUserExternalId** | **string** | Report only on the managed user you registered with this &#x60;externalId&#x60; (your own identifier for the user). Send this or &#x60;managedUserId&#x60;, not both. | 

### Return type

[**PartnerAnalyticsSummaryResponse**](PartnerAnalyticsSummaryResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPartnerAnalyticsTimeline_0

> PartnerAnalyticsTimelineResponse GetPartnerAnalyticsTimeline_0(ctx, partnerId).StartDate(startDate).EndDate(endDate).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Execute()

What was done with a partner's widgets, day by day



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose widgets to report on
	startDate := "startDate_example" // string | Start of the period, included. An ISO 8601 date (`2026-10-01`) or date-time with its offset. Default 30 days before `endDate`.  (optional)
	endDate := "endDate_example" // string | End of the period, not included, in the same forms. Default now. At most 366 days after `startDate`. (optional)
	managedUserId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Report only on this managed user (Widgetic's id for the user). Send this or `managedUserExternalId`, not both. (optional)
	managedUserExternalId := "managedUserExternalId_example" // string | Report only on the managed user you registered with this `externalId`. Send this or `managedUserId`, not both. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.GetPartnerAnalyticsTimeline_0(context.Background(), partnerId).StartDate(startDate).EndDate(endDate).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.GetPartnerAnalyticsTimeline_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerAnalyticsTimeline_0`: PartnerAnalyticsTimelineResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.GetPartnerAnalyticsTimeline_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose widgets to report on | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPartnerAnalyticsTimelineRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **startDate** | **string** | Start of the period, included. An ISO 8601 date (&#x60;2026-10-01&#x60;) or date-time with its offset. Default 30 days before &#x60;endDate&#x60;.  | 
 **endDate** | **string** | End of the period, not included, in the same forms. Default now. At most 366 days after &#x60;startDate&#x60;. | 
 **managedUserId** | **string** | Report only on this managed user (Widgetic&#39;s id for the user). Send this or &#x60;managedUserExternalId&#x60;, not both. | 
 **managedUserExternalId** | **string** | Report only on the managed user you registered with this &#x60;externalId&#x60;. Send this or &#x60;managedUserId&#x60;, not both. | 

### Return type

[**PartnerAnalyticsTimelineResponse**](PartnerAnalyticsTimelineResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPartnerAnalyticsTopWidgets_0

> PartnerAnalyticsTopWidgetsResponse GetPartnerAnalyticsTopWidgets_0(ctx, partnerId).StartDate(startDate).EndDate(endDate).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Limit(limit).Execute()

Which widgets were viewed the most



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose widgets to report on
	startDate := "startDate_example" // string | Start of the period, included. An ISO 8601 date (`2026-10-01`) or date-time with its offset. Default 30 days before `endDate`.  (optional)
	endDate := "endDate_example" // string | End of the period, not included, in the same forms. Default now. At most 366 days after `startDate`. (optional)
	managedUserId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Report only on this managed user (Widgetic's id for the user). Send this or `managedUserExternalId`, not both. (optional)
	managedUserExternalId := "managedUserExternalId_example" // string | Report only on the managed user you registered with this `externalId`. Send this or `managedUserId`, not both. (optional)
	limit := int32(56) // int32 | How many widgets to list at most (optional) (default to 10)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.GetPartnerAnalyticsTopWidgets_0(context.Background(), partnerId).StartDate(startDate).EndDate(endDate).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.GetPartnerAnalyticsTopWidgets_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerAnalyticsTopWidgets_0`: PartnerAnalyticsTopWidgetsResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.GetPartnerAnalyticsTopWidgets_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose widgets to report on | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPartnerAnalyticsTopWidgetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **startDate** | **string** | Start of the period, included. An ISO 8601 date (&#x60;2026-10-01&#x60;) or date-time with its offset. Default 30 days before &#x60;endDate&#x60;.  | 
 **endDate** | **string** | End of the period, not included, in the same forms. Default now. At most 366 days after &#x60;startDate&#x60;. | 
 **managedUserId** | **string** | Report only on this managed user (Widgetic&#39;s id for the user). Send this or &#x60;managedUserExternalId&#x60;, not both. | 
 **managedUserExternalId** | **string** | Report only on the managed user you registered with this &#x60;externalId&#x60;. Send this or &#x60;managedUserId&#x60;, not both. | 
 **limit** | **int32** | How many widgets to list at most | [default to 10]

### Return type

[**PartnerAnalyticsTopWidgetsResponse**](PartnerAnalyticsTopWidgetsResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPartnerBillingOverview_0

> GetPartnerBillingOverview200Response GetPartnerBillingOverview_0(ctx, partnerId).Execute()

Get comprehensive partner billing overview



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.GetPartnerBillingOverview_0(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.GetPartnerBillingOverview_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerBillingOverview_0`: GetPartnerBillingOverview200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.GetPartnerBillingOverview_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | Partner ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPartnerBillingOverviewRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetPartnerBillingOverview200Response**](GetPartnerBillingOverview200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPartnerContract_0

> PartnerContractResponse GetPartnerContract_0(ctx, partnerId).Execute()

Get a partner's contract



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose contract to read

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.GetPartnerContract_0(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.GetPartnerContract_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerContract_0`: PartnerContractResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.GetPartnerContract_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose contract to read | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPartnerContractRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PartnerContractResponse**](PartnerContractResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPartnerCreditBalance_0

> AccountCreditBalanceResponse GetPartnerCreditBalance_0(ctx, partnerId).Execute()

Get partner credit balance



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.GetPartnerCreditBalance_0(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.GetPartnerCreditBalance_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerCreditBalance_0`: AccountCreditBalanceResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.GetPartnerCreditBalance_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | Partner ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPartnerCreditBalanceRequest struct via the builder pattern


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


## GetPartnerCreditTransactions_0

> GetPartnerCreditTransactions200Response GetPartnerCreditTransactions_0(ctx, partnerId).Limit(limit).Offset(offset).Type_(type_).Execute()

Get partner credit transaction history



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
	limit := int32(56) // int32 | Number of transactions to return (optional) (default to 20)
	offset := int32(56) // int32 | Number of transactions to skip (optional) (default to 0)
	type_ := "type__example" // string | Only entries of this type, for instance `debit` for the credits spent. The types are listed on `AccountCreditTransaction`.  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.GetPartnerCreditTransactions_0(context.Background(), partnerId).Limit(limit).Offset(offset).Type_(type_).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.GetPartnerCreditTransactions_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerCreditTransactions_0`: GetPartnerCreditTransactions200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.GetPartnerCreditTransactions_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | Partner ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPartnerCreditTransactionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **limit** | **int32** | Number of transactions to return | [default to 20]
 **offset** | **int32** | Number of transactions to skip | [default to 0]
 **type_** | **string** | Only entries of this type, for instance &#x60;debit&#x60; for the credits spent. The types are listed on &#x60;AccountCreditTransaction&#x60;.  | 

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


## GetPartnerDataDatabase_0

> PartnerDataDatabaseResponse GetPartnerDataDatabase_0(ctx, partnerId).Execute()

See the Neon database a partner keeps the data of its compositions in



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose database to read

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.GetPartnerDataDatabase_0(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.GetPartnerDataDatabase_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerDataDatabase_0`: PartnerDataDatabaseResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.GetPartnerDataDatabase_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose database to read | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPartnerDataDatabaseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PartnerDataDatabaseResponse**](PartnerDataDatabaseResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPartnerDesignDefaults_0

> GetPartnerDesignDefaults200Response GetPartnerDesignDefaults_0(ctx, partnerId).Execute()

Read partner-wide design defaults

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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.GetPartnerDesignDefaults_0(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.GetPartnerDesignDefaults_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerDesignDefaults_0`: GetPartnerDesignDefaults200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.GetPartnerDesignDefaults_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPartnerDesignDefaultsRequest struct via the builder pattern


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


## GetPartnerEntryContextSigning_0

> PartnerEntryContextSigningResponse GetPartnerEntryContextSigning_0(ctx, partnerId).Execute()

See how the context of your embeds is signed



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose context signing to read

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.GetPartnerEntryContextSigning_0(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.GetPartnerEntryContextSigning_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerEntryContextSigning_0`: PartnerEntryContextSigningResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.GetPartnerEntryContextSigning_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose context signing to read | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPartnerEntryContextSigningRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PartnerEntryContextSigningResponse**](PartnerEntryContextSigningResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPartnerNotificationSettings_0

> PartnerNotificationSettingsResponse GetPartnerNotificationSettings_0(ctx, partnerId).Execute()

Where your notifications go



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose notification settings to read

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.GetPartnerNotificationSettings_0(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.GetPartnerNotificationSettings_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerNotificationSettings_0`: PartnerNotificationSettingsResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.GetPartnerNotificationSettings_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose notification settings to read | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPartnerNotificationSettingsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PartnerNotificationSettingsResponse**](PartnerNotificationSettingsResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPartnerStorageDestination_0

> PartnerStorageDestinationResponse GetPartnerStorageDestination_0(ctx, partnerId).Execute()

Get where a partner's uploaded files are stored



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose storage destination to read

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.GetPartnerStorageDestination_0(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.GetPartnerStorageDestination_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerStorageDestination_0`: PartnerStorageDestinationResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.GetPartnerStorageDestination_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose storage destination to read | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPartnerStorageDestinationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PartnerStorageDestinationResponse**](PartnerStorageDestinationResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPartnerStorageUsage_0

> PartnerStorageUsageResponse GetPartnerStorageUsage_0(ctx, partnerId).Limit(limit).Offset(offset).Execute()

What a partner's customers store



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose storage to report on
	limit := int32(56) // int32 | How many managed users to list at most (optional) (default to 50)
	offset := int32(56) // int32 | How many managed users to skip (optional) (default to 0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.GetPartnerStorageUsage_0(context.Background(), partnerId).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.GetPartnerStorageUsage_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerStorageUsage_0`: PartnerStorageUsageResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.GetPartnerStorageUsage_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose storage to report on | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPartnerStorageUsageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **limit** | **int32** | How many managed users to list at most | [default to 50]
 **offset** | **int32** | How many managed users to skip | [default to 0]

### Return type

[**PartnerStorageUsageResponse**](PartnerStorageUsageResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPartnerNotificationDeliveries_0

> PartnerNotificationDeliveryLogResponse ListPartnerNotificationDeliveries_0(ctx, partnerId).Limit(limit).Execute()

How your notifications reached you



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose deliveries to list
	limit := int32(56) // int32 | How many deliveries to list at most (optional) (default to 100)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.ListPartnerNotificationDeliveries_0(context.Background(), partnerId).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.ListPartnerNotificationDeliveries_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPartnerNotificationDeliveries_0`: PartnerNotificationDeliveryLogResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.ListPartnerNotificationDeliveries_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose deliveries to list | 

### Other Parameters

Other parameters are passed through a pointer to a apiListPartnerNotificationDeliveriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **limit** | **int32** | How many deliveries to list at most | [default to 100]

### Return type

[**PartnerNotificationDeliveryLogResponse**](PartnerNotificationDeliveryLogResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPartnerNotifications_0

> PartnerNotificationPageResponse ListPartnerNotifications_0(ctx, partnerId).Limit(limit).Before(before).Execute()

What your partner account was told



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose notifications to list
	limit := int32(56) // int32 | How many notifications to list at most (optional) (default to 20)
	before := time.Now() // time.Time | Only the notifications made before this moment. Give the `nextBefore` of the previous page. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.ListPartnerNotifications_0(context.Background(), partnerId).Limit(limit).Before(before).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.ListPartnerNotifications_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPartnerNotifications_0`: PartnerNotificationPageResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.ListPartnerNotifications_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose notifications to list | 

### Other Parameters

Other parameters are passed through a pointer to a apiListPartnerNotificationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **limit** | **int32** | How many notifications to list at most | [default to 20]
 **before** | **time.Time** | Only the notifications made before this moment. Give the &#x60;nextBefore&#x60; of the previous page. | 

### Return type

[**PartnerNotificationPageResponse**](PartnerNotificationPageResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPartnerPresets_0

> ListPartnerPresets200Response ListPartnerPresets_0(ctx, partnerId).Execute()

List the widgets a partner offers as presets



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose presets to list

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.ListPartnerPresets_0(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.ListPartnerPresets_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPartnerPresets_0`: ListPartnerPresets200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.ListPartnerPresets_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose presets to list | 

### Other Parameters

Other parameters are passed through a pointer to a apiListPartnerPresetsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ListPartnerPresets200Response**](ListPartnerPresets200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemovePartnerAdapterConnection_0

> RemoveUserAdapterConnection200Response RemovePartnerAdapterConnection_0(ctx, partnerId, adapterId, credentialKey).Execute()

Remove an adapter key from a partner



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner that keeps the key
	adapterId := "adapterId_example" // string | The adapter the key is for
	credentialKey := "credentialKey_example" // string | The key's name within the adapter

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.RemovePartnerAdapterConnection_0(context.Background(), partnerId, adapterId, credentialKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.RemovePartnerAdapterConnection_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemovePartnerAdapterConnection_0`: RemoveUserAdapterConnection200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.RemovePartnerAdapterConnection_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner that keeps the key | 
**adapterId** | **string** | The adapter the key is for | 
**credentialKey** | **string** | The key&#39;s name within the adapter | 

### Other Parameters

Other parameters are passed through a pointer to a apiRemovePartnerAdapterConnectionRequest struct via the builder pattern


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


## RemovePartnerDataDatabase_0

> PartnerDataDatabaseRemovalResponse RemovePartnerDataDatabase_0(ctx, partnerId).Execute()

Stop keeping the data of a partner's compositions in its own database



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose database to remove

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.RemovePartnerDataDatabase_0(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.RemovePartnerDataDatabase_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemovePartnerDataDatabase_0`: PartnerDataDatabaseRemovalResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.RemovePartnerDataDatabase_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose database to remove | 

### Other Parameters

Other parameters are passed through a pointer to a apiRemovePartnerDataDatabaseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PartnerDataDatabaseRemovalResponse**](PartnerDataDatabaseRemovalResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemovePartnerPreset_0

> PartnerPresetRemovalResponse RemovePartnerPreset_0(ctx, partnerId, key).Execute()

Take a widget off the partner's presets



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose preset to remove
	key := "key_example" // string | The key of the preset to remove

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.RemovePartnerPreset_0(context.Background(), partnerId, key).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.RemovePartnerPreset_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemovePartnerPreset_0`: PartnerPresetRemovalResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.RemovePartnerPreset_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose preset to remove | 
**key** | **string** | The key of the preset to remove | 

### Other Parameters

Other parameters are passed through a pointer to a apiRemovePartnerPresetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**PartnerPresetRemovalResponse**](PartnerPresetRemovalResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemovePartnerStorageDestination_0

> PartnerStorageRemovalResponse RemovePartnerStorageDestination_0(ctx, partnerId).Execute()

Stop storing a partner's uploaded files in its own bucket



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose storage destination to remove

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.RemovePartnerStorageDestination_0(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.RemovePartnerStorageDestination_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemovePartnerStorageDestination_0`: PartnerStorageRemovalResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.RemovePartnerStorageDestination_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose storage destination to remove | 

### Other Parameters

Other parameters are passed through a pointer to a apiRemovePartnerStorageDestinationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PartnerStorageRemovalResponse**](PartnerStorageRemovalResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReplayPartnerNotificationDelivery_0

> PartnerNotificationDeliveryResponse ReplayPartnerNotificationDelivery_0(ctx, partnerId, deliveryId).IdempotencyKey(idempotencyKey).Execute()

Send a webhook delivery again



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose delivery to replay
	deliveryId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The delivery to send again (must be a webhook delivery of this partner)
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.ReplayPartnerNotificationDelivery_0(context.Background(), partnerId, deliveryId).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.ReplayPartnerNotificationDelivery_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReplayPartnerNotificationDelivery_0`: PartnerNotificationDeliveryResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.ReplayPartnerNotificationDelivery_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose delivery to replay | 
**deliveryId** | **string** | The delivery to send again (must be a webhook delivery of this partner) | 

### Other Parameters

Other parameters are passed through a pointer to a apiReplayPartnerNotificationDeliveryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 

### Return type

[**PartnerNotificationDeliveryResponse**](PartnerNotificationDeliveryResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RotatePartnerEntryContextSecret_0

> PartnerEntryContextSecretResponse RotatePartnerEntryContextSecret_0(ctx, partnerId).IdempotencyKey(idempotencyKey).Execute()

Make a secret to sign the context of your embeds



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose secret to make
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.RotatePartnerEntryContextSecret_0(context.Background(), partnerId).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.RotatePartnerEntryContextSecret_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RotatePartnerEntryContextSecret_0`: PartnerEntryContextSecretResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.RotatePartnerEntryContextSecret_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose secret to make | 

### Other Parameters

Other parameters are passed through a pointer to a apiRotatePartnerEntryContextSecretRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 

### Return type

[**PartnerEntryContextSecretResponse**](PartnerEntryContextSecretResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RotatePartnerWebhookSecret_0

> PartnerNotificationSettingsChangeResponse RotatePartnerWebhookSecret_0(ctx, partnerId).IdempotencyKey(idempotencyKey).Execute()

Make a new secret for your webhook



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose webhook secret to replace
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.RotatePartnerWebhookSecret_0(context.Background(), partnerId).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.RotatePartnerWebhookSecret_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RotatePartnerWebhookSecret_0`: PartnerNotificationSettingsChangeResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.RotatePartnerWebhookSecret_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose webhook secret to replace | 

### Other Parameters

Other parameters are passed through a pointer to a apiRotatePartnerWebhookSecretRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 

### Return type

[**PartnerNotificationSettingsChangeResponse**](PartnerNotificationSettingsChangeResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SendPartnerNotificationTestEvent_0

> PartnerNotificationTestEventResultResponse SendPartnerNotificationTestEvent_0(ctx, partnerId).IdempotencyKey(idempotencyKey).PartnerNotificationTestEventRequest(partnerNotificationTestEventRequest).Execute()

Send a test event to your webhook



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose webhook to try
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	partnerNotificationTestEventRequest := *openapiclient.NewPartnerNotificationTestEventRequest(openapiclient.PartnerNotificationEventType("invoice.issued")) // PartnerNotificationTestEventRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.SendPartnerNotificationTestEvent_0(context.Background(), partnerId).IdempotencyKey(idempotencyKey).PartnerNotificationTestEventRequest(partnerNotificationTestEventRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.SendPartnerNotificationTestEvent_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SendPartnerNotificationTestEvent_0`: PartnerNotificationTestEventResultResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.SendPartnerNotificationTestEvent_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose webhook to try | 

### Other Parameters

Other parameters are passed through a pointer to a apiSendPartnerNotificationTestEventRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **partnerNotificationTestEventRequest** | [**PartnerNotificationTestEventRequest**](PartnerNotificationTestEventRequest.md) |  | 

### Return type

[**PartnerNotificationTestEventResultResponse**](PartnerNotificationTestEventResultResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetPartnerAdapterConnection_0

> SetUserAdapterConnection200Response SetPartnerAdapterConnection_0(ctx, partnerId, adapterId, credentialKey).SetAdapterConnectionRequest(setAdapterConnectionRequest).Execute()

Connect an adapter key to a partner



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner that keeps the key
	adapterId := "adapterId_example" // string | The adapter the key is for
	credentialKey := "credentialKey_example" // string | The key's name within the adapter
	setAdapterConnectionRequest := *openapiclient.NewSetAdapterConnectionRequest("YOUR_PROVIDER_KEY") // SetAdapterConnectionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.SetPartnerAdapterConnection_0(context.Background(), partnerId, adapterId, credentialKey).SetAdapterConnectionRequest(setAdapterConnectionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.SetPartnerAdapterConnection_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetPartnerAdapterConnection_0`: SetUserAdapterConnection200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.SetPartnerAdapterConnection_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner that keeps the key | 
**adapterId** | **string** | The adapter the key is for | 
**credentialKey** | **string** | The key&#39;s name within the adapter | 

### Other Parameters

Other parameters are passed through a pointer to a apiSetPartnerAdapterConnectionRequest struct via the builder pattern


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


## SetPartnerDataDatabase_0

> PartnerDataDatabaseResponse SetPartnerDataDatabase_0(ctx, partnerId).SetPartnerDataDatabaseRequest(setPartnerDataDatabaseRequest).Execute()

Keep the data of a partner's compositions in a Neon database of its own



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose database to set
	setPartnerDataDatabaseRequest := *openapiclient.NewSetPartnerDataDatabaseRequest("postgresql://widgetic_data:YOUR_PASSWORD@ep-cool-name-123456.eu-central-1.aws.neon.tech/neondb") // SetPartnerDataDatabaseRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.SetPartnerDataDatabase_0(context.Background(), partnerId).SetPartnerDataDatabaseRequest(setPartnerDataDatabaseRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.SetPartnerDataDatabase_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetPartnerDataDatabase_0`: PartnerDataDatabaseResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.SetPartnerDataDatabase_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose database to set | 

### Other Parameters

Other parameters are passed through a pointer to a apiSetPartnerDataDatabaseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **setPartnerDataDatabaseRequest** | [**SetPartnerDataDatabaseRequest**](SetPartnerDataDatabaseRequest.md) |  | 

### Return type

[**PartnerDataDatabaseResponse**](PartnerDataDatabaseResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetPartnerDesignDefaults_0

> GetPartnerDesignDefaults200Response SetPartnerDesignDefaults_0(ctx, partnerId).SetPartnerDesignDefaultsRequest(setPartnerDesignDefaultsRequest).Execute()

Set or clear partner-wide design defaults



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	setPartnerDesignDefaultsRequest := *openapiclient.NewSetPartnerDesignDefaultsRequest(map[string]interface{}(123)) // SetPartnerDesignDefaultsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.SetPartnerDesignDefaults_0(context.Background(), partnerId).SetPartnerDesignDefaultsRequest(setPartnerDesignDefaultsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.SetPartnerDesignDefaults_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetPartnerDesignDefaults_0`: GetPartnerDesignDefaults200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.SetPartnerDesignDefaults_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSetPartnerDesignDefaultsRequest struct via the builder pattern


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


## SetPartnerPreset_0

> PartnerPresetResponse SetPartnerPreset_0(ctx, partnerId, key).SetPartnerPresetRequest(setPartnerPresetRequest).Execute()

Make a widget a preset, or replace a preset



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose preset to set
	key := "key_example" // string | The name your code uses for the preset
	setPartnerPresetRequest := *openapiclient.NewSetPartnerPresetRequest("WidgetId_example") // SetPartnerPresetRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.SetPartnerPreset_0(context.Background(), partnerId, key).SetPartnerPresetRequest(setPartnerPresetRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.SetPartnerPreset_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetPartnerPreset_0`: PartnerPresetResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.SetPartnerPreset_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose preset to set | 
**key** | **string** | The name your code uses for the preset | 

### Other Parameters

Other parameters are passed through a pointer to a apiSetPartnerPresetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **setPartnerPresetRequest** | [**SetPartnerPresetRequest**](SetPartnerPresetRequest.md) |  | 

### Return type

[**PartnerPresetResponse**](PartnerPresetResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetPartnerStorageDestination_0

> PartnerStorageDestinationResponse SetPartnerStorageDestination_0(ctx, partnerId).SetPartnerStorageDestinationRequest(setPartnerStorageDestinationRequest).Execute()

Set where a partner's uploaded files are stored



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose storage destination to set
	setPartnerStorageDestinationRequest := *openapiclient.NewSetPartnerStorageDestinationRequest("https://abc123.r2.cloudflarestorage.com", "auto", "acme-widget-media", "https://media.example.com", "AccessKeyId_example", "SecretAccessKey_example") // SetPartnerStorageDestinationRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.SetPartnerStorageDestination_0(context.Background(), partnerId).SetPartnerStorageDestinationRequest(setPartnerStorageDestinationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.SetPartnerStorageDestination_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetPartnerStorageDestination_0`: PartnerStorageDestinationResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.SetPartnerStorageDestination_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose storage destination to set | 

### Other Parameters

Other parameters are passed through a pointer to a apiSetPartnerStorageDestinationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **setPartnerStorageDestinationRequest** | [**SetPartnerStorageDestinationRequest**](SetPartnerStorageDestinationRequest.md) |  | 

### Return type

[**PartnerStorageDestinationResponse**](PartnerStorageDestinationResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdatePartnerEntryContextSigning_0

> PartnerEntryContextSigningResponse UpdatePartnerEntryContextSigning_0(ctx, partnerId).UpdatePartnerEntryContextSigningRequest(updatePartnerEntryContextSigningRequest).IdempotencyKey(idempotencyKey).Execute()

Require a signed context, or stop requiring it



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose context signing to change
	updatePartnerEntryContextSigningRequest := *openapiclient.NewUpdatePartnerEntryContextSigningRequest(false) // UpdatePartnerEntryContextSigningRequest | 
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Optional: without it the call is carried out every time it is sent. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.UpdatePartnerEntryContextSigning_0(context.Background(), partnerId).UpdatePartnerEntryContextSigningRequest(updatePartnerEntryContextSigningRequest).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.UpdatePartnerEntryContextSigning_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdatePartnerEntryContextSigning_0`: PartnerEntryContextSigningResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.UpdatePartnerEntryContextSigning_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose context signing to change | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdatePartnerEntryContextSigningRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updatePartnerEntryContextSigningRequest** | [**UpdatePartnerEntryContextSigningRequest**](UpdatePartnerEntryContextSigningRequest.md) |  | 
 **idempotencyKey** | **string** | Optional: without it the call is carried out every time it is sent. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 

### Return type

[**PartnerEntryContextSigningResponse**](PartnerEntryContextSigningResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdatePartnerNotificationSettings_0

> PartnerNotificationSettingsChangeResponse UpdatePartnerNotificationSettings_0(ctx, partnerId).UpdatePartnerNotificationSettingsRequest(updatePartnerNotificationSettingsRequest).IdempotencyKey(idempotencyKey).Execute()

Choose where your notifications go



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose notification settings to change
	updatePartnerNotificationSettingsRequest := *openapiclient.NewUpdatePartnerNotificationSettingsRequest() // UpdatePartnerNotificationSettingsRequest | 
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Optional: without it the call is carried out every time it is sent. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.UpdatePartnerNotificationSettings_0(context.Background(), partnerId).UpdatePartnerNotificationSettingsRequest(updatePartnerNotificationSettingsRequest).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.UpdatePartnerNotificationSettings_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdatePartnerNotificationSettings_0`: PartnerNotificationSettingsChangeResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.UpdatePartnerNotificationSettings_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose notification settings to change | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdatePartnerNotificationSettingsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updatePartnerNotificationSettingsRequest** | [**UpdatePartnerNotificationSettingsRequest**](UpdatePartnerNotificationSettingsRequest.md) |  | 
 **idempotencyKey** | **string** | Optional: without it the call is carried out every time it is sent. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 

### Return type

[**PartnerNotificationSettingsChangeResponse**](PartnerNotificationSettingsChangeResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## VerifyPartnerDataDatabase_0

> PartnerDataDatabaseResponse VerifyPartnerDataDatabase_0(ctx, partnerId).Execute()

Check that a partner's own database still works



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose database to check

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.VerifyPartnerDataDatabase_0(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.VerifyPartnerDataDatabase_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `VerifyPartnerDataDatabase_0`: PartnerDataDatabaseResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.VerifyPartnerDataDatabase_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose database to check | 

### Other Parameters

Other parameters are passed through a pointer to a apiVerifyPartnerDataDatabaseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PartnerDataDatabaseResponse**](PartnerDataDatabaseResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## VerifyPartnerStorageDestination_0

> PartnerStorageDestinationResponse VerifyPartnerStorageDestination_0(ctx, partnerId).Execute()

Check that a partner's storage destination still works



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
	partnerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The partner whose storage destination to check

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnersAPI.VerifyPartnerStorageDestination_0(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnersAPI.VerifyPartnerStorageDestination_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `VerifyPartnerStorageDestination_0`: PartnerStorageDestinationResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnersAPI.VerifyPartnerStorageDestination_0`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**partnerId** | **string** | The partner whose storage destination to check | 

### Other Parameters

Other parameters are passed through a pointer to a apiVerifyPartnerStorageDestinationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PartnerStorageDestinationResponse**](PartnerStorageDestinationResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

