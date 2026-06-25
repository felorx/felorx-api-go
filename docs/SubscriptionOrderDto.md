# SubscriptionOrderDto

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
**Type** | Pointer to [**SubscriptionOrderType**](SubscriptionOrderType.md) |  | [optional]
**Status** | Pointer to [**SubscriptionOrderStatus**](SubscriptionOrderStatus.md) |  | [optional]
**AppId** | Pointer to **string** |  | [optional]
**PricingId** | Pointer to **string** |  | [optional]
**PlanPriceId** | Pointer to **NullableString** |  | [optional]
**ProductId** | Pointer to **NullableString** |  | [optional]
**Provider** | Pointer to [**BillingProvider**](BillingProvider.md) |  | [optional]
**BillingPeriod** | Pointer to [**SubBillingPeriod**](SubBillingPeriod.md) |  | [optional]
**BillingMode** | Pointer to [**BillingMode**](BillingMode.md) |  | [optional]
**Amount** | Pointer to **float64** |  | [optional]
**Currency** | Pointer to **NullableString** |  | [optional]
**ApprovalUrl** | Pointer to **NullableString** |  | [optional]

## Methods

### NewSubscriptionOrderDto

`func NewSubscriptionOrderDto() *SubscriptionOrderDto`

NewSubscriptionOrderDto instantiates a new SubscriptionOrderDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubscriptionOrderDtoWithDefaults

`func NewSubscriptionOrderDtoWithDefaults() *SubscriptionOrderDto`

NewSubscriptionOrderDtoWithDefaults instantiates a new SubscriptionOrderDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SubscriptionOrderDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SubscriptionOrderDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SubscriptionOrderDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SubscriptionOrderDto) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreationTime

`func (o *SubscriptionOrderDto) GetCreationTime() time.Time`

GetCreationTime returns the CreationTime field if non-nil, zero value otherwise.

### GetCreationTimeOk

`func (o *SubscriptionOrderDto) GetCreationTimeOk() (*time.Time, bool)`

GetCreationTimeOk returns a tuple with the CreationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreationTime

`func (o *SubscriptionOrderDto) SetCreationTime(v time.Time)`

SetCreationTime sets CreationTime field to given value.

### HasCreationTime

`func (o *SubscriptionOrderDto) HasCreationTime() bool`

HasCreationTime returns a boolean if a field has been set.

### GetCreatorId

`func (o *SubscriptionOrderDto) GetCreatorId() string`

GetCreatorId returns the CreatorId field if non-nil, zero value otherwise.

### GetCreatorIdOk

`func (o *SubscriptionOrderDto) GetCreatorIdOk() (*string, bool)`

GetCreatorIdOk returns a tuple with the CreatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatorId

`func (o *SubscriptionOrderDto) SetCreatorId(v string)`

SetCreatorId sets CreatorId field to given value.

### HasCreatorId

`func (o *SubscriptionOrderDto) HasCreatorId() bool`

HasCreatorId returns a boolean if a field has been set.

### SetCreatorIdNil

`func (o *SubscriptionOrderDto) SetCreatorIdNil(b bool)`

 SetCreatorIdNil sets the value for CreatorId to be an explicit nil

### UnsetCreatorId
`func (o *SubscriptionOrderDto) UnsetCreatorId()`

UnsetCreatorId ensures that no value is present for CreatorId, not even an explicit nil
### GetLastModificationTime

`func (o *SubscriptionOrderDto) GetLastModificationTime() time.Time`

GetLastModificationTime returns the LastModificationTime field if non-nil, zero value otherwise.

### GetLastModificationTimeOk

`func (o *SubscriptionOrderDto) GetLastModificationTimeOk() (*time.Time, bool)`

GetLastModificationTimeOk returns a tuple with the LastModificationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModificationTime

`func (o *SubscriptionOrderDto) SetLastModificationTime(v time.Time)`

SetLastModificationTime sets LastModificationTime field to given value.

### HasLastModificationTime

`func (o *SubscriptionOrderDto) HasLastModificationTime() bool`

HasLastModificationTime returns a boolean if a field has been set.

### SetLastModificationTimeNil

`func (o *SubscriptionOrderDto) SetLastModificationTimeNil(b bool)`

 SetLastModificationTimeNil sets the value for LastModificationTime to be an explicit nil

### UnsetLastModificationTime
`func (o *SubscriptionOrderDto) UnsetLastModificationTime()`

UnsetLastModificationTime ensures that no value is present for LastModificationTime, not even an explicit nil
### GetLastModifierId

`func (o *SubscriptionOrderDto) GetLastModifierId() string`

GetLastModifierId returns the LastModifierId field if non-nil, zero value otherwise.

### GetLastModifierIdOk

`func (o *SubscriptionOrderDto) GetLastModifierIdOk() (*string, bool)`

GetLastModifierIdOk returns a tuple with the LastModifierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModifierId

`func (o *SubscriptionOrderDto) SetLastModifierId(v string)`

SetLastModifierId sets LastModifierId field to given value.

### HasLastModifierId

