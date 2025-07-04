# AppPricingItemDto

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
**Key** | Pointer to **NullableString** | 键值, 例如: Seat, SingleFileMaxSize, UserStorageSize, MaxPuupeeCount, 见 AppPricingItemKeys.cs | [optional] 
**Name** | Pointer to **NullableString** | 名称: 坐席 | [optional] 
**Description** | Pointer to **NullableString** | 描述, 使用 Markdown 格式, 允许包含图片 | [optional] 
**LinkUrl** | Pointer to **NullableString** | 链接地址 | [optional] 
**Display** | Pointer to **NullableString** | 显示模板: 包括{0}个坐席 | [optional] 
**IsAvailable** | Pointer to **bool** | 是否可用 | [optional] 
**SortIndex** | Pointer to **int32** | 排序 | [optional] 

## Methods

### NewAppPricingItemDto

`func NewAppPricingItemDto() *AppPricingItemDto`

NewAppPricingItemDto instantiates a new AppPricingItemDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAppPricingItemDtoWithDefaults

`func NewAppPricingItemDtoWithDefaults() *AppPricingItemDto`

NewAppPricingItemDtoWithDefaults instantiates a new AppPricingItemDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AppPricingItemDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AppPricingItemDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AppPricingItemDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AppPricingItemDto) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreationTime

`func (o *AppPricingItemDto) GetCreationTime() time.Time`

GetCreationTime returns the CreationTime field if non-nil, zero value otherwise.

### GetCreationTimeOk

`func (o *AppPricingItemDto) GetCreationTimeOk() (*time.Time, bool)`

GetCreationTimeOk returns a tuple with the CreationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreationTime

`func (o *AppPricingItemDto) SetCreationTime(v time.Time)`

SetCreationTime sets CreationTime field to given value.

### HasCreationTime

`func (o *AppPricingItemDto) HasCreationTime() bool`

HasCreationTime returns a boolean if a field has been set.

### GetCreatorId

`func (o *AppPricingItemDto) GetCreatorId() string`

GetCreatorId returns the CreatorId field if non-nil, zero value otherwise.

### GetCreatorIdOk

`func (o *AppPricingItemDto) GetCreatorIdOk() (*string, bool)`

GetCreatorIdOk returns a tuple with the CreatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatorId

`func (o *AppPricingItemDto) SetCreatorId(v string)`

SetCreatorId sets CreatorId field to given value.

### HasCreatorId

`func (o *AppPricingItemDto) HasCreatorId() bool`

HasCreatorId returns a boolean if a field has been set.

### SetCreatorIdNil

`func (o *AppPricingItemDto) SetCreatorIdNil(b bool)`

 SetCreatorIdNil sets the value for CreatorId to be an explicit nil

### UnsetCreatorId
`func (o *AppPricingItemDto) UnsetCreatorId()`

UnsetCreatorId ensures that no value is present for CreatorId, not even an explicit nil
### GetLastModificationTime

`func (o *AppPricingItemDto) GetLastModificationTime() time.Time`

GetLastModificationTime returns the LastModificationTime field if non-nil, zero value otherwise.

### GetLastModificationTimeOk

`func (o *AppPricingItemDto) GetLastModificationTimeOk() (*time.Time, bool)`

GetLastModificationTimeOk returns a tuple with the LastModificationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModificationTime

`func (o *AppPricingItemDto) SetLastModificationTime(v time.Time)`

SetLastModificationTime sets LastModificationTime field to given value.

### HasLastModificationTime

`func (o *AppPricingItemDto) HasLastModificationTime() bool`

HasLastModificationTime returns a boolean if a field has been set.

### SetLastModificationTimeNil

`func (o *AppPricingItemDto) SetLastModificationTimeNil(b bool)`

 SetLastModificationTimeNil sets the value for LastModificationTime to be an explicit nil

### UnsetLastModificationTime
`func (o *AppPricingItemDto) UnsetLastModificationTime()`

