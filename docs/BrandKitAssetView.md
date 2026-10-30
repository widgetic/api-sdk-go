# BrandKitAssetView

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Kind** | **string** |  | 
**Name** | **string** |  | 
**CreatedAt** | **time.Time** |  | 
**Family** | Pointer to **string** |  | [optional] 
**Weight** | Pointer to **int32** |  | [optional] 
**Style** | Pointer to **string** |  | [optional] 
**Format** | Pointer to **string** |  | [optional] 
**Bytes** | Pointer to **int32** |  | [optional] 
**Url** | Pointer to **NullableString** |  | [optional] 
**Slug** | Pointer to **string** |  | [optional] 
**ExportName** | Pointer to **string** |  | [optional] 
**Svg** | Pointer to **string** |  | [optional] 

## Methods

### NewBrandKitAssetView

`func NewBrandKitAssetView(id string, kind string, name string, createdAt time.Time, ) *BrandKitAssetView`

NewBrandKitAssetView instantiates a new BrandKitAssetView object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBrandKitAssetViewWithDefaults

`func NewBrandKitAssetViewWithDefaults() *BrandKitAssetView`

NewBrandKitAssetViewWithDefaults instantiates a new BrandKitAssetView object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *BrandKitAssetView) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *BrandKitAssetView) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *BrandKitAssetView) SetId(v string)`

SetId sets Id field to given value.


### GetKind

`func (o *BrandKitAssetView) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *BrandKitAssetView) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *BrandKitAssetView) SetKind(v string)`

SetKind sets Kind field to given value.


### GetName

`func (o *BrandKitAssetView) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *BrandKitAssetView) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *BrandKitAssetView) SetName(v string)`

SetName sets Name field to given value.


### GetCreatedAt

`func (o *BrandKitAssetView) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *BrandKitAssetView) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *BrandKitAssetView) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetFamily

`func (o *BrandKitAssetView) GetFamily() string`

GetFamily returns the Family field if non-nil, zero value otherwise.

### GetFamilyOk

`func (o *BrandKitAssetView) GetFamilyOk() (*string, bool)`

GetFamilyOk returns a tuple with the Family field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFamily

`func (o *BrandKitAssetView) SetFamily(v string)`

SetFamily sets Family field to given value.

### HasFamily

`func (o *BrandKitAssetView) HasFamily() bool`

HasFamily returns a boolean if a field has been set.

### GetWeight

`func (o *BrandKitAssetView) GetWeight() int32`

GetWeight returns the Weight field if non-nil, zero value otherwise.

### GetWeightOk

`func (o *BrandKitAssetView) GetWeightOk() (*int32, bool)`

GetWeightOk returns a tuple with the Weight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeight

`func (o *BrandKitAssetView) SetWeight(v int32)`

SetWeight sets Weight field to given value.

### HasWeight

`func (o *BrandKitAssetView) HasWeight() bool`

HasWeight returns a boolean if a field has been set.

### GetStyle

`func (o *BrandKitAssetView) GetStyle() string`

GetStyle returns the Style field if non-nil, zero value otherwise.

### GetStyleOk

`func (o *BrandKitAssetView) GetStyleOk() (*string, bool)`

GetStyleOk returns a tuple with the Style field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStyle

`func (o *BrandKitAssetView) SetStyle(v string)`

SetStyle sets Style field to given value.

### HasStyle

`func (o *BrandKitAssetView) HasStyle() bool`

HasStyle returns a boolean if a field has been set.

### GetFormat

`func (o *BrandKitAssetView) GetFormat() string`

GetFormat returns the Format field if non-nil, zero value otherwise.

### GetFormatOk

`func (o *BrandKitAssetView) GetFormatOk() (*string, bool)`

GetFormatOk returns a tuple with the Format field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormat

`func (o *BrandKitAssetView) SetFormat(v string)`

SetFormat sets Format field to given value.

### HasFormat

`func (o *BrandKitAssetView) HasFormat() bool`

HasFormat returns a boolean if a field has been set.

### GetBytes

`func (o *BrandKitAssetView) GetBytes() int32`

GetBytes returns the Bytes field if non-nil, zero value otherwise.

### GetBytesOk

`func (o *BrandKitAssetView) GetBytesOk() (*int32, bool)`

GetBytesOk returns a tuple with the Bytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBytes

`func (o *BrandKitAssetView) SetBytes(v int32)`

SetBytes sets Bytes field to given value.

### HasBytes

`func (o *BrandKitAssetView) HasBytes() bool`

HasBytes returns a boolean if a field has been set.

### GetUrl

`func (o *BrandKitAssetView) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *BrandKitAssetView) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *BrandKitAssetView) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *BrandKitAssetView) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### SetUrlNil

`func (o *BrandKitAssetView) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *BrandKitAssetView) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil
### GetSlug

`func (o *BrandKitAssetView) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *BrandKitAssetView) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *BrandKitAssetView) SetSlug(v string)`

SetSlug sets Slug field to given value.

### HasSlug

`func (o *BrandKitAssetView) HasSlug() bool`

HasSlug returns a boolean if a field has been set.

### GetExportName

`func (o *BrandKitAssetView) GetExportName() string`

GetExportName returns the ExportName field if non-nil, zero value otherwise.

### GetExportNameOk

`func (o *BrandKitAssetView) GetExportNameOk() (*string, bool)`

GetExportNameOk returns a tuple with the ExportName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExportName

`func (o *BrandKitAssetView) SetExportName(v string)`

SetExportName sets ExportName field to given value.

### HasExportName

`func (o *BrandKitAssetView) HasExportName() bool`

HasExportName returns a boolean if a field has been set.

### GetSvg

`func (o *BrandKitAssetView) GetSvg() string`

GetSvg returns the Svg field if non-nil, zero value otherwise.

### GetSvgOk

`func (o *BrandKitAssetView) GetSvgOk() (*string, bool)`

GetSvgOk returns a tuple with the Svg field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSvg

`func (o *BrandKitAssetView) SetSvg(v string)`

SetSvg sets Svg field to given value.

### HasSvg

`func (o *BrandKitAssetView) HasSvg() bool`

HasSvg returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


