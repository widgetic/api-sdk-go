# GetCompositionEmbedSchemaResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Identifier of the schema | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Version** | Pointer to **string** | Version of the schema; it changes when a setting is added, removed or retyped | [optional] 
**Type** | Pointer to **string** | The tab this schema describes | [optional] 
**ComponentGroups** | Pointer to **[]map[string]interface{}** | The controls of the Embed tab, grouped as the editor shows them | [optional] 
**Defaults** | Pointer to **map[string]interface{}** | The value of every setting that declares one, by setting name. A value is a boolean, a number or a string, as the setting&#39;s &#x60;type&#x60; says. (Written as an open map, not as a choice of three types: a generated client cannot be built from a choice between plain types.)  | [optional] 

## Methods

### NewGetCompositionEmbedSchemaResponseData

`func NewGetCompositionEmbedSchemaResponseData() *GetCompositionEmbedSchemaResponseData`

NewGetCompositionEmbedSchemaResponseData instantiates a new GetCompositionEmbedSchemaResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetCompositionEmbedSchemaResponseDataWithDefaults

`func NewGetCompositionEmbedSchemaResponseDataWithDefaults() *GetCompositionEmbedSchemaResponseData`

NewGetCompositionEmbedSchemaResponseDataWithDefaults instantiates a new GetCompositionEmbedSchemaResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetCompositionEmbedSchemaResponseData) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetCompositionEmbedSchemaResponseData) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetCompositionEmbedSchemaResponseData) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *GetCompositionEmbedSchemaResponseData) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *GetCompositionEmbedSchemaResponseData) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *GetCompositionEmbedSchemaResponseData) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *GetCompositionEmbedSchemaResponseData) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *GetCompositionEmbedSchemaResponseData) HasName() bool`

HasName returns a boolean if a field has been set.

### GetVersion

`func (o *GetCompositionEmbedSchemaResponseData) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *GetCompositionEmbedSchemaResponseData) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *GetCompositionEmbedSchemaResponseData) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *GetCompositionEmbedSchemaResponseData) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### GetType

`func (o *GetCompositionEmbedSchemaResponseData) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *GetCompositionEmbedSchemaResponseData) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *GetCompositionEmbedSchemaResponseData) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *GetCompositionEmbedSchemaResponseData) HasType() bool`

HasType returns a boolean if a field has been set.

### GetComponentGroups

`func (o *GetCompositionEmbedSchemaResponseData) GetComponentGroups() []map[string]interface{}`

GetComponentGroups returns the ComponentGroups field if non-nil, zero value otherwise.

### GetComponentGroupsOk

`func (o *GetCompositionEmbedSchemaResponseData) GetComponentGroupsOk() (*[]map[string]interface{}, bool)`

GetComponentGroupsOk returns a tuple with the ComponentGroups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentGroups

`func (o *GetCompositionEmbedSchemaResponseData) SetComponentGroups(v []map[string]interface{})`

SetComponentGroups sets ComponentGroups field to given value.

### HasComponentGroups

`func (o *GetCompositionEmbedSchemaResponseData) HasComponentGroups() bool`

HasComponentGroups returns a boolean if a field has been set.

### GetDefaults

`func (o *GetCompositionEmbedSchemaResponseData) GetDefaults() map[string]interface{}`

GetDefaults returns the Defaults field if non-nil, zero value otherwise.

### GetDefaultsOk

`func (o *GetCompositionEmbedSchemaResponseData) GetDefaultsOk() (*map[string]interface{}, bool)`

GetDefaultsOk returns a tuple with the Defaults field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaults

`func (o *GetCompositionEmbedSchemaResponseData) SetDefaults(v map[string]interface{})`

SetDefaults sets Defaults field to given value.

### HasDefaults

`func (o *GetCompositionEmbedSchemaResponseData) HasDefaults() bool`

HasDefaults returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


