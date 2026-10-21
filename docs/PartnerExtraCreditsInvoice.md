# PartnerExtraCreditsInvoice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**InvoiceId** | **string** | Stripe&#39;s id for the invoice. | 
**Number** | **NullableString** | The number printed on the invoice, once Stripe has numbered it. | 
**HostedInvoiceUrl** | **NullableString** | The page where the invoice is viewed and paid. | 
**PdfUrl** | **NullableString** | A PDF of the invoice. | 
**Credits** | **int32** | The credits paying the invoice adds, once and for good. They do not expire. | 
**CreditPriceUsd** | **float32** | What one credit costs, in dollars. It is the list price, not the price of the contract. | 
**AmountUsd** | **float32** | The price of those credits, in dollars, before tax. Never more than &#x60;usd&#x60; of the request. | 
**TaxUsd** | **float32** | The tax added to the invoice, in dollars (0 when there is none). | 
**TotalUsd** | **float32** | What is paid, in dollars. The price plus the tax. | 
**Currency** | **string** | The currency of the invoice, in upper case (USD). | 
**DueDate** | **NullableTime** | When payment is due, as printed on the invoice. | 
**DueDays** | **int32** | How many days there are to pay. | 

## Methods

### NewPartnerExtraCreditsInvoice

`func NewPartnerExtraCreditsInvoice(invoiceId string, number NullableString, hostedInvoiceUrl NullableString, pdfUrl NullableString, credits int32, creditPriceUsd float32, amountUsd float32, taxUsd float32, totalUsd float32, currency string, dueDate NullableTime, dueDays int32, ) *PartnerExtraCreditsInvoice`

NewPartnerExtraCreditsInvoice instantiates a new PartnerExtraCreditsInvoice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerExtraCreditsInvoiceWithDefaults

`func NewPartnerExtraCreditsInvoiceWithDefaults() *PartnerExtraCreditsInvoice`

NewPartnerExtraCreditsInvoiceWithDefaults instantiates a new PartnerExtraCreditsInvoice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInvoiceId

`func (o *PartnerExtraCreditsInvoice) GetInvoiceId() string`

GetInvoiceId returns the InvoiceId field if non-nil, zero value otherwise.

### GetInvoiceIdOk

`func (o *PartnerExtraCreditsInvoice) GetInvoiceIdOk() (*string, bool)`

GetInvoiceIdOk returns a tuple with the InvoiceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceId

`func (o *PartnerExtraCreditsInvoice) SetInvoiceId(v string)`

SetInvoiceId sets InvoiceId field to given value.


### GetNumber

`func (o *PartnerExtraCreditsInvoice) GetNumber() string`

GetNumber returns the Number field if non-nil, zero value otherwise.

### GetNumberOk

`func (o *PartnerExtraCreditsInvoice) GetNumberOk() (*string, bool)`

GetNumberOk returns a tuple with the Number field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumber

`func (o *PartnerExtraCreditsInvoice) SetNumber(v string)`

SetNumber sets Number field to given value.


### SetNumberNil

`func (o *PartnerExtraCreditsInvoice) SetNumberNil(b bool)`

 SetNumberNil sets the value for Number to be an explicit nil

### UnsetNumber
`func (o *PartnerExtraCreditsInvoice) UnsetNumber()`

UnsetNumber ensures that no value is present for Number, not even an explicit nil
### GetHostedInvoiceUrl

`func (o *PartnerExtraCreditsInvoice) GetHostedInvoiceUrl() string`

GetHostedInvoiceUrl returns the HostedInvoiceUrl field if non-nil, zero value otherwise.

### GetHostedInvoiceUrlOk

`func (o *PartnerExtraCreditsInvoice) GetHostedInvoiceUrlOk() (*string, bool)`

GetHostedInvoiceUrlOk returns a tuple with the HostedInvoiceUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostedInvoiceUrl

`func (o *PartnerExtraCreditsInvoice) SetHostedInvoiceUrl(v string)`

SetHostedInvoiceUrl sets HostedInvoiceUrl field to given value.


### SetHostedInvoiceUrlNil

`func (o *PartnerExtraCreditsInvoice) SetHostedInvoiceUrlNil(b bool)`

 SetHostedInvoiceUrlNil sets the value for HostedInvoiceUrl to be an explicit nil

### UnsetHostedInvoiceUrl
`func (o *PartnerExtraCreditsInvoice) UnsetHostedInvoiceUrl()`

UnsetHostedInvoiceUrl ensures that no value is present for HostedInvoiceUrl, not even an explicit nil
### GetPdfUrl

`func (o *PartnerExtraCreditsInvoice) GetPdfUrl() string`

GetPdfUrl returns the PdfUrl field if non-nil, zero value otherwise.

### GetPdfUrlOk

`func (o *PartnerExtraCreditsInvoice) GetPdfUrlOk() (*string, bool)`

