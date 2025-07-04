# IdentityUserRole

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TenantId** | Pointer to **NullableString** |  | [optional] [readonly] 
**UserId** | Pointer to **string** |  | [optional] [readonly] 
**RoleId** | Pointer to **string** |  | [optional] [readonly] 

## Methods

### NewIdentityUserRole

`func NewIdentityUserRole() *IdentityUserRole`

NewIdentityUserRole instantiates a new IdentityUserRole object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIdentityUserRoleWithDefaults

`func NewIdentityUserRoleWithDefaults() *IdentityUserRole`

NewIdentityUserRoleWithDefaults instantiates a new IdentityUserRole object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTenantId

`func (o *IdentityUserRole) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *IdentityUserRole) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *IdentityUserRole) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.

### HasTenantId

`func (o *IdentityUserRole) HasTenantId() bool`

HasTenantId returns a boolean if a field has been set.

### SetTenantIdNil

`func (o *IdentityUserRole) SetTenantIdNil(b bool)`

 SetTenantIdNil sets the value for TenantId to be an explicit nil

### UnsetTenantId
`func (o *IdentityUserRole) UnsetTenantId()`

UnsetTenantId ensures that no value is present for TenantId, not even an explicit nil
### GetUserId

`func (o *IdentityUserRole) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *IdentityUserRole) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *IdentityUserRole) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *IdentityUserRole) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetRoleId

`func (o *IdentityUserRole) GetRoleId() string`

GetRoleId returns the RoleId field if non-nil, zero value otherwise.

### GetRoleIdOk

`func (o *IdentityUserRole) GetRoleIdOk() (*string, bool)`

GetRoleIdOk returns a tuple with the RoleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoleId

`func (o *IdentityUserRole) SetRoleId(v string)`

SetRoleId sets RoleId field to given value.

### HasRoleId

`func (o *IdentityUserRole) HasRoleId() bool`

HasRoleId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


