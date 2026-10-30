# BrandFont

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Family** | **string** |  | 
**Source** | **string** |  | 
**Weight** | Pointer to **int32** |  | [optional] 
**SizeMax** | Pointer to **int32** |  | [optional] 

## Methods

### NewBrandFont

`func NewBrandFont(family string, source string, ) *BrandFont`

NewBrandFont instantiates a new BrandFont object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBrandFontWithDefaults

`func NewBrandFontWithDefaults() *BrandFont`

NewBrandFontWithDefaults instantiates a new BrandFont object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFamily

`func (o *BrandFont) GetFamily() string`

GetFamily returns the Family field if non-nil, zero value otherwise.

### GetFamilyOk

`func (o *BrandFont) GetFamilyOk() (*string, bool)`

GetFamilyOk returns a tuple with the Family field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFamily

`func (o *BrandFont) SetFamily(v string)`

SetFamily sets Family field to given value.


### GetSource

`func (o *BrandFont) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *BrandFont) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *BrandFont) SetSource(v string)`

SetSource sets Source field to given value.


### GetWeight

`func (o *BrandFont) GetWeight() int32`

GetWeight returns the Weight field if non-nil, zero value otherwise.

### GetWeightOk

`func (o *BrandFont) GetWeightOk() (*int32, bool)`

GetWeightOk returns a tuple with the Weight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeight

`func (o *BrandFont) SetWeight(v int32)`

SetWeight sets Weight field to given value.

### HasWeight

`func (o *BrandFont) HasWeight() bool`

HasWeight returns a boolean if a field has been set.

### GetSizeMax

`func (o *BrandFont) GetSizeMax() int32`

GetSizeMax returns the SizeMax field if non-nil, zero value otherwise.

### GetSizeMaxOk

`func (o *BrandFont) GetSizeMaxOk() (*int32, bool)`

GetSizeMaxOk returns a tuple with the SizeMax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSizeMax

`func (o *BrandFont) SetSizeMax(v int32)`

SetSizeMax sets SizeMax field to given value.

### HasSizeMax

`func (o *BrandFont) HasSizeMax() bool`

HasSizeMax returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


