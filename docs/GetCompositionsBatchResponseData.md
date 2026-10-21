# GetCompositionsBatchResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Compositions** | Pointer to [**[]Composition**](Composition.md) |  | [optional] 
**Errors** | Pointer to [**[]GetWidgetsBatchResponseDataErrorsInner**](GetWidgetsBatchResponseDataErrorsInner.md) |  | [optional] 

## Methods

### NewGetCompositionsBatchResponseData

`func NewGetCompositionsBatchResponseData() *GetCompositionsBatchResponseData`

NewGetCompositionsBatchResponseData instantiates a new GetCompositionsBatchResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetCompositionsBatchResponseDataWithDefaults

`func NewGetCompositionsBatchResponseDataWithDefaults() *GetCompositionsBatchResponseData`

NewGetCompositionsBatchResponseDataWithDefaults instantiates a new GetCompositionsBatchResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompositions

`func (o *GetCompositionsBatchResponseData) GetCompositions() []Composition`

GetCompositions returns the Compositions field if non-nil, zero value otherwise.

### GetCompositionsOk

`func (o *GetCompositionsBatchResponseData) GetCompositionsOk() (*[]Composition, bool)`

GetCompositionsOk returns a tuple with the Compositions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompositions

`func (o *GetCompositionsBatchResponseData) SetCompositions(v []Composition)`

SetCompositions sets Compositions field to given value.

### HasCompositions

`func (o *GetCompositionsBatchResponseData) HasCompositions() bool`

HasCompositions returns a boolean if a field has been set.

### GetErrors

`func (o *GetCompositionsBatchResponseData) GetErrors() []GetWidgetsBatchResponseDataErrorsInner`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *GetCompositionsBatchResponseData) GetErrorsOk() (*[]GetWidgetsBatchResponseDataErrorsInner, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *GetCompositionsBatchResponseData) SetErrors(v []GetWidgetsBatchResponseDataErrorsInner)`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *GetCompositionsBatchResponseData) HasErrors() bool`

HasErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


