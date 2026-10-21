# CompositionDataSource

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** | The https address as it was saved, after the checks (a public host, never loopback, link-local or a metadata address) | 
**RefreshSeconds** | **int32** | How often the widget reads the address again, in seconds | 

## Methods

### NewCompositionDataSource

`func NewCompositionDataSource(url string, refreshSeconds int32, ) *CompositionDataSource`

NewCompositionDataSource instantiates a new CompositionDataSource object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompositionDataSourceWithDefaults

`func NewCompositionDataSourceWithDefaults() *CompositionDataSource`

NewCompositionDataSourceWithDefaults instantiates a new CompositionDataSource object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *CompositionDataSource) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *CompositionDataSource) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *CompositionDataSource) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetRefreshSeconds

`func (o *CompositionDataSource) GetRefreshSeconds() int32`

GetRefreshSeconds returns the RefreshSeconds field if non-nil, zero value otherwise.

### GetRefreshSecondsOk

`func (o *CompositionDataSource) GetRefreshSecondsOk() (*int32, bool)`

GetRefreshSecondsOk returns a tuple with the RefreshSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefreshSeconds

`func (o *CompositionDataSource) SetRefreshSeconds(v int32)`

SetRefreshSeconds sets RefreshSeconds field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


