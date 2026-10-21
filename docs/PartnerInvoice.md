# PartnerInvoice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**PartnerId** | Pointer to **NullableString** |  | [optional] 
**Number** | Pointer to **NullableString** | The number printed on the invoice, once it has been issued | [optional] 
**Description** | Pointer to **NullableString** | What the invoice is for | [optional] 
**Amount** | Pointer to **float32** | Total, in dollars. The price plus the tax (the same number as &#x60;total&#x60;) | [optional] 
**Subtotal** | Pointer to **float32** | The price, before tax, in dollars | [optional] 
**TaxAmount** | Pointer to **float32** | The tax on the price, in dollars. 0 when there is none, for example under the EU reverse charge | [optional] 
**Total** | Pointer to **float32** | What the partner pays, in dollars. The price plus the tax | [optional] 
**AmountDue** | Pointer to **NullableFloat32** | What is still owed, in dollars | [optional] 
**AmountPaid** | Pointer to **NullableFloat32** | What has been paid, in dollars | [optional] 
**Currency** | Pointer to **NullableString** |  | [optional] 
**FailureReason** | Pointer to **NullableString** | Why the last attempt to pay failed, in the payment provider&#39;s words for the card holder. Null unless the status is &#x60;failed&#x60;; the invoice stays payable from &#x60;hostedInvoiceUrl&#x60; | [optional] 
**Status** | Pointer to **string** | &#x60;open&#x60; waits for payment, &#x60;failed&#x60; waits for payment after an attempt was refused, &#x60;paid&#x60; is settled (a payment received outside the payment provider counts), &#x60;void&#x60; was cancelled and owes nothing, and &#x60;uncollectible&#x60; was written off  | [optional] 
**InvoiceDate** | Pointer to **NullableTime** |  | [optional] 
**DueDate** | Pointer to **NullableTime** |  | [optional] 
**PaidDate** | Pointer to **NullableTime** |  | [optional] 
**PeriodStart** | Pointer to **NullableTime** |  | [optional] 
**PeriodEnd** | Pointer to **NullableTime** |  | [optional] 
**PaymentMethod** | Pointer to **NullableString** | How it was paid, once it was | [optional] 
**HostedInvoiceUrl** | Pointer to **NullableString** | The page where the invoice can be viewed and paid, once it has been issued | [optional] 
**PdfUrl** | Pointer to **NullableString** | A PDF of the invoice, once it has been issued | [optional] 
**LineItems** | Pointer to **[]map[string]interface{}** |  | [optional] 
**CreatedAt** | Pointer to **NullableTime** |  | [optional] 
**UpdatedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewPartnerInvoice

`func NewPartnerInvoice() *PartnerInvoice`

NewPartnerInvoice instantiates a new PartnerInvoice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerInvoiceWithDefaults

`func NewPartnerInvoiceWithDefaults() *PartnerInvoice`

NewPartnerInvoiceWithDefaults instantiates a new PartnerInvoice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PartnerInvoice) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PartnerInvoice) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PartnerInvoice) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *PartnerInvoice) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPartnerId

`func (o *PartnerInvoice) GetPartnerId() string`

GetPartnerId returns the PartnerId field if non-nil, zero value otherwise.

### GetPartnerIdOk

`func (o *PartnerInvoice) GetPartnerIdOk() (*string, bool)`

GetPartnerIdOk returns a tuple with the PartnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartnerId

`func (o *PartnerInvoice) SetPartnerId(v string)`

SetPartnerId sets PartnerId field to given value.

### HasPartnerId

`func (o *PartnerInvoice) HasPartnerId() bool`

HasPartnerId returns a boolean if a field has been set.

### SetPartnerIdNil

`func (o *PartnerInvoice) SetPartnerIdNil(b bool)`

 SetPartnerIdNil sets the value for PartnerId to be an explicit nil

### UnsetPartnerId
`func (o *PartnerInvoice) UnsetPartnerId()`

UnsetPartnerId ensures that no value is present for PartnerId, not even an explicit nil
### GetNumber

`func (o *PartnerInvoice) GetNumber() string`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *PartnerInvoice) GetNumberOk() (*string, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *PartnerInvoice) SetNumber(v string)`

SetNumber sets Number field to given value.

### HasNumber

`func (o *PartnerInvoice) HasNumber() bool`

HasNumber returns a boolean if a field has been set.

### SetNumberNil

`func (o *PartnerInvoice) SetNumberNil(b bool)`

 SetNumberNil sets the value for Number to be an explicit nil

### UnsetNumber
`func (o *PartnerInvoice) UnsetNumber()`

UnsetNumber ensures that no value is present for Number, not even an explicit nil
### GetDescription

`func (o *PartnerInvoice) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PartnerInvoice) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PartnerInvoice) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *PartnerInvoice) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *PartnerInvoice) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *PartnerInvoice) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetAmount

