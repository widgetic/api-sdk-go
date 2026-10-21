# ExportCompositionEntryItems200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**[]CompositionEntryItem**](CompositionEntryItem.md) |  | 
**Meta** | [**ExportCompositionEntryItems200ResponseMeta**](ExportCompositionEntryItems200ResponseMeta.md) |  | 

## Methods

### NewExportCompositionEntryItems200Response

`func NewExportCompositionEntryItems200Response(success bool, data []CompositionEntryItem, meta ExportCompositionEntryItems200ResponseMeta, ) *ExportCompositionEntryItems200Response`

NewExportCompositionEntryItems200Response instantiates a new ExportCompositionEntryItems200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExportCompositionEntryItems200ResponseWithDefaults

`func NewExportCompositionEntryItems200ResponseWithDefaults() *ExportCompositionEntryItems200Response`

NewExportCompositionEntryItems200ResponseWithDefaults instantiates a new ExportCompositionEntryItems200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *ExportCompositionEntryItems200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ExportCompositionEntryItems200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ExportCompositionEntryItems200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *ExportCompositionEntryItems200Response) GetData() []CompositionEntryItem`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ExportCompositionEntryItems200Response) GetDataOk() (*[]CompositionEntryItem, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ExportCompositionEntryItems200Response) SetData(v []CompositionEntryItem)`

SetData sets Data field to given value.


### GetMeta

`func (o *ExportCompositionEntryItems200Response) GetMeta() ExportCompositionEntryItems200ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ExportCompositionEntryItems200Response) GetMetaOk() (*ExportCompositionEntryItems200ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ExportCompositionEntryItems200Response) SetMeta(v ExportCompositionEntryItems200ResponseMeta)`

SetMeta sets Meta field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


