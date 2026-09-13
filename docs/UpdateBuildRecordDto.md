# UpdateBuildRecordDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | [**BuildStatus**](BuildStatus.md) |  | 
**Logs** | Pointer to **NullableString** | 构建日志 | [optional] 
**ErrorMessage** | Pointer to **NullableString** | 错误信息 | [optional] 
**ArtifactUrl** | Pointer to **NullableString** | 构建产物下载地址 | [optional] 
**ArtifactSize** | Pointer to **NullableInt64** | 构建产物大小 (字节) | [optional] 

## Methods

### NewUpdateBuildRecordDto

`func NewUpdateBuildRecordDto(status BuildStatus, ) *UpdateBuildRecordDto`

NewUpdateBuildRecordDto instantiates a new UpdateBuildRecordDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateBuildRecordDtoWithDefaults

`func NewUpdateBuildRecordDtoWithDefaults() *UpdateBuildRecordDto`

NewUpdateBuildRecordDtoWithDefaults instantiates a new UpdateBuildRecordDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *UpdateBuildRecordDto) GetStatus() BuildStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *UpdateBuildRecordDto) GetStatusOk() (*BuildStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *UpdateBuildRecordDto) SetStatus(v BuildStatus)`

SetStatus sets Status field to given value.


### GetLogs

`func (o *UpdateBuildRecordDto) GetLogs() string`

GetLogs returns the Logs field if non-nil, zero value otherwise.

### GetLogsOk

`func (o *UpdateBuildRecordDto) GetLogsOk() (*string, bool)`

GetLogsOk returns a tuple with the Logs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogs

`func (o *UpdateBuildRecordDto) SetLogs(v string)`

SetLogs sets Logs field to given value.

### HasLogs

`func (o *UpdateBuildRecordDto) HasLogs() bool`

HasLogs returns a boolean if a field has been set.

### SetLogsNil

`func (o *UpdateBuildRecordDto) SetLogsNil(b bool)`

 SetLogsNil sets the value for Logs to be an explicit nil

### UnsetLogs
`func (o *UpdateBuildRecordDto) UnsetLogs()`

UnsetLogs ensures that no value is present for Logs, not even an explicit nil
### GetErrorMessage

`func (o *UpdateBuildRecordDto) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *UpdateBuildRecordDto) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *UpdateBuildRecordDto) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *UpdateBuildRecordDto) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.

### SetErrorMessageNil

`func (o *UpdateBuildRecordDto) SetErrorMessageNil(b bool)`

 SetErrorMessageNil sets the value for ErrorMessage to be an explicit nil

### UnsetErrorMessage
`func (o *UpdateBuildRecordDto) UnsetErrorMessage()`

UnsetErrorMessage ensures that no value is present for ErrorMessage, not even an explicit nil
### GetArtifactUrl

`func (o *UpdateBuildRecordDto) GetArtifactUrl() string`

GetArtifactUrl returns the ArtifactUrl field if non-nil, zero value otherwise.

### GetArtifactUrlOk

`func (o *UpdateBuildRecordDto) GetArtifactUrlOk() (*string, bool)`

GetArtifactUrlOk returns a tuple with the ArtifactUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArtifactUrl

`func (o *UpdateBuildRecordDto) SetArtifactUrl(v string)`

SetArtifactUrl sets ArtifactUrl field to given value.

### HasArtifactUrl

`func (o *UpdateBuildRecordDto) HasArtifactUrl() bool`

HasArtifactUrl returns a boolean if a field has been set.

### SetArtifactUrlNil

`func (o *UpdateBuildRecordDto) SetArtifactUrlNil(b bool)`

 SetArtifactUrlNil sets the value for ArtifactUrl to be an explicit nil

### UnsetArtifactUrl
`func (o *UpdateBuildRecordDto) UnsetArtifactUrl()`

UnsetArtifactUrl ensures that no value is present for ArtifactUrl, not even an explicit nil
### GetArtifactSize

`func (o *UpdateBuildRecordDto) GetArtifactSize() int64`

GetArtifactSize returns the ArtifactSize field if non-nil, zero value otherwise.

### GetArtifactSizeOk

`func (o *UpdateBuildRecordDto) GetArtifactSizeOk() (*int64, bool)`

GetArtifactSizeOk returns a tuple with the ArtifactSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArtifactSize

`func (o *UpdateBuildRecordDto) SetArtifactSize(v int64)`

SetArtifactSize sets ArtifactSize field to given value.

### HasArtifactSize

`func (o *UpdateBuildRecordDto) HasArtifactSize() bool`

HasArtifactSize returns a boolean if a field has been set.

### SetArtifactSizeNil

`func (o *UpdateBuildRecordDto) SetArtifactSizeNil(b bool)`

 SetArtifactSizeNil sets the value for ArtifactSize to be an explicit nil

### UnsetArtifactSize
`func (o *UpdateBuildRecordDto) UnsetArtifactSize()`

UnsetArtifactSize ensures that no value is present for ArtifactSize, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


