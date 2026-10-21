# PublicCompositionEntryRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Values** | **map[string]interface{}** | Column values to insert (never id or time columns). | 
**Context** | Pointer to **map[string]interface{}** | Host attribution from the embedding page. It is not authenticated unless the partner signs it (see the description of this operation): never use it for authorization on its own. At most 20 keys; string values up to 500 characters or finite numbers; 2048 bytes JSON total. A signed context carries two more keys, &#x60;widgetic_exp&#x60; and &#x60;widgetic_sig&#x60;: the gateway checks them and drops them, so they are neither stored nor announced. | [optional] 
**WriteToken** | Pointer to **NullableString** | Optional per-composition write token (&#x60;entries.writeToken&#x60; from &#x60;widgetic:host&#x60;, or &#x60;entryWriteToken&#x60; from &#x60;GET /embed/compositions/{compositionId}&#x60;) when not passed in the &#x60;X-Widgetic-Write-Token&#x60; header. | [optional] 

## Methods

### NewPublicCompositionEntryRequest

`func NewPublicCompositionEntryRequest(values map[string]interface{}, ) *PublicCompositionEntryRequest`

NewPublicCompositionEntryRequest instantiates a new PublicCompositionEntryRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublicCompositionEntryRequestWithDefaults

`func NewPublicCompositionEntryRequestWithDefaults() *PublicCompositionEntryRequest`

NewPublicCompositionEntryRequestWithDefaults instantiates a new PublicCompositionEntryRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetValues

`func (o *PublicCompositionEntryRequest) GetValues() map[string]interface{}`

GetValues returns the Values field if non-nil, zero value otherwise.

### GetValuesOk

`func (o *PublicCompositionEntryRequest) GetValuesOk() (*map[string]interface{}, bool)`

GetValuesOk returns a tuple with the Values field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValues

`func (o *PublicCompositionEntryRequest) SetValues(v map[string]interface{})`

SetValues sets Values field to given value.


### GetContext

`func (o *PublicCompositionEntryRequest) GetContext() map[string]interface{}`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *PublicCompositionEntryRequest) GetContextOk() (*map[string]interface{}, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *PublicCompositionEntryRequest) SetContext(v map[string]interface{})`

SetContext sets Context field to given value.

### HasContext

`func (o *PublicCompositionEntryRequest) HasContext() bool`

HasContext returns a boolean if a field has been set.

### SetContextNil

`func (o *PublicCompositionEntryRequest) SetContextNil(b bool)`

 SetContextNil sets the value for Context to be an explicit nil

### UnsetContext
`func (o *PublicCompositionEntryRequest) UnsetContext()`

UnsetContext ensures that no value is present for Context, not even an explicit nil
### GetWriteToken

`func (o *PublicCompositionEntryRequest) GetWriteToken() string`

GetWriteToken returns the WriteToken field if non-nil, zero value otherwise.

### GetWriteTokenOk

`func (o *PublicCompositionEntryRequest) GetWriteTokenOk() (*string, bool)`

GetWriteTokenOk returns a tuple with the WriteToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWriteToken

`func (o *PublicCompositionEntryRequest) SetWriteToken(v string)`

SetWriteToken sets WriteToken field to given value.

### HasWriteToken

`func (o *PublicCompositionEntryRequest) HasWriteToken() bool`

HasWriteToken returns a boolean if a field has been set.

### SetWriteTokenNil

`func (o *PublicCompositionEntryRequest) SetWriteTokenNil(b bool)`

 SetWriteTokenNil sets the value for WriteToken to be an explicit nil

### UnsetWriteToken
`func (o *PublicCompositionEntryRequest) UnsetWriteToken()`

UnsetWriteToken ensures that no value is present for WriteToken, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


