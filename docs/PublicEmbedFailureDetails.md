# PublicEmbedFailureDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Reason** | Pointer to **string** | For &#x60;DOMAIN_NOT_ALLOWED&#x60;, why the website was refused. | [optional] 
**HasDomainsConfigured** | Pointer to **bool** | For &#x60;DOMAIN_NOT_ALLOWED&#x60;, always true (an owner who listed nothing is never refused). | [optional] 

## Methods

### NewPublicEmbedFailureDetails

`func NewPublicEmbedFailureDetails() *PublicEmbedFailureDetails`

NewPublicEmbedFailureDetails instantiates a new PublicEmbedFailureDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublicEmbedFailureDetailsWithDefaults

`func NewPublicEmbedFailureDetailsWithDefaults() *PublicEmbedFailureDetails`

NewPublicEmbedFailureDetailsWithDefaults instantiates a new PublicEmbedFailureDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReason

`func (o *PublicEmbedFailureDetails) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *PublicEmbedFailureDetails) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *PublicEmbedFailureDetails) SetReason(v string)`

SetReason sets Reason field to given value.

### HasReason

`func (o *PublicEmbedFailureDetails) HasReason() bool`

HasReason returns a boolean if a field has been set.

### GetHasDomainsConfigured

`func (o *PublicEmbedFailureDetails) GetHasDomainsConfigured() bool`

GetHasDomainsConfigured returns the HasDomainsConfigured field if non-nil, zero value otherwise.

### GetHasDomainsConfiguredOk

`func (o *PublicEmbedFailureDetails) GetHasDomainsConfiguredOk() (*bool, bool)`

GetHasDomainsConfiguredOk returns a tuple with the HasDomainsConfigured field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasDomainsConfigured

`func (o *PublicEmbedFailureDetails) SetHasDomainsConfigured(v bool)`

SetHasDomainsConfigured sets HasDomainsConfigured field to given value.

### HasHasDomainsConfigured

`func (o *PublicEmbedFailureDetails) HasHasDomainsConfigured() bool`

HasHasDomainsConfigured returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


