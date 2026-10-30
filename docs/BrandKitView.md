# BrandKitView

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Owner** | [**BrandKitViewOwner**](BrandKitViewOwner.md) |  | 
**IsDefault** | **bool** |  | 
**CanEdit** | **bool** |  | 
**Version** | **int32** |  | 
**Tokens** | [**BrandKitTokens**](BrandKitTokens.md) |  | 
**Assets** | [**[]BrandKitAssetView**](BrandKitAssetView.md) |  | 
**FigmaSource** | Pointer to [**BrandKitFigmaSource**](BrandKitFigmaSource.md) |  | [optional] 
**UpdatedAt** | Pointer to **NullableTime** |  | [optional] 
**UpdatedBy** | Pointer to **NullableString** |  | [optional] 
**Warnings** | Pointer to **[]string** | Things worth fixing in the saved colors, such as a text color that is hard to read on the background. The kit is saved either way. | [optional] 

## Methods

### NewBrandKitView

`func NewBrandKitView(owner BrandKitViewOwner, isDefault bool, canEdit bool, version int32, tokens BrandKitTokens, assets []BrandKitAssetView, ) *BrandKitView`

NewBrandKitView instantiates a new BrandKitView object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBrandKitViewWithDefaults

`func NewBrandKitViewWithDefaults() *BrandKitView`

NewBrandKitViewWithDefaults instantiates a new BrandKitView object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOwner

`func (o *BrandKitView) GetOwner() BrandKitViewOwner`

GetOwner returns the Owner field if non-nil, zero value otherwise.

### GetOwnerOk

`func (o *BrandKitView) GetOwnerOk() (*BrandKitViewOwner, bool)`

GetOwnerOk returns a tuple with the Owner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwner

`func (o *BrandKitView) SetOwner(v BrandKitViewOwner)`

SetOwner sets Owner field to given value.


### GetIsDefault

`func (o *BrandKitView) GetIsDefault() bool`

GetIsDefault returns the IsDefault field if non-nil, zero value otherwise.

### GetIsDefaultOk

`func (o *BrandKitView) GetIsDefaultOk() (*bool, bool)`

GetIsDefaultOk returns a tuple with the IsDefault field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDefault

`func (o *BrandKitView) SetIsDefault(v bool)`

SetIsDefault sets IsDefault field to given value.


### GetCanEdit

`func (o *BrandKitView) GetCanEdit() bool`

GetCanEdit returns the CanEdit field if non-nil, zero value otherwise.

### GetCanEditOk

`func (o *BrandKitView) GetCanEditOk() (*bool, bool)`

GetCanEditOk returns a tuple with the CanEdit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanEdit

`func (o *BrandKitView) SetCanEdit(v bool)`

SetCanEdit sets CanEdit field to given value.


### GetVersion

`func (o *BrandKitView) GetVersion() int32`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *BrandKitView) GetVersionOk() (*int32, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *BrandKitView) SetVersion(v int32)`

SetVersion sets Version field to given value.


### GetTokens

`func (o *BrandKitView) GetTokens() BrandKitTokens`

GetTokens returns the Tokens field if non-nil, zero value otherwise.

### GetTokensOk

`func (o *BrandKitView) GetTokensOk() (*BrandKitTokens, bool)`

GetTokensOk returns a tuple with the Tokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokens

`func (o *BrandKitView) SetTokens(v BrandKitTokens)`

SetTokens sets Tokens field to given value.


### GetAssets

`func (o *BrandKitView) GetAssets() []BrandKitAssetView`

GetAssets returns the Assets field if non-nil, zero value otherwise.

### GetAssetsOk

`func (o *BrandKitView) GetAssetsOk() (*[]BrandKitAssetView, bool)`

GetAssetsOk returns a tuple with the Assets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssets

`func (o *BrandKitView) SetAssets(v []BrandKitAssetView)`

SetAssets sets Assets field to given value.


### GetFigmaSource

`func (o *BrandKitView) GetFigmaSource() BrandKitFigmaSource`

GetFigmaSource returns the FigmaSource field if non-nil, zero value otherwise.

### GetFigmaSourceOk

`func (o *BrandKitView) GetFigmaSourceOk() (*BrandKitFigmaSource, bool)`

GetFigmaSourceOk returns a tuple with the FigmaSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFigmaSource

`func (o *BrandKitView) SetFigmaSource(v BrandKitFigmaSource)`

SetFigmaSource sets FigmaSource field to given value.

### HasFigmaSource

`func (o *BrandKitView) HasFigmaSource() bool`

HasFigmaSource returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *BrandKitView) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *BrandKitView) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *BrandKitView) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *BrandKitView) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *BrandKitView) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *BrandKitView) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil
### GetUpdatedBy

`func (o *BrandKitView) GetUpdatedBy() string`

GetUpdatedBy returns the UpdatedBy field if non-nil, zero value otherwise.

### GetUpdatedByOk

`func (o *BrandKitView) GetUpdatedByOk() (*string, bool)`

GetUpdatedByOk returns a tuple with the UpdatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedBy

`func (o *BrandKitView) SetUpdatedBy(v string)`

SetUpdatedBy sets UpdatedBy field to given value.

### HasUpdatedBy

`func (o *BrandKitView) HasUpdatedBy() bool`

HasUpdatedBy returns a boolean if a field has been set.

### SetUpdatedByNil

`func (o *BrandKitView) SetUpdatedByNil(b bool)`

 SetUpdatedByNil sets the value for UpdatedBy to be an explicit nil

### UnsetUpdatedBy
`func (o *BrandKitView) UnsetUpdatedBy()`

UnsetUpdatedBy ensures that no value is present for UpdatedBy, not even an explicit nil
### GetWarnings

`func (o *BrandKitView) GetWarnings() []string`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *BrandKitView) GetWarningsOk() (*[]string, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *BrandKitView) SetWarnings(v []string)`

SetWarnings sets Warnings field to given value.

### HasWarnings

`func (o *BrandKitView) HasWarnings() bool`

HasWarnings returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


