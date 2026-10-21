# SetPartnerDataDatabaseRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConnectionString** | **string** | The connection string of a Neon database and role you made for this, as Neon shows it under Connect: &#x60;postgresql://&lt;role&gt;:&lt;password&gt;@ep-&lt;name&gt;.&lt;region&gt;.aws.neon.tech/&lt;database&gt;&#x60;. Either the direct or the pooled host works. Everything after the database name (&#x60;?sslmode&#x3D;...&#x60;) is ignored. It is stored encrypted and is never returned or logged. | 

## Methods

### NewSetPartnerDataDatabaseRequest

`func NewSetPartnerDataDatabaseRequest(connectionString string, ) *SetPartnerDataDatabaseRequest`

NewSetPartnerDataDatabaseRequest instantiates a new SetPartnerDataDatabaseRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSetPartnerDataDatabaseRequestWithDefaults

`func NewSetPartnerDataDatabaseRequestWithDefaults() *SetPartnerDataDatabaseRequest`

NewSetPartnerDataDatabaseRequestWithDefaults instantiates a new SetPartnerDataDatabaseRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConnectionString

`func (o *SetPartnerDataDatabaseRequest) GetConnectionString() string`

GetConnectionString returns the ConnectionString field if non-nil, zero value otherwise.

### GetConnectionStringOk

`func (o *SetPartnerDataDatabaseRequest) GetConnectionStringOk() (*string, bool)`

GetConnectionStringOk returns a tuple with the ConnectionString field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnectionString

`func (o *SetPartnerDataDatabaseRequest) SetConnectionString(v string)`

SetConnectionString sets ConnectionString field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


