# Upload

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Url** | **string** | The public address of the stored file | 
**MimeType** | **string** | The type of the stored file. A HEIC or HEIF photo is stored as &#x60;image/jpeg&#x60;. | 
**FileName** | **string** |  | 
**FileSize** | **int32** | Size of the stored file, in bytes | 
**Width** | Pointer to **NullableInt32** | Width in pixels, for images | [optional] 
**Height** | Pointer to **NullableInt32** | Height in pixels, for images | [optional] 
**StorageKey** | **string** | Where the file sits in its storage bucket | 
**ContextType** | **string** | What the file was uploaded for. Media for widget content is &#x60;content-property&#x60;. | 
**Source** | **string** | Which part of the product, or which client, uploaded the file. &#x60;widget-visitor-upload&#x60; is a file a visitor sent through a widget&#39;s upload adapter; it cannot be asked for when uploading. | 
**WidgetId** | Pointer to **NullableString** |  | [optional] 
**ConversationId** | Pointer to **NullableString** |  | [optional] 
**ManagedUserId** | Pointer to **NullableString** | The managed user the file was uploaded for, or null when it is the account&#39;s own. List one managed user&#39;s files with the &#x60;managed_user_id&#x60; or &#x60;managed_user_external_id&#x60; query parameter of &#x60;uploadsGet&#x60;. | [optional] 
**Purpose** | Pointer to **NullableString** | Where in the product the partner uses the file, or null when unknown | [optional] 

## Methods

### NewUpload

`func NewUpload(id string, url string, mimeType string, fileName string, fileSize int32, storageKey string, contextType string, source string, ) *Upload`

NewUpload instantiates a new Upload object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUploadWithDefaults

`func NewUploadWithDefaults() *Upload`

NewUploadWithDefaults instantiates a new Upload object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Upload) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Upload) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Upload) SetId(v string)`

SetId sets Id field to given value.


### GetUrl

`func (o *Upload) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *Upload) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *Upload) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetMimeType

`func (o *Upload) GetMimeType() string`

GetMimeType returns the MimeType field if non-nil, zero value otherwise.

### GetMimeTypeOk

`func (o *Upload) GetMimeTypeOk() (*string, bool)`

GetMimeTypeOk returns a tuple with the MimeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMimeType

`func (o *Upload) SetMimeType(v string)`

SetMimeType sets MimeType field to given value.


### GetFileName

`func (o *Upload) GetFileName() string`

GetFileName returns the FileName field if non-nil, zero value otherwise.

### GetFileNameOk

`func (o *Upload) GetFileNameOk() (*string, bool)`

GetFileNameOk returns a tuple with the FileName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileName

`func (o *Upload) SetFileName(v string)`

SetFileName sets FileName field to given value.


### GetFileSize

`func (o *Upload) GetFileSize() int32`

GetFileSize returns the FileSize field if non-nil, zero value otherwise.

### GetFileSizeOk

`func (o *Upload) GetFileSizeOk() (*int32, bool)`

GetFileSizeOk returns a tuple with the FileSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileSize

`func (o *Upload) SetFileSize(v int32)`

SetFileSize sets FileSize field to given value.


### GetWidth

`func (o *Upload) GetWidth() int32`

GetWidth returns the Width field if non-nil, zero value otherwise.

### GetWidthOk

`func (o *Upload) GetWidthOk() (*int32, bool)`

GetWidthOk returns a tuple with the Width field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidth

`func (o *Upload) SetWidth(v int32)`

SetWidth sets Width field to given value.

### HasWidth

`func (o *Upload) HasWidth() bool`

HasWidth returns a boolean if a field has been set.

### SetWidthNil

`func (o *Upload) SetWidthNil(b bool)`

 SetWidthNil sets the value for Width to be an explicit nil

### UnsetWidth
`func (o *Upload) UnsetWidth()`

UnsetWidth ensures that no value is present for Width, not even an explicit nil
### GetHeight

`func (o *Upload) GetHeight() int32`

GetHeight returns the Height field if non-nil, zero value otherwise.

### GetHeightOk

`func (o *Upload) GetHeightOk() (*int32, bool)`

GetHeightOk returns a tuple with the Height field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeight

`func (o *Upload) SetHeight(v int32)`

SetHeight sets Height field to given value.

### HasHeight

`func (o *Upload) HasHeight() bool`

HasHeight returns a boolean if a field has been set.

### SetHeightNil

`func (o *Upload) SetHeightNil(b bool)`

 SetHeightNil sets the value for Height to be an explicit nil

### UnsetHeight
`func (o *Upload) UnsetHeight()`

