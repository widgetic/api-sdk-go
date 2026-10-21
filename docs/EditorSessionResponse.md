# EditorSessionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** | Always &#x60;true&#x60; on a success. | 
**Data** | [**EditorSession**](EditorSession.md) |  | 
**Meta** | Pointer to [**ResponseMeta**](ResponseMeta.md) |  | [optional] 

## Methods

### NewEditorSessionResponse

`func NewEditorSessionResponse(success bool, data EditorSession, ) *EditorSessionResponse`

NewEditorSessionResponse instantiates a new EditorSessionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEditorSessionResponseWithDefaults

`func NewEditorSessionResponseWithDefaults() *EditorSessionResponse`

NewEditorSessionResponseWithDefaults instantiates a new EditorSessionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *EditorSessionResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *EditorSessionResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *EditorSessionResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *EditorSessionResponse) GetData() EditorSession`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *EditorSessionResponse) GetDataOk() (*EditorSession, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *EditorSessionResponse) SetData(v EditorSession)`

SetData sets Data field to given value.


### GetMeta

`func (o *EditorSessionResponse) GetMeta() ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *EditorSessionResponse) GetMetaOk() (*ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *EditorSessionResponse) SetMeta(v ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *EditorSessionResponse) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


