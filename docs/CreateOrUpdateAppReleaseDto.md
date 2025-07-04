# CreateOrUpdateAppReleaseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Version** | Pointer to **NullableString** |  | [optional] 
**VersionName** | Pointer to **NullableString** | 版本名称 | [optional] 
**VersionCode** | Pointer to **int64** | 构建编号 | [optional] 
**Notes** | Pointer to **NullableString** |  | [optional] 
**Platform** | Pointer to [**AppPlatform**](AppPlatform.md) |  | [optional] 
**Key** | Pointer to **NullableString** |  | [optional] 
**RapidCode** | Pointer to **NullableString** |  | [optional] 
**Size** | Pointer to **NullableInt64** |  | [optional] 
**Md5** | Pointer to **NullableString** |  | [optional] 
**SliceMd5** | Pointer to **NullableString** |  | [optional] 
**ArtifactType** | Pointer to [**ArtifactType**](ArtifactType.md) |  | [optional] 
**IsForceUpdate** | Pointer to **bool** |  | [optional] 
**AppId** | Pointer to **string** |  | [optional] 
**IsEnabled** | Pointer to **bool** |  | [optional] 
**Channel** | Pointer to **NullableString** |  | [optional] 
**Environment** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCreateOrUpdateAppReleaseDto

`func NewCreateOrUpdateAppReleaseDto() *CreateOrUpdateAppReleaseDto`

NewCreateOrUpdateAppReleaseDto instantiates a new CreateOrUpdateAppReleaseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrUpdateAppReleaseDtoWithDefaults

`func NewCreateOrUpdateAppReleaseDtoWithDefaults() *CreateOrUpdateAppReleaseDto`

NewCreateOrUpdateAppReleaseDtoWithDefaults instantiates a new CreateOrUpdateAppReleaseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVersion

`func (o *CreateOrUpdateAppReleaseDto) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *CreateOrUpdateAppReleaseDto) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *CreateOrUpdateAppReleaseDto) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *CreateOrUpdateAppReleaseDto) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### SetVersionNil

`func (o *CreateOrUpdateAppReleaseDto) SetVersionNil(b bool)`

 SetVersionNil sets the value for Version to be an explicit nil

### UnsetVersion
`func (o *CreateOrUpdateAppReleaseDto) UnsetVersion()`

UnsetVersion ensures that no value is present for Version, not even an explicit nil
### GetVersionName

`func (o *CreateOrUpdateAppReleaseDto) GetVersionName() string`

GetVersionName returns the VersionName field if non-nil, zero value otherwise.

### GetVersionNameOk

`func (o *CreateOrUpdateAppReleaseDto) GetVersionNameOk() (*string, bool)`

GetVersionNameOk returns a tuple with the VersionName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersionName

`func (o *CreateOrUpdateAppReleaseDto) SetVersionName(v string)`

SetVersionName sets VersionName field to given value.

### HasVersionName

`func (o *CreateOrUpdateAppReleaseDto) HasVersionName() bool`

HasVersionName returns a boolean if a field has been set.

### SetVersionNameNil

`func (o *CreateOrUpdateAppReleaseDto) SetVersionNameNil(b bool)`

 SetVersionNameNil sets the value for VersionName to be an explicit nil

### UnsetVersionName
`func (o *CreateOrUpdateAppReleaseDto) UnsetVersionName()`

UnsetVersionName ensures that no value is present for VersionName, not even an explicit nil
### GetVersionCode

`func (o *CreateOrUpdateAppReleaseDto) GetVersionCode() int64`

GetVersionCode returns the VersionCode field if non-nil, zero value otherwise.

### GetVersionCodeOk

`func (o *CreateOrUpdateAppReleaseDto) GetVersionCodeOk() (*int64, bool)`

GetVersionCodeOk returns a tuple with the VersionCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersionCode

`func (o *CreateOrUpdateAppReleaseDto) SetVersionCode(v int64)`

SetVersionCode sets VersionCode field to given value.

### HasVersionCode

`func (o *CreateOrUpdateAppReleaseDto) HasVersionCode() bool`

HasVersionCode returns a boolean if a field has been set.

### GetNotes

`func (o *CreateOrUpdateAppReleaseDto) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *CreateOrUpdateAppReleaseDto) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *CreateOrUpdateAppReleaseDto) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *CreateOrUpdateAppReleaseDto) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *CreateOrUpdateAppReleaseDto) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *CreateOrUpdateAppReleaseDto) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetPlatform

