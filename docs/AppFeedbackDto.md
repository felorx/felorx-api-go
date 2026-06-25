# AppFeedbackDto

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
**Content** | Pointer to **NullableString** | 反馈内容 | [optional]
**Type** | Pointer to [**AppFeedbackType**](AppFeedbackType.md) |  | [optional]
**Status** | Pointer to [**AppFeedbackStatus**](AppFeedbackStatus.md) |  | [optional]
**Contact** | Pointer to **NullableString** | 联系方式 | [optional]
**DeviceInfo** | Pointer to **NullableString** | 设备信息 | [optional]
**AppVersion** | Pointer to **NullableString** | 应用版本 | [optional]
**Reply** | Pointer to **NullableString** | 回复内容 | [optional]
**RepliedAt** | Pointer to **NullableTime** | 回复时间 | [optional]
**AttachmentKeys** | Pointer to **[]string** | 附件对象存储 key 列表 | [optional]

## Methods

### NewAppFeedbackDto

`func NewAppFeedbackDto() *AppFeedbackDto`

NewAppFeedbackDto instantiates a new AppFeedbackDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAppFeedbackDtoWithDefaults

`func NewAppFeedbackDtoWithDefaults() *AppFeedbackDto`

NewAppFeedbackDtoWithDefaults instantiates a new AppFeedbackDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AppFeedbackDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AppFeedbackDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AppFeedbackDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AppFeedbackDto) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreationTime

`func (o *AppFeedbackDto) GetCreationTime() time.Time`

GetCreationTime returns the CreationTime field if non-nil, zero value otherwise.

### GetCreationTimeOk

`func (o *AppFeedbackDto) GetCreationTimeOk() (*time.Time, bool)`

GetCreationTimeOk returns a tuple with the CreationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreationTime

`func (o *AppFeedbackDto) SetCreationTime(v time.Time)`

SetCreationTime sets CreationTime field to given value.

### HasCreationTime

`func (o *AppFeedbackDto) HasCreationTime() bool`

HasCreationTime returns a boolean if a field has been set.

### GetCreatorId

`func (o *AppFeedbackDto) GetCreatorId() string`

GetCreatorId returns the CreatorId field if non-nil, zero value otherwise.

### GetCreatorIdOk

`func (o *AppFeedbackDto) GetCreatorIdOk() (*string, bool)`

GetCreatorIdOk returns a tuple with the CreatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatorId

`func (o *AppFeedbackDto) SetCreatorId(v string)`

SetCreatorId sets CreatorId field to given value.

### HasCreatorId

`func (o *AppFeedbackDto) HasCreatorId() bool`

HasCreatorId returns a boolean if a field has been set.

### SetCreatorIdNil

`func (o *AppFeedbackDto) SetCreatorIdNil(b bool)`

 SetCreatorIdNil sets the value for CreatorId to be an explicit nil

### UnsetCreatorId
`func (o *AppFeedbackDto) UnsetCreatorId()`

UnsetCreatorId ensures that no value is present for CreatorId, not even an explicit nil
### GetLastModificationTime

`func (o *AppFeedbackDto) GetLastModificationTime() time.Time`

GetLastModificationTime returns the LastModificationTime field if non-nil, zero value otherwise.

### GetLastModificationTimeOk

`func (o *AppFeedbackDto) GetLastModificationTimeOk() (*time.Time, bool)`

GetLastModificationTimeOk returns a tuple with the LastModificationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModificationTime

`func (o *AppFeedbackDto) SetLastModificationTime(v time.Time)`

SetLastModificationTime sets LastModificationTime field to given value.

### HasLastModificationTime

`func (o *AppFeedbackDto) HasLastModificationTime() bool`

HasLastModificationTime returns a boolean if a field has been set.

### SetLastModificationTimeNil

`func (o *AppFeedbackDto) SetLastModificationTimeNil(b bool)`

 SetLastModificationTimeNil sets the value for LastModificationTime to be an explicit nil

### UnsetLastModificationTime
`func (o *AppFeedbackDto) UnsetLastModificationTime()`