`func (o *PartnerInvoice) GetAmount() float32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *PartnerInvoice) GetAmountOk() (*float32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *PartnerInvoice) SetAmount(v float32)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *PartnerInvoice) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetSubtotal

`func (o *PartnerInvoice) GetSubtotal() float32`

GetSubtotal returns the Subtotal field if non-nil, zero value otherwise.

### GetSubtotalOk

`func (o *PartnerInvoice) GetSubtotalOk() (*float32, bool)`

GetSubtotalOk returns a tuple with the Subtotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtotal

`func (o *PartnerInvoice) SetSubtotal(v float32)`

SetSubtotal sets Subtotal field to given value.

### HasSubtotal

`func (o *PartnerInvoice) HasSubtotal() bool`

HasSubtotal returns a boolean if a field has been set.

### GetTaxAmount

`func (o *PartnerInvoice) GetTaxAmount() float32`

GetTaxAmount returns the TaxAmount field if non-nil, zero value otherwise.

### GetTaxAmountOk

`func (o *PartnerInvoice) GetTaxAmountOk() (*float32, bool)`

GetTaxAmountOk returns a tuple with the TaxAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxAmount

`func (o *PartnerInvoice) SetTaxAmount(v float32)`

SetTaxAmount sets TaxAmount field to given value.

### HasTaxAmount

`func (o *PartnerInvoice) HasTaxAmount() bool`

HasTaxAmount returns a boolean if a field has been set.

### GetTotal

`func (o *PartnerInvoice) GetTotal() float32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *PartnerInvoice) GetTotalOk() (*float32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *PartnerInvoice) SetTotal(v float32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *PartnerInvoice) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetAmountDue

`func (o *PartnerInvoice) GetAmountDue() float32`

GetAmountDue returns the AmountDue field if non-nil, zero value otherwise.

### GetAmountDueOk

`func (o *PartnerInvoice) GetAmountDueOk() (*float32, bool)`

GetAmountDueOk returns a tuple with the AmountDue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmountDue

`func (o *PartnerInvoice) SetAmountDue(v float32)`

SetAmountDue sets AmountDue field to given value.

### HasAmountDue

`func (o *PartnerInvoice) HasAmountDue() bool`

HasAmountDue returns a boolean if a field has been set.

### SetAmountDueNil

`func (o *PartnerInvoice) SetAmountDueNil(b bool)`

 SetAmountDueNil sets the value for AmountDue to be an explicit nil

### UnsetAmountDue
`func (o *PartnerInvoice) UnsetAmountDue()`

UnsetAmountDue ensures that no value is present for AmountDue, not even an explicit nil
### GetAmountPaid

`func (o *PartnerInvoice) GetAmountPaid() float32`

GetAmountPaid returns the AmountPaid field if non-nil, zero value otherwise.

### GetAmountPaidOk

`func (o *PartnerInvoice) GetAmountPaidOk() (*float32, bool)`

GetAmountPaidOk returns a tuple with the AmountPaid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmountPaid

`func (o *PartnerInvoice) SetAmountPaid(v float32)`

SetAmountPaid sets AmountPaid field to given value.

### HasAmountPaid

`func (o *PartnerInvoice) HasAmountPaid() bool`

HasAmountPaid returns a boolean if a field has been set.

### SetAmountPaidNil

`func (o *PartnerInvoice) SetAmountPaidNil(b bool)`

 SetAmountPaidNil sets the value for AmountPaid to be an explicit nil

### UnsetAmountPaid
`func (o *PartnerInvoice) UnsetAmountPaid()`

UnsetAmountPaid ensures that no value is present for AmountPaid, not even an explicit nil
### GetCurrency

`func (o *PartnerInvoice) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *PartnerInvoice) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *PartnerInvoice) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *PartnerInvoice) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *PartnerInvoice) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *PartnerInvoice) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetFailureReason

`func (o *PartnerInvoice) GetFailureReason() string`

GetFailureReason returns the FailureReason field if non-nil, zero value otherwise.

### GetFailureReasonOk

`func (o *PartnerInvoice) GetFailureReasonOk() (*string, bool)`

GetFailureReasonOk returns a tuple with the FailureReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureReason

`func (o *PartnerInvoice) SetFailureReason(v string)`

SetFailureReason sets FailureReason field to given value.

### HasFailureReason

`func (o *PartnerInvoice) HasFailureReason() bool`

HasFailureReason returns a boolean if a field has been set.

### SetFailureReasonNil

`func (o *PartnerInvoice) SetFailureReasonNil(b bool)`

 SetFailureReasonNil sets the value for FailureReason to be an explicit nil

### UnsetFailureReason
`func (o *PartnerInvoice) UnsetFailureReason()`

UnsetFailureReason ensures that no value is present for FailureReason, not even an explicit nil
### GetStatus

`func (o *PartnerInvoice) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PartnerInvoice) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PartnerInvoice) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PartnerInvoice) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetInvoiceDate

