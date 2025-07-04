# CreateOrUpdateAppPricingDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Naming** | Pointer to [**AppPriceNaming**](AppPriceNaming.md) |  | [optional] 
**MonthProductId** | Pointer to **NullableString** | 商店订阅产品 ID | [optional] 
**YearProductId** | Pointer to **NullableString** | 商店订阅产品 ID | [optional] 
**Description** | Pointer to **NullableString** | 简单描述  适用于个人网站和任何想用基本的聊天方式与游客交流的人。  适用于希望改善客户关系的早期创业公司。  为需要全功能解决方案与客户沟通的公司而设。 | [optional] 
**AppId** | Pointer to **string** | APPID | [optional] 
**MonthPrice** | Pointer to **float64** | 价格 | [optional] 
**MonthDiscount** | Pointer to **NullableFloat64** | 折扣 | [optional] 
**MonthDiscountPrice** | Pointer to **NullableFloat64** | 折扣后价格 DiscountPrice &#x3D; Price * Discount | [optional] 
**MonthDiscountStartAt** | Pointer to **NullableTime** | 折扣开始时间 | [optional] 
**MonthDiscountEndAt** | Pointer to **NullableTime** | 折扣结束时间 | [optional] 
**YearPrice** | Pointer to **float64** | 价格 | [optional] 
**YearDiscount** | Pointer to **NullableFloat64** | 折扣 | [optional] 
**YearDiscountPrice** | Pointer to **NullableFloat64** | 折扣后价格 DiscountPrice &#x3D; Price * Discount | [optional] 
**YearDiscountStartAt** | Pointer to **NullableTime** | 折扣开始时间 | [optional] 
**YearDiscountEndAt** | Pointer to **NullableTime** | 折扣结束时间 | [optional] 
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

### GetMonthProductId

`func (o *CreateOrUpdateAppPricingDto) GetMonthProductId() string`

GetMonthProductId returns the MonthProductId field if non-nil, zero value otherwise.

### GetMonthProductIdOk

`func (o *CreateOrUpdateAppPricingDto) GetMonthProductIdOk() (*string, bool)`

GetMonthProductIdOk returns a tuple with the MonthProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthProductId

`func (o *CreateOrUpdateAppPricingDto) SetMonthProductId(v string)`

SetMonthProductId sets MonthProductId field to given value.

### HasMonthProductId

`func (o *CreateOrUpdateAppPricingDto) HasMonthProductId() bool`

HasMonthProductId returns a boolean if a field has been set.

### SetMonthProductIdNil

`func (o *CreateOrUpdateAppPricingDto) SetMonthProductIdNil(b bool)`

 SetMonthProductIdNil sets the value for MonthProductId to be an explicit nil

### UnsetMonthProductId
`func (o *CreateOrUpdateAppPricingDto) UnsetMonthProductId()`

UnsetMonthProductId ensures that no value is present for MonthProductId, not even an explicit nil
### GetYearProductId

`func (o *CreateOrUpdateAppPricingDto) GetYearProductId() string`

GetYearProductId returns the YearProductId field if non-nil, zero value otherwise.

### GetYearProductIdOk

`func (o *CreateOrUpdateAppPricingDto) GetYearProductIdOk() (*string, bool)`

GetYearProductIdOk returns a tuple with the YearProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearProductId

`func (o *CreateOrUpdateAppPricingDto) SetYearProductId(v string)`

SetYearProductId sets YearProductId field to given value.

### HasYearProductId

`func (o *CreateOrUpdateAppPricingDto) HasYearProductId() bool`

HasYearProductId returns a boolean if a field has been set.

### SetYearProductIdNil

`func (o *CreateOrUpdateAppPricingDto) SetYearProductIdNil(b bool)`

 SetYearProductIdNil sets the value for YearProductId to be an explicit nil

### UnsetYearProductId
`func (o *CreateOrUpdateAppPricingDto) UnsetYearProductId()`

UnsetYearProductId ensures that no value is present for YearProductId, not even an explicit nil
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

### GetMonthPrice

