# PublicAdapterCallResultData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Output** | **map[string]interface{}** | What the operation answered, exactly as it wrote it: its field names are NOT rewritten to camelCase on the way out. At most 256 KiB of JSON. Each operation documents its own fields. | 

## Methods

### NewPublicAdapterCallResultData

`func NewPublicAdapterCallResultData(output map[string]interface{}, ) *PublicAdapterCallResultData`

NewPublicAdapterCallResultData instantiates a new PublicAdapterCallResultData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublicAdapterCallResultDataWithDefaults

`func NewPublicAdapterCallResultDataWithDefaults() *PublicAdapterCallResultData`

NewPublicAdapterCallResultDataWithDefaults instantiates a new PublicAdapterCallResultData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOutput

`func (o *PublicAdapterCallResultData) GetOutput() map[string]interface{}`

GetOutput returns the Output field if non-nil, zero value otherwise.

### GetOutputOk

`func (o *PublicAdapterCallResultData) GetOutputOk() (*map[string]interface{}, bool)`

GetOutputOk returns a tuple with the Output field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutput

`func (o *PublicAdapterCallResultData) SetOutput(v map[string]interface{})`

SetOutput sets Output field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


