# PartnerDataDatabase

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PartnerId** | **string** |  | 
**Host** | **string** | The Neon host of the database, as it appears in its connection string (&#x60;ep-....neon.tech&#x60;). | 
**DatabaseName** | **string** | The name of the database in your Neon project. | 
**RoleName** | **string** | The role Widgetic connects as. | 
**VerifiedAt** | **time.Time** | When the database last passed the check. | 
**LastVerificationError** | **NullableString** | Why the latest re-check failed, in a sentence you can act on. Null when the last check passed. | 
**LastVerificationFailedAt** | **NullableTime** | When the latest re-check failed. Null when the last check passed. | 
**UpdatedAt** | **time.Time** |  | 

## Methods

### NewPartnerDataDatabase

`func NewPartnerDataDatabase(partnerId string, host string, databaseName string, roleName string, verifiedAt time.Time, lastVerificationError NullableString, lastVerificationFailedAt NullableTime, updatedAt time.Time, ) *PartnerDataDatabase`

NewPartnerDataDatabase instantiates a new PartnerDataDatabase object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPartnerDataDatabaseWithDefaults

`func NewPartnerDataDatabaseWithDefaults() *PartnerDataDatabase`

NewPartnerDataDatabaseWithDefaults instantiates a new PartnerDataDatabase object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPartnerId

`func (o *PartnerDataDatabase) GetPartnerId() string`

GetPartnerId returns the PartnerId field if non-nil, zero value otherwise.

### GetPartnerIdOk

`func (o *PartnerDataDatabase) GetPartnerIdOk() (*string, bool)`

GetPartnerIdOk returns a tuple with the PartnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartnerId

`func (o *PartnerDataDatabase) SetPartnerId(v string)`

SetPartnerId sets PartnerId field to given value.


### GetHost

`func (o *PartnerDataDatabase) GetHost() string`

GetHost returns the Host field if non-nil, zero value otherwise.

### GetHostOk

`func (o *PartnerDataDatabase) GetHostOk() (*string, bool)`

GetHostOk returns a tuple with the Host field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHost

`func (o *PartnerDataDatabase) SetHost(v string)`

SetHost sets Host field to given value.


### GetDatabaseName

`func (o *PartnerDataDatabase) GetDatabaseName() string`

GetDatabaseName returns the DatabaseName field if non-nil, zero value otherwise.

### GetDatabaseNameOk

`func (o *PartnerDataDatabase) GetDatabaseNameOk() (*string, bool)`

GetDatabaseNameOk returns a tuple with the DatabaseName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatabaseName

`func (o *PartnerDataDatabase) SetDatabaseName(v string)`

SetDatabaseName sets DatabaseName field to given value.


### GetRoleName

`func (o *PartnerDataDatabase) GetRoleName() string`

GetRoleName returns the RoleName field if non-nil, zero value otherwise.

### GetRoleNameOk

`func (o *PartnerDataDatabase) GetRoleNameOk() (*string, bool)`

GetRoleNameOk returns a tuple with the RoleName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoleName

`func (o *PartnerDataDatabase) SetRoleName(v string)`

SetRoleName sets RoleName field to given value.


### GetVerifiedAt

`func (o *PartnerDataDatabase) GetVerifiedAt() time.Time`

GetVerifiedAt returns the VerifiedAt field if non-nil, zero value otherwise.

### GetVerifiedAtOk

`func (o *PartnerDataDatabase) GetVerifiedAtOk() (*time.Time, bool)`

GetVerifiedAtOk returns a tuple with the VerifiedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerifiedAt

`func (o *PartnerDataDatabase) SetVerifiedAt(v time.Time)`

SetVerifiedAt sets VerifiedAt field to given value.


### GetLastVerificationError

`func (o *PartnerDataDatabase) GetLastVerificationError() string`

GetLastVerificationError returns the LastVerificationError field if non-nil, zero value otherwise.

### GetLastVerificationErrorOk

`func (o *PartnerDataDatabase) GetLastVerificationErrorOk() (*string, bool)`

GetLastVerificationErrorOk returns a tuple with the LastVerificationError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastVerificationError

`func (o *PartnerDataDatabase) SetLastVerificationError(v string)`

SetLastVerificationError sets LastVerificationError field to given value.


### SetLastVerificationErrorNil

`func (o *PartnerDataDatabase) SetLastVerificationErrorNil(b bool)`

 SetLastVerificationErrorNil sets the value for LastVerificationError to be an explicit nil

### UnsetLastVerificationError
`func (o *PartnerDataDatabase) UnsetLastVerificationError()`

UnsetLastVerificationError ensures that no value is present for LastVerificationError, not even an explicit nil
### GetLastVerificationFailedAt

`func (o *PartnerDataDatabase) GetLastVerificationFailedAt() time.Time`

GetLastVerificationFailedAt returns the LastVerificationFailedAt field if non-nil, zero value otherwise.

### GetLastVerificationFailedAtOk

`func (o *PartnerDataDatabase) GetLastVerificationFailedAtOk() (*time.Time, bool)`

GetLastVerificationFailedAtOk returns a tuple with the LastVerificationFailedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastVerificationFailedAt

`func (o *PartnerDataDatabase) SetLastVerificationFailedAt(v time.Time)`

SetLastVerificationFailedAt sets LastVerificationFailedAt field to given value.


### SetLastVerificationFailedAtNil

`func (o *PartnerDataDatabase) SetLastVerificationFailedAtNil(b bool)`

 SetLastVerificationFailedAtNil sets the value for LastVerificationFailedAt to be an explicit nil

### UnsetLastVerificationFailedAt
`func (o *PartnerDataDatabase) UnsetLastVerificationFailedAt()`

UnsetLastVerificationFailedAt ensures that no value is present for LastVerificationFailedAt, not even an explicit nil
### GetUpdatedAt

`func (o *PartnerDataDatabase) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *PartnerDataDatabase) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *PartnerDataDatabase) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