`func (o *CreateOrUpdateAppReleaseDto) GetPlatform() AppPlatform`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *CreateOrUpdateAppReleaseDto) GetPlatformOk() (*AppPlatform, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *CreateOrUpdateAppReleaseDto) SetPlatform(v AppPlatform)`

SetPlatform sets Platform field to given value.

### HasPlatform

`func (o *CreateOrUpdateAppReleaseDto) HasPlatform() bool`

HasPlatform returns a boolean if a field has been set.

### GetKey

`func (o *CreateOrUpdateAppReleaseDto) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *CreateOrUpdateAppReleaseDto) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *CreateOrUpdateAppReleaseDto) SetKey(v string)`

SetKey sets Key field to given value.

### HasKey

`func (o *CreateOrUpdateAppReleaseDto) HasKey() bool`

HasKey returns a boolean if a field has been set.

### SetKeyNil

`func (o *CreateOrUpdateAppReleaseDto) SetKeyNil(b bool)`

 SetKeyNil sets the value for Key to be an explicit nil

### UnsetKey
`func (o *CreateOrUpdateAppReleaseDto) UnsetKey()`

UnsetKey ensures that no value is present for Key, not even an explicit nil
### GetRapidCode

`func (o *CreateOrUpdateAppReleaseDto) GetRapidCode() string`

GetRapidCode returns the RapidCode field if non-nil, zero value otherwise.

### GetRapidCodeOk

`func (o *CreateOrUpdateAppReleaseDto) GetRapidCodeOk() (*string, bool)`

GetRapidCodeOk returns a tuple with the RapidCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRapidCode

`func (o *CreateOrUpdateAppReleaseDto) SetRapidCode(v string)`

SetRapidCode sets RapidCode field to given value.

### HasRapidCode

`func (o *CreateOrUpdateAppReleaseDto) HasRapidCode() bool`

HasRapidCode returns a boolean if a field has been set.

### SetRapidCodeNil

`func (o *CreateOrUpdateAppReleaseDto) SetRapidCodeNil(b bool)`

 SetRapidCodeNil sets the value for RapidCode to be an explicit nil

### UnsetRapidCode
`func (o *CreateOrUpdateAppReleaseDto) UnsetRapidCode()`

UnsetRapidCode ensures that no value is present for RapidCode, not even an explicit nil
### GetSize

`func (o *CreateOrUpdateAppReleaseDto) GetSize() int64`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *CreateOrUpdateAppReleaseDto) GetSizeOk() (*int64, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *CreateOrUpdateAppReleaseDto) SetSize(v int64)`

SetSize sets Size field to given value.

### HasSize

`func (o *CreateOrUpdateAppReleaseDto) HasSize() bool`

HasSize returns a boolean if a field has been set.

### SetSizeNil

`func (o *CreateOrUpdateAppReleaseDto) SetSizeNil(b bool)`

 SetSizeNil sets the value for Size to be an explicit nil

### UnsetSize
`func (o *CreateOrUpdateAppReleaseDto) UnsetSize()`

UnsetSize ensures that no value is present for Size, not even an explicit nil
### GetMd5

`func (o *CreateOrUpdateAppReleaseDto) GetMd5() string`

GetMd5 returns the Md5 field if non-nil, zero value otherwise.

### GetMd5Ok

`func (o *CreateOrUpdateAppReleaseDto) GetMd5Ok() (*string, bool)`

GetMd5Ok returns a tuple with the Md5 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMd5

`func (o *CreateOrUpdateAppReleaseDto) SetMd5(v string)`

SetMd5 sets Md5 field to given value.

### HasMd5

`func (o *CreateOrUpdateAppReleaseDto) HasMd5() bool`

HasMd5 returns a boolean if a field has been set.

### SetMd5Nil

`func (o *CreateOrUpdateAppReleaseDto) SetMd5Nil(b bool)`

 SetMd5Nil sets the value for Md5 to be an explicit nil

### UnsetMd5
`func (o *CreateOrUpdateAppReleaseDto) UnsetMd5()`

UnsetMd5 ensures that no value is present for Md5, not even an explicit nil
### GetSliceMd5

`func (o *CreateOrUpdateAppReleaseDto) GetSliceMd5() string`

GetSliceMd5 returns the SliceMd5 field if non-nil, zero value otherwise.

### GetSliceMd5Ok

`func (o *CreateOrUpdateAppReleaseDto) GetSliceMd5Ok() (*string, bool)`

GetSliceMd5Ok returns a tuple with the SliceMd5 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSliceMd5

`func (o *CreateOrUpdateAppReleaseDto) SetSliceMd5(v string)`

SetSliceMd5 sets SliceMd5 field to given value.

### HasSliceMd5

`func (o *CreateOrUpdateAppReleaseDto) HasSliceMd5() bool`

HasSliceMd5 returns a boolean if a field has been set.

### SetSliceMd5Nil

`func (o *CreateOrUpdateAppReleaseDto) SetSliceMd5Nil(b bool)`

 SetSliceMd5Nil sets the value for SliceMd5 to be an explicit nil

