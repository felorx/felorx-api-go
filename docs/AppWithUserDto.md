# AppWithUserDto

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
**Name** | Pointer to **NullableString** |  | [optional] 
**DisplayName** | Pointer to **NullableString** | 根据 Accept-Language 解析的展示标题（非持久化字段，来自语言包）。 | [optional] 
**Framework** | Pointer to [**AppFramework**](AppFramework.md) |  | [optional] 
**AppType** | Pointer to [**AppType**](AppType.md) |  | [optional] 
**Description** | Pointer to **NullableString** | 根据 Accept-Language 解析的短描述（非持久化字段）。 | [optional] 
**Icon** | Pointer to **NullableString** | 根据 Accept-Language 解析的图标存储键或 URL（非持久化字段）。 | [optional] 
**HomePage** | Pointer to **NullableString** | 产品首页 | [optional] 
**SortIndex** | Pointer to **int32** | 显示排序 | [optional] 
**GitRepository** | Pointer to **NullableString** |  | [optional] 
**GitRepositoryType** | Pointer to [**GitRepositoryType**](GitRepositoryType.md) |  | [optional] 
**IsEnabled** | Pointer to **bool** |  | [optional] 
**IsPublished** | Pointer to **bool** | 是否已经发布, 决定了是否给终端用户看见, 主要有一些 APP 自己使用 | [optional] 
**WebhookUrl** | Pointer to **NullableString** | Webhook Url 各种事件回调地址 | [optional] 
**BusinessDomain** | Pointer to **NullableString** | 业务域名 | [optional] 
**BusinessUrl** | Pointer to **NullableString** | 业务地址 | [optional] 
**SubscriptionPlatforms** | Pointer to **NullableString** | 可以订阅的平台 Platform 枚举, 并用\&quot;,\&quot;分割 | [optional] 
**FreePlatforms** | Pointer to **NullableString** | 暂时免费的平台, 付费功能免费用的平台, 用\&quot;,\&quot;分割 | [optional] 
**SpecJsonSchema** | Pointer to **NullableString** | 声明格式 | [optional] 
**DefaultStorageSize** | Pointer to **int64** | 默认存储空间大小 | [optional] 
**DefaultSingleFileMaxSize** | Pointer to **int64** | 默认单文件最大大小 | [optional] 
**LatestReleases** | Pointer to [**[]AppReleaseDto**](AppReleaseDto.md) |  | [optional] 
**Creator** | Pointer to [**IdentityUserDto**](IdentityUserDto.md) |  | [optional] 
**Subscribed** | Pointer to **bool** | 是否已经订阅 | [optional] 

## Methods

### NewAppWithUserDto

`func NewAppWithUserDto() *AppWithUserDto`

NewAppWithUserDto instantiates a new AppWithUserDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAppWithUserDtoWithDefaults

`func NewAppWithUserDtoWithDefaults() *AppWithUserDto`

NewAppWithUserDtoWithDefaults instantiates a new AppWithUserDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AppWithUserDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AppWithUserDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AppWithUserDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AppWithUserDto) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreationTime

`func (o *AppWithUserDto) GetCreationTime() time.Time`

GetCreationTime returns the CreationTime field if non-nil, zero value otherwise.

### GetCreationTimeOk

`func (o *AppWithUserDto) GetCreationTimeOk() (*time.Time, bool)`

GetCreationTimeOk returns a tuple with the CreationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreationTime

`func (o *AppWithUserDto) SetCreationTime(v time.Time)`

SetCreationTime sets CreationTime field to given value.

### HasCreationTime

`func (o *AppWithUserDto) HasCreationTime() bool`

HasCreationTime returns a boolean if a field has been set.

### GetCreatorId

`func (o *AppWithUserDto) GetCreatorId() string`

GetCreatorId returns the CreatorId field if non-nil, zero value otherwise.

### GetCreatorIdOk

`func (o *AppWithUserDto) GetCreatorIdOk() (*string, bool)`

GetCreatorIdOk returns a tuple with the CreatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatorId

