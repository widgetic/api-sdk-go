# DuplicateCompositionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | Optional new name for the duplicate (defaults to \&quot;Copy of [original name]\&quot;) | [optional] 
**IncludeDatabase** | Pointer to **bool** | Whether the duplicate gets the tables the original declares (&#x60;databaseSchema&#x60;), empty and in a schema of their own (default false). What visitors left in the original is never copied, and the duplicate never shares the original&#39;s data.  | [optional] [default to false]

## Methods

### NewDuplicateCompositionRequest

`func NewDuplicateCompositionRequest() *DuplicateCompositionRequest`

NewDuplicateCompositionRequest instantiates a new DuplicateCompositionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDuplicateCompositionRequestWithDefaults

`func NewDuplicateCompositionRequestWithDefaults() *DuplicateCompositionRequest`

NewDuplicateCompositionRequestWithDefaults instantiates a new DuplicateCompositionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *DuplicateCompositionRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *DuplicateCompositionRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *DuplicateCompositionRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *DuplicateCompositionRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetIncludeDatabase

`func (o *DuplicateCompositionRequest) GetIncludeDatabase() bool`

GetIncludeDatabase returns the IncludeDatabase field if non-nil, zero value otherwise.

### GetIncludeDatabaseOk

`func (o *DuplicateCompositionRequest) GetIncludeDatabaseOk() (*bool, bool)`

GetIncludeDatabaseOk returns a tuple with the IncludeDatabase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeDatabase

`func (o *DuplicateCompositionRequest) SetIncludeDatabase(v bool)`

SetIncludeDatabase sets IncludeDatabase field to given value.

### HasIncludeDatabase

`func (o *DuplicateCompositionRequest) HasIncludeDatabase() bool`

HasIncludeDatabase returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


