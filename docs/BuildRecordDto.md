# BuildRecordDto

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
**AppId** | Pointer to **string** | 应用ID | [optional] 
**AppName** | Pointer to **NullableString** | 应用名称 | [optional] 
**Version** | Pointer to **NullableString** | 版本号 | [optional] 
**Branch** | Pointer to **NullableString** | 分支名称 | [optional] 
**CommitHash** | Pointer to **NullableString** | 提交哈希 | [optional] 
**Trigger** | Pointer to [**BuildTrigger**](BuildTrigger.md) |  | [optional] 
**Platform** | Pointer to [**AppPlatform**](AppPlatform.md) |  | [optional] 
**ArtifactType** | Pointer to [**ArtifactType**](ArtifactType.md) |  | [optional] 
**Architecture** | Pointer to **NullableString** | 目标架构；空值或空字符串表示通用制品。 | [optional] 
**Environment** | Pointer to **NullableString** | 环境 | [optional] 
**BuildNumber** | Pointer to **NullableInt64** | 构建号 | [optional] 
**Status** | Pointer to [**BuildStatus**](BuildStatus.md) |  | [optional] 
**StartedAt** | Pointer to **time.Time** | 开始时间 | [optional] 
**CompletedAt** | Pointer to **NullableTime** | 结束时间 | [optional] 
**Logs** | Pointer to **NullableString** | 构建日志 | [optional] 
**ErrorMessage** | Pointer to **NullableString** | 错误信息 | [optional] 
**ArtifactUrl** | Pointer to **NullableString** | 构建产物下载地址 | [optional] 
**ArtifactSize** | Pointer to **NullableInt64** | 构建产物大小 (字节) | [optional] 
**CiSystem** | Pointer to **NullableString** | CI/CD 系统信息 | [optional] 
**CiBuildId** | Pointer to **NullableString** | CI/CD 构建ID | [optional] 
**CiBuildUrl** | Pointer to **NullableString** | CI/CD 构建URL | [optional] 
**Duration** | Pointer to **NullableInt32** | 构建持续时间 (秒) | [optional] 

## Methods

### NewBuildRecordDto

`func NewBuildRecordDto() *BuildRecordDto`

NewBuildRecordDto instantiates a new BuildRecordDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBuildRecordDtoWithDefaults

`func NewBuildRecordDtoWithDefaults() *BuildRecordDto`

NewBuildRecordDtoWithDefaults instantiates a new BuildRecordDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *BuildRecordDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *BuildRecordDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *BuildRecordDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *BuildRecordDto) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreationTime

`func (o *BuildRecordDto) GetCreationTime() time.Time`

GetCreationTime returns the CreationTime field if non-nil, zero value otherwise.

### GetCreationTimeOk

`func (o *BuildRecordDto) GetCreationTimeOk() (*time.Time, bool)`

GetCreationTimeOk returns a tuple with the CreationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreationTime

`func (o *BuildRecordDto) SetCreationTime(v time.Time)`

SetCreationTime sets CreationTime field to given value.

### HasCreationTime

`func (o *BuildRecordDto) HasCreationTime() bool`

HasCreationTime returns a boolean if a field has been set.

### GetCreatorId

`func (o *BuildRecordDto) GetCreatorId() string`

GetCreatorId returns the CreatorId field if non-nil, zero value otherwise.

### GetCreatorIdOk

`func (o *BuildRecordDto) GetCreatorIdOk() (*string, bool)`

GetCreatorIdOk returns a tuple with the CreatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatorId

`func (o *BuildRecordDto) SetCreatorId(v string)`

SetCreatorId sets CreatorId field to given value.

### HasCreatorId

`func (o *BuildRecordDto) HasCreatorId() bool`

HasCreatorId returns a boolean if a field has been set.

### SetCreatorIdNil

`func (o *BuildRecordDto) SetCreatorIdNil(b bool)`

 SetCreatorIdNil sets the value for CreatorId to be an explicit nil

### UnsetCreatorId
`func (o *BuildRecordDto) UnsetCreatorId()`

UnsetCreatorId ensures that no value is present for CreatorId, not even an explicit nil
### GetLastModificationTime