`func (o *AppWithUserDto) SetCreatorId(v string)`

SetCreatorId sets CreatorId field to given value.

### HasCreatorId

`func (o *AppWithUserDto) HasCreatorId() bool`

HasCreatorId returns a boolean if a field has been set.

### SetCreatorIdNil

`func (o *AppWithUserDto) SetCreatorIdNil(b bool)`

 SetCreatorIdNil sets the value for CreatorId to be an explicit nil

### UnsetCreatorId
`func (o *AppWithUserDto) UnsetCreatorId()`

UnsetCreatorId ensures that no value is present for CreatorId, not even an explicit nil
### GetLastModificationTime

`func (o *AppWithUserDto) GetLastModificationTime() time.Time`

GetLastModificationTime returns the LastModificationTime field if non-nil, zero value otherwise.

### GetLastModificationTimeOk

`func (o *AppWithUserDto) GetLastModificationTimeOk() (*time.Time, bool)`

GetLastModificationTimeOk returns a tuple with the LastModificationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModificationTime

`func (o *AppWithUserDto) SetLastModificationTime(v time.Time)`

SetLastModificationTime sets LastModificationTime field to given value.

### HasLastModificationTime

`func (o *AppWithUserDto) HasLastModificationTime() bool`

HasLastModificationTime returns a boolean if a field has been set.

### SetLastModificationTimeNil

`func (o *AppWithUserDto) SetLastModificationTimeNil(b bool)`

 SetLastModificationTimeNil sets the value for LastModificationTime to be an explicit nil

### UnsetLastModificationTime
`func (o *AppWithUserDto) UnsetLastModificationTime()`

UnsetLastModificationTime ensures that no value is present for LastModificationTime, not even an explicit nil
### GetLastModifierId

`func (o *AppWithUserDto) GetLastModifierId() string`

GetLastModifierId returns the LastModifierId field if non-nil, zero value otherwise.

### GetLastModifierIdOk

`func (o *AppWithUserDto) GetLastModifierIdOk() (*string, bool)`

GetLastModifierIdOk returns a tuple with the LastModifierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModifierId

`func (o *AppWithUserDto) SetLastModifierId(v string)`

SetLastModifierId sets LastModifierId field to given value.

### HasLastModifierId

`func (o *AppWithUserDto) HasLastModifierId() bool`

HasLastModifierId returns a boolean if a field has been set.

### SetLastModifierIdNil

`func (o *AppWithUserDto) SetLastModifierIdNil(b bool)`

 SetLastModifierIdNil sets the value for LastModifierId to be an explicit nil

### UnsetLastModifierId
`func (o *AppWithUserDto) UnsetLastModifierId()`

UnsetLastModifierId ensures that no value is present for LastModifierId, not even an explicit nil
### GetIsDeleted

`func (o *AppWithUserDto) GetIsDeleted() bool`

GetIsDeleted returns the IsDeleted field if non-nil, zero value otherwise.

### GetIsDeletedOk

`func (o *AppWithUserDto) GetIsDeletedOk() (*bool, bool)`

GetIsDeletedOk returns a tuple with the IsDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDeleted

`func (o *AppWithUserDto) SetIsDeleted(v bool)`

SetIsDeleted sets IsDeleted field to given value.

### HasIsDeleted

`func (o *AppWithUserDto) HasIsDeleted() bool`

HasIsDeleted returns a boolean if a field has been set.

### GetDeleterId

`func (o *AppWithUserDto) GetDeleterId() string`

GetDeleterId returns the DeleterId field if non-nil, zero value otherwise.

### GetDeleterIdOk

`func (o *AppWithUserDto) GetDeleterIdOk() (*string, bool)`

GetDeleterIdOk returns a tuple with the DeleterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleterId

`func (o *AppWithUserDto) SetDeleterId(v string)`

SetDeleterId sets DeleterId field to given value.

### HasDeleterId

`func (o *AppWithUserDto) HasDeleterId() bool`

HasDeleterId returns a boolean if a field has been set.

