# StoreProductMappingDto

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
**AppId** | Pointer to **string** |  | [optional] 
**PricingId** | Pointer to **string** |  | [optional] 
**PlanPriceId** | Pointer to **NullableString** |  | [optional] 
**Provider** | Pointer to [**BillingProvider**](BillingProvider.md) |  | [optional] 
**Platform** | Pointer to [**AppPlatform**](AppPlatform.md) |  | [optional] 
**Period** | Pointer to [**SubBillingPeriod**](SubBillingPeriod.md) |  | [optional] 
**StoreProductId** | Pointer to **NullableString** |  | [optional] 
**ExternalProductId** | Pointer to **NullableString** |  | [optional] 
**Environment** | Pointer to **NullableString** |  | [optional] 
**IsEnabled** | Pointer to **bool** |  | [optional] 

## Methods

### NewStoreProductMappingDto

`func NewStoreProductMappingDto() *StoreProductMappingDto`

NewStoreProductMappingDto instantiates a new StoreProductMappingDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStoreProductMappingDtoWithDefaults

`func NewStoreProductMappingDtoWithDefaults() *StoreProductMappingDto`

NewStoreProductMappingDtoWithDefaults instantiates a new StoreProductMappingDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *StoreProductMappingDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *StoreProductMappingDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *StoreProductMappingDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *StoreProductMappingDto) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreationTime

`func (o *StoreProductMappingDto) GetCreationTime() time.Time`

GetCreationTime returns the CreationTime field if non-nil, zero value otherwise.

### GetCreationTimeOk

`func (o *StoreProductMappingDto) GetCreationTimeOk() (*time.Time, bool)`

GetCreationTimeOk returns a tuple with the CreationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreationTime

`func (o *StoreProductMappingDto) SetCreationTime(v time.Time)`

SetCreationTime sets CreationTime field to given value.

### HasCreationTime

`func (o *StoreProductMappingDto) HasCreationTime() bool`

HasCreationTime returns a boolean if a field has been set.

### GetCreatorId

`func (o *StoreProductMappingDto) GetCreatorId() string`

GetCreatorId returns the CreatorId field if non-nil, zero value otherwise.

### GetCreatorIdOk

`func (o *StoreProductMappingDto) GetCreatorIdOk() (*string, bool)`

GetCreatorIdOk returns a tuple with the CreatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatorId

`func (o *StoreProductMappingDto) SetCreatorId(v string)`

SetCreatorId sets CreatorId field to given value.

### HasCreatorId

`func (o *StoreProductMappingDto) HasCreatorId() bool`

HasCreatorId returns a boolean if a field has been set.

### SetCreatorIdNil

`func (o *StoreProductMappingDto) SetCreatorIdNil(b bool)`

 SetCreatorIdNil sets the value for CreatorId to be an explicit nil

### UnsetCreatorId
`func (o *StoreProductMappingDto) UnsetCreatorId()`

UnsetCreatorId ensures that no value is present for CreatorId, not even an explicit nil
### GetLastModificationTime

`func (o *StoreProductMappingDto) GetLastModificationTime() time.Time`

GetLastModificationTime returns the LastModificationTime field if non-nil, zero value otherwise.

### GetLastModificationTimeOk

`func (o *StoreProductMappingDto) GetLastModificationTimeOk() (*time.Time, bool)`

GetLastModificationTimeOk returns a tuple with the LastModificationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModificationTime

`func (o *StoreProductMappingDto) SetLastModificationTime(v time.Time)`

SetLastModificationTime sets LastModificationTime field to given value.

### HasLastModificationTime

`func (o *StoreProductMappingDto) HasLastModificationTime() bool`

HasLastModificationTime returns a boolean if a field has been set.

### SetLastModificationTimeNil

`func (o *StoreProductMappingDto) SetLastModificationTimeNil(b bool)`

 SetLastModificationTimeNil sets the value for LastModificationTime to be an explicit nil

### UnsetLastModificationTime
`func (o *StoreProductMappingDto) UnsetLastModificationTime()`

UnsetLastModificationTime ensures that no value is present for LastModificationTime, not even an explicit nil
### GetLastModifierId

`func (o *StoreProductMappingDto) GetLastModifierId() string`

GetLastModifierId returns the LastModifierId field if non-nil, zero value otherwise.

### GetLastModifierIdOk

`func (o *StoreProductMappingDto) GetLastModifierIdOk() (*string, bool)`

GetLastModifierIdOk returns a tuple with the LastModifierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModifierId

`func (o *StoreProductMappingDto) SetLastModifierId(v string)`

SetLastModifierId sets LastModifierId field to given value.

### HasLastModifierId

`func (o *StoreProductMappingDto) HasLastModifierId() bool`

HasLastModifierId returns a boolean if a field has been set.

### SetLastModifierIdNil