`func (o *BuildRecordDto) GetLastModificationTime() time.Time`

GetLastModificationTime returns the LastModificationTime field if non-nil, zero value otherwise.

### GetLastModificationTimeOk

`func (o *BuildRecordDto) GetLastModificationTimeOk() (*time.Time, bool)`

GetLastModificationTimeOk returns a tuple with the LastModificationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModificationTime

`func (o *BuildRecordDto) SetLastModificationTime(v time.Time)`

SetLastModificationTime sets LastModificationTime field to given value.

### HasLastModificationTime

`func (o *BuildRecordDto) HasLastModificationTime() bool`

HasLastModificationTime returns a boolean if a field has been set.

### SetLastModificationTimeNil

`func (o *BuildRecordDto) SetLastModificationTimeNil(b bool)`

 SetLastModificationTimeNil sets the value for LastModificationTime to be an explicit nil

### UnsetLastModificationTime
`func (o *BuildRecordDto) UnsetLastModificationTime()`

UnsetLastModificationTime ensures that no value is present for LastModificationTime, not even an explicit nil
### GetLastModifierId

`func (o *BuildRecordDto) GetLastModifierId() string`

GetLastModifierId returns the LastModifierId field if non-nil, zero value otherwise.

### GetLastModifierIdOk

`func (o *BuildRecordDto) GetLastModifierIdOk() (*string, bool)`

GetLastModifierIdOk returns a tuple with the LastModifierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModifierId

`func (o *BuildRecordDto) SetLastModifierId(v string)`

SetLastModifierId sets LastModifierId field to given value.

### HasLastModifierId

`func (o *BuildRecordDto) HasLastModifierId() bool`

HasLastModifierId returns a boolean if a field has been set.

### SetLastModifierIdNil

`func (o *BuildRecordDto) SetLastModifierIdNil(b bool)`

 SetLastModifierIdNil sets the value for LastModifierId to be an explicit nil

### UnsetLastModifierId
`func (o *BuildRecordDto) UnsetLastModifierId()`

UnsetLastModifierId ensures that no value is present for LastModifierId, not even an explicit nil
### GetIsDeleted

`func (o *BuildRecordDto) GetIsDeleted() bool`

GetIsDeleted returns the IsDeleted field if non-nil, zero value otherwise.

### GetIsDeletedOk

`func (o *BuildRecordDto) GetIsDeletedOk() (*bool, bool)`

GetIsDeletedOk returns a tuple with the IsDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDeleted

`func (o *BuildRecordDto) SetIsDeleted(v bool)`

SetIsDeleted sets IsDeleted field to given value.

### HasIsDeleted

`func (o *BuildRecordDto) HasIsDeleted() bool`

HasIsDeleted returns a boolean if a field has been set.

### GetDeleterId

`func (o *BuildRecordDto) GetDeleterId() string`

GetDeleterId returns the DeleterId field if non-nil, zero value otherwise.

### GetDeleterIdOk

`func (o *BuildRecordDto) GetDeleterIdOk() (*string, bool)`

GetDeleterIdOk returns a tuple with the DeleterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleterId

`func (o *BuildRecordDto) SetDeleterId(v string)`

SetDeleterId sets DeleterId field to given value.

### HasDeleterId

`func (o *BuildRecordDto) HasDeleterId() bool`

HasDeleterId returns a boolean if a field has been set.

### SetDeleterIdNil

`func (o *BuildRecordDto) SetDeleterIdNil(b bool)`

 SetDeleterIdNil sets the value for DeleterId to be an explicit nil

### UnsetDeleterId
`func (o *BuildRecordDto) UnsetDeleterId()`

UnsetDeleterId ensures that no value is present for DeleterId, not even an explicit nil
### GetDeletionTime

`func (o *BuildRecordDto) GetDeletionTime() time.Time`

GetDeletionTime returns the DeletionTime field if non-nil, zero value otherwise.

### GetDeletionTimeOk

`func (o *BuildRecordDto) GetDeletionTimeOk() (*time.Time, bool)`

GetDeletionTimeOk returns a tuple with the DeletionTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletionTime

