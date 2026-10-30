# BrandKitTokens

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Colors** | [**[]BrandColor**](BrandColor.md) |  | 
**Fonts** | [**BrandKitTokensFonts**](BrandKitTokensFonts.md) |  | 
**Spacing** | [**BrandSpacing**](BrandSpacing.md) |  | 
**Instructions** | Pointer to **string** | The kit owner&#39;s own style notes, taken into account in every widget made with the kit, for example \&quot;Use the dark color as the background always and the light color for titles\&quot;. They are about how a widget looks and never about what it holds, and what a request names itself wins over them. Left out, Widgetic&#39;s default note applies (\&quot;Widget backgrounds to be white whenever possible.\&quot;); an empty string means none. | [optional] 

## Methods

### NewBrandKitTokens

`func NewBrandKitTokens(colors []BrandColor, fonts BrandKitTokensFonts, spacing BrandSpacing, ) *BrandKitTokens`

NewBrandKitTokens instantiates a new BrandKitTokens object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBrandKitTokensWithDefaults

`func NewBrandKitTokensWithDefaults() *BrandKitTokens`

NewBrandKitTokensWithDefaults instantiates a new BrandKitTokens object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetColors

`func (o *BrandKitTokens) GetColors() []BrandColor`

GetColors returns the Colors field if non-nil, zero value otherwise.

### GetColorsOk

`func (o *BrandKitTokens) GetColorsOk() (*[]BrandColor, bool)`

GetColorsOk returns a tuple with the Colors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColors

`func (o *BrandKitTokens) SetColors(v []BrandColor)`

SetColors sets Colors field to given value.


### GetFonts

`func (o *BrandKitTokens) GetFonts() BrandKitTokensFonts`

GetFonts returns the Fonts field if non-nil, zero value otherwise.

### GetFontsOk

`func (o *BrandKitTokens) GetFontsOk() (*BrandKitTokensFonts, bool)`

GetFontsOk returns a tuple with the Fonts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFonts

`func (o *BrandKitTokens) SetFonts(v BrandKitTokensFonts)`

SetFonts sets Fonts field to given value.


### GetSpacing

`func (o *BrandKitTokens) GetSpacing() BrandSpacing`

GetSpacing returns the Spacing field if non-nil, zero value otherwise.

### GetSpacingOk

`func (o *BrandKitTokens) GetSpacingOk() (*BrandSpacing, bool)`

GetSpacingOk returns a tuple with the Spacing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpacing

`func (o *BrandKitTokens) SetSpacing(v BrandSpacing)`

SetSpacing sets Spacing field to given value.


### GetInstructions

`func (o *BrandKitTokens) GetInstructions() string`

GetInstructions returns the Instructions field if non-nil, zero value otherwise.

### GetInstructionsOk

`func (o *BrandKitTokens) GetInstructionsOk() (*string, bool)`

GetInstructionsOk returns a tuple with the Instructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstructions

`func (o *BrandKitTokens) SetInstructions(v string)`

SetInstructions sets Instructions field to given value.

### HasInstructions

`func (o *BrandKitTokens) HasInstructions() bool`

HasInstructions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


