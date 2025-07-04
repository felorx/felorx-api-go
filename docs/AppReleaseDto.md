# AppReleaseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**CreationTime** | Pointer to **time.Time** |  | [optional] 
**CreatorId** | Pointer to **NullableString** |  | [optional] 
**LastModificationTime** | Pointer to **NullableTime** |  | [optional] 
**LastModifierId** | Pointer to **NullableString** |  | [optional] 
**IsDeleted** | Pointer to **bool** |  | [optional] 
**DeleterId** | Pointer to **NullableString** |  | [optional] 
**DeletionTime** | Pointer to **NullableTime** |  | [optional] 
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
**DownloadUrl** | Pointer to **NullableString** |  | [optional] 
**ArtifactType** | Pointer to [**ArtifactType**](ArtifactType.md) |  | [optional] 
**IsForceUpdate** | Pointer to **bool** |  | [optional] 
**AppId** | Pointer to **string** |  | [optional] 
**IsEnabled** | Pointer to **bool** |  | [optional] 
**Channel** | Pointer to **NullableString** |  | [optional] 
**Environment** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewAppReleaseDto

`func NewAppReleaseDto() *AppReleaseDto`

NewAppReleaseDto instantiates a new AppReleaseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAppReleaseDtoWithDefaults

`func NewAppReleaseDtoWithDefaults() *AppReleaseDto`

NewAppReleaseDtoWithDefaults instantiates a new AppReleaseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AppReleaseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AppReleaseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AppReleaseDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AppReleaseDto) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreationTime

`func (o *AppReleaseDto) GetCreationTime() time.Time`

GetCreationTime returns the CreationTime field if non-nil, zero value otherwise.

### GetCreationTimeOk

`func (o *AppReleaseDto) GetCreationTimeOk() (*time.Time, bool)`

GetCreationTimeOk returns a tuple with the CreationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreationTime

`func (o *AppReleaseDto) SetCreationTime(v time.Time)`

SetCreationTime sets CreationTime field to given value.

### HasCreationTime

`func (o *AppReleaseDto) HasCreationTime() bool`

HasCreationTime returns a boolean if a field has been set.

### GetCreatorId

`func (o *AppReleaseDto) GetCreatorId() string`

GetCreatorId returns the CreatorId field if non-nil, zero value otherwise.

### GetCreatorIdOk

`func (o *AppReleaseDto) GetCreatorIdOk() (*string, bool)`

GetCreatorIdOk returns a tuple with the CreatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatorId

`func (o *AppReleaseDto) SetCreatorId(v string)`

SetCreatorId sets CreatorId field to given value.

### HasCreatorId

`func (o *AppReleaseDto) HasCreatorId() bool`

HasCreatorId returns a boolean if a field has been set.

### SetCreatorIdNil

`func (o *AppReleaseDto) SetCreatorIdNil(b bool)`

 SetCreatorIdNil sets the value for CreatorId to be an explicit nil

### UnsetCreatorId
`func (o *AppReleaseDto) UnsetCreatorId()`

UnsetCreatorId ensures that no value is present for CreatorId, not even an explicit nil
### GetLastModificationTime

`func (o *AppReleaseDto) GetLastModificationTime() time.Time`

GetLastModificationTime returns the LastModificationTime field if non-nil, zero value otherwise.

### GetLastModificationTimeOk

`func (o *AppReleaseDto) GetLastModificationTimeOk() (*time.Time, bool)`

GetLastModificationTimeOk returns a tuple with the LastModificationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModificationTime

`func (o *AppReleaseDto) SetLastModificationTime(v time.Time)`

SetLastModificationTime sets LastModificationTime field to given value.

### HasLastModificationTime

`func (o *AppReleaseDto) HasLastModificationTime() bool`

HasLastModificationTime returns a boolean if a field has been set.

### SetLastModificationTimeNil

`func (o *AppReleaseDto) SetLastModificationTimeNil(b bool)`

 SetLastModificationTimeNil sets the value for LastModificationTime to be an explicit nil

