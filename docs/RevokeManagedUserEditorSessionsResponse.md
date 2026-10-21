# RevokeManagedUserEditorSessionsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Always &#x60;true&#x60; on a success. | 
**Data** | [**RevokeManagedUserEditorSessionsResponseData**](RevokeManagedUserEditorSessionsResponseData.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewRevokeManagedUserEditorSessionsResponse

`func NewRevokeManagedUserEditorSessionsResponse(success bool, data RevokeManagedUserEditorSessionsResponseData, ) *RevokeManagedUserEditorSessionsResponse`

NewRevokeManagedUserEditorSessionsResponse instantiates a new RevokeManagedUserEditorSessionsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRevokeManagedUserEditorSessionsResponseWithDefaults

`func NewRevokeManagedUserEditorSessionsResponseWithDefaults() *RevokeManagedUserEditorSessionsResponse`

NewRevokeManagedUserEditorSessionsResponseWithDefaults instantiates a new RevokeManagedUserEditorSessionsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *RevokeManagedUserEditorSessionsResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *RevokeManagedUserEditorSessionsResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *RevokeManagedUserEditorSessionsResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *RevokeManagedUserEditorSessionsResponse) GetData() RevokeManagedUserEditorSessionsResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *RevokeManagedUserEditorSessionsResponse) GetDataOk() (*RevokeManagedUserEditorSessionsResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *RevokeManagedUserEditorSessionsResponse) SetData(v RevokeManagedUserEditorSessionsResponseData)`

SetData sets Data field to given value.


### GetMeta

`func (o *RevokeManagedUserEditorSessionsResponse) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *RevokeManagedUserEditorSessionsResponse) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *RevokeManagedUserEditorSessionsResponse) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *RevokeManagedUserEditorSessionsResponse) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


