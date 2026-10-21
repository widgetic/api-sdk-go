# GetPublicCompositionEmbed200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CompositionId** | Pointer to **string** |  | [optional] 
**WidgetId** | Pointer to **string** |  | [optional] 
**Version** | Pointer to **int32** |  | [optional] 
**WidgetVersion** | Pointer to **int32** | Published widget version on the CDN artifact this composition uses. | [optional] 
**PlayerVersion** | Pointer to **int32** | Version of the player: the gateway frame wrapper that shows the widget, and the host bridge it speaks with the embedding page and the widget (currently 4). Raised when the messages between page, frame, and widget change in a way a widget could notice, such as a new &#x60;widgetic:host&#x60; field or a new forwarded event (2 added &#x60;entries&#x60;, 3 added &#x60;adapters&#x60;, 4 added &#x60;entries.writeToken&#x60;). It is not &#x60;widgetVersion&#x60; (the version of the published widget) and not the &#x60;version&#x60; inside a &#x60;widgetic:host&#x60; message. | [optional] 
**DataSource** | Pointer to [**NullableGetPublicCompositionEmbed200ResponseDataSource**](GetPublicCompositionEmbed200ResponseDataSource.md) |  | [optional] 
**EmbedUrl** | Pointer to **string** |  | [optional] 
**EntryWriteToken** | Pointer to **string** | Signed per-composition write token for &#x60;POST /embed/compositions/{compositionId}/entries/{table}&#x60;, also handed to the widget inside &#x60;widgetic:host&#x60; as &#x60;entries.writeToken&#x60;. | [optional] 
**Width** | Pointer to **int32** |  | [optional] 
**Height** | Pointer to **int32** |  | [optional] 
**Design** | Pointer to **map[string]interface{}** |  | [optional] 
**Content** | Pointer to **map[string]interface{}** |  | [optional] 
**ContentItems** | Pointer to **[]map[string]interface{}** |  | [optional] 
**IframeAllow** | Pointer to **string** | The browser features the widget needs the iframe that shows it to be allowed to use, as the value of that iframe&#39;s &#x60;allow&#x60; attribute (for example &#x60;camera; microphone&#x60;; the words are &#x60;camera&#x60;, &#x60;display-capture&#x60; and &#x60;microphone&#x60;). Present only for a widget that uses a module that needs one, and absent for every other widget. A page that embeds the frame itself copies it onto its own iframe (&#x60;allow&#x3D;\&quot;...\&quot;&#x60;); a page that does not leaves the widget to say, in its own words, that the feature is blocked there. The frame wrapper already passes it on to the iframe it holds. | [optional] 
**Direct** | Pointer to [**NullableGetPublicCompositionEmbed200ResponseDirect**](GetPublicCompositionEmbed200ResponseDirect.md) |  | [optional] 

## Methods

### NewGetPublicCompositionEmbed200Response

`func NewGetPublicCompositionEmbed200Response() *GetPublicCompositionEmbed200Response`

NewGetPublicCompositionEmbed200Response instantiates a new GetPublicCompositionEmbed200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetPublicCompositionEmbed200ResponseWithDefaults

`func NewGetPublicCompositionEmbed200ResponseWithDefaults() *GetPublicCompositionEmbed200Response`

NewGetPublicCompositionEmbed200ResponseWithDefaults instantiates a new GetPublicCompositionEmbed200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompositionId

`func (o *GetPublicCompositionEmbed200Response) GetCompositionId() string`

GetCompositionId returns the CompositionId field if non-nil, zero value otherwise.

### GetCompositionIdOk

`func (o *GetPublicCompositionEmbed200Response) GetCompositionIdOk() (*string, bool)`

GetCompositionIdOk returns a tuple with the CompositionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompositionId

`func (o *GetPublicCompositionEmbed200Response) SetCompositionId(v string)`

SetCompositionId sets CompositionId field to given value.

### HasCompositionId

`func (o *GetPublicCompositionEmbed200Response) HasCompositionId() bool`

HasCompositionId returns a boolean if a field has been set.

### GetWidgetId

`func (o *GetPublicCompositionEmbed200Response) GetWidgetId() string`

GetWidgetId returns the WidgetId field if non-nil, zero value otherwise.

### GetWidgetIdOk

`func (o *GetPublicCompositionEmbed200Response) GetWidgetIdOk() (*string, bool)`

GetWidgetIdOk returns a tuple with the WidgetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidgetId

`func (o *GetPublicCompositionEmbed200Response) SetWidgetId(v string)`

SetWidgetId sets WidgetId field to given value.

### HasWidgetId

`func (o *GetPublicCompositionEmbed200Response) HasWidgetId() bool`

HasWidgetId returns a boolean if a field has been set.

