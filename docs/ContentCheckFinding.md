# ContentCheckFinding

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Path** | **string** | Where it is, for example &#x60;content.interval&#x60; or &#x60;content.items[2].caption&#x60;. | 
**Message** | **string** | What is wrong, in a sentence. | 
**Expected** | Pointer to **string** | What the field takes. | [optional] 
**Actual** | Pointer to **string** | What was sent, shortened. Text and numbers as they were, anything else as its kind. | [optional] 

## Methods

### NewContentCheckFinding

`func NewContentCheckFinding(path string, message string, ) *ContentCheckFinding`

NewContentCheckFinding instantiates a new ContentCheckFinding object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContentCheckFindingWithDefaults

`func NewContentCheckFindingWithDefaults() *ContentCheckFinding`

NewContentCheckFindingWithDefaults instantiates a new ContentCheckFinding object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPath

`func (o *ContentCheckFinding) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *ContentCheckFinding) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *ContentCheckFinding) SetPath(v string)`

SetPath sets Path field to given value.


### GetMessage

`func (o *ContentCheckFinding) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *ContentCheckFinding) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *ContentCheckFinding) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetExpected

`func (o *ContentCheckFinding) GetExpected() string`

GetExpected returns the Expected field if non-nil, zero value otherwise.

### GetExpectedOk

`func (o *ContentCheckFinding) GetExpectedOk() (*string, bool)`

GetExpectedOk returns a tuple with the Expected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpected

`func (o *ContentCheckFinding) SetExpected(v string)`

SetExpected sets Expected field to given value.

### HasExpected

`func (o *ContentCheckFinding) HasExpected() bool`

HasExpected returns a boolean if a field has been set.

### GetActual

`func (o *ContentCheckFinding) GetActual() string`

GetActual returns the Actual field if non-nil, zero value otherwise.

### GetActualOk

`func (o *ContentCheckFinding) GetActualOk() (*string, bool)`

GetActualOk returns a tuple with the Actual field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActual

`func (o *ContentCheckFinding) SetActual(v string)`

SetActual sets Actual field to given value.

### HasActual

`func (o *ContentCheckFinding) HasActual() bool`

HasActual returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


