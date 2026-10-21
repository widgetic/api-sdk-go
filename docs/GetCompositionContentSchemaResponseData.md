# GetCompositionContentSchemaResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Version** | Pointer to **string** |  | [optional] 
**WidgetType** | Pointer to **string** |  | [optional] 
**Type** | Pointer to **string** |  | [optional] 
**Content** | Pointer to **map[string]interface{}** | Widget-wide fields; enriched properties may include &#x60;role&#x60; and &#x60;roleSource&#x60;. AI-built widgets keep their widget-wide fields in &#x60;genericContent&#x60;, as a list of properties, instead | [optional] 
**ContentItems** | Pointer to **map[string]interface{}** | Repeating list schema; list-level &#x60;role&#x60; is &#x60;list&#x60;; item fields use semantic roles. AI-built widgets store an array of default items instead, each repeating the same fields with their roles, and no list-level &#x60;role&#x60; | [optional] 
**Metadata** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewGetCompositionContentSchemaResponseData

`func NewGetCompositionContentSchemaResponseData() *GetCompositionContentSchemaResponseData`

NewGetCompositionContentSchemaResponseData instantiates a new GetCompositionContentSchemaResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetCompositionContentSchemaResponseDataWithDefaults

`func NewGetCompositionContentSchemaResponseDataWithDefaults() *GetCompositionContentSchemaResponseData`

NewGetCompositionContentSchemaResponseDataWithDefaults instantiates a new GetCompositionContentSchemaResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVersion

`func (o *GetCompositionContentSchemaResponseData) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *GetCompositionContentSchemaResponseData) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *GetCompositionContentSchemaResponseData) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *GetCompositionContentSchemaResponseData) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### GetWidgetType

`func (o *GetCompositionContentSchemaResponseData) GetWidgetType() string`

GetWidgetType returns the WidgetType field if non-nil, zero value otherwise.

### GetWidgetTypeOk

`func (o *GetCompositionContentSchemaResponseData) GetWidgetTypeOk() (*string, bool)`

GetWidgetTypeOk returns a tuple with the WidgetType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidgetType

`func (o *GetCompositionContentSchemaResponseData) SetWidgetType(v string)`

SetWidgetType sets WidgetType field to given value.

### HasWidgetType

`func (o *GetCompositionContentSchemaResponseData) HasWidgetType() bool`

HasWidgetType returns a boolean if a field has been set.

### GetType

`func (o *GetCompositionContentSchemaResponseData) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *GetCompositionContentSchemaResponseData) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *GetCompositionContentSchemaResponseData) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *GetCompositionContentSchemaResponseData) HasType() bool`

HasType returns a boolean if a field has been set.

### GetContent

`func (o *GetCompositionContentSchemaResponseData) GetContent() map[string]interface{}`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *GetCompositionContentSchemaResponseData) GetContentOk() (*map[string]interface{}, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *GetCompositionContentSchemaResponseData) SetContent(v map[string]interface{})`

SetContent sets Content field to given value.

### HasContent

`func (o *GetCompositionContentSchemaResponseData) HasContent() bool`

HasContent returns a boolean if a field has been set.

### GetContentItems

`func (o *GetCompositionContentSchemaResponseData) GetContentItems() map[string]interface{}`

GetContentItems returns the ContentItems field if non-nil, zero value otherwise.

### GetContentItemsOk

`func (o *GetCompositionContentSchemaResponseData) GetContentItemsOk() (*map[string]interface{}, bool)`

GetContentItemsOk returns a tuple with the ContentItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentItems

`func (o *GetCompositionContentSchemaResponseData) SetContentItems(v map[string]interface{})`

SetContentItems sets ContentItems field to given value.

### HasContentItems

`func (o *GetCompositionContentSchemaResponseData) HasContentItems() bool`

HasContentItems returns a boolean if a field has been set.

### GetMetadata

`func (o *GetCompositionContentSchemaResponseData) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *GetCompositionContentSchemaResponseData) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *GetCompositionContentSchemaResponseData) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *GetCompositionContentSchemaResponseData) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


