# CreateCompositionDatabaseRecord201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | **map[string]interface{}** | One row of one of the composition&#39;s tables. Its properties are the table&#39;s columns, named as the widget&#39;s &#x60;database.json&#x60; names them; the row&#39;s key is &#x60;id&#x60;. Read the table&#39;s columns with &#x60;getCompositionEntries&#x60; when you need the list.  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewCreateCompositionDatabaseRecord201Response

`func NewCreateCompositionDatabaseRecord201Response(success bool, data map[string]interface{}, ) *CreateCompositionDatabaseRecord201Response`

NewCreateCompositionDatabaseRecord201Response instantiates a new CreateCompositionDatabaseRecord201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateCompositionDatabaseRecord201ResponseWithDefaults

`func NewCreateCompositionDatabaseRecord201ResponseWithDefaults() *CreateCompositionDatabaseRecord201Response`

NewCreateCompositionDatabaseRecord201ResponseWithDefaults instantiates a new CreateCompositionDatabaseRecord201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *CreateCompositionDatabaseRecord201Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *CreateCompositionDatabaseRecord201Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *CreateCompositionDatabaseRecord201Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *CreateCompositionDatabaseRecord201Response) GetData() map[string]interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *CreateCompositionDatabaseRecord201Response) GetDataOk() (*map[string]interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *CreateCompositionDatabaseRecord201Response) SetData(v map[string]interface{})`

SetData sets Data field to given value.


### GetMeta

`func (o *CreateCompositionDatabaseRecord201Response) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *CreateCompositionDatabaseRecord201Response) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *CreateCompositionDatabaseRecord201Response) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *CreateCompositionDatabaseRecord201Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


