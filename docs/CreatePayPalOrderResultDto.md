# CreatePayPalOrderResultDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrderId** | Pointer to **string** | 本系统订单 ID | [optional] 
**PayPalOrderId** | Pointer to **NullableString** | PayPal 订单 ID（供前端按钮使用） | [optional] 
**PayPalSubscriptionId** | Pointer to **NullableString** | PayPal 订阅 ID（自动续费场景） | [optional] 
**ApprovalUrl** | Pointer to **NullableString** | PayPal approve 链接，可用于不使用 JS SDK 的桌面端跳转。 | [optional] 
**CheckoutKind** | Pointer to **NullableString** | order&#x3D;一次性订单，subscription&#x3D;自动续费订阅。 | [optional] 

## Methods

### NewCreatePayPalOrderResultDto

`func NewCreatePayPalOrderResultDto() *CreatePayPalOrderResultDto`

NewCreatePayPalOrderResultDto instantiates a new CreatePayPalOrderResultDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreatePayPalOrderResultDtoWithDefaults

`func NewCreatePayPalOrderResultDtoWithDefaults() *CreatePayPalOrderResultDto`

NewCreatePayPalOrderResultDtoWithDefaults instantiates a new CreatePayPalOrderResultDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrderId

`func (o *CreatePayPalOrderResultDto) GetOrderId() string`

GetOrderId returns the OrderId field if non-nil, zero value otherwise.

### GetOrderIdOk

`func (o *CreatePayPalOrderResultDto) GetOrderIdOk() (*string, bool)`

GetOrderIdOk returns a tuple with the OrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderId

`func (o *CreatePayPalOrderResultDto) SetOrderId(v string)`

SetOrderId sets OrderId field to given value.

### HasOrderId

`func (o *CreatePayPalOrderResultDto) HasOrderId() bool`

HasOrderId returns a boolean if a field has been set.

### GetPayPalOrderId

`func (o *CreatePayPalOrderResultDto) GetPayPalOrderId() string`

GetPayPalOrderId returns the PayPalOrderId field if non-nil, zero value otherwise.

### GetPayPalOrderIdOk

`func (o *CreatePayPalOrderResultDto) GetPayPalOrderIdOk() (*string, bool)`

GetPayPalOrderIdOk returns a tuple with the PayPalOrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayPalOrderId

`func (o *CreatePayPalOrderResultDto) SetPayPalOrderId(v string)`

SetPayPalOrderId sets PayPalOrderId field to given value.

### HasPayPalOrderId

`func (o *CreatePayPalOrderResultDto) HasPayPalOrderId() bool`

HasPayPalOrderId returns a boolean if a field has been set.

### SetPayPalOrderIdNil

`func (o *CreatePayPalOrderResultDto) SetPayPalOrderIdNil(b bool)`

 SetPayPalOrderIdNil sets the value for PayPalOrderId to be an explicit nil

### UnsetPayPalOrderId
`func (o *CreatePayPalOrderResultDto) UnsetPayPalOrderId()`

UnsetPayPalOrderId ensures that no value is present for PayPalOrderId, not even an explicit nil
### GetPayPalSubscriptionId

`func (o *CreatePayPalOrderResultDto) GetPayPalSubscriptionId() string`

GetPayPalSubscriptionId returns the PayPalSubscriptionId field if non-nil, zero value otherwise.

### GetPayPalSubscriptionIdOk

`func (o *CreatePayPalOrderResultDto) GetPayPalSubscriptionIdOk() (*string, bool)`

GetPayPalSubscriptionIdOk returns a tuple with the PayPalSubscriptionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayPalSubscriptionId

`func (o *CreatePayPalOrderResultDto) SetPayPalSubscriptionId(v string)`

SetPayPalSubscriptionId sets PayPalSubscriptionId field to given value.

### HasPayPalSubscriptionId

`func (o *CreatePayPalOrderResultDto) HasPayPalSubscriptionId() bool`

HasPayPalSubscriptionId returns a boolean if a field has been set.

### SetPayPalSubscriptionIdNil

`func (o *CreatePayPalOrderResultDto) SetPayPalSubscriptionIdNil(b bool)`

 SetPayPalSubscriptionIdNil sets the value for PayPalSubscriptionId to be an explicit nil

### UnsetPayPalSubscriptionId
`func (o *CreatePayPalOrderResultDto) UnsetPayPalSubscriptionId()`

UnsetPayPalSubscriptionId ensures that no value is present for PayPalSubscriptionId, not even an explicit nil
### GetApprovalUrl

`func (o *CreatePayPalOrderResultDto) GetApprovalUrl() string`

GetApprovalUrl returns the ApprovalUrl field if non-nil, zero value otherwise.

### GetApprovalUrlOk

`func (o *CreatePayPalOrderResultDto) GetApprovalUrlOk() (*string, bool)`

GetApprovalUrlOk returns a tuple with the ApprovalUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovalUrl

`func (o *CreatePayPalOrderResultDto) SetApprovalUrl(v string)`

SetApprovalUrl sets ApprovalUrl field to given value.

### HasApprovalUrl

`func (o *CreatePayPalOrderResultDto) HasApprovalUrl() bool`

HasApprovalUrl returns a boolean if a field has been set.

### SetApprovalUrlNil

`func (o *CreatePayPalOrderResultDto) SetApprovalUrlNil(b bool)`

 SetApprovalUrlNil sets the value for ApprovalUrl to be an explicit nil

### UnsetApprovalUrl
`func (o *CreatePayPalOrderResultDto) UnsetApprovalUrl()`

UnsetApprovalUrl ensures that no value is present for ApprovalUrl, not even an explicit nil
### GetCheckoutKind

`func (o *CreatePayPalOrderResultDto) GetCheckoutKind() string`

GetCheckoutKind returns the CheckoutKind field if non-nil, zero value otherwise.

### GetCheckoutKindOk

`func (o *CreatePayPalOrderResultDto) GetCheckoutKindOk() (*string, bool)`

GetCheckoutKindOk returns a tuple with the CheckoutKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckoutKind

`func (o *CreatePayPalOrderResultDto) SetCheckoutKind(v string)`

SetCheckoutKind sets CheckoutKind field to given value.

### HasCheckoutKind

`func (o *CreatePayPalOrderResultDto) HasCheckoutKind() bool`

HasCheckoutKind returns a boolean if a field has been set.

### SetCheckoutKindNil

`func (o *CreatePayPalOrderResultDto) SetCheckoutKindNil(b bool)`

 SetCheckoutKindNil sets the value for CheckoutKind to be an explicit nil

### UnsetCheckoutKind
`func (o *CreatePayPalOrderResultDto) UnsetCheckoutKind()`

UnsetCheckoutKind ensures that no value is present for CheckoutKind, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


