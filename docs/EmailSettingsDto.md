# EmailSettingsDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SmtpHost** | Pointer to **NullableString** |  | [optional] 
**SmtpPort** | Pointer to **int32** |  | [optional] 
**SmtpUserName** | Pointer to **NullableString** |  | [optional] 
**SmtpPassword** | Pointer to **NullableString** |  | [optional] 
**SmtpDomain** | Pointer to **NullableString** |  | [optional] 
**SmtpEnableSsl** | Pointer to **bool** |  | [optional] 
**SmtpUseDefaultCredentials** | Pointer to **bool** |  | [optional] 
**DefaultFromAddress** | Pointer to **NullableString** |  | [optional] 
**DefaultFromDisplayName** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewEmailSettingsDto

`func NewEmailSettingsDto() *EmailSettingsDto`

NewEmailSettingsDto instantiates a new EmailSettingsDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEmailSettingsDtoWithDefaults

`func NewEmailSettingsDtoWithDefaults() *EmailSettingsDto`

NewEmailSettingsDtoWithDefaults instantiates a new EmailSettingsDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSmtpHost

`func (o *EmailSettingsDto) GetSmtpHost() string`

GetSmtpHost returns the SmtpHost field if non-nil, zero value otherwise.

### GetSmtpHostOk

`func (o *EmailSettingsDto) GetSmtpHostOk() (*string, bool)`

GetSmtpHostOk returns a tuple with the SmtpHost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmtpHost

`func (o *EmailSettingsDto) SetSmtpHost(v string)`

SetSmtpHost sets SmtpHost field to given value.

### HasSmtpHost

`func (o *EmailSettingsDto) HasSmtpHost() bool`

HasSmtpHost returns a boolean if a field has been set.

### SetSmtpHostNil

`func (o *EmailSettingsDto) SetSmtpHostNil(b bool)`

 SetSmtpHostNil sets the value for SmtpHost to be an explicit nil

### UnsetSmtpHost
`func (o *EmailSettingsDto) UnsetSmtpHost()`

UnsetSmtpHost ensures that no value is present for SmtpHost, not even an explicit nil
### GetSmtpPort

`func (o *EmailSettingsDto) GetSmtpPort() int32`

GetSmtpPort returns the SmtpPort field if non-nil, zero value otherwise.

### GetSmtpPortOk

`func (o *EmailSettingsDto) GetSmtpPortOk() (*int32, bool)`

GetSmtpPortOk returns a tuple with the SmtpPort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmtpPort

`func (o *EmailSettingsDto) SetSmtpPort(v int32)`

SetSmtpPort sets SmtpPort field to given value.

### HasSmtpPort

`func (o *EmailSettingsDto) HasSmtpPort() bool`

HasSmtpPort returns a boolean if a field has been set.

### GetSmtpUserName

`func (o *EmailSettingsDto) GetSmtpUserName() string`

GetSmtpUserName returns the SmtpUserName field if non-nil, zero value otherwise.

### GetSmtpUserNameOk

`func (o *EmailSettingsDto) GetSmtpUserNameOk() (*string, bool)`

GetSmtpUserNameOk returns a tuple with the SmtpUserName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmtpUserName

`func (o *EmailSettingsDto) SetSmtpUserName(v string)`

SetSmtpUserName sets SmtpUserName field to given value.

### HasSmtpUserName

`func (o *EmailSettingsDto) HasSmtpUserName() bool`

HasSmtpUserName returns a boolean if a field has been set.

### SetSmtpUserNameNil

`func (o *EmailSettingsDto) SetSmtpUserNameNil(b bool)`

 SetSmtpUserNameNil sets the value for SmtpUserName to be an explicit nil

### UnsetSmtpUserName
`func (o *EmailSettingsDto) UnsetSmtpUserName()`

UnsetSmtpUserName ensures that no value is present for SmtpUserName, not even an explicit nil
### GetSmtpPassword

`func (o *EmailSettingsDto) GetSmtpPassword() string`

GetSmtpPassword returns the SmtpPassword field if non-nil, zero value otherwise.

### GetSmtpPasswordOk

`func (o *EmailSettingsDto) GetSmtpPasswordOk() (*string, bool)`

GetSmtpPasswordOk returns a tuple with the SmtpPassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmtpPassword

`func (o *EmailSettingsDto) SetSmtpPassword(v string)`

SetSmtpPassword sets SmtpPassword field to given value.

### HasSmtpPassword

`func (o *EmailSettingsDto) HasSmtpPassword() bool`

HasSmtpPassword returns a boolean if a field has been set.

### SetSmtpPasswordNil

`func (o *EmailSettingsDto) SetSmtpPasswordNil(b bool)`

 SetSmtpPasswordNil sets the value for SmtpPassword to be an explicit nil

### UnsetSmtpPassword
`func (o *EmailSettingsDto) UnsetSmtpPassword()`

UnsetSmtpPassword ensures that no value is present for SmtpPassword, not even an explicit nil
### GetSmtpDomain

`func (o *EmailSettingsDto) GetSmtpDomain() string`

GetSmtpDomain returns the SmtpDomain field if non-nil, zero value otherwise.

