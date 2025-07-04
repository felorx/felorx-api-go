# IdentityUserClaim

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] [readonly] 
**TenantId** | Pointer to **NullableString** |  | [optional] [readonly] 
**ClaimType** | Pointer to **NullableString** |  | [optional] [readonly] 
**ClaimValue** | Pointer to **NullableString** |  | [optional] [readonly] 
**UserId** | Pointer to **string** |  | [optional] 

## Methods

### NewIdentityUserClaim

`func NewIdentityUserClaim() *IdentityUserClaim`

NewIdentityUserClaim instantiates a new IdentityUserClaim object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIdentityUserClaimWithDefaults

`func NewIdentityUserClaimWithDefaults() *IdentityUserClaim`

NewIdentityUserClaimWithDefaults instantiates a new IdentityUserClaim object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *IdentityUserClaim) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *IdentityUserClaim) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *IdentityUserClaim) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *IdentityUserClaim) HasId() bool`

HasId returns a boolean if a field has been set.

### GetTenantId

`func (o *IdentityUserClaim) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *IdentityUserClaim) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *IdentityUserClaim) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.

### HasTenantId

`func (o *IdentityUserClaim) HasTenantId() bool`

HasTenantId returns a boolean if a field has been set.

### SetTenantIdNil

`func (o *IdentityUserClaim) SetTenantIdNil(b bool)`

 SetTenantIdNil sets the value for TenantId to be an explicit nil

### UnsetTenantId
`func (o *IdentityUserClaim) UnsetTenantId()`

UnsetTenantId ensures that no value is present for TenantId, not even an explicit nil
### GetClaimType

`func (o *IdentityUserClaim) GetClaimType() string`

GetClaimType returns the ClaimType field if non-nil, zero value otherwise.

### GetClaimTypeOk

`func (o *IdentityUserClaim) GetClaimTypeOk() (*string, bool)`

GetClaimTypeOk returns a tuple with the ClaimType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClaimType

`func (o *IdentityUserClaim) SetClaimType(v string)`

SetClaimType sets ClaimType field to given value.

### HasClaimType

`func (o *IdentityUserClaim) HasClaimType() bool`

HasClaimType returns a boolean if a field has been set.

### SetClaimTypeNil

`func (o *IdentityUserClaim) SetClaimTypeNil(b bool)`

 SetClaimTypeNil sets the value for ClaimType to be an explicit nil

### UnsetClaimType
`func (o *IdentityUserClaim) UnsetClaimType()`

UnsetClaimType ensures that no value is present for ClaimType, not even an explicit nil
### GetClaimValue

`func (o *IdentityUserClaim) GetClaimValue() string`

GetClaimValue returns the ClaimValue field if non-nil, zero value otherwise.

### GetClaimValueOk

`func (o *IdentityUserClaim) GetClaimValueOk() (*string, bool)`

GetClaimValueOk returns a tuple with the ClaimValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClaimValue

`func (o *IdentityUserClaim) SetClaimValue(v string)`

SetClaimValue sets ClaimValue field to given value.

### HasClaimValue

`func (o *IdentityUserClaim) HasClaimValue() bool`

HasClaimValue returns a boolean if a field has been set.

### SetClaimValueNil

`func (o *IdentityUserClaim) SetClaimValueNil(b bool)`

 SetClaimValueNil sets the value for ClaimValue to be an explicit nil

### UnsetClaimValue
`func (o *IdentityUserClaim) UnsetClaimValue()`

UnsetClaimValue ensures that no value is present for ClaimValue, not even an explicit nil
### GetUserId

`func (o *IdentityUserClaim) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *IdentityUserClaim) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *IdentityUserClaim) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *IdentityUserClaim) HasUserId() bool`

HasUserId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


