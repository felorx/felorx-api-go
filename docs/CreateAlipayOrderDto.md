# CreateAlipayOrderDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppId** | Pointer to **string** | 应用 ID。 | [optional] 
**PricingId** | Pointer to **string** | 定价方案 ID。 | [optional] 
**PlanType** | Pointer to **NullableString** | 计划类型：month&#x3D;月度, year&#x3D;年度, three_year&#x3D;三年, lifetime&#x3D;终身。 | [optional] 
**CheckoutMode** | Pointer to **NullableString** | 支付入口：page&#x3D;电脑网站支付, wap&#x3D;手机网站支付, app&#x3D;App 支付订单串。 | [optional] 
**ReturnUrl** | Pointer to **NullableString** | 支付完成后的同步跳转地址。 | [optional] 
**QuitUrl** | Pointer to **NullableString** | 手机网站支付中用户取消后的返回地址。 | [optional] 

## Methods

### NewCreateAlipayOrderDto

`func NewCreateAlipayOrderDto() *CreateAlipayOrderDto`

NewCreateAlipayOrderDto instantiates a new CreateAlipayOrderDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateAlipayOrderDtoWithDefaults

`func NewCreateAlipayOrderDtoWithDefaults() *CreateAlipayOrderDto`

NewCreateAlipayOrderDtoWithDefaults instantiates a new CreateAlipayOrderDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppId

`func (o *CreateAlipayOrderDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *CreateAlipayOrderDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *CreateAlipayOrderDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *CreateAlipayOrderDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetPricingId

`func (o *CreateAlipayOrderDto) GetPricingId() string`

GetPricingId returns the PricingId field if non-nil, zero value otherwise.

### GetPricingIdOk

`func (o *CreateAlipayOrderDto) GetPricingIdOk() (*string, bool)`

GetPricingIdOk returns a tuple with the PricingId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPricingId

`func (o *CreateAlipayOrderDto) SetPricingId(v string)`

SetPricingId sets PricingId field to given value.

### HasPricingId

`func (o *CreateAlipayOrderDto) HasPricingId() bool`

HasPricingId returns a boolean if a field has been set.

### GetPlanType

`func (o *CreateAlipayOrderDto) GetPlanType() string`

GetPlanType returns the PlanType field if non-nil, zero value otherwise.

### GetPlanTypeOk

`func (o *CreateAlipayOrderDto) GetPlanTypeOk() (*string, bool)`

GetPlanTypeOk returns a tuple with the PlanType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanType

`func (o *CreateAlipayOrderDto) SetPlanType(v string)`

SetPlanType sets PlanType field to given value.

### HasPlanType

`func (o *CreateAlipayOrderDto) HasPlanType() bool`

HasPlanType returns a boolean if a field has been set.

### SetPlanTypeNil

`func (o *CreateAlipayOrderDto) SetPlanTypeNil(b bool)`

 SetPlanTypeNil sets the value for PlanType to be an explicit nil

### UnsetPlanType
`func (o *CreateAlipayOrderDto) UnsetPlanType()`

UnsetPlanType ensures that no value is present for PlanType, not even an explicit nil
### GetCheckoutMode

`func (o *CreateAlipayOrderDto) GetCheckoutMode() string`

GetCheckoutMode returns the CheckoutMode field if non-nil, zero value otherwise.

### GetCheckoutModeOk

`func (o *CreateAlipayOrderDto) GetCheckoutModeOk() (*string, bool)`

GetCheckoutModeOk returns a tuple with the CheckoutMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckoutMode

`func (o *CreateAlipayOrderDto) SetCheckoutMode(v string)`

SetCheckoutMode sets CheckoutMode field to given value.

### HasCheckoutMode

`func (o *CreateAlipayOrderDto) HasCheckoutMode() bool`

HasCheckoutMode returns a boolean if a field has been set.

### SetCheckoutModeNil

`func (o *CreateAlipayOrderDto) SetCheckoutModeNil(b bool)`

 SetCheckoutModeNil sets the value for CheckoutMode to be an explicit nil

### UnsetCheckoutMode
`func (o *CreateAlipayOrderDto) UnsetCheckoutMode()`

UnsetCheckoutMode ensures that no value is present for CheckoutMode, not even an explicit nil
### GetReturnUrl

`func (o *CreateAlipayOrderDto) GetReturnUrl() string`

GetReturnUrl returns the ReturnUrl field if non-nil, zero value otherwise.

### GetReturnUrlOk

`func (o *CreateAlipayOrderDto) GetReturnUrlOk() (*string, bool)`

GetReturnUrlOk returns a tuple with the ReturnUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnUrl

`func (o *CreateAlipayOrderDto) SetReturnUrl(v string)`

SetReturnUrl sets ReturnUrl field to given value.

### HasReturnUrl

`func (o *CreateAlipayOrderDto) HasReturnUrl() bool`

HasReturnUrl returns a boolean if a field has been set.

### SetReturnUrlNil

`func (o *CreateAlipayOrderDto) SetReturnUrlNil(b bool)`

 SetReturnUrlNil sets the value for ReturnUrl to be an explicit nil

### UnsetReturnUrl
`func (o *CreateAlipayOrderDto) UnsetReturnUrl()`

UnsetReturnUrl ensures that no value is present for ReturnUrl, not even an explicit nil
### GetQuitUrl

`func (o *CreateAlipayOrderDto) GetQuitUrl() string`

GetQuitUrl returns the QuitUrl field if non-nil, zero value otherwise.

### GetQuitUrlOk

`func (o *CreateAlipayOrderDto) GetQuitUrlOk() (*string, bool)`

GetQuitUrlOk returns a tuple with the QuitUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuitUrl

`func (o *CreateAlipayOrderDto) SetQuitUrl(v string)`

SetQuitUrl sets QuitUrl field to given value.

### HasQuitUrl

`func (o *CreateAlipayOrderDto) HasQuitUrl() bool`

HasQuitUrl returns a boolean if a field has been set.

### SetQuitUrlNil

`func (o *CreateAlipayOrderDto) SetQuitUrlNil(b bool)`

 SetQuitUrlNil sets the value for QuitUrl to be an explicit nil

### UnsetQuitUrl
`func (o *CreateAlipayOrderDto) UnsetQuitUrl()`

UnsetQuitUrl ensures that no value is present for QuitUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


