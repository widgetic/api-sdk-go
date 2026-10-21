# GetManagedUsersByManagerIdResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]ManagedUser**](ManagedUser.md) |  | [optional] 
**Page** | Pointer to **int32** |  | [optional] 
**Size** | Pointer to **int32** |  | [optional] 
**Total** | Pointer to **int32** |  | [optional] 

## Methods

### NewGetManagedUsersByManagerIdResponseData

`func NewGetManagedUsersByManagerIdResponseData() *GetManagedUsersByManagerIdResponseData`

NewGetManagedUsersByManagerIdResponseData instantiates a new GetManagedUsersByManagerIdResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetManagedUsersByManagerIdResponseDataWithDefaults

`func NewGetManagedUsersByManagerIdResponseDataWithDefaults() *GetManagedUsersByManagerIdResponseData`

NewGetManagedUsersByManagerIdResponseDataWithDefaults instantiates a new GetManagedUsersByManagerIdResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *GetManagedUsersByManagerIdResponseData) GetData() []ManagedUser`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetManagedUsersByManagerIdResponseData) GetDataOk() (*[]ManagedUser, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetManagedUsersByManagerIdResponseData) SetData(v []ManagedUser)`

SetData sets Data field to given value.

### HasData

`func (o *GetManagedUsersByManagerIdResponseData) HasData() bool`

HasData returns a boolean if a field has been set.

### GetPage

`func (o *GetManagedUsersByManagerIdResponseData) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *GetManagedUsersByManagerIdResponseData) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *GetManagedUsersByManagerIdResponseData) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *GetManagedUsersByManagerIdResponseData) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetSize

`func (o *GetManagedUsersByManagerIdResponseData) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *GetManagedUsersByManagerIdResponseData) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *GetManagedUsersByManagerIdResponseData) SetSize(v int32)`

SetSize sets Size field to given value.

### HasSize

`func (o *GetManagedUsersByManagerIdResponseData) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetTotal

`func (o *GetManagedUsersByManagerIdResponseData) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *GetManagedUsersByManagerIdResponseData) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *GetManagedUsersByManagerIdResponseData) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *GetManagedUsersByManagerIdResponseData) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


