# PatchBrandKitRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Colors** | Pointer to [**[]BrandColor**](BrandColor.md) | The whole list of colors (it replaces the saved list). | [optional] 
**Fonts** | Pointer to [**PatchBrandKitRequestFonts**](PatchBrandKitRequestFonts.md) |  | [optional] 
**Spacing** | Pointer to [**PatchBrandKitRequestSpacing**](PatchBrandKitRequestSpacing.md) |  | [optional] 
**CornerRadius** | Pointer to **int32** | One corner radius in pixels for the whole kit; the small, medium and large radii are made from it. 0 gives square corners. A radius step sent in &#x60;spacing&#x60; wins over the one made from this value. | [optional] 
**Instructions** | Pointer to **string** | The kit owner&#39;s style notes (see &#x60;tokens.instructions&#x60;). An empty string removes them. | [optional] 
**ExpectedVersion** | Pointer to **int32** | Refuse the change with a 409 when the kit was saved again since this version was read. | [optional] 

## Methods

### NewPatchBrandKitRequest

`func NewPatchBrandKitRequest() *PatchBrandKitRequest`

NewPatchBrandKitRequest instantiates a new PatchBrandKitRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPatchBrandKitRequestWithDefaults

`func NewPatchBrandKitRequestWithDefaults() *PatchBrandKitRequest`

NewPatchBrandKitRequestWithDefaults instantiates a new PatchBrandKitRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetColors

`func (o *PatchBrandKitRequest) GetColors() []BrandColor`

GetColors returns the Colors field if non-nil, zero value otherwise.

### GetColorsOk

`func (o *PatchBrandKitRequest) GetColorsOk() (*[]BrandColor, bool)`

GetColorsOk returns a tuple with the Colors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColors

`func (o *PatchBrandKitRequest) SetColors(v []BrandColor)`

SetColors sets Colors field to given value.

### HasColors

`func (o *PatchBrandKitRequest) HasColors() bool`

HasColors returns a boolean if a field has been set.

### GetFonts

`func (o *PatchBrandKitRequest) GetFonts() PatchBrandKitRequestFonts`

GetFonts returns the Fonts field if non-nil, zero value otherwise.

### GetFontsOk

`func (o *PatchBrandKitRequest) GetFontsOk() (*PatchBrandKitRequestFonts, bool)`

GetFontsOk returns a tuple with the Fonts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFonts

`func (o *PatchBrandKitRequest) SetFonts(v PatchBrandKitRequestFonts)`

SetFonts sets Fonts field to given value.

### HasFonts

`func (o *PatchBrandKitRequest) HasFonts() bool`

HasFonts returns a boolean if a field has been set.

### GetSpacing

`func (o *PatchBrandKitRequest) GetSpacing() PatchBrandKitRequestSpacing`

GetSpacing returns the Spacing field if non-nil, zero value otherwise.

### GetSpacingOk

`func (o *PatchBrandKitRequest) GetSpacingOk() (*PatchBrandKitRequestSpacing, bool)`

GetSpacingOk returns a tuple with the Spacing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpacing

`func (o *PatchBrandKitRequest) SetSpacing(v PatchBrandKitRequestSpacing)`

SetSpacing sets Spacing field to given value.

### HasSpacing

`func (o *PatchBrandKitRequest) HasSpacing() bool`

HasSpacing returns a boolean if a field has been set.

### GetCornerRadius

`func (o *PatchBrandKitRequest) GetCornerRadius() int32`

GetCornerRadius returns the CornerRadius field if non-nil, zero value otherwise.

### GetCornerRadiusOk

`func (o *PatchBrandKitRequest) GetCornerRadiusOk() (*int32, bool)`

GetCornerRadiusOk returns a tuple with the CornerRadius field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCornerRadius

`func (o *PatchBrandKitRequest) SetCornerRadius(v int32)`

SetCornerRadius sets CornerRadius field to given value.

### HasCornerRadius

`func (o *PatchBrandKitRequest) HasCornerRadius() bool`

HasCornerRadius returns a boolean if a field has been set.

### GetInstructions

`func (o *PatchBrandKitRequest) GetInstructions() string`

GetInstructions returns the Instructions field if non-nil, zero value otherwise.

### GetInstructionsOk

`func (o *PatchBrandKitRequest) GetInstructionsOk() (*string, bool)`

GetInstructionsOk returns a tuple with the Instructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstructions

`func (o *PatchBrandKitRequest) SetInstructions(v string)`

SetInstructions sets Instructions field to given value.

### HasInstructions

`func (o *PatchBrandKitRequest) HasInstructions() bool`

HasInstructions returns a boolean if a field has been set.

### GetExpectedVersion

`func (o *PatchBrandKitRequest) GetExpectedVersion() int32`

GetExpectedVersion returns the ExpectedVersion field if non-nil, zero value otherwise.

### GetExpectedVersionOk

`func (o *PatchBrandKitRequest) GetExpectedVersionOk() (*int32, bool)`

GetExpectedVersionOk returns a tuple with the ExpectedVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedVersion

`func (o *PatchBrandKitRequest) SetExpectedVersion(v int32)`

SetExpectedVersion sets ExpectedVersion field to given value.

### HasExpectedVersion

`func (o *PatchBrandKitRequest) HasExpectedVersion() bool`

HasExpectedVersion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


