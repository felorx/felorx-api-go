# SubscriptionDto

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
**ExpireAt** | Pointer to **NullableTime** | 会员过期时间 | [optional] 
**AppId** | Pointer to **string** | 应用 ID | [optional] 
**PriceNaming** | Pointer to [**AppPriceNaming**](AppPriceNaming.md) |  | [optional] 
**PricingId** | Pointer to **string** |  | [optional] 

## Methods

### NewSubscriptionDto

`func NewSubscriptionDto() *SubscriptionDto`

NewSubscriptionDto instantiates a new SubscriptionDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubscriptionDtoWithDefaults

`func NewSubscriptionDtoWithDefaults() *SubscriptionDto`

NewSubscriptionDtoWithDefaults instantiates a new SubscriptionDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SubscriptionDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SubscriptionDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SubscriptionDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SubscriptionDto) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreationTime

`func (o *SubscriptionDto) GetCreationTime() time.Time`

GetCreationTime returns the CreationTime field if non-nil, zero value otherwise.

### GetCreationTimeOk

`func (o *SubscriptionDto) GetCreationTimeOk() (*time.Time, bool)`

GetCreationTimeOk returns a tuple with the CreationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreationTime

`func (o *SubscriptionDto) SetCreationTime(v time.Time)`

SetCreationTime sets CreationTime field to given value.

### HasCreationTime

`func (o *SubscriptionDto) HasCreationTime() bool`

HasCreationTime returns a boolean if a field has been set.

### GetCreatorId

`func (o *SubscriptionDto) GetCreatorId() string`

GetCreatorId returns the CreatorId field if non-nil, zero value otherwise.

### GetCreatorIdOk

`func (o *SubscriptionDto) GetCreatorIdOk() (*string, bool)`

GetCreatorIdOk returns a tuple with the CreatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatorId

`func (o *SubscriptionDto) SetCreatorId(v string)`

SetCreatorId sets CreatorId field to given value.

### HasCreatorId

`func (o *SubscriptionDto) HasCreatorId() bool`

HasCreatorId returns a boolean if a field has been set.

### SetCreatorIdNil

`func (o *SubscriptionDto) SetCreatorIdNil(b bool)`

 SetCreatorIdNil sets the value for CreatorId to be an explicit nil

### UnsetCreatorId
`func (o *SubscriptionDto) UnsetCreatorId()`

UnsetCreatorId ensures that no value is present for CreatorId, not even an explicit nil
### GetLastModificationTime

`func (o *SubscriptionDto) GetLastModificationTime() time.Time`

GetLastModificationTime returns the LastModificationTime field if non-nil, zero value otherwise.

### GetLastModificationTimeOk

`func (o *SubscriptionDto) GetLastModificationTimeOk() (*time.Time, bool)`

GetLastModificationTimeOk returns a tuple with the LastModificationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModificationTime

`func (o *SubscriptionDto) SetLastModificationTime(v time.Time)`

SetLastModificationTime sets LastModificationTime field to given value.

### HasLastModificationTime

`func (o *SubscriptionDto) HasLastModificationTime() bool`

HasLastModificationTime returns a boolean if a field has been set.

### SetLastModificationTimeNil

`func (o *SubscriptionDto) SetLastModificationTimeNil(b bool)`

 SetLastModificationTimeNil sets the value for LastModificationTime to be an explicit nil

### UnsetLastModificationTime
`func (o *SubscriptionDto) UnsetLastModificationTime()`

UnsetLastModificationTime ensures that no value is present for LastModificationTime, not even an explicit nil
### GetLastModifierId

`func (o *SubscriptionDto) GetLastModifierId() string`

GetLastModifierId returns the LastModifierId field if non-nil, zero value otherwise.

### GetLastModifierIdOk

`func (o *SubscriptionDto) GetLastModifierIdOk() (*string, bool)`

GetLastModifierIdOk returns a tuple with the LastModifierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModifierId

`func (o *SubscriptionDto) SetLastModifierId(v string)`

SetLastModifierId sets LastModifierId field to given value.

### HasLastModifierId

`func (o *SubscriptionDto) HasLastModifierId() bool`

HasLastModifierId returns a boolean if a field has been set.

### SetLastModifierIdNil

`func (o *SubscriptionDto) SetLastModifierIdNil(b bool)`

 SetLastModifierIdNil sets the value for LastModifierId to be an explicit nil

### UnsetLastModifierId
`func (o *SubscriptionDto) UnsetLastModifierId()`

UnsetLastModifierId ensures that no value is present for LastModifierId, not even an explicit nil
### GetIsDeleted

`func (o *SubscriptionDto) GetIsDeleted() bool`

GetIsDeleted returns the IsDeleted field if non-nil, zero value otherwise.

### GetIsDeletedOk

