# IdentityUserCreateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExtraProperties** | Pointer to **map[string]interface{}** |  | [optional] [readonly] 
**UserName** | **string** |  | 
**Name** | Pointer to **NullableString** |  | [optional] 
**Surname** | Pointer to **NullableString** |  | [optional] 
**Email** | **string** |  | 
**PhoneNumber** | Pointer to **NullableString** |  | [optional] 
**IsActive** | Pointer to **bool** |  | [optional] 
**LockoutEnabled** | Pointer to **bool** |  | [optional] 
**RoleNames** | Pointer to **[]string** |  | [optional] 
**Password** | **string** |  | 

## Methods

### NewIdentityUserCreateDto

`func NewIdentityUserCreateDto(userName string, email string, password string, ) *IdentityUserCreateDto`

NewIdentityUserCreateDto instantiates a new IdentityUserCreateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIdentityUserCreateDtoWithDefaults

`func NewIdentityUserCreateDtoWithDefaults() *IdentityUserCreateDto`

NewIdentityUserCreateDtoWithDefaults instantiates a new IdentityUserCreateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExtraProperties

`func (o *IdentityUserCreateDto) GetExtraProperties() map[string]interface{}`

GetExtraProperties returns the ExtraProperties field if non-nil, zero value otherwise.

### GetExtraPropertiesOk

`func (o *IdentityUserCreateDto) GetExtraPropertiesOk() (*map[string]interface{}, bool)`

GetExtraPropertiesOk returns a tuple with the ExtraProperties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtraProperties

`func (o *IdentityUserCreateDto) SetExtraProperties(v map[string]interface{})`

SetExtraProperties sets ExtraProperties field to given value.

### HasExtraProperties

`func (o *IdentityUserCreateDto) HasExtraProperties() bool`

HasExtraProperties returns a boolean if a field has been set.

### SetExtraPropertiesNil

`func (o *IdentityUserCreateDto) SetExtraPropertiesNil(b bool)`

 SetExtraPropertiesNil sets the value for ExtraProperties to be an explicit nil

### UnsetExtraProperties
`func (o *IdentityUserCreateDto) UnsetExtraProperties()`

UnsetExtraProperties ensures that no value is present for ExtraProperties, not even an explicit nil
### GetUserName

`func (o *IdentityUserCreateDto) GetUserName() string`

GetUserName returns the UserName field if non-nil, zero value otherwise.

### GetUserNameOk

`func (o *IdentityUserCreateDto) GetUserNameOk() (*string, bool)`

GetUserNameOk returns a tuple with the UserName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserName

`func (o *IdentityUserCreateDto) SetUserName(v string)`

SetUserName sets UserName field to given value.


### GetName

`func (o *IdentityUserCreateDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *IdentityUserCreateDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *IdentityUserCreateDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *IdentityUserCreateDto) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *IdentityUserCreateDto) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *IdentityUserCreateDto) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetSurname

`func (o *IdentityUserCreateDto) GetSurname() string`

GetSurname returns the Surname field if non-nil, zero value otherwise.

### GetSurnameOk

`func (o *IdentityUserCreateDto) GetSurnameOk() (*string, bool)`

GetSurnameOk returns a tuple with the Surname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSurname

`func (o *IdentityUserCreateDto) SetSurname(v string)`

SetSurname sets Surname field to given value.

### HasSurname

`func (o *IdentityUserCreateDto) HasSurname() bool`

HasSurname returns a boolean if a field has been set.

### SetSurnameNil

`func (o *IdentityUserCreateDto) SetSurnameNil(b bool)`

 SetSurnameNil sets the value for Surname to be an explicit nil

### UnsetSurname
`func (o *IdentityUserCreateDto) UnsetSurname()`

UnsetSurname ensures that no value is present for Surname, not even an explicit nil
### GetEmail

`func (o *IdentityUserCreateDto) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *IdentityUserCreateDto) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *IdentityUserCreateDto) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetPhoneNumber

`func (o *IdentityUserCreateDto) GetPhoneNumber() string`

GetPhoneNumber returns the PhoneNumber field if non-nil, zero value otherwise.

### GetPhoneNumberOk

`func (o *IdentityUserCreateDto) GetPhoneNumberOk() (*string, bool)`

GetPhoneNumberOk returns a tuple with the PhoneNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhoneNumber

`func (o *IdentityUserCreateDto) SetPhoneNumber(v string)`

SetPhoneNumber sets PhoneNumber field to given value.

### HasPhoneNumber

`func (o *IdentityUserCreateDto) HasPhoneNumber() bool`

HasPhoneNumber returns a boolean if a field has been set.

### SetPhoneNumberNil

`func (o *IdentityUserCreateDto) SetPhoneNumberNil(b bool)`

 SetPhoneNumberNil sets the value for PhoneNumber to be an explicit nil

### UnsetPhoneNumber
`func (o *IdentityUserCreateDto) UnsetPhoneNumber()`

UnsetPhoneNumber ensures that no value is present for PhoneNumber, not even an explicit nil
### GetIsActive

`func (o *IdentityUserCreateDto) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *IdentityUserCreateDto) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *IdentityUserCreateDto) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *IdentityUserCreateDto) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### GetLockoutEnabled

`func (o *IdentityUserCreateDto) GetLockoutEnabled() bool`

GetLockoutEnabled returns the LockoutEnabled field if non-nil, zero value otherwise.

### GetLockoutEnabledOk

`func (o *IdentityUserCreateDto) GetLockoutEnabledOk() (*bool, bool)`

GetLockoutEnabledOk returns a tuple with the LockoutEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLockoutEnabled

`func (o *IdentityUserCreateDto) SetLockoutEnabled(v bool)`

SetLockoutEnabled sets LockoutEnabled field to given value.

### HasLockoutEnabled

`func (o *IdentityUserCreateDto) HasLockoutEnabled() bool`

HasLockoutEnabled returns a boolean if a field has been set.

### GetRoleNames

`func (o *IdentityUserCreateDto) GetRoleNames() []string`

GetRoleNames returns the RoleNames field if non-nil, zero value otherwise.

### GetRoleNamesOk

`func (o *IdentityUserCreateDto) GetRoleNamesOk() (*[]string, bool)`

GetRoleNamesOk returns a tuple with the RoleNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoleNames

`func (o *IdentityUserCreateDto) SetRoleNames(v []string)`

SetRoleNames sets RoleNames field to given value.

### HasRoleNames

`func (o *IdentityUserCreateDto) HasRoleNames() bool`

HasRoleNames returns a boolean if a field has been set.

### SetRoleNamesNil

`func (o *IdentityUserCreateDto) SetRoleNamesNil(b bool)`

 SetRoleNamesNil sets the value for RoleNames to be an explicit nil

### UnsetRoleNames
`func (o *IdentityUserCreateDto) UnsetRoleNames()`

UnsetRoleNames ensures that no value is present for RoleNames, not even an explicit nil
### GetPassword

`func (o *IdentityUserCreateDto) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *IdentityUserCreateDto) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *IdentityUserCreateDto) SetPassword(v string)`

SetPassword sets Password field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


