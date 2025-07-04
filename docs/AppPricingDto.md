# AppPricingDto

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

### NewAppPricingDto

`func NewAppPricingDto() *AppPricingDto`

NewAppPricingDto instantiates a new AppPricingDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAppPricingDtoWithDefaults

`func NewAppPricingDtoWithDefaults() *AppPricingDto`

NewAppPricingDtoWithDefaults instantiates a new AppPricingDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AppPricingDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AppPricingDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AppPricingDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AppPricingDto) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreationTime

`func (o *AppPricingDto) GetCreationTime() time.Time`

GetCreationTime returns the CreationTime field if non-nil, zero value otherwise.

### GetCreationTimeOk

`func (o *AppPricingDto) GetCreationTimeOk() (*time.Time, bool)`

GetCreationTimeOk returns a tuple with the CreationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreationTime

`func (o *AppPricingDto) SetCreationTime(v time.Time)`

SetCreationTime sets CreationTime field to given value.

### HasCreationTime

`func (o *AppPricingDto) HasCreationTime() bool`

HasCreationTime returns a boolean if a field has been set.

### GetCreatorId

`func (o *AppPricingDto) GetCreatorId() string`

GetCreatorId returns the CreatorId field if non-nil, zero value otherwise.

### GetCreatorIdOk

`func (o *AppPricingDto) GetCreatorIdOk() (*string, bool)`

GetCreatorIdOk returns a tuple with the CreatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatorId

`func (o *AppPricingDto) SetCreatorId(v string)`

SetCreatorId sets CreatorId field to given value.

### HasCreatorId

`func (o *AppPricingDto) HasCreatorId() bool`

HasCreatorId returns a boolean if a field has been set.

### SetCreatorIdNil

`func (o *AppPricingDto) SetCreatorIdNil(b bool)`

 SetCreatorIdNil sets the value for CreatorId to be an explicit nil

### UnsetCreatorId
`func (o *AppPricingDto) UnsetCreatorId()`

UnsetCreatorId ensures that no value is present for CreatorId, not even an explicit nil
### GetLastModificationTime

`func (o *AppPricingDto) GetLastModificationTime() time.Time`

GetLastModificationTime returns the LastModificationTime field if non-nil, zero value otherwise.

### GetLastModificationTimeOk

`func (o *AppPricingDto) GetLastModificationTimeOk() (*time.Time, bool)`

GetLastModificationTimeOk returns a tuple with the LastModificationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModificationTime

`func (o *AppPricingDto) SetLastModificationTime(v time.Time)`

SetLastModificationTime sets LastModificationTime field to given value.

### HasLastModificationTime

`func (o *AppPricingDto) HasLastModificationTime() bool`

HasLastModificationTime returns a boolean if a field has been set.

### SetLastModificationTimeNil

`func (o *AppPricingDto) SetLastModificationTimeNil(b bool)`

 SetLastModificationTimeNil sets the value for LastModificationTime to be an explicit nil

### UnsetLastModificationTime
`func (o *AppPricingDto) UnsetLastModificationTime()`

UnsetLastModificationTime ensures that no value is present for LastModificationTime, not even an explicit nil
### GetLastModifierId

`func (o *AppPricingDto) GetLastModifierId() string`

GetLastModifierId returns the LastModifierId field if non-nil, zero value otherwise.

### GetLastModifierIdOk

`func (o *AppPricingDto) GetLastModifierIdOk() (*string, bool)`

GetLastModifierIdOk returns a tuple with the LastModifierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModifierId

`func (o *AppPricingDto) SetLastModifierId(v string)`

SetLastModifierId sets LastModifierId field to given value.

### HasLastModifierId

`func (o *AppPricingDto) HasLastModifierId() bool`

HasLastModifierId returns a boolean if a field has been set.

### SetLastModifierIdNil

`func (o *AppPricingDto) SetLastModifierIdNil(b bool)`

 SetLastModifierIdNil sets the value for LastModifierId to be an explicit nil

### UnsetLastModifierId
`func (o *AppPricingDto) UnsetLastModifierId()`

UnsetLastModifierId ensures that no value is present for LastModifierId, not even an explicit nil
### GetIsDeleted

`func (o *AppPricingDto) GetIsDeleted() bool`

GetIsDeleted returns the IsDeleted field if non-nil, zero value otherwise.