### UnsetLastModificationTime
`func (o *AppReleaseDto) UnsetLastModificationTime()`

UnsetLastModificationTime ensures that no value is present for LastModificationTime, not even an explicit nil
### GetLastModifierId

`func (o *AppReleaseDto) GetLastModifierId() string`

GetLastModifierId returns the LastModifierId field if non-nil, zero value otherwise.

### GetLastModifierIdOk

`func (o *AppReleaseDto) GetLastModifierIdOk() (*string, bool)`

GetLastModifierIdOk returns a tuple with the LastModifierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModifierId

`func (o *AppReleaseDto) SetLastModifierId(v string)`

SetLastModifierId sets LastModifierId field to given value.

### HasLastModifierId

`func (o *AppReleaseDto) HasLastModifierId() bool`

HasLastModifierId returns a boolean if a field has been set.

### SetLastModifierIdNil

`func (o *AppReleaseDto) SetLastModifierIdNil(b bool)`

 SetLastModifierIdNil sets the value for LastModifierId to be an explicit nil

### UnsetLastModifierId
`func (o *AppReleaseDto) UnsetLastModifierId()`

UnsetLastModifierId ensures that no value is present for LastModifierId, not even an explicit nil
### GetIsDeleted

`func (o *AppReleaseDto) GetIsDeleted() bool`

GetIsDeleted returns the IsDeleted field if non-nil, zero value otherwise.

### GetIsDeletedOk

`func (o *AppReleaseDto) GetIsDeletedOk() (*bool, bool)`

GetIsDeletedOk returns a tuple with the IsDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDeleted

`func (o *AppReleaseDto) SetIsDeleted(v bool)`

SetIsDeleted sets IsDeleted field to given value.

### HasIsDeleted

`func (o *AppReleaseDto) HasIsDeleted() bool`

HasIsDeleted returns a boolean if a field has been set.

### GetDeleterId

`func (o *AppReleaseDto) GetDeleterId() string`

GetDeleterId returns the DeleterId field if non-nil, zero value otherwise.

### GetDeleterIdOk

`func (o *AppReleaseDto) GetDeleterIdOk() (*string, bool)`

GetDeleterIdOk returns a tuple with the DeleterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleterId

`func (o *AppReleaseDto) SetDeleterId(v string)`

SetDeleterId sets DeleterId field to given value.

### HasDeleterId

`func (o *AppReleaseDto) HasDeleterId() bool`

HasDeleterId returns a boolean if a field has been set.

### SetDeleterIdNil

`func (o *AppReleaseDto) SetDeleterIdNil(b bool)`

 SetDeleterIdNil sets the value for DeleterId to be an explicit nil

### UnsetDeleterId
`func (o *AppReleaseDto) UnsetDeleterId()`

UnsetDeleterId ensures that no value is present for DeleterId, not even an explicit nil
### GetDeletionTime

`func (o *AppReleaseDto) GetDeletionTime() time.Time`

GetDeletionTime returns the DeletionTime field if non-nil, zero value otherwise.

### GetDeletionTimeOk

`func (o *AppReleaseDto) GetDeletionTimeOk() (*time.Time, bool)`

GetDeletionTimeOk returns a tuple with the DeletionTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletionTime

`func (o *AppReleaseDto) SetDeletionTime(v time.Time)`

SetDeletionTime sets DeletionTime field to given value.

### HasDeletionTime

`func (o *AppReleaseDto) HasDeletionTime() bool`

HasDeletionTime returns a boolean if a field has been set.

### SetDeletionTimeNil

`func (o *AppReleaseDto) SetDeletionTimeNil(b bool)`

 SetDeletionTimeNil sets the value for DeletionTime to be an explicit nil

### UnsetDeletionTime
`func (o *AppReleaseDto) UnsetDeletionTime()`

