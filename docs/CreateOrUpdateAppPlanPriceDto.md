# CreateOrUpdateAppPlanPriceDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppId** | Pointer to **string** |  | [optional] 
**PricingId** | Pointer to **string** |  | [optional] 
**Period** | Pointer to [**SubBillingPeriod**](SubBillingPeriod.md) |  | [optional] 
**Mode** | Pointer to [**BillingMode**](BillingMode.md) |  | [optional] 
**Market** | Pointer to [**BillingMarket**](BillingMarket.md) |  | [optional] 
**Currency** | Pointer to **NullableString** |  | [optional] 
**Amount** | Pointer to **float64** |  | [optional] 
**DiscountAmount** | Pointer to **NullableFloat64** |  | [optional] 
**DurationDays** | Pointer to **NullableInt32** |  | [optional] 
**IsEnabled** | Pointer to **bool** |  | [optional] 
**SortIndex** | Pointer to **int32** |  | [optional] 
**DisplayName** | Pointer to **NullableString** |  | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCreateOrUpdateAppPlanPriceDto

`func NewCreateOrUpdateAppPlanPriceDto() *CreateOrUpdateAppPlanPriceDto`

NewCreateOrUpdateAppPlanPriceDto instantiates a new CreateOrUpdateAppPlanPriceDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrUpdateAppPlanPriceDtoWithDefaults

`func NewCreateOrUpdateAppPlanPriceDtoWithDefaults() *CreateOrUpdateAppPlanPriceDto`

NewCreateOrUpdateAppPlanPriceDtoWithDefaults instantiates a new CreateOrUpdateAppPlanPriceDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppId

`func (o *CreateOrUpdateAppPlanPriceDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *CreateOrUpdateAppPlanPriceDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *CreateOrUpdateAppPlanPriceDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *CreateOrUpdateAppPlanPriceDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetPricingId

`func (o *CreateOrUpdateAppPlanPriceDto) GetPricingId() string`

GetPricingId returns the PricingId field if non-nil, zero value otherwise.

### GetPricingIdOk

`func (o *CreateOrUpdateAppPlanPriceDto) GetPricingIdOk() (*string, bool)`

GetPricingIdOk returns a tuple with the PricingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPricingId

`func (o *CreateOrUpdateAppPlanPriceDto) SetPricingId(v string)`

SetPricingId sets PricingId field to given value.

### HasPricingId

`func (o *CreateOrUpdateAppPlanPriceDto) HasPricingId() bool`

HasPricingId returns a boolean if a field has been set.

### GetPeriod

`func (o *CreateOrUpdateAppPlanPriceDto) GetPeriod() SubBillingPeriod`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *CreateOrUpdateAppPlanPriceDto) GetPeriodOk() (*SubBillingPeriod, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *CreateOrUpdateAppPlanPriceDto) SetPeriod(v SubBillingPeriod)`

SetPeriod sets Period field to given value.

### HasPeriod

`func (o *CreateOrUpdateAppPlanPriceDto) HasPeriod() bool`

HasPeriod returns a boolean if a field has been set.

### GetMode

`func (o *CreateOrUpdateAppPlanPriceDto) GetMode() BillingMode`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *CreateOrUpdateAppPlanPriceDto) GetModeOk() (*BillingMode, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *CreateOrUpdateAppPlanPriceDto) SetMode(v BillingMode)`

SetMode sets Mode field to given value.

### HasMode

`func (o *CreateOrUpdateAppPlanPriceDto) HasMode() bool`

HasMode returns a boolean if a field has been set.

### GetMarket

`func (o *CreateOrUpdateAppPlanPriceDto) GetMarket() BillingMarket`

GetMarket returns the Market field if non-nil, zero value otherwise.

### GetMarketOk

`func (o *CreateOrUpdateAppPlanPriceDto) GetMarketOk() (*BillingMarket, bool)`

GetMarketOk returns a tuple with the Market field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarket

`func (o *CreateOrUpdateAppPlanPriceDto) SetMarket(v BillingMarket)`

SetMarket sets Market field to given value.

### HasMarket

`func (o *CreateOrUpdateAppPlanPriceDto) HasMarket() bool`

HasMarket returns a boolean if a field has been set.

### GetCurrency

`func (o *CreateOrUpdateAppPlanPriceDto) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CreateOrUpdateAppPlanPriceDto) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CreateOrUpdateAppPlanPriceDto) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *CreateOrUpdateAppPlanPriceDto) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *CreateOrUpdateAppPlanPriceDto) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *CreateOrUpdateAppPlanPriceDto) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetAmount

`func (o *CreateOrUpdateAppPlanPriceDto) GetAmount() float64`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *CreateOrUpdateAppPlanPriceDto) GetAmountOk() (*float64, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *CreateOrUpdateAppPlanPriceDto) SetAmount(v float64)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *CreateOrUpdateAppPlanPriceDto) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetDiscountAmount

`func (o *CreateOrUpdateAppPlanPriceDto) GetDiscountAmount() float64`

GetDiscountAmount returns the DiscountAmount field if non-nil, zero value otherwise.

