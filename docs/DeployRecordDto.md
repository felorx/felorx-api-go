# DeployRecordDto

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
**BuildRecordId** | Pointer to **string** | 构建记录ID | [optional] 
**BuildRecordVersion** | Pointer to **NullableString** | 构建记录版本 | [optional] 
**Version** | Pointer to **NullableString** | 版本号 | [optional] 
**Platform** | Pointer to [**AppPlatform**](AppPlatform.md) |  | [optional] 
**Environment** | Pointer to **NullableString** | 部署环境 | [optional] 
**Status** | Pointer to [**DeployStatus**](DeployStatus.md) |  | [optional] 
**StartedAt** | Pointer to **time.Time** | 开始时间 | [optional] 
**CompletedAt** | Pointer to **NullableTime** | 结束时间 | [optional] 
**ErrorMessage** | Pointer to **NullableString** | 错误信息 | [optional] 
**DeployUrl** | Pointer to **NullableString** | 部署地址 | [optional] 
**DeployTarget** | Pointer to **NullableString** | 部署目标 | [optional] 
**DeployChannel** | Pointer to **NullableString** | 部署渠道 | [optional] 
**CiSystem** | Pointer to **NullableString** | CI/CD 系统信息 | [optional] 
**CiDeployId** | Pointer to **NullableString** | CI/CD 部署ID | [optional] 
**CiDeployUrl** | Pointer to **NullableString** | CI/CD 部署URL | [optional] 
**Duration** | Pointer to **NullableInt32** | 部署持续时间 (秒) | [optional] 

## Methods

### NewDeployRecordDto

`func NewDeployRecordDto() *DeployRecordDto`

NewDeployRecordDto instantiates a new DeployRecordDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeployRecordDtoWithDefaults

`func NewDeployRecordDtoWithDefaults() *DeployRecordDto`

NewDeployRecordDtoWithDefaults instantiates a new DeployRecordDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *DeployRecordDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DeployRecordDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DeployRecordDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *DeployRecordDto) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreationTime

`func (o *DeployRecordDto) GetCreationTime() time.Time`

GetCreationTime returns the CreationTime field if non-nil, zero value otherwise.

### GetCreationTimeOk

`func (o *DeployRecordDto) GetCreationTimeOk() (*time.Time, bool)`

GetCreationTimeOk returns a tuple with the CreationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreationTime

`func (o *DeployRecordDto) SetCreationTime(v time.Time)`

SetCreationTime sets CreationTime field to given value.

### HasCreationTime

`func (o *DeployRecordDto) HasCreationTime() bool`

HasCreationTime returns a boolean if a field has been set.

### GetCreatorId

`func (o *DeployRecordDto) GetCreatorId() string`

GetCreatorId returns the CreatorId field if non-nil, zero value otherwise.

### GetCreatorIdOk

`func (o *DeployRecordDto) GetCreatorIdOk() (*string, bool)`

GetCreatorIdOk returns a tuple with the CreatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatorId

`func (o *DeployRecordDto) SetCreatorId(v string)`

SetCreatorId sets CreatorId field to given value.

### HasCreatorId

`func (o *DeployRecordDto) HasCreatorId() bool`

HasCreatorId returns a boolean if a field has been set.

### SetCreatorIdNil

`func (o *DeployRecordDto) SetCreatorIdNil(b bool)`

 SetCreatorIdNil sets the value for CreatorId to be an explicit nil

### UnsetCreatorId
`func (o *DeployRecordDto) UnsetCreatorId()`

UnsetCreatorId ensures that no value is present for CreatorId, not even an explicit nil
### GetLastModificationTime

`func (o *DeployRecordDto) GetLastModificationTime() time.Time`

GetLastModificationTime returns the LastModificationTime field if non-nil, zero value otherwise.

### GetLastModificationTimeOk

`func (o *DeployRecordDto) GetLastModificationTimeOk() (*time.Time, bool)`

GetLastModificationTimeOk returns a tuple with the LastModificationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModificationTime

`func (o *DeployRecordDto) SetLastModificationTime(v time.Time)`

SetLastModificationTime sets LastModificationTime field to given value.

### HasLastModificationTime

`func (o *DeployRecordDto) HasLastModificationTime() bool`

