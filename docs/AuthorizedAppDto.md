# AuthorizedAppDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional]
**ClientId** | Pointer to **NullableString** |  | [optional]
**DisplayName** | Pointer to **NullableString** |  | [optional]
**ClientUri** | Pointer to **NullableString** |  | [optional]
**LogoUri** | Pointer to **NullableString** |  | [optional]
**Scopes** | Pointer to **NullableString** |  | [optional]
**CreationTime** | Pointer to **time.Time** |  | [optional]
**LastAuthorizationTime** | Pointer to **NullableTime** |  | [optional]

## Methods

### NewAuthorizedAppDto

`func NewAuthorizedAppDto() *AuthorizedAppDto`

NewAuthorizedAppDto instantiates a new AuthorizedAppDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuthorizedAppDtoWithDefaults

`func NewAuthorizedAppDtoWithDefaults() *AuthorizedAppDto`

NewAuthorizedAppDtoWithDefaults instantiates a new AuthorizedAppDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AuthorizedAppDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AuthorizedAppDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AuthorizedAppDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AuthorizedAppDto) HasId() bool`

HasId returns a boolean if a field has been set.

### GetClientId

`func (o *AuthorizedAppDto) GetClientId() string`

GetClientId returns the ClientId field if non-nil, zero value otherwise.

### GetClientIdOk

`func (o *AuthorizedAppDto) GetClientIdOk() (*string, bool)`

GetClientIdOk returns a tuple with the ClientId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientId

`func (o *AuthorizedAppDto) SetClientId(v string)`

SetClientId sets ClientId field to given value.

### HasClientId

`func (o *AuthorizedAppDto) HasClientId() bool`

HasClientId returns a boolean if a field has been set.

### SetClientIdNil

`func (o *AuthorizedAppDto) SetClientIdNil(b bool)`

 SetClientIdNil sets the value for ClientId to be an explicit nil

### UnsetClientId
`func (o *AuthorizedAppDto) UnsetClientId()`

UnsetClientId ensures that no value is present for ClientId, not even an explicit nil
### GetDisplayName

`func (o *AuthorizedAppDto) GetDisplayName() string`

GetDisplayName returns the DisplayName field if non-nil, zero value otherwise.

### GetDisplayNameOk

`func (o *AuthorizedAppDto) GetDisplayNameOk() (*string, bool)`

GetDisplayNameOk returns a tuple with the DisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayName

`func (o *AuthorizedAppDto) SetDisplayName(v string)`

SetDisplayName sets DisplayName field to given value.

### HasDisplayName

`func (o *AuthorizedAppDto) HasDisplayName() bool`

HasDisplayName returns a boolean if a field has been set.

### SetDisplayNameNil

`func (o *AuthorizedAppDto) SetDisplayNameNil(b bool)`

 SetDisplayNameNil sets the value for DisplayName to be an explicit nil

### UnsetDisplayName
`func (o *AuthorizedAppDto) UnsetDisplayName()`

UnsetDisplayName ensures that no value is present for DisplayName, not even an explicit nil
### GetClientUri

`func (o *AuthorizedAppDto) GetClientUri() string`

GetClientUri returns the ClientUri field if non-nil, zero value otherwise.

### GetClientUriOk

`func (o *AuthorizedAppDto) GetClientUriOk() (*string, bool)`

GetClientUriOk returns a tuple with the ClientUri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientUri

`func (o *AuthorizedAppDto) SetClientUri(v string)`

SetClientUri sets ClientUri field to given value.

### HasClientUri

`func (o *AuthorizedAppDto) HasClientUri() bool`

HasClientUri returns a boolean if a field has been set.

### SetClientUriNil

`func (o *AuthorizedAppDto) SetClientUriNil(b bool)`

 SetClientUriNil sets the value for ClientUri to be an explicit nil

### UnsetClientUri
`func (o *AuthorizedAppDto) UnsetClientUri()`

UnsetClientUri ensures that no value is present for ClientUri, not even an explicit nil
### GetLogoUri

`func (o *AuthorizedAppDto) GetLogoUri() string`

GetLogoUri returns the LogoUri field if non-nil, zero value otherwise.

### GetLogoUriOk

`func (o *AuthorizedAppDto) GetLogoUriOk() (*string, bool)`

GetLogoUriOk returns a tuple with the LogoUri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogoUri

`func (o *AuthorizedAppDto) SetLogoUri(v string)`

SetLogoUri sets LogoUri field to given value.

### HasLogoUri

`func (o *AuthorizedAppDto) HasLogoUri() bool`

HasLogoUri returns a boolean if a field has been set.

### SetLogoUriNil

`func (o *AuthorizedAppDto) SetLogoUriNil(b bool)`

 SetLogoUriNil sets the value for LogoUri to be an explicit nil

### UnsetLogoUri
`func (o *AuthorizedAppDto) UnsetLogoUri()`

UnsetLogoUri ensures that no value is present for LogoUri, not even an explicit nil
### GetScopes

`func (o *AuthorizedAppDto) GetScopes() string`

GetScopes returns the Scopes field if non-nil, zero value otherwise.

### GetScopesOk

`func (o *AuthorizedAppDto) GetScopesOk() (*string, bool)`

GetScopesOk returns a tuple with the Scopes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopes

`func (o *AuthorizedAppDto) SetScopes(v string)`

SetScopes sets Scopes field to given value.

### HasScopes

`func (o *AuthorizedAppDto) HasScopes() bool`

HasScopes returns a boolean if a field has been set.

### SetScopesNil

`func (o *AuthorizedAppDto) SetScopesNil(b bool)`

 SetScopesNil sets the value for Scopes to be an explicit nil

### UnsetScopes
`func (o *AuthorizedAppDto) UnsetScopes()`

UnsetScopes ensures that no value is present for Scopes, not even an explicit nil
### GetCreationTime

`func (o *AuthorizedAppDto) GetCreationTime() time.Time`

GetCreationTime returns the CreationTime field if non-nil, zero value otherwise.

### GetCreationTimeOk

`func (o *AuthorizedAppDto) GetCreationTimeOk() (*time.Time, bool)`

GetCreationTimeOk returns a tuple with the CreationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreationTime

`func (o *AuthorizedAppDto) SetCreationTime(v time.Time)`

SetCreationTime sets CreationTime field to given value.

### HasCreationTime

`func (o *AuthorizedAppDto) HasCreationTime() bool`

HasCreationTime returns a boolean if a field has been set.

### GetLastAuthorizationTime

`func (o *AuthorizedAppDto) GetLastAuthorizationTime() time.Time`

GetLastAuthorizationTime returns the LastAuthorizationTime field if non-nil, zero value otherwise.

### GetLastAuthorizationTimeOk

`func (o *AuthorizedAppDto) GetLastAuthorizationTimeOk() (*time.Time, bool)`

GetLastAuthorizationTimeOk returns a tuple with the LastAuthorizationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastAuthorizationTime

`func (o *AuthorizedAppDto) SetLastAuthorizationTime(v time.Time)`

SetLastAuthorizationTime sets LastAuthorizationTime field to given value.

### HasLastAuthorizationTime

`func (o *AuthorizedAppDto) HasLastAuthorizationTime() bool`

HasLastAuthorizationTime returns a boolean if a field has been set.

### SetLastAuthorizationTimeNil

`func (o *AuthorizedAppDto) SetLastAuthorizationTimeNil(b bool)`

 SetLastAuthorizationTimeNil sets the value for LastAuthorizationTime to be an explicit nil

### UnsetLastAuthorizationTime
`func (o *AuthorizedAppDto) UnsetLastAuthorizationTime()`

UnsetLastAuthorizationTime ensures that no value is present for LastAuthorizationTime, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