### UnsetSliceMd5
`func (o *CreateOrUpdateAppReleaseDto) UnsetSliceMd5()`

UnsetSliceMd5 ensures that no value is present for SliceMd5, not even an explicit nil
### GetArtifactType

`func (o *CreateOrUpdateAppReleaseDto) GetArtifactType() ArtifactType`

GetArtifactType returns the ArtifactType field if non-nil, zero value otherwise.

### GetArtifactTypeOk

`func (o *CreateOrUpdateAppReleaseDto) GetArtifactTypeOk() (*ArtifactType, bool)`

GetArtifactTypeOk returns a tuple with the ArtifactType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArtifactType

`func (o *CreateOrUpdateAppReleaseDto) SetArtifactType(v ArtifactType)`

SetArtifactType sets ArtifactType field to given value.

### HasArtifactType

`func (o *CreateOrUpdateAppReleaseDto) HasArtifactType() bool`

HasArtifactType returns a boolean if a field has been set.

### GetIsForceUpdate

`func (o *CreateOrUpdateAppReleaseDto) GetIsForceUpdate() bool`

GetIsForceUpdate returns the IsForceUpdate field if non-nil, zero value otherwise.

### GetIsForceUpdateOk

`func (o *CreateOrUpdateAppReleaseDto) GetIsForceUpdateOk() (*bool, bool)`

GetIsForceUpdateOk returns a tuple with the IsForceUpdate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsForceUpdate

`func (o *CreateOrUpdateAppReleaseDto) SetIsForceUpdate(v bool)`

SetIsForceUpdate sets IsForceUpdate field to given value.

### HasIsForceUpdate

`func (o *CreateOrUpdateAppReleaseDto) HasIsForceUpdate() bool`

HasIsForceUpdate returns a boolean if a field has been set.

### GetAppId

`func (o *CreateOrUpdateAppReleaseDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *CreateOrUpdateAppReleaseDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *CreateOrUpdateAppReleaseDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *CreateOrUpdateAppReleaseDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetIsEnabled

`func (o *CreateOrUpdateAppReleaseDto) GetIsEnabled() bool`

GetIsEnabled returns the IsEnabled field if non-nil, zero value otherwise.

### GetIsEnabledOk

`func (o *CreateOrUpdateAppReleaseDto) GetIsEnabledOk() (*bool, bool)`

GetIsEnabledOk returns a tuple with the IsEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsEnabled

`func (o *CreateOrUpdateAppReleaseDto) SetIsEnabled(v bool)`

SetIsEnabled sets IsEnabled field to given value.

### HasIsEnabled

`func (o *CreateOrUpdateAppReleaseDto) HasIsEnabled() bool`

HasIsEnabled returns a boolean if a field has been set.

### GetChannel

`func (o *CreateOrUpdateAppReleaseDto) GetChannel() string`

GetChannel returns the Channel field if non-nil, zero value otherwise.

### GetChannelOk

`func (o *CreateOrUpdateAppReleaseDto) GetChannelOk() (*string, bool)`

GetChannelOk returns a tuple with the Channel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannel

`func (o *CreateOrUpdateAppReleaseDto) SetChannel(v string)`

SetChannel sets Channel field to given value.

### HasChannel

`func (o *CreateOrUpdateAppReleaseDto) HasChannel() bool`

HasChannel returns a boolean if a field has been set.

### SetChannelNil

`func (o *CreateOrUpdateAppReleaseDto) SetChannelNil(b bool)`

 SetChannelNil sets the value for Channel to be an explicit nil

### UnsetChannel
`func (o *CreateOrUpdateAppReleaseDto) UnsetChannel()`

UnsetChannel ensures that no value is present for Channel, not even an explicit nil
### GetEnvironment

`func (o *CreateOrUpdateAppReleaseDto) GetEnvironment() string`

GetEnvironment returns the Environment field if non-nil, zero value otherwise.

### GetEnvironmentOk

`func (o *CreateOrUpdateAppReleaseDto) GetEnvironmentOk() (*string, bool)`

GetEnvironmentOk returns a tuple with the Environment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnvironment

`func (o *CreateOrUpdateAppReleaseDto) SetEnvironment(v string)`

SetEnvironment sets Environment field to given value.

### HasEnvironment

`func (o *CreateOrUpdateAppReleaseDto) HasEnvironment() bool`

HasEnvironment returns a boolean if a field has been set.

### SetEnvironmentNil

`func (o *CreateOrUpdateAppReleaseDto) SetEnvironmentNil(b bool)`

 SetEnvironmentNil sets the value for Environment to be an explicit nil

### UnsetEnvironment
`func (o *CreateOrUpdateAppReleaseDto) UnsetEnvironment()`

UnsetEnvironment ensures that no value is present for Environment, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