HasLastModificationTime returns a boolean if a field has been set.

### SetLastModificationTimeNil

`func (o *DeployRecordDto) SetLastModificationTimeNil(b bool)`

 SetLastModificationTimeNil sets the value for LastModificationTime to be an explicit nil

### UnsetLastModificationTime
`func (o *DeployRecordDto) UnsetLastModificationTime()`

UnsetLastModificationTime ensures that no value is present for LastModificationTime, not even an explicit nil
### GetLastModifierId

`func (o *DeployRecordDto) GetLastModifierId() string`

GetLastModifierId returns the LastModifierId field if non-nil, zero value otherwise.

### GetLastModifierIdOk

`func (o *DeployRecordDto) GetLastModifierIdOk() (*string, bool)`

GetLastModifierIdOk returns a tuple with the LastModifierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModifierId

`func (o *DeployRecordDto) SetLastModifierId(v string)`

SetLastModifierId sets LastModifierId field to given value.

### HasLastModifierId

`func (o *DeployRecordDto) HasLastModifierId() bool`

HasLastModifierId returns a boolean if a field has been set.

### SetLastModifierIdNil

`func (o *DeployRecordDto) SetLastModifierIdNil(b bool)`

 SetLastModifierIdNil sets the value for LastModifierId to be an explicit nil

### UnsetLastModifierId
`func (o *DeployRecordDto) UnsetLastModifierId()`

UnsetLastModifierId ensures that no value is present for LastModifierId, not even an explicit nil
### GetIsDeleted

`func (o *DeployRecordDto) GetIsDeleted() bool`

GetIsDeleted returns the IsDeleted field if non-nil, zero value otherwise.

### GetIsDeletedOk

`func (o *DeployRecordDto) GetIsDeletedOk() (*bool, bool)`

GetIsDeletedOk returns a tuple with the IsDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDeleted

`func (o *DeployRecordDto) SetIsDeleted(v bool)`

SetIsDeleted sets IsDeleted field to given value.

### HasIsDeleted

`func (o *DeployRecordDto) HasIsDeleted() bool`

HasIsDeleted returns a boolean if a field has been set.

### GetDeleterId

`func (o *DeployRecordDto) GetDeleterId() string`

GetDeleterId returns the DeleterId field if non-nil, zero value otherwise.

### GetDeleterIdOk

`func (o *DeployRecordDto) GetDeleterIdOk() (*string, bool)`

GetDeleterIdOk returns a tuple with the DeleterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleterId

`func (o *DeployRecordDto) SetDeleterId(v string)`

SetDeleterId sets DeleterId field to given value.

### HasDeleterId

`func (o *DeployRecordDto) HasDeleterId() bool`

HasDeleterId returns a boolean if a field has been set.

### SetDeleterIdNil

`func (o *DeployRecordDto) SetDeleterIdNil(b bool)`

 SetDeleterIdNil sets the value for DeleterId to be an explicit nil

### UnsetDeleterId
`func (o *DeployRecordDto) UnsetDeleterId()`

UnsetDeleterId ensures that no value is present for DeleterId, not even an explicit nil
### GetDeletionTime

`func (o *DeployRecordDto) GetDeletionTime() time.Time`

GetDeletionTime returns the DeletionTime field if non-nil, zero value otherwise.

### GetDeletionTimeOk

`func (o *DeployRecordDto) GetDeletionTimeOk() (*time.Time, bool)`

GetDeletionTimeOk returns a tuple with the DeletionTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletionTime

`func (o *DeployRecordDto) SetDeletionTime(v time.Time)`

SetDeletionTime sets DeletionTime field to given value.

### HasDeletionTime

`func (o *DeployRecordDto) HasDeletionTime() bool`

HasDeletionTime returns a boolean if a field has been set.

### SetDeletionTimeNil

`func (o *DeployRecordDto) SetDeletionTimeNil(b bool)`

 SetDeletionTimeNil sets the value for DeletionTime to be an explicit nil

### UnsetDeletionTime
`func (o *DeployRecordDto) UnsetDeletionTime()`

UnsetDeletionTime ensures that no value is present for DeletionTime, not even an explicit nil
### GetAppId

