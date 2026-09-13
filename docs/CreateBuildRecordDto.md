# CreateBuildRecordDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppId** | **string** | 应用ID | 
**Version** | **string** | 版本号 | 
**Branch** | **string** | 分支名称 | 
**CommitHash** | **string** | 提交哈希 | 
**Trigger** | Pointer to [**BuildTrigger**](BuildTrigger.md) |  | [optional] 
**Platform** | [**AppPlatform**](AppPlatform.md) |  | 
**ArtifactType** | [**ArtifactType**](ArtifactType.md) |  | 
**Architecture** | Pointer to **NullableString** | 目标架构（x64、arm64、arm、riscv64、universal 或 multiarch）。 | [optional] 
**Environment** | Pointer to **NullableString** | 环境 | [optional] 
**CiSystem** | Pointer to **NullableString** | CI/CD 系统信息 | [optional] 
**CiBuildId** | Pointer to **NullableString** | CI/CD 构建ID | [optional] 
**CiBuildUrl** | Pointer to **NullableString** | CI/CD 构建URL | [optional] 

## Methods

### NewCreateBuildRecordDto

`func NewCreateBuildRecordDto(appId string, version string, branch string, commitHash string, platform AppPlatform, artifactType ArtifactType, ) *CreateBuildRecordDto`

NewCreateBuildRecordDto instantiates a new CreateBuildRecordDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateBuildRecordDtoWithDefaults

`func NewCreateBuildRecordDtoWithDefaults() *CreateBuildRecordDto`

NewCreateBuildRecordDtoWithDefaults instantiates a new CreateBuildRecordDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppId

`func (o *CreateBuildRecordDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *CreateBuildRecordDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *CreateBuildRecordDto) SetAppId(v string)`

SetAppId sets AppId field to given value.


### GetVersion

`func (o *CreateBuildRecordDto) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *CreateBuildRecordDto) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *CreateBuildRecordDto) SetVersion(v string)`

SetVersion sets Version field to given value.


### GetBranch

`func (o *CreateBuildRecordDto) GetBranch() string`

GetBranch returns the Branch field if non-nil, zero value otherwise.

### GetBranchOk

`func (o *CreateBuildRecordDto) GetBranchOk() (*string, bool)`

GetBranchOk returns a tuple with the Branch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBranch

`func (o *CreateBuildRecordDto) SetBranch(v string)`

SetBranch sets Branch field to given value.


### GetCommitHash

`func (o *CreateBuildRecordDto) GetCommitHash() string`

GetCommitHash returns the CommitHash field if non-nil, zero value otherwise.

### GetCommitHashOk

`func (o *CreateBuildRecordDto) GetCommitHashOk() (*string, bool)`

GetCommitHashOk returns a tuple with the CommitHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommitHash

`func (o *CreateBuildRecordDto) SetCommitHash(v string)`

SetCommitHash sets CommitHash field to given value.


### GetTrigger

`func (o *CreateBuildRecordDto) GetTrigger() BuildTrigger`

GetTrigger returns the Trigger field if non-nil, zero value otherwise.

### GetTriggerOk

`func (o *CreateBuildRecordDto) GetTriggerOk() (*BuildTrigger, bool)`

GetTriggerOk returns a tuple with the Trigger field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrigger

`func (o *CreateBuildRecordDto) SetTrigger(v BuildTrigger)`

SetTrigger sets Trigger field to given value.

### HasTrigger

`func (o *CreateBuildRecordDto) HasTrigger() bool`

HasTrigger returns a boolean if a field has been set.

### GetPlatform

