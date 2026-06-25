# UpdateDeployRecordDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | [**DeployStatus**](DeployStatus.md) |  |
**Logs** | Pointer to **NullableString** | 部署日志 | [optional]
**ErrorMessage** | Pointer to **NullableString** | 错误信息 | [optional]
**DeployUrl** | Pointer to **NullableString** | 部署地址 | [optional]

## Methods

### NewUpdateDeployRecordDto

`func NewUpdateDeployRecordDto(status DeployStatus, ) *UpdateDeployRecordDto`

NewUpdateDeployRecordDto instantiates a new UpdateDeployRecordDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateDeployRecordDtoWithDefaults

`func NewUpdateDeployRecordDtoWithDefaults() *UpdateDeployRecordDto`

NewUpdateDeployRecordDtoWithDefaults instantiates a new UpdateDeployRecordDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *UpdateDeployRecordDto) GetStatus() DeployStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *UpdateDeployRecordDto) GetStatusOk() (*DeployStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *UpdateDeployRecordDto) SetStatus(v DeployStatus)`

SetStatus sets Status field to given value.


### GetLogs

`func (o *UpdateDeployRecordDto) GetLogs() string`

GetLogs returns the Logs field if non-nil, zero value otherwise.

### GetLogsOk

`func (o *UpdateDeployRecordDto) GetLogsOk() (*string, bool)`

GetLogsOk returns a tuple with the Logs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogs

`func (o *UpdateDeployRecordDto) SetLogs(v string)`

SetLogs sets Logs field to given value.

### HasLogs

`func (o *UpdateDeployRecordDto) HasLogs() bool`

HasLogs returns a boolean if a field has been set.

### SetLogsNil

`func (o *UpdateDeployRecordDto) SetLogsNil(b bool)`

 SetLogsNil sets the value for Logs to be an explicit nil

### UnsetLogs
`func (o *UpdateDeployRecordDto) UnsetLogs()`

UnsetLogs ensures that no value is present for Logs, not even an explicit nil
### GetErrorMessage

`func (o *UpdateDeployRecordDto) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *UpdateDeployRecordDto) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *UpdateDeployRecordDto) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *UpdateDeployRecordDto) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.

### SetErrorMessageNil

`func (o *UpdateDeployRecordDto) SetErrorMessageNil(b bool)`

 SetErrorMessageNil sets the value for ErrorMessage to be an explicit nil

### UnsetErrorMessage
`func (o *UpdateDeployRecordDto) UnsetErrorMessage()`

UnsetErrorMessage ensures that no value is present for ErrorMessage, not even an explicit nil
### GetDeployUrl

`func (o *UpdateDeployRecordDto) GetDeployUrl() string`

GetDeployUrl returns the DeployUrl field if non-nil, zero value otherwise.

### GetDeployUrlOk

`func (o *UpdateDeployRecordDto) GetDeployUrlOk() (*string, bool)`

GetDeployUrlOk returns a tuple with the DeployUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeployUrl

`func (o *UpdateDeployRecordDto) SetDeployUrl(v string)`

SetDeployUrl sets DeployUrl field to given value.

### HasDeployUrl

`func (o *UpdateDeployRecordDto) HasDeployUrl() bool`

HasDeployUrl returns a boolean if a field has been set.

### SetDeployUrlNil

`func (o *UpdateDeployRecordDto) SetDeployUrlNil(b bool)`

 SetDeployUrlNil sets the value for DeployUrl to be an explicit nil

### UnsetDeployUrl
`func (o *UpdateDeployRecordDto) UnsetDeployUrl()`

UnsetDeployUrl ensures that no value is present for DeployUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