### GetSmtpDomainOk

`func (o *EmailSettingsDto) GetSmtpDomainOk() (*string, bool)`

GetSmtpDomainOk returns a tuple with the SmtpDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmtpDomain

`func (o *EmailSettingsDto) SetSmtpDomain(v string)`

SetSmtpDomain sets SmtpDomain field to given value.

### HasSmtpDomain

`func (o *EmailSettingsDto) HasSmtpDomain() bool`

HasSmtpDomain returns a boolean if a field has been set.

### SetSmtpDomainNil

`func (o *EmailSettingsDto) SetSmtpDomainNil(b bool)`

 SetSmtpDomainNil sets the value for SmtpDomain to be an explicit nil

### UnsetSmtpDomain
`func (o *EmailSettingsDto) UnsetSmtpDomain()`

UnsetSmtpDomain ensures that no value is present for SmtpDomain, not even an explicit nil
### GetSmtpEnableSsl

`func (o *EmailSettingsDto) GetSmtpEnableSsl() bool`

GetSmtpEnableSsl returns the SmtpEnableSsl field if non-nil, zero value otherwise.

### GetSmtpEnableSslOk

`func (o *EmailSettingsDto) GetSmtpEnableSslOk() (*bool, bool)`

GetSmtpEnableSslOk returns a tuple with the SmtpEnableSsl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmtpEnableSsl

`func (o *EmailSettingsDto) SetSmtpEnableSsl(v bool)`

SetSmtpEnableSsl sets SmtpEnableSsl field to given value.

### HasSmtpEnableSsl

`func (o *EmailSettingsDto) HasSmtpEnableSsl() bool`

HasSmtpEnableSsl returns a boolean if a field has been set.

### GetSmtpUseDefaultCredentials

`func (o *EmailSettingsDto) GetSmtpUseDefaultCredentials() bool`

GetSmtpUseDefaultCredentials returns the SmtpUseDefaultCredentials field if non-nil, zero value otherwise.

### GetSmtpUseDefaultCredentialsOk

`func (o *EmailSettingsDto) GetSmtpUseDefaultCredentialsOk() (*bool, bool)`

GetSmtpUseDefaultCredentialsOk returns a tuple with the SmtpUseDefaultCredentials field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmtpUseDefaultCredentials

`func (o *EmailSettingsDto) SetSmtpUseDefaultCredentials(v bool)`

SetSmtpUseDefaultCredentials sets SmtpUseDefaultCredentials field to given value.

### HasSmtpUseDefaultCredentials

`func (o *EmailSettingsDto) HasSmtpUseDefaultCredentials() bool`

HasSmtpUseDefaultCredentials returns a boolean if a field has been set.

### GetDefaultFromAddress

`func (o *EmailSettingsDto) GetDefaultFromAddress() string`

GetDefaultFromAddress returns the DefaultFromAddress field if non-nil, zero value otherwise.

### GetDefaultFromAddressOk

`func (o *EmailSettingsDto) GetDefaultFromAddressOk() (*string, bool)`

GetDefaultFromAddressOk returns a tuple with the DefaultFromAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultFromAddress

`func (o *EmailSettingsDto) SetDefaultFromAddress(v string)`

SetDefaultFromAddress sets DefaultFromAddress field to given value.

### HasDefaultFromAddress

`func (o *EmailSettingsDto) HasDefaultFromAddress() bool`

HasDefaultFromAddress returns a boolean if a field has been set.

### SetDefaultFromAddressNil

`func (o *EmailSettingsDto) SetDefaultFromAddressNil(b bool)`

 SetDefaultFromAddressNil sets the value for DefaultFromAddress to be an explicit nil

### UnsetDefaultFromAddress
`func (o *EmailSettingsDto) UnsetDefaultFromAddress()`

UnsetDefaultFromAddress ensures that no value is present for DefaultFromAddress, not even an explicit nil
### GetDefaultFromDisplayName

`func (o *EmailSettingsDto) GetDefaultFromDisplayName() string`

GetDefaultFromDisplayName returns the DefaultFromDisplayName field if non-nil, zero value otherwise.

### GetDefaultFromDisplayNameOk

`func (o *EmailSettingsDto) GetDefaultFromDisplayNameOk() (*string, bool)`

GetDefaultFromDisplayNameOk returns a tuple with the DefaultFromDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultFromDisplayName

`func (o *EmailSettingsDto) SetDefaultFromDisplayName(v string)`

SetDefaultFromDisplayName sets DefaultFromDisplayName field to given value.

### HasDefaultFromDisplayName

`func (o *EmailSettingsDto) HasDefaultFromDisplayName() bool`

HasDefaultFromDisplayName returns a boolean if a field has been set.

### SetDefaultFromDisplayNameNil

`func (o *EmailSettingsDto) SetDefaultFromDisplayNameNil(b bool)`

 SetDefaultFromDisplayNameNil sets the value for DefaultFromDisplayName to be an explicit nil

### UnsetDefaultFromDisplayName
`func (o *EmailSettingsDto) UnsetDefaultFromDisplayName()`

UnsetDefaultFromDisplayName ensures that no value is present for DefaultFromDisplayName, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


