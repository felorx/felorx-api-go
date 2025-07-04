# CurrentTenantDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **NullableString** |  | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 
**IsAvailable** | Pointer to **bool** |  | [optional] 

## Methods

### NewCurrentTenantDto

`func NewCurrentTenantDto() *CurrentTenantDto`

NewCurrentTenantDto instantiates a new CurrentTenantDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCurrentTenantDtoWithDefaults

`func NewCurrentTenantDtoWithDefaults() *CurrentTenantDto`

NewCurrentTenantDtoWithDefaults instantiates a new CurrentTenantDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CurrentTenantDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CurrentTenantDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CurrentTenantDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CurrentTenantDto) HasId() bool`

HasId returns a boolean if a field has been set.

### SetIdNil

`func (o *CurrentTenantDto) SetIdNil(b bool)`

 SetIdNil sets the value for Id to be an explicit nil

### UnsetId
`func (o *CurrentTenantDto) UnsetId()`

UnsetId ensures that no value is present for Id, not even an explicit nil
### GetName

`func (o *CurrentTenantDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CurrentTenantDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CurrentTenantDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CurrentTenantDto) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *CurrentTenantDto) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *CurrentTenantDto) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetIsAvailable

`func (o *CurrentTenantDto) GetIsAvailable() bool`

GetIsAvailable returns the IsAvailable field if non-nil, zero value otherwise.

### GetIsAvailableOk

`func (o *CurrentTenantDto) GetIsAvailableOk() (*bool, bool)`

GetIsAvailableOk returns a tuple with the IsAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsAvailable

`func (o *CurrentTenantDto) SetIsAvailable(v bool)`

SetIsAvailable sets IsAvailable field to given value.

### HasIsAvailable

`func (o *CurrentTenantDto) HasIsAvailable() bool`

HasIsAvailable returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


