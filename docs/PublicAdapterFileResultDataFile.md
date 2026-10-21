# PublicAdapterFileResultDataFile

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** | Where the stored file is. Always an https address. | 
**Name** | **string** | The name it is stored under. It is not the name the visitor gave, which is only kept as far as it is plain text. | 
**Size** | **int32** | Its size in bytes. | 
**Type** | **string** | Its media type, as proved from its bytes. | 
**Width** | **NullableInt32** | The width in pixels of a picture, otherwise null. | 
**Height** | **NullableInt32** | The height in pixels of a picture, otherwise null. | 

## Methods

### NewPublicAdapterFileResultDataFile

`func NewPublicAdapterFileResultDataFile(url string, name string, size int32, type_ string, width NullableInt32, height NullableInt32, ) *PublicAdapterFileResultDataFile`

NewPublicAdapterFileResultDataFile instantiates a new PublicAdapterFileResultDataFile object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublicAdapterFileResultDataFileWithDefaults

`func NewPublicAdapterFileResultDataFileWithDefaults() *PublicAdapterFileResultDataFile`

NewPublicAdapterFileResultDataFileWithDefaults instantiates a new PublicAdapterFileResultDataFile object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *PublicAdapterFileResultDataFile) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *PublicAdapterFileResultDataFile) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *PublicAdapterFileResultDataFile) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetName

`func (o *PublicAdapterFileResultDataFile) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PublicAdapterFileResultDataFile) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PublicAdapterFileResultDataFile) SetName(v string)`

SetName sets Name field to given value.


### GetSize

`func (o *PublicAdapterFileResultDataFile) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *PublicAdapterFileResultDataFile) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *PublicAdapterFileResultDataFile) SetSize(v int32)`

SetSize sets Size field to given value.


### GetType

`func (o *PublicAdapterFileResultDataFile) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PublicAdapterFileResultDataFile) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PublicAdapterFileResultDataFile) SetType(v string)`

SetType sets Type field to given value.


### GetWidth

`func (o *PublicAdapterFileResultDataFile) GetWidth() int32`

GetWidth returns the Width field if non-nil, zero value otherwise.

### GetWidthOk

`func (o *PublicAdapterFileResultDataFile) GetWidthOk() (*int32, bool)`

GetWidthOk returns a tuple with the Width field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidth

`func (o *PublicAdapterFileResultDataFile) SetWidth(v int32)`

SetWidth sets Width field to given value.


### SetWidthNil

`func (o *PublicAdapterFileResultDataFile) SetWidthNil(b bool)`

 SetWidthNil sets the value for Width to be an explicit nil

### UnsetWidth
`func (o *PublicAdapterFileResultDataFile) UnsetWidth()`

UnsetWidth ensures that no value is present for Width, not even an explicit nil
### GetHeight

`func (o *PublicAdapterFileResultDataFile) GetHeight() int32`

GetHeight returns the Height field if non-nil, zero value otherwise.

### GetHeightOk

`func (o *PublicAdapterFileResultDataFile) GetHeightOk() (*int32, bool)`

GetHeightOk returns a tuple with the Height field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeight

`func (o *PublicAdapterFileResultDataFile) SetHeight(v int32)`

SetHeight sets Height field to given value.


### SetHeightNil

`func (o *PublicAdapterFileResultDataFile) SetHeightNil(b bool)`

 SetHeightNil sets the value for Height to be an explicit nil

### UnsetHeight
`func (o *PublicAdapterFileResultDataFile) UnsetHeight()`

UnsetHeight ensures that no value is present for Height, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


