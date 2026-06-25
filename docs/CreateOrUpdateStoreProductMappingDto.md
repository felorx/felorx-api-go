# CreateOrUpdateStoreProductMappingDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **NullableString** |  | [optional]
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

### NewCreateOrUpdateStoreProductMappingDto

`func NewCreateOrUpdateStoreProductMappingDto() *CreateOrUpdateStoreProductMappingDto`

NewCreateOrUpdateStoreProductMappingDto instantiates a new CreateOrUpdateStoreProductMappingDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrUpdateStoreProductMappingDtoWithDefaults

`func NewCreateOrUpdateStoreProductMappingDtoWithDefaults() *CreateOrUpdateStoreProductMappingDto`

NewCreateOrUpdateStoreProductMappingDtoWithDefaults instantiates a new CreateOrUpdateStoreProductMappingDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateOrUpdateStoreProductMappingDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateOrUpdateStoreProductMappingDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateOrUpdateStoreProductMappingDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CreateOrUpdateStoreProductMappingDto) HasId() bool`

HasId returns a boolean if a field has been set.

### SetIdNil

`func (o *CreateOrUpdateStoreProductMappingDto) SetIdNil(b bool)`

 SetIdNil sets the value for Id to be an explicit nil

### UnsetId
`func (o *CreateOrUpdateStoreProductMappingDto) UnsetId()`

UnsetId ensures that no value is present for Id, not even an explicit nil
### GetAppId

`func (o *CreateOrUpdateStoreProductMappingDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *CreateOrUpdateStoreProductMappingDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *CreateOrUpdateStoreProductMappingDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *CreateOrUpdateStoreProductMappingDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetPricingId

`func (o *CreateOrUpdateStoreProductMappingDto) GetPricingId() string`

GetPricingId returns the PricingId field if non-nil, zero value otherwise.

### GetPricingIdOk

`func (o *CreateOrUpdateStoreProductMappingDto) GetPricingIdOk() (*string, bool)`

GetPricingIdOk returns a tuple with the PricingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPricingId

`func (o *CreateOrUpdateStoreProductMappingDto) SetPricingId(v string)`

SetPricingId sets PricingId field to given value.

### HasPricingId

`func (o *CreateOrUpdateStoreProductMappingDto) HasPricingId() bool`

HasPricingId returns a boolean if a field has been set.

### GetPlanPriceId

`func (o *CreateOrUpdateStoreProductMappingDto) GetPlanPriceId() string`

GetPlanPriceId returns the PlanPriceId field if non-nil, zero value otherwise.

### GetPlanPriceIdOk

`func (o *CreateOrUpdateStoreProductMappingDto) GetPlanPriceIdOk() (*string, bool)`

GetPlanPriceIdOk returns a tuple with the PlanPriceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanPriceId

`func (o *CreateOrUpdateStoreProductMappingDto) SetPlanPriceId(v string)`

SetPlanPriceId sets PlanPriceId field to given value.

### HasPlanPriceId

`func (o *CreateOrUpdateStoreProductMappingDto) HasPlanPriceId() bool`

HasPlanPriceId returns a boolean if a field has been set.

### SetPlanPriceIdNil

`func (o *CreateOrUpdateStoreProductMappingDto) SetPlanPriceIdNil(b bool)`

 SetPlanPriceIdNil sets the value for PlanPriceId to be an explicit nil

### UnsetPlanPriceId
`func (o *CreateOrUpdateStoreProductMappingDto) UnsetPlanPriceId()`

UnsetPlanPriceId ensures that no value is present for PlanPriceId, not even an explicit nil
### GetProvider

`func (o *CreateOrUpdateStoreProductMappingDto) GetProvider() BillingProvider`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *CreateOrUpdateStoreProductMappingDto) GetProviderOk() (*BillingProvider, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *CreateOrUpdateStoreProductMappingDto) SetProvider(v BillingProvider)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *CreateOrUpdateStoreProductMappingDto) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### GetPlatform

`func (o *CreateOrUpdateStoreProductMappingDto) GetPlatform() AppPlatform`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *CreateOrUpdateStoreProductMappingDto) GetPlatformOk() (*AppPlatform, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *CreateOrUpdateStoreProductMappingDto) SetPlatform(v AppPlatform)`

SetPlatform sets Platform field to given value.

### HasPlatform

`func (o *CreateOrUpdateStoreProductMappingDto) HasPlatform() bool`

HasPlatform returns a boolean if a field has been set.

### GetPeriod

`func (o *CreateOrUpdateStoreProductMappingDto) GetPeriod() SubBillingPeriod`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *CreateOrUpdateStoreProductMappingDto) GetPeriodOk() (*SubBillingPeriod, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *CreateOrUpdateStoreProductMappingDto) SetPeriod(v SubBillingPeriod)`