`func (o *DeployRecordDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *DeployRecordDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *DeployRecordDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *DeployRecordDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetAppName

`func (o *DeployRecordDto) GetAppName() string`

GetAppName returns the AppName field if non-nil, zero value otherwise.

### GetAppNameOk

`func (o *DeployRecordDto) GetAppNameOk() (*string, bool)`

GetAppNameOk returns a tuple with the AppName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppName

`func (o *DeployRecordDto) SetAppName(v string)`

SetAppName sets AppName field to given value.

### HasAppName

`func (o *DeployRecordDto) HasAppName() bool`

HasAppName returns a boolean if a field has been set.

### SetAppNameNil

`func (o *DeployRecordDto) SetAppNameNil(b bool)`

 SetAppNameNil sets the value for AppName to be an explicit nil

### UnsetAppName
`func (o *DeployRecordDto) UnsetAppName()`

UnsetAppName ensures that no value is present for AppName, not even an explicit nil
### GetBuildRecordId

`func (o *DeployRecordDto) GetBuildRecordId() string`

GetBuildRecordId returns the BuildRecordId field if non-nil, zero value otherwise.

### GetBuildRecordIdOk

`func (o *DeployRecordDto) GetBuildRecordIdOk() (*string, bool)`

GetBuildRecordIdOk returns a tuple with the BuildRecordId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildRecordId

`func (o *DeployRecordDto) SetBuildRecordId(v string)`

SetBuildRecordId sets BuildRecordId field to given value.

### HasBuildRecordId

`func (o *DeployRecordDto) HasBuildRecordId() bool`

HasBuildRecordId returns a boolean if a field has been set.

### GetBuildRecordVersion

`func (o *DeployRecordDto) GetBuildRecordVersion() string`

GetBuildRecordVersion returns the BuildRecordVersion field if non-nil, zero value otherwise.

### GetBuildRecordVersionOk

`func (o *DeployRecordDto) GetBuildRecordVersionOk() (*string, bool)`

GetBuildRecordVersionOk returns a tuple with the BuildRecordVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildRecordVersion

`func (o *DeployRecordDto) SetBuildRecordVersion(v string)`

SetBuildRecordVersion sets BuildRecordVersion field to given value.

### HasBuildRecordVersion

`func (o *DeployRecordDto) HasBuildRecordVersion() bool`

HasBuildRecordVersion returns a boolean if a field has been set.

### SetBuildRecordVersionNil

`func (o *DeployRecordDto) SetBuildRecordVersionNil(b bool)`

 SetBuildRecordVersionNil sets the value for BuildRecordVersion to be an explicit nil

### UnsetBuildRecordVersion
`func (o *DeployRecordDto) UnsetBuildRecordVersion()`

UnsetBuildRecordVersion ensures that no value is present for BuildRecordVersion, not even an explicit nil
### GetVersion

`func (o *DeployRecordDto) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *DeployRecordDto) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *DeployRecordDto) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *DeployRecordDto) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### SetVersionNil

`func (o *DeployRecordDto) SetVersionNil(b bool)`

 SetVersionNil sets the value for Version to be an explicit nil

### UnsetVersion
`func (o *DeployRecordDto) UnsetVersion()`

UnsetVersion ensures that no value is present for Version, not even an explicit nil
### GetPlatform

`func (o *DeployRecordDto) GetPlatform() AppPlatform`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *DeployRecordDto) GetPlatformOk() (*AppPlatform, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *DeployRecordDto) SetPlatform(v AppPlatform)`

SetPlatform sets Platform field to given value.

### HasPlatform

`func (o *DeployRecordDto) HasPlatform() bool`

HasPlatform returns a boolean if a field has been set.

### GetEnvironment

`func (o *DeployRecordDto) GetEnvironment() string`

GetEnvironment returns the Environment field if non-nil, zero value otherwise.

### GetEnvironmentOk

`func (o *DeployRecordDto) GetEnvironmentOk() (*string, bool)`

GetEnvironmentOk returns a tuple with the Environment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnvironment

`func (o *DeployRecordDto) SetEnvironment(v string)`

SetEnvironment sets Environment field to given value.

### HasEnvironment

`func (o *DeployRecordDto) HasEnvironment() bool`

HasEnvironment returns a boolean if a field has been set.

### SetEnvironmentNil

`func (o *DeployRecordDto) SetEnvironmentNil(b bool)`

 SetEnvironmentNil sets the value for Environment to be an explicit nil

### UnsetEnvironment
`func (o *DeployRecordDto) UnsetEnvironment()`

UnsetEnvironment ensures that no value is present for Environment, not even an explicit nil
### GetStatus

`func (o *DeployRecordDto) GetStatus() DeployStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DeployRecordDto) GetStatusOk() (*DeployStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DeployRecordDto) SetStatus(v DeployStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *DeployRecordDto) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetStartedAt

`func (o *DeployRecordDto) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *DeployRecordDto) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *DeployRecordDto) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.

### HasStartedAt

`func (o *DeployRecordDto) HasStartedAt() bool`

HasStartedAt returns a boolean if a field has been set.

### GetCompletedAt

`func (o *DeployRecordDto) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *DeployRecordDto) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *DeployRecordDto) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *DeployRecordDto) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *DeployRecordDto) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *DeployRecordDto) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetErrorMessage

`func (o *DeployRecordDto) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *DeployRecordDto) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *DeployRecordDto) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *DeployRecordDto) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.

### SetErrorMessageNil

`func (o *DeployRecordDto) SetErrorMessageNil(b bool)`

 SetErrorMessageNil sets the value for ErrorMessage to be an explicit nil

### UnsetErrorMessage
`func (o *DeployRecordDto) UnsetErrorMessage()`

UnsetErrorMessage ensures that no value is present for ErrorMessage, not even an explicit nil
### GetDeployUrl

`func (o *DeployRecordDto) GetDeployUrl() string`

GetDeployUrl returns the DeployUrl field if non-nil, zero value otherwise.

### GetDeployUrlOk

`func (o *DeployRecordDto) GetDeployUrlOk() (*string, bool)`

GetDeployUrlOk returns a tuple with the DeployUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeployUrl

`func (o *DeployRecordDto) SetDeployUrl(v string)`

SetDeployUrl sets DeployUrl field to given value.

### HasDeployUrl

`func (o *DeployRecordDto) HasDeployUrl() bool`

HasDeployUrl returns a boolean if a field has been set.

### SetDeployUrlNil

`func (o *DeployRecordDto) SetDeployUrlNil(b bool)`

 SetDeployUrlNil sets the value for DeployUrl to be an explicit nil

### UnsetDeployUrl
`func (o *DeployRecordDto) UnsetDeployUrl()`

UnsetDeployUrl ensures that no value is present for DeployUrl, not even an explicit nil
### GetDeployTarget

`func (o *DeployRecordDto) GetDeployTarget() string`

GetDeployTarget returns the DeployTarget field if non-nil, zero value otherwise.

### GetDeployTargetOk

`func (o *DeployRecordDto) GetDeployTargetOk() (*string, bool)`

GetDeployTargetOk returns a tuple with the DeployTarget field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeployTarget

`func (o *DeployRecordDto) SetDeployTarget(v string)`

SetDeployTarget sets DeployTarget field to given value.

### HasDeployTarget

`func (o *DeployRecordDto) HasDeployTarget() bool`

HasDeployTarget returns a boolean if a field has been set.

### SetDeployTargetNil

`func (o *DeployRecordDto) SetDeployTargetNil(b bool)`

 SetDeployTargetNil sets the value for DeployTarget to be an explicit nil

### UnsetDeployTarget
`func (o *DeployRecordDto) UnsetDeployTarget()`

UnsetDeployTarget ensures that no value is present for DeployTarget, not even an explicit nil
### GetDeployChannel

`func (o *DeployRecordDto) GetDeployChannel() string`

GetDeployChannel returns the DeployChannel field if non-nil, zero value otherwise.

### GetDeployChannelOk

`func (o *DeployRecordDto) GetDeployChannelOk() (*string, bool)`

GetDeployChannelOk returns a tuple with the DeployChannel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeployChannel

`func (o *DeployRecordDto) SetDeployChannel(v string)`

SetDeployChannel sets DeployChannel field to given value.

### HasDeployChannel

`func (o *DeployRecordDto) HasDeployChannel() bool`

HasDeployChannel returns a boolean if a field has been set.

### SetDeployChannelNil

`func (o *DeployRecordDto) SetDeployChannelNil(b bool)`

 SetDeployChannelNil sets the value for DeployChannel to be an explicit nil

### UnsetDeployChannel
`func (o *DeployRecordDto) UnsetDeployChannel()`

UnsetDeployChannel ensures that no value is present for DeployChannel, not even an explicit nil
### GetCiSystem

`func (o *DeployRecordDto) GetCiSystem() string`

GetCiSystem returns the CiSystem field if non-nil, zero value otherwise.

### GetCiSystemOk

`func (o *DeployRecordDto) GetCiSystemOk() (*string, bool)`

GetCiSystemOk returns a tuple with the CiSystem field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCiSystem

`func (o *DeployRecordDto) SetCiSystem(v string)`

SetCiSystem sets CiSystem field to given value.

### HasCiSystem

`func (o *DeployRecordDto) HasCiSystem() bool`

HasCiSystem returns a boolean if a field has been set.

### SetCiSystemNil

`func (o *DeployRecordDto) SetCiSystemNil(b bool)`

 SetCiSystemNil sets the value for CiSystem to be an explicit nil

### UnsetCiSystem
`func (o *DeployRecordDto) UnsetCiSystem()`

UnsetCiSystem ensures that no value is present for CiSystem, not even an explicit nil
### GetCiDeployId

`func (o *DeployRecordDto) GetCiDeployId() string`

GetCiDeployId returns the CiDeployId field if non-nil, zero value otherwise.

### GetCiDeployIdOk

`func (o *DeployRecordDto) GetCiDeployIdOk() (*string, bool)`

GetCiDeployIdOk returns a tuple with the CiDeployId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCiDeployId

`func (o *DeployRecordDto) SetCiDeployId(v string)`

SetCiDeployId sets CiDeployId field to given value.

### HasCiDeployId

`func (o *DeployRecordDto) HasCiDeployId() bool`

HasCiDeployId returns a boolean if a field has been set.

### SetCiDeployIdNil

`func (o *DeployRecordDto) SetCiDeployIdNil(b bool)`

 SetCiDeployIdNil sets the value for CiDeployId to be an explicit nil

### UnsetCiDeployId
`func (o *DeployRecordDto) UnsetCiDeployId()`

UnsetCiDeployId ensures that no value is present for CiDeployId, not even an explicit nil
### GetCiDeployUrl

`func (o *DeployRecordDto) GetCiDeployUrl() string`

GetCiDeployUrl returns the CiDeployUrl field if non-nil, zero value otherwise.

### GetCiDeployUrlOk

`func (o *DeployRecordDto) GetCiDeployUrlOk() (*string, bool)`

GetCiDeployUrlOk returns a tuple with the CiDeployUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCiDeployUrl

`func (o *DeployRecordDto) SetCiDeployUrl(v string)`

SetCiDeployUrl sets CiDeployUrl field to given value.

### HasCiDeployUrl

`func (o *DeployRecordDto) HasCiDeployUrl() bool`

HasCiDeployUrl returns a boolean if a field has been set.

### SetCiDeployUrlNil

`func (o *DeployRecordDto) SetCiDeployUrlNil(b bool)`

 SetCiDeployUrlNil sets the value for CiDeployUrl to be an explicit nil

### UnsetCiDeployUrl
`func (o *DeployRecordDto) UnsetCiDeployUrl()`

UnsetCiDeployUrl ensures that no value is present for CiDeployUrl, not even an explicit nil
### GetDuration

`func (o *DeployRecordDto) GetDuration() int32`

GetDuration returns the Duration field if non-nil, zero value otherwise.

### GetDurationOk

`func (o *DeployRecordDto) GetDurationOk() (*int32, bool)`

GetDurationOk returns a tuple with the Duration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuration

`func (o *DeployRecordDto) SetDuration(v int32)`

SetDuration sets Duration field to given value.

### HasDuration

`func (o *DeployRecordDto) HasDuration() bool`

HasDuration returns a boolean if a field has been set.

### SetDurationNil

`func (o *DeployRecordDto) SetDurationNil(b bool)`

 SetDurationNil sets the value for Duration to be an explicit nil

### UnsetDuration
`func (o *DeployRecordDto) UnsetDuration()`

UnsetDuration ensures that no value is present for Duration, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


