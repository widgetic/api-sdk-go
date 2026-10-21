# GetCompositionDesignSchemaResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Always &#x60;true&#x60; on a success. | 
**Data** | [**GetCompositionDesignSchemaResponseData**](GetCompositionDesignSchemaResponseData.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewGetCompositionDesignSchemaResponse

`func NewGetCompositionDesignSchemaResponse(success bool, data GetCompositionDesignSchemaResponseData, ) *GetCompositionDesignSchemaResponse`

NewGetCompositionDesignSchemaResponse instantiates a new GetCompositionDesignSchemaResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetCompositionDesignSchemaResponseWithDefaults

`func NewGetCompositionDesignSchemaResponseWithDefaults() *GetCompositionDesignSchemaResponse`

NewGetCompositionDesignSchemaResponseWithDefaults instantiates a new GetCompositionDesignSchemaResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *GetCompositionDesignSchemaResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *GetCompositionDesignSchemaResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *GetCompositionDesignSchemaResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *GetCompositionDesignSchemaResponse) GetData() GetCompositionDesignSchemaResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetCompositionDesignSchemaResponse) GetDataOk() (*GetCompositionDesignSchemaResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetCompositionDesignSchemaResponse) SetData(v GetCompositionDesignSchemaResponseData)`

SetData sets Data field to given value.


### GetMeta

`func (o *GetCompositionDesignSchemaResponse) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetCompositionDesignSchemaResponse) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetCompositionDesignSchemaResponse) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetCompositionDesignSchemaResponse) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