`func (o *SubscriptionDto) GetIsDeletedOk() (*bool, bool)`

GetIsDeletedOk returns a tuple with the IsDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDeleted

`func (o *SubscriptionDto) SetIsDeleted(v bool)`

SetIsDeleted sets IsDeleted field to given value.

### HasIsDeleted

`func (o *SubscriptionDto) HasIsDeleted() bool`

HasIsDeleted returns a boolean if a field has been set.

### GetDeleterId

`func (o *SubscriptionDto) GetDeleterId() string`

GetDeleterId returns the DeleterId field if non-nil, zero value otherwise.

### GetDeleterIdOk

`func (o *SubscriptionDto) GetDeleterIdOk() (*string, bool)`

GetDeleterIdOk returns a tuple with the DeleterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleterId

`func (o *SubscriptionDto) SetDeleterId(v string)`

SetDeleterId sets DeleterId field to given value.

### HasDeleterId

`func (o *SubscriptionDto) HasDeleterId() bool`

HasDeleterId returns a boolean if a field has been set.

### SetDeleterIdNil

`func (o *SubscriptionDto) SetDeleterIdNil(b bool)`

 SetDeleterIdNil sets the value for DeleterId to be an explicit nil

### UnsetDeleterId
`func (o *SubscriptionDto) UnsetDeleterId()`

UnsetDeleterId ensures that no value is present for DeleterId, not even an explicit nil
### GetDeletionTime

`func (o *SubscriptionDto) GetDeletionTime() time.Time`

GetDeletionTime returns the DeletionTime field if non-nil, zero value otherwise.

### GetDeletionTimeOk

`func (o *SubscriptionDto) GetDeletionTimeOk() (*time.Time, bool)`

GetDeletionTimeOk returns a tuple with the DeletionTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletionTime

`func (o *SubscriptionDto) SetDeletionTime(v time.Time)`

SetDeletionTime sets DeletionTime field to given value.

### HasDeletionTime

`func (o *SubscriptionDto) HasDeletionTime() bool`

HasDeletionTime returns a boolean if a field has been set.

### SetDeletionTimeNil

`func (o *SubscriptionDto) SetDeletionTimeNil(b bool)`

 SetDeletionTimeNil sets the value for DeletionTime to be an explicit nil

### UnsetDeletionTime
`func (o *SubscriptionDto) UnsetDeletionTime()`

UnsetDeletionTime ensures that no value is present for DeletionTime, not even an explicit nil
### GetExpireAt

`func (o *SubscriptionDto) GetExpireAt() time.Time`

GetExpireAt returns the ExpireAt field if non-nil, zero value otherwise.

### GetExpireAtOk

`func (o *SubscriptionDto) GetExpireAtOk() (*time.Time, bool)`

GetExpireAtOk returns a tuple with the ExpireAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpireAt

`func (o *SubscriptionDto) SetExpireAt(v time.Time)`

SetExpireAt sets ExpireAt field to given value.

### HasExpireAt

`func (o *SubscriptionDto) HasExpireAt() bool`

HasExpireAt returns a boolean if a field has been set.

### SetExpireAtNil

`func (o *SubscriptionDto) SetExpireAtNil(b bool)`

 SetExpireAtNil sets the value for ExpireAt to be an explicit nil

### UnsetExpireAt
`func (o *SubscriptionDto) UnsetExpireAt()`

UnsetExpireAt ensures that no value is present for ExpireAt, not even an explicit nil
### GetAppId

`func (o *SubscriptionDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *SubscriptionDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *SubscriptionDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *SubscriptionDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetPriceNaming

`func (o *SubscriptionDto) GetPriceNaming() AppPriceNaming`

GetPriceNaming returns the PriceNaming field if non-nil, zero value otherwise.

### GetPriceNamingOk

`func (o *SubscriptionDto) GetPriceNamingOk() (*AppPriceNaming, bool)`

GetPriceNamingOk returns a tuple with the PriceNaming field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceNaming

`func (o *SubscriptionDto) SetPriceNaming(v AppPriceNaming)`

SetPriceNaming sets PriceNaming field to given value.

### HasPriceNaming

`func (o *SubscriptionDto) HasPriceNaming() bool`

HasPriceNaming returns a boolean if a field has been set.

### GetPricingId

`func (o *SubscriptionDto) GetPricingId() string`

GetPricingId returns the PricingId field if non-nil, zero value otherwise.

### GetPricingIdOk

`func (o *SubscriptionDto) GetPricingIdOk() (*string, bool)`

GetPricingIdOk returns a tuple with the PricingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPricingId

`func (o *SubscriptionDto) SetPricingId(v string)`

SetPricingId sets PricingId field to given value.

### HasPricingId

`func (o *SubscriptionDto) HasPricingId() bool`

HasPricingId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


