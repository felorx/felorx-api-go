# CreateOpenIddictApplicationDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **NullableString** |  | [optional] 
**DisplayName** | Pointer to **NullableString** |  | [optional] 
**DisplayNames** | Pointer to **NullableString** |  | [optional] 
**Permissions** | Pointer to **[]string** |  | [optional] 
**PostLogoutRedirectUris** | Pointer to **NullableString** |  | [optional] 
**Properties** | Pointer to **NullableString** |  | [optional] 
**RedirectUris** | Pointer to **NullableString** |  | [optional] 
**Requirements** | Pointer to **NullableString** |  | [optional] 
**ClientUri** | Pointer to **NullableString** |  | [optional] 
**LogoUri** | Pointer to **NullableString** |  | [optional] 
**GrantTypes** | Pointer to **[]string** |  | [optional] 
**Scopes** | Pointer to **[]string** |  | [optional] 

## Methods

### NewCreateOpenIddictApplicationDto

`func NewCreateOpenIddictApplicationDto() *CreateOpenIddictApplicationDto`

NewCreateOpenIddictApplicationDto instantiates a new CreateOpenIddictApplicationDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOpenIddictApplicationDtoWithDefaults

`func NewCreateOpenIddictApplicationDtoWithDefaults() *CreateOpenIddictApplicationDto`

NewCreateOpenIddictApplicationDtoWithDefaults instantiates a new CreateOpenIddictApplicationDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *CreateOpenIddictApplicationDto) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreateOpenIddictApplicationDto) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreateOpenIddictApplicationDto) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *CreateOpenIddictApplicationDto) HasType() bool`

HasType returns a boolean if a field has been set.

### SetTypeNil

`func (o *CreateOpenIddictApplicationDto) SetTypeNil(b bool)`

 SetTypeNil sets the value for Type to be an explicit nil

### UnsetType
`func (o *CreateOpenIddictApplicationDto) UnsetType()`

UnsetType ensures that no value is present for Type, not even an explicit nil
### GetDisplayName

`func (o *CreateOpenIddictApplicationDto) GetDisplayName() string`

GetDisplayName returns the DisplayName field if non-nil, zero value otherwise.

### GetDisplayNameOk

`func (o *CreateOpenIddictApplicationDto) GetDisplayNameOk() (*string, bool)`

GetDisplayNameOk returns a tuple with the DisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayName

`func (o *CreateOpenIddictApplicationDto) SetDisplayName(v string)`

SetDisplayName sets DisplayName field to given value.

### HasDisplayName

`func (o *CreateOpenIddictApplicationDto) HasDisplayName() bool`

HasDisplayName returns a boolean if a field has been set.

### SetDisplayNameNil

`func (o *CreateOpenIddictApplicationDto) SetDisplayNameNil(b bool)`

 SetDisplayNameNil sets the value for DisplayName to be an explicit nil

### UnsetDisplayName
`func (o *CreateOpenIddictApplicationDto) UnsetDisplayName()`

UnsetDisplayName ensures that no value is present for DisplayName, not even an explicit nil
### GetDisplayNames

`func (o *CreateOpenIddictApplicationDto) GetDisplayNames() string`

GetDisplayNames returns the DisplayNames field if non-nil, zero value otherwise.

### GetDisplayNamesOk

`func (o *CreateOpenIddictApplicationDto) GetDisplayNamesOk() (*string, bool)`

GetDisplayNamesOk returns a tuple with the DisplayNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayNames

`func (o *CreateOpenIddictApplicationDto) SetDisplayNames(v string)`

SetDisplayNames sets DisplayNames field to given value.

### HasDisplayNames

`func (o *CreateOpenIddictApplicationDto) HasDisplayNames() bool`

HasDisplayNames returns a boolean if a field has been set.

### SetDisplayNamesNil

`func (o *CreateOpenIddictApplicationDto) SetDisplayNamesNil(b bool)`

 SetDisplayNamesNil sets the value for DisplayNames to be an explicit nil

### UnsetDisplayNames
`func (o *CreateOpenIddictApplicationDto) UnsetDisplayNames()`

UnsetDisplayNames ensures that no value is present for DisplayNames, not even an explicit nil
### GetPermissions

`func (o *CreateOpenIddictApplicationDto) GetPermissions() []string`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *CreateOpenIddictApplicationDto) GetPermissionsOk() (*[]string, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *CreateOpenIddictApplicationDto) SetPermissions(v []string)`

SetPermissions sets Permissions field to given value.

### HasPermissions

`func (o *CreateOpenIddictApplicationDto) HasPermissions() bool`

