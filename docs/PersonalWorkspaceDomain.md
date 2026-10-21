# PersonalWorkspaceDomain

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The id of the entry. Use it to change or remove the entry | 
**UserId** | **string** | The account the list belongs to | 
**Domain** | **string** | The website as it is kept: lower case, with no scheme, port, path or leading &#x60;www.&#x60;. A leading &#x60;*.&#x60; means the website and all of its subdomains | 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**UpdatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewPersonalWorkspaceDomain

`func NewPersonalWorkspaceDomain(id string, userId string, domain string, ) *PersonalWorkspaceDomain`

NewPersonalWorkspaceDomain instantiates a new PersonalWorkspaceDomain object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPersonalWorkspaceDomainWithDefaults

`func NewPersonalWorkspaceDomainWithDefaults() *PersonalWorkspaceDomain`

NewPersonalWorkspaceDomainWithDefaults instantiates a new PersonalWorkspaceDomain object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PersonalWorkspaceDomain) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PersonalWorkspaceDomain) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PersonalWorkspaceDomain) SetId(v string)`

SetId sets Id field to given value.


### GetUserId

`func (o *PersonalWorkspaceDomain) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *PersonalWorkspaceDomain) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *PersonalWorkspaceDomain) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetDomain

`func (o *PersonalWorkspaceDomain) GetDomain() string`

GetDomain returns the Domain field if non-nil, zero value otherwise.

### GetDomainOk

`func (o *PersonalWorkspaceDomain) GetDomainOk() (*string, bool)`

GetDomainOk returns a tuple with the Domain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomain

`func (o *PersonalWorkspaceDomain) SetDomain(v string)`

SetDomain sets Domain field to given value.


### GetCreatedAt

`func (o *PersonalWorkspaceDomain) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *PersonalWorkspaceDomain) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *PersonalWorkspaceDomain) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *PersonalWorkspaceDomain) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *PersonalWorkspaceDomain) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *PersonalWorkspaceDomain) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *PersonalWorkspaceDomain) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *PersonalWorkspaceDomain) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


