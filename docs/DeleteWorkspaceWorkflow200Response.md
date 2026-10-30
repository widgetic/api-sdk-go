# DeleteWorkspaceWorkflow200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**WorkflowRemoved**](WorkflowRemoved.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewDeleteWorkspaceWorkflow200Response

`func NewDeleteWorkspaceWorkflow200Response(success bool, data WorkflowRemoved, ) *DeleteWorkspaceWorkflow200Response`

NewDeleteWorkspaceWorkflow200Response instantiates a new DeleteWorkspaceWorkflow200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeleteWorkspaceWorkflow200ResponseWithDefaults

`func NewDeleteWorkspaceWorkflow200ResponseWithDefaults() *DeleteWorkspaceWorkflow200Response`

NewDeleteWorkspaceWorkflow200ResponseWithDefaults instantiates a new DeleteWorkspaceWorkflow200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *DeleteWorkspaceWorkflow200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *DeleteWorkspaceWorkflow200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *DeleteWorkspaceWorkflow200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *DeleteWorkspaceWorkflow200Response) GetData() WorkflowRemoved`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *DeleteWorkspaceWorkflow200Response) GetDataOk() (*WorkflowRemoved, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *DeleteWorkspaceWorkflow200Response) SetData(v WorkflowRemoved)`

SetData sets Data field to given value.


### GetMeta

`func (o *DeleteWorkspaceWorkflow200Response) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *DeleteWorkspaceWorkflow200Response) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *DeleteWorkspaceWorkflow200Response) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *DeleteWorkspaceWorkflow200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