HasPermissions returns a boolean if a field has been set.

### SetPermissionsNil

`func (o *CreateOpenIddictApplicationDto) SetPermissionsNil(b bool)`

 SetPermissionsNil sets the value for Permissions to be an explicit nil

### UnsetPermissions
`func (o *CreateOpenIddictApplicationDto) UnsetPermissions()`

UnsetPermissions ensures that no value is present for Permissions, not even an explicit nil
### GetPostLogoutRedirectUris

`func (o *CreateOpenIddictApplicationDto) GetPostLogoutRedirectUris() string`

GetPostLogoutRedirectUris returns the PostLogoutRedirectUris field if non-nil, zero value otherwise.

### GetPostLogoutRedirectUrisOk

`func (o *CreateOpenIddictApplicationDto) GetPostLogoutRedirectUrisOk() (*string, bool)`

GetPostLogoutRedirectUrisOk returns a tuple with the PostLogoutRedirectUris field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostLogoutRedirectUris

`func (o *CreateOpenIddictApplicationDto) SetPostLogoutRedirectUris(v string)`

SetPostLogoutRedirectUris sets PostLogoutRedirectUris field to given value.

### HasPostLogoutRedirectUris

`func (o *CreateOpenIddictApplicationDto) HasPostLogoutRedirectUris() bool`

HasPostLogoutRedirectUris returns a boolean if a field has been set.

### SetPostLogoutRedirectUrisNil

`func (o *CreateOpenIddictApplicationDto) SetPostLogoutRedirectUrisNil(b bool)`

 SetPostLogoutRedirectUrisNil sets the value for PostLogoutRedirectUris to be an explicit nil

### UnsetPostLogoutRedirectUris
`func (o *CreateOpenIddictApplicationDto) UnsetPostLogoutRedirectUris()`

UnsetPostLogoutRedirectUris ensures that no value is present for PostLogoutRedirectUris, not even an explicit nil
### GetProperties

`func (o *CreateOpenIddictApplicationDto) GetProperties() string`

GetProperties returns the Properties field if non-nil, zero value otherwise.

### GetPropertiesOk

`func (o *CreateOpenIddictApplicationDto) GetPropertiesOk() (*string, bool)`

GetPropertiesOk returns a tuple with the Properties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperties

`func (o *CreateOpenIddictApplicationDto) SetProperties(v string)`

SetProperties sets Properties field to given value.

### HasProperties

`func (o *CreateOpenIddictApplicationDto) HasProperties() bool`

HasProperties returns a boolean if a field has been set.

### SetPropertiesNil

`func (o *CreateOpenIddictApplicationDto) SetPropertiesNil(b bool)`

 SetPropertiesNil sets the value for Properties to be an explicit nil

### UnsetProperties
`func (o *CreateOpenIddictApplicationDto) UnsetProperties()`

UnsetProperties ensures that no value is present for Properties, not even an explicit nil
### GetRedirectUris

`func (o *CreateOpenIddictApplicationDto) GetRedirectUris() string`

GetRedirectUris returns the RedirectUris field if non-nil, zero value otherwise.

### GetRedirectUrisOk

`func (o *CreateOpenIddictApplicationDto) GetRedirectUrisOk() (*string, bool)`

GetRedirectUrisOk returns a tuple with the RedirectUris field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedirectUris

`func (o *CreateOpenIddictApplicationDto) SetRedirectUris(v string)`

SetRedirectUris sets RedirectUris field to given value.

### HasRedirectUris

`func (o *CreateOpenIddictApplicationDto) HasRedirectUris() bool`

HasRedirectUris returns a boolean if a field has been set.

### SetRedirectUrisNil

`func (o *CreateOpenIddictApplicationDto) SetRedirectUrisNil(b bool)`

 SetRedirectUrisNil sets the value for RedirectUris to be an explicit nil

### UnsetRedirectUris
`func (o *CreateOpenIddictApplicationDto) UnsetRedirectUris()`

UnsetRedirectUris ensures that no value is present for RedirectUris, not even an explicit nil
### GetRequirements

`func (o *CreateOpenIddictApplicationDto) GetRequirements() string`

GetRequirements returns the Requirements field if non-nil, zero value otherwise.

### GetRequirementsOk

`func (o *CreateOpenIddictApplicationDto) GetRequirementsOk() (*string, bool)`

GetRequirementsOk returns a tuple with the Requirements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequirements

`func (o *CreateOpenIddictApplicationDto) SetRequirements(v string)`

SetRequirements sets Requirements field to given value.

### HasRequirements

`func (o *CreateOpenIddictApplicationDto) HasRequirements() bool`

