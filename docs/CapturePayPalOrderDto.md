# CapturePayPalOrderDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PayPalOrderId** | Pointer to **NullableString** | PayPal 订单 ID | [optional] 
**PayPalSubscriptionId** | Pointer to **NullableString** | PayPal 订阅 ID。自动续费场景使用该字段。 | [optional] 

## Methods

### NewCapturePayPalOrderDto

`func NewCapturePayPalOrderDto() *CapturePayPalOrderDto`

NewCapturePayPalOrderDto instantiates a new CapturePayPalOrderDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCapturePayPalOrderDtoWithDefaults

`func NewCapturePayPalOrderDtoWithDefaults() *CapturePayPalOrderDto`

NewCapturePayPalOrderDtoWithDefaults instantiates a new CapturePayPalOrderDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPayPalOrderId

`func (o *CapturePayPalOrderDto) GetPayPalOrderId() string`

GetPayPalOrderId returns the PayPalOrderId field if non-nil, zero value otherwise.

### GetPayPalOrderIdOk

`func (o *CapturePayPalOrderDto) GetPayPalOrderIdOk() (*string, bool)`

GetPayPalOrderIdOk returns a tuple with the PayPalOrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayPalOrderId

`func (o *CapturePayPalOrderDto) SetPayPalOrderId(v string)`

SetPayPalOrderId sets PayPalOrderId field to given value.

### HasPayPalOrderId

`func (o *CapturePayPalOrderDto) HasPayPalOrderId() bool`

HasPayPalOrderId returns a boolean if a field has been set.

### SetPayPalOrderIdNil

`func (o *CapturePayPalOrderDto) SetPayPalOrderIdNil(b bool)`

 SetPayPalOrderIdNil sets the value for PayPalOrderId to be an explicit nil

### UnsetPayPalOrderId
`func (o *CapturePayPalOrderDto) UnsetPayPalOrderId()`

UnsetPayPalOrderId ensures that no value is present for PayPalOrderId, not even an explicit nil
### GetPayPalSubscriptionId

`func (o *CapturePayPalOrderDto) GetPayPalSubscriptionId() string`

GetPayPalSubscriptionId returns the PayPalSubscriptionId field if non-nil, zero value otherwise.

### GetPayPalSubscriptionIdOk

`func (o *CapturePayPalOrderDto) GetPayPalSubscriptionIdOk() (*string, bool)`

GetPayPalSubscriptionIdOk returns a tuple with the PayPalSubscriptionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayPalSubscriptionId

`func (o *CapturePayPalOrderDto) SetPayPalSubscriptionId(v string)`

SetPayPalSubscriptionId sets PayPalSubscriptionId field to given value.

### HasPayPalSubscriptionId

`func (o *CapturePayPalOrderDto) HasPayPalSubscriptionId() bool`

HasPayPalSubscriptionId returns a boolean if a field has been set.

### SetPayPalSubscriptionIdNil

`func (o *CapturePayPalOrderDto) SetPayPalSubscriptionIdNil(b bool)`

 SetPayPalSubscriptionIdNil sets the value for PayPalSubscriptionId to be an explicit nil

### UnsetPayPalSubscriptionId
`func (o *CapturePayPalOrderDto) UnsetPayPalSubscriptionId()`

UnsetPayPalSubscriptionId ensures that no value is present for PayPalSubscriptionId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