`func (o *BuildRecordDto) SetDeletionTime(v time.Time)`

SetDeletionTime sets DeletionTime field to given value.

### HasDeletionTime

`func (o *BuildRecordDto) HasDeletionTime() bool`

HasDeletionTime returns a boolean if a field has been set.

### SetDeletionTimeNil

`func (o *BuildRecordDto) SetDeletionTimeNil(b bool)`

 SetDeletionTimeNil sets the value for DeletionTime to be an explicit nil

### UnsetDeletionTime
`func (o *BuildRecordDto) UnsetDeletionTime()`

UnsetDeletionTime ensures that no value is present for DeletionTime, not even an explicit nil
### GetAppId

`func (o *BuildRecordDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *BuildRecordDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *BuildRecordDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *BuildRecordDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetAppName

`func (o *BuildRecordDto) GetAppName() string`

GetAppName returns the AppName field if non-nil, zero value otherwise.

### GetAppNameOk

`func (o *BuildRecordDto) GetAppNameOk() (*string, bool)`

GetAppNameOk returns a tuple with the AppName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppName

`func (o *BuildRecordDto) SetAppName(v string)`

SetAppName sets AppName field to given value.

### HasAppName

`func (o *BuildRecordDto) HasAppName() bool`

HasAppName returns a boolean if a field has been set.

### SetAppNameNil

`func (o *BuildRecordDto) SetAppNameNil(b bool)`

 SetAppNameNil sets the value for AppName to be an explicit nil

### UnsetAppName
`func (o *BuildRecordDto) UnsetAppName()`

UnsetAppName ensures that no value is present for AppName, not even an explicit nil
### GetVersion

`func (o *BuildRecordDto) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *BuildRecordDto) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *BuildRecordDto) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *BuildRecordDto) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### SetVersionNil

`func (o *BuildRecordDto) SetVersionNil(b bool)`

 SetVersionNil sets the value for Version to be an explicit nil

### UnsetVersion
`func (o *BuildRecordDto) UnsetVersion()`

UnsetVersion ensures that no value is present for Version, not even an explicit nil
### GetBranch

`func (o *BuildRecordDto) GetBranch() string`

GetBranch returns the Branch field if non-nil, zero value otherwise.

### GetBranchOk

`func (o *BuildRecordDto) GetBranchOk() (*string, bool)`

GetBranchOk returns a tuple with the Branch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBranch

`func (o *BuildRecordDto) SetBranch(v string)`

SetBranch sets Branch field to given value.

### HasBranch

`func (o *BuildRecordDto) HasBranch() bool`

HasBranch returns a boolean if a field has been set.

### SetBranchNil

`func (o *BuildRecordDto) SetBranchNil(b bool)`

 SetBranchNil sets the value for Branch to be an explicit nil

### UnsetBranch
`func (o *BuildRecordDto) UnsetBranch()`

UnsetBranch ensures that no value is present for Branch, not even an explicit nil
### GetCommitHash

`func (o *BuildRecordDto) GetCommitHash() string`

GetCommitHash returns the CommitHash field if non-nil, zero value otherwise.

### GetCommitHashOk

`func (o *BuildRecordDto) GetCommitHashOk() (*string, bool)`

GetCommitHashOk returns a tuple with the CommitHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommitHash

`func (o *BuildRecordDto) SetCommitHash(v string)`

SetCommitHash sets CommitHash field to given value.

### HasCommitHash

`func (o *BuildRecordDto) HasCommitHash() bool`

HasCommitHash returns a boolean if a field has been set.

### SetCommitHashNil

`func (o *BuildRecordDto) SetCommitHashNil(b bool)`

 SetCommitHashNil sets the value for CommitHash to be an explicit nil

### UnsetCommitHash
`func (o *BuildRecordDto) UnsetCommitHash()`

UnsetCommitHash ensures that no value is present for CommitHash, not even an explicit nil
### GetTrigger

`func (o *BuildRecordDto) GetTrigger() BuildTrigger`

GetTrigger returns the Trigger field if non-nil, zero value otherwise.

### GetTriggerOk