`func (o *StoreProductMappingDto) SetLastModifierIdNil(b bool)`

 SetLastModifierIdNil sets the value for LastModifierId to be an explicit nil

### UnsetLastModifierId
`func (o *StoreProductMappingDto) UnsetLastModifierId()`

UnsetLastModifierId ensures that no value is present for LastModifierId, not even an explicit nil
### GetIsDeleted

`func (o *StoreProductMappingDto) GetIsDeleted() bool`

GetIsDeleted returns the IsDeleted field if non-nil, zero value otherwise.

### GetIsDeletedOk

`func (o *StoreProductMappingDto) GetIsDeletedOk() (*bool, bool)`

GetIsDeletedOk returns a tuple with the IsDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDeleted

`func (o *StoreProductMappingDto) SetIsDeleted(v bool)`

SetIsDeleted sets IsDeleted field to given value.

### HasIsDeleted

`func (o *StoreProductMappingDto) HasIsDeleted() bool`

HasIsDeleted returns a boolean if a field has been set.

### GetDeleterId

`func (o *StoreProductMappingDto) GetDeleterId() string`

GetDeleterId returns the DeleterId field if non-nil, zero value otherwise.

### GetDeleterIdOk

`func (o *StoreProductMappingDto) GetDeleterIdOk() (*string, bool)`

GetDeleterIdOk returns a tuple with the DeleterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleterId

`func (o *StoreProductMappingDto) SetDeleterId(v string)`

SetDeleterId sets DeleterId field to given value.

### HasDeleterId

`func (o *StoreProductMappingDto) HasDeleterId() bool`

HasDeleterId returns a boolean if a field has been set.

### SetDeleterIdNil

`func (o *StoreProductMappingDto) SetDeleterIdNil(b bool)`

 SetDeleterIdNil sets the value for DeleterId to be an explicit nil

### UnsetDeleterId
`func (o *StoreProductMappingDto) UnsetDeleterId()`

UnsetDeleterId ensures that no value is present for DeleterId, not even an explicit nil
### GetDeletionTime

`func (o *StoreProductMappingDto) GetDeletionTime() time.Time`

GetDeletionTime returns the DeletionTime field if non-nil, zero value otherwise.

### GetDeletionTimeOk

`func (o *StoreProductMappingDto) GetDeletionTimeOk() (*time.Time, bool)`

GetDeletionTimeOk returns a tuple with the DeletionTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletionTime

`func (o *StoreProductMappingDto) SetDeletionTime(v time.Time)`

SetDeletionTime sets DeletionTime field to given value.

### HasDeletionTime

`func (o *StoreProductMappingDto) HasDeletionTime() bool`

HasDeletionTime returns a boolean if a field has been set.

### SetDeletionTimeNil

`func (o *StoreProductMappingDto) SetDeletionTimeNil(b bool)`

 SetDeletionTimeNil sets the value for DeletionTime to be an explicit nil

### UnsetDeletionTime
`func (o *StoreProductMappingDto) UnsetDeletionTime()`

UnsetDeletionTime ensures that no value is present for DeletionTime, not even an explicit nil
### GetAppId

`func (o *StoreProductMappingDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *StoreProductMappingDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *StoreProductMappingDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *StoreProductMappingDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetPricingId

`func (o *StoreProductMappingDto) GetPricingId() string`

GetPricingId returns the PricingId field if non-nil, zero value otherwise.

### GetPricingIdOk

`func (o *StoreProductMappingDto) GetPricingIdOk() (*string, bool)`

GetPricingIdOk returns a tuple with the PricingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPricingId

`func (o *StoreProductMappingDto) SetPricingId(v string)`

SetPricingId sets PricingId field to given value.

### HasPricingId

`func (o *StoreProductMappingDto) HasPricingId() bool`

HasPricingId returns a boolean if a field has been set.

### GetPlanPriceId

`func (o *StoreProductMappingDto) GetPlanPriceId() string`

GetPlanPriceId returns the PlanPriceId field if non-nil, zero value otherwise.

### GetPlanPriceIdOk

`func (o *StoreProductMappingDto) GetPlanPriceIdOk() (*string, bool)`

GetPlanPriceIdOk returns a tuple with the PlanPriceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanPriceId

`func (o *StoreProductMappingDto) SetPlanPriceId(v string)`

SetPlanPriceId sets PlanPriceId field to given value.

### HasPlanPriceId

`func (o *StoreProductMappingDto) HasPlanPriceId() bool`

HasPlanPriceId returns a boolean if a field has been set.

### SetPlanPriceIdNil

`func (o *StoreProductMappingDto) SetPlanPriceIdNil(b bool)`

 SetPlanPriceIdNil sets the value for PlanPriceId to be an explicit nil

### UnsetPlanPriceId
`func (o *StoreProductMappingDto) UnsetPlanPriceId()`

UnsetPlanPriceId ensures that no value is present for PlanPriceId, not even an explicit nil
### GetProvider

`func (o *StoreProductMappingDto) GetProvider() BillingProvider`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *StoreProductMappingDto) GetProviderOk() (*BillingProvider, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *StoreProductMappingDto) SetProvider(v BillingProvider)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *StoreProductMappingDto) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### GetPlatform

`func (o *StoreProductMappingDto) GetPlatform() AppPlatform`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *StoreProductMappingDto) GetPlatformOk() (*AppPlatform, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *StoreProductMappingDto) SetPlatform(v AppPlatform)`

