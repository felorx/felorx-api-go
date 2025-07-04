# CreateOrUpdateAppDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **NullableString** |  | [optional] 
**DisplayName** | Pointer to **NullableString** |  | [optional] 
**Framework** | Pointer to [**AppFramework**](AppFramework.md) |  | [optional] 
**AppType** | Pointer to [**AppType**](AppType.md) |  | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**Icon** | Pointer to **NullableString** |  | [optional] 
**HomePage** | Pointer to **NullableString** | 产品首页 | [optional] 
**SortIndex** | Pointer to **int32** | 显示排序 | [optional] 
**GitRepository** | Pointer to **NullableString** |  | [optional] 
**GitRepositoryType** | Pointer to [**GitRepositoryType**](GitRepositoryType.md) |  | [optional] 
**IsEnabled** | Pointer to **bool** |  | [optional] 
**WebhookUrl** | Pointer to **NullableString** | Webhook Url 各种事件回调地址 | [optional] 
**BusinessDomain** | Pointer to **NullableString** | 业务域名 | [optional] 
**BusinessUrl** | Pointer to **NullableString** | 业务地址 | [optional] 
**SubscriptionPlatforms** | Pointer to **NullableString** | 可以订阅的平台 Platform 枚举, 并用\&quot;,\&quot;分割 | [optional] 
**FreePlatforms** | Pointer to **NullableString** | 暂时免费的平台, 付费功能免费用的平台, 用\&quot;,\&quot;分割 | [optional] 
**SpecJsonSchema** | Pointer to **NullableString** | 声明格式 | [optional] 
**DefaultStorageSize** | Pointer to **int64** | 默认存储空间大小 | [optional] 
**DefaultSingleFileMaxSize** | Pointer to **int64** | 默认单文件最大大小 | [optional] 
**IsPublished** | Pointer to **bool** | 是否已经发布, 决定了是否给终端用户看见, 主要有一些 APP 自己使用 | [optional] 
**OpenClient** | Pointer to [**CreateOpenIddictApplicationDto**](CreateOpenIddictApplicationDto.md) |  | [optional] 

## Methods

### NewCreateOrUpdateAppDto

`func NewCreateOrUpdateAppDto() *CreateOrUpdateAppDto`

NewCreateOrUpdateAppDto instantiates a new CreateOrUpdateAppDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrUpdateAppDtoWithDefaults

`func NewCreateOrUpdateAppDtoWithDefaults() *CreateOrUpdateAppDto`

NewCreateOrUpdateAppDtoWithDefaults instantiates a new CreateOrUpdateAppDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateOrUpdateAppDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateOrUpdateAppDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateOrUpdateAppDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CreateOrUpdateAppDto) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *CreateOrUpdateAppDto) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *CreateOrUpdateAppDto) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetDisplayName

`func (o *CreateOrUpdateAppDto) GetDisplayName() string`

GetDisplayName returns the DisplayName field if non-nil, zero value otherwise.

### GetDisplayNameOk

`func (o *CreateOrUpdateAppDto) GetDisplayNameOk() (*string, bool)`

GetDisplayNameOk returns a tuple with the DisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayName

`func (o *CreateOrUpdateAppDto) SetDisplayName(v string)`

SetDisplayName sets DisplayName field to given value.

### HasDisplayName

`func (o *CreateOrUpdateAppDto) HasDisplayName() bool`

HasDisplayName returns a boolean if a field has been set.

### SetDisplayNameNil

`func (o *CreateOrUpdateAppDto) SetDisplayNameNil(b bool)`

 SetDisplayNameNil sets the value for DisplayName to be an explicit nil

### UnsetDisplayName
`func (o *CreateOrUpdateAppDto) UnsetDisplayName()`

UnsetDisplayName ensures that no value is present for DisplayName, not even an explicit nil
### GetFramework

`func (o *CreateOrUpdateAppDto) GetFramework() AppFramework`

GetFramework returns the Framework field if non-nil, zero value otherwise.

### GetFrameworkOk

`func (o *CreateOrUpdateAppDto) GetFrameworkOk() (*AppFramework, bool)`

GetFrameworkOk returns a tuple with the Framework field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFramework

`func (o *CreateOrUpdateAppDto) SetFramework(v AppFramework)`

SetFramework sets Framework field to given value.

### HasFramework

`func (o *CreateOrUpdateAppDto) HasFramework() bool`

HasFramework returns a boolean if a field has been set.

### GetAppType

`func (o *CreateOrUpdateAppDto) GetAppType() AppType`

GetAppType returns the AppType field if non-nil, zero value otherwise.

### GetAppTypeOk

`func (o *CreateOrUpdateAppDto) GetAppTypeOk() (*AppType, bool)`

GetAppTypeOk returns a tuple with the AppType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppType

`func (o *CreateOrUpdateAppDto) SetAppType(v AppType)`

SetAppType sets AppType field to given value.

### HasAppType

`func (o *CreateOrUpdateAppDto) HasAppType() bool`

HasAppType returns a boolean if a field has been set.

### GetDescription

`func (o *CreateOrUpdateAppDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateOrUpdateAppDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateOrUpdateAppDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateOrUpdateAppDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *CreateOrUpdateAppDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *CreateOrUpdateAppDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetIcon

`func (o *CreateOrUpdateAppDto) GetIcon() string`

GetIcon returns the Icon field if non-nil, zero value otherwise.

### GetIconOk

`func (o *CreateOrUpdateAppDto) GetIconOk() (*string, bool)`

GetIconOk returns a tuple with the Icon field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIcon

`func (o *CreateOrUpdateAppDto) SetIcon(v string)`

SetIcon sets Icon field to given value.

### HasIcon

`func (o *CreateOrUpdateAppDto) HasIcon() bool`

HasIcon returns a boolean if a field has been set.

### SetIconNil

`func (o *CreateOrUpdateAppDto) SetIconNil(b bool)`

 SetIconNil sets the value for Icon to be an explicit nil

### UnsetIcon
`func (o *CreateOrUpdateAppDto) UnsetIcon()`

UnsetIcon ensures that no value is present for Icon, not even an explicit nil
### GetHomePage

`func (o *CreateOrUpdateAppDto) GetHomePage() string`

GetHomePage returns the HomePage field if non-nil, zero value otherwise.

### GetHomePageOk

`func (o *CreateOrUpdateAppDto) GetHomePageOk() (*string, bool)`

GetHomePageOk returns a tuple with the HomePage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHomePage

`func (o *CreateOrUpdateAppDto) SetHomePage(v string)`

SetHomePage sets HomePage field to given value.

### HasHomePage

`func (o *CreateOrUpdateAppDto) HasHomePage() bool`

HasHomePage returns a boolean if a field has been set.

### SetHomePageNil

`func (o *CreateOrUpdateAppDto) SetHomePageNil(b bool)`

 SetHomePageNil sets the value for HomePage to be an explicit nil

### UnsetHomePage
`func (o *CreateOrUpdateAppDto) UnsetHomePage()`

UnsetHomePage ensures that no value is present for HomePage, not even an explicit nil
### GetSortIndex

`func (o *CreateOrUpdateAppDto) GetSortIndex() int32`

GetSortIndex returns the SortIndex field if non-nil, zero value otherwise.

### GetSortIndexOk

`func (o *CreateOrUpdateAppDto) GetSortIndexOk() (*int32, bool)`

GetSortIndexOk returns a tuple with the SortIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortIndex

`func (o *CreateOrUpdateAppDto) SetSortIndex(v int32)`

SetSortIndex sets SortIndex field to given value.

### HasSortIndex

`func (o *CreateOrUpdateAppDto) HasSortIndex() bool`

HasSortIndex returns a boolean if a field has been set.

### GetGitRepository

`func (o *CreateOrUpdateAppDto) GetGitRepository() string`

GetGitRepository returns the GitRepository field if non-nil, zero value otherwise.

### GetGitRepositoryOk

`func (o *CreateOrUpdateAppDto) GetGitRepositoryOk() (*string, bool)`

GetGitRepositoryOk returns a tuple with the GitRepository field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGitRepository

`func (o *CreateOrUpdateAppDto) SetGitRepository(v string)`

SetGitRepository sets GitRepository field to given value.

### HasGitRepository

`func (o *CreateOrUpdateAppDto) HasGitRepository() bool`

HasGitRepository returns a boolean if a field has been set.

### SetGitRepositoryNil

`func (o *CreateOrUpdateAppDto) SetGitRepositoryNil(b bool)`

 SetGitRepositoryNil sets the value for GitRepository to be an explicit nil

### UnsetGitRepository
`func (o *CreateOrUpdateAppDto) UnsetGitRepository()`

UnsetGitRepository ensures that no value is present for GitRepository, not even an explicit nil
### GetGitRepositoryType

`func (o *CreateOrUpdateAppDto) GetGitRepositoryType() GitRepositoryType`

GetGitRepositoryType returns the GitRepositoryType field if non-nil, zero value otherwise.

### GetGitRepositoryTypeOk

`func (o *CreateOrUpdateAppDto) GetGitRepositoryTypeOk() (*GitRepositoryType, bool)`

GetGitRepositoryTypeOk returns a tuple with the GitRepositoryType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGitRepositoryType

`func (o *CreateOrUpdateAppDto) SetGitRepositoryType(v GitRepositoryType)`

SetGitRepositoryType sets GitRepositoryType field to given value.

### HasGitRepositoryType

`func (o *CreateOrUpdateAppDto) HasGitRepositoryType() bool`

HasGitRepositoryType returns a boolean if a field has been set.

### GetIsEnabled

`func (o *CreateOrUpdateAppDto) GetIsEnabled() bool`

GetIsEnabled returns the IsEnabled field if non-nil, zero value otherwise.

### GetIsEnabledOk

`func (o *CreateOrUpdateAppDto) GetIsEnabledOk() (*bool, bool)`

GetIsEnabledOk returns a tuple with the IsEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsEnabled

`func (o *CreateOrUpdateAppDto) SetIsEnabled(v bool)`

SetIsEnabled sets IsEnabled field to given value.

### HasIsEnabled

`func (o *CreateOrUpdateAppDto) HasIsEnabled() bool`

HasIsEnabled returns a boolean if a field has been set.

### GetWebhookUrl

`func (o *CreateOrUpdateAppDto) GetWebhookUrl() string`

GetWebhookUrl returns the WebhookUrl field if non-nil, zero value otherwise.

### GetWebhookUrlOk

`func (o *CreateOrUpdateAppDto) GetWebhookUrlOk() (*string, bool)`

GetWebhookUrlOk returns a tuple with the WebhookUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhookUrl

`func (o *CreateOrUpdateAppDto) SetWebhookUrl(v string)`

SetWebhookUrl sets WebhookUrl field to given value.

### HasWebhookUrl

`func (o *CreateOrUpdateAppDto) HasWebhookUrl() bool`

HasWebhookUrl returns a boolean if a field has been set.

### SetWebhookUrlNil

`func (o *CreateOrUpdateAppDto) SetWebhookUrlNil(b bool)`

 SetWebhookUrlNil sets the value for WebhookUrl to be an explicit nil

### UnsetWebhookUrl
`func (o *CreateOrUpdateAppDto) UnsetWebhookUrl()`

UnsetWebhookUrl ensures that no value is present for WebhookUrl, not even an explicit nil
### GetBusinessDomain

`func (o *CreateOrUpdateAppDto) GetBusinessDomain() string`

GetBusinessDomain returns the BusinessDomain field if non-nil, zero value otherwise.

### GetBusinessDomainOk

`func (o *CreateOrUpdateAppDto) GetBusinessDomainOk() (*string, bool)`

GetBusinessDomainOk returns a tuple with the BusinessDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessDomain

`func (o *CreateOrUpdateAppDto) SetBusinessDomain(v string)`

SetBusinessDomain sets BusinessDomain field to given value.

### HasBusinessDomain

`func (o *CreateOrUpdateAppDto) HasBusinessDomain() bool`

HasBusinessDomain returns a boolean if a field has been set.

### SetBusinessDomainNil

`func (o *CreateOrUpdateAppDto) SetBusinessDomainNil(b bool)`

 SetBusinessDomainNil sets the value for BusinessDomain to be an explicit nil

### UnsetBusinessDomain
`func (o *CreateOrUpdateAppDto) UnsetBusinessDomain()`

UnsetBusinessDomain ensures that no value is present for BusinessDomain, not even an explicit nil
### GetBusinessUrl

`func (o *CreateOrUpdateAppDto) GetBusinessUrl() string`

GetBusinessUrl returns the BusinessUrl field if non-nil, zero value otherwise.

### GetBusinessUrlOk

`func (o *CreateOrUpdateAppDto) GetBusinessUrlOk() (*string, bool)`

GetBusinessUrlOk returns a tuple with the BusinessUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessUrl

`func (o *CreateOrUpdateAppDto) SetBusinessUrl(v string)`

SetBusinessUrl sets BusinessUrl field to given value.

### HasBusinessUrl

`func (o *CreateOrUpdateAppDto) HasBusinessUrl() bool`

HasBusinessUrl returns a boolean if a field has been set.

### SetBusinessUrlNil

`func (o *CreateOrUpdateAppDto) SetBusinessUrlNil(b bool)`

 SetBusinessUrlNil sets the value for BusinessUrl to be an explicit nil

### UnsetBusinessUrl
`func (o *CreateOrUpdateAppDto) UnsetBusinessUrl()`

UnsetBusinessUrl ensures that no value is present for BusinessUrl, not even an explicit nil
### GetSubscriptionPlatforms

`func (o *CreateOrUpdateAppDto) GetSubscriptionPlatforms() string`

GetSubscriptionPlatforms returns the SubscriptionPlatforms field if non-nil, zero value otherwise.

### GetSubscriptionPlatformsOk

`func (o *CreateOrUpdateAppDto) GetSubscriptionPlatformsOk() (*string, bool)`

GetSubscriptionPlatformsOk returns a tuple with the SubscriptionPlatforms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubscriptionPlatforms

`func (o *CreateOrUpdateAppDto) SetSubscriptionPlatforms(v string)`

SetSubscriptionPlatforms sets SubscriptionPlatforms field to given value.

### HasSubscriptionPlatforms

`func (o *CreateOrUpdateAppDto) HasSubscriptionPlatforms() bool`

HasSubscriptionPlatforms returns a boolean if a field has been set.

### SetSubscriptionPlatformsNil

`func (o *CreateOrUpdateAppDto) SetSubscriptionPlatformsNil(b bool)`

 SetSubscriptionPlatformsNil sets the value for SubscriptionPlatforms to be an explicit nil

### UnsetSubscriptionPlatforms
`func (o *CreateOrUpdateAppDto) UnsetSubscriptionPlatforms()`

UnsetSubscriptionPlatforms ensures that no value is present for SubscriptionPlatforms, not even an explicit nil
### GetFreePlatforms

`func (o *CreateOrUpdateAppDto) GetFreePlatforms() string`

GetFreePlatforms returns the FreePlatforms field if non-nil, zero value otherwise.

### GetFreePlatformsOk

`func (o *CreateOrUpdateAppDto) GetFreePlatformsOk() (*string, bool)`

GetFreePlatformsOk returns a tuple with the FreePlatforms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreePlatforms

`func (o *CreateOrUpdateAppDto) SetFreePlatforms(v string)`

SetFreePlatforms sets FreePlatforms field to given value.

### HasFreePlatforms

`func (o *CreateOrUpdateAppDto) HasFreePlatforms() bool`

HasFreePlatforms returns a boolean if a field has been set.

### SetFreePlatformsNil

`func (o *CreateOrUpdateAppDto) SetFreePlatformsNil(b bool)`

 SetFreePlatformsNil sets the value for FreePlatforms to be an explicit nil

### UnsetFreePlatforms
`func (o *CreateOrUpdateAppDto) UnsetFreePlatforms()`

UnsetFreePlatforms ensures that no value is present for FreePlatforms, not even an explicit nil
### GetSpecJsonSchema

`func (o *CreateOrUpdateAppDto) GetSpecJsonSchema() string`

GetSpecJsonSchema returns the SpecJsonSchema field if non-nil, zero value otherwise.

### GetSpecJsonSchemaOk

`func (o *CreateOrUpdateAppDto) GetSpecJsonSchemaOk() (*string, bool)`

GetSpecJsonSchemaOk returns a tuple with the SpecJsonSchema field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpecJsonSchema

`func (o *CreateOrUpdateAppDto) SetSpecJsonSchema(v string)`

SetSpecJsonSchema sets SpecJsonSchema field to given value.

### HasSpecJsonSchema

`func (o *CreateOrUpdateAppDto) HasSpecJsonSchema() bool`

HasSpecJsonSchema returns a boolean if a field has been set.

### SetSpecJsonSchemaNil

`func (o *CreateOrUpdateAppDto) SetSpecJsonSchemaNil(b bool)`

 SetSpecJsonSchemaNil sets the value for SpecJsonSchema to be an explicit nil

### UnsetSpecJsonSchema
`func (o *CreateOrUpdateAppDto) UnsetSpecJsonSchema()`

UnsetSpecJsonSchema ensures that no value is present for SpecJsonSchema, not even an explicit nil
### GetDefaultStorageSize

`func (o *CreateOrUpdateAppDto) GetDefaultStorageSize() int64`

GetDefaultStorageSize returns the DefaultStorageSize field if non-nil, zero value otherwise.

### GetDefaultStorageSizeOk

`func (o *CreateOrUpdateAppDto) GetDefaultStorageSizeOk() (*int64, bool)`

GetDefaultStorageSizeOk returns a tuple with the DefaultStorageSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultStorageSize

`func (o *CreateOrUpdateAppDto) SetDefaultStorageSize(v int64)`

SetDefaultStorageSize sets DefaultStorageSize field to given value.

### HasDefaultStorageSize

`func (o *CreateOrUpdateAppDto) HasDefaultStorageSize() bool`

HasDefaultStorageSize returns a boolean if a field has been set.

### GetDefaultSingleFileMaxSize

`func (o *CreateOrUpdateAppDto) GetDefaultSingleFileMaxSize() int64`

GetDefaultSingleFileMaxSize returns the DefaultSingleFileMaxSize field if non-nil, zero value otherwise.

### GetDefaultSingleFileMaxSizeOk

`func (o *CreateOrUpdateAppDto) GetDefaultSingleFileMaxSizeOk() (*int64, bool)`

GetDefaultSingleFileMaxSizeOk returns a tuple with the DefaultSingleFileMaxSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultSingleFileMaxSize

`func (o *CreateOrUpdateAppDto) SetDefaultSingleFileMaxSize(v int64)`

SetDefaultSingleFileMaxSize sets DefaultSingleFileMaxSize field to given value.

### HasDefaultSingleFileMaxSize

`func (o *CreateOrUpdateAppDto) HasDefaultSingleFileMaxSize() bool`

HasDefaultSingleFileMaxSize returns a boolean if a field has been set.

### GetIsPublished

`func (o *CreateOrUpdateAppDto) GetIsPublished() bool`

GetIsPublished returns the IsPublished field if non-nil, zero value otherwise.

### GetIsPublishedOk

`func (o *CreateOrUpdateAppDto) GetIsPublishedOk() (*bool, bool)`

GetIsPublishedOk returns a tuple with the IsPublished field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPublished

`func (o *CreateOrUpdateAppDto) SetIsPublished(v bool)`

SetIsPublished sets IsPublished field to given value.

### HasIsPublished

`func (o *CreateOrUpdateAppDto) HasIsPublished() bool`

HasIsPublished returns a boolean if a field has been set.

### GetOpenClient

`func (o *CreateOrUpdateAppDto) GetOpenClient() CreateOpenIddictApplicationDto`

GetOpenClient returns the OpenClient field if non-nil, zero value otherwise.

### GetOpenClientOk

`func (o *CreateOrUpdateAppDto) GetOpenClientOk() (*CreateOpenIddictApplicationDto, bool)`

GetOpenClientOk returns a tuple with the OpenClient field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpenClient

`func (o *CreateOrUpdateAppDto) SetOpenClient(v CreateOpenIddictApplicationDto)`

SetOpenClient sets OpenClient field to given value.

### HasOpenClient

`func (o *CreateOrUpdateAppDto) HasOpenClient() bool`

HasOpenClient returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