UnsetDeletionTime ensures that no value is present for DeletionTime, not even an explicit nil
### GetVersion

`func (o *AppReleaseDto) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *AppReleaseDto) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *AppReleaseDto) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *AppReleaseDto) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### SetVersionNil

`func (o *AppReleaseDto) SetVersionNil(b bool)`

 SetVersionNil sets the value for Version to be an explicit nil

### UnsetVersion
`func (o *AppReleaseDto) UnsetVersion()`

UnsetVersion ensures that no value is present for Version, not even an explicit nil
### GetVersionName

`func (o *AppReleaseDto) GetVersionName() string`

GetVersionName returns the VersionName field if non-nil, zero value otherwise.

### GetVersionNameOk

`func (o *AppReleaseDto) GetVersionNameOk() (*string, bool)`

GetVersionNameOk returns a tuple with the VersionName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersionName

`func (o *AppReleaseDto) SetVersionName(v string)`

SetVersionName sets VersionName field to given value.

### HasVersionName

`func (o *AppReleaseDto) HasVersionName() bool`

HasVersionName returns a boolean if a field has been set.

### SetVersionNameNil

`func (o *AppReleaseDto) SetVersionNameNil(b bool)`

 SetVersionNameNil sets the value for VersionName to be an explicit nil

### UnsetVersionName
`func (o *AppReleaseDto) UnsetVersionName()`

UnsetVersionName ensures that no value is present for VersionName, not even an explicit nil
### GetVersionCode

`func (o *AppReleaseDto) GetVersionCode() int64`

GetVersionCode returns the VersionCode field if non-nil, zero value otherwise.

### GetVersionCodeOk

`func (o *AppReleaseDto) GetVersionCodeOk() (*int64, bool)`

GetVersionCodeOk returns a tuple with the VersionCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersionCode

`func (o *AppReleaseDto) SetVersionCode(v int64)`

SetVersionCode sets VersionCode field to given value.

### HasVersionCode

`func (o *AppReleaseDto) HasVersionCode() bool`

HasVersionCode returns a boolean if a field has been set.

### GetNotes

`func (o *AppReleaseDto) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *AppReleaseDto) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *AppReleaseDto) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *AppReleaseDto) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *AppReleaseDto) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *AppReleaseDto) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetPlatform

`func (o *AppReleaseDto) GetPlatform() AppPlatform`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *AppReleaseDto) GetPlatformOk() (*AppPlatform, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *AppReleaseDto) SetPlatform(v AppPlatform)`

SetPlatform sets Platform field to given value.

### HasPlatform

`func (o *AppReleaseDto) HasPlatform() bool`

HasPlatform returns a boolean if a field has been set.

### GetKey

`func (o *AppReleaseDto) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *AppReleaseDto) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *AppReleaseDto) SetKey(v string)`

SetKey sets Key field to given value.

### HasKey

`func (o *AppReleaseDto) HasKey() bool`

HasKey returns a boolean if a field has been set.

### SetKeyNil

`func (o *AppReleaseDto) SetKeyNil(b bool)`

 SetKeyNil sets the value for Key to be an explicit nil

### UnsetKey
`func (o *AppReleaseDto) UnsetKey()`

UnsetKey ensures that no value is present for Key, not even an explicit nil
### GetRapidCode

`func (o *AppReleaseDto) GetRapidCode() string`

GetRapidCode returns the RapidCode field if non-nil, zero value otherwise.

### GetRapidCodeOk

`func (o *AppReleaseDto) GetRapidCodeOk() (*string, bool)`

GetRapidCodeOk returns a tuple with the RapidCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRapidCode

`func (o *AppReleaseDto) SetRapidCode(v string)`

SetRapidCode sets RapidCode field to given value.

### HasRapidCode

`func (o *AppReleaseDto) HasRapidCode() bool`

HasRapidCode returns a boolean if a field has been set.

### SetRapidCodeNil

`func (o *AppReleaseDto) SetRapidCodeNil(b bool)`

 SetRapidCodeNil sets the value for RapidCode to be an explicit nil

### UnsetRapidCode
`func (o *AppReleaseDto) UnsetRapidCode()`

UnsetRapidCode ensures that no value is present for RapidCode, not even an explicit nil
### GetSize

`func (o *AppReleaseDto) GetSize() int64`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *AppReleaseDto) GetSizeOk() (*int64, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *AppReleaseDto) SetSize(v int64)`

