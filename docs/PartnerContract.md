# PartnerContract

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**PartnerId** | Pointer to **string** |  | [optional] 
**CustomPrice** | Pointer to **NullableFloat32** | The agreed price per &#x60;billingCycle&#x60;; null when the standard price applies | [optional] 
**CustomCredits** | Pointer to **NullableInt32** | Credits received each billing period (&#x60;billingCycle&#x60;); null when the standard allowance applies | [optional] 
**CreditPriceUsd** | Pointer to **NullableFloat32** | The agreed price of one credit, in dollars; null when the list price applies | [optional] 
**EffectiveCreditPriceUsd** | Pointer to **float32** | What one credit costs you, in dollars. The agreed price, or the list price when none was agreed | [optional] 
**PeriodTotalUsd** | Pointer to **NullableFloat32** | What one billing period costs, in dollars before tax, &#x60;customCredits&#x60; times &#x60;effectiveCreditPriceUsd&#x60;. Null while no credits were agreed | [optional] 
**AdditionalFeatures** | Pointer to **[]string** | Features included beyond the standard partner plan | [optional] 
**BillingCycle** | Pointer to **string** |  | [optional] 
**MinimumCommitmentMonths** | Pointer to **int32** |  | [optional] 
**SupportSla** | Pointer to **string** |  | [optional] 
**ContractStartDate** | Pointer to **NullableString** |  | [optional] 
**ContractEndDate** | Pointer to **NullableString** | Null when the contract runs until it is ended | [optional] 
**IsActiveContract** | Pointer to **bool** | True while the contract is in force, that is when it is open-ended or today falls between its start and end | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewPartnerContract

`func NewPartnerContract() *PartnerContract`

NewPartnerContract instantiates a new PartnerContract object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerContractWithDefaults

`func NewPartnerContractWithDefaults() *PartnerContract`

NewPartnerContractWithDefaults instantiates a new PartnerContract object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PartnerContract) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PartnerContract) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PartnerContract) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *PartnerContract) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPartnerId

`func (o *PartnerContract) GetPartnerId() string`

GetPartnerId returns the PartnerId field if non-nil, zero value otherwise.

### GetPartnerIdOk

`func (o *PartnerContract) GetPartnerIdOk() (*string, bool)`

GetPartnerIdOk returns a tuple with the PartnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartnerId

`func (o *PartnerContract) SetPartnerId(v string)`

SetPartnerId sets PartnerId field to given value.

### HasPartnerId

`func (o *PartnerContract) HasPartnerId() bool`

HasPartnerId returns a boolean if a field has been set.

### GetCustomPrice

`func (o *PartnerContract) GetCustomPrice() float32`

GetCustomPrice returns the CustomPrice field if non-nil, zero value otherwise.

### GetCustomPriceOk

`func (o *PartnerContract) GetCustomPriceOk() (*float32, bool)`

GetCustomPriceOk returns a tuple with the CustomPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomPrice

`func (o *PartnerContract) SetCustomPrice(v float32)`

SetCustomPrice sets CustomPrice field to given value.

### HasCustomPrice

`func (o *PartnerContract) HasCustomPrice() bool`

HasCustomPrice returns a boolean if a field has been set.

### SetCustomPriceNil

`func (o *PartnerContract) SetCustomPriceNil(b bool)`

 SetCustomPriceNil sets the value for CustomPrice to be an explicit nil

### UnsetCustomPrice
`func (o *PartnerContract) UnsetCustomPrice()`

UnsetCustomPrice ensures that no value is present for CustomPrice, not even an explicit nil
### GetCustomCredits

`func (o *PartnerContract) GetCustomCredits() int32`

GetCustomCredits returns the CustomCredits field if non-nil, zero value otherwise.

### GetCustomCreditsOk

`func (o *PartnerContract) GetCustomCreditsOk() (*int32, bool)`

GetCustomCreditsOk returns a tuple with the CustomCredits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomCredits

`func (o *PartnerContract) SetCustomCredits(v int32)`

SetCustomCredits sets CustomCredits field to given value.

### HasCustomCredits

`func (o *PartnerContract) HasCustomCredits() bool`

HasCustomCredits returns a boolean if a field has been set.

### SetCustomCreditsNil

`func (o *PartnerContract) SetCustomCreditsNil(b bool)`

 SetCustomCreditsNil sets the value for CustomCredits to be an explicit nil

### UnsetCustomCredits
`func (o *PartnerContract) UnsetCustomCredits()`

