# PartnerNotification

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Type** | [**PartnerNotificationEventType**](PartnerNotificationEventType.md) |  | 
**Title** | **string** | One line that says what happened | 
**Body** | **string** | A few sentences that say what happened and what to do about it | 
**Tone** | **string** | How serious it is | 
**Data** | **map[string]interface{}** | The facts of the event, named in camelCase. An invoice event carries &#x60;invoiceNumber&#x60;, &#x60;subtotal&#x60;, &#x60;taxAmount&#x60;, &#x60;total&#x60;, &#x60;currency&#x60;, &#x60;dueDate&#x60;, &#x60;hostedInvoiceUrl&#x60; (the page where it is paid) and &#x60;purpose&#x60; (&#x60;contract&#x60;, or &#x60;extra_credits&#x60; for credits you bought on top of the contract: an unpaid invoice for extra credits never stops the account, the credits are just not added until it is paid); a payment adds &#x60;paidAt&#x60;, a failed payment &#x60;reason&#x60;, a reminder &#x60;daysUntilDue&#x60; or &#x60;daysOverdue&#x60;. A credits event carries &#x60;band&#x60; (&#x60;low&#x60; or &#x60;empty&#x60;), &#x60;balance&#x60; and &#x60;threshold&#x60;. &#x60;credits.managed_user_cap_reached&#x60; (one of your managed users used its monthly credits and a request was refused) goes to your webhook only when subscribed, once per managed user each month, and carries &#x60;managedUserId&#x60;, &#x60;externalId&#x60;, &#x60;monthlyCredits&#x60;, &#x60;creditsUsed&#x60;, &#x60;resetsAt&#x60; and &#x60;reachedAt&#x60;. A standing event carries &#x60;status&#x60;, &#x60;previousStatus&#x60; and &#x60;reason&#x60;; &#x60;partner.paused&#x60; with &#x60;status: payment_arrears&#x60; means that an overdue invoice stopped the account (nobody paused it, and &#x60;reason&#x60; names the invoice), and &#x60;partner.resumed&#x60; with &#x60;previousStatus: payment_arrears&#x60; means that its payment ended that. A storage event carries &#x60;reason&#x60; and &#x60;checkedAt&#x60;. Content events (&#x60;composition.created&#x60;, &#x60;composition.updated&#x60;, &#x60;widget.published&#x60;, &#x60;upload.created&#x60;, &#x60;entry.created&#x60;, &#x60;workflow.created&#x60;, &#x60;workflow.published&#x60;, &#x60;workflow.state_changed&#x60;, &#x60;workflow.deleted&#x60;) go to your webhook only when subscribed; they do not appear in the dashboard list. &#x60;composition.created&#x60; carries &#x60;compositionId&#x60;, &#x60;widgetId&#x60;, &#x60;name&#x60;, &#x60;managedUserId&#x60;, &#x60;externalId&#x60; and &#x60;createdAt&#x60;; &#x60;composition.updated&#x60; carries &#x60;compositionId&#x60;, &#x60;widgetId&#x60;, &#x60;name&#x60;, &#x60;managedUserId&#x60;, &#x60;externalId&#x60;, &#x60;contentVersion&#x60; and &#x60;savedAt&#x60;, and is sent for the first save of a composition in each five minutes (read the composition for its current state); &#x60;widget.published&#x60; carries &#x60;widgetId&#x60;, &#x60;name&#x60;, &#x60;managedUserId&#x60;, &#x60;externalId&#x60;, &#x60;version&#x60; and &#x60;publishedAt&#x60;; &#x60;upload.created&#x60; carries &#x60;uploadId&#x60;, &#x60;name&#x60;, &#x60;mimeType&#x60;, &#x60;sizeBytes&#x60;, &#x60;address&#x60;, &#x60;managedUserId&#x60;, &#x60;externalId&#x60;, &#x60;purpose&#x60; and &#x60;createdAt&#x60;; &#x60;entry.created&#x60; carries &#x60;compositionId&#x60;, &#x60;table&#x60;, &#x60;entryId&#x60;, &#x60;createdAt&#x60; and &#x60;context&#x60; (the host attribution of the embedding page, or null), and none of the values the visitor entered: read those with the entries routes. The four workflow events are about the workflows your managed users make (only a workflow made for a managed user is told; one your own people made is not). &#x60;workflow.created&#x60; carries &#x60;workflowId&#x60;, &#x60;name&#x60;, &#x60;managedUserId&#x60;, &#x60;externalId&#x60;, &#x60;createdAt&#x60; and &#x60;presetKey&#x60; (the key you gave the starting point the workflow was started from with &#x60;setPartnerWorkflowPreset&#x60;, or null when it was drawn new or copied), and is sent for a copy of a workflow and for a start from a starting point too; &#x60;workflow.published&#x60; carries &#x60;workflowId&#x60;, &#x60;name&#x60;, &#x60;managedUserId&#x60;, &#x60;externalId&#x60;, &#x60;versionId&#x60;, &#x60;versionNumber&#x60; (1 for the first publication) and &#x60;publishedAt&#x60;; &#x60;workflow.state_changed&#x60; carries &#x60;workflowId&#x60;, &#x60;name&#x60;, &#x60;managedUserId&#x60;, &#x60;externalId&#x60;, &#x60;action&#x60; (&#x60;pause&#x60;, &#x60;resume&#x60;, &#x60;archive&#x60; or &#x60;unarchive&#x60;), &#x60;previousStatus&#x60; and &#x60;status&#x60; (each &#x60;draft&#x60;, &#x60;live&#x60;, &#x60;paused&#x60; or &#x60;archived&#x60;) and &#x60;changedAt&#x60;; &#x60;workflow.deleted&#x60; carries &#x60;workflowId&#x60;, &#x60;name&#x60;, &#x60;managedUserId&#x60;, &#x60;externalId&#x60;, &#x60;previousStatus&#x60; (the state it was in when it was deleted: &#x60;draft&#x60;, &#x60;live&#x60;, &#x60;paused&#x60; or &#x60;archived&#x60;) and &#x60;deletedAt&#x60;, and means that the workflow with its versions and counts is gone (the compositions it chained are not touched). Read the workflow for what it holds now (a deleted one is not found). Ignore an event type you do not know: more may be added. &#x60;sendPartnerNotificationTestEvent&#x60; sends a sample of every one of them. | 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewPartnerNotification

