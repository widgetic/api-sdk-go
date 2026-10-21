# GetCompositionPreviewResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CompositionId** | Pointer to **string** | The composition this is the preview of | [optional] 
**WidgetId** | Pointer to **string** | The widget whose build is served | [optional] 
**Version** | Pointer to **int32** | The published version of that widget | [optional] 
**PreviewUrl** | Pointer to **string** | The page to load in a frame | [optional] 

## Methods

### NewGetCompositionPreviewResponseData

`func NewGetCompositionPreviewResponseData() *GetCompositionPreviewResponseData`

NewGetCompositionPreviewResponseData instantiates a new GetCompositionPreviewResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetCompositionPreviewResponseDataWithDefaults

`func NewGetCompositionPreviewResponseDataWithDefaults() *GetCompositionPreviewResponseData`

NewGetCompositionPreviewResponseDataWithDefaults instantiates a new GetCompositionPreviewResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompositionId

`func (o *GetCompositionPreviewResponseData) GetCompositionId() string`

GetCompositionId returns the CompositionId field if non-nil, zero value otherwise.

### GetCompositionIdOk

`func (o *GetCompositionPreviewResponseData) GetCompositionIdOk() (*string, bool)`

GetCompositionIdOk returns a tuple with the CompositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompositionId

`func (o *GetCompositionPreviewResponseData) SetCompositionId(v string)`

SetCompositionId sets CompositionId field to given value.

### HasCompositionId

`func (o *GetCompositionPreviewResponseData) HasCompositionId() bool`

HasCompositionId returns a boolean if a field has been set.

### GetWidgetId

`func (o *GetCompositionPreviewResponseData) GetWidgetId() string`

GetWidgetId returns the WidgetId field if non-nil, zero value otherwise.

### GetWidgetIdOk

`func (o *GetCompositionPreviewResponseData) GetWidgetIdOk() (*string, bool)`

GetWidgetIdOk returns a tuple with the WidgetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidgetId

`func (o *GetCompositionPreviewResponseData) SetWidgetId(v string)`

SetWidgetId sets WidgetId field to given value.

### HasWidgetId

`func (o *GetCompositionPreviewResponseData) HasWidgetId() bool`

HasWidgetId returns a boolean if a field has been set.

### GetVersion

`func (o *GetCompositionPreviewResponseData) GetVersion() int32`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *GetCompositionPreviewResponseData) GetVersionOk() (*int32, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *GetCompositionPreviewResponseData) SetVersion(v int32)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *GetCompositionPreviewResponseData) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### GetPreviewUrl

`func (o *GetCompositionPreviewResponseData) GetPreviewUrl() string`

GetPreviewUrl returns the PreviewUrl field if non-nil, zero value otherwise.

### GetPreviewUrlOk

`func (o *GetCompositionPreviewResponseData) GetPreviewUrlOk() (*string, bool)`

GetPreviewUrlOk returns a tuple with the PreviewUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewUrl

`func (o *GetCompositionPreviewResponseData) SetPreviewUrl(v string)`

SetPreviewUrl sets PreviewUrl field to given value.

### HasPreviewUrl

`func (o *GetCompositionPreviewResponseData) HasPreviewUrl() bool`

HasPreviewUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