SetSize sets Size field to given value.

### HasSize

`func (o *AppReleaseDto) HasSize() bool`

HasSize returns a boolean if a field has been set.

### SetSizeNil

`func (o *AppReleaseDto) SetSizeNil(b bool)`

 SetSizeNil sets the value for Size to be an explicit nil

### UnsetSize
`func (o *AppReleaseDto) UnsetSize()`

UnsetSize ensures that no value is present for Size, not even an explicit nil
### GetMd5

`func (o *AppReleaseDto) GetMd5() string`

GetMd5 returns the Md5 field if non-nil, zero value otherwise.

### GetMd5Ok

`func (o *AppReleaseDto) GetMd5Ok() (*string, bool)`

GetMd5Ok returns a tuple with the Md5 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMd5

`func (o *AppReleaseDto) SetMd5(v string)`

SetMd5 sets Md5 field to given value.

### HasMd5

`func (o *AppReleaseDto) HasMd5() bool`

HasMd5 returns a boolean if a field has been set.

### SetMd5Nil

`func (o *AppReleaseDto) SetMd5Nil(b bool)`

 SetMd5Nil sets the value for Md5 to be an explicit nil

### UnsetMd5
`func (o *AppReleaseDto) UnsetMd5()`

UnsetMd5 ensures that no value is present for Md5, not even an explicit nil
### GetSliceMd5

`func (o *AppReleaseDto) GetSliceMd5() string`

GetSliceMd5 returns the SliceMd5 field if non-nil, zero value otherwise.

### GetSliceMd5Ok

`func (o *AppReleaseDto) GetSliceMd5Ok() (*string, bool)`

GetSliceMd5Ok returns a tuple with the SliceMd5 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSliceMd5

`func (o *AppReleaseDto) SetSliceMd5(v string)`

SetSliceMd5 sets SliceMd5 field to given value.

### HasSliceMd5

`func (o *AppReleaseDto) HasSliceMd5() bool`

HasSliceMd5 returns a boolean if a field has been set.

### SetSliceMd5Nil

`func (o *AppReleaseDto) SetSliceMd5Nil(b bool)`

 SetSliceMd5Nil sets the value for SliceMd5 to be an explicit nil

### UnsetSliceMd5
`func (o *AppReleaseDto) UnsetSliceMd5()`

UnsetSliceMd5 ensures that no value is present for SliceMd5, not even an explicit nil
### GetDownloadUrl

`func (o *AppReleaseDto) GetDownloadUrl() string`

GetDownloadUrl returns the DownloadUrl field if non-nil, zero value otherwise.

### GetDownloadUrlOk

`func (o *AppReleaseDto) GetDownloadUrlOk() (*string, bool)`

GetDownloadUrlOk returns a tuple with the DownloadUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDownloadUrl

`func (o *AppReleaseDto) SetDownloadUrl(v string)`

SetDownloadUrl sets DownloadUrl field to given value.

### HasDownloadUrl

`func (o *AppReleaseDto) HasDownloadUrl() bool`

HasDownloadUrl returns a boolean if a field has been set.

### SetDownloadUrlNil

`func (o *AppReleaseDto) SetDownloadUrlNil(b bool)`

 SetDownloadUrlNil sets the value for DownloadUrl to be an explicit nil

### UnsetDownloadUrl
`func (o *AppReleaseDto) UnsetDownloadUrl()`

UnsetDownloadUrl ensures that no value is present for DownloadUrl, not even an explicit nil
### GetArtifactType