`func (o *BuildRecordDto) GetTriggerOk() (*BuildTrigger, bool)`

GetTriggerOk returns a tuple with the Trigger field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrigger

`func (o *BuildRecordDto) SetTrigger(v BuildTrigger)`

SetTrigger sets Trigger field to given value.

### HasTrigger

`func (o *BuildRecordDto) HasTrigger() bool`

HasTrigger returns a boolean if a field has been set.

### GetPlatform

`func (o *BuildRecordDto) GetPlatform() AppPlatform`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *BuildRecordDto) GetPlatformOk() (*AppPlatform, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *BuildRecordDto) SetPlatform(v AppPlatform)`

SetPlatform sets Platform field to given value.

### HasPlatform

`func (o *BuildRecordDto) HasPlatform() bool`

HasPlatform returns a boolean if a field has been set.

### GetArtifactType

`func (o *BuildRecordDto) GetArtifactType() ArtifactType`

GetArtifactType returns the ArtifactType field if non-nil, zero value otherwise.

### GetArtifactTypeOk

`func (o *BuildRecordDto) GetArtifactTypeOk() (*ArtifactType, bool)`

GetArtifactTypeOk returns a tuple with the ArtifactType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArtifactType

`func (o *BuildRecordDto) SetArtifactType(v ArtifactType)`

SetArtifactType sets ArtifactType field to given value.

### HasArtifactType

`func (o *BuildRecordDto) HasArtifactType() bool`

HasArtifactType returns a boolean if a field has been set.

### GetArchitecture

`func (o *BuildRecordDto) GetArchitecture() string`

GetArchitecture returns the Architecture field if non-nil, zero value otherwise.

### GetArchitectureOk

`func (o *BuildRecordDto) GetArchitectureOk() (*string, bool)`

GetArchitectureOk returns a tuple with the Architecture field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchitecture

`func (o *BuildRecordDto) SetArchitecture(v string)`

SetArchitecture sets Architecture field to given value.

### HasArchitecture

`func (o *BuildRecordDto) HasArchitecture() bool`

HasArchitecture returns a boolean if a field has been set.

### SetArchitectureNil

`func (o *BuildRecordDto) SetArchitectureNil(b bool)`

 SetArchitectureNil sets the value for Architecture to be an explicit nil

### UnsetArchitecture
`func (o *BuildRecordDto) UnsetArchitecture()`

UnsetArchitecture ensures that no value is present for Architecture, not even an explicit nil
### GetEnvironment

`func (o *BuildRecordDto) GetEnvironment() string`

GetEnvironment returns the Environment field if non-nil, zero value otherwise.

### GetEnvironmentOk

`func (o *BuildRecordDto) GetEnvironmentOk() (*string, bool)`

GetEnvironmentOk returns a tuple with the Environment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnvironment

`func (o *BuildRecordDto) SetEnvironment(v string)`

SetEnvironment sets Environment field to given value.

### HasEnvironment

`func (o *BuildRecordDto) HasEnvironment() bool`

HasEnvironment returns a boolean if a field has been set.

### SetEnvironmentNil

`func (o *BuildRecordDto) SetEnvironmentNil(b bool)`

 SetEnvironmentNil sets the value for Environment to be an explicit nil

### UnsetEnvironment
`func (o *BuildRecordDto) UnsetEnvironment()`

UnsetEnvironment ensures that no value is present for Environment, not even an explicit nil
### GetBuildNumber

`func (o *BuildRecordDto) GetBuildNumber() int64`

GetBuildNumber returns the BuildNumber field if non-nil, zero value otherwise.

### GetBuildNumberOk

`func (o *BuildRecordDto) GetBuildNumberOk() (*int64, bool)`

GetBuildNumberOk returns a tuple with the BuildNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildNumber

`func (o *BuildRecordDto) SetBuildNumber(v int64)`

SetBuildNumber sets BuildNumber field to given value.

### HasBuildNumber

`func (o *BuildRecordDto) HasBuildNumber() bool`

HasBuildNumber returns a boolean if a field has been set.

### SetBuildNumberNil

`func (o *BuildRecordDto) SetBuildNumberNil(b bool)`

 SetBuildNumberNil sets the value for BuildNumber to be an explicit nil

### UnsetBuildNumber
`func (o *BuildRecordDto) UnsetBuildNumber()`

UnsetBuildNumber ensures that no value is present for BuildNumber, not even an explicit nil
### GetStatus

`func (o *BuildRecordDto) GetStatus() BuildStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *BuildRecordDto) GetStatusOk() (*BuildStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *BuildRecordDto) SetStatus(v BuildStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *BuildRecordDto) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetStartedAt

`func (o *BuildRecordDto) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *BuildRecordDto) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *BuildRecordDto) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.

### HasStartedAt

`func (o *BuildRecordDto) HasStartedAt() bool`

HasStartedAt returns a boolean if a field has been set.

### GetCompletedAt

`func (o *BuildRecordDto) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *BuildRecordDto) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *BuildRecordDto) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *BuildRecordDto) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *BuildRecordDto) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *BuildRecordDto) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetLogs

`func (o *BuildRecordDto) GetLogs() string`

GetLogs returns the Logs field if non-nil, zero value otherwise.

### GetLogsOk

`func (o *BuildRecordDto) GetLogsOk() (*string, bool)`

GetLogsOk returns a tuple with the Logs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogs

`func (o *BuildRecordDto) SetLogs(v string)`

SetLogs sets Logs field to given value.

### HasLogs

`func (o *BuildRecordDto) HasLogs() bool`

HasLogs returns a boolean if a field has been set.

### SetLogsNil

`func (o *BuildRecordDto) SetLogsNil(b bool)`

 SetLogsNil sets the value for Logs to be an explicit nil

### UnsetLogs
`func (o *BuildRecordDto) UnsetLogs()`

UnsetLogs ensures that no value is present for Logs, not even an explicit nil
### GetErrorMessage

