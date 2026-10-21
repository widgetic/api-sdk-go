# SetPartnerPresetRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**WidgetId** | **string** | One of the partner&#39;s own widgets. A widget is a preset under at most one key. | 
**Title** | Pointer to **NullableString** | What your picker shows. Leave it out to show the widget&#39;s own name. | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**Position** | Pointer to **int32** | Where the preset sits in the list. Smallest first; presets with the same position are ordered by key. | [optional] [default to 0]

## Methods

### NewSetPartnerPresetRequest

`func NewSetPartnerPresetRequest(widgetId string, ) *SetPartnerPresetRequest`

NewSetPartnerPresetRequest instantiates a new SetPartnerPresetRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSetPartnerPresetRequestWithDefaults

`func NewSetPartnerPresetRequestWithDefaults() *SetPartnerPresetRequest`

NewSetPartnerPresetRequestWithDefaults instantiates a new SetPartnerPresetRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWidgetId

`func (o *SetPartnerPresetRequest) GetWidgetId() string`

GetWidgetId returns the WidgetId field if non-nil, zero value otherwise.

### GetWidgetIdOk

`func (o *SetPartnerPresetRequest) GetWidgetIdOk() (*string, bool)`

GetWidgetIdOk returns a tuple with the WidgetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidgetId

`func (o *SetPartnerPresetRequest) SetWidgetId(v string)`

SetWidgetId sets WidgetId field to given value.


### GetTitle

`func (o *SetPartnerPresetRequest) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *SetPartnerPresetRequest) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *SetPartnerPresetRequest) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *SetPartnerPresetRequest) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *SetPartnerPresetRequest) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *SetPartnerPresetRequest) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetDescription

`func (o *SetPartnerPresetRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *SetPartnerPresetRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *SetPartnerPresetRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *SetPartnerPresetRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *SetPartnerPresetRequest) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *SetPartnerPresetRequest) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetPosition

`func (o *SetPartnerPresetRequest) GetPosition() int32`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *SetPartnerPresetRequest) GetPositionOk() (*int32, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *SetPartnerPresetRequest) SetPosition(v int32)`

SetPosition sets Position field to given value.

### HasPosition

`func (o *SetPartnerPresetRequest) HasPosition() bool`

HasPosition returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