### GetVersion

`func (o *GetPublicCompositionEmbed200Response) GetVersion() int32`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *GetPublicCompositionEmbed200Response) GetVersionOk() (*int32, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *GetPublicCompositionEmbed200Response) SetVersion(v int32)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *GetPublicCompositionEmbed200Response) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### GetWidgetVersion

`func (o *GetPublicCompositionEmbed200Response) GetWidgetVersion() int32`

GetWidgetVersion returns the WidgetVersion field if non-nil, zero value otherwise.

### GetWidgetVersionOk

`func (o *GetPublicCompositionEmbed200Response) GetWidgetVersionOk() (*int32, bool)`

GetWidgetVersionOk returns a tuple with the WidgetVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidgetVersion

`func (o *GetPublicCompositionEmbed200Response) SetWidgetVersion(v int32)`

SetWidgetVersion sets WidgetVersion field to given value.

### HasWidgetVersion

`func (o *GetPublicCompositionEmbed200Response) HasWidgetVersion() bool`

HasWidgetVersion returns a boolean if a field has been set.

### GetPlayerVersion

`func (o *GetPublicCompositionEmbed200Response) GetPlayerVersion() int32`

GetPlayerVersion returns the PlayerVersion field if non-nil, zero value otherwise.

### GetPlayerVersionOk

`func (o *GetPublicCompositionEmbed200Response) GetPlayerVersionOk() (*int32, bool)`

GetPlayerVersionOk returns a tuple with the PlayerVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlayerVersion

`func (o *GetPublicCompositionEmbed200Response) SetPlayerVersion(v int32)`

SetPlayerVersion sets PlayerVersion field to given value.

### HasPlayerVersion

`func (o *GetPublicCompositionEmbed200Response) HasPlayerVersion() bool`

HasPlayerVersion returns a boolean if a field has been set.

### GetDataSource

`func (o *GetPublicCompositionEmbed200Response) GetDataSource() GetPublicCompositionEmbed200ResponseDataSource`

GetDataSource returns the DataSource field if non-nil, zero value otherwise.

### GetDataSourceOk

`func (o *GetPublicCompositionEmbed200Response) GetDataSourceOk() (*GetPublicCompositionEmbed200ResponseDataSource, bool)`

GetDataSourceOk returns a tuple with the DataSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataSource

`func (o *GetPublicCompositionEmbed200Response) SetDataSource(v GetPublicCompositionEmbed200ResponseDataSource)`

SetDataSource sets DataSource field to given value.

### HasDataSource

`func (o *GetPublicCompositionEmbed200Response) HasDataSource() bool`

HasDataSource returns a boolean if a field has been set.

### SetDataSourceNil

`func (o *GetPublicCompositionEmbed200Response) SetDataSourceNil(b bool)`

 SetDataSourceNil sets the value for DataSource to be an explicit nil

### UnsetDataSource
`func (o *GetPublicCompositionEmbed200Response) UnsetDataSource()`

UnsetDataSource ensures that no value is present for DataSource, not even an explicit nil
### GetEmbedUrl

`func (o *GetPublicCompositionEmbed200Response) GetEmbedUrl() string`

GetEmbedUrl returns the EmbedUrl field if non-nil, zero value otherwise.

### GetEmbedUrlOk

`func (o *GetPublicCompositionEmbed200Response) GetEmbedUrlOk() (*string, bool)`

GetEmbedUrlOk returns a tuple with the EmbedUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmbedUrl

`func (o *GetPublicCompositionEmbed200Response) SetEmbedUrl(v string)`

SetEmbedUrl sets EmbedUrl field to given value.

### HasEmbedUrl

`func (o *GetPublicCompositionEmbed200Response) HasEmbedUrl() bool`

HasEmbedUrl returns a boolean if a field has been set.

### GetEntryWriteToken

`func (o *GetPublicCompositionEmbed200Response) GetEntryWriteToken() string`

GetEntryWriteToken returns the EntryWriteToken field if non-nil, zero value otherwise.

### GetEntryWriteTokenOk

`func (o *GetPublicCompositionEmbed200Response) GetEntryWriteTokenOk() (*string, bool)`

GetEntryWriteTokenOk returns a tuple with the EntryWriteToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntryWriteToken

`func (o *GetPublicCompositionEmbed200Response) SetEntryWriteToken(v string)`

SetEntryWriteToken sets EntryWriteToken field to given value.

### HasEntryWriteToken

`func (o *GetPublicCompositionEmbed200Response) HasEntryWriteToken() bool`

HasEntryWriteToken returns a boolean if a field has been set.

### GetWidth

`func (o *GetPublicCompositionEmbed200Response) GetWidth() int32`

GetWidth returns the Width field if non-nil, zero value otherwise.

