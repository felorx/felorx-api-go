# CreateOrUpdateAppPricingDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Naming** | Pointer to [**AppPriceNaming**](AppPriceNaming.md) |  | [optional]
**Description** | Pointer to **NullableString** | 简单描述  适用于个人网站和任何想用基本的聊天方式与游客交流的人。  适用于希望改善客户关系的早期创业公司。  为需要全功能解决方案与客户沟通的公司而设。 | [optional]
**AppId** | Pointer to **string** | APPID | [optional]
**SortIndex** | Pointer to **int32** | 排序 | [optional]
**Items** | Pointer to [**[]AppPricingItemValueDto**](AppPricingItemValueDto.md) | 收费点 | [optional]

## Methods

### NewCreateOrUpdateAppPricingDto

`func NewCreateOrUpdateAppPricingDto() *CreateOrUpdateAppPricingDto`

NewCreateOrUpdateAppPricingDto instantiates a new CreateOrUpdateAppPricingDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrUpdateAppPricingDtoWithDefaults

`func NewCreateOrUpdateAppPricingDtoWithDefaults() *CreateOrUpdateAppPricingDto`

NewCreateOrUpdateAppPricingDtoWithDefaults instantiates a new CreateOrUpdateAppPricingDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNaming

`func (o *CreateOrUpdateAppPricingDto) GetNaming() AppPriceNaming`

GetNaming returns the Naming field if non-nil, zero value otherwise.

### GetNamingOk

`func (o *CreateOrUpdateAppPricingDto) GetNamingOk() (*AppPriceNaming, bool)`

GetNamingOk returns a tuple with the Naming field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNaming

`func (o *CreateOrUpdateAppPricingDto) SetNaming(v AppPriceNaming)`

SetNaming sets Naming field to given value.

### HasNaming

`func (o *CreateOrUpdateAppPricingDto) HasNaming() bool`

HasNaming returns a boolean if a field has been set.

### GetDescription

`func (o *CreateOrUpdateAppPricingDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateOrUpdateAppPricingDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateOrUpdateAppPricingDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateOrUpdateAppPricingDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *CreateOrUpdateAppPricingDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *CreateOrUpdateAppPricingDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetAppId

`func (o *CreateOrUpdateAppPricingDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *CreateOrUpdateAppPricingDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *CreateOrUpdateAppPricingDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *CreateOrUpdateAppPricingDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetSortIndex

`func (o *CreateOrUpdateAppPricingDto) GetSortIndex() int32`

GetSortIndex returns the SortIndex field if non-nil, zero value otherwise.

### GetSortIndexOk

`func (o *CreateOrUpdateAppPricingDto) GetSortIndexOk() (*int32, bool)`

GetSortIndexOk returns a tuple with the SortIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortIndex

`func (o *CreateOrUpdateAppPricingDto) SetSortIndex(v int32)`

SetSortIndex sets SortIndex field to given value.

### HasSortIndex

`func (o *CreateOrUpdateAppPricingDto) HasSortIndex() bool`

HasSortIndex returns a boolean if a field has been set.

### GetItems

`func (o *CreateOrUpdateAppPricingDto) GetItems() []AppPricingItemValueDto`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *CreateOrUpdateAppPricingDto) GetItemsOk() (*[]AppPricingItemValueDto, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *CreateOrUpdateAppPricingDto) SetItems(v []AppPricingItemValueDto)`

SetItems sets Items field to given value.

### HasItems

`func (o *CreateOrUpdateAppPricingDto) HasItems() bool`

HasItems returns a boolean if a field has been set.

### SetItemsNil

`func (o *CreateOrUpdateAppPricingDto) SetItemsNil(b bool)`

 SetItemsNil sets the value for Items to be an explicit nil

### UnsetItems
`func (o *CreateOrUpdateAppPricingDto) UnsetItems()`

UnsetItems ensures that no value is present for Items, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