UnsetLastModificationTime ensures that no value is present for LastModificationTime, not even an explicit nil
### GetLastModifierId

`func (o *AppPricingItemDto) GetLastModifierId() string`

GetLastModifierId returns the LastModifierId field if non-nil, zero value otherwise.

### GetLastModifierIdOk

`func (o *AppPricingItemDto) GetLastModifierIdOk() (*string, bool)`

GetLastModifierIdOk returns a tuple with the LastModifierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModifierId

`func (o *AppPricingItemDto) SetLastModifierId(v string)`

SetLastModifierId sets LastModifierId field to given value.

### HasLastModifierId

`func (o *AppPricingItemDto) HasLastModifierId() bool`

HasLastModifierId returns a boolean if a field has been set.

### SetLastModifierIdNil

`func (o *AppPricingItemDto) SetLastModifierIdNil(b bool)`

 SetLastModifierIdNil sets the value for LastModifierId to be an explicit nil

### UnsetLastModifierId
`func (o *AppPricingItemDto) UnsetLastModifierId()`

UnsetLastModifierId ensures that no value is present for LastModifierId, not even an explicit nil
### GetIsDeleted

`func (o *AppPricingItemDto) GetIsDeleted() bool`

GetIsDeleted returns the IsDeleted field if non-nil, zero value otherwise.

### GetIsDeletedOk

`func (o *AppPricingItemDto) GetIsDeletedOk() (*bool, bool)`

GetIsDeletedOk returns a tuple with the IsDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDeleted

`func (o *AppPricingItemDto) SetIsDeleted(v bool)`

SetIsDeleted sets IsDeleted field to given value.

### HasIsDeleted

`func (o *AppPricingItemDto) HasIsDeleted() bool`

HasIsDeleted returns a boolean if a field has been set.

### GetDeleterId

`func (o *AppPricingItemDto) GetDeleterId() string`

GetDeleterId returns the DeleterId field if non-nil, zero value otherwise.

### GetDeleterIdOk

`func (o *AppPricingItemDto) GetDeleterIdOk() (*string, bool)`

GetDeleterIdOk returns a tuple with the DeleterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleterId

`func (o *AppPricingItemDto) SetDeleterId(v string)`

SetDeleterId sets DeleterId field to given value.

### HasDeleterId

`func (o *AppPricingItemDto) HasDeleterId() bool`

HasDeleterId returns a boolean if a field has been set.

### SetDeleterIdNil

`func (o *AppPricingItemDto) SetDeleterIdNil(b bool)`

 SetDeleterIdNil sets the value for DeleterId to be an explicit nil

### UnsetDeleterId
`func (o *AppPricingItemDto) UnsetDeleterId()`

UnsetDeleterId ensures that no value is present for DeleterId, not even an explicit nil
### GetDeletionTime

`func (o *AppPricingItemDto) GetDeletionTime() time.Time`

GetDeletionTime returns the DeletionTime field if non-nil, zero value otherwise.

### GetDeletionTimeOk

`func (o *AppPricingItemDto) GetDeletionTimeOk() (*time.Time, bool)`

GetDeletionTimeOk returns a tuple with the DeletionTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletionTime

`func (o *AppPricingItemDto) SetDeletionTime(v time.Time)`

SetDeletionTime sets DeletionTime field to given value.

### HasDeletionTime

`func (o *AppPricingItemDto) HasDeletionTime() bool`

HasDeletionTime returns a boolean if a field has been set.

### SetDeletionTimeNil

`func (o *AppPricingItemDto) SetDeletionTimeNil(b bool)`

 SetDeletionTimeNil sets the value for DeletionTime to be an explicit nil

### UnsetDeletionTime
`func (o *AppPricingItemDto) UnsetDeletionTime()`

UnsetDeletionTime ensures that no value is present for DeletionTime, not even an explicit nil
### GetKey

`func (o *AppPricingItemDto) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *AppPricingItemDto) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *AppPricingItemDto) SetKey(v string)`