`func (o *BuildRecordDto) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *BuildRecordDto) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *BuildRecordDto) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *BuildRecordDto) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.

### SetErrorMessageNil

`func (o *BuildRecordDto) SetErrorMessageNil(b bool)`

 SetErrorMessageNil sets the value for ErrorMessage to be an explicit nil

### UnsetErrorMessage
`func (o *BuildRecordDto) UnsetErrorMessage()`

UnsetErrorMessage ensures that no value is present for ErrorMessage, not even an explicit nil
### GetArtifactUrl

`func (o *BuildRecordDto) GetArtifactUrl() string`

GetArtifactUrl returns the ArtifactUrl field if non-nil, zero value otherwise.

### GetArtifactUrlOk

`func (o *BuildRecordDto) GetArtifactUrlOk() (*string, bool)`

GetArtifactUrlOk returns a tuple with the ArtifactUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArtifactUrl

`func (o *BuildRecordDto) SetArtifactUrl(v string)`

SetArtifactUrl sets ArtifactUrl field to given value.

### HasArtifactUrl

`func (o *BuildRecordDto) HasArtifactUrl() bool`

HasArtifactUrl returns a boolean if a field has been set.

### SetArtifactUrlNil

`func (o *BuildRecordDto) SetArtifactUrlNil(b bool)`

 SetArtifactUrlNil sets the value for ArtifactUrl to be an explicit nil

### UnsetArtifactUrl
`func (o *BuildRecordDto) UnsetArtifactUrl()`

UnsetArtifactUrl ensures that no value is present for ArtifactUrl, not even an explicit nil
### GetArtifactSize

`func (o *BuildRecordDto) GetArtifactSize() int64`

GetArtifactSize returns the ArtifactSize field if non-nil, zero value otherwise.

### GetArtifactSizeOk

`func (o *BuildRecordDto) GetArtifactSizeOk() (*int64, bool)`

GetArtifactSizeOk returns a tuple with the ArtifactSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArtifactSize

`func (o *BuildRecordDto) SetArtifactSize(v int64)`

SetArtifactSize sets ArtifactSize field to given value.

### HasArtifactSize

`func (o *BuildRecordDto) HasArtifactSize() bool`

HasArtifactSize returns a boolean if a field has been set.

### SetArtifactSizeNil

`func (o *BuildRecordDto) SetArtifactSizeNil(b bool)`

 SetArtifactSizeNil sets the value for ArtifactSize to be an explicit nil

### UnsetArtifactSize
`func (o *BuildRecordDto) UnsetArtifactSize()`

UnsetArtifactSize ensures that no value is present for ArtifactSize, not even an explicit nil
### GetCiSystem

`func (o *BuildRecordDto) GetCiSystem() string`

GetCiSystem returns the CiSystem field if non-nil, zero value otherwise.

### GetCiSystemOk

`func (o *BuildRecordDto) GetCiSystemOk() (*string, bool)`

GetCiSystemOk returns a tuple with the CiSystem field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCiSystem

`func (o *BuildRecordDto) SetCiSystem(v string)`

SetCiSystem sets CiSystem field to given value.

### HasCiSystem

`func (o *BuildRecordDto) HasCiSystem() bool`

HasCiSystem returns a boolean if a field has been set.

### SetCiSystemNil

`func (o *BuildRecordDto) SetCiSystemNil(b bool)`

 SetCiSystemNil sets the value for CiSystem to be an explicit nil

### UnsetCiSystem
`func (o *BuildRecordDto) UnsetCiSystem()`

UnsetCiSystem ensures that no value is present for CiSystem, not even an explicit nil
### GetCiBuildId

`func (o *BuildRecordDto) GetCiBuildId() string`

GetCiBuildId returns the CiBuildId field if non-nil, zero value otherwise.

### GetCiBuildIdOk

`func (o *BuildRecordDto) GetCiBuildIdOk() (*string, bool)`

GetCiBuildIdOk returns a tuple with the CiBuildId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCiBuildId

`func (o *BuildRecordDto) SetCiBuildId(v string)`

SetCiBuildId sets CiBuildId field to given value.

### HasCiBuildId

`func (o *BuildRecordDto) HasCiBuildId() bool`

HasCiBuildId returns a boolean if a field has been set.

### SetCiBuildIdNil

`func (o *BuildRecordDto) SetCiBuildIdNil(b bool)`

 SetCiBuildIdNil sets the value for CiBuildId to be an explicit nil

### UnsetCiBuildId
`func (o *BuildRecordDto) UnsetCiBuildId()`

UnsetCiBuildId ensures that no value is present for CiBuildId, not even an explicit nil
### GetCiBuildUrl

`func (o *BuildRecordDto) GetCiBuildUrl() string`

GetCiBuildUrl returns the CiBuildUrl field if non-nil, zero value otherwise.

### GetCiBuildUrlOk

`func (o *BuildRecordDto) GetCiBuildUrlOk() (*string, bool)`

GetCiBuildUrlOk returns a tuple with the CiBuildUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCiBuildUrl

`func (o *BuildRecordDto) SetCiBuildUrl(v string)`

SetCiBuildUrl sets CiBuildUrl field to given value.

### HasCiBuildUrl

`func (o *BuildRecordDto) HasCiBuildUrl() bool`

HasCiBuildUrl returns a boolean if a field has been set.

### SetCiBuildUrlNil

`func (o *BuildRecordDto) SetCiBuildUrlNil(b bool)`

 SetCiBuildUrlNil sets the value for CiBuildUrl to be an explicit nil

### UnsetCiBuildUrl
`func (o *BuildRecordDto) UnsetCiBuildUrl()`

UnsetCiBuildUrl ensures that no value is present for CiBuildUrl, not even an explicit nil
### GetDuration

`func (o *BuildRecordDto) GetDuration() int32`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *BuildRecordDto) GetDurationOk() (*int32, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *BuildRecordDto) SetDuration(v int32)`

SetDuration sets Duration field to given value.

### HasDuration

`func (o *BuildRecordDto) HasDuration() bool`

HasDuration returns a boolean if a field has been set.

### SetDurationNil

`func (o *BuildRecordDto) SetDurationNil(b bool)`

 SetDurationNil sets the value for Duration to be an explicit nil

### UnsetDuration
`func (o *BuildRecordDto) UnsetDuration()`

UnsetDuration ensures that no value is present for Duration, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


