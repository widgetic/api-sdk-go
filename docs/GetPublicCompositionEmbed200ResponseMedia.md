# GetPublicCompositionEmbed200ResponseMedia

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Optimize** | Pointer to **bool** | The owner&#39;s \&quot;Optimize images for the web\&quot; account setting (ON until they turn it off). When true the Embed SDK may ask Cloudflare for a right-sized, modern-format copy of each content image; when false it uses the originals. | [optional] 

## Methods

### NewGetPublicCompositionEmbed200ResponseMedia

`func NewGetPublicCompositionEmbed200ResponseMedia() *GetPublicCompositionEmbed200ResponseMedia`

NewGetPublicCompositionEmbed200ResponseMedia instantiates a new GetPublicCompositionEmbed200ResponseMedia object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetPublicCompositionEmbed200ResponseMediaWithDefaults

`func NewGetPublicCompositionEmbed200ResponseMediaWithDefaults() *GetPublicCompositionEmbed200ResponseMedia`

NewGetPublicCompositionEmbed200ResponseMediaWithDefaults instantiates a new GetPublicCompositionEmbed200ResponseMedia object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOptimize

`func (o *GetPublicCompositionEmbed200ResponseMedia) GetOptimize() bool`

GetOptimize returns the Optimize field if non-nil, zero value otherwise.

### GetOptimizeOk

`func (o *GetPublicCompositionEmbed200ResponseMedia) GetOptimizeOk() (*bool, bool)`

GetOptimizeOk returns a tuple with the Optimize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptimize

`func (o *GetPublicCompositionEmbed200ResponseMedia) SetOptimize(v bool)`

SetOptimize sets Optimize field to given value.

### HasOptimize

`func (o *GetPublicCompositionEmbed200ResponseMedia) HasOptimize() bool`

HasOptimize returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


