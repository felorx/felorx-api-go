# CreateDeployRecordDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppId** | **string** | 应用ID |
**BuildRecordId** | **string** | 构建记录ID |
**Version** | **string** | 版本号 |
**Platform** | [**AppPlatform**](AppPlatform.md) |  |
**Environment** | **string** | 部署环境 |
**DeployUrl** | Pointer to **NullableString** | 部署地址 | [optional]
**DeployTarget** | Pointer to **NullableString** | 部署目标 | [optional]
**DeployChannel** | Pointer to **NullableString** | 部署渠道 | [optional]
**CiSystem** | Pointer to **NullableString** | CI/CD 系统信息 | [optional]
**CiDeployId** | Pointer to **NullableString** | CI/CD 部署ID | [optional]
**CiDeployUrl** | Pointer to **NullableString** | CI/CD 部署URL | [optional]

## Methods

### NewCreateDeployRecordDto

`func NewCreateDeployRecordDto(appId string, buildRecordId string, version string, platform AppPlatform, environment string, ) *CreateDeployRecordDto`

NewCreateDeployRecordDto instantiates a new CreateDeployRecordDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDeployRecordDtoWithDefaults

`func NewCreateDeployRecordDtoWithDefaults() *CreateDeployRecordDto`

NewCreateDeployRecordDtoWithDefaults instantiates a new CreateDeployRecordDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppId

`func (o *CreateDeployRecordDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *CreateDeployRecordDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *CreateDeployRecordDto) SetAppId(v string)`

SetAppId sets AppId field to given value.


### GetBuildRecordId

`func (o *CreateDeployRecordDto) GetBuildRecordId() string`

GetBuildRecordId returns the BuildRecordId field if non-nil, zero value otherwise.

### GetBuildRecordIdOk

`func (o *CreateDeployRecordDto) GetBuildRecordIdOk() (*string, bool)`

GetBuildRecordIdOk returns a tuple with the BuildRecordId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildRecordId

`func (o *CreateDeployRecordDto) SetBuildRecordId(v string)`

SetBuildRecordId sets BuildRecordId field to given value.


### GetVersion

`func (o *CreateDeployRecordDto) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *CreateDeployRecordDto) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *CreateDeployRecordDto) SetVersion(v string)`

SetVersion sets Version field to given value.


### GetPlatform