`func (o *CreateOrUpdateAppPricingDto) GetMonthPrice() float64`

GetMonthPrice returns the MonthPrice field if non-nil, zero value otherwise.

### GetMonthPriceOk

`func (o *CreateOrUpdateAppPricingDto) GetMonthPriceOk() (*float64, bool)`

GetMonthPriceOk returns a tuple with the MonthPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthPrice

`func (o *CreateOrUpdateAppPricingDto) SetMonthPrice(v float64)`

SetMonthPrice sets MonthPrice field to given value.

### HasMonthPrice

`func (o *CreateOrUpdateAppPricingDto) HasMonthPrice() bool`

HasMonthPrice returns a boolean if a field has been set.

### GetMonthDiscount

`func (o *CreateOrUpdateAppPricingDto) GetMonthDiscount() float64`

GetMonthDiscount returns the MonthDiscount field if non-nil, zero value otherwise.

### GetMonthDiscountOk

`func (o *CreateOrUpdateAppPricingDto) GetMonthDiscountOk() (*float64, bool)`

GetMonthDiscountOk returns a tuple with the MonthDiscount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthDiscount

`func (o *CreateOrUpdateAppPricingDto) SetMonthDiscount(v float64)`

SetMonthDiscount sets MonthDiscount field to given value.

### HasMonthDiscount

`func (o *CreateOrUpdateAppPricingDto) HasMonthDiscount() bool`

HasMonthDiscount returns a boolean if a field has been set.

### SetMonthDiscountNil

`func (o *CreateOrUpdateAppPricingDto) SetMonthDiscountNil(b bool)`

 SetMonthDiscountNil sets the value for MonthDiscount to be an explicit nil

### UnsetMonthDiscount
`func (o *CreateOrUpdateAppPricingDto) UnsetMonthDiscount()`

UnsetMonthDiscount ensures that no value is present for MonthDiscount, not even an explicit nil
### GetMonthDiscountPrice

`func (o *CreateOrUpdateAppPricingDto) GetMonthDiscountPrice() float64`

GetMonthDiscountPrice returns the MonthDiscountPrice field if non-nil, zero value otherwise.

### GetMonthDiscountPriceOk

`func (o *CreateOrUpdateAppPricingDto) GetMonthDiscountPriceOk() (*float64, bool)`

GetMonthDiscountPriceOk returns a tuple with the MonthDiscountPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthDiscountPrice

`func (o *CreateOrUpdateAppPricingDto) SetMonthDiscountPrice(v float64)`

SetMonthDiscountPrice sets MonthDiscountPrice field to given value.

### HasMonthDiscountPrice

`func (o *CreateOrUpdateAppPricingDto) HasMonthDiscountPrice() bool`

HasMonthDiscountPrice returns a boolean if a field has been set.

### SetMonthDiscountPriceNil

`func (o *CreateOrUpdateAppPricingDto) SetMonthDiscountPriceNil(b bool)`

 SetMonthDiscountPriceNil sets the value for MonthDiscountPrice to be an explicit nil

### UnsetMonthDiscountPrice
`func (o *CreateOrUpdateAppPricingDto) UnsetMonthDiscountPrice()`

UnsetMonthDiscountPrice ensures that no value is present for MonthDiscountPrice, not even an explicit nil
### GetMonthDiscountStartAt

`func (o *CreateOrUpdateAppPricingDto) GetMonthDiscountStartAt() time.Time`

GetMonthDiscountStartAt returns the MonthDiscountStartAt field if non-nil, zero value otherwise.

### GetMonthDiscountStartAtOk

`func (o *CreateOrUpdateAppPricingDto) GetMonthDiscountStartAtOk() (*time.Time, bool)`

GetMonthDiscountStartAtOk returns a tuple with the MonthDiscountStartAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthDiscountStartAt

`func (o *CreateOrUpdateAppPricingDto) SetMonthDiscountStartAt(v time.Time)`

SetMonthDiscountStartAt sets MonthDiscountStartAt field to given value.

### HasMonthDiscountStartAt

