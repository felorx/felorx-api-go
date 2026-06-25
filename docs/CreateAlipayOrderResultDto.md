# CreateAlipayOrderResultDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrderId** | Pointer to **string** | 本系统订单 ID。 | [optional]
**OutTradeNo** | Pointer to **NullableString** | 支付宝商户订单号 out_trade_no。 | [optional]
**CheckoutMode** | Pointer to **NullableString** | 支付入口：page、wap 或 app。 | [optional]
**PaymentForm** | Pointer to **NullableString** | 电脑/手机网站支付的 HTML 表单，可由 Web 前端写入页面并提交。 | [optional]
**PaymentUrl** | Pointer to **NullableString** | 从支付表单中提取出的跳转地址。桌面和 Android 可用外部浏览器打开。 | [optional]
**OrderString** | Pointer to **NullableString** | App 支付订单串，原生客户端接支付宝 App SDK 时使用。 | [optional]

## Methods

### NewCreateAlipayOrderResultDto

`func NewCreateAlipayOrderResultDto() *CreateAlipayOrderResultDto`

NewCreateAlipayOrderResultDto instantiates a new CreateAlipayOrderResultDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateAlipayOrderResultDtoWithDefaults

`func NewCreateAlipayOrderResultDtoWithDefaults() *CreateAlipayOrderResultDto`

NewCreateAlipayOrderResultDtoWithDefaults instantiates a new CreateAlipayOrderResultDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrderId

`func (o *CreateAlipayOrderResultDto) GetOrderId() string`

GetOrderId returns the OrderId field if non-nil, zero value otherwise.

### GetOrderIdOk

`func (o *CreateAlipayOrderResultDto) GetOrderIdOk() (*string, bool)`

GetOrderIdOk returns a tuple with the OrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderId

`func (o *CreateAlipayOrderResultDto) SetOrderId(v string)`

SetOrderId sets OrderId field to given value.

### HasOrderId

`func (o *CreateAlipayOrderResultDto) HasOrderId() bool`

HasOrderId returns a boolean if a field has been set.

### GetOutTradeNo

`func (o *CreateAlipayOrderResultDto) GetOutTradeNo() string`

GetOutTradeNo returns the OutTradeNo field if non-nil, zero value otherwise.

### GetOutTradeNoOk

`func (o *CreateAlipayOrderResultDto) GetOutTradeNoOk() (*string, bool)`

GetOutTradeNoOk returns a tuple with the OutTradeNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutTradeNo

`func (o *CreateAlipayOrderResultDto) SetOutTradeNo(v string)`

SetOutTradeNo sets OutTradeNo field to given value.

### HasOutTradeNo

`func (o *CreateAlipayOrderResultDto) HasOutTradeNo() bool`

HasOutTradeNo returns a boolean if a field has been set.

### SetOutTradeNoNil

`func (o *CreateAlipayOrderResultDto) SetOutTradeNoNil(b bool)`

 SetOutTradeNoNil sets the value for OutTradeNo to be an explicit nil

### UnsetOutTradeNo
`func (o *CreateAlipayOrderResultDto) UnsetOutTradeNo()`

UnsetOutTradeNo ensures that no value is present for OutTradeNo, not even an explicit nil
### GetCheckoutMode

`func (o *CreateAlipayOrderResultDto) GetCheckoutMode() string`

GetCheckoutMode returns the CheckoutMode field if non-nil, zero value otherwise.

### GetCheckoutModeOk

`func (o *CreateAlipayOrderResultDto) GetCheckoutModeOk() (*string, bool)`

GetCheckoutModeOk returns a tuple with the CheckoutMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckoutMode

`func (o *CreateAlipayOrderResultDto) SetCheckoutMode(v string)`

SetCheckoutMode sets CheckoutMode field to given value.

### HasCheckoutMode

`func (o *CreateAlipayOrderResultDto) HasCheckoutMode() bool`

HasCheckoutMode returns a boolean if a field has been set.

### SetCheckoutModeNil

`func (o *CreateAlipayOrderResultDto) SetCheckoutModeNil(b bool)`

 SetCheckoutModeNil sets the value for CheckoutMode to be an explicit nil

### UnsetCheckoutMode
`func (o *CreateAlipayOrderResultDto) UnsetCheckoutMode()`

UnsetCheckoutMode ensures that no value is present for CheckoutMode, not even an explicit nil
### GetPaymentForm

`func (o *CreateAlipayOrderResultDto) GetPaymentForm() string`

GetPaymentForm returns the PaymentForm field if non-nil, zero value otherwise.

### GetPaymentFormOk

`func (o *CreateAlipayOrderResultDto) GetPaymentFormOk() (*string, bool)`

GetPaymentFormOk returns a tuple with the PaymentForm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentForm

`func (o *CreateAlipayOrderResultDto) SetPaymentForm(v string)`

SetPaymentForm sets PaymentForm field to given value.

### HasPaymentForm

`func (o *CreateAlipayOrderResultDto) HasPaymentForm() bool`

HasPaymentForm returns a boolean if a field has been set.

### SetPaymentFormNil

`func (o *CreateAlipayOrderResultDto) SetPaymentFormNil(b bool)`

 SetPaymentFormNil sets the value for PaymentForm to be an explicit nil

### UnsetPaymentForm
`func (o *CreateAlipayOrderResultDto) UnsetPaymentForm()`

UnsetPaymentForm ensures that no value is present for PaymentForm, not even an explicit nil
### GetPaymentUrl

`func (o *CreateAlipayOrderResultDto) GetPaymentUrl() string`

GetPaymentUrl returns the PaymentUrl field if non-nil, zero value otherwise.

### GetPaymentUrlOk

`func (o *CreateAlipayOrderResultDto) GetPaymentUrlOk() (*string, bool)`

GetPaymentUrlOk returns a tuple with the PaymentUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentUrl

`func (o *CreateAlipayOrderResultDto) SetPaymentUrl(v string)`

SetPaymentUrl sets PaymentUrl field to given value.

### HasPaymentUrl

`func (o *CreateAlipayOrderResultDto) HasPaymentUrl() bool`

HasPaymentUrl returns a boolean if a field has been set.

### SetPaymentUrlNil

`func (o *CreateAlipayOrderResultDto) SetPaymentUrlNil(b bool)`

 SetPaymentUrlNil sets the value for PaymentUrl to be an explicit nil

### UnsetPaymentUrl
`func (o *CreateAlipayOrderResultDto) UnsetPaymentUrl()`

UnsetPaymentUrl ensures that no value is present for PaymentUrl, not even an explicit nil
### GetOrderString

`func (o *CreateAlipayOrderResultDto) GetOrderString() string`

GetOrderString returns the OrderString field if non-nil, zero value otherwise.

### GetOrderStringOk

`func (o *CreateAlipayOrderResultDto) GetOrderStringOk() (*string, bool)`

GetOrderStringOk returns a tuple with the OrderString field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderString

`func (o *CreateAlipayOrderResultDto) SetOrderString(v string)`

SetOrderString sets OrderString field to given value.

### HasOrderString

`func (o *CreateAlipayOrderResultDto) HasOrderString() bool`

HasOrderString returns a boolean if a field has been set.

### SetOrderStringNil

`func (o *CreateAlipayOrderResultDto) SetOrderStringNil(b bool)`

 SetOrderStringNil sets the value for OrderString to be an explicit nil

### UnsetOrderString
`func (o *CreateAlipayOrderResultDto) UnsetOrderString()`

UnsetOrderString ensures that no value is present for OrderString, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