### SetDeleterIdNil

`func (o *AppWithUserDto) SetDeleterIdNil(b bool)`

 SetDeleterIdNil sets the value for DeleterId to be an explicit nil

### UnsetDeleterId
`func (o *AppWithUserDto) UnsetDeleterId()`

UnsetDeleterId ensures that no value is present for DeleterId, not even an explicit nil
### GetDeletionTime

`func (o *AppWithUserDto) GetDeletionTime() time.Time`

GetDeletionTime returns the DeletionTime field if non-nil, zero value otherwise.

### GetDeletionTimeOk

`func (o *AppWithUserDto) GetDeletionTimeOk() (*time.Time, bool)`

GetDeletionTimeOk returns a tuple with the DeletionTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletionTime

`func (o *AppWithUserDto) SetDeletionTime(v time.Time)`

SetDeletionTime sets DeletionTime field to given value.

### HasDeletionTime

`func (o *AppWithUserDto) HasDeletionTime() bool`

HasDeletionTime returns a boolean if a field has been set.

### SetDeletionTimeNil

`func (o *AppWithUserDto) SetDeletionTimeNil(b bool)`

 SetDeletionTimeNil sets the value for DeletionTime to be an explicit nil

### UnsetDeletionTime
`func (o *AppWithUserDto) UnsetDeletionTime()`

UnsetDeletionTime ensures that no value is present for DeletionTime, not even an explicit nil
### GetName

