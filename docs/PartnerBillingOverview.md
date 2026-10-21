# PartnerBillingOverview

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Partner** | [**PartnerBillingOverviewPartner**](PartnerBillingOverviewPartner.md) |  | 
**OperationalCredits** | [**PartnerBillingOverviewOperationalCredits**](PartnerBillingOverviewOperationalCredits.md) |  | 
**PartnerCustomization** | Pointer to [**NullablePartnerCustomization**](PartnerCustomization.md) | The partner&#39;s contract; null while none has been recorded | [optional] 
**BillingIntegration** | [**PartnerBillingOverviewBillingIntegration**](PartnerBillingOverviewBillingIntegration.md) |  | 

## Methods

### NewPartnerBillingOverview

`func NewPartnerBillingOverview(partner PartnerBillingOverviewPartner, operationalCredits PartnerBillingOverviewOperationalCredits, billingIntegration PartnerBillingOverviewBillingIntegration, ) *PartnerBillingOverview`

NewPartnerBillingOverview instantiates a new PartnerBillingOverview object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerBillingOverviewWithDefaults

`func NewPartnerBillingOverviewWithDefaults() *PartnerBillingOverview`

NewPartnerBillingOverviewWithDefaults instantiates a new PartnerBillingOverview object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPartner

`func (o *PartnerBillingOverview) GetPartner() PartnerBillingOverviewPartner`

GetPartner returns the Partner field if non-nil, zero value otherwise.

### GetPartnerOk

`func (o *PartnerBillingOverview) GetPartnerOk() (*PartnerBillingOverviewPartner, bool)`

GetPartnerOk returns a tuple with the Partner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartner

`func (o *PartnerBillingOverview) SetPartner(v PartnerBillingOverviewPartner)`

SetPartner sets Partner field to given value.


### GetOperationalCredits

`func (o *PartnerBillingOverview) GetOperationalCredits() PartnerBillingOverviewOperationalCredits`

GetOperationalCredits returns the OperationalCredits field if non-nil, zero value otherwise.

### GetOperationalCreditsOk

`func (o *PartnerBillingOverview) GetOperationalCreditsOk() (*PartnerBillingOverviewOperationalCredits, bool)`

GetOperationalCreditsOk returns a tuple with the OperationalCredits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperationalCredits

`func (o *PartnerBillingOverview) SetOperationalCredits(v PartnerBillingOverviewOperationalCredits)`

SetOperationalCredits sets OperationalCredits field to given value.


### GetPartnerCustomization

`func (o *PartnerBillingOverview) GetPartnerCustomization() PartnerCustomization`

GetPartnerCustomization returns the PartnerCustomization field if non-nil, zero value otherwise.

### GetPartnerCustomizationOk

`func (o *PartnerBillingOverview) GetPartnerCustomizationOk() (*PartnerCustomization, bool)`

GetPartnerCustomizationOk returns a tuple with the PartnerCustomization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartnerCustomization

`func (o *PartnerBillingOverview) SetPartnerCustomization(v PartnerCustomization)`

SetPartnerCustomization sets PartnerCustomization field to given value.

### HasPartnerCustomization

`func (o *PartnerBillingOverview) HasPartnerCustomization() bool`

HasPartnerCustomization returns a boolean if a field has been set.

### SetPartnerCustomizationNil

`func (o *PartnerBillingOverview) SetPartnerCustomizationNil(b bool)`

 SetPartnerCustomizationNil sets the value for PartnerCustomization to be an explicit nil

### UnsetPartnerCustomization
`func (o *PartnerBillingOverview) UnsetPartnerCustomization()`

UnsetPartnerCustomization ensures that no value is present for PartnerCustomization, not even an explicit nil
### GetBillingIntegration

`func (o *PartnerBillingOverview) GetBillingIntegration() PartnerBillingOverviewBillingIntegration`

GetBillingIntegration returns the BillingIntegration field if non-nil, zero value otherwise.

### GetBillingIntegrationOk

`func (o *PartnerBillingOverview) GetBillingIntegrationOk() (*PartnerBillingOverviewBillingIntegration, bool)`

GetBillingIntegrationOk returns a tuple with the BillingIntegration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingIntegration

`func (o *PartnerBillingOverview) SetBillingIntegration(v PartnerBillingOverviewBillingIntegration)`

SetBillingIntegration sets BillingIntegration field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


