# CreateAppFeedbackDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppId** | **string** | 应用ID | 
**Content** | **string** | 反馈内容 | 
**Type** | [**AppFeedbackType**](AppFeedbackType.md) |  | 
**Contact** | Pointer to **NullableString** | 联系方式（可选） | [optional] 
**DeviceInfo** | Pointer to **NullableString** | 设备信息（可选） | [optional] 
**AppVersion** | Pointer to **NullableString** | 应用版本（可选） | [optional] 
**AttachmentKeys** | Pointer to **[]string** | 截图/图片附件（对象存储 key，最多 5 个） | [optional] 

## Methods

### NewCreateAppFeedbackDto

`func NewCreateAppFeedbackDto(appId string, content string, type_ AppFeedbackType, ) *CreateAppFeedbackDto`

NewCreateAppFeedbackDto instantiates a new CreateAppFeedbackDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateAppFeedbackDtoWithDefaults

`func NewCreateAppFeedbackDtoWithDefaults() *CreateAppFeedbackDto`

NewCreateAppFeedbackDtoWithDefaults instantiates a new CreateAppFeedbackDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppId

`func (o *CreateAppFeedbackDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *CreateAppFeedbackDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *CreateAppFeedbackDto) SetAppId(v string)`

SetAppId sets AppId field to given value.


### GetContent

`func (o *CreateAppFeedbackDto) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *CreateAppFeedbackDto) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *CreateAppFeedbackDto) SetContent(v string)`

SetContent sets Content field to given value.


### GetType

`func (o *CreateAppFeedbackDto) GetType() AppFeedbackType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreateAppFeedbackDto) GetTypeOk() (*AppFeedbackType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreateAppFeedbackDto) SetType(v AppFeedbackType)`

SetType sets Type field to given value.


### GetContact

`func (o *CreateAppFeedbackDto) GetContact() string`

GetContact returns the Contact field if non-nil, zero value otherwise.

### GetContactOk

`func (o *CreateAppFeedbackDto) GetContactOk() (*string, bool)`

GetContactOk returns a tuple with the Contact field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContact

`func (o *CreateAppFeedbackDto) SetContact(v string)`

SetContact sets Contact field to given value.

### HasContact

`func (o *CreateAppFeedbackDto) HasContact() bool`

HasContact returns a boolean if a field has been set.

### SetContactNil

`func (o *CreateAppFeedbackDto) SetContactNil(b bool)`

 SetContactNil sets the value for Contact to be an explicit nil

### UnsetContact
`func (o *CreateAppFeedbackDto) UnsetContact()`

UnsetContact ensures that no value is present for Contact, not even an explicit nil
### GetDeviceInfo

`func (o *CreateAppFeedbackDto) GetDeviceInfo() string`

GetDeviceInfo returns the DeviceInfo field if non-nil, zero value otherwise.

### GetDeviceInfoOk

`func (o *CreateAppFeedbackDto) GetDeviceInfoOk() (*string, bool)`

GetDeviceInfoOk returns a tuple with the DeviceInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceInfo

`func (o *CreateAppFeedbackDto) SetDeviceInfo(v string)`

SetDeviceInfo sets DeviceInfo field to given value.

### HasDeviceInfo

`func (o *CreateAppFeedbackDto) HasDeviceInfo() bool`

HasDeviceInfo returns a boolean if a field has been set.

### SetDeviceInfoNil

`func (o *CreateAppFeedbackDto) SetDeviceInfoNil(b bool)`

 SetDeviceInfoNil sets the value for DeviceInfo to be an explicit nil

### UnsetDeviceInfo
`func (o *CreateAppFeedbackDto) UnsetDeviceInfo()`

UnsetDeviceInfo ensures that no value is present for DeviceInfo, not even an explicit nil
### GetAppVersion

`func (o *CreateAppFeedbackDto) GetAppVersion() string`

GetAppVersion returns the AppVersion field if non-nil, zero value otherwise.

### GetAppVersionOk

`func (o *CreateAppFeedbackDto) GetAppVersionOk() (*string, bool)`

GetAppVersionOk returns a tuple with the AppVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppVersion

`func (o *CreateAppFeedbackDto) SetAppVersion(v string)`

SetAppVersion sets AppVersion field to given value.

### HasAppVersion

`func (o *CreateAppFeedbackDto) HasAppVersion() bool`

HasAppVersion returns a boolean if a field has been set.

### SetAppVersionNil

`func (o *CreateAppFeedbackDto) SetAppVersionNil(b bool)`

 SetAppVersionNil sets the value for AppVersion to be an explicit nil

### UnsetAppVersion
`func (o *CreateAppFeedbackDto) UnsetAppVersion()`

UnsetAppVersion ensures that no value is present for AppVersion, not even an explicit nil
### GetAttachmentKeys

`func (o *CreateAppFeedbackDto) GetAttachmentKeys() []string`

GetAttachmentKeys returns the AttachmentKeys field if non-nil, zero value otherwise.

### GetAttachmentKeysOk

`func (o *CreateAppFeedbackDto) GetAttachmentKeysOk() (*[]string, bool)`

GetAttachmentKeysOk returns a tuple with the AttachmentKeys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachmentKeys

`func (o *CreateAppFeedbackDto) SetAttachmentKeys(v []string)`

SetAttachmentKeys sets AttachmentKeys field to given value.

### HasAttachmentKeys

`func (o *CreateAppFeedbackDto) HasAttachmentKeys() bool`

HasAttachmentKeys returns a boolean if a field has been set.

### SetAttachmentKeysNil

`func (o *CreateAppFeedbackDto) SetAttachmentKeysNil(b bool)`

 SetAttachmentKeysNil sets the value for AttachmentKeys to be an explicit nil

### UnsetAttachmentKeys
`func (o *CreateAppFeedbackDto) UnsetAttachmentKeys()`

UnsetAttachmentKeys ensures that no value is present for AttachmentKeys, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


