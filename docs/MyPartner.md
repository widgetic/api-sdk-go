# MyPartner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | The id every other partner route asks for (&#x60;/partners/{partnerId}/...&#x60;) | 
**Name** | **string** |  | 
**Status** | **string** | &#x60;active&#x60; while the partner is in force. &#x60;inactive&#x60; until Widgetic activates it (and after a deactivation). &#x60;suspended&#x60; while it is paused, which is done by hand and comes back when Widgetic resumes it.  | 
**ContactEmail** | Pointer to **NullableString** |  | [optional] 
**AllowedDomains** | **[]string** | The domains Widgetic added to the embeds of this partner&#39;s customers. The domains the person added themselves are on the domains route of the account.  | 
**PlatformDomain** | **NullableString** | The website where the partner integrates Widgetic, as a bare name. It and every subdomain of it (&#x60;app.acme.com&#x60;, &#x60;learn.eu.acme.com&#x60;) can always show the partner&#39;s widgets, the ones its customers make through it included, and send entries to them, whatever &#x60;allowedDomains&#x60; and the account&#39;s own domain list say, so a list can never lock the partner&#39;s own website out. It is not an entry of &#x60;allowedDomains&#x60;, and it does not turn an empty list into a restriction: a partner that lists nothing stays unrestricted for every website. Widgetic sets it when the partner is set up; contact Widgetic to change it. &#x60;null&#x60; when none has been set.  | 
**SuspendedAt** | **NullableTime** | When the partner was paused; null unless it is paused now | 
**SuspensionReason** | **NullableString** | The reason given when the partner was paused, as the partner is told it; null unless it is paused now | 
**CreatedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewMyPartner

`func NewMyPartner(id string, name string, status string, allowedDomains []string, platformDomain NullableString, suspendedAt NullableTime, suspensionReason NullableString, ) *MyPartner`

NewMyPartner instantiates a new MyPartner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMyPartnerWithDefaults

`func NewMyPartnerWithDefaults() *MyPartner`

NewMyPartnerWithDefaults instantiates a new MyPartner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *MyPartner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *MyPartner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *MyPartner) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *MyPartner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *MyPartner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *MyPartner) SetName(v string)`

SetName sets Name field to given value.


### GetStatus

`func (o *MyPartner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *MyPartner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *MyPartner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetContactEmail

`func (o *MyPartner) GetContactEmail() string`

GetContactEmail returns the ContactEmail field if non-nil, zero value otherwise.

### GetContactEmailOk

`func (o *MyPartner) GetContactEmailOk() (*string, bool)`

GetContactEmailOk returns a tuple with the ContactEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactEmail

`func (o *MyPartner) SetContactEmail(v string)`

SetContactEmail sets ContactEmail field to given value.

### HasContactEmail

`func (o *MyPartner) HasContactEmail() bool`

HasContactEmail returns a boolean if a field has been set.

### SetContactEmailNil

`func (o *MyPartner) SetContactEmailNil(b bool)`

 SetContactEmailNil sets the value for ContactEmail to be an explicit nil

### UnsetContactEmail
`func (o *MyPartner) UnsetContactEmail()`

UnsetContactEmail ensures that no value is present for ContactEmail, not even an explicit nil
### GetAllowedDomains

`func (o *MyPartner) GetAllowedDomains() []string`

GetAllowedDomains returns the AllowedDomains field if non-nil, zero value otherwise.

### GetAllowedDomainsOk

`func (o *MyPartner) GetAllowedDomainsOk() (*[]string, bool)`

GetAllowedDomainsOk returns a tuple with the AllowedDomains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowedDomains

`func (o *MyPartner) SetAllowedDomains(v []string)`

SetAllowedDomains sets AllowedDomains field to given value.


### GetPlatformDomain

`func (o *MyPartner) GetPlatformDomain() string`

GetPlatformDomain returns the PlatformDomain field if non-nil, zero value otherwise.

### GetPlatformDomainOk

`func (o *MyPartner) GetPlatformDomainOk() (*string, bool)`

GetPlatformDomainOk returns a tuple with the PlatformDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatformDomain

`func (o *MyPartner) SetPlatformDomain(v string)`

SetPlatformDomain sets PlatformDomain field to given value.


### SetPlatformDomainNil

`func (o *MyPartner) SetPlatformDomainNil(b bool)`

 SetPlatformDomainNil sets the value for PlatformDomain to be an explicit nil

### UnsetPlatformDomain
`func (o *MyPartner) UnsetPlatformDomain()`

UnsetPlatformDomain ensures that no value is present for PlatformDomain, not even an explicit nil
### GetSuspendedAt

`func (o *MyPartner) GetSuspendedAt() time.Time`

GetSuspendedAt returns the SuspendedAt field if non-nil, zero value otherwise.

### GetSuspendedAtOk

`func (o *MyPartner) GetSuspendedAtOk() (*time.Time, bool)`

GetSuspendedAtOk returns a tuple with the SuspendedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuspendedAt

`func (o *MyPartner) SetSuspendedAt(v time.Time)`

SetSuspendedAt sets SuspendedAt field to given value.


### SetSuspendedAtNil

`func (o *MyPartner) SetSuspendedAtNil(b bool)`

 SetSuspendedAtNil sets the value for SuspendedAt to be an explicit nil

### UnsetSuspendedAt
`func (o *MyPartner) UnsetSuspendedAt()`

UnsetSuspendedAt ensures that no value is present for SuspendedAt, not even an explicit nil
### GetSuspensionReason

`func (o *MyPartner) GetSuspensionReason() string`

GetSuspensionReason returns the SuspensionReason field if non-nil, zero value otherwise.

### GetSuspensionReasonOk

`func (o *MyPartner) GetSuspensionReasonOk() (*string, bool)`

GetSuspensionReasonOk returns a tuple with the SuspensionReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuspensionReason

`func (o *MyPartner) SetSuspensionReason(v string)`

SetSuspensionReason sets SuspensionReason field to given value.


### SetSuspensionReasonNil

`func (o *MyPartner) SetSuspensionReasonNil(b bool)`

 SetSuspensionReasonNil sets the value for SuspensionReason to be an explicit nil

### UnsetSuspensionReason
`func (o *MyPartner) UnsetSuspensionReason()`

UnsetSuspensionReason ensures that no value is present for SuspensionReason, not even an explicit nil
### GetCreatedAt

`func (o *MyPartner) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *MyPartner) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *MyPartner) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *MyPartner) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *MyPartner) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *MyPartner) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


