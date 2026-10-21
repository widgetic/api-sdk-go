# PartnerCustomization

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Unique identifier for the customization | [optional] 
**PartnerId** | Pointer to **string** | ID of the partner this customization belongs to | [optional] 
**CustomPrice** | Pointer to **float32** | Custom monthly price override | [optional] 
**CustomCredits** | Pointer to **float32** | Credits the partner receives each billing period (&#x60;billingCycle&#x60;). What a period costs is derived from it, see &#x60;periodTotalUsd&#x60; | [optional] 
**CreditPriceUsd** | Pointer to **NullableFloat32** | What the partner pays for one credit, in dollars (up to four decimals). Null means the list price | [optional] 
**EffectiveCreditPriceUsd** | Pointer to **float32** | What one credit costs the partner, in dollars. &#x60;creditPriceUsd&#x60; when the contract names one, the list price otherwise | [optional] 
**PeriodTotalUsd** | Pointer to **NullableFloat32** | What one billing period costs, in dollars before tax. &#x60;customCredits&#x60; times &#x60;effectiveCreditPriceUsd&#x60;; null while the contract names no credits | [optional] 
**AdditionalFeatures** | Pointer to **[]string** | Additional features beyond base partner plan | [optional] 
**BillingCycle** | Pointer to **string** | Billing cycle for the customization | [optional] 
**MinimumCommitmentMonths** | Pointer to **float32** | Minimum commitment period in months | [optional] 
**SupportSla** | Pointer to **string** | Support SLA percentage | [optional] 
**ContractStartDate** | Pointer to **string** | Contract start date | [optional] 
**ContractEndDate** | Pointer to **string** | Contract end date | [optional] 
**Notes** | Pointer to **string** | Admin notes about the customization | [optional] 
**IsActiveContract** | Pointer to **bool** | Whether the contract is currently active | [optional] 
**CreatedAt** | Pointer to **time.Time** | Creation timestamp | [optional] 
**UpdatedAt** | Pointer to **time.Time** | Last update timestamp | [optional] 

## Methods

### NewPartnerCustomization

`func NewPartnerCustomization() *PartnerCustomization`

NewPartnerCustomization instantiates a new PartnerCustomization object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerCustomizationWithDefaults

`func NewPartnerCustomizationWithDefaults() *PartnerCustomization`

NewPartnerCustomizationWithDefaults instantiates a new PartnerCustomization object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PartnerCustomization) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PartnerCustomization) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PartnerCustomization) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *PartnerCustomization) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPartnerId

`func (o *PartnerCustomization) GetPartnerId() string`

GetPartnerId returns the PartnerId field if non-nil, zero value otherwise.

### GetPartnerIdOk

`func (o *PartnerCustomization) GetPartnerIdOk() (*string, bool)`

GetPartnerIdOk returns a tuple with the PartnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartnerId

`func (o *PartnerCustomization) SetPartnerId(v string)`

SetPartnerId sets PartnerId field to given value.

### HasPartnerId

`func (o *PartnerCustomization) HasPartnerId() bool`

HasPartnerId returns a boolean if a field has been set.

### GetCustomPrice

`func (o *PartnerCustomization) GetCustomPrice() float32`

GetCustomPrice returns the CustomPrice field if non-nil, zero value otherwise.

### GetCustomPriceOk

`func (o *PartnerCustomization) GetCustomPriceOk() (*float32, bool)`

GetCustomPriceOk returns a tuple with the CustomPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomPrice

`func (o *PartnerCustomization) SetCustomPrice(v float32)`

SetCustomPrice sets CustomPrice field to given value.

### HasCustomPrice

`func (o *PartnerCustomization) HasCustomPrice() bool`

HasCustomPrice returns a boolean if a field has been set.

### GetCustomCredits

`func (o *PartnerCustomization) GetCustomCredits() float32`

GetCustomCredits returns the CustomCredits field if non-nil, zero value otherwise.

### GetCustomCreditsOk

`func (o *PartnerCustomization) GetCustomCreditsOk() (*float32, bool)`

GetCustomCreditsOk returns a tuple with the CustomCredits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomCredits

`func (o *PartnerCustomization) SetCustomCredits(v float32)`

SetCustomCredits sets CustomCredits field to given value.

### HasCustomCredits

`func (o *PartnerCustomization) HasCustomCredits() bool`