UnsetLastModificationTime ensures that no value is present for LastModificationTime, not even an explicit nil
### GetLastModifierId

`func (o *AppFeedbackDto) GetLastModifierId() string`

GetLastModifierId returns the LastModifierId field if non-nil, zero value otherwise.

### GetLastModifierIdOk

`func (o *AppFeedbackDto) GetLastModifierIdOk() (*string, bool)`

GetLastModifierIdOk returns a tuple with the LastModifierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModifierId

`func (o *AppFeedbackDto) SetLastModifierId(v string)`

SetLastModifierId sets LastModifierId field to given value.

### HasLastModifierId

`func (o *AppFeedbackDto) HasLastModifierId() bool`

HasLastModifierId returns a boolean if a field has been set.

### SetLastModifierIdNil

`func (o *AppFeedbackDto) SetLastModifierIdNil(b bool)`

 SetLastModifierIdNil sets the value for LastModifierId to be an explicit nil

### UnsetLastModifierId
`func (o *AppFeedbackDto) UnsetLastModifierId()`

UnsetLastModifierId ensures that no value is present for LastModifierId, not even an explicit nil
### GetIsDeleted

`func (o *AppFeedbackDto) GetIsDeleted() bool`

GetIsDeleted returns the IsDeleted field if non-nil, zero value otherwise.

### GetIsDeletedOk

`func (o *AppFeedbackDto) GetIsDeletedOk() (*bool, bool)`

GetIsDeletedOk returns a tuple with the IsDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDeleted

`func (o *AppFeedbackDto) SetIsDeleted(v bool)`

SetIsDeleted sets IsDeleted field to given value.

### HasIsDeleted

`func (o *AppFeedbackDto) HasIsDeleted() bool`

HasIsDeleted returns a boolean if a field has been set.

### GetDeleterId

`func (o *AppFeedbackDto) GetDeleterId() string`

GetDeleterId returns the DeleterId field if non-nil, zero value otherwise.

### GetDeleterIdOk

`func (o *AppFeedbackDto) GetDeleterIdOk() (*string, bool)`

GetDeleterIdOk returns a tuple with the DeleterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleterId

`func (o *AppFeedbackDto) SetDeleterId(v string)`

SetDeleterId sets DeleterId field to given value.

### HasDeleterId

`func (o *AppFeedbackDto) HasDeleterId() bool`

HasDeleterId returns a boolean if a field has been set.

### SetDeleterIdNil

`func (o *AppFeedbackDto) SetDeleterIdNil(b bool)`

 SetDeleterIdNil sets the value for DeleterId to be an explicit nil

### UnsetDeleterId
`func (o *AppFeedbackDto) UnsetDeleterId()`

UnsetDeleterId ensures that no value is present for DeleterId, not even an explicit nil
### GetDeletionTime

`func (o *AppFeedbackDto) GetDeletionTime() time.Time`

GetDeletionTime returns the DeletionTime field if non-nil, zero value otherwise.

### GetDeletionTimeOk

`func (o *AppFeedbackDto) GetDeletionTimeOk() (*time.Time, bool)`

GetDeletionTimeOk returns a tuple with the DeletionTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletionTime

`func (o *AppFeedbackDto) SetDeletionTime(v time.Time)`

SetDeletionTime sets DeletionTime field to given value.

### HasDeletionTime

`func (o *AppFeedbackDto) HasDeletionTime() bool`

HasDeletionTime returns a boolean if a field has been set.

### SetDeletionTimeNil

`func (o *AppFeedbackDto) SetDeletionTimeNil(b bool)`

 SetDeletionTimeNil sets the value for DeletionTime to be an explicit nil

### UnsetDeletionTime
`func (o *AppFeedbackDto) UnsetDeletionTime()`

UnsetDeletionTime ensures that no value is present for DeletionTime, not even an explicit nil
### GetAppId

