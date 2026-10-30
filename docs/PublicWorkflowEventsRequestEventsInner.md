# PublicWorkflowEventsRequestEventsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**K** | **string** | &#x60;n&#x60; a visitor reached a block, &#x60;e&#x60; a visitor took a connection, &#x60;f&#x60; moving a visitor on failed. | 
**Id** | **string** | The block or connection counted. | 
**C** | Pointer to **int32** | How many times (1 when not given). | [optional] 

## Methods

### NewPublicWorkflowEventsRequestEventsInner

`func NewPublicWorkflowEventsRequestEventsInner(k string, id string, ) *PublicWorkflowEventsRequestEventsInner`

NewPublicWorkflowEventsRequestEventsInner instantiates a new PublicWorkflowEventsRequestEventsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublicWorkflowEventsRequestEventsInnerWithDefaults

`func NewPublicWorkflowEventsRequestEventsInnerWithDefaults() *PublicWorkflowEventsRequestEventsInner`

NewPublicWorkflowEventsRequestEventsInnerWithDefaults instantiates a new PublicWorkflowEventsRequestEventsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetK

`func (o *PublicWorkflowEventsRequestEventsInner) GetK() string`

GetK returns the K field if non-nil, zero value otherwise.

### GetKOk

`func (o *PublicWorkflowEventsRequestEventsInner) GetKOk() (*string, bool)`

GetKOk returns a tuple with the K field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetK

`func (o *PublicWorkflowEventsRequestEventsInner) SetK(v string)`

SetK sets K field to given value.


### GetId

`func (o *PublicWorkflowEventsRequestEventsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PublicWorkflowEventsRequestEventsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PublicWorkflowEventsRequestEventsInner) SetId(v string)`

SetId sets Id field to given value.


### GetC

`func (o *PublicWorkflowEventsRequestEventsInner) GetC() int32`

GetC returns the C field if non-nil, zero value otherwise.

### GetCOk

`func (o *PublicWorkflowEventsRequestEventsInner) GetCOk() (*int32, bool)`

GetCOk returns a tuple with the C field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetC

`func (o *PublicWorkflowEventsRequestEventsInner) SetC(v int32)`

SetC sets C field to given value.

### HasC

`func (o *PublicWorkflowEventsRequestEventsInner) HasC() bool`

HasC returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