SetKey sets Key field to given value.

### HasKey

`func (o *AppPricingItemDto) HasKey() bool`

HasKey returns a boolean if a field has been set.

### SetKeyNil

`func (o *AppPricingItemDto) SetKeyNil(b bool)`

 SetKeyNil sets the value for Key to be an explicit nil

### UnsetKey
`func (o *AppPricingItemDto) UnsetKey()`

UnsetKey ensures that no value is present for Key, not even an explicit nil
### GetName

`func (o *AppPricingItemDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AppPricingItemDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AppPricingItemDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *AppPricingItemDto) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *AppPricingItemDto) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *AppPricingItemDto) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetDescription

`func (o *AppPricingItemDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *AppPricingItemDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *AppPricingItemDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *AppPricingItemDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *AppPricingItemDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *AppPricingItemDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetLinkUrl

`func (o *AppPricingItemDto) GetLinkUrl() string`

GetLinkUrl returns the LinkUrl field if non-nil, zero value otherwise.

### GetLinkUrlOk

`func (o *AppPricingItemDto) GetLinkUrlOk() (*string, bool)`

GetLinkUrlOk returns a tuple with the LinkUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinkUrl

`func (o *AppPricingItemDto) SetLinkUrl(v string)`

SetLinkUrl sets LinkUrl field to given value.

### HasLinkUrl

`func (o *AppPricingItemDto) HasLinkUrl() bool`

HasLinkUrl returns a boolean if a field has been set.

### SetLinkUrlNil

`func (o *AppPricingItemDto) SetLinkUrlNil(b bool)`

 SetLinkUrlNil sets the value for LinkUrl to be an explicit nil

### UnsetLinkUrl
`func (o *AppPricingItemDto) UnsetLinkUrl()`

UnsetLinkUrl ensures that no value is present for LinkUrl, not even an explicit nil
### GetDisplay

`func (o *AppPricingItemDto) GetDisplay() string`

GetDisplay returns the Display field if non-nil, zero value otherwise.

### GetDisplayOk

`func (o *AppPricingItemDto) GetDisplayOk() (*string, bool)`

GetDisplayOk returns a tuple with the Display field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplay

`func (o *AppPricingItemDto) SetDisplay(v string)`

SetDisplay sets Display field to given value.

### HasDisplay

`func (o *AppPricingItemDto) HasDisplay() bool`

HasDisplay returns a boolean if a field has been set.

### SetDisplayNil

`func (o *AppPricingItemDto) SetDisplayNil(b bool)`

 SetDisplayNil sets the value for Display to be an explicit nil

### UnsetDisplay
`func (o *AppPricingItemDto) UnsetDisplay()`

UnsetDisplay ensures that no value is present for Display, not even an explicit nil
### GetIsAvailable

`func (o *AppPricingItemDto) GetIsAvailable() bool`

GetIsAvailable returns the IsAvailable field if non-nil, zero value otherwise.

### GetIsAvailableOk

`func (o *AppPricingItemDto) GetIsAvailableOk() (*bool, bool)`

GetIsAvailableOk returns a tuple with the IsAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsAvailable

`func (o *AppPricingItemDto) SetIsAvailable(v bool)`

SetIsAvailable sets IsAvailable field to given value.

### HasIsAvailable

`func (o *AppPricingItemDto) HasIsAvailable() bool`

HasIsAvailable returns a boolean if a field has been set.

### GetSortIndex

`func (o *AppPricingItemDto) GetSortIndex() int32`

GetSortIndex returns the SortIndex field if non-nil, zero value otherwise.

### GetSortIndexOk

`func (o *AppPricingItemDto) GetSortIndexOk() (*int32, bool)`

GetSortIndexOk returns a tuple with the SortIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortIndex

`func (o *AppPricingItemDto) SetSortIndex(v int32)`

SetSortIndex sets SortIndex field to given value.

### HasSortIndex

`func (o *AppPricingItemDto) HasSortIndex() bool`

HasSortIndex returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


