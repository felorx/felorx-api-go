# UserStorageDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppId** | Pointer to **string** | 所属应用 | [optional] 
**AppName** | Pointer to **NullableString** | 应用名称 | [optional] 
**PriceNaming** | Pointer to [**AppPriceNaming**](AppPriceNaming.md) |  | [optional] 
**Size** | Pointer to **int64** | 用户存储容量 | [optional] 
**CurrentSize** | Pointer to **int64** | 当前使用大小 | [optional] 
**TotalCount** | Pointer to **int32** |  | [optional] 
**SingleFileMaxSize** | Pointer to **int64** | 单文件最大大小 | [optional] 
**ExpireAt** | Pointer to **NullableTime** | 过期时间, 为空表示永久有效, 一般是订阅产品的过期时间 | [optional] 
**Items** | Pointer to [**[]UserStorageItemDto**](UserStorageItemDto.md) |  | [optional] 

## Methods

### NewUserStorageDto

`func NewUserStorageDto() *UserStorageDto`

NewUserStorageDto instantiates a new UserStorageDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserStorageDtoWithDefaults

`func NewUserStorageDtoWithDefaults() *UserStorageDto`

NewUserStorageDtoWithDefaults instantiates a new UserStorageDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppId

`func (o *UserStorageDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *UserStorageDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *UserStorageDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *UserStorageDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetAppName

`func (o *UserStorageDto) GetAppName() string`

GetAppName returns the AppName field if non-nil, zero value otherwise.

### GetAppNameOk

`func (o *UserStorageDto) GetAppNameOk() (*string, bool)`

GetAppNameOk returns a tuple with the AppName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppName

`func (o *UserStorageDto) SetAppName(v string)`

SetAppName sets AppName field to given value.

### HasAppName

`func (o *UserStorageDto) HasAppName() bool`

HasAppName returns a boolean if a field has been set.

### SetAppNameNil

`func (o *UserStorageDto) SetAppNameNil(b bool)`

 SetAppNameNil sets the value for AppName to be an explicit nil

### UnsetAppName
`func (o *UserStorageDto) UnsetAppName()`

UnsetAppName ensures that no value is present for AppName, not even an explicit nil
### GetPriceNaming

`func (o *UserStorageDto) GetPriceNaming() AppPriceNaming`

GetPriceNaming returns the PriceNaming field if non-nil, zero value otherwise.

### GetPriceNamingOk

`func (o *UserStorageDto) GetPriceNamingOk() (*AppPriceNaming, bool)`

GetPriceNamingOk returns a tuple with the PriceNaming field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceNaming

`func (o *UserStorageDto) SetPriceNaming(v AppPriceNaming)`

SetPriceNaming sets PriceNaming field to given value.

### HasPriceNaming

`func (o *UserStorageDto) HasPriceNaming() bool`

HasPriceNaming returns a boolean if a field has been set.

### GetSize

`func (o *UserStorageDto) GetSize() int64`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *UserStorageDto) GetSizeOk() (*int64, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *UserStorageDto) SetSize(v int64)`

SetSize sets Size field to given value.

### HasSize

`func (o *UserStorageDto) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetCurrentSize

`func (o *UserStorageDto) GetCurrentSize() int64`

GetCurrentSize returns the CurrentSize field if non-nil, zero value otherwise.

### GetCurrentSizeOk

`func (o *UserStorageDto) GetCurrentSizeOk() (*int64, bool)`

GetCurrentSizeOk returns a tuple with the CurrentSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentSize

`func (o *UserStorageDto) SetCurrentSize(v int64)`

SetCurrentSize sets CurrentSize field to given value.

### HasCurrentSize

`func (o *UserStorageDto) HasCurrentSize() bool`

HasCurrentSize returns a boolean if a field has been set.

### GetTotalCount

`func (o *UserStorageDto) GetTotalCount() int32`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *UserStorageDto) GetTotalCountOk() (*int32, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *UserStorageDto) SetTotalCount(v int32)`

SetTotalCount sets TotalCount field to given value.

### HasTotalCount

`func (o *UserStorageDto) HasTotalCount() bool`

HasTotalCount returns a boolean if a field has been set.

### GetSingleFileMaxSize

`func (o *UserStorageDto) GetSingleFileMaxSize() int64`

GetSingleFileMaxSize returns the SingleFileMaxSize field if non-nil, zero value otherwise.

### GetSingleFileMaxSizeOk

`func (o *UserStorageDto) GetSingleFileMaxSizeOk() (*int64, bool)`

GetSingleFileMaxSizeOk returns a tuple with the SingleFileMaxSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSingleFileMaxSize

`func (o *UserStorageDto) SetSingleFileMaxSize(v int64)`

SetSingleFileMaxSize sets SingleFileMaxSize field to given value.

### HasSingleFileMaxSize

`func (o *UserStorageDto) HasSingleFileMaxSize() bool`

HasSingleFileMaxSize returns a boolean if a field has been set.

### GetExpireAt

`func (o *UserStorageDto) GetExpireAt() time.Time`

GetExpireAt returns the ExpireAt field if non-nil, zero value otherwise.

### GetExpireAtOk

`func (o *UserStorageDto) GetExpireAtOk() (*time.Time, bool)`

GetExpireAtOk returns a tuple with the ExpireAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpireAt

`func (o *UserStorageDto) SetExpireAt(v time.Time)`

SetExpireAt sets ExpireAt field to given value.

### HasExpireAt

`func (o *UserStorageDto) HasExpireAt() bool`

HasExpireAt returns a boolean if a field has been set.

### SetExpireAtNil

`func (o *UserStorageDto) SetExpireAtNil(b bool)`

 SetExpireAtNil sets the value for ExpireAt to be an explicit nil

### UnsetExpireAt
`func (o *UserStorageDto) UnsetExpireAt()`

UnsetExpireAt ensures that no value is present for ExpireAt, not even an explicit nil
### GetItems

`func (o *UserStorageDto) GetItems() []UserStorageItemDto`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *UserStorageDto) GetItemsOk() (*[]UserStorageItemDto, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *UserStorageDto) SetItems(v []UserStorageItemDto)`

SetItems sets Items field to given value.

### HasItems

`func (o *UserStorageDto) HasItems() bool`

HasItems returns a boolean if a field has been set.

### SetItemsNil

`func (o *UserStorageDto) SetItemsNil(b bool)`

 SetItemsNil sets the value for Items to be an explicit nil

### UnsetItems
`func (o *UserStorageDto) UnsetItems()`

UnsetItems ensures that no value is present for Items, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


