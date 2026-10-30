# PublicWorkflowEventsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**VersionId** | **string** |  | 
**Token** | **string** | The &#x60;eventToken&#x60; of the workflow, read for the same version. | 
**Events** | Pointer to [**[]PublicWorkflowEventsRequestEventsInner**](PublicWorkflowEventsRequestEventsInner.md) | The counts of what visitors did. At least one of &#x60;events&#x60; and &#x60;heights&#x60; is needed. | [optional] 
**Heights** | Pointer to [**[]PublicWorkflowEventsRequestHeightsInner**](PublicWorkflowEventsRequestHeightsInner.md) | How tall steps of this version settled in the visitor&#39;s browser, so that the embed code of the workflow can start its box at the height visitors saw instead of a guess. The Embed SDK sends one for a visitor who has no remembered height for the step. The gateway keeps the latest few for each composition (the median is what the code gets); a composition that this version does not show is left out. At least one of &#x60;events&#x60; and &#x60;heights&#x60; is needed.  | [optional] 

## Methods

### NewPublicWorkflowEventsRequest

`func NewPublicWorkflowEventsRequest(versionId string, token string, ) *PublicWorkflowEventsRequest`

NewPublicWorkflowEventsRequest instantiates a new PublicWorkflowEventsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublicWorkflowEventsRequestWithDefaults

`func NewPublicWorkflowEventsRequestWithDefaults() *PublicWorkflowEventsRequest`

NewPublicWorkflowEventsRequestWithDefaults instantiates a new PublicWorkflowEventsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVersionId

`func (o *PublicWorkflowEventsRequest) GetVersionId() string`

GetVersionId returns the VersionId field if non-nil, zero value otherwise.

### GetVersionIdOk

`func (o *PublicWorkflowEventsRequest) GetVersionIdOk() (*string, bool)`

GetVersionIdOk returns a tuple with the VersionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersionId

`func (o *PublicWorkflowEventsRequest) SetVersionId(v string)`

SetVersionId sets VersionId field to given value.


### GetToken

`func (o *PublicWorkflowEventsRequest) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *PublicWorkflowEventsRequest) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *PublicWorkflowEventsRequest) SetToken(v string)`

SetToken sets Token field to given value.


### GetEvents

`func (o *PublicWorkflowEventsRequest) GetEvents() []PublicWorkflowEventsRequestEventsInner`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *PublicWorkflowEventsRequest) GetEventsOk() (*[]PublicWorkflowEventsRequestEventsInner, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *PublicWorkflowEventsRequest) SetEvents(v []PublicWorkflowEventsRequestEventsInner)`

SetEvents sets Events field to given value.

### HasEvents

`func (o *PublicWorkflowEventsRequest) HasEvents() bool`

HasEvents returns a boolean if a field has been set.

### GetHeights

`func (o *PublicWorkflowEventsRequest) GetHeights() []PublicWorkflowEventsRequestHeightsInner`

GetHeights returns the Heights field if non-nil, zero value otherwise.

### GetHeightsOk

`func (o *PublicWorkflowEventsRequest) GetHeightsOk() (*[]PublicWorkflowEventsRequestHeightsInner, bool)`

GetHeightsOk returns a tuple with the Heights field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeights

`func (o *PublicWorkflowEventsRequest) SetHeights(v []PublicWorkflowEventsRequestHeightsInner)`

SetHeights sets Heights field to given value.

### HasHeights

`func (o *PublicWorkflowEventsRequest) HasHeights() bool`

HasHeights returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


