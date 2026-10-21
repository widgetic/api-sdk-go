# PartnerPreset

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | **string** | The name the partner&#39;s code uses for the preset | 
**WidgetId** | **string** | The partner&#39;s widget. Use it to make a composition (&#x60;createComposition&#x60; with this &#x60;widgetId&#x60;). | 
**Title** | **NullableString** | What the partner&#39;s picker shows. Null means show &#x60;widgetName&#x60;. | 
**Description** | **NullableString** |  | 
**Position** | **int32** | The list is ordered by this, smallest first, then by key | 
**WidgetName** | **string** | The widget&#39;s own name | 
**ThumbnailUrl** | **NullableString** | The widget&#39;s thumbnail, when it has one | 
**CreatedAt** | **time.Time** |  | 
**UpdatedAt** | **time.Time** |  | 

## Methods

### NewPartnerPreset

`func NewPartnerPreset(key string, widgetId string, title NullableString, description NullableString, position int32, widgetName string, thumbnailUrl NullableString, createdAt time.Time, updatedAt time.Time, ) *PartnerPreset`

NewPartnerPreset instantiates a new PartnerPreset object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerPresetWithDefaults

`func NewPartnerPresetWithDefaults() *PartnerPreset`

NewPartnerPresetWithDefaults instantiates a new PartnerPreset object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *PartnerPreset) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *PartnerPreset) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *PartnerPreset) SetKey(v string)`

SetKey sets Key field to given value.


### GetWidgetId

`func (o *PartnerPreset) GetWidgetId() string`

GetWidgetId returns the WidgetId field if non-nil, zero value otherwise.

### GetWidgetIdOk

`func (o *PartnerPreset) GetWidgetIdOk() (*string, bool)`

GetWidgetIdOk returns a tuple with the WidgetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidgetId

`func (o *PartnerPreset) SetWidgetId(v string)`

SetWidgetId sets WidgetId field to given value.


### GetTitle

`func (o *PartnerPreset) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *PartnerPreset) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *PartnerPreset) SetTitle(v string)`

SetTitle sets Title field to given value.


### SetTitleNil

`func (o *PartnerPreset) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *PartnerPreset) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetDescription

`func (o *PartnerPreset) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PartnerPreset) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PartnerPreset) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *PartnerPreset) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *PartnerPreset) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetPosition

`func (o *PartnerPreset) GetPosition() int32`

GetPosition returns the Position field if non-nil, zero value otherwise.

### GetPositionOk

`func (o *PartnerPreset) GetPositionOk() (*int32, bool)`

GetPositionOk returns a tuple with the Position field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosition

`func (o *PartnerPreset) SetPosition(v int32)`

SetPosition sets Position field to given value.


### GetWidgetName

`func (o *PartnerPreset) GetWidgetName() string`

GetWidgetName returns the WidgetName field if non-nil, zero value otherwise.

### GetWidgetNameOk

`func (o *PartnerPreset) GetWidgetNameOk() (*string, bool)`

GetWidgetNameOk returns a tuple with the WidgetName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidgetName

`func (o *PartnerPreset) SetWidgetName(v string)`

SetWidgetName sets WidgetName field to given value.


### GetThumbnailUrl

`func (o *PartnerPreset) GetThumbnailUrl() string`

GetThumbnailUrl returns the ThumbnailUrl field if non-nil, zero value otherwise.

### GetThumbnailUrlOk

`func (o *PartnerPreset) GetThumbnailUrlOk() (*string, bool)`

GetThumbnailUrlOk returns a tuple with the ThumbnailUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThumbnailUrl

`func (o *PartnerPreset) SetThumbnailUrl(v string)`

SetThumbnailUrl sets ThumbnailUrl field to given value.


### SetThumbnailUrlNil

`func (o *PartnerPreset) SetThumbnailUrlNil(b bool)`

 SetThumbnailUrlNil sets the value for ThumbnailUrl to be an explicit nil

### UnsetThumbnailUrl
`func (o *PartnerPreset) UnsetThumbnailUrl()`

UnsetThumbnailUrl ensures that no value is present for ThumbnailUrl, not even an explicit nil
### GetCreatedAt

`func (o *PartnerPreset) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *PartnerPreset) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *PartnerPreset) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *PartnerPreset) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *PartnerPreset) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *PartnerPreset) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


