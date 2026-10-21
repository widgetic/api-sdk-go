# GetAllCanvasesResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]Canvas**](Canvas.md) |  | [optional] 
**Page** | Pointer to **int32** |  | [optional] 
**Size** | Pointer to **int32** |  | [optional] 
**Total** | Pointer to **int32** | Total number of canvases matching the criteria | [optional] 

## Methods

### NewGetAllCanvasesResponseData

`func NewGetAllCanvasesResponseData() *GetAllCanvasesResponseData`

NewGetAllCanvasesResponseData instantiates a new GetAllCanvasesResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetAllCanvasesResponseDataWithDefaults

`func NewGetAllCanvasesResponseDataWithDefaults() *GetAllCanvasesResponseData`

NewGetAllCanvasesResponseDataWithDefaults instantiates a new GetAllCanvasesResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *GetAllCanvasesResponseData) GetData() []Canvas`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetAllCanvasesResponseData) GetDataOk() (*[]Canvas, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetAllCanvasesResponseData) SetData(v []Canvas)`

SetData sets Data field to given value.

### HasData

`func (o *GetAllCanvasesResponseData) HasData() bool`

HasData returns a boolean if a field has been set.

### GetPage

`func (o *GetAllCanvasesResponseData) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *GetAllCanvasesResponseData) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *GetAllCanvasesResponseData) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *GetAllCanvasesResponseData) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetSize

`func (o *GetAllCanvasesResponseData) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *GetAllCanvasesResponseData) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *GetAllCanvasesResponseData) SetSize(v int32)`

SetSize sets Size field to given value.

### HasSize

`func (o *GetAllCanvasesResponseData) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetTotal

`func (o *GetAllCanvasesResponseData) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *GetAllCanvasesResponseData) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *GetAllCanvasesResponseData) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *GetAllCanvasesResponseData) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