UnsetCustomCredits ensures that no value is present for CustomCredits, not even an explicit nil
### GetCreditPriceUsd

`func (o *PartnerContract) GetCreditPriceUsd() float32`

GetCreditPriceUsd returns the CreditPriceUsd field if non-nil, zero value otherwise.

### GetCreditPriceUsdOk

`func (o *PartnerContract) GetCreditPriceUsdOk() (*float32, bool)`

GetCreditPriceUsdOk returns a tuple with the CreditPriceUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditPriceUsd

`func (o *PartnerContract) SetCreditPriceUsd(v float32)`

SetCreditPriceUsd sets CreditPriceUsd field to given value.

### HasCreditPriceUsd

`func (o *PartnerContract) HasCreditPriceUsd() bool`

HasCreditPriceUsd returns a boolean if a field has been set.

### SetCreditPriceUsdNil

`func (o *PartnerContract) SetCreditPriceUsdNil(b bool)`

 SetCreditPriceUsdNil sets the value for CreditPriceUsd to be an explicit nil

### UnsetCreditPriceUsd
`func (o *PartnerContract) UnsetCreditPriceUsd()`

UnsetCreditPriceUsd ensures that no value is present for CreditPriceUsd, not even an explicit nil
### GetEffectiveCreditPriceUsd

`func (o *PartnerContract) GetEffectiveCreditPriceUsd() float32`

GetEffectiveCreditPriceUsd returns the EffectiveCreditPriceUsd field if non-nil, zero value otherwise.

### GetEffectiveCreditPriceUsdOk

`func (o *PartnerContract) GetEffectiveCreditPriceUsdOk() (*float32, bool)`

GetEffectiveCreditPriceUsdOk returns a tuple with the EffectiveCreditPriceUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffectiveCreditPriceUsd

`func (o *PartnerContract) SetEffectiveCreditPriceUsd(v float32)`

SetEffectiveCreditPriceUsd sets EffectiveCreditPriceUsd field to given value.

### HasEffectiveCreditPriceUsd

`func (o *PartnerContract) HasEffectiveCreditPriceUsd() bool`

HasEffectiveCreditPriceUsd returns a boolean if a field has been set.

### GetPeriodTotalUsd

`func (o *PartnerContract) GetPeriodTotalUsd() float32`

GetPeriodTotalUsd returns the PeriodTotalUsd field if non-nil, zero value otherwise.

### GetPeriodTotalUsdOk

`func (o *PartnerContract) GetPeriodTotalUsdOk() (*float32, bool)`

GetPeriodTotalUsdOk returns a tuple with the PeriodTotalUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodTotalUsd

`func (o *PartnerContract) SetPeriodTotalUsd(v float32)`

SetPeriodTotalUsd sets PeriodTotalUsd field to given value.

### HasPeriodTotalUsd

`func (o *PartnerContract) HasPeriodTotalUsd() bool`

HasPeriodTotalUsd returns a boolean if a field has been set.

### SetPeriodTotalUsdNil

`func (o *PartnerContract) SetPeriodTotalUsdNil(b bool)`

 SetPeriodTotalUsdNil sets the value for PeriodTotalUsd to be an explicit nil

### UnsetPeriodTotalUsd
`func (o *PartnerContract) UnsetPeriodTotalUsd()`

UnsetPeriodTotalUsd ensures that no value is present for PeriodTotalUsd, not even an explicit nil
### GetAdditionalFeatures

`func (o *PartnerContract) GetAdditionalFeatures() []string`

GetAdditionalFeatures returns the AdditionalFeatures field if non-nil, zero value otherwise.

### GetAdditionalFeaturesOk

`func (o *PartnerContract) GetAdditionalFeaturesOk() (*[]string, bool)`

GetAdditionalFeaturesOk returns a tuple with the AdditionalFeatures field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalFeatures

`func (o *PartnerContract) SetAdditionalFeatures(v []string)`

SetAdditionalFeatures sets AdditionalFeatures field to given value.

### HasAdditionalFeatures

`func (o *PartnerContract) HasAdditionalFeatures() bool`

HasAdditionalFeatures returns a boolean if a field has been set.

### GetBillingCycle

`func (o *PartnerContract) GetBillingCycle() string`

GetBillingCycle returns the BillingCycle field if non-nil, zero value otherwise.

### GetBillingCycleOk

`func (o *PartnerContract) GetBillingCycleOk() (*string, bool)`

GetBillingCycleOk returns a tuple with the BillingCycle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingCycle

`func (o *PartnerContract) SetBillingCycle(v string)`

