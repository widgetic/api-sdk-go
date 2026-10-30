# SaveWorkspaceWorkflow200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**Workflow**](Workflow.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewSaveWorkspaceWorkflow200Response

`func NewSaveWorkspaceWorkflow200Response(success bool, data Workflow, ) *SaveWorkspaceWorkflow200Response`

NewSaveWorkspaceWorkflow200Response instantiates a new SaveWorkspaceWorkflow200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSaveWorkspaceWorkflow200ResponseWithDefaults

`func NewSaveWorkspaceWorkflow200ResponseWithDefaults() *SaveWorkspaceWorkflow200Response`

NewSaveWorkspaceWorkflow200ResponseWithDefaults instantiates a new SaveWorkspaceWorkflow200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *SaveWorkspaceWorkflow200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *SaveWorkspaceWorkflow200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *SaveWorkspaceWorkflow200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *SaveWorkspaceWorkflow200Response) GetData() Workflow`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *SaveWorkspaceWorkflow200Response) GetDataOk() (*Workflow, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *SaveWorkspaceWorkflow200Response) SetData(v Workflow)`

SetData sets Data field to given value.


### GetMeta

`func (o *SaveWorkspaceWorkflow200Response) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *SaveWorkspaceWorkflow200Response) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *SaveWorkspaceWorkflow200Response) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *SaveWorkspaceWorkflow200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