`func (o *CreateOrUpdateAppPricingDto) HasMonthDiscountStartAt() bool`

HasMonthDiscountStartAt returns a boolean if a field has been set.

### SetMonthDiscountStartAtNil

`func (o *CreateOrUpdateAppPricingDto) SetMonthDiscountStartAtNil(b bool)`

 SetMonthDiscountStartAtNil sets the value for MonthDiscountStartAt to be an explicit nil

### UnsetMonthDiscountStartAt
`func (o *CreateOrUpdateAppPricingDto) UnsetMonthDiscountStartAt()`

UnsetMonthDiscountStartAt ensures that no value is present for MonthDiscountStartAt, not even an explicit nil
### GetMonthDiscountEndAt

`func (o *CreateOrUpdateAppPricingDto) GetMonthDiscountEndAt() time.Time`

GetMonthDiscountEndAt returns the MonthDiscountEndAt field if non-nil, zero value otherwise.

### GetMonthDiscountEndAtOk

`func (o *CreateOrUpdateAppPricingDto) GetMonthDiscountEndAtOk() (*time.Time, bool)`

GetMonthDiscountEndAtOk returns a tuple with the MonthDiscountEndAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthDiscountEndAt

`func (o *CreateOrUpdateAppPricingDto) SetMonthDiscountEndAt(v time.Time)`

SetMonthDiscountEndAt sets MonthDiscountEndAt field to given value.

### HasMonthDiscountEndAt

`func (o *CreateOrUpdateAppPricingDto) HasMonthDiscountEndAt() bool`

HasMonthDiscountEndAt returns a boolean if a field has been set.

### SetMonthDiscountEndAtNil

`func (o *CreateOrUpdateAppPricingDto) SetMonthDiscountEndAtNil(b bool)`

 SetMonthDiscountEndAtNil sets the value for MonthDiscountEndAt to be an explicit nil

### UnsetMonthDiscountEndAt
`func (o *CreateOrUpdateAppPricingDto) UnsetMonthDiscountEndAt()`

UnsetMonthDiscountEndAt ensures that no value is present for MonthDiscountEndAt, not even an explicit nil
### GetYearPrice

`func (o *CreateOrUpdateAppPricingDto) GetYearPrice() float64`

GetYearPrice returns the YearPrice field if non-nil, zero value otherwise.

### GetYearPriceOk

`func (o *CreateOrUpdateAppPricingDto) GetYearPriceOk() (*float64, bool)`

GetYearPriceOk returns a tuple with the YearPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearPrice

`func (o *CreateOrUpdateAppPricingDto) SetYearPrice(v float64)`

SetYearPrice sets YearPrice field to given value.

### HasYearPrice

`func (o *CreateOrUpdateAppPricingDto) HasYearPrice() bool`

HasYearPrice returns a boolean if a field has been set.

### GetYearDiscount

`func (o *CreateOrUpdateAppPricingDto) GetYearDiscount() float64`

GetYearDiscount returns the YearDiscount field if non-nil, zero value otherwise.

### GetYearDiscountOk

`func (o *CreateOrUpdateAppPricingDto) GetYearDiscountOk() (*float64, bool)`

GetYearDiscountOk returns a tuple with the YearDiscount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearDiscount

`func (o *CreateOrUpdateAppPricingDto) SetYearDiscount(v float64)`

SetYearDiscount sets YearDiscount field to given value.

### HasYearDiscount

`func (o *CreateOrUpdateAppPricingDto) HasYearDiscount() bool`

HasYearDiscount returns a boolean if a field has been set.

### SetYearDiscountNil

`func (o *CreateOrUpdateAppPricingDto) SetYearDiscountNil(b bool)`

 SetYearDiscountNil sets the value for YearDiscount to be an explicit nil

### UnsetYearDiscount
`func (o *CreateOrUpdateAppPricingDto) UnsetYearDiscount()`

UnsetYearDiscount ensures that no value is present for YearDiscount, not even an explicit nil
### GetYearDiscountPrice