SetBillingCycle sets BillingCycle field to given value.

### HasBillingCycle

`func (o *PartnerContract) HasBillingCycle() bool`

HasBillingCycle returns a boolean if a field has been set.

### GetMinimumCommitmentMonths

`func (o *PartnerContract) GetMinimumCommitmentMonths() int32`

GetMinimumCommitmentMonths returns the MinimumCommitmentMonths field if non-nil, zero value otherwise.

### GetMinimumCommitmentMonthsOk

`func (o *PartnerContract) GetMinimumCommitmentMonthsOk() (*int32, bool)`

GetMinimumCommitmentMonthsOk returns a tuple with the MinimumCommitmentMonths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimumCommitmentMonths

`func (o *PartnerContract) SetMinimumCommitmentMonths(v int32)`

SetMinimumCommitmentMonths sets MinimumCommitmentMonths field to given value.

### HasMinimumCommitmentMonths

`func (o *PartnerContract) HasMinimumCommitmentMonths() bool`

HasMinimumCommitmentMonths returns a boolean if a field has been set.

### GetSupportSla

`func (o *PartnerContract) GetSupportSla() string`

GetSupportSla returns the SupportSla field if non-nil, zero value otherwise.

### GetSupportSlaOk

`func (o *PartnerContract) GetSupportSlaOk() (*string, bool)`

GetSupportSlaOk returns a tuple with the SupportSla field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportSla

`func (o *PartnerContract) SetSupportSla(v string)`

SetSupportSla sets SupportSla field to given value.

### HasSupportSla

`func (o *PartnerContract) HasSupportSla() bool`

HasSupportSla returns a boolean if a field has been set.

### GetContractStartDate

`func (o *PartnerContract) GetContractStartDate() string`

GetContractStartDate returns the ContractStartDate field if non-nil, zero value otherwise.

### GetContractStartDateOk

`func (o *PartnerContract) GetContractStartDateOk() (*string, bool)`

GetContractStartDateOk returns a tuple with the ContractStartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContractStartDate

`func (o *PartnerContract) SetContractStartDate(v string)`

SetContractStartDate sets ContractStartDate field to given value.

### HasContractStartDate

`func (o *PartnerContract) HasContractStartDate() bool`

HasContractStartDate returns a boolean if a field has been set.

### SetContractStartDateNil

`func (o *PartnerContract) SetContractStartDateNil(b bool)`

 SetContractStartDateNil sets the value for ContractStartDate to be an explicit nil

### UnsetContractStartDate
`func (o *PartnerContract) UnsetContractStartDate()`

UnsetContractStartDate ensures that no value is present for ContractStartDate, not even an explicit nil
### GetContractEndDate

`func (o *PartnerContract) GetContractEndDate() string`

GetContractEndDate returns the ContractEndDate field if non-nil, zero value otherwise.

### GetContractEndDateOk

`func (o *PartnerContract) GetContractEndDateOk() (*string, bool)`

GetContractEndDateOk returns a tuple with the ContractEndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContractEndDate

`func (o *PartnerContract) SetContractEndDate(v string)`

SetContractEndDate sets ContractEndDate field to given value.

### HasContractEndDate

`func (o *PartnerContract) HasContractEndDate() bool`

HasContractEndDate returns a boolean if a field has been set.

### SetContractEndDateNil

`func (o *PartnerContract) SetContractEndDateNil(b bool)`

 SetContractEndDateNil sets the value for ContractEndDate to be an explicit nil

### UnsetContractEndDate
`func (o *PartnerContract) UnsetContractEndDate()`

UnsetContractEndDate ensures that no value is present for ContractEndDate, not even an explicit nil
### GetIsActiveContract

`func (o *PartnerContract) GetIsActiveContract() bool`

GetIsActiveContract returns the IsActiveContract field if non-nil, zero value otherwise.

### GetIsActiveContractOk

`func (o *PartnerContract) GetIsActiveContractOk() (*bool, bool)`

GetIsActiveContractOk returns a tuple with the IsActiveContract field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActiveContract

`func (o *PartnerContract) SetIsActiveContract(v bool)`

SetIsActiveContract sets IsActiveContract field to given value.

### HasIsActiveContract

`func (o *PartnerContract) HasIsActiveContract() bool`

HasIsActiveContract returns a boolean if a field has been set.

### GetCreatedAt

`func (o *PartnerContract) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *PartnerContract) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *PartnerContract) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *PartnerContract) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *PartnerContract) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *PartnerContract) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *PartnerContract) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *PartnerContract) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