HasRequirements returns a boolean if a field has been set.

### SetRequirementsNil

`func (o *CreateOpenIddictApplicationDto) SetRequirementsNil(b bool)`

 SetRequirementsNil sets the value for Requirements to be an explicit nil

### UnsetRequirements
`func (o *CreateOpenIddictApplicationDto) UnsetRequirements()`

UnsetRequirements ensures that no value is present for Requirements, not even an explicit nil
### GetClientUri

`func (o *CreateOpenIddictApplicationDto) GetClientUri() string`

GetClientUri returns the ClientUri field if non-nil, zero value otherwise.

### GetClientUriOk

`func (o *CreateOpenIddictApplicationDto) GetClientUriOk() (*string, bool)`

GetClientUriOk returns a tuple with the ClientUri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientUri

`func (o *CreateOpenIddictApplicationDto) SetClientUri(v string)`

SetClientUri sets ClientUri field to given value.

### HasClientUri

`func (o *CreateOpenIddictApplicationDto) HasClientUri() bool`

HasClientUri returns a boolean if a field has been set.

### SetClientUriNil

`func (o *CreateOpenIddictApplicationDto) SetClientUriNil(b bool)`

 SetClientUriNil sets the value for ClientUri to be an explicit nil

### UnsetClientUri
`func (o *CreateOpenIddictApplicationDto) UnsetClientUri()`

UnsetClientUri ensures that no value is present for ClientUri, not even an explicit nil
### GetLogoUri

`func (o *CreateOpenIddictApplicationDto) GetLogoUri() string`

GetLogoUri returns the LogoUri field if non-nil, zero value otherwise.

### GetLogoUriOk

`func (o *CreateOpenIddictApplicationDto) GetLogoUriOk() (*string, bool)`

GetLogoUriOk returns a tuple with the LogoUri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogoUri

`func (o *CreateOpenIddictApplicationDto) SetLogoUri(v string)`

SetLogoUri sets LogoUri field to given value.

### HasLogoUri

`func (o *CreateOpenIddictApplicationDto) HasLogoUri() bool`

HasLogoUri returns a boolean if a field has been set.

### SetLogoUriNil

`func (o *CreateOpenIddictApplicationDto) SetLogoUriNil(b bool)`

 SetLogoUriNil sets the value for LogoUri to be an explicit nil

### UnsetLogoUri
`func (o *CreateOpenIddictApplicationDto) UnsetLogoUri()`

UnsetLogoUri ensures that no value is present for LogoUri, not even an explicit nil
### GetGrantTypes

`func (o *CreateOpenIddictApplicationDto) GetGrantTypes() []string`

GetGrantTypes returns the GrantTypes field if non-nil, zero value otherwise.

### GetGrantTypesOk

`func (o *CreateOpenIddictApplicationDto) GetGrantTypesOk() (*[]string, bool)`

GetGrantTypesOk returns a tuple with the GrantTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrantTypes

`func (o *CreateOpenIddictApplicationDto) SetGrantTypes(v []string)`

SetGrantTypes sets GrantTypes field to given value.

### HasGrantTypes

`func (o *CreateOpenIddictApplicationDto) HasGrantTypes() bool`

HasGrantTypes returns a boolean if a field has been set.

### SetGrantTypesNil

`func (o *CreateOpenIddictApplicationDto) SetGrantTypesNil(b bool)`

 SetGrantTypesNil sets the value for GrantTypes to be an explicit nil

### UnsetGrantTypes
`func (o *CreateOpenIddictApplicationDto) UnsetGrantTypes()`

UnsetGrantTypes ensures that no value is present for GrantTypes, not even an explicit nil
### GetScopes

`func (o *CreateOpenIddictApplicationDto) GetScopes() []string`

GetScopes returns the Scopes field if non-nil, zero value otherwise.

### GetScopesOk

`func (o *CreateOpenIddictApplicationDto) GetScopesOk() (*[]string, bool)`

GetScopesOk returns a tuple with the Scopes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopes

`func (o *CreateOpenIddictApplicationDto) SetScopes(v []string)`

SetScopes sets Scopes field to given value.

### HasScopes

`func (o *CreateOpenIddictApplicationDto) HasScopes() bool`

HasScopes returns a boolean if a field has been set.

### SetScopesNil

`func (o *CreateOpenIddictApplicationDto) SetScopesNil(b bool)`

 SetScopesNil sets the value for Scopes to be an explicit nil

### UnsetScopes
`func (o *CreateOpenIddictApplicationDto) UnsetScopes()`

UnsetScopes ensures that no value is present for Scopes, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