SetPeriod sets Period field to given value.

### HasPeriod

`func (o *CreateOrUpdateStoreProductMappingDto) HasPeriod() bool`

HasPeriod returns a boolean if a field has been set.

### GetStoreProductId

`func (o *CreateOrUpdateStoreProductMappingDto) GetStoreProductId() string`

GetStoreProductId returns the StoreProductId field if non-nil, zero value otherwise.

### GetStoreProductIdOk

`func (o *CreateOrUpdateStoreProductMappingDto) GetStoreProductIdOk() (*string, bool)`

GetStoreProductIdOk returns a tuple with the StoreProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoreProductId

`func (o *CreateOrUpdateStoreProductMappingDto) SetStoreProductId(v string)`

SetStoreProductId sets StoreProductId field to given value.

### HasStoreProductId

`func (o *CreateOrUpdateStoreProductMappingDto) HasStoreProductId() bool`

HasStoreProductId returns a boolean if a field has been set.

### SetStoreProductIdNil

`func (o *CreateOrUpdateStoreProductMappingDto) SetStoreProductIdNil(b bool)`

 SetStoreProductIdNil sets the value for StoreProductId to be an explicit nil

### UnsetStoreProductId
`func (o *CreateOrUpdateStoreProductMappingDto) UnsetStoreProductId()`

UnsetStoreProductId ensures that no value is present for StoreProductId, not even an explicit nil
### GetExternalProductId

`func (o *CreateOrUpdateStoreProductMappingDto) GetExternalProductId() string`

GetExternalProductId returns the ExternalProductId field if non-nil, zero value otherwise.

### GetExternalProductIdOk

`func (o *CreateOrUpdateStoreProductMappingDto) GetExternalProductIdOk() (*string, bool)`

GetExternalProductIdOk returns a tuple with the ExternalProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalProductId

`func (o *CreateOrUpdateStoreProductMappingDto) SetExternalProductId(v string)`

SetExternalProductId sets ExternalProductId field to given value.

### HasExternalProductId

`func (o *CreateOrUpdateStoreProductMappingDto) HasExternalProductId() bool`

HasExternalProductId returns a boolean if a field has been set.

### SetExternalProductIdNil

`func (o *CreateOrUpdateStoreProductMappingDto) SetExternalProductIdNil(b bool)`

 SetExternalProductIdNil sets the value for ExternalProductId to be an explicit nil

### UnsetExternalProductId
`func (o *CreateOrUpdateStoreProductMappingDto) UnsetExternalProductId()`

UnsetExternalProductId ensures that no value is present for ExternalProductId, not even an explicit nil
### GetEnvironment

`func (o *CreateOrUpdateStoreProductMappingDto) GetEnvironment() string`

GetEnvironment returns the Environment field if non-nil, zero value otherwise.

### GetEnvironmentOk

`func (o *CreateOrUpdateStoreProductMappingDto) GetEnvironmentOk() (*string, bool)`

GetEnvironmentOk returns a tuple with the Environment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnvironment

`func (o *CreateOrUpdateStoreProductMappingDto) SetEnvironment(v string)`

SetEnvironment sets Environment field to given value.

### HasEnvironment

`func (o *CreateOrUpdateStoreProductMappingDto) HasEnvironment() bool`

HasEnvironment returns a boolean if a field has been set.

### SetEnvironmentNil

`func (o *CreateOrUpdateStoreProductMappingDto) SetEnvironmentNil(b bool)`

 SetEnvironmentNil sets the value for Environment to be an explicit nil

### UnsetEnvironment
`func (o *CreateOrUpdateStoreProductMappingDto) UnsetEnvironment()`

UnsetEnvironment ensures that no value is present for Environment, not even an explicit nil
### GetIsEnabled

`func (o *CreateOrUpdateStoreProductMappingDto) GetIsEnabled() bool`

GetIsEnabled returns the IsEnabled field if non-nil, zero value otherwise.

### GetIsEnabledOk

`func (o *CreateOrUpdateStoreProductMappingDto) GetIsEnabledOk() (*bool, bool)`

GetIsEnabledOk returns a tuple with the IsEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsEnabled

`func (o *CreateOrUpdateStoreProductMappingDto) SetIsEnabled(v bool)`

SetIsEnabled sets IsEnabled field to given value.

### HasIsEnabled

`func (o *CreateOrUpdateStoreProductMappingDto) HasIsEnabled() bool`

HasIsEnabled returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


