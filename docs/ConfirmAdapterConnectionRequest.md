# ConfirmAdapterConnectionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | **string** | The digits of the code Widgetic emailed to the address, with nothing else. It works for 30 minutes and for five wrong tries; after that, save the address again and a new code is emailed | 

## Methods

### NewConfirmAdapterConnectionRequest

`func NewConfirmAdapterConnectionRequest(code string, ) *ConfirmAdapterConnectionRequest`

NewConfirmAdapterConnectionRequest instantiates a new ConfirmAdapterConnectionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConfirmAdapterConnectionRequestWithDefaults

`func NewConfirmAdapterConnectionRequestWithDefaults() *ConfirmAdapterConnectionRequest`

NewConfirmAdapterConnectionRequestWithDefaults instantiates a new ConfirmAdapterConnectionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *ConfirmAdapterConnectionRequest) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *ConfirmAdapterConnectionRequest) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *ConfirmAdapterConnectionRequest) SetCode(v string)`

SetCode sets Code field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