GetPdfUrlOk returns a tuple with the PdfUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPdfUrl

`func (o *PartnerExtraCreditsInvoice) SetPdfUrl(v string)`

SetPdfUrl sets PdfUrl field to given value.


### SetPdfUrlNil

`func (o *PartnerExtraCreditsInvoice) SetPdfUrlNil(b bool)`

 SetPdfUrlNil sets the value for PdfUrl to be an explicit nil

### UnsetPdfUrl
`func (o *PartnerExtraCreditsInvoice) UnsetPdfUrl()`

UnsetPdfUrl ensures that no value is present for PdfUrl, not even an explicit nil
### GetCredits

`func (o *PartnerExtraCreditsInvoice) GetCredits() int32`

GetCredits returns the Credits field if non-nil, zero value otherwise.

### GetCreditsOk

`func (o *PartnerExtraCreditsInvoice) GetCreditsOk() (*int32, bool)`

GetCreditsOk returns a tuple with the Credits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredits

`func (o *PartnerExtraCreditsInvoice) SetCredits(v int32)`

SetCredits sets Credits field to given value.


### GetCreditPriceUsd

`func (o *PartnerExtraCreditsInvoice) GetCreditPriceUsd() float32`

GetCreditPriceUsd returns the CreditPriceUsd field if non-nil, zero value otherwise.

### GetCreditPriceUsdOk

`func (o *PartnerExtraCreditsInvoice) GetCreditPriceUsdOk() (*float32, bool)`

GetCreditPriceUsdOk returns a tuple with the CreditPriceUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditPriceUsd

`func (o *PartnerExtraCreditsInvoice) SetCreditPriceUsd(v float32)`

SetCreditPriceUsd sets CreditPriceUsd field to given value.


### GetAmountUsd

`func (o *PartnerExtraCreditsInvoice) GetAmountUsd() float32`

GetAmountUsd returns the AmountUsd field if non-nil, zero value otherwise.

### GetAmountUsdOk

`func (o *PartnerExtraCreditsInvoice) GetAmountUsdOk() (*float32, bool)`

GetAmountUsdOk returns a tuple with the AmountUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmountUsd

`func (o *PartnerExtraCreditsInvoice) SetAmountUsd(v float32)`

SetAmountUsd sets AmountUsd field to given value.


### GetTaxUsd

`func (o *PartnerExtraCreditsInvoice) GetTaxUsd() float32`

GetTaxUsd returns the TaxUsd field if non-nil, zero value otherwise.

### GetTaxUsdOk

`func (o *PartnerExtraCreditsInvoice) GetTaxUsdOk() (*float32, bool)`

GetTaxUsdOk returns a tuple with the TaxUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxUsd

`func (o *PartnerExtraCreditsInvoice) SetTaxUsd(v float32)`

SetTaxUsd sets TaxUsd field to given value.


### GetTotalUsd

`func (o *PartnerExtraCreditsInvoice) GetTotalUsd() float32`

GetTotalUsd returns the TotalUsd field if non-nil, zero value otherwise.

### GetTotalUsdOk

`func (o *PartnerExtraCreditsInvoice) GetTotalUsdOk() (*float32, bool)`

GetTotalUsdOk returns a tuple with the TotalUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalUsd

`func (o *PartnerExtraCreditsInvoice) SetTotalUsd(v float32)`

SetTotalUsd sets TotalUsd field to given value.


### GetCurrency

`func (o *PartnerExtraCreditsInvoice) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *PartnerExtraCreditsInvoice) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *PartnerExtraCreditsInvoice) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetDueDate

`func (o *PartnerExtraCreditsInvoice) GetDueDate() time.Time`

GetDueDate returns the DueDate field if non-nil, zero value otherwise.

### GetDueDateOk

`func (o *PartnerExtraCreditsInvoice) GetDueDateOk() (*time.Time, bool)`

GetDueDateOk returns a tuple with the DueDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDate

`func (o *PartnerExtraCreditsInvoice) SetDueDate(v time.Time)`

SetDueDate sets DueDate field to given value.


### SetDueDateNil

`func (o *PartnerExtraCreditsInvoice) SetDueDateNil(b bool)`

 SetDueDateNil sets the value for DueDate to be an explicit nil

### UnsetDueDate
`func (o *PartnerExtraCreditsInvoice) UnsetDueDate()`

UnsetDueDate ensures that no value is present for DueDate, not even an explicit nil
### GetDueDays

`func (o *PartnerExtraCreditsInvoice) GetDueDays() int32`

GetDueDays returns the DueDays field if non-nil, zero value otherwise.

### GetDueDaysOk

`func (o *PartnerExtraCreditsInvoice) GetDueDaysOk() (*int32, bool)`

GetDueDaysOk returns a tuple with the DueDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueDays

`func (o *PartnerExtraCreditsInvoice) SetDueDays(v int32)`

SetDueDays sets DueDays field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