`func (o *CreateOrUpdateAppPricingDto) GetYearDiscountPrice() float64`

GetYearDiscountPrice returns the YearDiscountPrice field if non-nil, zero value otherwise.

### GetYearDiscountPriceOk

`func (o *CreateOrUpdateAppPricingDto) GetYearDiscountPriceOk() (*float64, bool)`

GetYearDiscountPriceOk returns a tuple with the YearDiscountPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearDiscountPrice

`func (o *CreateOrUpdateAppPricingDto) SetYearDiscountPrice(v float64)`

SetYearDiscountPrice sets YearDiscountPrice field to given value.

### HasYearDiscountPrice

`func (o *CreateOrUpdateAppPricingDto) HasYearDiscountPrice() bool`

HasYearDiscountPrice returns a boolean if a field has been set.

### SetYearDiscountPriceNil

`func (o *CreateOrUpdateAppPricingDto) SetYearDiscountPriceNil(b bool)`

 SetYearDiscountPriceNil sets the value for YearDiscountPrice to be an explicit nil

### UnsetYearDiscountPrice
`func (o *CreateOrUpdateAppPricingDto) UnsetYearDiscountPrice()`

UnsetYearDiscountPrice ensures that no value is present for YearDiscountPrice, not even an explicit nil
### GetYearDiscountStartAt

`func (o *CreateOrUpdateAppPricingDto) GetYearDiscountStartAt() time.Time`

GetYearDiscountStartAt returns the YearDiscountStartAt field if non-nil, zero value otherwise.

### GetYearDiscountStartAtOk

`func (o *CreateOrUpdateAppPricingDto) GetYearDiscountStartAtOk() (*time.Time, bool)`

GetYearDiscountStartAtOk returns a tuple with the YearDiscountStartAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearDiscountStartAt

`func (o *CreateOrUpdateAppPricingDto) SetYearDiscountStartAt(v time.Time)`

SetYearDiscountStartAt sets YearDiscountStartAt field to given value.

### HasYearDiscountStartAt

`func (o *CreateOrUpdateAppPricingDto) HasYearDiscountStartAt() bool`

HasYearDiscountStartAt returns a boolean if a field has been set.

### SetYearDiscountStartAtNil

`func (o *CreateOrUpdateAppPricingDto) SetYearDiscountStartAtNil(b bool)`

 SetYearDiscountStartAtNil sets the value for YearDiscountStartAt to be an explicit nil

### UnsetYearDiscountStartAt
`func (o *CreateOrUpdateAppPricingDto) UnsetYearDiscountStartAt()`

UnsetYearDiscountStartAt ensures that no value is present for YearDiscountStartAt, not even an explicit nil
### GetYearDiscountEndAt

`func (o *CreateOrUpdateAppPricingDto) GetYearDiscountEndAt() time.Time`

GetYearDiscountEndAt returns the YearDiscountEndAt field if non-nil, zero value otherwise.

### GetYearDiscountEndAtOk

`func (o *CreateOrUpdateAppPricingDto) GetYearDiscountEndAtOk() (*time.Time, bool)`

GetYearDiscountEndAtOk returns a tuple with the YearDiscountEndAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearDiscountEndAt

`func (o *CreateOrUpdateAppPricingDto) SetYearDiscountEndAt(v time.Time)`

SetYearDiscountEndAt sets YearDiscountEndAt field to given value.

### HasYearDiscountEndAt

`func (o *CreateOrUpdateAppPricingDto) HasYearDiscountEndAt() bool`

HasYearDiscountEndAt returns a boolean if a field has been set.

### SetYearDiscountEndAtNil

`func (o *CreateOrUpdateAppPricingDto) SetYearDiscountEndAtNil(b bool)`

 SetYearDiscountEndAtNil sets the value for YearDiscountEndAt to be an explicit nil

### UnsetYearDiscountEndAt
`func (o *CreateOrUpdateAppPricingDto) UnsetYearDiscountEndAt()`

UnsetYearDiscountEndAt ensures that no value is present for YearDiscountEndAt, not even an explicit nil
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