HasCustomCredits returns a boolean if a field has been set.

### GetCreditPriceUsd

`func (o *PartnerCustomization) GetCreditPriceUsd() float32`

GetCreditPriceUsd returns the CreditPriceUsd field if non-nil, zero value otherwise.

### GetCreditPriceUsdOk

`func (o *PartnerCustomization) GetCreditPriceUsdOk() (*float32, bool)`

GetCreditPriceUsdOk returns a tuple with the CreditPriceUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditPriceUsd

`func (o *PartnerCustomization) SetCreditPriceUsd(v float32)`

SetCreditPriceUsd sets CreditPriceUsd field to given value.

### HasCreditPriceUsd

`func (o *PartnerCustomization) HasCreditPriceUsd() bool`

HasCreditPriceUsd returns a boolean if a field has been set.

### SetCreditPriceUsdNil

`func (o *PartnerCustomization) SetCreditPriceUsdNil(b bool)`

 SetCreditPriceUsdNil sets the value for CreditPriceUsd to be an explicit nil

### UnsetCreditPriceUsd
`func (o *PartnerCustomization) UnsetCreditPriceUsd()`

UnsetCreditPriceUsd ensures that no value is present for CreditPriceUsd, not even an explicit nil
### GetEffectiveCreditPriceUsd

`func (o *PartnerCustomization) GetEffectiveCreditPriceUsd() float32`

GetEffectiveCreditPriceUsd returns the EffectiveCreditPriceUsd field if non-nil, zero value otherwise.

### GetEffectiveCreditPriceUsdOk

`func (o *PartnerCustomization) GetEffectiveCreditPriceUsdOk() (*float32, bool)`

GetEffectiveCreditPriceUsdOk returns a tuple with the EffectiveCreditPriceUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectiveCreditPriceUsd

`func (o *PartnerCustomization) SetEffectiveCreditPriceUsd(v float32)`

SetEffectiveCreditPriceUsd sets EffectiveCreditPriceUsd field to given value.

### HasEffectiveCreditPriceUsd

`func (o *PartnerCustomization) HasEffectiveCreditPriceUsd() bool`

HasEffectiveCreditPriceUsd returns a boolean if a field has been set.

### GetPeriodTotalUsd

`func (o *PartnerCustomization) GetPeriodTotalUsd() float32`

GetPeriodTotalUsd returns the PeriodTotalUsd field if non-nil, zero value otherwise.

### GetPeriodTotalUsdOk

`func (o *PartnerCustomization) GetPeriodTotalUsdOk() (*float32, bool)`

GetPeriodTotalUsdOk returns a tuple with the PeriodTotalUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodTotalUsd

`func (o *PartnerCustomization) SetPeriodTotalUsd(v float32)`

SetPeriodTotalUsd sets PeriodTotalUsd field to given value.

### HasPeriodTotalUsd

`func (o *PartnerCustomization) HasPeriodTotalUsd() bool`

HasPeriodTotalUsd returns a boolean if a field has been set.

### SetPeriodTotalUsdNil

`func (o *PartnerCustomization) SetPeriodTotalUsdNil(b bool)`

 SetPeriodTotalUsdNil sets the value for PeriodTotalUsd to be an explicit nil

### UnsetPeriodTotalUsd
`func (o *PartnerCustomization) UnsetPeriodTotalUsd()`

UnsetPeriodTotalUsd ensures that no value is present for PeriodTotalUsd, not even an explicit nil
### GetAdditionalFeatures

`func (o *PartnerCustomization) GetAdditionalFeatures() []string`

GetAdditionalFeatures returns the AdditionalFeatures field if non-nil, zero value otherwise.

### GetAdditionalFeaturesOk

`func (o *PartnerCustomization) GetAdditionalFeaturesOk() (*[]string, bool)`

GetAdditionalFeaturesOk returns a tuple with the AdditionalFeatures field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalFeatures

`func (o *PartnerCustomization) SetAdditionalFeatures(v []string)`

SetAdditionalFeatures sets AdditionalFeatures field to given value.

### HasAdditionalFeatures

`func (o *PartnerCustomization) HasAdditionalFeatures() bool`

HasAdditionalFeatures returns a boolean if a field has been set.

### GetBillingCycle

`func (o *PartnerCustomization) GetBillingCycle() string`

GetBillingCycle returns the BillingCycle field if non-nil, zero value otherwise.