`func NewPartnerNotification(id string, type_ PartnerNotificationEventType, title string, body string, tone string, data map[string]interface{}, createdAt time.Time, ) *PartnerNotification`

NewPartnerNotification instantiates a new PartnerNotification object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerNotificationWithDefaults

`func NewPartnerNotificationWithDefaults() *PartnerNotification`

NewPartnerNotificationWithDefaults instantiates a new PartnerNotification object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PartnerNotification) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PartnerNotification) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PartnerNotification) SetId(v string)`

SetId sets Id field to given value.


### GetType

`func (o *PartnerNotification) GetType() PartnerNotificationEventType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PartnerNotification) GetTypeOk() (*PartnerNotificationEventType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PartnerNotification) SetType(v PartnerNotificationEventType)`

SetType sets Type field to given value.


### GetTitle

`func (o *PartnerNotification) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *PartnerNotification) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *PartnerNotification) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetBody

`func (o *PartnerNotification) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *PartnerNotification) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *PartnerNotification) SetBody(v string)`

SetBody sets Body field to given value.


### GetTone

`func (o *PartnerNotification) GetTone() string`

GetTone returns the Tone field if non-nil, zero value otherwise.

### GetToneOk

`func (o *PartnerNotification) GetToneOk() (*string, bool)`

GetToneOk returns a tuple with the Tone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTone

`func (o *PartnerNotification) SetTone(v string)`

SetTone sets Tone field to given value.


### GetData

`func (o *PartnerNotification) GetData() map[string]interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *PartnerNotification) GetDataOk() (*map[string]interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *PartnerNotification) SetData(v map[string]interface{})`

SetData sets Data field to given value.


### GetCreatedAt

`func (o *PartnerNotification) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *PartnerNotification) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *PartnerNotification) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


