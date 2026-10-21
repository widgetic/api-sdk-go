# GetCompositionDatabaseRecords200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | **[]map[string]interface{}** |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewGetCompositionDatabaseRecords200Response

`func NewGetCompositionDatabaseRecords200Response(success bool, data []map[string]interface{}, ) *GetCompositionDatabaseRecords200Response`

NewGetCompositionDatabaseRecords200Response instantiates a new GetCompositionDatabaseRecords200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetCompositionDatabaseRecords200ResponseWithDefaults

`func NewGetCompositionDatabaseRecords200ResponseWithDefaults() *GetCompositionDatabaseRecords200Response`

NewGetCompositionDatabaseRecords200ResponseWithDefaults instantiates a new GetCompositionDatabaseRecords200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *GetCompositionDatabaseRecords200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetCompositionDatabaseRecords200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetCompositionDatabaseRecords200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *GetCompositionDatabaseRecords200Response) GetData() []map[string]interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetCompositionDatabaseRecords200Response) GetDataOk() (*[]map[string]interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetCompositionDatabaseRecords200Response) SetData(v []map[string]interface{})`

SetData sets Data field to given value.


### GetMeta

`func (o *GetCompositionDatabaseRecords200Response) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetCompositionDatabaseRecords200Response) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetCompositionDatabaseRecords200Response) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetCompositionDatabaseRecords200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