SetPlatform sets Platform field to given value.

### HasPlatform

`func (o *StoreProductMappingDto) HasPlatform() bool`

HasPlatform returns a boolean if a field has been set.

### GetPeriod

`func (o *StoreProductMappingDto) GetPeriod() SubBillingPeriod`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *StoreProductMappingDto) GetPeriodOk() (*SubBillingPeriod, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *StoreProductMappingDto) SetPeriod(v SubBillingPeriod)`

SetPeriod sets Period field to given value.

### HasPeriod

`func (o *StoreProductMappingDto) HasPeriod() bool`

HasPeriod returns a boolean if a field has been set.

### GetStoreProductId

`func (o *StoreProductMappingDto) GetStoreProductId() string`

GetStoreProductId returns the StoreProductId field if non-nil, zero value otherwise.

### GetStoreProductIdOk

`func (o *StoreProductMappingDto) GetStoreProductIdOk() (*string, bool)`

GetStoreProductIdOk returns a tuple with the StoreProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoreProductId

`func (o *StoreProductMappingDto) SetStoreProductId(v string)`

SetStoreProductId sets StoreProductId field to given value.

### HasStoreProductId

`func (o *StoreProductMappingDto) HasStoreProductId() bool`

HasStoreProductId returns a boolean if a field has been set.

### SetStoreProductIdNil

`func (o *StoreProductMappingDto) SetStoreProductIdNil(b bool)`

 SetStoreProductIdNil sets the value for StoreProductId to be an explicit nil

### UnsetStoreProductId
`func (o *StoreProductMappingDto) UnsetStoreProductId()`

UnsetStoreProductId ensures that no value is present for StoreProductId, not even an explicit nil
### GetExternalProductId

`func (o *StoreProductMappingDto) GetExternalProductId() string`

GetExternalProductId returns the ExternalProductId field if non-nil, zero value otherwise.

### GetExternalProductIdOk

`func (o *StoreProductMappingDto) GetExternalProductIdOk() (*string, bool)`

GetExternalProductIdOk returns a tuple with the ExternalProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalProductId

`func (o *StoreProductMappingDto) SetExternalProductId(v string)`

SetExternalProductId sets ExternalProductId field to given value.

### HasExternalProductId

`func (o *StoreProductMappingDto) HasExternalProductId() bool`

HasExternalProductId returns a boolean if a field has been set.

### SetExternalProductIdNil

`func (o *StoreProductMappingDto) SetExternalProductIdNil(b bool)`

 SetExternalProductIdNil sets the value for ExternalProductId to be an explicit nil

### UnsetExternalProductId
`func (o *StoreProductMappingDto) UnsetExternalProductId()`

UnsetExternalProductId ensures that no value is present for ExternalProductId, not even an explicit nil
### GetEnvironment

`func (o *StoreProductMappingDto) GetEnvironment() string`

GetEnvironment returns the Environment field if non-nil, zero value otherwise.

### GetEnvironmentOk

`func (o *StoreProductMappingDto) GetEnvironmentOk() (*string, bool)`

GetEnvironmentOk returns a tuple with the Environment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnvironment

`func (o *StoreProductMappingDto) SetEnvironment(v string)`

SetEnvironment sets Environment field to given value.

### HasEnvironment

`func (o *StoreProductMappingDto) HasEnvironment() bool`

HasEnvironment returns a boolean if a field has been set.

### SetEnvironmentNil

`func (o *StoreProductMappingDto) SetEnvironmentNil(b bool)`

 SetEnvironmentNil sets the value for Environment to be an explicit nil

### UnsetEnvironment
`func (o *StoreProductMappingDto) UnsetEnvironment()`

UnsetEnvironment ensures that no value is present for Environment, not even an explicit nil
### GetIsEnabled

`func (o *StoreProductMappingDto) GetIsEnabled() bool`

GetIsEnabled returns the IsEnabled field if non-nil, zero value otherwise.

### GetIsEnabledOk

`func (o *StoreProductMappingDto) GetIsEnabledOk() (*bool, bool)`

GetIsEnabledOk returns a tuple with the IsEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsEnabled

`func (o *StoreProductMappingDto) SetIsEnabled(v bool)`

SetIsEnabled sets IsEnabled field to given value.

### HasIsEnabled

`func (o *StoreProductMappingDto) HasIsEnabled() bool`

HasIsEnabled returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