`func (o *SubscriptionOrderDto) HasLastModifierId() bool`

HasLastModifierId returns a boolean if a field has been set.

### SetLastModifierIdNil

`func (o *SubscriptionOrderDto) SetLastModifierIdNil(b bool)`

 SetLastModifierIdNil sets the value for LastModifierId to be an explicit nil

### UnsetLastModifierId
`func (o *SubscriptionOrderDto) UnsetLastModifierId()`

UnsetLastModifierId ensures that no value is present for LastModifierId, not even an explicit nil
### GetIsDeleted

`func (o *SubscriptionOrderDto) GetIsDeleted() bool`

GetIsDeleted returns the IsDeleted field if non-nil, zero value otherwise.

### GetIsDeletedOk

`func (o *SubscriptionOrderDto) GetIsDeletedOk() (*bool, bool)`

GetIsDeletedOk returns a tuple with the IsDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDeleted

`func (o *SubscriptionOrderDto) SetIsDeleted(v bool)`

SetIsDeleted sets IsDeleted field to given value.

### HasIsDeleted

`func (o *SubscriptionOrderDto) HasIsDeleted() bool`

HasIsDeleted returns a boolean if a field has been set.

### GetDeleterId

`func (o *SubscriptionOrderDto) GetDeleterId() string`

GetDeleterId returns the DeleterId field if non-nil, zero value otherwise.

### GetDeleterIdOk

`func (o *SubscriptionOrderDto) GetDeleterIdOk() (*string, bool)`

GetDeleterIdOk returns a tuple with the DeleterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleterId

`func (o *SubscriptionOrderDto) SetDeleterId(v string)`

SetDeleterId sets DeleterId field to given value.

### HasDeleterId

`func (o *SubscriptionOrderDto) HasDeleterId() bool`

HasDeleterId returns a boolean if a field has been set.

### SetDeleterIdNil

`func (o *SubscriptionOrderDto) SetDeleterIdNil(b bool)`

 SetDeleterIdNil sets the value for DeleterId to be an explicit nil

### UnsetDeleterId
`func (o *SubscriptionOrderDto) UnsetDeleterId()`

UnsetDeleterId ensures that no value is present for DeleterId, not even an explicit nil
### GetDeletionTime

`func (o *SubscriptionOrderDto) GetDeletionTime() time.Time`

GetDeletionTime returns the DeletionTime field if non-nil, zero value otherwise.

### GetDeletionTimeOk

`func (o *SubscriptionOrderDto) GetDeletionTimeOk() (*time.Time, bool)`

GetDeletionTimeOk returns a tuple with the DeletionTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletionTime

`func (o *SubscriptionOrderDto) SetDeletionTime(v time.Time)`

SetDeletionTime sets DeletionTime field to given value.

### HasDeletionTime

`func (o *SubscriptionOrderDto) HasDeletionTime() bool`

HasDeletionTime returns a boolean if a field has been set.

### SetDeletionTimeNil

`func (o *SubscriptionOrderDto) SetDeletionTimeNil(b bool)`

 SetDeletionTimeNil sets the value for DeletionTime to be an explicit nil

### UnsetDeletionTime
`func (o *SubscriptionOrderDto) UnsetDeletionTime()`

UnsetDeletionTime ensures that no value is present for DeletionTime, not even an explicit nil
### GetType

`func (o *SubscriptionOrderDto) GetType() SubscriptionOrderType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SubscriptionOrderDto) GetTypeOk() (*SubscriptionOrderType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SubscriptionOrderDto) SetType(v SubscriptionOrderType)`

SetType sets Type field to given value.

### HasType

`func (o *SubscriptionOrderDto) HasType() bool`

HasType returns a boolean if a field has been set.

### GetStatus