`func (o *CreateDeployRecordDto) GetPlatform() AppPlatform`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *CreateDeployRecordDto) GetPlatformOk() (*AppPlatform, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *CreateDeployRecordDto) SetPlatform(v AppPlatform)`

SetPlatform sets Platform field to given value.


### GetEnvironment

`func (o *CreateDeployRecordDto) GetEnvironment() string`

GetEnvironment returns the Environment field if non-nil, zero value otherwise.

### GetEnvironmentOk

`func (o *CreateDeployRecordDto) GetEnvironmentOk() (*string, bool)`

GetEnvironmentOk returns a tuple with the Environment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnvironment

`func (o *CreateDeployRecordDto) SetEnvironment(v string)`

SetEnvironment sets Environment field to given value.


### GetDeployUrl

`func (o *CreateDeployRecordDto) GetDeployUrl() string`

GetDeployUrl returns the DeployUrl field if non-nil, zero value otherwise.

### GetDeployUrlOk

`func (o *CreateDeployRecordDto) GetDeployUrlOk() (*string, bool)`

GetDeployUrlOk returns a tuple with the DeployUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeployUrl

`func (o *CreateDeployRecordDto) SetDeployUrl(v string)`

SetDeployUrl sets DeployUrl field to given value.

### HasDeployUrl

`func (o *CreateDeployRecordDto) HasDeployUrl() bool`

HasDeployUrl returns a boolean if a field has been set.

### SetDeployUrlNil

`func (o *CreateDeployRecordDto) SetDeployUrlNil(b bool)`

 SetDeployUrlNil sets the value for DeployUrl to be an explicit nil

### UnsetDeployUrl
`func (o *CreateDeployRecordDto) UnsetDeployUrl()`

UnsetDeployUrl ensures that no value is present for DeployUrl, not even an explicit nil
### GetDeployTarget

`func (o *CreateDeployRecordDto) GetDeployTarget() string`

GetDeployTarget returns the DeployTarget field if non-nil, zero value otherwise.

### GetDeployTargetOk

`func (o *CreateDeployRecordDto) GetDeployTargetOk() (*string, bool)`

GetDeployTargetOk returns a tuple with the DeployTarget field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeployTarget

`func (o *CreateDeployRecordDto) SetDeployTarget(v string)`

SetDeployTarget sets DeployTarget field to given value.

### HasDeployTarget

`func (o *CreateDeployRecordDto) HasDeployTarget() bool`

HasDeployTarget returns a boolean if a field has been set.

### SetDeployTargetNil

`func (o *CreateDeployRecordDto) SetDeployTargetNil(b bool)`

 SetDeployTargetNil sets the value for DeployTarget to be an explicit nil

### UnsetDeployTarget
`func (o *CreateDeployRecordDto) UnsetDeployTarget()`

UnsetDeployTarget ensures that no value is present for DeployTarget, not even an explicit nil
### GetDeployChannel

`func (o *CreateDeployRecordDto) GetDeployChannel() string`

GetDeployChannel returns the DeployChannel field if non-nil, zero value otherwise.

### GetDeployChannelOk

`func (o *CreateDeployRecordDto) GetDeployChannelOk() (*string, bool)`

GetDeployChannelOk returns a tuple with the DeployChannel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeployChannel

`func (o *CreateDeployRecordDto) SetDeployChannel(v string)`

SetDeployChannel sets DeployChannel field to given value.

### HasDeployChannel

`func (o *CreateDeployRecordDto) HasDeployChannel() bool`

HasDeployChannel returns a boolean if a field has been set.

### SetDeployChannelNil

`func (o *CreateDeployRecordDto) SetDeployChannelNil(b bool)`

 SetDeployChannelNil sets the value for DeployChannel to be an explicit nil

### UnsetDeployChannel
`func (o *CreateDeployRecordDto) UnsetDeployChannel()`

UnsetDeployChannel ensures that no value is present for DeployChannel, not even an explicit nil
### GetCiSystem

`func (o *CreateDeployRecordDto) GetCiSystem() string`

GetCiSystem returns the CiSystem field if non-nil, zero value otherwise.

### GetCiSystemOk

`func (o *CreateDeployRecordDto) GetCiSystemOk() (*string, bool)`

GetCiSystemOk returns a tuple with the CiSystem field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCiSystem

`func (o *CreateDeployRecordDto) SetCiSystem(v string)`

SetCiSystem sets CiSystem field to given value.

### HasCiSystem

`func (o *CreateDeployRecordDto) HasCiSystem() bool`

HasCiSystem returns a boolean if a field has been set.

### SetCiSystemNil

`func (o *CreateDeployRecordDto) SetCiSystemNil(b bool)`

 SetCiSystemNil sets the value for CiSystem to be an explicit nil

### UnsetCiSystem
`func (o *CreateDeployRecordDto) UnsetCiSystem()`

UnsetCiSystem ensures that no value is present for CiSystem, not even an explicit nil
### GetCiDeployId

`func (o *CreateDeployRecordDto) GetCiDeployId() string`

GetCiDeployId returns the CiDeployId field if non-nil, zero value otherwise.

### GetCiDeployIdOk

`func (o *CreateDeployRecordDto) GetCiDeployIdOk() (*string, bool)`

GetCiDeployIdOk returns a tuple with the CiDeployId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCiDeployId

`func (o *CreateDeployRecordDto) SetCiDeployId(v string)`

SetCiDeployId sets CiDeployId field to given value.

### HasCiDeployId

`func (o *CreateDeployRecordDto) HasCiDeployId() bool`

HasCiDeployId returns a boolean if a field has been set.

### SetCiDeployIdNil

`func (o *CreateDeployRecordDto) SetCiDeployIdNil(b bool)`

 SetCiDeployIdNil sets the value for CiDeployId to be an explicit nil

### UnsetCiDeployId
`func (o *CreateDeployRecordDto) UnsetCiDeployId()`

UnsetCiDeployId ensures that no value is present for CiDeployId, not even an explicit nil
### GetCiDeployUrl

`func (o *CreateDeployRecordDto) GetCiDeployUrl() string`

GetCiDeployUrl returns the CiDeployUrl field if non-nil, zero value otherwise.

### GetCiDeployUrlOk

`func (o *CreateDeployRecordDto) GetCiDeployUrlOk() (*string, bool)`

GetCiDeployUrlOk returns a tuple with the CiDeployUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCiDeployUrl

`func (o *CreateDeployRecordDto) SetCiDeployUrl(v string)`

SetCiDeployUrl sets CiDeployUrl field to given value.

### HasCiDeployUrl

`func (o *CreateDeployRecordDto) HasCiDeployUrl() bool`

HasCiDeployUrl returns a boolean if a field has been set.

### SetCiDeployUrlNil

`func (o *CreateDeployRecordDto) SetCiDeployUrlNil(b bool)`

 SetCiDeployUrlNil sets the value for CiDeployUrl to be an explicit nil

### UnsetCiDeployUrl
`func (o *CreateDeployRecordDto) UnsetCiDeployUrl()`

UnsetCiDeployUrl ensures that no value is present for CiDeployUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