`func (o *CreateBuildRecordDto) GetPlatform() AppPlatform`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *CreateBuildRecordDto) GetPlatformOk() (*AppPlatform, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *CreateBuildRecordDto) SetPlatform(v AppPlatform)`

SetPlatform sets Platform field to given value.


### GetArtifactType

`func (o *CreateBuildRecordDto) GetArtifactType() ArtifactType`

GetArtifactType returns the ArtifactType field if non-nil, zero value otherwise.

### GetArtifactTypeOk

`func (o *CreateBuildRecordDto) GetArtifactTypeOk() (*ArtifactType, bool)`

GetArtifactTypeOk returns a tuple with the ArtifactType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArtifactType

`func (o *CreateBuildRecordDto) SetArtifactType(v ArtifactType)`

SetArtifactType sets ArtifactType field to given value.


### GetArchitecture

`func (o *CreateBuildRecordDto) GetArchitecture() string`

GetArchitecture returns the Architecture field if non-nil, zero value otherwise.

### GetArchitectureOk

`func (o *CreateBuildRecordDto) GetArchitectureOk() (*string, bool)`

GetArchitectureOk returns a tuple with the Architecture field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchitecture

`func (o *CreateBuildRecordDto) SetArchitecture(v string)`

SetArchitecture sets Architecture field to given value.

### HasArchitecture

`func (o *CreateBuildRecordDto) HasArchitecture() bool`

HasArchitecture returns a boolean if a field has been set.

### SetArchitectureNil

`func (o *CreateBuildRecordDto) SetArchitectureNil(b bool)`

 SetArchitectureNil sets the value for Architecture to be an explicit nil

### UnsetArchitecture
`func (o *CreateBuildRecordDto) UnsetArchitecture()`

UnsetArchitecture ensures that no value is present for Architecture, not even an explicit nil
### GetEnvironment

`func (o *CreateBuildRecordDto) GetEnvironment() string`

GetEnvironment returns the Environment field if non-nil, zero value otherwise.

### GetEnvironmentOk

`func (o *CreateBuildRecordDto) GetEnvironmentOk() (*string, bool)`

GetEnvironmentOk returns a tuple with the Environment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnvironment

`func (o *CreateBuildRecordDto) SetEnvironment(v string)`

SetEnvironment sets Environment field to given value.

### HasEnvironment

`func (o *CreateBuildRecordDto) HasEnvironment() bool`

HasEnvironment returns a boolean if a field has been set.

### SetEnvironmentNil

`func (o *CreateBuildRecordDto) SetEnvironmentNil(b bool)`

 SetEnvironmentNil sets the value for Environment to be an explicit nil

### UnsetEnvironment
`func (o *CreateBuildRecordDto) UnsetEnvironment()`

UnsetEnvironment ensures that no value is present for Environment, not even an explicit nil
### GetCiSystem

`func (o *CreateBuildRecordDto) GetCiSystem() string`

GetCiSystem returns the CiSystem field if non-nil, zero value otherwise.

### GetCiSystemOk

`func (o *CreateBuildRecordDto) GetCiSystemOk() (*string, bool)`

GetCiSystemOk returns a tuple with the CiSystem field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCiSystem

`func (o *CreateBuildRecordDto) SetCiSystem(v string)`

SetCiSystem sets CiSystem field to given value.

### HasCiSystem

`func (o *CreateBuildRecordDto) HasCiSystem() bool`

HasCiSystem returns a boolean if a field has been set.

### SetCiSystemNil

`func (o *CreateBuildRecordDto) SetCiSystemNil(b bool)`

 SetCiSystemNil sets the value for CiSystem to be an explicit nil

### UnsetCiSystem
`func (o *CreateBuildRecordDto) UnsetCiSystem()`

UnsetCiSystem ensures that no value is present for CiSystem, not even an explicit nil
### GetCiBuildId

`func (o *CreateBuildRecordDto) GetCiBuildId() string`

GetCiBuildId returns the CiBuildId field if non-nil, zero value otherwise.

### GetCiBuildIdOk

`func (o *CreateBuildRecordDto) GetCiBuildIdOk() (*string, bool)`

GetCiBuildIdOk returns a tuple with the CiBuildId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCiBuildId

`func (o *CreateBuildRecordDto) SetCiBuildId(v string)`

SetCiBuildId sets CiBuildId field to given value.

### HasCiBuildId

`func (o *CreateBuildRecordDto) HasCiBuildId() bool`

HasCiBuildId returns a boolean if a field has been set.

### SetCiBuildIdNil

`func (o *CreateBuildRecordDto) SetCiBuildIdNil(b bool)`

 SetCiBuildIdNil sets the value for CiBuildId to be an explicit nil

### UnsetCiBuildId
`func (o *CreateBuildRecordDto) UnsetCiBuildId()`

UnsetCiBuildId ensures that no value is present for CiBuildId, not even an explicit nil
### GetCiBuildUrl

`func (o *CreateBuildRecordDto) GetCiBuildUrl() string`

GetCiBuildUrl returns the CiBuildUrl field if non-nil, zero value otherwise.

### GetCiBuildUrlOk

`func (o *CreateBuildRecordDto) GetCiBuildUrlOk() (*string, bool)`

GetCiBuildUrlOk returns a tuple with the CiBuildUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCiBuildUrl

`func (o *CreateBuildRecordDto) SetCiBuildUrl(v string)`

SetCiBuildUrl sets CiBuildUrl field to given value.

### HasCiBuildUrl

`func (o *CreateBuildRecordDto) HasCiBuildUrl() bool`

HasCiBuildUrl returns a boolean if a field has been set.

### SetCiBuildUrlNil

`func (o *CreateBuildRecordDto) SetCiBuildUrlNil(b bool)`

 SetCiBuildUrlNil sets the value for CiBuildUrl to be an explicit nil

### UnsetCiBuildUrl
`func (o *CreateBuildRecordDto) UnsetCiBuildUrl()`

UnsetCiBuildUrl ensures that no value is present for CiBuildUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