`func (o *AppReleaseDto) GetArtifactType() ArtifactType`

GetArtifactType returns the ArtifactType field if non-nil, zero value otherwise.

### GetArtifactTypeOk

`func (o *AppReleaseDto) GetArtifactTypeOk() (*ArtifactType, bool)`

GetArtifactTypeOk returns a tuple with the ArtifactType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArtifactType

`func (o *AppReleaseDto) SetArtifactType(v ArtifactType)`

SetArtifactType sets ArtifactType field to given value.

### HasArtifactType

`func (o *AppReleaseDto) HasArtifactType() bool`

HasArtifactType returns a boolean if a field has been set.

### GetIsForceUpdate

`func (o *AppReleaseDto) GetIsForceUpdate() bool`

GetIsForceUpdate returns the IsForceUpdate field if non-nil, zero value otherwise.

### GetIsForceUpdateOk

`func (o *AppReleaseDto) GetIsForceUpdateOk() (*bool, bool)`

GetIsForceUpdateOk returns a tuple with the IsForceUpdate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsForceUpdate

`func (o *AppReleaseDto) SetIsForceUpdate(v bool)`

SetIsForceUpdate sets IsForceUpdate field to given value.

### HasIsForceUpdate

`func (o *AppReleaseDto) HasIsForceUpdate() bool`

HasIsForceUpdate returns a boolean if a field has been set.

### GetAppId

`func (o *AppReleaseDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *AppReleaseDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *AppReleaseDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *AppReleaseDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetIsEnabled

`func (o *AppReleaseDto) GetIsEnabled() bool`

GetIsEnabled returns the IsEnabled field if non-nil, zero value otherwise.

### GetIsEnabledOk

`func (o *AppReleaseDto) GetIsEnabledOk() (*bool, bool)`

GetIsEnabledOk returns a tuple with the IsEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsEnabled

`func (o *AppReleaseDto) SetIsEnabled(v bool)`

SetIsEnabled sets IsEnabled field to given value.

### HasIsEnabled

`func (o *AppReleaseDto) HasIsEnabled() bool`

HasIsEnabled returns a boolean if a field has been set.

### GetChannel

`func (o *AppReleaseDto) GetChannel() string`

GetChannel returns the Channel field if non-nil, zero value otherwise.

### GetChannelOk

`func (o *AppReleaseDto) GetChannelOk() (*string, bool)`

GetChannelOk returns a tuple with the Channel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannel

`func (o *AppReleaseDto) SetChannel(v string)`

SetChannel sets Channel field to given value.

### HasChannel

`func (o *AppReleaseDto) HasChannel() bool`

HasChannel returns a boolean if a field has been set.

### SetChannelNil

`func (o *AppReleaseDto) SetChannelNil(b bool)`

 SetChannelNil sets the value for Channel to be an explicit nil

### UnsetChannel
`func (o *AppReleaseDto) UnsetChannel()`

UnsetChannel ensures that no value is present for Channel, not even an explicit nil
### GetEnvironment

`func (o *AppReleaseDto) GetEnvironment() string`

GetEnvironment returns the Environment field if non-nil, zero value otherwise.

### GetEnvironmentOk

`func (o *AppReleaseDto) GetEnvironmentOk() (*string, bool)`

GetEnvironmentOk returns a tuple with the Environment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnvironment

`func (o *AppReleaseDto) SetEnvironment(v string)`

SetEnvironment sets Environment field to given value.

### HasEnvironment

`func (o *AppReleaseDto) HasEnvironment() bool`

HasEnvironment returns a boolean if a field has been set.

### SetEnvironmentNil

`func (o *AppReleaseDto) SetEnvironmentNil(b bool)`

 SetEnvironmentNil sets the value for Environment to be an explicit nil

### UnsetEnvironment
`func (o *AppReleaseDto) UnsetEnvironment()`

UnsetEnvironment ensures that no value is present for Environment, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


