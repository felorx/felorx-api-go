# CreatePayPalOrderDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppId** | Pointer to **string** | 应用 ID | [optional] 
**PricingId** | Pointer to **string** | 定价方案 ID | [optional] 
**PlanType** | Pointer to **NullableString** | 计划类型：month&#x3D;月度, year&#x3D;年度, three_year&#x3D;三年, lifetime&#x3D;终身 | [optional] 
**ReturnUrl** | Pointer to **NullableString** | 支付完成后返回地址，桌面端可传深链。 | [optional] 
**CancelUrl** | Pointer to **NullableString** | 支付取消后返回地址，桌面端可传深链。 | [optional] 

## Methods

### NewCreatePayPalOrderDto

`func NewCreatePayPalOrderDto() *CreatePayPalOrderDto`

NewCreatePayPalOrderDto instantiates a new CreatePayPalOrderDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreatePayPalOrderDtoWithDefaults

`func NewCreatePayPalOrderDtoWithDefaults() *CreatePayPalOrderDto`

NewCreatePayPalOrderDtoWithDefaults instantiates a new CreatePayPalOrderDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppId

`func (o *CreatePayPalOrderDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *CreatePayPalOrderDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *CreatePayPalOrderDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *CreatePayPalOrderDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetPricingId

`func (o *CreatePayPalOrderDto) GetPricingId() string`

GetPricingId returns the PricingId field if non-nil, zero value otherwise.

### GetPricingIdOk

`func (o *CreatePayPalOrderDto) GetPricingIdOk() (*string, bool)`

GetPricingIdOk returns a tuple with the PricingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPricingId

`func (o *CreatePayPalOrderDto) SetPricingId(v string)`

SetPricingId sets PricingId field to given value.

### HasPricingId

`func (o *CreatePayPalOrderDto) HasPricingId() bool`

HasPricingId returns a boolean if a field has been set.

### GetPlanType

`func (o *CreatePayPalOrderDto) GetPlanType() string`

GetPlanType returns the PlanType field if non-nil, zero value otherwise.

### GetPlanTypeOk

`func (o *CreatePayPalOrderDto) GetPlanTypeOk() (*string, bool)`

GetPlanTypeOk returns a tuple with the PlanType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanType

`func (o *CreatePayPalOrderDto) SetPlanType(v string)`

SetPlanType sets PlanType field to given value.

### HasPlanType

`func (o *CreatePayPalOrderDto) HasPlanType() bool`

HasPlanType returns a boolean if a field has been set.

### SetPlanTypeNil

`func (o *CreatePayPalOrderDto) SetPlanTypeNil(b bool)`

 SetPlanTypeNil sets the value for PlanType to be an explicit nil

### UnsetPlanType
`func (o *CreatePayPalOrderDto) UnsetPlanType()`

UnsetPlanType ensures that no value is present for PlanType, not even an explicit nil
### GetReturnUrl

`func (o *CreatePayPalOrderDto) GetReturnUrl() string`

GetReturnUrl returns the ReturnUrl field if non-nil, zero value otherwise.

### GetReturnUrlOk

`func (o *CreatePayPalOrderDto) GetReturnUrlOk() (*string, bool)`

GetReturnUrlOk returns a tuple with the ReturnUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnUrl

`func (o *CreatePayPalOrderDto) SetReturnUrl(v string)`

SetReturnUrl sets ReturnUrl field to given value.

### HasReturnUrl

`func (o *CreatePayPalOrderDto) HasReturnUrl() bool`

HasReturnUrl returns a boolean if a field has been set.

### SetReturnUrlNil

`func (o *CreatePayPalOrderDto) SetReturnUrlNil(b bool)`

 SetReturnUrlNil sets the value for ReturnUrl to be an explicit nil

### UnsetReturnUrl
`func (o *CreatePayPalOrderDto) UnsetReturnUrl()`

UnsetReturnUrl ensures that no value is present for ReturnUrl, not even an explicit nil
### GetCancelUrl

`func (o *CreatePayPalOrderDto) GetCancelUrl() string`

GetCancelUrl returns the CancelUrl field if non-nil, zero value otherwise.

### GetCancelUrlOk

`func (o *CreatePayPalOrderDto) GetCancelUrlOk() (*string, bool)`

GetCancelUrlOk returns a tuple with the CancelUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancelUrl

`func (o *CreatePayPalOrderDto) SetCancelUrl(v string)`

SetCancelUrl sets CancelUrl field to given value.

### HasCancelUrl

`func (o *CreatePayPalOrderDto) HasCancelUrl() bool`

HasCancelUrl returns a boolean if a field has been set.

### SetCancelUrlNil

`func (o *CreatePayPalOrderDto) SetCancelUrlNil(b bool)`

 SetCancelUrlNil sets the value for CancelUrl to be an explicit nil

### UnsetCancelUrl
`func (o *CreatePayPalOrderDto) UnsetCancelUrl()`

UnsetCancelUrl ensures that no value is present for CancelUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