`func (o *AppWithUserDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AppWithUserDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AppWithUserDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *AppWithUserDto) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *AppWithUserDto) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *AppWithUserDto) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetDisplayName

`func (o *AppWithUserDto) GetDisplayName() string`

GetDisplayName returns the DisplayName field if non-nil, zero value otherwise.

### GetDisplayNameOk

`func (o *AppWithUserDto) GetDisplayNameOk() (*string, bool)`

GetDisplayNameOk returns a tuple with the DisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayName

`func (o *AppWithUserDto) SetDisplayName(v string)`

SetDisplayName sets DisplayName field to given value.

### HasDisplayName

`func (o *AppWithUserDto) HasDisplayName() bool`

HasDisplayName returns a boolean if a field has been set.

### SetDisplayNameNil

`func (o *AppWithUserDto) SetDisplayNameNil(b bool)`

 SetDisplayNameNil sets the value for DisplayName to be an explicit nil

### UnsetDisplayName
`func (o *AppWithUserDto) UnsetDisplayName()`

UnsetDisplayName ensures that no value is present for DisplayName, not even an explicit nil
### GetFramework

`func (o *AppWithUserDto) GetFramework() AppFramework`

GetFramework returns the Framework field if non-nil, zero value otherwise.

### GetFrameworkOk

`func (o *AppWithUserDto) GetFrameworkOk() (*AppFramework, bool)`

GetFrameworkOk returns a tuple with the Framework field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFramework

`func (o *AppWithUserDto) SetFramework(v AppFramework)`

SetFramework sets Framework field to given value.

### HasFramework

`func (o *AppWithUserDto) HasFramework() bool`

HasFramework returns a boolean if a field has been set.

### GetAppType

`func (o *AppWithUserDto) GetAppType() AppType`

GetAppType returns the AppType field if non-nil, zero value otherwise.

### GetAppTypeOk

`func (o *AppWithUserDto) GetAppTypeOk() (*AppType, bool)`

GetAppTypeOk returns a tuple with the AppType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppType

`func (o *AppWithUserDto) SetAppType(v AppType)`

SetAppType sets AppType field to given value.

### HasAppType

`func (o *AppWithUserDto) HasAppType() bool`

HasAppType returns a boolean if a field has been set.

### GetDescription

`func (o *AppWithUserDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *AppWithUserDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *AppWithUserDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *AppWithUserDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *AppWithUserDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *AppWithUserDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetIcon

`func (o *AppWithUserDto) GetIcon() string`

GetIcon returns the Icon field if non-nil, zero value otherwise.

### GetIconOk

`func (o *AppWithUserDto) GetIconOk() (*string, bool)`

GetIconOk returns a tuple with the Icon field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIcon

`func (o *AppWithUserDto) SetIcon(v string)`

SetIcon sets Icon field to given value.

### HasIcon

`func (o *AppWithUserDto) HasIcon() bool`

HasIcon returns a boolean if a field has been set.

### SetIconNil

`func (o *AppWithUserDto) SetIconNil(b bool)`

 SetIconNil sets the value for Icon to be an explicit nil

### UnsetIcon
`func (o *AppWithUserDto) UnsetIcon()`

UnsetIcon ensures that no value is present for Icon, not even an explicit nil
### GetHomePage

`func (o *AppWithUserDto) GetHomePage() string`

GetHomePage returns the HomePage field if non-nil, zero value otherwise.

### GetHomePageOk

`func (o *AppWithUserDto) GetHomePageOk() (*string, bool)`

GetHomePageOk returns a tuple with the HomePage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHomePage

`func (o *AppWithUserDto) SetHomePage(v string)`

SetHomePage sets HomePage field to given value.

### HasHomePage

`func (o *AppWithUserDto) HasHomePage() bool`

HasHomePage returns a boolean if a field has been set.

### SetHomePageNil

`func (o *AppWithUserDto) SetHomePageNil(b bool)`

 SetHomePageNil sets the value for HomePage to be an explicit nil

### UnsetHomePage
`func (o *AppWithUserDto) UnsetHomePage()`

UnsetHomePage ensures that no value is present for HomePage, not even an explicit nil
### GetSortIndex

`func (o *AppWithUserDto) GetSortIndex() int32`

GetSortIndex returns the SortIndex field if non-nil, zero value otherwise.

### GetSortIndexOk

`func (o *AppWithUserDto) GetSortIndexOk() (*int32, bool)`

GetSortIndexOk returns a tuple with the SortIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortIndex

`func (o *AppWithUserDto) SetSortIndex(v int32)`

SetSortIndex sets SortIndex field to given value.

### HasSortIndex

`func (o *AppWithUserDto) HasSortIndex() bool`

HasSortIndex returns a boolean if a field has been set.

### GetGitRepository

`func (o *AppWithUserDto) GetGitRepository() string`

GetGitRepository returns the GitRepository field if non-nil, zero value otherwise.

### GetGitRepositoryOk

`func (o *AppWithUserDto) GetGitRepositoryOk() (*string, bool)`

GetGitRepositoryOk returns a tuple with the GitRepository field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGitRepository

`func (o *AppWithUserDto) SetGitRepository(v string)`

SetGitRepository sets GitRepository field to given value.

### HasGitRepository

`func (o *AppWithUserDto) HasGitRepository() bool`

HasGitRepository returns a boolean if a field has been set.

### SetGitRepositoryNil

`func (o *AppWithUserDto) SetGitRepositoryNil(b bool)`

 SetGitRepositoryNil sets the value for GitRepository to be an explicit nil

### UnsetGitRepository
`func (o *AppWithUserDto) UnsetGitRepository()`

UnsetGitRepository ensures that no value is present for GitRepository, not even an explicit nil
### GetGitRepositoryType

`func (o *AppWithUserDto) GetGitRepositoryType() GitRepositoryType`

GetGitRepositoryType returns the GitRepositoryType field if non-nil, zero value otherwise.

### GetGitRepositoryTypeOk

`func (o *AppWithUserDto) GetGitRepositoryTypeOk() (*GitRepositoryType, bool)`

GetGitRepositoryTypeOk returns a tuple with the GitRepositoryType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGitRepositoryType

`func (o *AppWithUserDto) SetGitRepositoryType(v GitRepositoryType)`

SetGitRepositoryType sets GitRepositoryType field to given value.

### HasGitRepositoryType

`func (o *AppWithUserDto) HasGitRepositoryType() bool`

HasGitRepositoryType returns a boolean if a field has been set.

### GetIsEnabled

`func (o *AppWithUserDto) GetIsEnabled() bool`

GetIsEnabled returns the IsEnabled field if non-nil, zero value otherwise.

### GetIsEnabledOk

`func (o *AppWithUserDto) GetIsEnabledOk() (*bool, bool)`

GetIsEnabledOk returns a tuple with the IsEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsEnabled

`func (o *AppWithUserDto) SetIsEnabled(v bool)`

SetIsEnabled sets IsEnabled field to given value.

### HasIsEnabled

`func (o *AppWithUserDto) HasIsEnabled() bool`

HasIsEnabled returns a boolean if a field has been set.

### GetIsPublished

`func (o *AppWithUserDto) GetIsPublished() bool`

GetIsPublished returns the IsPublished field if non-nil, zero value otherwise.

### GetIsPublishedOk

`func (o *AppWithUserDto) GetIsPublishedOk() (*bool, bool)`

GetIsPublishedOk returns a tuple with the IsPublished field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPublished

`func (o *AppWithUserDto) SetIsPublished(v bool)`

SetIsPublished sets IsPublished field to given value.

### HasIsPublished

`func (o *AppWithUserDto) HasIsPublished() bool`

HasIsPublished returns a boolean if a field has been set.

### GetWebhookUrl

`func (o *AppWithUserDto) GetWebhookUrl() string`

GetWebhookUrl returns the WebhookUrl field if non-nil, zero value otherwise.

### GetWebhookUrlOk

`func (o *AppWithUserDto) GetWebhookUrlOk() (*string, bool)`

GetWebhookUrlOk returns a tuple with the WebhookUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhookUrl

`func (o *AppWithUserDto) SetWebhookUrl(v string)`

SetWebhookUrl sets WebhookUrl field to given value.

### HasWebhookUrl

`func (o *AppWithUserDto) HasWebhookUrl() bool`

HasWebhookUrl returns a boolean if a field has been set.

### SetWebhookUrlNil

`func (o *AppWithUserDto) SetWebhookUrlNil(b bool)`

 SetWebhookUrlNil sets the value for WebhookUrl to be an explicit nil

### UnsetWebhookUrl
`func (o *AppWithUserDto) UnsetWebhookUrl()`

UnsetWebhookUrl ensures that no value is present for WebhookUrl, not even an explicit nil
### GetBusinessDomain

`func (o *AppWithUserDto) GetBusinessDomain() string`

GetBusinessDomain returns the BusinessDomain field if non-nil, zero value otherwise.

### GetBusinessDomainOk

`func (o *AppWithUserDto) GetBusinessDomainOk() (*string, bool)`

GetBusinessDomainOk returns a tuple with the BusinessDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessDomain

`func (o *AppWithUserDto) SetBusinessDomain(v string)`

SetBusinessDomain sets BusinessDomain field to given value.

### HasBusinessDomain

`func (o *AppWithUserDto) HasBusinessDomain() bool`

HasBusinessDomain returns a boolean if a field has been set.

### SetBusinessDomainNil

`func (o *AppWithUserDto) SetBusinessDomainNil(b bool)`

 SetBusinessDomainNil sets the value for BusinessDomain to be an explicit nil

### UnsetBusinessDomain
`func (o *AppWithUserDto) UnsetBusinessDomain()`

UnsetBusinessDomain ensures that no value is present for BusinessDomain, not even an explicit nil
### GetBusinessUrl

`func (o *AppWithUserDto) GetBusinessUrl() string`

GetBusinessUrl returns the BusinessUrl field if non-nil, zero value otherwise.

### GetBusinessUrlOk

`func (o *AppWithUserDto) GetBusinessUrlOk() (*string, bool)`

GetBusinessUrlOk returns a tuple with the BusinessUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessUrl

`func (o *AppWithUserDto) SetBusinessUrl(v string)`

SetBusinessUrl sets BusinessUrl field to given value.

### HasBusinessUrl

`func (o *AppWithUserDto) HasBusinessUrl() bool`

HasBusinessUrl returns a boolean if a field has been set.

### SetBusinessUrlNil

`func (o *AppWithUserDto) SetBusinessUrlNil(b bool)`

 SetBusinessUrlNil sets the value for BusinessUrl to be an explicit nil

### UnsetBusinessUrl
`func (o *AppWithUserDto) UnsetBusinessUrl()`

UnsetBusinessUrl ensures that no value is present for BusinessUrl, not even an explicit nil
### GetSubscriptionPlatforms

`func (o *AppWithUserDto) GetSubscriptionPlatforms() string`

GetSubscriptionPlatforms returns the SubscriptionPlatforms field if non-nil, zero value otherwise.

### GetSubscriptionPlatformsOk

`func (o *AppWithUserDto) GetSubscriptionPlatformsOk() (*string, bool)`

GetSubscriptionPlatformsOk returns a tuple with the SubscriptionPlatforms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubscriptionPlatforms

`func (o *AppWithUserDto) SetSubscriptionPlatforms(v string)`

SetSubscriptionPlatforms sets SubscriptionPlatforms field to given value.

### HasSubscriptionPlatforms

`func (o *AppWithUserDto) HasSubscriptionPlatforms() bool`

HasSubscriptionPlatforms returns a boolean if a field has been set.

### SetSubscriptionPlatformsNil

`func (o *AppWithUserDto) SetSubscriptionPlatformsNil(b bool)`

 SetSubscriptionPlatformsNil sets the value for SubscriptionPlatforms to be an explicit nil

### UnsetSubscriptionPlatforms
`func (o *AppWithUserDto) UnsetSubscriptionPlatforms()`

UnsetSubscriptionPlatforms ensures that no value is present for SubscriptionPlatforms, not even an explicit nil
### GetFreePlatforms

`func (o *AppWithUserDto) GetFreePlatforms() string`

GetFreePlatforms returns the FreePlatforms field if non-nil, zero value otherwise.

### GetFreePlatformsOk

`func (o *AppWithUserDto) GetFreePlatformsOk() (*string, bool)`

GetFreePlatformsOk returns a tuple with the FreePlatforms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreePlatforms

`func (o *AppWithUserDto) SetFreePlatforms(v string)`

SetFreePlatforms sets FreePlatforms field to given value.

### HasFreePlatforms

`func (o *AppWithUserDto) HasFreePlatforms() bool`

HasFreePlatforms returns a boolean if a field has been set.

### SetFreePlatformsNil

`func (o *AppWithUserDto) SetFreePlatformsNil(b bool)`

 SetFreePlatformsNil sets the value for FreePlatforms to be an explicit nil

### UnsetFreePlatforms
`func (o *AppWithUserDto) UnsetFreePlatforms()`

UnsetFreePlatforms ensures that no value is present for FreePlatforms, not even an explicit nil
### GetSpecJsonSchema

`func (o *AppWithUserDto) GetSpecJsonSchema() string`

GetSpecJsonSchema returns the SpecJsonSchema field if non-nil, zero value otherwise.

### GetSpecJsonSchemaOk

`func (o *AppWithUserDto) GetSpecJsonSchemaOk() (*string, bool)`

GetSpecJsonSchemaOk returns a tuple with the SpecJsonSchema field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpecJsonSchema

`func (o *AppWithUserDto) SetSpecJsonSchema(v string)`

SetSpecJsonSchema sets SpecJsonSchema field to given value.

### HasSpecJsonSchema

`func (o *AppWithUserDto) HasSpecJsonSchema() bool`

HasSpecJsonSchema returns a boolean if a field has been set.

### SetSpecJsonSchemaNil

`func (o *AppWithUserDto) SetSpecJsonSchemaNil(b bool)`

 SetSpecJsonSchemaNil sets the value for SpecJsonSchema to be an explicit nil

### UnsetSpecJsonSchema
`func (o *AppWithUserDto) UnsetSpecJsonSchema()`

UnsetSpecJsonSchema ensures that no value is present for SpecJsonSchema, not even an explicit nil
### GetDefaultStorageSize

`func (o *AppWithUserDto) GetDefaultStorageSize() int64`

GetDefaultStorageSize returns the DefaultStorageSize field if non-nil, zero value otherwise.

### GetDefaultStorageSizeOk

`func (o *AppWithUserDto) GetDefaultStorageSizeOk() (*int64, bool)`

GetDefaultStorageSizeOk returns a tuple with the DefaultStorageSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultStorageSize

`func (o *AppWithUserDto) SetDefaultStorageSize(v int64)`

SetDefaultStorageSize sets DefaultStorageSize field to given value.

### HasDefaultStorageSize

`func (o *AppWithUserDto) HasDefaultStorageSize() bool`

HasDefaultStorageSize returns a boolean if a field has been set.

### GetDefaultSingleFileMaxSize

`func (o *AppWithUserDto) GetDefaultSingleFileMaxSize() int64`

GetDefaultSingleFileMaxSize returns the DefaultSingleFileMaxSize field if non-nil, zero value otherwise.

### GetDefaultSingleFileMaxSizeOk

`func (o *AppWithUserDto) GetDefaultSingleFileMaxSizeOk() (*int64, bool)`

GetDefaultSingleFileMaxSizeOk returns a tuple with the DefaultSingleFileMaxSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultSingleFileMaxSize

`func (o *AppWithUserDto) SetDefaultSingleFileMaxSize(v int64)`

SetDefaultSingleFileMaxSize sets DefaultSingleFileMaxSize field to given value.

### HasDefaultSingleFileMaxSize

`func (o *AppWithUserDto) HasDefaultSingleFileMaxSize() bool`

HasDefaultSingleFileMaxSize returns a boolean if a field has been set.

### GetLatestReleases

`func (o *AppWithUserDto) GetLatestReleases() []AppReleaseDto`

GetLatestReleases returns the LatestReleases field if non-nil, zero value otherwise.

### GetLatestReleasesOk

`func (o *AppWithUserDto) GetLatestReleasesOk() (*[]AppReleaseDto, bool)`

GetLatestReleasesOk returns a tuple with the LatestReleases field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestReleases

`func (o *AppWithUserDto) SetLatestReleases(v []AppReleaseDto)`

SetLatestReleases sets LatestReleases field to given value.

### HasLatestReleases

`func (o *AppWithUserDto) HasLatestReleases() bool`

HasLatestReleases returns a boolean if a field has been set.

### SetLatestReleasesNil

`func (o *AppWithUserDto) SetLatestReleasesNil(b bool)`

 SetLatestReleasesNil sets the value for LatestReleases to be an explicit nil

### UnsetLatestReleases
`func (o *AppWithUserDto) UnsetLatestReleases()`

UnsetLatestReleases ensures that no value is present for LatestReleases, not even an explicit nil
### GetCreator

`func (o *AppWithUserDto) GetCreator() IdentityUserDto`

GetCreator returns the Creator field if non-nil, zero value otherwise.

### GetCreatorOk

`func (o *AppWithUserDto) GetCreatorOk() (*IdentityUserDto, bool)`

GetCreatorOk returns a tuple with the Creator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreator

`func (o *AppWithUserDto) SetCreator(v IdentityUserDto)`

SetCreator sets Creator field to given value.

### HasCreator

`func (o *AppWithUserDto) HasCreator() bool`

HasCreator returns a boolean if a field has been set.

### GetSubscribed

`func (o *AppWithUserDto) GetSubscribed() bool`

GetSubscribed returns the Subscribed field if non-nil, zero value otherwise.

### GetSubscribedOk

`func (o *AppWithUserDto) GetSubscribedOk() (*bool, bool)`

GetSubscribedOk returns a tuple with the Subscribed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubscribed

`func (o *AppWithUserDto) SetSubscribed(v bool)`

SetSubscribed sets Subscribed field to given value.

### HasSubscribed

`func (o *AppWithUserDto) HasSubscribed() bool`

HasSubscribed returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


