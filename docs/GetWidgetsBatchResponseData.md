# GetWidgetsBatchResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Widgets** | Pointer to [**[]Widget**](Widget.md) |  | [optional] 
**Errors** | Pointer to [**[]GetWidgetsBatchResponseDataErrorsInner**](GetWidgetsBatchResponseDataErrorsInner.md) |  | [optional] 

## Methods

### NewGetWidgetsBatchResponseData

`func NewGetWidgetsBatchResponseData() *GetWidgetsBatchResponseData`

NewGetWidgetsBatchResponseData instantiates a new GetWidgetsBatchResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetWidgetsBatchResponseDataWithDefaults

`func NewGetWidgetsBatchResponseDataWithDefaults() *GetWidgetsBatchResponseData`

NewGetWidgetsBatchResponseDataWithDefaults instantiates a new GetWidgetsBatchResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWidgets

`func (o *GetWidgetsBatchResponseData) GetWidgets() []Widget`

GetWidgets returns the Widgets field if non-nil, zero value otherwise.

### GetWidgetsOk

`func (o *GetWidgetsBatchResponseData) GetWidgetsOk() (*[]Widget, bool)`

GetWidgetsOk returns a tuple with the Widgets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidgets

`func (o *GetWidgetsBatchResponseData) SetWidgets(v []Widget)`

SetWidgets sets Widgets field to given value.

### HasWidgets

`func (o *GetWidgetsBatchResponseData) HasWidgets() bool`

HasWidgets returns a boolean if a field has been set.

### GetErrors

`func (o *GetWidgetsBatchResponseData) GetErrors() []GetWidgetsBatchResponseDataErrorsInner`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *GetWidgetsBatchResponseData) GetErrorsOk() (*[]GetWidgetsBatchResponseDataErrorsInner, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *GetWidgetsBatchResponseData) SetErrors(v []GetWidgetsBatchResponseDataErrorsInner)`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *GetWidgetsBatchResponseData) HasErrors() bool`

HasErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