### GetBillingCycleOk

`func (o *PartnerCustomization) GetBillingCycleOk() (*string, bool)`

GetBillingCycleOk returns a tuple with the BillingCycle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingCycle

`func (o *PartnerCustomization) SetBillingCycle(v string)`

SetBillingCycle sets BillingCycle field to given value.

### HasBillingCycle

`func (o *PartnerCustomization) HasBillingCycle() bool`

HasBillingCycle returns a boolean if a field has been set.

### GetMinimumCommitmentMonths

`func (o *PartnerCustomization) GetMinimumCommitmentMonths() float32`

GetMinimumCommitmentMonths returns the MinimumCommitmentMonths field if non-nil, zero value otherwise.

### GetMinimumCommitmentMonthsOk

`func (o *PartnerCustomization) GetMinimumCommitmentMonthsOk() (*float32, bool)`

GetMinimumCommitmentMonthsOk returns a tuple with the MinimumCommitmentMonths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumCommitmentMonths

`func (o *PartnerCustomization) SetMinimumCommitmentMonths(v float32)`

SetMinimumCommitmentMonths sets MinimumCommitmentMonths field to given value.

### HasMinimumCommitmentMonths

`func (o *PartnerCustomization) HasMinimumCommitmentMonths() bool`

HasMinimumCommitmentMonths returns a boolean if a field has been set.

### GetSupportSla

`func (o *PartnerCustomization) GetSupportSla() string`

GetSupportSla returns the SupportSla field if non-nil, zero value otherwise.

### GetSupportSlaOk

`func (o *PartnerCustomization) GetSupportSlaOk() (*string, bool)`

GetSupportSlaOk returns a tuple with the SupportSla field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportSla

`func (o *PartnerCustomization) SetSupportSla(v string)`

SetSupportSla sets SupportSla field to given value.

### HasSupportSla

`func (o *PartnerCustomization) HasSupportSla() bool`

HasSupportSla returns a boolean if a field has been set.

### GetContractStartDate

`func (o *PartnerCustomization) GetContractStartDate() string`

GetContractStartDate returns the ContractStartDate field if non-nil, zero value otherwise.

### GetContractStartDateOk

`func (o *PartnerCustomization) GetContractStartDateOk() (*string, bool)`

GetContractStartDateOk returns a tuple with the ContractStartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContractStartDate

`func (o *PartnerCustomization) SetContractStartDate(v string)`

SetContractStartDate sets ContractStartDate field to given value.

### HasContractStartDate

`func (o *PartnerCustomization) HasContractStartDate() bool`

HasContractStartDate returns a boolean if a field has been set.

### GetContractEndDate

`func (o *PartnerCustomization) GetContractEndDate() string`

GetContractEndDate returns the ContractEndDate field if non-nil, zero value otherwise.

### GetContractEndDateOk

`func (o *PartnerCustomization) GetContractEndDateOk() (*string, bool)`

GetContractEndDateOk returns a tuple with the ContractEndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContractEndDate

`func (o *PartnerCustomization) SetContractEndDate(v string)`

SetContractEndDate sets ContractEndDate field to given value.

### HasContractEndDate

`func (o *PartnerCustomization) HasContractEndDate() bool`

HasContractEndDate returns a boolean if a field has been set.

### GetNotes

`func (o *PartnerCustomization) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *PartnerCustomization) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *PartnerCustomization) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *PartnerCustomization) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### GetIsActiveContract

`func (o *PartnerCustomization) GetIsActiveContract() bool`

GetIsActiveContract returns the IsActiveContract field if non-nil, zero value otherwise.

### GetIsActiveContractOk

`func (o *PartnerCustomization) GetIsActiveContractOk() (*bool, bool)`

GetIsActiveContractOk returns a tuple with the IsActiveContract field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActiveContract

`func (o *PartnerCustomization) SetIsActiveContract(v bool)`

SetIsActiveContract sets IsActiveContract field to given value.

### HasIsActiveContract

`func (o *PartnerCustomization) HasIsActiveContract() bool`

HasIsActiveContract returns a boolean if a field has been set.

### GetCreatedAt

`func (o *PartnerCustomization) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *PartnerCustomization) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *PartnerCustomization) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *PartnerCustomization) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *PartnerCustomization) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *PartnerCustomization) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *PartnerCustomization) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *PartnerCustomization) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