`func (o *AppFeedbackDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *AppFeedbackDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *AppFeedbackDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *AppFeedbackDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetAppName

`func (o *AppFeedbackDto) GetAppName() string`

GetAppName returns the AppName field if non-nil, zero value otherwise.

### GetAppNameOk

`func (o *AppFeedbackDto) GetAppNameOk() (*string, bool)`

GetAppNameOk returns a tuple with the AppName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppName

`func (o *AppFeedbackDto) SetAppName(v string)`

SetAppName sets AppName field to given value.

### HasAppName

`func (o *AppFeedbackDto) HasAppName() bool`

HasAppName returns a boolean if a field has been set.

### SetAppNameNil

`func (o *AppFeedbackDto) SetAppNameNil(b bool)`

 SetAppNameNil sets the value for AppName to be an explicit nil

### UnsetAppName
`func (o *AppFeedbackDto) UnsetAppName()`

UnsetAppName ensures that no value is present for AppName, not even an explicit nil
### GetContent

`func (o *AppFeedbackDto) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *AppFeedbackDto) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *AppFeedbackDto) SetContent(v string)`

SetContent sets Content field to given value.

### HasContent

`func (o *AppFeedbackDto) HasContent() bool`

HasContent returns a boolean if a field has been set.

### SetContentNil

`func (o *AppFeedbackDto) SetContentNil(b bool)`

 SetContentNil sets the value for Content to be an explicit nil

### UnsetContent
`func (o *AppFeedbackDto) UnsetContent()`

UnsetContent ensures that no value is present for Content, not even an explicit nil
### GetType

`func (o *AppFeedbackDto) GetType() AppFeedbackType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *AppFeedbackDto) GetTypeOk() (*AppFeedbackType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *AppFeedbackDto) SetType(v AppFeedbackType)`

SetType sets Type field to given value.

### HasType

`func (o *AppFeedbackDto) HasType() bool`

HasType returns a boolean if a field has been set.

### GetStatus

`func (o *AppFeedbackDto) GetStatus() AppFeedbackStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AppFeedbackDto) GetStatusOk() (*AppFeedbackStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AppFeedbackDto) SetStatus(v AppFeedbackStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *AppFeedbackDto) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetContact

`func (o *AppFeedbackDto) GetContact() string`

GetContact returns the Contact field if non-nil, zero value otherwise.

### GetContactOk

`func (o *AppFeedbackDto) GetContactOk() (*string, bool)`

GetContactOk returns a tuple with the Contact field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContact

`func (o *AppFeedbackDto) SetContact(v string)`

SetContact sets Contact field to given value.

### HasContact

`func (o *AppFeedbackDto) HasContact() bool`

HasContact returns a boolean if a field has been set.

### SetContactNil

`func (o *AppFeedbackDto) SetContactNil(b bool)`

 SetContactNil sets the value for Contact to be an explicit nil

### UnsetContact
`func (o *AppFeedbackDto) UnsetContact()`

UnsetContact ensures that no value is present for Contact, not even an explicit nil
### GetDeviceInfo

`func (o *AppFeedbackDto) GetDeviceInfo() string`

GetDeviceInfo returns the DeviceInfo field if non-nil, zero value otherwise.

### GetDeviceInfoOk

`func (o *AppFeedbackDto) GetDeviceInfoOk() (*string, bool)`

GetDeviceInfoOk returns a tuple with the DeviceInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceInfo

`func (o *AppFeedbackDto) SetDeviceInfo(v string)`

SetDeviceInfo sets DeviceInfo field to given value.

### HasDeviceInfo

`func (o *AppFeedbackDto) HasDeviceInfo() bool`

HasDeviceInfo returns a boolean if a field has been set.

### SetDeviceInfoNil

`func (o *AppFeedbackDto) SetDeviceInfoNil(b bool)`

 SetDeviceInfoNil sets the value for DeviceInfo to be an explicit nil

### UnsetDeviceInfo
`func (o *AppFeedbackDto) UnsetDeviceInfo()`

UnsetDeviceInfo ensures that no value is present for DeviceInfo, not even an explicit nil
### GetAppVersion

