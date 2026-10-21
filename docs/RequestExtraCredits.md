# RequestExtraCredits

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Usd** | **float32** | The dollars to spend on credits, to the cent: at least 10, at most 100000 in one request. The invoice is for the most whole credits that money buys at the list price of a credit, so it is never for more than this (12.34 buys 123 credits and the invoice says 12.30).  | 

## Methods

### NewRequestExtraCredits

`func NewRequestExtraCredits(usd float32, ) *RequestExtraCredits`

NewRequestExtraCredits instantiates a new RequestExtraCredits object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRequestExtraCreditsWithDefaults

`func NewRequestExtraCreditsWithDefaults() *RequestExtraCredits`

NewRequestExtraCreditsWithDefaults instantiates a new RequestExtraCredits object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUsd

`func (o *RequestExtraCredits) GetUsd() float32`

GetUsd returns the Usd field if non-nil, zero value otherwise.

### GetUsdOk

`func (o *RequestExtraCredits) GetUsdOk() (*float32, bool)`

GetUsdOk returns a tuple with the Usd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsd

`func (o *RequestExtraCredits) SetUsd(v float32)`

SetUsd sets Usd field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