UnsetHeight ensures that no value is present for Height, not even an explicit nil
### GetStorageKey

`func (o *Upload) GetStorageKey() string`

GetStorageKey returns the StorageKey field if non-nil, zero value otherwise.

### GetStorageKeyOk

`func (o *Upload) GetStorageKeyOk() (*string, bool)`

GetStorageKeyOk returns a tuple with the StorageKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStorageKey

`func (o *Upload) SetStorageKey(v string)`

SetStorageKey sets StorageKey field to given value.


### GetContextType

`func (o *Upload) GetContextType() string`

GetContextType returns the ContextType field if non-nil, zero value otherwise.

### GetContextTypeOk

`func (o *Upload) GetContextTypeOk() (*string, bool)`

GetContextTypeOk returns a tuple with the ContextType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContextType

`func (o *Upload) SetContextType(v string)`

SetContextType sets ContextType field to given value.


### GetSource

`func (o *Upload) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *Upload) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *Upload) SetSource(v string)`

SetSource sets Source field to given value.


### GetWidgetId

`func (o *Upload) GetWidgetId() string`

GetWidgetId returns the WidgetId field if non-nil, zero value otherwise.

### GetWidgetIdOk

`func (o *Upload) GetWidgetIdOk() (*string, bool)`

GetWidgetIdOk returns a tuple with the WidgetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidgetId

`func (o *Upload) SetWidgetId(v string)`

SetWidgetId sets WidgetId field to given value.

### HasWidgetId

`func (o *Upload) HasWidgetId() bool`

HasWidgetId returns a boolean if a field has been set.

### SetWidgetIdNil

`func (o *Upload) SetWidgetIdNil(b bool)`

 SetWidgetIdNil sets the value for WidgetId to be an explicit nil

### UnsetWidgetId
`func (o *Upload) UnsetWidgetId()`

UnsetWidgetId ensures that no value is present for WidgetId, not even an explicit nil
### GetConversationId

`func (o *Upload) GetConversationId() string`

GetConversationId returns the ConversationId field if non-nil, zero value otherwise.

### GetConversationIdOk

`func (o *Upload) GetConversationIdOk() (*string, bool)`

GetConversationIdOk returns a tuple with the ConversationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConversationId

`func (o *Upload) SetConversationId(v string)`

SetConversationId sets ConversationId field to given value.

### HasConversationId

`func (o *Upload) HasConversationId() bool`

HasConversationId returns a boolean if a field has been set.

### SetConversationIdNil

`func (o *Upload) SetConversationIdNil(b bool)`

 SetConversationIdNil sets the value for ConversationId to be an explicit nil

### UnsetConversationId
`func (o *Upload) UnsetConversationId()`

UnsetConversationId ensures that no value is present for ConversationId, not even an explicit nil
### GetManagedUserId

`func (o *Upload) GetManagedUserId() string`

GetManagedUserId returns the ManagedUserId field if non-nil, zero value otherwise.

### GetManagedUserIdOk

`func (o *Upload) GetManagedUserIdOk() (*string, bool)`

GetManagedUserIdOk returns a tuple with the ManagedUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManagedUserId

`func (o *Upload) SetManagedUserId(v string)`

SetManagedUserId sets ManagedUserId field to given value.

### HasManagedUserId

`func (o *Upload) HasManagedUserId() bool`

HasManagedUserId returns a boolean if a field has been set.

### SetManagedUserIdNil

`func (o *Upload) SetManagedUserIdNil(b bool)`

 SetManagedUserIdNil sets the value for ManagedUserId to be an explicit nil

### UnsetManagedUserId
`func (o *Upload) UnsetManagedUserId()`

UnsetManagedUserId ensures that no value is present for ManagedUserId, not even an explicit nil
### GetPurpose

`func (o *Upload) GetPurpose() string`

GetPurpose returns the Purpose field if non-nil, zero value otherwise.

### GetPurposeOk

`func (o *Upload) GetPurposeOk() (*string, bool)`

GetPurposeOk returns a tuple with the Purpose field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurpose

`func (o *Upload) SetPurpose(v string)`

SetPurpose sets Purpose field to given value.

### HasPurpose

`func (o *Upload) HasPurpose() bool`

HasPurpose returns a boolean if a field has been set.

### SetPurposeNil

`func (o *Upload) SetPurposeNil(b bool)`

 SetPurposeNil sets the value for Purpose to be an explicit nil

### UnsetPurpose
`func (o *Upload) UnsetPurpose()`

UnsetPurpose ensures that no value is present for Purpose, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