`func (o *PartnerInvoice) GetInvoiceDate() time.Time`

GetInvoiceDate returns the InvoiceDate field if non-nil, zero value otherwise.

### GetInvoiceDateOk

`func (o *PartnerInvoice) GetInvoiceDateOk() (*time.Time, bool)`

GetInvoiceDateOk returns a tuple with the InvoiceDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceDate

`func (o *PartnerInvoice) SetInvoiceDate(v time.Time)`

SetInvoiceDate sets InvoiceDate field to given value.

### HasInvoiceDate

`func (o *PartnerInvoice) HasInvoiceDate() bool`

HasInvoiceDate returns a boolean if a field has been set.

### SetInvoiceDateNil

`func (o *PartnerInvoice) SetInvoiceDateNil(b bool)`

 SetInvoiceDateNil sets the value for InvoiceDate to be an explicit nil

### UnsetInvoiceDate
`func (o *PartnerInvoice) UnsetInvoiceDate()`

UnsetInvoiceDate ensures that no value is present for InvoiceDate, not even an explicit nil
### GetDueDate

`func (o *PartnerInvoice) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *PartnerInvoice) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *PartnerInvoice) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.

### HasDueDate

`func (o *PartnerInvoice) HasDueDate() bool`

HasDueDate returns a boolean if a field has been set.

### SetDueDateNil

`func (o *PartnerInvoice) SetDueDateNil(b bool)`

 SetDueDateNil sets the value for DueDate to be an explicit nil

### UnsetDueDate
`func (o *PartnerInvoice) UnsetDueDate()`

UnsetDueDate ensures that no value is present for DueDate, not even an explicit nil
### GetPaidDate

`func (o *PartnerInvoice) GetPaidDate() time.Time`

GetPaidDate returns the PaidDate field if non-nil, zero value otherwise.

### GetPaidDateOk

`func (o *PartnerInvoice) GetPaidDateOk() (*time.Time, bool)`

GetPaidDateOk returns a tuple with the PaidDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaidDate

`func (o *PartnerInvoice) SetPaidDate(v time.Time)`

SetPaidDate sets PaidDate field to given value.

### HasPaidDate

`func (o *PartnerInvoice) HasPaidDate() bool`

HasPaidDate returns a boolean if a field has been set.

### SetPaidDateNil

`func (o *PartnerInvoice) SetPaidDateNil(b bool)`

 SetPaidDateNil sets the value for PaidDate to be an explicit nil

### UnsetPaidDate
`func (o *PartnerInvoice) UnsetPaidDate()`

UnsetPaidDate ensures that no value is present for PaidDate, not even an explicit nil
### GetPeriodStart

`func (o *PartnerInvoice) GetPeriodStart() time.Time`

GetPeriodStart returns the PeriodStart field if non-nil, zero value otherwise.

### GetPeriodStartOk

`func (o *PartnerInvoice) GetPeriodStartOk() (*time.Time, bool)`

GetPeriodStartOk returns a tuple with the PeriodStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodStart

`func (o *PartnerInvoice) SetPeriodStart(v time.Time)`

SetPeriodStart sets PeriodStart field to given value.

### HasPeriodStart

`func (o *PartnerInvoice) HasPeriodStart() bool`

HasPeriodStart returns a boolean if a field has been set.

### SetPeriodStartNil

`func (o *PartnerInvoice) SetPeriodStartNil(b bool)`

 SetPeriodStartNil sets the value for PeriodStart to be an explicit nil

### UnsetPeriodStart
`func (o *PartnerInvoice) UnsetPeriodStart()`

UnsetPeriodStart ensures that no value is present for PeriodStart, not even an explicit nil
### GetPeriodEnd

`func (o *PartnerInvoice) GetPeriodEnd() time.Time`

GetPeriodEnd returns the PeriodEnd field if non-nil, zero value otherwise.

### GetPeriodEndOk

`func (o *PartnerInvoice) GetPeriodEndOk() (*time.Time, bool)`

GetPeriodEndOk returns a tuple with the PeriodEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodEnd

`func (o *PartnerInvoice) SetPeriodEnd(v time.Time)`

SetPeriodEnd sets PeriodEnd field to given value.

### HasPeriodEnd

`func (o *PartnerInvoice) HasPeriodEnd() bool`

HasPeriodEnd returns a boolean if a field has been set.

### SetPeriodEndNil

`func (o *PartnerInvoice) SetPeriodEndNil(b bool)`

 SetPeriodEndNil sets the value for PeriodEnd to be an explicit nil

### UnsetPeriodEnd
`func (o *PartnerInvoice) UnsetPeriodEnd()`

UnsetPeriodEnd ensures that no value is present for PeriodEnd, not even an explicit nil
### GetPaymentMethod

`func (o *PartnerInvoice) GetPaymentMethod() string`

GetPaymentMethod returns the PaymentMethod field if non-nil, zero value otherwise.

### GetPaymentMethodOk

`func (o *PartnerInvoice) GetPaymentMethodOk() (*string, bool)`

GetPaymentMethodOk returns a tuple with the PaymentMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentMethod

`func (o *PartnerInvoice) SetPaymentMethod(v string)`

SetPaymentMethod sets PaymentMethod field to given value.

### HasPaymentMethod

`func (o *PartnerInvoice) HasPaymentMethod() bool`

HasPaymentMethod returns a boolean if a field has been set.

### SetPaymentMethodNil

`func (o *PartnerInvoice) SetPaymentMethodNil(b bool)`

 SetPaymentMethodNil sets the value for PaymentMethod to be an explicit nil

### UnsetPaymentMethod
`func (o *PartnerInvoice) UnsetPaymentMethod()`

UnsetPaymentMethod ensures that no value is present for PaymentMethod, not even an explicit nil
### GetHostedInvoiceUrl

`func (o *PartnerInvoice) GetHostedInvoiceUrl() string`

GetHostedInvoiceUrl returns the HostedInvoiceUrl field if non-nil, zero value otherwise.

### GetHostedInvoiceUrlOk

`func (o *PartnerInvoice) GetHostedInvoiceUrlOk() (*string, bool)`

GetHostedInvoiceUrlOk returns a tuple with the HostedInvoiceUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostedInvoiceUrl

`func (o *PartnerInvoice) SetHostedInvoiceUrl(v string)`

SetHostedInvoiceUrl sets HostedInvoiceUrl field to given value.

### HasHostedInvoiceUrl

`func (o *PartnerInvoice) HasHostedInvoiceUrl() bool`

HasHostedInvoiceUrl returns a boolean if a field has been set.

### SetHostedInvoiceUrlNil

`func (o *PartnerInvoice) SetHostedInvoiceUrlNil(b bool)`

 SetHostedInvoiceUrlNil sets the value for HostedInvoiceUrl to be an explicit nil

### UnsetHostedInvoiceUrl
`func (o *PartnerInvoice) UnsetHostedInvoiceUrl()`

UnsetHostedInvoiceUrl ensures that no value is present for HostedInvoiceUrl, not even an explicit nil
### GetPdfUrl

`func (o *PartnerInvoice) GetPdfUrl() string`

GetPdfUrl returns the PdfUrl field if non-nil, zero value otherwise.

### GetPdfUrlOk

`func (o *PartnerInvoice) GetPdfUrlOk() (*string, bool)`

GetPdfUrlOk returns a tuple with the PdfUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPdfUrl

`func (o *PartnerInvoice) SetPdfUrl(v string)`

SetPdfUrl sets PdfUrl field to given value.

### HasPdfUrl

`func (o *PartnerInvoice) HasPdfUrl() bool`

HasPdfUrl returns a boolean if a field has been set.

### SetPdfUrlNil

`func (o *PartnerInvoice) SetPdfUrlNil(b bool)`

 SetPdfUrlNil sets the value for PdfUrl to be an explicit nil

### UnsetPdfUrl
`func (o *PartnerInvoice) UnsetPdfUrl()`

UnsetPdfUrl ensures that no value is present for PdfUrl, not even an explicit nil
### GetLineItems

`func (o *PartnerInvoice) GetLineItems() []map[string]interface{}`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *PartnerInvoice) GetLineItemsOk() (*[]map[string]interface{}, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *PartnerInvoice) SetLineItems(v []map[string]interface{})`

SetLineItems sets LineItems field to given value.

### HasLineItems

`func (o *PartnerInvoice) HasLineItems() bool`

HasLineItems returns a boolean if a field has been set.

### SetLineItemsNil

`func (o *PartnerInvoice) SetLineItemsNil(b bool)`

 SetLineItemsNil sets the value for LineItems to be an explicit nil

### UnsetLineItems
`func (o *PartnerInvoice) UnsetLineItems()`

UnsetLineItems ensures that no value is present for LineItems, not even an explicit nil
### GetCreatedAt

`func (o *PartnerInvoice) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *PartnerInvoice) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *PartnerInvoice) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *PartnerInvoice) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *PartnerInvoice) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *PartnerInvoice) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetUpdatedAt

`func (o *PartnerInvoice) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *PartnerInvoice) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *PartnerInvoice) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *PartnerInvoice) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *PartnerInvoice) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *PartnerInvoice) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