### GetIsDeletedOk

`func (o *AppPricingDto) GetIsDeletedOk() (*bool, bool)`

GetIsDeletedOk returns a tuple with the IsDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDeleted

`func (o *AppPricingDto) SetIsDeleted(v bool)`

SetIsDeleted sets IsDeleted field to given value.

### HasIsDeleted

`func (o *AppPricingDto) HasIsDeleted() bool`

HasIsDeleted returns a boolean if a field has been set.

### GetDeleterId

`func (o *AppPricingDto) GetDeleterId() string`

GetDeleterId returns the DeleterId field if non-nil, zero value otherwise.

### GetDeleterIdOk

`func (o *AppPricingDto) GetDeleterIdOk() (*string, bool)`

GetDeleterIdOk returns a tuple with the DeleterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleterId

`func (o *AppPricingDto) SetDeleterId(v string)`

SetDeleterId sets DeleterId field to given value.

### HasDeleterId

`func (o *AppPricingDto) HasDeleterId() bool`

HasDeleterId returns a boolean if a field has been set.

### SetDeleterIdNil

`func (o *AppPricingDto) SetDeleterIdNil(b bool)`

 SetDeleterIdNil sets the value for DeleterId to be an explicit nil

### UnsetDeleterId
`func (o *AppPricingDto) UnsetDeleterId()`

UnsetDeleterId ensures that no value is present for DeleterId, not even an explicit nil
### GetDeletionTime

`func (o *AppPricingDto) GetDeletionTime() time.Time`

GetDeletionTime returns the DeletionTime field if non-nil, zero value otherwise.

### GetDeletionTimeOk

`func (o *AppPricingDto) GetDeletionTimeOk() (*time.Time, bool)`

GetDeletionTimeOk returns a tuple with the DeletionTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletionTime

`func (o *AppPricingDto) SetDeletionTime(v time.Time)`

SetDeletionTime sets DeletionTime field to given value.

### HasDeletionTime

`func (o *AppPricingDto) HasDeletionTime() bool`

HasDeletionTime returns a boolean if a field has been set.

### SetDeletionTimeNil

`func (o *AppPricingDto) SetDeletionTimeNil(b bool)`

 SetDeletionTimeNil sets the value for DeletionTime to be an explicit nil

### UnsetDeletionTime
`func (o *AppPricingDto) UnsetDeletionTime()`

UnsetDeletionTime ensures that no value is present for DeletionTime, not even an explicit nil
### GetNaming

`func (o *AppPricingDto) GetNaming() AppPriceNaming`

GetNaming returns the Naming field if non-nil, zero value otherwise.

### GetNamingOk

`func (o *AppPricingDto) GetNamingOk() (*AppPriceNaming, bool)`

GetNamingOk returns a tuple with the Naming field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNaming

`func (o *AppPricingDto) SetNaming(v AppPriceNaming)`

SetNaming sets Naming field to given value.

### HasNaming

`func (o *AppPricingDto) HasNaming() bool`

HasNaming returns a boolean if a field has been set.

### GetMonthProductId

`func (o *AppPricingDto) GetMonthProductId() string`

GetMonthProductId returns the MonthProductId field if non-nil, zero value otherwise.

### GetMonthProductIdOk

`func (o *AppPricingDto) GetMonthProductIdOk() (*string, bool)`

GetMonthProductIdOk returns a tuple with the MonthProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthProductId

`func (o *AppPricingDto) SetMonthProductId(v string)`

SetMonthProductId sets MonthProductId field to given value.

### HasMonthProductId

`func (o *AppPricingDto) HasMonthProductId() bool`

HasMonthProductId returns a boolean if a field has been set.

### SetMonthProductIdNil

`func (o *AppPricingDto) SetMonthProductIdNil(b bool)`

 SetMonthProductIdNil sets the value for MonthProductId to be an explicit nil

### UnsetMonthProductId
`func (o *AppPricingDto) UnsetMonthProductId()`

UnsetMonthProductId ensures that no value is present for MonthProductId, not even an explicit nil
### GetYearProductId

`func (o *AppPricingDto) GetYearProductId() string`

GetYearProductId returns the YearProductId field if non-nil, zero value otherwise.

### GetYearProductIdOk

`func (o *AppPricingDto) GetYearProductIdOk() (*string, bool)`

GetYearProductIdOk returns a tuple with the YearProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearProductId

`func (o *AppPricingDto) SetYearProductId(v string)`

SetYearProductId sets YearProductId field to given value.

### HasYearProductId

`func (o *AppPricingDto) HasYearProductId() bool`

HasYearProductId returns a boolean if a field has been set.

### SetYearProductIdNil

`func (o *AppPricingDto) SetYearProductIdNil(b bool)`

 SetYearProductIdNil sets the value for YearProductId to be an explicit nil

### UnsetYearProductId
`func (o *AppPricingDto) UnsetYearProductId()`

UnsetYearProductId ensures that no value is present for YearProductId, not even an explicit nil
### GetDescription

`func (o *AppPricingDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *AppPricingDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *AppPricingDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *AppPricingDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *AppPricingDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *AppPricingDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetAppId

`func (o *AppPricingDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *AppPricingDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *AppPricingDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *AppPricingDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetMonthPrice

`func (o *AppPricingDto) GetMonthPrice() float64`

GetMonthPrice returns the MonthPrice field if non-nil, zero value otherwise.

### GetMonthPriceOk

`func (o *AppPricingDto) GetMonthPriceOk() (*float64, bool)`

GetMonthPriceOk returns a tuple with the MonthPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthPrice

`func (o *AppPricingDto) SetMonthPrice(v float64)`

SetMonthPrice sets MonthPrice field to given value.

### HasMonthPrice

`func (o *AppPricingDto) HasMonthPrice() bool`

HasMonthPrice returns a boolean if a field has been set.

### GetMonthDiscount

`func (o *AppPricingDto) GetMonthDiscount() float64`

GetMonthDiscount returns the MonthDiscount field if non-nil, zero value otherwise.

### GetMonthDiscountOk

`func (o *AppPricingDto) GetMonthDiscountOk() (*float64, bool)`

GetMonthDiscountOk returns a tuple with the MonthDiscount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthDiscount

`func (o *AppPricingDto) SetMonthDiscount(v float64)`

SetMonthDiscount sets MonthDiscount field to given value.

### HasMonthDiscount

`func (o *AppPricingDto) HasMonthDiscount() bool`

HasMonthDiscount returns a boolean if a field has been set.

### SetMonthDiscountNil

`func (o *AppPricingDto) SetMonthDiscountNil(b bool)`

 SetMonthDiscountNil sets the value for MonthDiscount to be an explicit nil

### UnsetMonthDiscount
`func (o *AppPricingDto) UnsetMonthDiscount()`

UnsetMonthDiscount ensures that no value is present for MonthDiscount, not even an explicit nil
### GetMonthDiscountPrice

`func (o *AppPricingDto) GetMonthDiscountPrice() float64`

GetMonthDiscountPrice returns the MonthDiscountPrice field if non-nil, zero value otherwise.

### GetMonthDiscountPriceOk

`func (o *AppPricingDto) GetMonthDiscountPriceOk() (*float64, bool)`

GetMonthDiscountPriceOk returns a tuple with the MonthDiscountPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthDiscountPrice

`func (o *AppPricingDto) SetMonthDiscountPrice(v float64)`

SetMonthDiscountPrice sets MonthDiscountPrice field to given value.

### HasMonthDiscountPrice

`func (o *AppPricingDto) HasMonthDiscountPrice() bool`

HasMonthDiscountPrice returns a boolean if a field has been set.

### SetMonthDiscountPriceNil

`func (o *AppPricingDto) SetMonthDiscountPriceNil(b bool)`

 SetMonthDiscountPriceNil sets the value for MonthDiscountPrice to be an explicit nil

### UnsetMonthDiscountPrice
`func (o *AppPricingDto) UnsetMonthDiscountPrice()`

UnsetMonthDiscountPrice ensures that no value is present for MonthDiscountPrice, not even an explicit nil
### GetMonthDiscountStartAt

`func (o *AppPricingDto) GetMonthDiscountStartAt() time.Time`

GetMonthDiscountStartAt returns the MonthDiscountStartAt field if non-nil, zero value otherwise.

### GetMonthDiscountStartAtOk

`func (o *AppPricingDto) GetMonthDiscountStartAtOk() (*time.Time, bool)`

GetMonthDiscountStartAtOk returns a tuple with the MonthDiscountStartAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthDiscountStartAt

`func (o *AppPricingDto) SetMonthDiscountStartAt(v time.Time)`

SetMonthDiscountStartAt sets MonthDiscountStartAt field to given value.

### HasMonthDiscountStartAt

`func (o *AppPricingDto) HasMonthDiscountStartAt() bool`

HasMonthDiscountStartAt returns a boolean if a field has been set.

### SetMonthDiscountStartAtNil

`func (o *AppPricingDto) SetMonthDiscountStartAtNil(b bool)`

 SetMonthDiscountStartAtNil sets the value for MonthDiscountStartAt to be an explicit nil

### UnsetMonthDiscountStartAt
`func (o *AppPricingDto) UnsetMonthDiscountStartAt()`

UnsetMonthDiscountStartAt ensures that no value is present for MonthDiscountStartAt, not even an explicit nil
### GetMonthDiscountEndAt

`func (o *AppPricingDto) GetMonthDiscountEndAt() time.Time`

GetMonthDiscountEndAt returns the MonthDiscountEndAt field if non-nil, zero value otherwise.

### GetMonthDiscountEndAtOk

`func (o *AppPricingDto) GetMonthDiscountEndAtOk() (*time.Time, bool)`

GetMonthDiscountEndAtOk returns a tuple with the MonthDiscountEndAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthDiscountEndAt

`func (o *AppPricingDto) SetMonthDiscountEndAt(v time.Time)`

SetMonthDiscountEndAt sets MonthDiscountEndAt field to given value.

### HasMonthDiscountEndAt

`func (o *AppPricingDto) HasMonthDiscountEndAt() bool`

HasMonthDiscountEndAt returns a boolean if a field has been set.

### SetMonthDiscountEndAtNil

`func (o *AppPricingDto) SetMonthDiscountEndAtNil(b bool)`

 SetMonthDiscountEndAtNil sets the value for MonthDiscountEndAt to be an explicit nil

### UnsetMonthDiscountEndAt
`func (o *AppPricingDto) UnsetMonthDiscountEndAt()`

UnsetMonthDiscountEndAt ensures that no value is present for MonthDiscountEndAt, not even an explicit nil
### GetYearPrice

`func (o *AppPricingDto) GetYearPrice() float64`

GetYearPrice returns the YearPrice field if non-nil, zero value otherwise.

### GetYearPriceOk

`func (o *AppPricingDto) GetYearPriceOk() (*float64, bool)`

GetYearPriceOk returns a tuple with the YearPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearPrice

`func (o *AppPricingDto) SetYearPrice(v float64)`

SetYearPrice sets YearPrice field to given value.

### HasYearPrice

`func (o *AppPricingDto) HasYearPrice() bool`

HasYearPrice returns a boolean if a field has been set.

### GetYearDiscount

`func (o *AppPricingDto) GetYearDiscount() float64`

GetYearDiscount returns the YearDiscount field if non-nil, zero value otherwise.

### GetYearDiscountOk

`func (o *AppPricingDto) GetYearDiscountOk() (*float64, bool)`

GetYearDiscountOk returns a tuple with the YearDiscount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearDiscount

`func (o *AppPricingDto) SetYearDiscount(v float64)`

SetYearDiscount sets YearDiscount field to given value.

### HasYearDiscount

`func (o *AppPricingDto) HasYearDiscount() bool`

HasYearDiscount returns a boolean if a field has been set.

### SetYearDiscountNil

`func (o *AppPricingDto) SetYearDiscountNil(b bool)`

 SetYearDiscountNil sets the value for YearDiscount to be an explicit nil

### UnsetYearDiscount
`func (o *AppPricingDto) UnsetYearDiscount()`

UnsetYearDiscount ensures that no value is present for YearDiscount, not even an explicit nil
### GetYearDiscountPrice

`func (o *AppPricingDto) GetYearDiscountPrice() float64`

GetYearDiscountPrice returns the YearDiscountPrice field if non-nil, zero value otherwise.

### GetYearDiscountPriceOk

`func (o *AppPricingDto) GetYearDiscountPriceOk() (*float64, bool)`

GetYearDiscountPriceOk returns a tuple with the YearDiscountPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearDiscountPrice

`func (o *AppPricingDto) SetYearDiscountPrice(v float64)`

SetYearDiscountPrice sets YearDiscountPrice field to given value.

### HasYearDiscountPrice

`func (o *AppPricingDto) HasYearDiscountPrice() bool`

HasYearDiscountPrice returns a boolean if a field has been set.

### SetYearDiscountPriceNil

`func (o *AppPricingDto) SetYearDiscountPriceNil(b bool)`

 SetYearDiscountPriceNil sets the value for YearDiscountPrice to be an explicit nil

### UnsetYearDiscountPrice
`func (o *AppPricingDto) UnsetYearDiscountPrice()`

UnsetYearDiscountPrice ensures that no value is present for YearDiscountPrice, not even an explicit nil
### GetYearDiscountStartAt

`func (o *AppPricingDto) GetYearDiscountStartAt() time.Time`

GetYearDiscountStartAt returns the YearDiscountStartAt field if non-nil, zero value otherwise.

### GetYearDiscountStartAtOk

`func (o *AppPricingDto) GetYearDiscountStartAtOk() (*time.Time, bool)`

GetYearDiscountStartAtOk returns a tuple with the YearDiscountStartAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearDiscountStartAt

`func (o *AppPricingDto) SetYearDiscountStartAt(v time.Time)`

SetYearDiscountStartAt sets YearDiscountStartAt field to given value.

### HasYearDiscountStartAt

`func (o *AppPricingDto) HasYearDiscountStartAt() bool`

HasYearDiscountStartAt returns a boolean if a field has been set.

### SetYearDiscountStartAtNil

`func (o *AppPricingDto) SetYearDiscountStartAtNil(b bool)`

 SetYearDiscountStartAtNil sets the value for YearDiscountStartAt to be an explicit nil

### UnsetYearDiscountStartAt
`func (o *AppPricingDto) UnsetYearDiscountStartAt()`

UnsetYearDiscountStartAt ensures that no value is present for YearDiscountStartAt, not even an explicit nil
### GetYearDiscountEndAt

`func (o *AppPricingDto) GetYearDiscountEndAt() time.Time`

GetYearDiscountEndAt returns the YearDiscountEndAt field if non-nil, zero value otherwise.

### GetYearDiscountEndAtOk

`func (o *AppPricingDto) GetYearDiscountEndAtOk() (*time.Time, bool)`

GetYearDiscountEndAtOk returns a tuple with the YearDiscountEndAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearDiscountEndAt

`func (o *AppPricingDto) SetYearDiscountEndAt(v time.Time)`

SetYearDiscountEndAt sets YearDiscountEndAt field to given value.

### HasYearDiscountEndAt

`func (o *AppPricingDto) HasYearDiscountEndAt() bool`

HasYearDiscountEndAt returns a boolean if a field has been set.

### SetYearDiscountEndAtNil

`func (o *AppPricingDto) SetYearDiscountEndAtNil(b bool)`

 SetYearDiscountEndAtNil sets the value for YearDiscountEndAt to be an explicit nil

### UnsetYearDiscountEndAt
`func (o *AppPricingDto) UnsetYearDiscountEndAt()`

UnsetYearDiscountEndAt ensures that no value is present for YearDiscountEndAt, not even an explicit nil
### GetSortIndex

`func (o *AppPricingDto) GetSortIndex() int32`

GetSortIndex returns the SortIndex field if non-nil, zero value otherwise.

### GetSortIndexOk

`func (o *AppPricingDto) GetSortIndexOk() (*int32, bool)`

GetSortIndexOk returns a tuple with the SortIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortIndex

`func (o *AppPricingDto) SetSortIndex(v int32)`

SetSortIndex sets SortIndex field to given value.

### HasSortIndex

`func (o *AppPricingDto) HasSortIndex() bool`

HasSortIndex returns a boolean if a field has been set.

### GetItems

`func (o *AppPricingDto) GetItems() []AppPricingItemValueDto`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *AppPricingDto) GetItemsOk() (*[]AppPricingItemValueDto, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *AppPricingDto) SetItems(v []AppPricingItemValueDto)`

SetItems sets Items field to given value.

### HasItems

`func (o *AppPricingDto) HasItems() bool`

HasItems returns a boolean if a field has been set.

### SetItemsNil

`func (o *AppPricingDto) SetItemsNil(b bool)`

 SetItemsNil sets the value for Items to be an explicit nil

### UnsetItems
`func (o *AppPricingDto) UnsetItems()`

UnsetItems ensures that no value is present for Items, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