### GetDiscountAmountOk

`func (o *CreateOrUpdateAppPlanPriceDto) GetDiscountAmountOk() (*float64, bool)`

GetDiscountAmountOk returns a tuple with the DiscountAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountAmount

`func (o *CreateOrUpdateAppPlanPriceDto) SetDiscountAmount(v float64)`

SetDiscountAmount sets DiscountAmount field to given value.

### HasDiscountAmount

`func (o *CreateOrUpdateAppPlanPriceDto) HasDiscountAmount() bool`

HasDiscountAmount returns a boolean if a field has been set.

### SetDiscountAmountNil

`func (o *CreateOrUpdateAppPlanPriceDto) SetDiscountAmountNil(b bool)`

 SetDiscountAmountNil sets the value for DiscountAmount to be an explicit nil

### UnsetDiscountAmount
`func (o *CreateOrUpdateAppPlanPriceDto) UnsetDiscountAmount()`

UnsetDiscountAmount ensures that no value is present for DiscountAmount, not even an explicit nil
### GetDurationDays

`func (o *CreateOrUpdateAppPlanPriceDto) GetDurationDays() int32`

GetDurationDays returns the DurationDays field if non-nil, zero value otherwise.

### GetDurationDaysOk

`func (o *CreateOrUpdateAppPlanPriceDto) GetDurationDaysOk() (*int32, bool)`

GetDurationDaysOk returns a tuple with the DurationDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationDays

`func (o *CreateOrUpdateAppPlanPriceDto) SetDurationDays(v int32)`

SetDurationDays sets DurationDays field to given value.

### HasDurationDays

`func (o *CreateOrUpdateAppPlanPriceDto) HasDurationDays() bool`

HasDurationDays returns a boolean if a field has been set.

### SetDurationDaysNil

`func (o *CreateOrUpdateAppPlanPriceDto) SetDurationDaysNil(b bool)`

 SetDurationDaysNil sets the value for DurationDays to be an explicit nil

### UnsetDurationDays
`func (o *CreateOrUpdateAppPlanPriceDto) UnsetDurationDays()`

UnsetDurationDays ensures that no value is present for DurationDays, not even an explicit nil
### GetIsEnabled

`func (o *CreateOrUpdateAppPlanPriceDto) GetIsEnabled() bool`

GetIsEnabled returns the IsEnabled field if non-nil, zero value otherwise.

### GetIsEnabledOk

`func (o *CreateOrUpdateAppPlanPriceDto) GetIsEnabledOk() (*bool, bool)`

GetIsEnabledOk returns a tuple with the IsEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsEnabled

`func (o *CreateOrUpdateAppPlanPriceDto) SetIsEnabled(v bool)`

SetIsEnabled sets IsEnabled field to given value.

### HasIsEnabled

`func (o *CreateOrUpdateAppPlanPriceDto) HasIsEnabled() bool`

HasIsEnabled returns a boolean if a field has been set.

### GetSortIndex

`func (o *CreateOrUpdateAppPlanPriceDto) GetSortIndex() int32`

GetSortIndex returns the SortIndex field if non-nil, zero value otherwise.

### GetSortIndexOk

`func (o *CreateOrUpdateAppPlanPriceDto) GetSortIndexOk() (*int32, bool)`

GetSortIndexOk returns a tuple with the SortIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSortIndex

`func (o *CreateOrUpdateAppPlanPriceDto) SetSortIndex(v int32)`

SetSortIndex sets SortIndex field to given value.

### HasSortIndex

`func (o *CreateOrUpdateAppPlanPriceDto) HasSortIndex() bool`

HasSortIndex returns a boolean if a field has been set.

### GetDisplayName

`func (o *CreateOrUpdateAppPlanPriceDto) GetDisplayName() string`

GetDisplayName returns the DisplayName field if non-nil, zero value otherwise.

### GetDisplayNameOk

`func (o *CreateOrUpdateAppPlanPriceDto) GetDisplayNameOk() (*string, bool)`

GetDisplayNameOk returns a tuple with the DisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayName

`func (o *CreateOrUpdateAppPlanPriceDto) SetDisplayName(v string)`

SetDisplayName sets DisplayName field to given value.

### HasDisplayName

`func (o *CreateOrUpdateAppPlanPriceDto) HasDisplayName() bool`

HasDisplayName returns a boolean if a field has been set.

### SetDisplayNameNil

`func (o *CreateOrUpdateAppPlanPriceDto) SetDisplayNameNil(b bool)`

 SetDisplayNameNil sets the value for DisplayName to be an explicit nil

### UnsetDisplayName
`func (o *CreateOrUpdateAppPlanPriceDto) UnsetDisplayName()`

UnsetDisplayName ensures that no value is present for DisplayName, not even an explicit nil
### GetDescription

`func (o *CreateOrUpdateAppPlanPriceDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreateOrUpdateAppPlanPriceDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreateOrUpdateAppPlanPriceDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreateOrUpdateAppPlanPriceDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *CreateOrUpdateAppPlanPriceDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *CreateOrUpdateAppPlanPriceDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


