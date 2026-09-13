# CurrentUserDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IsAuthenticated** | Pointer to **bool** |  | [optional] 
**Id** | Pointer to **NullableString** |  | [optional] 
**TenantId** | Pointer to **NullableString** |  | [optional] 
**ImpersonatorUserId** | Pointer to **NullableString** |  | [optional] 
**ImpersonatorTenantId** | Pointer to **NullableString** |  | [optional] 
**ImpersonatorUserName** | Pointer to **NullableString** |  | [optional] 
**ImpersonatorTenantName** | Pointer to **NullableString** |  | [optional] 
**UserName** | Pointer to **NullableString** |  | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 
**SurName** | Pointer to **NullableString** |  | [optional] 
**Email** | Pointer to **NullableString** |  | [optional] 
**EmailVerified** | Pointer to **bool** |  | [optional] 
**PhoneNumber** | Pointer to **NullableString** |  | [optional] 
**PhoneNumberVerified** | Pointer to **bool** |  | [optional] 
**Roles** | Pointer to **[]string** |  | [optional] 

## Methods

### NewCurrentUserDto

`func NewCurrentUserDto() *CurrentUserDto`

NewCurrentUserDto instantiates a new CurrentUserDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCurrentUserDtoWithDefaults

`func NewCurrentUserDtoWithDefaults() *CurrentUserDto`

NewCurrentUserDtoWithDefaults instantiates a new CurrentUserDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIsAuthenticated

`func (o *CurrentUserDto) GetIsAuthenticated() bool`

GetIsAuthenticated returns the IsAuthenticated field if non-nil, zero value otherwise.

### GetIsAuthenticatedOk

`func (o *CurrentUserDto) GetIsAuthenticatedOk() (*bool, bool)`

GetIsAuthenticatedOk returns a tuple with the IsAuthenticated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsAuthenticated

`func (o *CurrentUserDto) SetIsAuthenticated(v bool)`

SetIsAuthenticated sets IsAuthenticated field to given value.

### HasIsAuthenticated

`func (o *CurrentUserDto) HasIsAuthenticated() bool`

HasIsAuthenticated returns a boolean if a field has been set.

### GetId

`func (o *CurrentUserDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CurrentUserDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CurrentUserDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CurrentUserDto) HasId() bool`

HasId returns a boolean if a field has been set.

### SetIdNil

`func (o *CurrentUserDto) SetIdNil(b bool)`

 SetIdNil sets the value for Id to be an explicit nil

### UnsetId
`func (o *CurrentUserDto) UnsetId()`

UnsetId ensures that no value is present for Id, not even an explicit nil
### GetTenantId

