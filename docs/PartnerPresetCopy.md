# PartnerPresetCopy

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PresetKey** | **string** |  | 
**ManagedUserId** | **string** | The managed user the copy was made for | 
**CanvasId** | **string** | The new canvas the copy is on | 
**WidgetId** | **string** | The new widget, which is not a preset and which only this managed user&#39;s editor reaches | 
**WidgetName** | **string** |  | 
**Warnings** | **[]string** | Things that did not go as planned but did not stop the copy. Empty when everything did. | 

## Methods

### NewPartnerPresetCopy

`func NewPartnerPresetCopy(presetKey string, managedUserId string, canvasId string, widgetId string, widgetName string, warnings []string, ) *PartnerPresetCopy`

NewPartnerPresetCopy instantiates a new PartnerPresetCopy object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerPresetCopyWithDefaults

`func NewPartnerPresetCopyWithDefaults() *PartnerPresetCopy`

NewPartnerPresetCopyWithDefaults instantiates a new PartnerPresetCopy object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPresetKey

`func (o *PartnerPresetCopy) GetPresetKey() string`

GetPresetKey returns the PresetKey field if non-nil, zero value otherwise.

### GetPresetKeyOk

`func (o *PartnerPresetCopy) GetPresetKeyOk() (*string, bool)`

GetPresetKeyOk returns a tuple with the PresetKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPresetKey

`func (o *PartnerPresetCopy) SetPresetKey(v string)`

SetPresetKey sets PresetKey field to given value.


### GetManagedUserId

`func (o *PartnerPresetCopy) GetManagedUserId() string`

GetManagedUserId returns the ManagedUserId field if non-nil, zero value otherwise.

### GetManagedUserIdOk

`func (o *PartnerPresetCopy) GetManagedUserIdOk() (*string, bool)`

GetManagedUserIdOk returns a tuple with the ManagedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUserId

`func (o *PartnerPresetCopy) SetManagedUserId(v string)`

SetManagedUserId sets ManagedUserId field to given value.


### GetCanvasId

`func (o *PartnerPresetCopy) GetCanvasId() string`

GetCanvasId returns the CanvasId field if non-nil, zero value otherwise.

### GetCanvasIdOk

`func (o *PartnerPresetCopy) GetCanvasIdOk() (*string, bool)`

GetCanvasIdOk returns a tuple with the CanvasId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanvasId

`func (o *PartnerPresetCopy) SetCanvasId(v string)`

SetCanvasId sets CanvasId field to given value.


### GetWidgetId

`func (o *PartnerPresetCopy) GetWidgetId() string`

GetWidgetId returns the WidgetId field if non-nil, zero value otherwise.

### GetWidgetIdOk

`func (o *PartnerPresetCopy) GetWidgetIdOk() (*string, bool)`

GetWidgetIdOk returns a tuple with the WidgetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidgetId

`func (o *PartnerPresetCopy) SetWidgetId(v string)`

SetWidgetId sets WidgetId field to given value.


### GetWidgetName

`func (o *PartnerPresetCopy) GetWidgetName() string`

GetWidgetName returns the WidgetName field if non-nil, zero value otherwise.

### GetWidgetNameOk

`func (o *PartnerPresetCopy) GetWidgetNameOk() (*string, bool)`

GetWidgetNameOk returns a tuple with the WidgetName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidgetName

`func (o *PartnerPresetCopy) SetWidgetName(v string)`

SetWidgetName sets WidgetName field to given value.


### GetWarnings

`func (o *PartnerPresetCopy) GetWarnings() []string`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *PartnerPresetCopy) GetWarningsOk() (*[]string, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *PartnerPresetCopy) SetWarnings(v []string)`

SetWarnings sets Warnings field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


