# \PartnerAPI

All URIs are relative to *https://api.widgetic.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddAiAnswersKnowledgeDocument**](PartnerAPI.md#AddAiAnswersKnowledgeDocument) | **Post** /compositions/{id}/adapters/ai-answers/knowledge/documents | Add a document for a widget&#39;s AI to answer from
[**AddPersonalWorkspaceDomain**](PartnerAPI.md#AddPersonalWorkspaceDomain) | **Post** /users/{id}/workspace/domains | Allow a website to show your widgets
[**CallPublicCompositionAdapter**](PartnerAPI.md#CallPublicCompositionAdapter) | **Post** /embed/compositions/{compositionId}/adapters/{adapterId}/{operation} | Call a gateway operation of an adapter a published widget uses
[**CheckCompositionAccess**](PartnerAPI.md#CheckCompositionAccess) | **Get** /compositions/{id}/access | Check Composition Access
[**CopyPresetForManagedUser**](PartnerAPI.md#CopyPresetForManagedUser) | **Post** /managed-users/{id}/presets/{key}/copy | Give a managed user a copy of one of your presets
[**CreateCanvas**](PartnerAPI.md#CreateCanvas) | **Post** /canvases | Create Canvas
[**CreateComposition**](PartnerAPI.md#CreateComposition) | **Post** /compositions | Create Composition
[**CreateCompositionContentItem**](PartnerAPI.md#CreateCompositionContentItem) | **Post** /compositions/{id}/content/{list}/items | Add a content list item
[**CreateCompositionDatabaseRecord**](PartnerAPI.md#CreateCompositionDatabaseRecord) | **Post** /compositions/{id}/database/{table} | Create Record In Composition Database
[**CreateCompositionFromPreset**](PartnerAPI.md#CreateCompositionFromPreset) | **Post** /managed-users/{id}/presets/{key}/composition | Create a composition from one of your presets in one call
[**CreateCompositionFromWidget**](PartnerAPI.md#CreateCompositionFromWidget) | **Post** /widgets/{id}/composition | Create a composition for a widget in one call
[**CreateManagedUser**](PartnerAPI.md#CreateManagedUser) | **Post** /managed-users | Create Managed User
[**CreateManagedUserEditorSession**](PartnerAPI.md#CreateManagedUserEditorSession) | **Post** /managed-users/{id}/editor-sessions | Create an editor session for a managed user
[**CreatePartnerExtraCreditsInvoice**](PartnerAPI.md#CreatePartnerExtraCreditsInvoice) | **Post** /partners/{partnerId}/credits/extra-invoice | Buy extra credits for a partner
[**CreatePublicCompositionEntry**](PartnerAPI.md#CreatePublicCompositionEntry) | **Post** /embed/compositions/{compositionId}/entries/{table} | Append a visitor entry through the gateway
[**CreateUserApiKey**](PartnerAPI.md#CreateUserApiKey) | **Post** /users/{id}/keys | Create an API key
[**CreateWidget**](PartnerAPI.md#CreateWidget) | **Post** /widgets | Create Widget
[**DeleteCanvas**](PartnerAPI.md#DeleteCanvas) | **Delete** /canvases/{id} | Delete Canvas
[**DeleteComposition**](PartnerAPI.md#DeleteComposition) | **Delete** /compositions/{id} | Delete Composition
[**DeleteCompositionContentItem**](PartnerAPI.md#DeleteCompositionContentItem) | **Delete** /compositions/{id}/content/{list}/items/{itemId} | Delete a content list item
[**DeleteCompositionDataSource**](PartnerAPI.md#DeleteCompositionDataSource) | **Delete** /compositions/{id}/data-source | Remove the composition data source binding
[**DeleteCompositionDatabaseRecord**](PartnerAPI.md#DeleteCompositionDatabaseRecord) | **Delete** /compositions/{id}/database/{table}/{recordId} | Delete Record From Composition Database
[**DeleteCompositionEntryItems**](PartnerAPI.md#DeleteCompositionEntryItems) | **Delete** /compositions/{id}/entries/{table}/items | Delete composition entry items by id or host context
[**DeleteManagedUser**](PartnerAPI.md#DeleteManagedUser) | **Delete** /managed-users/{id} | Delete Managed User
[**DeletePersonalWorkspaceDomain**](PartnerAPI.md#DeletePersonalWorkspaceDomain) | **Delete** /users/{id}/workspace/domains/{domainId} | Stop allowing a website to show your widgets
[**DeleteUserApiKey**](PartnerAPI.md#DeleteUserApiKey) | **Delete** /users/{id}/keys/{keyId} | Delete an API key
[**DescribeCompositionEntries**](PartnerAPI.md#DescribeCompositionEntries) | **Get** /compositions/{id}/entries | Describe What a Composition Keeps
[**DuplicateComposition**](PartnerAPI.md#DuplicateComposition) | **Post** /compositions/{id}/duplicate | Duplicate Composition
[**ExportCompositionEntryItems**](PartnerAPI.md#ExportCompositionEntryItems) | **Get** /compositions/{id}/entries/{table}/export | Export composition entry items
[**GetAiAnswersKnowledge**](PartnerAPI.md#GetAiAnswersKnowledge) | **Get** /compositions/{id}/adapters/ai-answers/knowledge | See the documents a widget&#39;s AI answers from
[**GetAllCanvases**](PartnerAPI.md#GetAllCanvases) | **Get** /canvases | Get All Canvases
[**GetAllCompositions**](PartnerAPI.md#GetAllCompositions) | **Get** /compositions | Get All Compositions
[**GetAllManagedUsers**](PartnerAPI.md#GetAllManagedUsers) | **Get** /managed-users | Get Managed Users
[**GetCanvas**](PartnerAPI.md#GetCanvas) | **Get** /canvases/{id} | Get Canvas
[**GetCompositionById**](PartnerAPI.md#GetCompositionById) | **Get** /compositions/{id} | Get Composition
[**GetCompositionContent**](PartnerAPI.md#GetCompositionContent) | **Get** /compositions/{id}/content | Get Current Content
[**GetCompositionContentSchema**](PartnerAPI.md#GetCompositionContentSchema) | **Get** /compositions/{id}/schema/content | Get Content Schema
[**GetCompositionDataSource**](PartnerAPI.md#GetCompositionDataSource) | **Get** /compositions/{id}/data-source | Read the composition data source binding
[**GetCompositionDatabaseRecord**](PartnerAPI.md#GetCompositionDatabaseRecord) | **Get** /compositions/{id}/database/{table}/{recordId} | Get Record From Composition Database
[**GetCompositionDatabaseRecords**](PartnerAPI.md#GetCompositionDatabaseRecords) | **Get** /compositions/{id}/database/{table} | Get All Records From Composition Database Table
[**GetCompositionDesign**](PartnerAPI.md#GetCompositionDesign) | **Get** /compositions/{id}/design | Get Composition Design
[**GetCompositionDesignSchema**](PartnerAPI.md#GetCompositionDesignSchema) | **Get** /compositions/{id}/schema/design | Get Design Schema
[**GetCompositionEmbedSchema**](PartnerAPI.md#GetCompositionEmbedSchema) | **Get** /compositions/{id}/schema/embed | Get Embed Schema
[**GetCompositionEmbedSettings**](PartnerAPI.md#GetCompositionEmbedSettings) | **Get** /compositions/{id}/embed-settings | Get Composition Embed Settings
[**GetCompositionPreview**](PartnerAPI.md#GetCompositionPreview) | **Get** /compositions/{id}/preview | Get Composition Preview
[**GetCompositionVersions**](PartnerAPI.md#GetCompositionVersions) | **Get** /compositions/{id}/versions | Get Composition Versions
[**GetCompositionsBatch**](PartnerAPI.md#GetCompositionsBatch) | **Post** /compositions/batch | Get Compositions Batch
[**GetInvoicesByPartnerId**](PartnerAPI.md#GetInvoicesByPartnerId) | **Get** /invoices/partner/{partnerId} | List a partner&#39;s invoices
[**GetManagedUserById**](PartnerAPI.md#GetManagedUserById) | **Get** /managed-users/{id} | Get Managed User By ID
[**GetManagedUserDesignDefaults**](PartnerAPI.md#GetManagedUserDesignDefaults) | **Get** /managed-users/{id}/design-defaults | Read design defaults for one managed user
[**GetManagedUserEntitlements**](PartnerAPI.md#GetManagedUserEntitlements) | **Get** /entitlements/managed-users/{managedUserId} | Get managed user entitlements
[**GetManagedUserLimits**](PartnerAPI.md#GetManagedUserLimits) | **Get** /managed-users/{id}/limits | Read monthly credit cap and usage for one managed user
[**GetManagedUserStorageUsage**](PartnerAPI.md#GetManagedUserStorageUsage) | **Get** /managed-users/{id}/storage-usage | Storage used by one managed user&#39;s uploads
[**GetManagedUserUsage**](PartnerAPI.md#GetManagedUserUsage) | **Get** /managed-users/{id}/usage | What a managed user&#39;s editor sessions spent
[**GetManagedUsersByManagerId**](PartnerAPI.md#GetManagedUsersByManagerId) | **Get** /users/{managerId}/managed-users | Get Managed Users By Manager
[**GetMyPartners**](PartnerAPI.md#GetMyPartners) | **Get** /partners/mine | Find the partner you administer
[**GetPartnerAdapterConnections**](PartnerAPI.md#GetPartnerAdapterConnections) | **Get** /partners/{partnerId}/adapter-connections | See which adapter keys a partner has connected
[**GetPartnerAnalyticsByManagedUser**](PartnerAPI.md#GetPartnerAnalyticsByManagedUser) | **Get** /partners/{partnerId}/analytics/managed-users | What each managed user&#39;s widgets did
[**GetPartnerAnalyticsSummary**](PartnerAPI.md#GetPartnerAnalyticsSummary) | **Get** /partners/{partnerId}/analytics/summary | What was done with a partner&#39;s published widgets
[**GetPartnerAnalyticsTimeline**](PartnerAPI.md#GetPartnerAnalyticsTimeline) | **Get** /partners/{partnerId}/analytics/timeline | What was done with a partner&#39;s widgets, day by day
[**GetPartnerAnalyticsTopWidgets**](PartnerAPI.md#GetPartnerAnalyticsTopWidgets) | **Get** /partners/{partnerId}/analytics/top-widgets | Which widgets were viewed the most
[**GetPartnerBillingOverview**](PartnerAPI.md#GetPartnerBillingOverview) | **Get** /partners/{partnerId}/billing-overview | Get comprehensive partner billing overview
[**GetPartnerContract**](PartnerAPI.md#GetPartnerContract) | **Get** /partners/{partnerId}/contract | Get a partner&#39;s contract
[**GetPartnerCreditBalance**](PartnerAPI.md#GetPartnerCreditBalance) | **Get** /partners/{partnerId}/credits/balance | Get partner credit balance
[**GetPartnerCreditTransactions**](PartnerAPI.md#GetPartnerCreditTransactions) | **Get** /partners/{partnerId}/credits/transactions | Get partner credit transaction history
[**GetPartnerDataDatabase**](PartnerAPI.md#GetPartnerDataDatabase) | **Get** /partners/{partnerId}/data-database | See the Neon database a partner keeps the data of its compositions in
[**GetPartnerDesignDefaults**](PartnerAPI.md#GetPartnerDesignDefaults) | **Get** /partners/{partnerId}/design-defaults | Read partner-wide design defaults
[**GetPartnerEntitlements**](PartnerAPI.md#GetPartnerEntitlements) | **Get** /entitlements/partners/{partnerId} | Get partner entitlements
[**GetPartnerEntryContextSigning**](PartnerAPI.md#GetPartnerEntryContextSigning) | **Get** /partners/{partnerId}/entry-context-signing | See how the context of your embeds is signed
[**GetPartnerNotificationSettings**](PartnerAPI.md#GetPartnerNotificationSettings) | **Get** /partners/{partnerId}/notifications/settings | Where your notifications go
[**GetPartnerStorageDestination**](PartnerAPI.md#GetPartnerStorageDestination) | **Get** /partners/{partnerId}/storage | Get where a partner&#39;s uploaded files are stored
[**GetPartnerStorageUsage**](PartnerAPI.md#GetPartnerStorageUsage) | **Get** /partners/{partnerId}/storage/usage | What a partner&#39;s customers store
[**GetPersonalWorkspaceDomains**](PartnerAPI.md#GetPersonalWorkspaceDomains) | **Get** /users/{id}/workspace/domains | List the websites allowed to show your widgets
[**GetPublicCompositionEmbed**](PartnerAPI.md#GetPublicCompositionEmbed) | **Get** /embed/compositions/{compositionId} | Resolve a composition UUID to a published widget URL
[**GetPublicCompositionIframe**](PartnerAPI.md#GetPublicCompositionIframe) | **Get** /embed/compositions/{compositionId}/frame | Embed a published composition with its saved values
[**GetUserAdapterConnections**](PartnerAPI.md#GetUserAdapterConnections) | **Get** /users/{userId}/adapter-connections | See which adapter keys an account has connected
[**GetUserApiKeyUsageLogs**](PartnerAPI.md#GetUserApiKeyUsageLogs) | **Get** /users/{id}/api-keys/{keyId}/logs | Read what an API key was used for
[**GetUserApiKeys**](PartnerAPI.md#GetUserApiKeys) | **Get** /users/{id}/keys | List the API keys of an account
[**GetUserCreditBalance**](PartnerAPI.md#GetUserCreditBalance) | **Get** /credits/user/{userId}/balance | Get an account&#39;s credit balance
[**GetUserCreditTransactions**](PartnerAPI.md#GetUserCreditTransactions) | **Get** /credits/user/{userId}/transactions | List an account&#39;s credit ledger
[**GetWidgets**](PartnerAPI.md#GetWidgets) | **Get** /widgets | List Widgets
[**GetWidgetsBatch**](PartnerAPI.md#GetWidgetsBatch) | **Post** /widgets/batch | Get Widgets Batch
[**ListCompositionEntryItems**](PartnerAPI.md#ListCompositionEntryItems) | **Get** /compositions/{id}/entries/{table}/items | List composition entry items with paging and filters
[**ListManagedUserEntries**](PartnerAPI.md#ListManagedUserEntries) | **Get** /managed-users/{id}/entries | List entries across a managed user&#39;s compositions
[**ListPartnerNotificationDeliveries**](PartnerAPI.md#ListPartnerNotificationDeliveries) | **Get** /partners/{partnerId}/notifications/deliveries | How your notifications reached you
[**ListPartnerNotifications**](PartnerAPI.md#ListPartnerNotifications) | **Get** /partners/{partnerId}/notifications | What your partner account was told
[**ListPartnerPresets**](PartnerAPI.md#ListPartnerPresets) | **Get** /partners/{partnerId}/presets | List the widgets a partner offers as presets
[**OperationsIdGet**](PartnerAPI.md#OperationsIdGet) | **Get** /operations/{id} | Get operation status
[**PatchCompositionContentItem**](PartnerAPI.md#PatchCompositionContentItem) | **Patch** /compositions/{id}/content/{list}/items/{itemId} | Update a content list item
[**PostPublicCompositionEmbedStatus**](PartnerAPI.md#PostPublicCompositionEmbedStatus) | **Post** /embed/compositions/status | Batch-check whether compositions are currently served for embed
[**ReadCompositionEntries**](PartnerAPI.md#ReadCompositionEntries) | **Get** /compositions/{id}/entries/{table} | Read the Entries of a Composition&#39;s Table
[**RemoveAiAnswersKnowledgeDocument**](PartnerAPI.md#RemoveAiAnswersKnowledgeDocument) | **Delete** /compositions/{id}/adapters/ai-answers/knowledge/documents/{documentId} | Remove a document from a widget&#39;s knowledge base
[**RemovePartnerAdapterConnection**](PartnerAPI.md#RemovePartnerAdapterConnection) | **Delete** /partners/{partnerId}/adapter-connections/{adapterId}/{credentialKey} | Remove an adapter key from a partner
[**RemovePartnerDataDatabase**](PartnerAPI.md#RemovePartnerDataDatabase) | **Delete** /partners/{partnerId}/data-database | Stop keeping the data of a partner&#39;s compositions in its own database
[**RemovePartnerPreset**](PartnerAPI.md#RemovePartnerPreset) | **Delete** /partners/{partnerId}/presets/{key} | Take a widget off the partner&#39;s presets
[**RemovePartnerStorageDestination**](PartnerAPI.md#RemovePartnerStorageDestination) | **Delete** /partners/{partnerId}/storage | Stop storing a partner&#39;s uploaded files in its own bucket
[**RemoveUserAdapterConnection**](PartnerAPI.md#RemoveUserAdapterConnection) | **Delete** /users/{userId}/adapter-connections/{adapterId}/{credentialKey} | Remove an adapter key from an account
[**ReplayPartnerNotificationDelivery**](PartnerAPI.md#ReplayPartnerNotificationDelivery) | **Post** /partners/{partnerId}/notifications/deliveries/{deliveryId}/replay | Send a webhook delivery again
[**RevokeManagedUserEditorSession**](PartnerAPI.md#RevokeManagedUserEditorSession) | **Delete** /managed-users/{id}/editor-sessions/{sessionId} | End one editor session of a managed user
[**RevokeManagedUserEditorSessions**](PartnerAPI.md#RevokeManagedUserEditorSessions) | **Delete** /managed-users/{id}/editor-sessions | End every editor session of a managed user
[**RotatePartnerEntryContextSecret**](PartnerAPI.md#RotatePartnerEntryContextSecret) | **Post** /partners/{partnerId}/entry-context-signing/secret | Make a secret to sign the context of your embeds
[**RotatePartnerWebhookSecret**](PartnerAPI.md#RotatePartnerWebhookSecret) | **Post** /partners/{partnerId}/notifications/webhook-secret | Make a new secret for your webhook
[**SendPartnerNotificationTestEvent**](PartnerAPI.md#SendPartnerNotificationTestEvent) | **Post** /partners/{partnerId}/notifications/test-event | Send a test event to your webhook
[**SetCompositionDataSource**](PartnerAPI.md#SetCompositionDataSource) | **Put** /compositions/{id}/data-source | Bind a public JSON data source for embed refresh
[**SetDynamicContent**](PartnerAPI.md#SetDynamicContent) | **Put** /compositions/{id}/content | Set Dynamic Content
[**SetManagedUserDesignDefaults**](PartnerAPI.md#SetManagedUserDesignDefaults) | **Put** /managed-users/{id}/design-defaults | Set or clear design defaults for one managed user
[**SetManagedUserLimits**](PartnerAPI.md#SetManagedUserLimits) | **Put** /managed-users/{id}/limits | Set or clear the monthly credit cap for one managed user
[**SetPartnerAdapterConnection**](PartnerAPI.md#SetPartnerAdapterConnection) | **Put** /partners/{partnerId}/adapter-connections/{adapterId}/{credentialKey} | Connect an adapter key to a partner
[**SetPartnerDataDatabase**](PartnerAPI.md#SetPartnerDataDatabase) | **Put** /partners/{partnerId}/data-database | Keep the data of a partner&#39;s compositions in a Neon database of its own
[**SetPartnerDesignDefaults**](PartnerAPI.md#SetPartnerDesignDefaults) | **Put** /partners/{partnerId}/design-defaults | Set or clear partner-wide design defaults
[**SetPartnerPreset**](PartnerAPI.md#SetPartnerPreset) | **Put** /partners/{partnerId}/presets/{key} | Make a widget a preset, or replace a preset
[**SetPartnerStorageDestination**](PartnerAPI.md#SetPartnerStorageDestination) | **Put** /partners/{partnerId}/storage | Set where a partner&#39;s uploaded files are stored
[**SetUserAdapterConnection**](PartnerAPI.md#SetUserAdapterConnection) | **Put** /users/{userId}/adapter-connections/{adapterId}/{credentialKey} | Connect an adapter key to an account
[**UpdateCanvas**](PartnerAPI.md#UpdateCanvas) | **Put** /canvases/{id} | Update Canvas
[**UpdateComposition**](PartnerAPI.md#UpdateComposition) | **Put** /compositions/{id} | Update Composition
[**UpdateCompositionDatabaseRecord**](PartnerAPI.md#UpdateCompositionDatabaseRecord) | **Put** /compositions/{id}/database/{table}/{recordId} | Update Record In Composition Database
[**UpdateCompositionStatus**](PartnerAPI.md#UpdateCompositionStatus) | **Put** /compositions/{id}/status | Update Composition Status
[**UpdateManagedUser**](PartnerAPI.md#UpdateManagedUser) | **Put** /managed-users/{id} | Update Managed User
[**UpdatePartnerEntryContextSigning**](PartnerAPI.md#UpdatePartnerEntryContextSigning) | **Put** /partners/{partnerId}/entry-context-signing | Require a signed context, or stop requiring it
[**UpdatePartnerNotificationSettings**](PartnerAPI.md#UpdatePartnerNotificationSettings) | **Put** /partners/{partnerId}/notifications/settings | Choose where your notifications go
[**UpdatePersonalWorkspaceDomain**](PartnerAPI.md#UpdatePersonalWorkspaceDomain) | **Put** /users/{id}/workspace/domains/{domainId} | Change a website on your list
[**UpdateUserApiKey**](PartnerAPI.md#UpdateUserApiKey) | **Put** /users/{id}/keys/{keyId} | Rename an API key, or switch it off or on
[**UploadPublicCompositionAdapterFile**](PartnerAPI.md#UploadPublicCompositionAdapterFile) | **Put** /embed/compositions/{compositionId}/adapters/upload/files/{ticket} | Send the file a visitor chose through the upload adapter of a published widget
[**UploadsGet**](PartnerAPI.md#UploadsGet) | **Get** /uploads | List the account&#39;s uploads
[**UploadsIdDelete**](PartnerAPI.md#UploadsIdDelete) | **Delete** /uploads/{id} | Delete an upload
[**UploadsIdGet**](PartnerAPI.md#UploadsIdGet) | **Get** /uploads/{id} | Get an upload by id
[**UploadsLimitsGet**](PartnerAPI.md#UploadsLimitsGet) | **Get** /uploads/limits | Upload size limits and accepted file types
[**UploadsPost**](PartnerAPI.md#UploadsPost) | **Post** /uploads | Upload a file
[**ValidateCompositionContent**](PartnerAPI.md#ValidateCompositionContent) | **Post** /compositions/{id}/content/validate | Validate Content
[**ValidateToken**](PartnerAPI.md#ValidateToken) | **Get** /tokens/validate | Validate current authentication token
[**VerifyPartnerDataDatabase**](PartnerAPI.md#VerifyPartnerDataDatabase) | **Post** /partners/{partnerId}/data-database/verify | Check that a partner&#39;s own database still works
[**VerifyPartnerStorageDestination**](PartnerAPI.md#VerifyPartnerStorageDestination) | **Post** /partners/{partnerId}/storage/verify | Check that a partner&#39;s storage destination still works



## AddAiAnswersKnowledgeDocument

> AddAiAnswersKnowledgeDocument201Response AddAiAnswersKnowledgeDocument(ctx, id).AddAiAnswersKnowledgeDocumentRequest(addAiAnswersKnowledgeDocumentRequest).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Add a document for a widget's AI to answer from



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The widget (composition) to add the document to
	addAiAnswersKnowledgeDocumentRequest := *openapiclient.NewAddAiAnswersKnowledgeDocumentRequest("Shipping and returns", "Orders ship within 2 business days. Returns are accepted for 30 days after delivery, in the original packaging.") // AddAiAnswersKnowledgeDocumentRequest | 
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.AddAiAnswersKnowledgeDocument(context.Background(), id).AddAiAnswersKnowledgeDocumentRequest(addAiAnswersKnowledgeDocumentRequest).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.AddAiAnswersKnowledgeDocument``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AddAiAnswersKnowledgeDocument`: AddAiAnswersKnowledgeDocument201Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.AddAiAnswersKnowledgeDocument`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The widget (composition) to add the document to | 

### Other Parameters

Other parameters are passed through a pointer to a apiAddAiAnswersKnowledgeDocumentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **addAiAnswersKnowledgeDocumentRequest** | [**AddAiAnswersKnowledgeDocumentRequest**](AddAiAnswersKnowledgeDocumentRequest.md) |  | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**AddAiAnswersKnowledgeDocument201Response**](AddAiAnswersKnowledgeDocument201Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AddPersonalWorkspaceDomain

> PersonalWorkspaceDomainResultResponse AddPersonalWorkspaceDomain(ctx, id).AddDomainRequest(addDomainRequest).Execute()

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
	resp, r, err := apiClient.PartnerAPI.AddPersonalWorkspaceDomain(context.Background(), id).AddDomainRequest(addDomainRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.AddPersonalWorkspaceDomain``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AddPersonalWorkspaceDomain`: PersonalWorkspaceDomainResultResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.AddPersonalWorkspaceDomain`: %v\n", resp)
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


## CallPublicCompositionAdapter

> PublicAdapterCallResult CallPublicCompositionAdapter(ctx, compositionId, adapterId, operation).PublicAdapterCallRequest(publicAdapterCallRequest).Execute()

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
	resp, r, err := apiClient.PartnerAPI.CallPublicCompositionAdapter(context.Background(), compositionId, adapterId, operation).PublicAdapterCallRequest(publicAdapterCallRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.CallPublicCompositionAdapter``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CallPublicCompositionAdapter`: PublicAdapterCallResult
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.CallPublicCompositionAdapter`: %v\n", resp)
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


## CheckCompositionAccess

> CheckCompositionAccessResponse CheckCompositionAccess(ctx, id).Execute()

Check Composition Access



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Composition ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.CheckCompositionAccess(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.CheckCompositionAccess``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CheckCompositionAccess`: CheckCompositionAccessResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.CheckCompositionAccess`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Composition ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCheckCompositionAccessRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CheckCompositionAccessResponse**](CheckCompositionAccessResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CopyPresetForManagedUser

> PartnerPresetCopyResponse CopyPresetForManagedUser(ctx, id, key).IdempotencyKey(idempotencyKey).CopyPartnerPresetRequest(copyPartnerPresetRequest).Execute()

Give a managed user a copy of one of your presets



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The managed user to give the copy to (Widgetic's id for the user)
	key := "key_example" // string | The key of the preset to copy
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	copyPartnerPresetRequest := *openapiclient.NewCopyPartnerPresetRequest() // CopyPartnerPresetRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.CopyPresetForManagedUser(context.Background(), id, key).IdempotencyKey(idempotencyKey).CopyPartnerPresetRequest(copyPartnerPresetRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.CopyPresetForManagedUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CopyPresetForManagedUser`: PartnerPresetCopyResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.CopyPresetForManagedUser`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The managed user to give the copy to (Widgetic&#39;s id for the user) | 
**key** | **string** | The key of the preset to copy | 

### Other Parameters

Other parameters are passed through a pointer to a apiCopyPresetForManagedUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **copyPartnerPresetRequest** | [**CopyPartnerPresetRequest**](CopyPartnerPresetRequest.md) |  | 

### Return type

[**PartnerPresetCopyResponse**](PartnerPresetCopyResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateCanvas

> CanvasResponse CreateCanvas(ctx).CreateCanvasRequest(createCanvasRequest).Execute()

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
	resp, r, err := apiClient.PartnerAPI.CreateCanvas(context.Background()).CreateCanvasRequest(createCanvasRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.CreateCanvas``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateCanvas`: CanvasResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.CreateCanvas`: %v\n", resp)
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


## CreateComposition

> CreateCompositionFromWidget201Response CreateComposition(ctx).IdempotencyKey(idempotencyKey).CreateCompositionRequest(createCompositionRequest).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Create Composition



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
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	createCompositionRequest := *openapiclient.NewCreateCompositionRequest("My New Composition", "123e4567-e89b-12d3-a456-426614174002") // CreateCompositionRequest | 
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.CreateComposition(context.Background()).IdempotencyKey(idempotencyKey).CreateCompositionRequest(createCompositionRequest).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.CreateComposition``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateComposition`: CreateCompositionFromWidget201Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.CreateComposition`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateCompositionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **createCompositionRequest** | [**CreateCompositionRequest**](CreateCompositionRequest.md) |  | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

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


## CreateCompositionContentItem

> CreateCompositionContentItem201Response CreateCompositionContentItem(ctx, id, list).IdempotencyKey(idempotencyKey).CreateCompositionContentItemRequest(createCompositionContentItemRequest).IfMatch(ifMatch).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Add a content list item



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
	list := "list_example" // string | List name from the content schema (`contentItems`) or `items`
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	createCompositionContentItemRequest := *openapiclient.NewCreateCompositionContentItemRequest() // CreateCompositionContentItemRequest | 
	ifMatch := "ifMatch_example" // string | Optional content version from ETag (optional)
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.CreateCompositionContentItem(context.Background(), id, list).IdempotencyKey(idempotencyKey).CreateCompositionContentItemRequest(createCompositionContentItemRequest).IfMatch(ifMatch).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.CreateCompositionContentItem``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateCompositionContentItem`: CreateCompositionContentItem201Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.CreateCompositionContentItem`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**list** | **string** | List name from the content schema (&#x60;contentItems&#x60;) or &#x60;items&#x60; | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateCompositionContentItemRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **createCompositionContentItemRequest** | [**CreateCompositionContentItemRequest**](CreateCompositionContentItemRequest.md) |  | 
 **ifMatch** | **string** | Optional content version from ETag | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**CreateCompositionContentItem201Response**](CreateCompositionContentItem201Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateCompositionDatabaseRecord

> CreateCompositionDatabaseRecord201Response CreateCompositionDatabaseRecord(ctx, id, table).IdempotencyKey(idempotencyKey).Body(body).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Create Record In Composition Database



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the composition
	table := "table_example" // string | Name of the database table
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	body := map[string]interface{}{ ... } // map[string]interface{} | 
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.CreateCompositionDatabaseRecord(context.Background(), id, table).IdempotencyKey(idempotencyKey).Body(body).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.CreateCompositionDatabaseRecord``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateCompositionDatabaseRecord`: CreateCompositionDatabaseRecord201Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.CreateCompositionDatabaseRecord`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the composition | 
**table** | **string** | Name of the database table | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateCompositionDatabaseRecordRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **body** | **map[string]interface{}** |  | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**CreateCompositionDatabaseRecord201Response**](CreateCompositionDatabaseRecord201Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateCompositionFromPreset

> CreateCompositionFromWidget201Response CreateCompositionFromPreset(ctx, id, key).IdempotencyKey(idempotencyKey).CreateCompositionFromPresetRequest(createCompositionFromPresetRequest).Execute()

Create a composition from one of your presets in one call



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
	key := "key_example" // string | 
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	createCompositionFromPresetRequest := *openapiclient.NewCreateCompositionFromPresetRequest("Name_example") // CreateCompositionFromPresetRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.CreateCompositionFromPreset(context.Background(), id, key).IdempotencyKey(idempotencyKey).CreateCompositionFromPresetRequest(createCompositionFromPresetRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.CreateCompositionFromPreset``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateCompositionFromPreset`: CreateCompositionFromWidget201Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.CreateCompositionFromPreset`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**key** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateCompositionFromPresetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **createCompositionFromPresetRequest** | [**CreateCompositionFromPresetRequest**](CreateCompositionFromPresetRequest.md) |  | 

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


## CreateCompositionFromWidget

> CreateCompositionFromWidget201Response CreateCompositionFromWidget(ctx, id).IdempotencyKey(idempotencyKey).CreateCompositionFromWidgetRequest(createCompositionFromWidgetRequest).Execute()

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
	resp, r, err := apiClient.PartnerAPI.CreateCompositionFromWidget(context.Background(), id).IdempotencyKey(idempotencyKey).CreateCompositionFromWidgetRequest(createCompositionFromWidgetRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.CreateCompositionFromWidget``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateCompositionFromWidget`: CreateCompositionFromWidget201Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.CreateCompositionFromWidget`: %v\n", resp)
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


## CreateManagedUser

> ManagedUserResponse CreateManagedUser(ctx).IdempotencyKey(idempotencyKey).CreateManagedUserRequest(createManagedUserRequest).Execute()

Create Managed User



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
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	createManagedUserRequest := *openapiclient.NewCreateManagedUserRequest("external-user-123") // CreateManagedUserRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.CreateManagedUser(context.Background()).IdempotencyKey(idempotencyKey).CreateManagedUserRequest(createManagedUserRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.CreateManagedUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateManagedUser`: ManagedUserResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.CreateManagedUser`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateManagedUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **createManagedUserRequest** | [**CreateManagedUserRequest**](CreateManagedUserRequest.md) |  | 

### Return type

[**ManagedUserResponse**](ManagedUserResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateManagedUserEditorSession

> EditorSessionResponse CreateManagedUserEditorSession(ctx, id).CreateEditorSessionRequest(createEditorSessionRequest).Execute()

Create an editor session for a managed user



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The managed user the session is for (Widgetic's id for the user)
	createEditorSessionRequest := *openapiclient.NewCreateEditorSessionRequest([]string{"Surfaces_example"}) // CreateEditorSessionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.CreateManagedUserEditorSession(context.Background(), id).CreateEditorSessionRequest(createEditorSessionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.CreateManagedUserEditorSession``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateManagedUserEditorSession`: EditorSessionResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.CreateManagedUserEditorSession`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The managed user the session is for (Widgetic&#39;s id for the user) | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateManagedUserEditorSessionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createEditorSessionRequest** | [**CreateEditorSessionRequest**](CreateEditorSessionRequest.md) |  | 

### Return type

[**EditorSessionResponse**](EditorSessionResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreatePartnerExtraCreditsInvoice

> PartnerExtraCreditsInvoiceResponse CreatePartnerExtraCreditsInvoice(ctx, partnerId).IdempotencyKey(idempotencyKey).RequestExtraCredits(requestExtraCredits).Execute()

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
	resp, r, err := apiClient.PartnerAPI.CreatePartnerExtraCreditsInvoice(context.Background(), partnerId).IdempotencyKey(idempotencyKey).RequestExtraCredits(requestExtraCredits).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.CreatePartnerExtraCreditsInvoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreatePartnerExtraCreditsInvoice`: PartnerExtraCreditsInvoiceResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.CreatePartnerExtraCreditsInvoice`: %v\n", resp)
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


## CreatePublicCompositionEntry

> PublicCompositionEntryCreated CreatePublicCompositionEntry(ctx, compositionId, table).PublicCompositionEntryRequest(publicCompositionEntryRequest).XWidgeticWriteToken(xWidgeticWriteToken).Execute()

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.CreatePublicCompositionEntry(context.Background(), compositionId, table).PublicCompositionEntryRequest(publicCompositionEntryRequest).XWidgeticWriteToken(xWidgeticWriteToken).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.CreatePublicCompositionEntry``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreatePublicCompositionEntry`: PublicCompositionEntryCreated
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.CreatePublicCompositionEntry`: %v\n", resp)
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


## CreateUserApiKey

> CreatedUserApiKeyResponse CreateUserApiKey(ctx, id).IdempotencyKey(idempotencyKey).CreateUserApiKeyRequest(createUserApiKeyRequest).Execute()

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
	resp, r, err := apiClient.PartnerAPI.CreateUserApiKey(context.Background(), id).IdempotencyKey(idempotencyKey).CreateUserApiKeyRequest(createUserApiKeyRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.CreateUserApiKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateUserApiKey`: CreatedUserApiKeyResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.CreateUserApiKey`: %v\n", resp)
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


## CreateWidget

> CreateWidget201Response CreateWidget(ctx).IdempotencyKey(idempotencyKey).CreateWidgetRequest(createWidgetRequest).Execute()

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
	resp, r, err := apiClient.PartnerAPI.CreateWidget(context.Background()).IdempotencyKey(idempotencyKey).CreateWidgetRequest(createWidgetRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.CreateWidget``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateWidget`: CreateWidget201Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.CreateWidget`: %v\n", resp)
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


## DeleteCanvas

> CanvasResponse DeleteCanvas(ctx, id).Execute()

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
	resp, r, err := apiClient.PartnerAPI.DeleteCanvas(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.DeleteCanvas``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteCanvas`: CanvasResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.DeleteCanvas`: %v\n", resp)
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


## DeleteComposition

> DeleteComposition(ctx, id).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Delete Composition



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of the composition to delete
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.PartnerAPI.DeleteComposition(context.Background(), id).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.DeleteComposition``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The ID of the composition to delete | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteCompositionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

 (empty response body)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteCompositionContentItem

> DeleteCompositionContentItemResponse DeleteCompositionContentItem(ctx, id, list, itemId).IdempotencyKey(idempotencyKey).IfMatch(ifMatch).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Delete a content list item

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
	list := "list_example" // string | 
	itemId := "itemId_example" // string | 
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	ifMatch := "ifMatch_example" // string |  (optional)
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.DeleteCompositionContentItem(context.Background(), id, list, itemId).IdempotencyKey(idempotencyKey).IfMatch(ifMatch).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.DeleteCompositionContentItem``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteCompositionContentItem`: DeleteCompositionContentItemResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.DeleteCompositionContentItem`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**list** | **string** |  | 
**itemId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteCompositionContentItemRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **ifMatch** | **string** |  | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**DeleteCompositionContentItemResponse**](DeleteCompositionContentItemResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteCompositionDataSource

> DeleteCompositionDataSourceResponse DeleteCompositionDataSource(ctx, id).IdempotencyKey(idempotencyKey).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Remove the composition data source binding



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
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.DeleteCompositionDataSource(context.Background(), id).IdempotencyKey(idempotencyKey).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.DeleteCompositionDataSource``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteCompositionDataSource`: DeleteCompositionDataSourceResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.DeleteCompositionDataSource`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteCompositionDataSourceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**DeleteCompositionDataSourceResponse**](DeleteCompositionDataSourceResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteCompositionDatabaseRecord

> CreateCompositionDatabaseRecord201Response DeleteCompositionDatabaseRecord(ctx, id, table, recordId).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Delete Record From Composition Database



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the composition
	table := "table_example" // string | Name of the database table
	recordId := "recordId_example" // string | ID of the record to delete
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.DeleteCompositionDatabaseRecord(context.Background(), id, table, recordId).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.DeleteCompositionDatabaseRecord``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteCompositionDatabaseRecord`: CreateCompositionDatabaseRecord201Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.DeleteCompositionDatabaseRecord`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the composition | 
**table** | **string** | Name of the database table | 
**recordId** | **string** | ID of the record to delete | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteCompositionDatabaseRecordRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**CreateCompositionDatabaseRecord201Response**](CreateCompositionDatabaseRecord201Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteCompositionEntryItems

> CompositionEntryDeleteSuccess DeleteCompositionEntryItems(ctx, id, table).Ids(ids).Context(context).Filter(filter).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Delete composition entry items by id or host context



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
	table := "table_example" // string | 
	ids := "ids_example" // string |  (optional)
	context := map[string]string{"key": map[string]string{"key": "Inner_example"}} // map[string]string | Host context filters as `context[key]=value` (max 5 keys, counting dotted `context.key` too). Use `column.<name>=value` for columns whose names collide with reserved parameters. (optional)
	filter := map[string]string{"key": map[string]string{"key": "Inner_example"}} // map[string]string | Column filters as `filter[columnName]=value` (same meaning as bare `columnName=value` or `column.columnName=value`; max 10 column filters counting all spellings). A plain `filter=value` still filters a column named `filter`. (optional)
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.DeleteCompositionEntryItems(context.Background(), id, table).Ids(ids).Context(context).Filter(filter).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.DeleteCompositionEntryItems``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteCompositionEntryItems`: CompositionEntryDeleteSuccess
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.DeleteCompositionEntryItems`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**table** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteCompositionEntryItemsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **ids** | **string** |  | 
 **context** | **map[string]map[string]string** | Host context filters as &#x60;context[key]&#x3D;value&#x60; (max 5 keys, counting dotted &#x60;context.key&#x60; too). Use &#x60;column.&lt;name&gt;&#x3D;value&#x60; for columns whose names collide with reserved parameters. | 
 **filter** | **map[string]map[string]string** | Column filters as &#x60;filter[columnName]&#x3D;value&#x60; (same meaning as bare &#x60;columnName&#x3D;value&#x60; or &#x60;column.columnName&#x3D;value&#x60;; max 10 column filters counting all spellings). A plain &#x60;filter&#x3D;value&#x60; still filters a column named &#x60;filter&#x60;. | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**CompositionEntryDeleteSuccess**](CompositionEntryDeleteSuccess.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteManagedUser

> DeleteManagedUser200Response DeleteManagedUser(ctx, id).Execute()

Delete Managed User



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the managed user to delete

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.DeleteManagedUser(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.DeleteManagedUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteManagedUser`: DeleteManagedUser200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.DeleteManagedUser`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the managed user to delete | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteManagedUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DeleteManagedUser200Response**](DeleteManagedUser200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeletePersonalWorkspaceDomain

> DeletePersonalWorkspaceDomainResponse DeletePersonalWorkspaceDomain(ctx, id, domainId).Execute()

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
	resp, r, err := apiClient.PartnerAPI.DeletePersonalWorkspaceDomain(context.Background(), id, domainId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.DeletePersonalWorkspaceDomain``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeletePersonalWorkspaceDomain`: DeletePersonalWorkspaceDomainResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.DeletePersonalWorkspaceDomain`: %v\n", resp)
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


## DeleteUserApiKey

> DeleteUserApiKeyResponse DeleteUserApiKey(ctx, id, keyId).Execute()

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
	resp, r, err := apiClient.PartnerAPI.DeleteUserApiKey(context.Background(), id, keyId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.DeleteUserApiKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteUserApiKey`: DeleteUserApiKeyResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.DeleteUserApiKey`: %v\n", resp)
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


## DescribeCompositionEntries

> CompositionEntriesDescriptionResponse DescribeCompositionEntries(ctx, id).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Describe What a Composition Keeps



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the composition
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.DescribeCompositionEntries(context.Background(), id).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.DescribeCompositionEntries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DescribeCompositionEntries`: CompositionEntriesDescriptionResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.DescribeCompositionEntries`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the composition | 

### Other Parameters

Other parameters are passed through a pointer to a apiDescribeCompositionEntriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**CompositionEntriesDescriptionResponse**](CompositionEntriesDescriptionResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DuplicateComposition

> DuplicateComposition202Response DuplicateComposition(ctx, id).IdempotencyKey(idempotencyKey).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).DuplicateCompositionRequest(duplicateCompositionRequest).Execute()

Duplicate Composition



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the composition to duplicate
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	duplicateCompositionRequest := *openapiclient.NewDuplicateCompositionRequest() // DuplicateCompositionRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.DuplicateComposition(context.Background(), id).IdempotencyKey(idempotencyKey).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).DuplicateCompositionRequest(duplicateCompositionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.DuplicateComposition``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DuplicateComposition`: DuplicateComposition202Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.DuplicateComposition`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the composition to duplicate | 

### Other Parameters

Other parameters are passed through a pointer to a apiDuplicateCompositionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **duplicateCompositionRequest** | [**DuplicateCompositionRequest**](DuplicateCompositionRequest.md) |  | 

### Return type

[**DuplicateComposition202Response**](DuplicateComposition202Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ExportCompositionEntryItems

> string ExportCompositionEntryItems(ctx, id, table).Format(format).Order(order).Since(since).Until(until).Context(context).Filter(filter).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Export composition entry items



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	table := "table_example" // string | 
	format := "format_example" // string |  (optional) (default to "csv")
	order := "order_example" // string | `desc` (the default) lists the newest entry first, `asc` the oldest. Entries are sorted by their time, then by their id (compared as text, byte by byte) in the same direction, so the order of two entries made at the same instant is always the same; an entry with no time counts as the oldest. A table with no time column is sorted by its id. The managed-user feed sorts by time, then by composition id, table and id.  (optional) (default to "desc")
	since := time.Now() // time.Time | Only entries made at this time or later: `since` is INCLUSIVE (an entry made at exactly `since` is returned). A date and time with an offset, such as `2026-10-01T00:00:00Z`; anything else answers 400 `INVALID_SINCE`. An entry with no time never matches, and a table with no time column answers 400 `ENTRY_TABLE_HAS_NO_TIME`.  (optional)
	until := time.Now() // time.Time | Only entries made before this time: `until` is EXCLUSIVE (an entry made at exactly `until` is NOT returned), so `since=A&until=B` followed by `since=B&until=C` counts every entry once. Same form and same refusals as `since` (400 `INVALID_UNTIL`).  (optional)
	context := map[string]string{"key": map[string]string{"key": "Inner_example"}} // map[string]string | Host context filters as `context[key]=value` (max 5 keys, counting dotted `context.key` too). Use `column.<name>=value` for columns whose names collide with reserved parameters. (optional)
	filter := map[string]string{"key": map[string]string{"key": "Inner_example"}} // map[string]string | Column filters as `filter[columnName]=value` (same meaning as bare `columnName=value` or `column.columnName=value`; max 10 column filters counting all spellings). A plain `filter=value` still filters a column named `filter`. (optional)
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.ExportCompositionEntryItems(context.Background(), id, table).Format(format).Order(order).Since(since).Until(until).Context(context).Filter(filter).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.ExportCompositionEntryItems``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ExportCompositionEntryItems`: string
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.ExportCompositionEntryItems`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**table** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiExportCompositionEntryItemsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **format** | **string** |  | [default to &quot;csv&quot;]
 **order** | **string** | &#x60;desc&#x60; (the default) lists the newest entry first, &#x60;asc&#x60; the oldest. Entries are sorted by their time, then by their id (compared as text, byte by byte) in the same direction, so the order of two entries made at the same instant is always the same; an entry with no time counts as the oldest. A table with no time column is sorted by its id. The managed-user feed sorts by time, then by composition id, table and id.  | [default to &quot;desc&quot;]
 **since** | **time.Time** | Only entries made at this time or later: &#x60;since&#x60; is INCLUSIVE (an entry made at exactly &#x60;since&#x60; is returned). A date and time with an offset, such as &#x60;2026-10-01T00:00:00Z&#x60;; anything else answers 400 &#x60;INVALID_SINCE&#x60;. An entry with no time never matches, and a table with no time column answers 400 &#x60;ENTRY_TABLE_HAS_NO_TIME&#x60;.  | 
 **until** | **time.Time** | Only entries made before this time: &#x60;until&#x60; is EXCLUSIVE (an entry made at exactly &#x60;until&#x60; is NOT returned), so &#x60;since&#x3D;A&amp;until&#x3D;B&#x60; followed by &#x60;since&#x3D;B&amp;until&#x3D;C&#x60; counts every entry once. Same form and same refusals as &#x60;since&#x60; (400 &#x60;INVALID_UNTIL&#x60;).  | 
 **context** | **map[string]map[string]string** | Host context filters as &#x60;context[key]&#x3D;value&#x60; (max 5 keys, counting dotted &#x60;context.key&#x60; too). Use &#x60;column.&lt;name&gt;&#x3D;value&#x60; for columns whose names collide with reserved parameters. | 
 **filter** | **map[string]map[string]string** | Column filters as &#x60;filter[columnName]&#x3D;value&#x60; (same meaning as bare &#x60;columnName&#x3D;value&#x60; or &#x60;column.columnName&#x3D;value&#x60;; max 10 column filters counting all spellings). A plain &#x60;filter&#x3D;value&#x60; still filters a column named &#x60;filter&#x60;. | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

**string**

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/csv, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAiAnswersKnowledge

> GetAiAnswersKnowledge200Response GetAiAnswersKnowledge(ctx, id).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

See the documents a widget's AI answers from



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The widget (composition) whose documents to list
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.GetAiAnswersKnowledge(context.Background(), id).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetAiAnswersKnowledge``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAiAnswersKnowledge`: GetAiAnswersKnowledge200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetAiAnswersKnowledge`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The widget (composition) whose documents to list | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAiAnswersKnowledgeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**GetAiAnswersKnowledge200Response**](GetAiAnswersKnowledge200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAllCanvases

> GetAllCanvasesResponse GetAllCanvases(ctx).Page(page).Size(size).Sort(sort).CreatedAfter(createdAfter).CreatedBefore(createdBefore).UpdatedAfter(updatedAfter).UpdatedBefore(updatedBefore).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetAllCanvases(context.Background()).Page(page).Size(size).Sort(sort).CreatedAfter(createdAfter).CreatedBefore(createdBefore).UpdatedAfter(updatedAfter).UpdatedBefore(updatedBefore).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetAllCanvases``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAllCanvases`: GetAllCanvasesResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetAllCanvases`: %v\n", resp)
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


## GetAllCompositions

> GetAllCompositions200Response GetAllCompositions(ctx).Page(page).Size(size).Sort(sort).WidgetId(widgetId).Workspace(workspace).ProjectFolder(projectFolder).Status(status).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Get All Compositions



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
	page := int32(56) // int32 | Page number for pagination (optional) (default to 1)
	size := int32(56) // int32 | Number of items per page (optional) (default to 20)
	sort := "createdAt:desc" // string | The order of the list, as `<field>:<asc|desc>`. The field is `createdAt`, `updatedAt`, `name` or `status` (the snake_case spelling, such as `created_at`, is read too). `asc` or `desc` alone orders by `createdAt`. Default: `createdAt:desc`. Any other field is a 400.  (optional)
	widgetId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Filter compositions by widget ID (optional)
	workspace := "workspace_example" // string | Filter by workspace (optional)
	projectFolder := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Only the compositions in this project (the project's id). (optional)
	status := "status_example" // string | Only the compositions in this status. Without it, every status is listed. (optional)
	managedUserId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | List only the compositions made for this managed user (Widgetic's id for the user). Send this or `managedUserExternalId`, not both. Send it as `managedUserId`; the snake_case spelling `managed_user_id` is refused with a 400, not ignored. (optional)
	managedUserExternalId := "managedUserExternalId_example" // string | List only the compositions made for the managed user you registered with this `externalId` (your own identifier for the user). Send this or `managedUserId`, not both. (optional)
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.GetAllCompositions(context.Background()).Page(page).Size(size).Sort(sort).WidgetId(widgetId).Workspace(workspace).ProjectFolder(projectFolder).Status(status).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetAllCompositions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAllCompositions`: GetAllCompositions200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetAllCompositions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAllCompositionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** | Page number for pagination | [default to 1]
 **size** | **int32** | Number of items per page | [default to 20]
 **sort** | **string** | The order of the list, as &#x60;&lt;field&gt;:&lt;asc|desc&gt;&#x60;. The field is &#x60;createdAt&#x60;, &#x60;updatedAt&#x60;, &#x60;name&#x60; or &#x60;status&#x60; (the snake_case spelling, such as &#x60;created_at&#x60;, is read too). &#x60;asc&#x60; or &#x60;desc&#x60; alone orders by &#x60;createdAt&#x60;. Default: &#x60;createdAt:desc&#x60;. Any other field is a 400.  | 
 **widgetId** | **string** | Filter compositions by widget ID | 
 **workspace** | **string** | Filter by workspace | 
 **projectFolder** | **string** | Only the compositions in this project (the project&#39;s id). | 
 **status** | **string** | Only the compositions in this status. Without it, every status is listed. | 
 **managedUserId** | **string** | List only the compositions made for this managed user (Widgetic&#39;s id for the user). Send this or &#x60;managedUserExternalId&#x60;, not both. Send it as &#x60;managedUserId&#x60;; the snake_case spelling &#x60;managed_user_id&#x60; is refused with a 400, not ignored. | 
 **managedUserExternalId** | **string** | List only the compositions made for the managed user you registered with this &#x60;externalId&#x60; (your own identifier for the user). Send this or &#x60;managedUserId&#x60;, not both. | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**GetAllCompositions200Response**](GetAllCompositions200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAllManagedUsers

> GetAllManagedUsers200Response GetAllManagedUsers(ctx).Page(page).Size(size).Sort(sort).Execute()

Get Managed Users



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
	page := int32(56) // int32 | Page number for pagination (optional) (default to 1)
	size := int32(56) // int32 | Number of items per page (optional) (default to 10)
	sort := "sort_example" // string | Sort field and direction, `<field>:<asc|desc>`. The field is `createdAt`, `updatedAt` or `externalId` (the snake_case spellings `created_at`, `updated_at` and `external_id` work too); `asc` or `desc` alone sorts by `createdAt`. Any other field is a 400. (optional) (default to "createdAt:desc")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.GetAllManagedUsers(context.Background()).Page(page).Size(size).Sort(sort).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetAllManagedUsers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAllManagedUsers`: GetAllManagedUsers200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetAllManagedUsers`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAllManagedUsersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** | Page number for pagination | [default to 1]
 **size** | **int32** | Number of items per page | [default to 10]
 **sort** | **string** | Sort field and direction, &#x60;&lt;field&gt;:&lt;asc|desc&gt;&#x60;. The field is &#x60;createdAt&#x60;, &#x60;updatedAt&#x60; or &#x60;externalId&#x60; (the snake_case spellings &#x60;created_at&#x60;, &#x60;updated_at&#x60; and &#x60;external_id&#x60; work too); &#x60;asc&#x60; or &#x60;desc&#x60; alone sorts by &#x60;createdAt&#x60;. Any other field is a 400. | [default to &quot;createdAt:desc&quot;]

### Return type

[**GetAllManagedUsers200Response**](GetAllManagedUsers200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCanvas

> CanvasResponse GetCanvas(ctx, id).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetCanvas(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetCanvas``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCanvas`: CanvasResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetCanvas`: %v\n", resp)
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


## GetCompositionById

> CreateCompositionFromWidget201Response GetCompositionById(ctx, id).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Get Composition



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Composition ID
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.GetCompositionById(context.Background(), id).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetCompositionById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCompositionById`: CreateCompositionFromWidget201Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetCompositionById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Composition ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCompositionByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**CreateCompositionFromWidget201Response**](CreateCompositionFromWidget201Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCompositionContent

> GetCompositionContentResponse GetCompositionContent(ctx, id).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Get Current Content



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the composition
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.GetCompositionContent(context.Background(), id).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetCompositionContent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCompositionContent`: GetCompositionContentResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetCompositionContent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the composition | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCompositionContentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**GetCompositionContentResponse**](GetCompositionContentResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCompositionContentSchema

> GetCompositionContentSchemaResponse GetCompositionContentSchema(ctx, id).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Get Content Schema



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the composition
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.GetCompositionContentSchema(context.Background(), id).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetCompositionContentSchema``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCompositionContentSchema`: GetCompositionContentSchemaResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetCompositionContentSchema`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the composition | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCompositionContentSchemaRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**GetCompositionContentSchemaResponse**](GetCompositionContentSchemaResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCompositionDataSource

> GetCompositionDataSourceResponse GetCompositionDataSource(ctx, id).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Read the composition data source binding



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
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.GetCompositionDataSource(context.Background(), id).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetCompositionDataSource``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCompositionDataSource`: GetCompositionDataSourceResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetCompositionDataSource`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCompositionDataSourceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**GetCompositionDataSourceResponse**](GetCompositionDataSourceResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCompositionDatabaseRecord

> CreateCompositionDatabaseRecord201Response GetCompositionDatabaseRecord(ctx, id, table, recordId).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Get Record From Composition Database



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the composition
	table := "table_example" // string | Name of the database table
	recordId := "recordId_example" // string | ID of the record to retrieve
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.GetCompositionDatabaseRecord(context.Background(), id, table, recordId).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetCompositionDatabaseRecord``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCompositionDatabaseRecord`: CreateCompositionDatabaseRecord201Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetCompositionDatabaseRecord`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the composition | 
**table** | **string** | Name of the database table | 
**recordId** | **string** | ID of the record to retrieve | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCompositionDatabaseRecordRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**CreateCompositionDatabaseRecord201Response**](CreateCompositionDatabaseRecord201Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCompositionDatabaseRecords

> GetCompositionDatabaseRecords200Response GetCompositionDatabaseRecords(ctx, id, table).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Get All Records From Composition Database Table



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the composition
	table := "table_example" // string | Name of the database table
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.GetCompositionDatabaseRecords(context.Background(), id, table).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetCompositionDatabaseRecords``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCompositionDatabaseRecords`: GetCompositionDatabaseRecords200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetCompositionDatabaseRecords`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the composition | 
**table** | **string** | Name of the database table | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCompositionDatabaseRecordsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**GetCompositionDatabaseRecords200Response**](GetCompositionDatabaseRecords200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCompositionDesign

> GetCompositionDesignResponse GetCompositionDesign(ctx, id).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Get Composition Design



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the composition
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.GetCompositionDesign(context.Background(), id).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetCompositionDesign``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCompositionDesign`: GetCompositionDesignResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetCompositionDesign`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the composition | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCompositionDesignRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**GetCompositionDesignResponse**](GetCompositionDesignResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCompositionDesignSchema

> GetCompositionDesignSchemaResponse GetCompositionDesignSchema(ctx, id).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Get Design Schema



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the composition
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.GetCompositionDesignSchema(context.Background(), id).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetCompositionDesignSchema``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCompositionDesignSchema`: GetCompositionDesignSchemaResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetCompositionDesignSchema`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the composition | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCompositionDesignSchemaRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**GetCompositionDesignSchemaResponse**](GetCompositionDesignSchemaResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCompositionEmbedSchema

> GetCompositionEmbedSchemaResponse GetCompositionEmbedSchema(ctx, id).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Get Embed Schema



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the composition
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.GetCompositionEmbedSchema(context.Background(), id).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetCompositionEmbedSchema``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCompositionEmbedSchema`: GetCompositionEmbedSchemaResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetCompositionEmbedSchema`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the composition | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCompositionEmbedSchemaRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**GetCompositionEmbedSchemaResponse**](GetCompositionEmbedSchemaResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCompositionEmbedSettings

> GetCompositionEmbedSettingsResponse GetCompositionEmbedSettings(ctx, id).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Get Composition Embed Settings



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the composition
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.GetCompositionEmbedSettings(context.Background(), id).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetCompositionEmbedSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCompositionEmbedSettings`: GetCompositionEmbedSettingsResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetCompositionEmbedSettings`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the composition | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCompositionEmbedSettingsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**GetCompositionEmbedSettingsResponse**](GetCompositionEmbedSettingsResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCompositionPreview

> GetCompositionPreviewResponse GetCompositionPreview(ctx, id).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Get Composition Preview



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the composition
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.GetCompositionPreview(context.Background(), id).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetCompositionPreview``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCompositionPreview`: GetCompositionPreviewResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetCompositionPreview`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the composition | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCompositionPreviewRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**GetCompositionPreviewResponse**](GetCompositionPreviewResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCompositionVersions

> GetCompositionVersions200Response GetCompositionVersions(ctx, id).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Get Composition Versions



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Composition ID
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.GetCompositionVersions(context.Background(), id).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetCompositionVersions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCompositionVersions`: GetCompositionVersions200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetCompositionVersions`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Composition ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCompositionVersionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**GetCompositionVersions200Response**](GetCompositionVersions200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCompositionsBatch

> GetCompositionsBatchResponse GetCompositionsBatch(ctx).GetCompositionsBatchRequest(getCompositionsBatchRequest).Execute()

Get Compositions Batch



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
	getCompositionsBatchRequest := *openapiclient.NewGetCompositionsBatchRequest([]string{"CompositionIds_example"}) // GetCompositionsBatchRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.GetCompositionsBatch(context.Background()).GetCompositionsBatchRequest(getCompositionsBatchRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetCompositionsBatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCompositionsBatch`: GetCompositionsBatchResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetCompositionsBatch`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetCompositionsBatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **getCompositionsBatchRequest** | [**GetCompositionsBatchRequest**](GetCompositionsBatchRequest.md) |  | 

### Return type

[**GetCompositionsBatchResponse**](GetCompositionsBatchResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetInvoicesByPartnerId

> GetInvoicesByPartnerId200Response GetInvoicesByPartnerId(ctx, partnerId).Status(status).Limit(limit).Offset(offset).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetInvoicesByPartnerId(context.Background(), partnerId).Status(status).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetInvoicesByPartnerId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetInvoicesByPartnerId`: GetInvoicesByPartnerId200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetInvoicesByPartnerId`: %v\n", resp)
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


## GetManagedUserById

> ManagedUserResponse GetManagedUserById(ctx, id).Execute()

Get Managed User By ID



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the managed user to retrieve

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.GetManagedUserById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetManagedUserById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetManagedUserById`: ManagedUserResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetManagedUserById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the managed user to retrieve | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetManagedUserByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ManagedUserResponse**](ManagedUserResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetManagedUserDesignDefaults

> GetPartnerDesignDefaults200Response GetManagedUserDesignDefaults(ctx, id).Execute()

Read design defaults for one managed user

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
	resp, r, err := apiClient.PartnerAPI.GetManagedUserDesignDefaults(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetManagedUserDesignDefaults``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetManagedUserDesignDefaults`: GetPartnerDesignDefaults200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetManagedUserDesignDefaults`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetManagedUserDesignDefaultsRequest struct via the builder pattern


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


## GetManagedUserEntitlements

> GetManagedUserEntitlementsResponse GetManagedUserEntitlements(ctx, managedUserId).IncludeExpired(includeExpired).Feature(feature).Source(source).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetManagedUserEntitlements(context.Background(), managedUserId).IncludeExpired(includeExpired).Feature(feature).Source(source).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetManagedUserEntitlements``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetManagedUserEntitlements`: GetManagedUserEntitlementsResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetManagedUserEntitlements`: %v\n", resp)
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


## GetManagedUserLimits

> GetManagedUserLimits200Response GetManagedUserLimits(ctx, id).Execute()

Read monthly credit cap and usage for one managed user

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
	resp, r, err := apiClient.PartnerAPI.GetManagedUserLimits(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetManagedUserLimits``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetManagedUserLimits`: GetManagedUserLimits200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetManagedUserLimits`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetManagedUserLimitsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetManagedUserLimits200Response**](GetManagedUserLimits200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetManagedUserStorageUsage

> GetManagedUserStorageUsage200Response GetManagedUserStorageUsage(ctx, id).Execute()

Storage used by one managed user's uploads

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
	resp, r, err := apiClient.PartnerAPI.GetManagedUserStorageUsage(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetManagedUserStorageUsage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetManagedUserStorageUsage`: GetManagedUserStorageUsage200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetManagedUserStorageUsage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetManagedUserStorageUsageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetManagedUserStorageUsage200Response**](GetManagedUserStorageUsage200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetManagedUserUsage

> ManagedUserUsageResponse GetManagedUserUsage(ctx, id).StartDate(startDate).EndDate(endDate).Execute()

What a managed user's editor sessions spent



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The managed user whose usage you want (Widgetic's id for the user)
	startDate := "startDate_example" // string | Start of the period, included: an ISO 8601 date (`2026-10-01`) or date-time with its offset (`2026-10-01T08:00:00Z`). Default: 30 days before `endDate`.  (optional)
	endDate := "endDate_example" // string | End of the period, not included, in the same forms. Default: now. It must be after `startDate`, by at most 366 days.  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.GetManagedUserUsage(context.Background(), id).StartDate(startDate).EndDate(endDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetManagedUserUsage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetManagedUserUsage`: ManagedUserUsageResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetManagedUserUsage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The managed user whose usage you want (Widgetic&#39;s id for the user) | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetManagedUserUsageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **startDate** | **string** | Start of the period, included: an ISO 8601 date (&#x60;2026-10-01&#x60;) or date-time with its offset (&#x60;2026-10-01T08:00:00Z&#x60;). Default: 30 days before &#x60;endDate&#x60;.  | 
 **endDate** | **string** | End of the period, not included, in the same forms. Default: now. It must be after &#x60;startDate&#x60;, by at most 366 days.  | 

### Return type

[**ManagedUserUsageResponse**](ManagedUserUsageResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetManagedUsersByManagerId

> GetManagedUsersByManagerIdResponse GetManagedUsersByManagerId(ctx, managerId).Page(page).Size(size).Sort(sort).Execute()

Get Managed Users By Manager



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
	managerId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the manager
	page := int32(56) // int32 | Page number for pagination (optional) (default to 1)
	size := int32(56) // int32 | Number of items per page (optional) (default to 10)
	sort := "sort_example" // string | Sort field and direction, `<field>:<asc|desc>`. The field is `createdAt`, `updatedAt` or `externalId` (the snake_case spellings `created_at`, `updated_at` and `external_id` work too); `asc` or `desc` alone sorts by `createdAt`. Any other field is a 400. (optional) (default to "createdAt:desc")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.GetManagedUsersByManagerId(context.Background(), managerId).Page(page).Size(size).Sort(sort).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetManagedUsersByManagerId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetManagedUsersByManagerId`: GetManagedUsersByManagerIdResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetManagedUsersByManagerId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**managerId** | **string** | ID of the manager | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetManagedUsersByManagerIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **page** | **int32** | Page number for pagination | [default to 1]
 **size** | **int32** | Number of items per page | [default to 10]
 **sort** | **string** | Sort field and direction, &#x60;&lt;field&gt;:&lt;asc|desc&gt;&#x60;. The field is &#x60;createdAt&#x60;, &#x60;updatedAt&#x60; or &#x60;externalId&#x60; (the snake_case spellings &#x60;created_at&#x60;, &#x60;updated_at&#x60; and &#x60;external_id&#x60; work too); &#x60;asc&#x60; or &#x60;desc&#x60; alone sorts by &#x60;createdAt&#x60;. Any other field is a 400. | [default to &quot;createdAt:desc&quot;]

### Return type

[**GetManagedUsersByManagerIdResponse**](GetManagedUsersByManagerIdResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetMyPartners

> MyPartnersResponse GetMyPartners(ctx).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetMyPartners(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetMyPartners``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMyPartners`: MyPartnersResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetMyPartners`: %v\n", resp)
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


## GetPartnerAdapterConnections

> GetUserAdapterConnections200Response GetPartnerAdapterConnections(ctx, partnerId).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetPartnerAdapterConnections(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetPartnerAdapterConnections``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerAdapterConnections`: GetUserAdapterConnections200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetPartnerAdapterConnections`: %v\n", resp)
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


## GetPartnerAnalyticsByManagedUser

> PartnerAnalyticsByManagedUserResponse GetPartnerAnalyticsByManagedUser(ctx, partnerId).StartDate(startDate).EndDate(endDate).Limit(limit).Offset(offset).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetPartnerAnalyticsByManagedUser(context.Background(), partnerId).StartDate(startDate).EndDate(endDate).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetPartnerAnalyticsByManagedUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerAnalyticsByManagedUser`: PartnerAnalyticsByManagedUserResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetPartnerAnalyticsByManagedUser`: %v\n", resp)
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


## GetPartnerAnalyticsSummary

> PartnerAnalyticsSummaryResponse GetPartnerAnalyticsSummary(ctx, partnerId).StartDate(startDate).EndDate(endDate).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetPartnerAnalyticsSummary(context.Background(), partnerId).StartDate(startDate).EndDate(endDate).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetPartnerAnalyticsSummary``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerAnalyticsSummary`: PartnerAnalyticsSummaryResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetPartnerAnalyticsSummary`: %v\n", resp)
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


## GetPartnerAnalyticsTimeline

> PartnerAnalyticsTimelineResponse GetPartnerAnalyticsTimeline(ctx, partnerId).StartDate(startDate).EndDate(endDate).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetPartnerAnalyticsTimeline(context.Background(), partnerId).StartDate(startDate).EndDate(endDate).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetPartnerAnalyticsTimeline``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerAnalyticsTimeline`: PartnerAnalyticsTimelineResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetPartnerAnalyticsTimeline`: %v\n", resp)
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


## GetPartnerAnalyticsTopWidgets

> PartnerAnalyticsTopWidgetsResponse GetPartnerAnalyticsTopWidgets(ctx, partnerId).StartDate(startDate).EndDate(endDate).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Limit(limit).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetPartnerAnalyticsTopWidgets(context.Background(), partnerId).StartDate(startDate).EndDate(endDate).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetPartnerAnalyticsTopWidgets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerAnalyticsTopWidgets`: PartnerAnalyticsTopWidgetsResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetPartnerAnalyticsTopWidgets`: %v\n", resp)
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


## GetPartnerBillingOverview

> GetPartnerBillingOverview200Response GetPartnerBillingOverview(ctx, partnerId).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetPartnerBillingOverview(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetPartnerBillingOverview``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerBillingOverview`: GetPartnerBillingOverview200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetPartnerBillingOverview`: %v\n", resp)
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


## GetPartnerContract

> PartnerContractResponse GetPartnerContract(ctx, partnerId).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetPartnerContract(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetPartnerContract``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerContract`: PartnerContractResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetPartnerContract`: %v\n", resp)
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


## GetPartnerCreditBalance

> AccountCreditBalanceResponse GetPartnerCreditBalance(ctx, partnerId).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetPartnerCreditBalance(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetPartnerCreditBalance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerCreditBalance`: AccountCreditBalanceResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetPartnerCreditBalance`: %v\n", resp)
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


## GetPartnerCreditTransactions

> GetPartnerCreditTransactions200Response GetPartnerCreditTransactions(ctx, partnerId).Limit(limit).Offset(offset).Type_(type_).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetPartnerCreditTransactions(context.Background(), partnerId).Limit(limit).Offset(offset).Type_(type_).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetPartnerCreditTransactions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerCreditTransactions`: GetPartnerCreditTransactions200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetPartnerCreditTransactions`: %v\n", resp)
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


## GetPartnerDataDatabase

> PartnerDataDatabaseResponse GetPartnerDataDatabase(ctx, partnerId).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetPartnerDataDatabase(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetPartnerDataDatabase``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerDataDatabase`: PartnerDataDatabaseResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetPartnerDataDatabase`: %v\n", resp)
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


## GetPartnerDesignDefaults

> GetPartnerDesignDefaults200Response GetPartnerDesignDefaults(ctx, partnerId).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetPartnerDesignDefaults(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetPartnerDesignDefaults``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerDesignDefaults`: GetPartnerDesignDefaults200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetPartnerDesignDefaults`: %v\n", resp)
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


## GetPartnerEntitlements

> GetPartnerEntitlementsResponse GetPartnerEntitlements(ctx, partnerId).IncludeExpired(includeExpired).Feature(feature).Source(source).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetPartnerEntitlements(context.Background(), partnerId).IncludeExpired(includeExpired).Feature(feature).Source(source).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetPartnerEntitlements``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerEntitlements`: GetPartnerEntitlementsResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetPartnerEntitlements`: %v\n", resp)
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


## GetPartnerEntryContextSigning

> PartnerEntryContextSigningResponse GetPartnerEntryContextSigning(ctx, partnerId).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetPartnerEntryContextSigning(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetPartnerEntryContextSigning``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerEntryContextSigning`: PartnerEntryContextSigningResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetPartnerEntryContextSigning`: %v\n", resp)
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


## GetPartnerNotificationSettings

> PartnerNotificationSettingsResponse GetPartnerNotificationSettings(ctx, partnerId).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetPartnerNotificationSettings(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetPartnerNotificationSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerNotificationSettings`: PartnerNotificationSettingsResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetPartnerNotificationSettings`: %v\n", resp)
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


## GetPartnerStorageDestination

> PartnerStorageDestinationResponse GetPartnerStorageDestination(ctx, partnerId).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetPartnerStorageDestination(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetPartnerStorageDestination``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerStorageDestination`: PartnerStorageDestinationResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetPartnerStorageDestination`: %v\n", resp)
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


## GetPartnerStorageUsage

> PartnerStorageUsageResponse GetPartnerStorageUsage(ctx, partnerId).Limit(limit).Offset(offset).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetPartnerStorageUsage(context.Background(), partnerId).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetPartnerStorageUsage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPartnerStorageUsage`: PartnerStorageUsageResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetPartnerStorageUsage`: %v\n", resp)
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


## GetPersonalWorkspaceDomains

> GetPersonalWorkspaceDomains200Response GetPersonalWorkspaceDomains(ctx, id).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetPersonalWorkspaceDomains(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetPersonalWorkspaceDomains``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPersonalWorkspaceDomains`: GetPersonalWorkspaceDomains200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetPersonalWorkspaceDomains`: %v\n", resp)
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


## GetPublicCompositionEmbed

> GetPublicCompositionEmbed200Response GetPublicCompositionEmbed(ctx, compositionId).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetPublicCompositionEmbed(context.Background(), compositionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetPublicCompositionEmbed``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPublicCompositionEmbed`: GetPublicCompositionEmbed200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetPublicCompositionEmbed`: %v\n", resp)
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


## GetPublicCompositionIframe

> string GetPublicCompositionIframe(ctx, compositionId).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetPublicCompositionIframe(context.Background(), compositionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetPublicCompositionIframe``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPublicCompositionIframe`: string
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetPublicCompositionIframe`: %v\n", resp)
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


## GetUserAdapterConnections

> GetUserAdapterConnections200Response GetUserAdapterConnections(ctx, userId).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetUserAdapterConnections(context.Background(), userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetUserAdapterConnections``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserAdapterConnections`: GetUserAdapterConnections200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetUserAdapterConnections`: %v\n", resp)
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


## GetUserApiKeyUsageLogs

> GetUserApiKeyUsageLogsResponse GetUserApiKeyUsageLogs(ctx, id, keyId).Limit(limit).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetUserApiKeyUsageLogs(context.Background(), id, keyId).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetUserApiKeyUsageLogs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserApiKeyUsageLogs`: GetUserApiKeyUsageLogsResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetUserApiKeyUsageLogs`: %v\n", resp)
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


## GetUserApiKeys

> GetUserApiKeys200Response GetUserApiKeys(ctx, id).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetUserApiKeys(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetUserApiKeys``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserApiKeys`: GetUserApiKeys200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetUserApiKeys`: %v\n", resp)
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


## GetUserCreditBalance

> AccountCreditBalanceResponse GetUserCreditBalance(ctx, userId).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetUserCreditBalance(context.Background(), userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetUserCreditBalance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserCreditBalance`: AccountCreditBalanceResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetUserCreditBalance`: %v\n", resp)
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


## GetUserCreditTransactions

> GetPartnerCreditTransactions200Response GetUserCreditTransactions(ctx, userId).TransactionType(transactionType).Limit(limit).Offset(offset).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetUserCreditTransactions(context.Background(), userId).TransactionType(transactionType).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetUserCreditTransactions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserCreditTransactions`: GetPartnerCreditTransactions200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetUserCreditTransactions`: %v\n", resp)
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


## GetWidgets

> GetWidgets200Response GetWidgets(ctx).Page(page).Size(size).CanvasId(canvasId).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetWidgets(context.Background()).Page(page).Size(size).CanvasId(canvasId).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetWidgets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetWidgets`: GetWidgets200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetWidgets`: %v\n", resp)
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


## GetWidgetsBatch

> GetWidgetsBatchResponse GetWidgetsBatch(ctx).GetWidgetsBatchRequest(getWidgetsBatchRequest).Execute()

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
	resp, r, err := apiClient.PartnerAPI.GetWidgetsBatch(context.Background()).GetWidgetsBatchRequest(getWidgetsBatchRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.GetWidgetsBatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetWidgetsBatch`: GetWidgetsBatchResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.GetWidgetsBatch`: %v\n", resp)
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


## ListCompositionEntryItems

> CompositionEntryItemsPageSuccess ListCompositionEntryItems(ctx, id, table).Limit(limit).Order(order).Since(since).Until(until).Cursor(cursor).Context(context).Filter(filter).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

List composition entry items with paging and filters



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	table := "table_example" // string | 
	limit := int32(56) // int32 |  (optional) (default to 25)
	order := "order_example" // string | `desc` (the default) lists the newest entry first, `asc` the oldest. Entries are sorted by their time, then by their id (compared as text, byte by byte) in the same direction, so the order of two entries made at the same instant is always the same; an entry with no time counts as the oldest. A table with no time column is sorted by its id. The managed-user feed sorts by time, then by composition id, table and id.  (optional) (default to "desc")
	since := time.Now() // time.Time | Only entries made at this time or later: `since` is INCLUSIVE (an entry made at exactly `since` is returned). A date and time with an offset, such as `2026-10-01T00:00:00Z`; anything else answers 400 `INVALID_SINCE`. An entry with no time never matches, and a table with no time column answers 400 `ENTRY_TABLE_HAS_NO_TIME`.  (optional)
	until := time.Now() // time.Time | Only entries made before this time: `until` is EXCLUSIVE (an entry made at exactly `until` is NOT returned), so `since=A&until=B` followed by `since=B&until=C` counts every entry once. Same form and same refusals as `since` (400 `INVALID_UNTIL`).  (optional)
	cursor := "cursor_example" // string |  (optional)
	context := map[string]string{"key": map[string]string{"key": "Inner_example"}} // map[string]string | Host context filters as `context[key]=value` (max 5 keys, counting dotted `context.key` too). Use `column.<name>=value` for columns whose names collide with reserved parameters. (optional)
	filter := map[string]string{"key": map[string]string{"key": "Inner_example"}} // map[string]string | Column filters as `filter[columnName]=value` (same meaning as bare `columnName=value` or `column.columnName=value`; max 10 column filters counting all spellings). A plain `filter=value` still filters a column named `filter`. (optional)
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.ListCompositionEntryItems(context.Background(), id, table).Limit(limit).Order(order).Since(since).Until(until).Cursor(cursor).Context(context).Filter(filter).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.ListCompositionEntryItems``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCompositionEntryItems`: CompositionEntryItemsPageSuccess
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.ListCompositionEntryItems`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**table** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListCompositionEntryItemsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **limit** | **int32** |  | [default to 25]
 **order** | **string** | &#x60;desc&#x60; (the default) lists the newest entry first, &#x60;asc&#x60; the oldest. Entries are sorted by their time, then by their id (compared as text, byte by byte) in the same direction, so the order of two entries made at the same instant is always the same; an entry with no time counts as the oldest. A table with no time column is sorted by its id. The managed-user feed sorts by time, then by composition id, table and id.  | [default to &quot;desc&quot;]
 **since** | **time.Time** | Only entries made at this time or later: &#x60;since&#x60; is INCLUSIVE (an entry made at exactly &#x60;since&#x60; is returned). A date and time with an offset, such as &#x60;2026-10-01T00:00:00Z&#x60;; anything else answers 400 &#x60;INVALID_SINCE&#x60;. An entry with no time never matches, and a table with no time column answers 400 &#x60;ENTRY_TABLE_HAS_NO_TIME&#x60;.  | 
 **until** | **time.Time** | Only entries made before this time: &#x60;until&#x60; is EXCLUSIVE (an entry made at exactly &#x60;until&#x60; is NOT returned), so &#x60;since&#x3D;A&amp;until&#x3D;B&#x60; followed by &#x60;since&#x3D;B&amp;until&#x3D;C&#x60; counts every entry once. Same form and same refusals as &#x60;since&#x60; (400 &#x60;INVALID_UNTIL&#x60;).  | 
 **cursor** | **string** |  | 
 **context** | **map[string]map[string]string** | Host context filters as &#x60;context[key]&#x3D;value&#x60; (max 5 keys, counting dotted &#x60;context.key&#x60; too). Use &#x60;column.&lt;name&gt;&#x3D;value&#x60; for columns whose names collide with reserved parameters. | 
 **filter** | **map[string]map[string]string** | Column filters as &#x60;filter[columnName]&#x3D;value&#x60; (same meaning as bare &#x60;columnName&#x3D;value&#x60; or &#x60;column.columnName&#x3D;value&#x60;; max 10 column filters counting all spellings). A plain &#x60;filter&#x3D;value&#x60; still filters a column named &#x60;filter&#x60;. | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**CompositionEntryItemsPageSuccess**](CompositionEntryItemsPageSuccess.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListManagedUserEntries

> ManagedUserEntriesPageSuccess ListManagedUserEntries(ctx, id).CompositionId(compositionId).Table(table).Limit(limit).Order(order).Since(since).Until(until).Cursor(cursor).Context(context).Filter(filter).Execute()

List entries across a managed user's compositions



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	compositionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	table := "table_example" // string |  (optional)
	limit := int32(56) // int32 |  (optional) (default to 25)
	order := "order_example" // string | `desc` (the default) lists the newest entry first, `asc` the oldest. Entries are sorted by their time, then by their id (compared as text, byte by byte) in the same direction, so the order of two entries made at the same instant is always the same; an entry with no time counts as the oldest. A table with no time column is sorted by its id. The managed-user feed sorts by time, then by composition id, table and id.  (optional) (default to "desc")
	since := time.Now() // time.Time | Only entries made at this time or later: `since` is INCLUSIVE (an entry made at exactly `since` is returned). A date and time with an offset, such as `2026-10-01T00:00:00Z`; anything else answers 400 `INVALID_SINCE`. An entry with no time never matches, and a table with no time column answers 400 `ENTRY_TABLE_HAS_NO_TIME`.  (optional)
	until := time.Now() // time.Time | Only entries made before this time: `until` is EXCLUSIVE (an entry made at exactly `until` is NOT returned), so `since=A&until=B` followed by `since=B&until=C` counts every entry once. Same form and same refusals as `since` (400 `INVALID_UNTIL`).  (optional)
	cursor := "cursor_example" // string |  (optional)
	context := map[string]string{"key": map[string]string{"key": "Inner_example"}} // map[string]string | Host context filters as `context[key]=value` (max 5 keys, counting dotted `context.key` too). Use `column.<name>=value` for columns whose names collide with reserved parameters. (optional)
	filter := map[string]string{"key": map[string]string{"key": "Inner_example"}} // map[string]string | Column filters as `filter[columnName]=value` (same meaning as bare `columnName=value` or `column.columnName=value`; max 10 column filters counting all spellings). A plain `filter=value` still filters a column named `filter`. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.ListManagedUserEntries(context.Background(), id).CompositionId(compositionId).Table(table).Limit(limit).Order(order).Since(since).Until(until).Cursor(cursor).Context(context).Filter(filter).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.ListManagedUserEntries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListManagedUserEntries`: ManagedUserEntriesPageSuccess
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.ListManagedUserEntries`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListManagedUserEntriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **compositionId** | **string** |  | 
 **table** | **string** |  | 
 **limit** | **int32** |  | [default to 25]
 **order** | **string** | &#x60;desc&#x60; (the default) lists the newest entry first, &#x60;asc&#x60; the oldest. Entries are sorted by their time, then by their id (compared as text, byte by byte) in the same direction, so the order of two entries made at the same instant is always the same; an entry with no time counts as the oldest. A table with no time column is sorted by its id. The managed-user feed sorts by time, then by composition id, table and id.  | [default to &quot;desc&quot;]
 **since** | **time.Time** | Only entries made at this time or later: &#x60;since&#x60; is INCLUSIVE (an entry made at exactly &#x60;since&#x60; is returned). A date and time with an offset, such as &#x60;2026-10-01T00:00:00Z&#x60;; anything else answers 400 &#x60;INVALID_SINCE&#x60;. An entry with no time never matches, and a table with no time column answers 400 &#x60;ENTRY_TABLE_HAS_NO_TIME&#x60;.  | 
 **until** | **time.Time** | Only entries made before this time: &#x60;until&#x60; is EXCLUSIVE (an entry made at exactly &#x60;until&#x60; is NOT returned), so &#x60;since&#x3D;A&amp;until&#x3D;B&#x60; followed by &#x60;since&#x3D;B&amp;until&#x3D;C&#x60; counts every entry once. Same form and same refusals as &#x60;since&#x60; (400 &#x60;INVALID_UNTIL&#x60;).  | 
 **cursor** | **string** |  | 
 **context** | **map[string]map[string]string** | Host context filters as &#x60;context[key]&#x3D;value&#x60; (max 5 keys, counting dotted &#x60;context.key&#x60; too). Use &#x60;column.&lt;name&gt;&#x3D;value&#x60; for columns whose names collide with reserved parameters. | 
 **filter** | **map[string]map[string]string** | Column filters as &#x60;filter[columnName]&#x3D;value&#x60; (same meaning as bare &#x60;columnName&#x3D;value&#x60; or &#x60;column.columnName&#x3D;value&#x60;; max 10 column filters counting all spellings). A plain &#x60;filter&#x3D;value&#x60; still filters a column named &#x60;filter&#x60;. | 

### Return type

[**ManagedUserEntriesPageSuccess**](ManagedUserEntriesPageSuccess.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPartnerNotificationDeliveries

> PartnerNotificationDeliveryLogResponse ListPartnerNotificationDeliveries(ctx, partnerId).Limit(limit).Execute()

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
	resp, r, err := apiClient.PartnerAPI.ListPartnerNotificationDeliveries(context.Background(), partnerId).Limit(limit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.ListPartnerNotificationDeliveries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPartnerNotificationDeliveries`: PartnerNotificationDeliveryLogResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.ListPartnerNotificationDeliveries`: %v\n", resp)
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


## ListPartnerNotifications

> PartnerNotificationPageResponse ListPartnerNotifications(ctx, partnerId).Limit(limit).Before(before).Execute()

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
	resp, r, err := apiClient.PartnerAPI.ListPartnerNotifications(context.Background(), partnerId).Limit(limit).Before(before).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.ListPartnerNotifications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPartnerNotifications`: PartnerNotificationPageResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.ListPartnerNotifications`: %v\n", resp)
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


## ListPartnerPresets

> ListPartnerPresets200Response ListPartnerPresets(ctx, partnerId).Execute()

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
	resp, r, err := apiClient.PartnerAPI.ListPartnerPresets(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.ListPartnerPresets``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPartnerPresets`: ListPartnerPresets200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.ListPartnerPresets`: %v\n", resp)
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


## OperationsIdGet

> OperationsIdGetResponse OperationsIdGet(ctx, id).Execute()

Get operation status



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Operation identifier returned when the job was created.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.OperationsIdGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.OperationsIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OperationsIdGet`: OperationsIdGetResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.OperationsIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Operation identifier returned when the job was created. | 

### Other Parameters

Other parameters are passed through a pointer to a apiOperationsIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**OperationsIdGetResponse**](OperationsIdGetResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PatchCompositionContentItem

> CreateCompositionContentItem201Response PatchCompositionContentItem(ctx, id, list, itemId).IdempotencyKey(idempotencyKey).RequestBody(requestBody).IfMatch(ifMatch).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Update a content list item

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
	list := "list_example" // string | 
	itemId := "itemId_example" // string | 
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	requestBody := map[string]interface{}{"key": interface{}(123)} // map[string]interface{} | 
	ifMatch := "ifMatch_example" // string |  (optional)
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.PatchCompositionContentItem(context.Background(), id, list, itemId).IdempotencyKey(idempotencyKey).RequestBody(requestBody).IfMatch(ifMatch).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.PatchCompositionContentItem``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PatchCompositionContentItem`: CreateCompositionContentItem201Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.PatchCompositionContentItem`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 
**list** | **string** |  | 
**itemId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPatchCompositionContentItemRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **requestBody** | **map[string]interface{}** |  | 
 **ifMatch** | **string** |  | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**CreateCompositionContentItem201Response**](CreateCompositionContentItem201Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostPublicCompositionEmbedStatus

> PostPublicCompositionEmbedStatus200Response PostPublicCompositionEmbedStatus(ctx).PostPublicCompositionEmbedStatusRequest(postPublicCompositionEmbedStatusRequest).Execute()

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
	resp, r, err := apiClient.PartnerAPI.PostPublicCompositionEmbedStatus(context.Background()).PostPublicCompositionEmbedStatusRequest(postPublicCompositionEmbedStatusRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.PostPublicCompositionEmbedStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostPublicCompositionEmbedStatus`: PostPublicCompositionEmbedStatus200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.PostPublicCompositionEmbedStatus`: %v\n", resp)
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


## ReadCompositionEntries

> CompositionEntriesReadingResponse ReadCompositionEntries(ctx, id, table).GroupBy(groupBy).Rows(rows).Aggregate(aggregate).Column(column).Since(since).Until(until).Context(context).Filter(filter).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Read the Entries of a Composition's Table



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the composition
	table := "table_example" // string | The table to read, exactly as `describeCompositionEntries` lists it
	groupBy := "groupBy_example" // string | A column of the table to count entries per value of (optional)
	rows := int32(56) // int32 | How many of the newest entries to return (0 returns counts and tallies only) (optional) (default to 0)
	aggregate := "count,avg" // string | The functions to compute, comma-separated, from `count`, `avg`, `min`, `max` and `sum` (for example `count,avg`). Adds `aggregates` to the answer. Any other name answers 400 `ENTRY_AGGREGATE_INVALID`.  (optional)
	column := "column_example" // string | The numeric column `avg`, `min`, `max` and `sum` are computed over. Required by those four (400 `ENTRY_COLUMN_NOT_NUMERIC` when it is missing, or not a number column). Only with `aggregate`.  (optional)
	since := time.Now() // time.Time | Only entries made at this time or later: `since` is INCLUSIVE (an entry made at exactly `since` is returned). A date and time with an offset, such as `2026-10-01T00:00:00Z`; anything else answers 400 `INVALID_SINCE`. An entry with no time never matches, and a table with no time column answers 400 `ENTRY_TABLE_HAS_NO_TIME`.  (optional)
	until := time.Now() // time.Time | Only entries made before this time: `until` is EXCLUSIVE (an entry made at exactly `until` is NOT returned), so `since=A&until=B` followed by `since=B&until=C` counts every entry once. Same form and same refusals as `since` (400 `INVALID_UNTIL`).  (optional)
	context := map[string]string{"key": map[string]string{"key": "Inner_example"}} // map[string]string | Host context filters as `context[key]=value` (max 5 keys, counting dotted `context.key` too). Use `column.<name>=value` for columns whose names collide with reserved parameters. (optional)
	filter := map[string]string{"key": map[string]string{"key": "Inner_example"}} // map[string]string | Column filters as `filter[columnName]=value` (same meaning as bare `columnName=value` or `column.columnName=value`; max 10 column filters counting all spellings). A plain `filter=value` still filters a column named `filter`. (optional)
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.ReadCompositionEntries(context.Background(), id, table).GroupBy(groupBy).Rows(rows).Aggregate(aggregate).Column(column).Since(since).Until(until).Context(context).Filter(filter).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.ReadCompositionEntries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReadCompositionEntries`: CompositionEntriesReadingResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.ReadCompositionEntries`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the composition | 
**table** | **string** | The table to read, exactly as &#x60;describeCompositionEntries&#x60; lists it | 

### Other Parameters

Other parameters are passed through a pointer to a apiReadCompositionEntriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **groupBy** | **string** | A column of the table to count entries per value of | 
 **rows** | **int32** | How many of the newest entries to return (0 returns counts and tallies only) | [default to 0]
 **aggregate** | **string** | The functions to compute, comma-separated, from &#x60;count&#x60;, &#x60;avg&#x60;, &#x60;min&#x60;, &#x60;max&#x60; and &#x60;sum&#x60; (for example &#x60;count,avg&#x60;). Adds &#x60;aggregates&#x60; to the answer. Any other name answers 400 &#x60;ENTRY_AGGREGATE_INVALID&#x60;.  | 
 **column** | **string** | The numeric column &#x60;avg&#x60;, &#x60;min&#x60;, &#x60;max&#x60; and &#x60;sum&#x60; are computed over. Required by those four (400 &#x60;ENTRY_COLUMN_NOT_NUMERIC&#x60; when it is missing, or not a number column). Only with &#x60;aggregate&#x60;.  | 
 **since** | **time.Time** | Only entries made at this time or later: &#x60;since&#x60; is INCLUSIVE (an entry made at exactly &#x60;since&#x60; is returned). A date and time with an offset, such as &#x60;2026-10-01T00:00:00Z&#x60;; anything else answers 400 &#x60;INVALID_SINCE&#x60;. An entry with no time never matches, and a table with no time column answers 400 &#x60;ENTRY_TABLE_HAS_NO_TIME&#x60;.  | 
 **until** | **time.Time** | Only entries made before this time: &#x60;until&#x60; is EXCLUSIVE (an entry made at exactly &#x60;until&#x60; is NOT returned), so &#x60;since&#x3D;A&amp;until&#x3D;B&#x60; followed by &#x60;since&#x3D;B&amp;until&#x3D;C&#x60; counts every entry once. Same form and same refusals as &#x60;since&#x60; (400 &#x60;INVALID_UNTIL&#x60;).  | 
 **context** | **map[string]map[string]string** | Host context filters as &#x60;context[key]&#x3D;value&#x60; (max 5 keys, counting dotted &#x60;context.key&#x60; too). Use &#x60;column.&lt;name&gt;&#x3D;value&#x60; for columns whose names collide with reserved parameters. | 
 **filter** | **map[string]map[string]string** | Column filters as &#x60;filter[columnName]&#x3D;value&#x60; (same meaning as bare &#x60;columnName&#x3D;value&#x60; or &#x60;column.columnName&#x3D;value&#x60;; max 10 column filters counting all spellings). A plain &#x60;filter&#x3D;value&#x60; still filters a column named &#x60;filter&#x60;. | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**CompositionEntriesReadingResponse**](CompositionEntriesReadingResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemoveAiAnswersKnowledgeDocument

> RemoveAiAnswersKnowledgeDocument200Response RemoveAiAnswersKnowledgeDocument(ctx, id, documentId).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Remove a document from a widget's knowledge base



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The widget (composition) the document is in
	documentId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The document to remove
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.RemoveAiAnswersKnowledgeDocument(context.Background(), id, documentId).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.RemoveAiAnswersKnowledgeDocument``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemoveAiAnswersKnowledgeDocument`: RemoveAiAnswersKnowledgeDocument200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.RemoveAiAnswersKnowledgeDocument`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The widget (composition) the document is in | 
**documentId** | **string** | The document to remove | 

### Other Parameters

Other parameters are passed through a pointer to a apiRemoveAiAnswersKnowledgeDocumentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**RemoveAiAnswersKnowledgeDocument200Response**](RemoveAiAnswersKnowledgeDocument200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemovePartnerAdapterConnection

> RemoveUserAdapterConnection200Response RemovePartnerAdapterConnection(ctx, partnerId, adapterId, credentialKey).Execute()

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
	resp, r, err := apiClient.PartnerAPI.RemovePartnerAdapterConnection(context.Background(), partnerId, adapterId, credentialKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.RemovePartnerAdapterConnection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemovePartnerAdapterConnection`: RemoveUserAdapterConnection200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.RemovePartnerAdapterConnection`: %v\n", resp)
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


## RemovePartnerDataDatabase

> PartnerDataDatabaseRemovalResponse RemovePartnerDataDatabase(ctx, partnerId).Execute()

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
	resp, r, err := apiClient.PartnerAPI.RemovePartnerDataDatabase(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.RemovePartnerDataDatabase``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemovePartnerDataDatabase`: PartnerDataDatabaseRemovalResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.RemovePartnerDataDatabase`: %v\n", resp)
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


## RemovePartnerPreset

> PartnerPresetRemovalResponse RemovePartnerPreset(ctx, partnerId, key).Execute()

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
	resp, r, err := apiClient.PartnerAPI.RemovePartnerPreset(context.Background(), partnerId, key).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.RemovePartnerPreset``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemovePartnerPreset`: PartnerPresetRemovalResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.RemovePartnerPreset`: %v\n", resp)
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


## RemovePartnerStorageDestination

> PartnerStorageRemovalResponse RemovePartnerStorageDestination(ctx, partnerId).Execute()

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
	resp, r, err := apiClient.PartnerAPI.RemovePartnerStorageDestination(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.RemovePartnerStorageDestination``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemovePartnerStorageDestination`: PartnerStorageRemovalResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.RemovePartnerStorageDestination`: %v\n", resp)
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


## RemoveUserAdapterConnection

> RemoveUserAdapterConnection200Response RemoveUserAdapterConnection(ctx, userId, adapterId, credentialKey).Execute()

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
	resp, r, err := apiClient.PartnerAPI.RemoveUserAdapterConnection(context.Background(), userId, adapterId, credentialKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.RemoveUserAdapterConnection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemoveUserAdapterConnection`: RemoveUserAdapterConnection200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.RemoveUserAdapterConnection`: %v\n", resp)
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


## ReplayPartnerNotificationDelivery

> PartnerNotificationDeliveryResponse ReplayPartnerNotificationDelivery(ctx, partnerId, deliveryId).IdempotencyKey(idempotencyKey).Execute()

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
	resp, r, err := apiClient.PartnerAPI.ReplayPartnerNotificationDelivery(context.Background(), partnerId, deliveryId).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.ReplayPartnerNotificationDelivery``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReplayPartnerNotificationDelivery`: PartnerNotificationDeliveryResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.ReplayPartnerNotificationDelivery`: %v\n", resp)
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


## RevokeManagedUserEditorSession

> DeleteManagedUser200Response RevokeManagedUserEditorSession(ctx, id, sessionId).Execute()

End one editor session of a managed user



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The managed user the session is for
	sessionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The `sessionId` of the session, from `createManagedUserEditorSession`

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.RevokeManagedUserEditorSession(context.Background(), id, sessionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.RevokeManagedUserEditorSession``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RevokeManagedUserEditorSession`: DeleteManagedUser200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.RevokeManagedUserEditorSession`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The managed user the session is for | 
**sessionId** | **string** | The &#x60;sessionId&#x60; of the session, from &#x60;createManagedUserEditorSession&#x60; | 

### Other Parameters

Other parameters are passed through a pointer to a apiRevokeManagedUserEditorSessionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**DeleteManagedUser200Response**](DeleteManagedUser200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RevokeManagedUserEditorSessions

> RevokeManagedUserEditorSessionsResponse RevokeManagedUserEditorSessions(ctx, id).Execute()

End every editor session of a managed user



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The managed user whose sessions end

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.RevokeManagedUserEditorSessions(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.RevokeManagedUserEditorSessions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RevokeManagedUserEditorSessions`: RevokeManagedUserEditorSessionsResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.RevokeManagedUserEditorSessions`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | The managed user whose sessions end | 

### Other Parameters

Other parameters are passed through a pointer to a apiRevokeManagedUserEditorSessionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RevokeManagedUserEditorSessionsResponse**](RevokeManagedUserEditorSessionsResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RotatePartnerEntryContextSecret

> PartnerEntryContextSecretResponse RotatePartnerEntryContextSecret(ctx, partnerId).IdempotencyKey(idempotencyKey).Execute()

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
	resp, r, err := apiClient.PartnerAPI.RotatePartnerEntryContextSecret(context.Background(), partnerId).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.RotatePartnerEntryContextSecret``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RotatePartnerEntryContextSecret`: PartnerEntryContextSecretResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.RotatePartnerEntryContextSecret`: %v\n", resp)
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


## RotatePartnerWebhookSecret

> PartnerNotificationSettingsChangeResponse RotatePartnerWebhookSecret(ctx, partnerId).IdempotencyKey(idempotencyKey).Execute()

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
	resp, r, err := apiClient.PartnerAPI.RotatePartnerWebhookSecret(context.Background(), partnerId).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.RotatePartnerWebhookSecret``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RotatePartnerWebhookSecret`: PartnerNotificationSettingsChangeResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.RotatePartnerWebhookSecret`: %v\n", resp)
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


## SendPartnerNotificationTestEvent

> PartnerNotificationTestEventResultResponse SendPartnerNotificationTestEvent(ctx, partnerId).IdempotencyKey(idempotencyKey).PartnerNotificationTestEventRequest(partnerNotificationTestEventRequest).Execute()

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
	resp, r, err := apiClient.PartnerAPI.SendPartnerNotificationTestEvent(context.Background(), partnerId).IdempotencyKey(idempotencyKey).PartnerNotificationTestEventRequest(partnerNotificationTestEventRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.SendPartnerNotificationTestEvent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SendPartnerNotificationTestEvent`: PartnerNotificationTestEventResultResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.SendPartnerNotificationTestEvent`: %v\n", resp)
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


## SetCompositionDataSource

> CompositionDataSourceResponse SetCompositionDataSource(ctx, id).IdempotencyKey(idempotencyKey).SetCompositionDataSourceRequest(setCompositionDataSourceRequest).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Bind a public JSON data source for embed refresh



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
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	setCompositionDataSourceRequest := *openapiclient.NewSetCompositionDataSourceRequest("Url_example", int32(123)) // SetCompositionDataSourceRequest | 
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.SetCompositionDataSource(context.Background(), id).IdempotencyKey(idempotencyKey).SetCompositionDataSourceRequest(setCompositionDataSourceRequest).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.SetCompositionDataSource``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetCompositionDataSource`: CompositionDataSourceResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.SetCompositionDataSource`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSetCompositionDataSourceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **setCompositionDataSourceRequest** | [**SetCompositionDataSourceRequest**](SetCompositionDataSourceRequest.md) |  | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**CompositionDataSourceResponse**](CompositionDataSourceResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetDynamicContent

> SetDynamicContentResponse SetDynamicContent(ctx, id).IdempotencyKey(idempotencyKey).SetDynamicContentRequest(setDynamicContentRequest).IfMatch(ifMatch).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Set Dynamic Content



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the composition
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	setDynamicContentRequest := *openapiclient.NewSetDynamicContentRequest(map[string]interface{}(123)) // SetDynamicContentRequest | 
	ifMatch := "ifMatch_example" // string | Optional content version from ETag (`\"3\"`, `3`, or `*`) (optional)
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.SetDynamicContent(context.Background(), id).IdempotencyKey(idempotencyKey).SetDynamicContentRequest(setDynamicContentRequest).IfMatch(ifMatch).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.SetDynamicContent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetDynamicContent`: SetDynamicContentResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.SetDynamicContent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the composition | 

### Other Parameters

Other parameters are passed through a pointer to a apiSetDynamicContentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **setDynamicContentRequest** | [**SetDynamicContentRequest**](SetDynamicContentRequest.md) |  | 
 **ifMatch** | **string** | Optional content version from ETag (&#x60;\&quot;3\&quot;&#x60;, &#x60;3&#x60;, or &#x60;*&#x60;) | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**SetDynamicContentResponse**](SetDynamicContentResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetManagedUserDesignDefaults

> GetPartnerDesignDefaults200Response SetManagedUserDesignDefaults(ctx, id).SetPartnerDesignDefaultsRequest(setPartnerDesignDefaultsRequest).Execute()

Set or clear design defaults for one managed user



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
	setPartnerDesignDefaultsRequest := *openapiclient.NewSetPartnerDesignDefaultsRequest(map[string]interface{}(123)) // SetPartnerDesignDefaultsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.SetManagedUserDesignDefaults(context.Background(), id).SetPartnerDesignDefaultsRequest(setPartnerDesignDefaultsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.SetManagedUserDesignDefaults``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetManagedUserDesignDefaults`: GetPartnerDesignDefaults200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.SetManagedUserDesignDefaults`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSetManagedUserDesignDefaultsRequest struct via the builder pattern


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


## SetManagedUserLimits

> GetManagedUserLimits200Response SetManagedUserLimits(ctx, id).SetManagedUserLimitsRequest(setManagedUserLimitsRequest).Execute()

Set or clear the monthly credit cap for one managed user



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
	setManagedUserLimitsRequest := *openapiclient.NewSetManagedUserLimitsRequest(NullableInt32(123)) // SetManagedUserLimitsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.SetManagedUserLimits(context.Background(), id).SetManagedUserLimitsRequest(setManagedUserLimitsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.SetManagedUserLimits``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetManagedUserLimits`: GetManagedUserLimits200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.SetManagedUserLimits`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSetManagedUserLimitsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **setManagedUserLimitsRequest** | [**SetManagedUserLimitsRequest**](SetManagedUserLimitsRequest.md) |  | 

### Return type

[**GetManagedUserLimits200Response**](GetManagedUserLimits200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetPartnerAdapterConnection

> SetUserAdapterConnection200Response SetPartnerAdapterConnection(ctx, partnerId, adapterId, credentialKey).SetAdapterConnectionRequest(setAdapterConnectionRequest).Execute()

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
	resp, r, err := apiClient.PartnerAPI.SetPartnerAdapterConnection(context.Background(), partnerId, adapterId, credentialKey).SetAdapterConnectionRequest(setAdapterConnectionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.SetPartnerAdapterConnection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetPartnerAdapterConnection`: SetUserAdapterConnection200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.SetPartnerAdapterConnection`: %v\n", resp)
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


## SetPartnerDataDatabase

> PartnerDataDatabaseResponse SetPartnerDataDatabase(ctx, partnerId).SetPartnerDataDatabaseRequest(setPartnerDataDatabaseRequest).Execute()

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
	resp, r, err := apiClient.PartnerAPI.SetPartnerDataDatabase(context.Background(), partnerId).SetPartnerDataDatabaseRequest(setPartnerDataDatabaseRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.SetPartnerDataDatabase``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetPartnerDataDatabase`: PartnerDataDatabaseResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.SetPartnerDataDatabase`: %v\n", resp)
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


## SetPartnerDesignDefaults

> GetPartnerDesignDefaults200Response SetPartnerDesignDefaults(ctx, partnerId).SetPartnerDesignDefaultsRequest(setPartnerDesignDefaultsRequest).Execute()

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
	resp, r, err := apiClient.PartnerAPI.SetPartnerDesignDefaults(context.Background(), partnerId).SetPartnerDesignDefaultsRequest(setPartnerDesignDefaultsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.SetPartnerDesignDefaults``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetPartnerDesignDefaults`: GetPartnerDesignDefaults200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.SetPartnerDesignDefaults`: %v\n", resp)
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


## SetPartnerPreset

> PartnerPresetResponse SetPartnerPreset(ctx, partnerId, key).SetPartnerPresetRequest(setPartnerPresetRequest).Execute()

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
	resp, r, err := apiClient.PartnerAPI.SetPartnerPreset(context.Background(), partnerId, key).SetPartnerPresetRequest(setPartnerPresetRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.SetPartnerPreset``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetPartnerPreset`: PartnerPresetResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.SetPartnerPreset`: %v\n", resp)
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


## SetPartnerStorageDestination

> PartnerStorageDestinationResponse SetPartnerStorageDestination(ctx, partnerId).SetPartnerStorageDestinationRequest(setPartnerStorageDestinationRequest).Execute()

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
	resp, r, err := apiClient.PartnerAPI.SetPartnerStorageDestination(context.Background(), partnerId).SetPartnerStorageDestinationRequest(setPartnerStorageDestinationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.SetPartnerStorageDestination``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetPartnerStorageDestination`: PartnerStorageDestinationResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.SetPartnerStorageDestination`: %v\n", resp)
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


## SetUserAdapterConnection

> SetUserAdapterConnection200Response SetUserAdapterConnection(ctx, userId, adapterId, credentialKey).SetAdapterConnectionRequest(setAdapterConnectionRequest).Execute()

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
	resp, r, err := apiClient.PartnerAPI.SetUserAdapterConnection(context.Background(), userId, adapterId, credentialKey).SetAdapterConnectionRequest(setAdapterConnectionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.SetUserAdapterConnection``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetUserAdapterConnection`: SetUserAdapterConnection200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.SetUserAdapterConnection`: %v\n", resp)
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


## UpdateCanvas

> CanvasResponse UpdateCanvas(ctx, id).UpdateCanvasRequest(updateCanvasRequest).Execute()

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
	resp, r, err := apiClient.PartnerAPI.UpdateCanvas(context.Background(), id).UpdateCanvasRequest(updateCanvasRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.UpdateCanvas``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateCanvas`: CanvasResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.UpdateCanvas`: %v\n", resp)
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


## UpdateComposition

> CreateCompositionFromWidget201Response UpdateComposition(ctx, id).IdempotencyKey(idempotencyKey).UpdateComposition(updateComposition).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Update Composition



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Composition ID
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	updateComposition := *openapiclient.NewUpdateComposition() // UpdateComposition | 
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.UpdateComposition(context.Background(), id).IdempotencyKey(idempotencyKey).UpdateComposition(updateComposition).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.UpdateComposition``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateComposition`: CreateCompositionFromWidget201Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.UpdateComposition`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Composition ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateCompositionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **updateComposition** | [**UpdateComposition**](UpdateComposition.md) |  | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

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


## UpdateCompositionDatabaseRecord

> CreateCompositionDatabaseRecord201Response UpdateCompositionDatabaseRecord(ctx, id, table, recordId).IdempotencyKey(idempotencyKey).Body(body).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Update Record In Composition Database



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the composition
	table := "table_example" // string | Name of the database table
	recordId := "recordId_example" // string | ID of the record to update
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	body := map[string]interface{}{ ... } // map[string]interface{} | 
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.UpdateCompositionDatabaseRecord(context.Background(), id, table, recordId).IdempotencyKey(idempotencyKey).Body(body).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.UpdateCompositionDatabaseRecord``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateCompositionDatabaseRecord`: CreateCompositionDatabaseRecord201Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.UpdateCompositionDatabaseRecord`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the composition | 
**table** | **string** | Name of the database table | 
**recordId** | **string** | ID of the record to update | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateCompositionDatabaseRecordRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **body** | **map[string]interface{}** |  | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**CreateCompositionDatabaseRecord201Response**](CreateCompositionDatabaseRecord201Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateCompositionStatus

> CompositionResponse UpdateCompositionStatus(ctx, id).IdempotencyKey(idempotencyKey).UpdateCompositionStatusRequest(updateCompositionStatusRequest).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Update Composition Status



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Composition ID
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	updateCompositionStatusRequest := *openapiclient.NewUpdateCompositionStatusRequest("Status_example") // UpdateCompositionStatusRequest | 
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.UpdateCompositionStatus(context.Background(), id).IdempotencyKey(idempotencyKey).UpdateCompositionStatusRequest(updateCompositionStatusRequest).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.UpdateCompositionStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateCompositionStatus`: CompositionResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.UpdateCompositionStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Composition ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateCompositionStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **updateCompositionStatusRequest** | [**UpdateCompositionStatusRequest**](UpdateCompositionStatusRequest.md) |  | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**CompositionResponse**](CompositionResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateManagedUser

> ManagedUserResponse UpdateManagedUser(ctx, id).IdempotencyKey(idempotencyKey).UpdateManagedUser(updateManagedUser).Execute()

Update Managed User



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the managed user to update
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	updateManagedUser := *openapiclient.NewUpdateManagedUser() // UpdateManagedUser | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.UpdateManagedUser(context.Background(), id).IdempotencyKey(idempotencyKey).UpdateManagedUser(updateManagedUser).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.UpdateManagedUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateManagedUser`: ManagedUserResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.UpdateManagedUser`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the managed user to update | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateManagedUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **updateManagedUser** | [**UpdateManagedUser**](UpdateManagedUser.md) |  | 

### Return type

[**ManagedUserResponse**](ManagedUserResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdatePartnerEntryContextSigning

> PartnerEntryContextSigningResponse UpdatePartnerEntryContextSigning(ctx, partnerId).UpdatePartnerEntryContextSigningRequest(updatePartnerEntryContextSigningRequest).IdempotencyKey(idempotencyKey).Execute()

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
	resp, r, err := apiClient.PartnerAPI.UpdatePartnerEntryContextSigning(context.Background(), partnerId).UpdatePartnerEntryContextSigningRequest(updatePartnerEntryContextSigningRequest).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.UpdatePartnerEntryContextSigning``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdatePartnerEntryContextSigning`: PartnerEntryContextSigningResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.UpdatePartnerEntryContextSigning`: %v\n", resp)
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


## UpdatePartnerNotificationSettings

> PartnerNotificationSettingsChangeResponse UpdatePartnerNotificationSettings(ctx, partnerId).UpdatePartnerNotificationSettingsRequest(updatePartnerNotificationSettingsRequest).IdempotencyKey(idempotencyKey).Execute()

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
	resp, r, err := apiClient.PartnerAPI.UpdatePartnerNotificationSettings(context.Background(), partnerId).UpdatePartnerNotificationSettingsRequest(updatePartnerNotificationSettingsRequest).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.UpdatePartnerNotificationSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdatePartnerNotificationSettings`: PartnerNotificationSettingsChangeResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.UpdatePartnerNotificationSettings`: %v\n", resp)
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


## UpdatePersonalWorkspaceDomain

> PersonalWorkspaceDomainResultResponse UpdatePersonalWorkspaceDomain(ctx, id, domainId).UpdateDomainRequest(updateDomainRequest).Execute()

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
	resp, r, err := apiClient.PartnerAPI.UpdatePersonalWorkspaceDomain(context.Background(), id, domainId).UpdateDomainRequest(updateDomainRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.UpdatePersonalWorkspaceDomain``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdatePersonalWorkspaceDomain`: PersonalWorkspaceDomainResultResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.UpdatePersonalWorkspaceDomain`: %v\n", resp)
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


## UpdateUserApiKey

> UserApiKeyResponse UpdateUserApiKey(ctx, id, keyId).UpdateUserApiKeyRequest(updateUserApiKeyRequest).Execute()

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
	resp, r, err := apiClient.PartnerAPI.UpdateUserApiKey(context.Background(), id, keyId).UpdateUserApiKeyRequest(updateUserApiKeyRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.UpdateUserApiKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateUserApiKey`: UserApiKeyResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.UpdateUserApiKey`: %v\n", resp)
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


## UploadPublicCompositionAdapterFile

> PublicAdapterFileResult UploadPublicCompositionAdapterFile(ctx, compositionId, ticket).Body(body).Execute()

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
	resp, r, err := apiClient.PartnerAPI.UploadPublicCompositionAdapterFile(context.Background(), compositionId, ticket).Body(body).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.UploadPublicCompositionAdapterFile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadPublicCompositionAdapterFile`: PublicAdapterFileResult
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.UploadPublicCompositionAdapterFile`: %v\n", resp)
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


## UploadsGet

> UploadsGet200Response UploadsGet(ctx).Limit(limit).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Execute()

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
	resp, r, err := apiClient.PartnerAPI.UploadsGet(context.Background()).Limit(limit).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.UploadsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadsGet`: UploadsGet200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.UploadsGet`: %v\n", resp)
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


## UploadsIdDelete

> UploadsIdDelete200Response UploadsIdDelete(ctx, id).Execute()

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
	resp, r, err := apiClient.PartnerAPI.UploadsIdDelete(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.UploadsIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadsIdDelete`: UploadsIdDelete200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.UploadsIdDelete`: %v\n", resp)
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


## UploadsIdGet

> UploadResponse UploadsIdGet(ctx, id).Execute()

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
	resp, r, err := apiClient.PartnerAPI.UploadsIdGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.UploadsIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadsIdGet`: UploadResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.UploadsIdGet`: %v\n", resp)
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


## UploadsLimitsGet

> UploadLimitsResponse UploadsLimitsGet(ctx).Execute()

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
	resp, r, err := apiClient.PartnerAPI.UploadsLimitsGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.UploadsLimitsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadsLimitsGet`: UploadLimitsResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.UploadsLimitsGet`: %v\n", resp)
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


## UploadsPost

> UploadResponse UploadsPost(ctx).File(file).ContextType(contextType).Source(source).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Purpose(purpose).Execute()

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
	resp, r, err := apiClient.PartnerAPI.UploadsPost(context.Background()).File(file).ContextType(contextType).Source(source).ManagedUserId(managedUserId).ManagedUserExternalId(managedUserExternalId).Purpose(purpose).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.UploadsPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadsPost`: UploadResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.UploadsPost`: %v\n", resp)
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


## ValidateCompositionContent

> ValidateCompositionContentResponse ValidateCompositionContent(ctx, id).IdempotencyKey(idempotencyKey).RequestBody(requestBody).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()

Validate Content



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | ID of the composition
	idempotencyKey := "9b2d6f0a-3c41-4e5a-8d77-1f2e3a4b5c6d" // string | Required: a call without it is refused with `400`. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, `-` and `_`. Send the same key again when you retry (after a timeout, a dropped connection or a `5xx`) and the call is carried out once: the retry gets the first answer back, marked `X-Idempotency-Cached: true`. The same key with a different body is refused with `422`, and a retry that arrives while the first call is still running with `409` (see `Retry-After`).
	requestBody := map[string]interface{}{"key": interface{}(123)} // map[string]interface{} | 
	xManagedUserId := "3f2b8c1e-7a4d-4e0b-9c55-2d1a6b7e8f90" // string | The id Widgetic gave the managed user (`POST /managed-users`). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)
	xManagedUserExternalId := "customer-1042" // string | Your own id for the managed user (its `externalId`), when you do not keep Widgetic's. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer's work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user's compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers `404` (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers `404` with `MANAGED_USER_NOT_FOUND`. An empty, repeated or malformed header is `400` with `MANAGED_USER_SCOPE_INVALID`; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with `403` and `MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE`: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer's browser holds, use an editor session. An `Idempotency-Key` is kept apart for each managed user. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PartnerAPI.ValidateCompositionContent(context.Background(), id).IdempotencyKey(idempotencyKey).RequestBody(requestBody).XManagedUserId(xManagedUserId).XManagedUserExternalId(xManagedUserExternalId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.ValidateCompositionContent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ValidateCompositionContent`: ValidateCompositionContentResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.ValidateCompositionContent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | ID of the composition | 

### Other Parameters

Other parameters are passed through a pointer to a apiValidateCompositionContentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **idempotencyKey** | **string** | Required: a call without it is refused with &#x60;400&#x60;. A key of your own that names this one request; a UUID is ideal. It is 8 to 50 characters of letters, digits, &#x60;-&#x60; and &#x60;_&#x60;. Send the same key again when you retry (after a timeout, a dropped connection or a &#x60;5xx&#x60;) and the call is carried out once: the retry gets the first answer back, marked &#x60;X-Idempotency-Cached: true&#x60;. The same key with a different body is refused with &#x60;422&#x60;, and a retry that arrives while the first call is still running with &#x60;409&#x60; (see &#x60;Retry-After&#x60;). | 
 **requestBody** | **map[string]interface{}** |  | 
 **xManagedUserId** | **string** | The id Widgetic gave the managed user (&#x60;POST /managed-users&#x60;). Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 
 **xManagedUserExternalId** | **string** | Your own id for the managed user (its &#x60;externalId&#x60;), when you do not keep Widgetic&#39;s. Makes this call for one of your managed users, so that a mistake in your own code cannot reach another customer&#39;s work. Send this header, or the other one, never both. Left out, the call works on your whole account, as it always has. With it, the call reaches only that user&#39;s compositions: a list shows only theirs, a composition the call makes is filed under them, and a composition of another user, or one that does not exist, answers &#x60;404&#x60; (the same answer, so the call cannot be used to find out what another customer has). A managed user that is not yours answers &#x60;404&#x60; with &#x60;MANAGED_USER_NOT_FOUND&#x60;. An empty, repeated or malformed header is &#x60;400&#x60; with &#x60;MANAGED_USER_SCOPE_INVALID&#x60;; an empty header is never read as no header. A call that is about the whole account, such as the list of your managed users, is refused with &#x60;403&#x60; and &#x60;MANAGED_USER_SCOPE_ROUTE_NOT_AVAILABLE&#x60;: send it without the header. Only your API key can send it. The header is a limit the call asks for: whoever holds the key can leave it out, so for a credential that a customer&#39;s browser holds, use an editor session. An &#x60;Idempotency-Key&#x60; is kept apart for each managed user. | 

### Return type

[**ValidateCompositionContentResponse**](ValidateCompositionContentResponse.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ValidateToken

> ValidateToken200Response ValidateToken(ctx).Execute()

Validate current authentication token

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
	resp, r, err := apiClient.PartnerAPI.ValidateToken(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.ValidateToken``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ValidateToken`: ValidateToken200Response
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.ValidateToken`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiValidateTokenRequest struct via the builder pattern


### Return type

[**ValidateToken200Response**](ValidateToken200Response.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth), [BearerAuth](../README.md#BearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## VerifyPartnerDataDatabase

> PartnerDataDatabaseResponse VerifyPartnerDataDatabase(ctx, partnerId).Execute()

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
	resp, r, err := apiClient.PartnerAPI.VerifyPartnerDataDatabase(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.VerifyPartnerDataDatabase``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `VerifyPartnerDataDatabase`: PartnerDataDatabaseResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.VerifyPartnerDataDatabase`: %v\n", resp)
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


## VerifyPartnerStorageDestination

> PartnerStorageDestinationResponse VerifyPartnerStorageDestination(ctx, partnerId).Execute()

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
	resp, r, err := apiClient.PartnerAPI.VerifyPartnerStorageDestination(context.Background(), partnerId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PartnerAPI.VerifyPartnerStorageDestination``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `VerifyPartnerStorageDestination`: PartnerStorageDestinationResponse
	fmt.Fprintf(os.Stdout, "Response from `PartnerAPI.VerifyPartnerStorageDestination`: %v\n", resp)
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