`func (o *AppFeedbackDto) GetAppVersion() string`

GetAppVersion returns the AppVersion field if non-nil, zero value otherwise.

### GetAppVersionOk

`func (o *AppFeedbackDto) GetAppVersionOk() (*string, bool)`

GetAppVersionOk returns a tuple with the AppVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppVersion

`func (o *AppFeedbackDto) SetAppVersion(v string)`

SetAppVersion sets AppVersion field to given value.

### HasAppVersion

`func (o *AppFeedbackDto) HasAppVersion() bool`

HasAppVersion returns a boolean if a field has been set.

### SetAppVersionNil

`func (o *AppFeedbackDto) SetAppVersionNil(b bool)`

 SetAppVersionNil sets the value for AppVersion to be an explicit nil

### UnsetAppVersion
`func (o *AppFeedbackDto) UnsetAppVersion()`

UnsetAppVersion ensures that no value is present for AppVersion, not even an explicit nil
### GetReply

`func (o *AppFeedbackDto) GetReply() string`

GetReply returns the Reply field if non-nil, zero value otherwise.

### GetReplyOk

`func (o *AppFeedbackDto) GetReplyOk() (*string, bool)`

GetReplyOk returns a tuple with the Reply field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReply

`func (o *AppFeedbackDto) SetReply(v string)`

SetReply sets Reply field to given value.

### HasReply

`func (o *AppFeedbackDto) HasReply() bool`

HasReply returns a boolean if a field has been set.

### SetReplyNil

`func (o *AppFeedbackDto) SetReplyNil(b bool)`

 SetReplyNil sets the value for Reply to be an explicit nil

### UnsetReply
`func (o *AppFeedbackDto) UnsetReply()`

UnsetReply ensures that no value is present for Reply, not even an explicit nil
### GetRepliedAt

`func (o *AppFeedbackDto) GetRepliedAt() time.Time`

GetRepliedAt returns the RepliedAt field if non-nil, zero value otherwise.

### GetRepliedAtOk

`func (o *AppFeedbackDto) GetRepliedAtOk() (*time.Time, bool)`

GetRepliedAtOk returns a tuple with the RepliedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepliedAt

`func (o *AppFeedbackDto) SetRepliedAt(v time.Time)`

SetRepliedAt sets RepliedAt field to given value.

### HasRepliedAt

`func (o *AppFeedbackDto) HasRepliedAt() bool`

HasRepliedAt returns a boolean if a field has been set.

### SetRepliedAtNil

`func (o *AppFeedbackDto) SetRepliedAtNil(b bool)`

 SetRepliedAtNil sets the value for RepliedAt to be an explicit nil

### UnsetRepliedAt
`func (o *AppFeedbackDto) UnsetRepliedAt()`

UnsetRepliedAt ensures that no value is present for RepliedAt, not even an explicit nil
### GetAttachmentKeys

`func (o *AppFeedbackDto) GetAttachmentKeys() []string`

GetAttachmentKeys returns the AttachmentKeys field if non-nil, zero value otherwise.

### GetAttachmentKeysOk

`func (o *AppFeedbackDto) GetAttachmentKeysOk() (*[]string, bool)`

GetAttachmentKeysOk returns a tuple with the AttachmentKeys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttachmentKeys

`func (o *AppFeedbackDto) SetAttachmentKeys(v []string)`

SetAttachmentKeys sets AttachmentKeys field to given value.

### HasAttachmentKeys

`func (o *AppFeedbackDto) HasAttachmentKeys() bool`

HasAttachmentKeys returns a boolean if a field has been set.

### SetAttachmentKeysNil

`func (o *AppFeedbackDto) SetAttachmentKeysNil(b bool)`

 SetAttachmentKeysNil sets the value for AttachmentKeys to be an explicit nil

### UnsetAttachmentKeys
`func (o *AppFeedbackDto) UnsetAttachmentKeys()`

UnsetAttachmentKeys ensures that no value is present for AttachmentKeys, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


