# OfferWorkflowPresetRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**WorkflowId** | **string** | One of your own published workflows. | 
**Title** | Pointer to **NullableString** | What the picker shows. Leave it out to show the workflow&#39;s name. | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**Position** | Pointer to **int32** | Where it sits in the list. Smallest first; the same position is ordered by key. | [optional] [default to 0]

## Methods

### NewOfferWorkflowPresetRequest

`func NewOfferWorkflowPresetRequest(workflowId string, ) *OfferWorkflowPresetRequest`

NewOfferWorkflowPresetRequest instantiates a new OfferWorkflowPresetRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOfferWorkflowPresetRequestWithDefaults

`func NewOfferWorkflowPresetRequestWithDefaults() *OfferWorkflowPresetRequest`

NewOfferWorkflowPresetRequestWithDefaults instantiates a new OfferWorkflowPresetRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWorkflowId

`func (o *OfferWorkflowPresetRequest) GetWorkflowId() string`

GetWorkflowId returns the WorkflowId field if non-nil, zero value otherwise.

### GetWorkflowIdOk

`func (o *OfferWorkflowPresetRequest) GetWorkflowIdOk() (*string, bool)`

GetWorkflowIdOk returns a tuple with the WorkflowId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowId

`func (o *OfferWorkflowPresetRequest) SetWorkflowId(v string)`

SetWorkflowId sets WorkflowId field to given value.


### GetTitle

`func (o *OfferWorkflowPresetRequest) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *OfferWorkflowPresetRequest) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *OfferWorkflowPresetRequest) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *OfferWorkflowPresetRequest) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *OfferWorkflowPresetRequest) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *OfferWorkflowPresetRequest) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetDescription

`func (o *OfferWorkflowPresetRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *OfferWorkflowPresetRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *OfferWorkflowPresetRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *OfferWorkflowPresetRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *OfferWorkflowPresetRequest) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *OfferWorkflowPresetRequest) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetPosition

`func (o *OfferWorkflowPresetRequest) GetPosition() int32`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *OfferWorkflowPresetRequest) GetPositionOk() (*int32, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *OfferWorkflowPresetRequest) SetPosition(v int32)`

SetPosition sets Position field to given value.

### HasPosition

`func (o *OfferWorkflowPresetRequest) HasPosition() bool`

HasPosition returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