### GetWidthOk

`func (o *GetPublicCompositionEmbed200Response) GetWidthOk() (*int32, bool)`

GetWidthOk returns a tuple with the Width field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidth

`func (o *GetPublicCompositionEmbed200Response) SetWidth(v int32)`

SetWidth sets Width field to given value.

### HasWidth

`func (o *GetPublicCompositionEmbed200Response) HasWidth() bool`

HasWidth returns a boolean if a field has been set.

### GetHeight

`func (o *GetPublicCompositionEmbed200Response) GetHeight() int32`

GetHeight returns the Height field if non-nil, zero value otherwise.

### GetHeightOk

`func (o *GetPublicCompositionEmbed200Response) GetHeightOk() (*int32, bool)`

GetHeightOk returns a tuple with the Height field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeight

`func (o *GetPublicCompositionEmbed200Response) SetHeight(v int32)`

SetHeight sets Height field to given value.

### HasHeight

`func (o *GetPublicCompositionEmbed200Response) HasHeight() bool`

HasHeight returns a boolean if a field has been set.

### GetDesign

`func (o *GetPublicCompositionEmbed200Response) GetDesign() map[string]interface{}`

GetDesign returns the Design field if non-nil, zero value otherwise.

### GetDesignOk

`func (o *GetPublicCompositionEmbed200Response) GetDesignOk() (*map[string]interface{}, bool)`

GetDesignOk returns a tuple with the Design field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDesign

`func (o *GetPublicCompositionEmbed200Response) SetDesign(v map[string]interface{})`

SetDesign sets Design field to given value.

### HasDesign

`func (o *GetPublicCompositionEmbed200Response) HasDesign() bool`

HasDesign returns a boolean if a field has been set.

### GetContent

`func (o *GetPublicCompositionEmbed200Response) GetContent() map[string]interface{}`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *GetPublicCompositionEmbed200Response) GetContentOk() (*map[string]interface{}, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *GetPublicCompositionEmbed200Response) SetContent(v map[string]interface{})`

SetContent sets Content field to given value.

### HasContent

`func (o *GetPublicCompositionEmbed200Response) HasContent() bool`

HasContent returns a boolean if a field has been set.

### GetContentItems

`func (o *GetPublicCompositionEmbed200Response) GetContentItems() []map[string]interface{}`

GetContentItems returns the ContentItems field if non-nil, zero value otherwise.

### GetContentItemsOk

`func (o *GetPublicCompositionEmbed200Response) GetContentItemsOk() (*[]map[string]interface{}, bool)`

GetContentItemsOk returns a tuple with the ContentItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentItems

`func (o *GetPublicCompositionEmbed200Response) SetContentItems(v []map[string]interface{})`

SetContentItems sets ContentItems field to given value.

### HasContentItems

`func (o *GetPublicCompositionEmbed200Response) HasContentItems() bool`

HasContentItems returns a boolean if a field has been set.

### GetIframeAllow

`func (o *GetPublicCompositionEmbed200Response) GetIframeAllow() string`

GetIframeAllow returns the IframeAllow field if non-nil, zero value otherwise.

### GetIframeAllowOk

`func (o *GetPublicCompositionEmbed200Response) GetIframeAllowOk() (*string, bool)`

GetIframeAllowOk returns a tuple with the IframeAllow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIframeAllow

`func (o *GetPublicCompositionEmbed200Response) SetIframeAllow(v string)`

SetIframeAllow sets IframeAllow field to given value.

### HasIframeAllow

`func (o *GetPublicCompositionEmbed200Response) HasIframeAllow() bool`

HasIframeAllow returns a boolean if a field has been set.

### GetDirect

`func (o *GetPublicCompositionEmbed200Response) GetDirect() GetPublicCompositionEmbed200ResponseDirect`

GetDirect returns the Direct field if non-nil, zero value otherwise.

### GetDirectOk

`func (o *GetPublicCompositionEmbed200Response) GetDirectOk() (*GetPublicCompositionEmbed200ResponseDirect, bool)`

GetDirectOk returns a tuple with the Direct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirect

`func (o *GetPublicCompositionEmbed200Response) SetDirect(v GetPublicCompositionEmbed200ResponseDirect)`

SetDirect sets Direct field to given value.

### HasDirect

`func (o *GetPublicCompositionEmbed200Response) HasDirect() bool`

HasDirect returns a boolean if a field has been set.

### SetDirectNil

`func (o *GetPublicCompositionEmbed200Response) SetDirectNil(b bool)`

 SetDirectNil sets the value for Direct to be an explicit nil

### UnsetDirect
`func (o *GetPublicCompositionEmbed200Response) UnsetDirect()`

UnsetDirect ensures that no value is present for Direct, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


