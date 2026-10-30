# PutBrandKitRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Tokens** | [**BrandKitTokens**](BrandKitTokens.md) |  | 
**FigmaSource** | Pointer to [**BrandKitFigmaSource**](BrandKitFigmaSource.md) |  | [optional] 
**ExpectedVersion** | Pointer to **int32** |  | [optional] 

## Methods

### NewPutBrandKitRequest

`func NewPutBrandKitRequest(tokens BrandKitTokens, ) *PutBrandKitRequest`

NewPutBrandKitRequest instantiates a new PutBrandKitRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPutBrandKitRequestWithDefaults

`func NewPutBrandKitRequestWithDefaults() *PutBrandKitRequest`

NewPutBrandKitRequestWithDefaults instantiates a new PutBrandKitRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTokens

`func (o *PutBrandKitRequest) GetTokens() BrandKitTokens`

GetTokens returns the Tokens field if non-nil, zero value otherwise.

### GetTokensOk

`func (o *PutBrandKitRequest) GetTokensOk() (*BrandKitTokens, bool)`

GetTokensOk returns a tuple with the Tokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokens

`func (o *PutBrandKitRequest) SetTokens(v BrandKitTokens)`

SetTokens sets Tokens field to given value.


### GetFigmaSource

`func (o *PutBrandKitRequest) GetFigmaSource() BrandKitFigmaSource`

GetFigmaSource returns the FigmaSource field if non-nil, zero value otherwise.

### GetFigmaSourceOk

`func (o *PutBrandKitRequest) GetFigmaSourceOk() (*BrandKitFigmaSource, bool)`

GetFigmaSourceOk returns a tuple with the FigmaSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFigmaSource

`func (o *PutBrandKitRequest) SetFigmaSource(v BrandKitFigmaSource)`

SetFigmaSource sets FigmaSource field to given value.

### HasFigmaSource

`func (o *PutBrandKitRequest) HasFigmaSource() bool`

HasFigmaSource returns a boolean if a field has been set.

### GetExpectedVersion

`func (o *PutBrandKitRequest) GetExpectedVersion() int32`

GetExpectedVersion returns the ExpectedVersion field if non-nil, zero value otherwise.

### GetExpectedVersionOk

`func (o *PutBrandKitRequest) GetExpectedVersionOk() (*int32, bool)`

GetExpectedVersionOk returns a tuple with the ExpectedVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedVersion

`func (o *PutBrandKitRequest) SetExpectedVersion(v int32)`

SetExpectedVersion sets ExpectedVersion field to given value.

### HasExpectedVersion

`func (o *PutBrandKitRequest) HasExpectedVersion() bool`

HasExpectedVersion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


