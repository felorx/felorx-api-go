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
**Hash** | Pointer to **NullableString** |  | [optional]
**ArtifactType** | Pointer to [**ArtifactType**](ArtifactType.md) |  | [optional]
**Publisher** | Pointer to [**AppPublisher**](AppPublisher.md) |  | [optional]
**IsForceUpdate** | Pointer to **bool** |  | [optional]
**AppId** | Pointer to **string** |  | [optional]
**IsEnabled** | Pointer to **bool** |  | [optional]
**Channel** | Pointer to [**ReleaseChannel**](ReleaseChannel.md) |  | [optional]
**BuildRecordId** | Pointer to **NullableString** | 构建记录ID（可选，如果提供则使用对应构建的BuildNumber作为VersionCode） | [optional]

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
### GetHash

`func (o *CreateOrUpdateAppReleaseDto) GetHash() string`

GetHash returns the Hash field if non-nil, zero value otherwise.

### GetHashOk

`func (o *CreateOrUpdateAppReleaseDto) GetHashOk() (*string, bool)`

GetHashOk returns a tuple with the Hash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHash

`func (o *CreateOrUpdateAppReleaseDto) SetHash(v string)`

SetHash sets Hash field to given value.

### HasHash

`func (o *CreateOrUpdateAppReleaseDto) HasHash() bool`

HasHash returns a boolean if a field has been set.

### SetHashNil

`func (o *CreateOrUpdateAppReleaseDto) SetHashNil(b bool)`

 SetHashNil sets the value for Hash to be an explicit nil

### UnsetHash
`func (o *CreateOrUpdateAppReleaseDto) UnsetHash()`

UnsetHash ensures that no value is present for Hash, not even an explicit nil
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

### GetPublisher

`func (o *CreateOrUpdateAppReleaseDto) GetPublisher() AppPublisher`

GetPublisher returns the Publisher field if non-nil, zero value otherwise.

### GetPublisherOk

`func (o *CreateOrUpdateAppReleaseDto) GetPublisherOk() (*AppPublisher, bool)`

GetPublisherOk returns a tuple with the Publisher field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublisher

`func (o *CreateOrUpdateAppReleaseDto) SetPublisher(v AppPublisher)`

SetPublisher sets Publisher field to given value.

### HasPublisher

`func (o *CreateOrUpdateAppReleaseDto) HasPublisher() bool`

HasPublisher returns a boolean if a field has been set.

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

`func (o *CreateOrUpdateAppReleaseDto) GetChannel() ReleaseChannel`

GetChannel returns the Channel field if non-nil, zero value otherwise.

### GetChannelOk

`func (o *CreateOrUpdateAppReleaseDto) GetChannelOk() (*ReleaseChannel, bool)`

GetChannelOk returns a tuple with the Channel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannel

`func (o *CreateOrUpdateAppReleaseDto) SetChannel(v ReleaseChannel)`

SetChannel sets Channel field to given value.

### HasChannel

`func (o *CreateOrUpdateAppReleaseDto) HasChannel() bool`

HasChannel returns a boolean if a field has been set.

### GetBuildRecordId

`func (o *CreateOrUpdateAppReleaseDto) GetBuildRecordId() string`

GetBuildRecordId returns the BuildRecordId field if non-nil, zero value otherwise.

### GetBuildRecordIdOk

`func (o *CreateOrUpdateAppReleaseDto) GetBuildRecordIdOk() (*string, bool)`

GetBuildRecordIdOk returns a tuple with the BuildRecordId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildRecordId

`func (o *CreateOrUpdateAppReleaseDto) SetBuildRecordId(v string)`

SetBuildRecordId sets BuildRecordId field to given value.

### HasBuildRecordId

`func (o *CreateOrUpdateAppReleaseDto) HasBuildRecordId() bool`

HasBuildRecordId returns a boolean if a field has been set.

### SetBuildRecordIdNil

`func (o *CreateOrUpdateAppReleaseDto) SetBuildRecordIdNil(b bool)`

 SetBuildRecordIdNil sets the value for BuildRecordId to be an explicit nil

### UnsetBuildRecordId
`func (o *CreateOrUpdateAppReleaseDto) UnsetBuildRecordId()`

UnsetBuildRecordId ensures that no value is present for BuildRecordId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


