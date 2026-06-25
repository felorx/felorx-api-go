# CreateOrUpdateAppPricingItemDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | Pointer to **NullableString** | 键值, 例如: Seat, MaxListCount（见 AppPricingItemKeys） | [optional]
**AppId** | Pointer to **NullableString** | 所属应用 | [optional]
**Name** | Pointer to **NullableString** | 名称: 坐席 | [optional]
**Description** | Pointer to **NullableString** | 描述, 使用 Markdown 格式, 允许包含图片 | [optional]
**LinkUrl** | Pointer to **NullableString** | 链接地址 | [optional]
**Display** | Pointer to **NullableString** | 显示模板: 包括{0}个坐席 | [optional]
**SortIndex** | Pointer to **int32** | 排序 | [optional]

## Methods

### NewCreateOrUpdateAppPricingItemDto

`func NewCreateOrUpdateAppPricingItemDto() *CreateOrUpdateAppPricingItemDto`

NewCreateOrUpdateAppPricingItemDto instantiates a new CreateOrUpdateAppPricingItemDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrUpdateAppPricingItemDtoWithDefaults

`func NewCreateOrUpdateAppPricingItemDtoWithDefaults() *CreateOrUpdateAppPricingItemDto`

NewCreateOrUpdateAppPricingItemDtoWithDefaults instantiates a new CreateOrUpdateAppPricingItemDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *CreateOrUpdateAppPricingItemDto) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *CreateOrUpdateAppPricingItemDto) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *CreateOrUpdateAppPricingItemDto) SetKey(v string)`

SetKey sets Key field to given value.

### HasKey

`func (o *CreateOrUpdateAppPricingItemDto) HasKey() bool`

HasKey returns a boolean if a field has been set.

### SetKeyNil

`func (o *CreateOrUpdateAppPricingItemDto) SetKeyNil(b bool)`

 SetKeyNil sets the value for Key to be an explicit nil

### UnsetKey
`func (o *CreateOrUpdateAppPricingItemDto) UnsetKey()`

UnsetKey ensures that no value is present for Key, not even an explicit nil
### GetAppId

`func (o *CreateOrUpdateAppPricingItemDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *CreateOrUpdateAppPricingItemDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *CreateOrUpdateAppPricingItemDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *CreateOrUpdateAppPricingItemDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### SetAppIdNil

`func (o *CreateOrUpdateAppPricingItemDto) SetAppIdNil(b bool)`

 SetAppIdNil sets the value for AppId to be an explicit nil

### UnsetAppId
`func (o *CreateOrUpdateAppPricingItemDto) UnsetAppId()`

UnsetAppId ensures that no value is present for AppId, not even an explicit nil
### GetName

`func (o *CreateOrUpdateAppPricingItemDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateOrUpdateAppPricingItemDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateOrUpdateAppPricingItemDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CreateOrUpdateAppPricingItemDto) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *CreateOrUpdateAppPricingItemDto) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *CreateOrUpdateAppPricingItemDto) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetDescription

`func (o *CreateOrUpdateAppPricingItemDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateOrUpdateAppPricingItemDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateOrUpdateAppPricingItemDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateOrUpdateAppPricingItemDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *CreateOrUpdateAppPricingItemDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *CreateOrUpdateAppPricingItemDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetLinkUrl

`func (o *CreateOrUpdateAppPricingItemDto) GetLinkUrl() string`

GetLinkUrl returns the LinkUrl field if non-nil, zero value otherwise.

### GetLinkUrlOk

`func (o *CreateOrUpdateAppPricingItemDto) GetLinkUrlOk() (*string, bool)`

GetLinkUrlOk returns a tuple with the LinkUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinkUrl

`func (o *CreateOrUpdateAppPricingItemDto) SetLinkUrl(v string)`

SetLinkUrl sets LinkUrl field to given value.

### HasLinkUrl

`func (o *CreateOrUpdateAppPricingItemDto) HasLinkUrl() bool`

HasLinkUrl returns a boolean if a field has been set.

### SetLinkUrlNil

`func (o *CreateOrUpdateAppPricingItemDto) SetLinkUrlNil(b bool)`

 SetLinkUrlNil sets the value for LinkUrl to be an explicit nil

### UnsetLinkUrl
`func (o *CreateOrUpdateAppPricingItemDto) UnsetLinkUrl()`

UnsetLinkUrl ensures that no value is present for LinkUrl, not even an explicit nil
### GetDisplay

`func (o *CreateOrUpdateAppPricingItemDto) GetDisplay() string`

GetDisplay returns the Display field if non-nil, zero value otherwise.

### GetDisplayOk

`func (o *CreateOrUpdateAppPricingItemDto) GetDisplayOk() (*string, bool)`

GetDisplayOk returns a tuple with the Display field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplay

`func (o *CreateOrUpdateAppPricingItemDto) SetDisplay(v string)`

SetDisplay sets Display field to given value.

### HasDisplay

`func (o *CreateOrUpdateAppPricingItemDto) HasDisplay() bool`

HasDisplay returns a boolean if a field has been set.

### SetDisplayNil

`func (o *CreateOrUpdateAppPricingItemDto) SetDisplayNil(b bool)`

 SetDisplayNil sets the value for Display to be an explicit nil

### UnsetDisplay
`func (o *CreateOrUpdateAppPricingItemDto) UnsetDisplay()`

UnsetDisplay ensures that no value is present for Display, not even an explicit nil
### GetSortIndex

`func (o *CreateOrUpdateAppPricingItemDto) GetSortIndex() int32`

GetSortIndex returns the SortIndex field if non-nil, zero value otherwise.

### GetSortIndexOk

`func (o *CreateOrUpdateAppPricingItemDto) GetSortIndexOk() (*int32, bool)`

GetSortIndexOk returns a tuple with the SortIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortIndex

`func (o *CreateOrUpdateAppPricingItemDto) SetSortIndex(v int32)`

SetSortIndex sets SortIndex field to given value.

### HasSortIndex

`func (o *CreateOrUpdateAppPricingItemDto) HasSortIndex() bool`

HasSortIndex returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