`func (o *SubscriptionOrderDto) GetStatus() SubscriptionOrderStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SubscriptionOrderDto) GetStatusOk() (*SubscriptionOrderStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SubscriptionOrderDto) SetStatus(v SubscriptionOrderStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SubscriptionOrderDto) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetAppId

`func (o *SubscriptionOrderDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *SubscriptionOrderDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *SubscriptionOrderDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *SubscriptionOrderDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetPricingId

`func (o *SubscriptionOrderDto) GetPricingId() string`

GetPricingId returns the PricingId field if non-nil, zero value otherwise.

### GetPricingIdOk

`func (o *SubscriptionOrderDto) GetPricingIdOk() (*string, bool)`

GetPricingIdOk returns a tuple with the PricingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPricingId

`func (o *SubscriptionOrderDto) SetPricingId(v string)`

SetPricingId sets PricingId field to given value.

### HasPricingId

`func (o *SubscriptionOrderDto) HasPricingId() bool`

HasPricingId returns a boolean if a field has been set.

### GetPlanPriceId

`func (o *SubscriptionOrderDto) GetPlanPriceId() string`

GetPlanPriceId returns the PlanPriceId field if non-nil, zero value otherwise.

### GetPlanPriceIdOk

`func (o *SubscriptionOrderDto) GetPlanPriceIdOk() (*string, bool)`

GetPlanPriceIdOk returns a tuple with the PlanPriceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanPriceId

`func (o *SubscriptionOrderDto) SetPlanPriceId(v string)`

SetPlanPriceId sets PlanPriceId field to given value.

### HasPlanPriceId

`func (o *SubscriptionOrderDto) HasPlanPriceId() bool`

HasPlanPriceId returns a boolean if a field has been set.

### SetPlanPriceIdNil

`func (o *SubscriptionOrderDto) SetPlanPriceIdNil(b bool)`

 SetPlanPriceIdNil sets the value for PlanPriceId to be an explicit nil

### UnsetPlanPriceId
`func (o *SubscriptionOrderDto) UnsetPlanPriceId()`

UnsetPlanPriceId ensures that no value is present for PlanPriceId, not even an explicit nil
### GetProductId

`func (o *SubscriptionOrderDto) GetProductId() string`

GetProductId returns the ProductId field if non-nil, zero value otherwise.

### GetProductIdOk

`func (o *SubscriptionOrderDto) GetProductIdOk() (*string, bool)`

GetProductIdOk returns a tuple with the ProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductId

`func (o *SubscriptionOrderDto) SetProductId(v string)`

SetProductId sets ProductId field to given value.

### HasProductId

`func (o *SubscriptionOrderDto) HasProductId() bool`

HasProductId returns a boolean if a field has been set.

### SetProductIdNil

`func (o *SubscriptionOrderDto) SetProductIdNil(b bool)`

 SetProductIdNil sets the value for ProductId to be an explicit nil

### UnsetProductId
`func (o *SubscriptionOrderDto) UnsetProductId()`

UnsetProductId ensures that no value is present for ProductId, not even an explicit nil
### GetProvider

`func (o *SubscriptionOrderDto) GetProvider() BillingProvider`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *SubscriptionOrderDto) GetProviderOk() (*BillingProvider, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *SubscriptionOrderDto) SetProvider(v BillingProvider)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *SubscriptionOrderDto) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### GetBillingPeriod

`func (o *SubscriptionOrderDto) GetBillingPeriod() SubBillingPeriod`

GetBillingPeriod returns the BillingPeriod field if non-nil, zero value otherwise.

### GetBillingPeriodOk

`func (o *SubscriptionOrderDto) GetBillingPeriodOk() (*SubBillingPeriod, bool)`

GetBillingPeriodOk returns a tuple with the BillingPeriod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingPeriod

`func (o *SubscriptionOrderDto) SetBillingPeriod(v SubBillingPeriod)`

SetBillingPeriod sets BillingPeriod field to given value.

### HasBillingPeriod

`func (o *SubscriptionOrderDto) HasBillingPeriod() bool`

HasBillingPeriod returns a boolean if a field has been set.

### GetBillingMode

`func (o *SubscriptionOrderDto) GetBillingMode() BillingMode`

GetBillingMode returns the BillingMode field if non-nil, zero value otherwise.

### GetBillingModeOk

`func (o *SubscriptionOrderDto) GetBillingModeOk() (*BillingMode, bool)`

GetBillingModeOk returns a tuple with the BillingMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingMode

`func (o *SubscriptionOrderDto) SetBillingMode(v BillingMode)`

SetBillingMode sets BillingMode field to given value.

### HasBillingMode

`func (o *SubscriptionOrderDto) HasBillingMode() bool`

HasBillingMode returns a boolean if a field has been set.

### GetAmount

`func (o *SubscriptionOrderDto) GetAmount() float64`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *SubscriptionOrderDto) GetAmountOk() (*float64, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *SubscriptionOrderDto) SetAmount(v float64)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *SubscriptionOrderDto) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetCurrency

`func (o *SubscriptionOrderDto) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *SubscriptionOrderDto) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *SubscriptionOrderDto) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *SubscriptionOrderDto) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *SubscriptionOrderDto) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *SubscriptionOrderDto) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetApprovalUrl

`func (o *SubscriptionOrderDto) GetApprovalUrl() string`

GetApprovalUrl returns the ApprovalUrl field if non-nil, zero value otherwise.

### GetApprovalUrlOk

`func (o *SubscriptionOrderDto) GetApprovalUrlOk() (*string, bool)`

GetApprovalUrlOk returns a tuple with the ApprovalUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovalUrl

`func (o *SubscriptionOrderDto) SetApprovalUrl(v string)`

SetApprovalUrl sets ApprovalUrl field to given value.

### HasApprovalUrl

`func (o *SubscriptionOrderDto) HasApprovalUrl() bool`

HasApprovalUrl returns a boolean if a field has been set.

### SetApprovalUrlNil

`func (o *SubscriptionOrderDto) SetApprovalUrlNil(b bool)`

 SetApprovalUrlNil sets the value for ApprovalUrl to be an explicit nil

### UnsetApprovalUrl
`func (o *SubscriptionOrderDto) UnsetApprovalUrl()`

UnsetApprovalUrl ensures that no value is present for ApprovalUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