`func (o *CurrentUserDto) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *CurrentUserDto) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *CurrentUserDto) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.

### HasTenantId

`func (o *CurrentUserDto) HasTenantId() bool`

HasTenantId returns a boolean if a field has been set.

### SetTenantIdNil

`func (o *CurrentUserDto) SetTenantIdNil(b bool)`

 SetTenantIdNil sets the value for TenantId to be an explicit nil

### UnsetTenantId
`func (o *CurrentUserDto) UnsetTenantId()`

UnsetTenantId ensures that no value is present for TenantId, not even an explicit nil
### GetImpersonatorUserId

`func (o *CurrentUserDto) GetImpersonatorUserId() string`

GetImpersonatorUserId returns the ImpersonatorUserId field if non-nil, zero value otherwise.

### GetImpersonatorUserIdOk

`func (o *CurrentUserDto) GetImpersonatorUserIdOk() (*string, bool)`

GetImpersonatorUserIdOk returns a tuple with the ImpersonatorUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImpersonatorUserId

`func (o *CurrentUserDto) SetImpersonatorUserId(v string)`

SetImpersonatorUserId sets ImpersonatorUserId field to given value.

### HasImpersonatorUserId

`func (o *CurrentUserDto) HasImpersonatorUserId() bool`

HasImpersonatorUserId returns a boolean if a field has been set.

### SetImpersonatorUserIdNil

`func (o *CurrentUserDto) SetImpersonatorUserIdNil(b bool)`

 SetImpersonatorUserIdNil sets the value for ImpersonatorUserId to be an explicit nil

### UnsetImpersonatorUserId
`func (o *CurrentUserDto) UnsetImpersonatorUserId()`

UnsetImpersonatorUserId ensures that no value is present for ImpersonatorUserId, not even an explicit nil
### GetImpersonatorTenantId

`func (o *CurrentUserDto) GetImpersonatorTenantId() string`

GetImpersonatorTenantId returns the ImpersonatorTenantId field if non-nil, zero value otherwise.

### GetImpersonatorTenantIdOk

`func (o *CurrentUserDto) GetImpersonatorTenantIdOk() (*string, bool)`

GetImpersonatorTenantIdOk returns a tuple with the ImpersonatorTenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImpersonatorTenantId

`func (o *CurrentUserDto) SetImpersonatorTenantId(v string)`

SetImpersonatorTenantId sets ImpersonatorTenantId field to given value.

### HasImpersonatorTenantId

`func (o *CurrentUserDto) HasImpersonatorTenantId() bool`

HasImpersonatorTenantId returns a boolean if a field has been set.

### SetImpersonatorTenantIdNil

`func (o *CurrentUserDto) SetImpersonatorTenantIdNil(b bool)`

 SetImpersonatorTenantIdNil sets the value for ImpersonatorTenantId to be an explicit nil

### UnsetImpersonatorTenantId
`func (o *CurrentUserDto) UnsetImpersonatorTenantId()`

UnsetImpersonatorTenantId ensures that no value is present for ImpersonatorTenantId, not even an explicit nil
### GetImpersonatorUserName

`func (o *CurrentUserDto) GetImpersonatorUserName() string`

GetImpersonatorUserName returns the ImpersonatorUserName field if non-nil, zero value otherwise.

### GetImpersonatorUserNameOk

`func (o *CurrentUserDto) GetImpersonatorUserNameOk() (*string, bool)`

GetImpersonatorUserNameOk returns a tuple with the ImpersonatorUserName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImpersonatorUserName

`func (o *CurrentUserDto) SetImpersonatorUserName(v string)`

SetImpersonatorUserName sets ImpersonatorUserName field to given value.

### HasImpersonatorUserName

`func (o *CurrentUserDto) HasImpersonatorUserName() bool`

HasImpersonatorUserName returns a boolean if a field has been set.

### SetImpersonatorUserNameNil

`func (o *CurrentUserDto) SetImpersonatorUserNameNil(b bool)`

 SetImpersonatorUserNameNil sets the value for ImpersonatorUserName to be an explicit nil

### UnsetImpersonatorUserName
`func (o *CurrentUserDto) UnsetImpersonatorUserName()`

UnsetImpersonatorUserName ensures that no value is present for ImpersonatorUserName, not even an explicit nil
### GetImpersonatorTenantName

`func (o *CurrentUserDto) GetImpersonatorTenantName() string`

GetImpersonatorTenantName returns the ImpersonatorTenantName field if non-nil, zero value otherwise.

### GetImpersonatorTenantNameOk

`func (o *CurrentUserDto) GetImpersonatorTenantNameOk() (*string, bool)`

GetImpersonatorTenantNameOk returns a tuple with the ImpersonatorTenantName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImpersonatorTenantName

`func (o *CurrentUserDto) SetImpersonatorTenantName(v string)`

SetImpersonatorTenantName sets ImpersonatorTenantName field to given value.

### HasImpersonatorTenantName

`func (o *CurrentUserDto) HasImpersonatorTenantName() bool`

HasImpersonatorTenantName returns a boolean if a field has been set.

### SetImpersonatorTenantNameNil

`func (o *CurrentUserDto) SetImpersonatorTenantNameNil(b bool)`

 SetImpersonatorTenantNameNil sets the value for ImpersonatorTenantName to be an explicit nil

### UnsetImpersonatorTenantName
`func (o *CurrentUserDto) UnsetImpersonatorTenantName()`

UnsetImpersonatorTenantName ensures that no value is present for ImpersonatorTenantName, not even an explicit nil
### GetUserName

`func (o *CurrentUserDto) GetUserName() string`

GetUserName returns the UserName field if non-nil, zero value otherwise.

### GetUserNameOk

`func (o *CurrentUserDto) GetUserNameOk() (*string, bool)`

GetUserNameOk returns a tuple with the UserName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserName

`func (o *CurrentUserDto) SetUserName(v string)`

SetUserName sets UserName field to given value.

### HasUserName

`func (o *CurrentUserDto) HasUserName() bool`

HasUserName returns a boolean if a field has been set.

### SetUserNameNil

`func (o *CurrentUserDto) SetUserNameNil(b bool)`

 SetUserNameNil sets the value for UserName to be an explicit nil

### UnsetUserName
`func (o *CurrentUserDto) UnsetUserName()`

UnsetUserName ensures that no value is present for UserName, not even an explicit nil
### GetName

`func (o *CurrentUserDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CurrentUserDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CurrentUserDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CurrentUserDto) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *CurrentUserDto) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *CurrentUserDto) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetSurName

`func (o *CurrentUserDto) GetSurName() string`

GetSurName returns the SurName field if non-nil, zero value otherwise.

### GetSurNameOk

`func (o *CurrentUserDto) GetSurNameOk() (*string, bool)`

GetSurNameOk returns a tuple with the SurName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSurName

`func (o *CurrentUserDto) SetSurName(v string)`

SetSurName sets SurName field to given value.

### HasSurName

`func (o *CurrentUserDto) HasSurName() bool`

HasSurName returns a boolean if a field has been set.

### SetSurNameNil

`func (o *CurrentUserDto) SetSurNameNil(b bool)`

 SetSurNameNil sets the value for SurName to be an explicit nil

### UnsetSurName
`func (o *CurrentUserDto) UnsetSurName()`

UnsetSurName ensures that no value is present for SurName, not even an explicit nil
### GetEmail

`func (o *CurrentUserDto) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CurrentUserDto) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CurrentUserDto) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *CurrentUserDto) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### SetEmailNil

`func (o *CurrentUserDto) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *CurrentUserDto) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil
### GetEmailVerified

`func (o *CurrentUserDto) GetEmailVerified() bool`

GetEmailVerified returns the EmailVerified field if non-nil, zero value otherwise.

### GetEmailVerifiedOk

`func (o *CurrentUserDto) GetEmailVerifiedOk() (*bool, bool)`

GetEmailVerifiedOk returns a tuple with the EmailVerified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailVerified

`func (o *CurrentUserDto) SetEmailVerified(v bool)`

SetEmailVerified sets EmailVerified field to given value.

### HasEmailVerified

`func (o *CurrentUserDto) HasEmailVerified() bool`

HasEmailVerified returns a boolean if a field has been set.

### GetPhoneNumber

`func (o *CurrentUserDto) GetPhoneNumber() string`

GetPhoneNumber returns the PhoneNumber field if non-nil, zero value otherwise.

### GetPhoneNumberOk

`func (o *CurrentUserDto) GetPhoneNumberOk() (*string, bool)`

GetPhoneNumberOk returns a tuple with the PhoneNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhoneNumber

`func (o *CurrentUserDto) SetPhoneNumber(v string)`

SetPhoneNumber sets PhoneNumber field to given value.

### HasPhoneNumber

`func (o *CurrentUserDto) HasPhoneNumber() bool`

HasPhoneNumber returns a boolean if a field has been set.

### SetPhoneNumberNil

`func (o *CurrentUserDto) SetPhoneNumberNil(b bool)`

 SetPhoneNumberNil sets the value for PhoneNumber to be an explicit nil

### UnsetPhoneNumber
`func (o *CurrentUserDto) UnsetPhoneNumber()`

UnsetPhoneNumber ensures that no value is present for PhoneNumber, not even an explicit nil
### GetPhoneNumberVerified

`func (o *CurrentUserDto) GetPhoneNumberVerified() bool`

GetPhoneNumberVerified returns the PhoneNumberVerified field if non-nil, zero value otherwise.

### GetPhoneNumberVerifiedOk

`func (o *CurrentUserDto) GetPhoneNumberVerifiedOk() (*bool, bool)`

GetPhoneNumberVerifiedOk returns a tuple with the PhoneNumberVerified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhoneNumberVerified

`func (o *CurrentUserDto) SetPhoneNumberVerified(v bool)`

SetPhoneNumberVerified sets PhoneNumberVerified field to given value.

### HasPhoneNumberVerified

`func (o *CurrentUserDto) HasPhoneNumberVerified() bool`

HasPhoneNumberVerified returns a boolean if a field has been set.

### GetRoles

`func (o *CurrentUserDto) GetRoles() []string`

GetRoles returns the Roles field if non-nil, zero value otherwise.

### GetRolesOk

`func (o *CurrentUserDto) GetRolesOk() (*[]string, bool)`

GetRolesOk returns a tuple with the Roles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoles

`func (o *CurrentUserDto) SetRoles(v []string)`

SetRoles sets Roles field to given value.

### HasRoles

`func (o *CurrentUserDto) HasRoles() bool`

HasRoles returns a boolean if a field has been set.

### SetRolesNil

`func (o *CurrentUserDto) SetRolesNil(b bool)`

 SetRolesNil sets the value for Roles to be an explicit nil

### UnsetRoles
`func (o *CurrentUserDto) UnsetRoles()`

UnsetRoles ensures that no value is present for Roles, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


