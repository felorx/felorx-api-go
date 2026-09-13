# CreateCreditPayPalOrderResultDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrderId** | Pointer to **string** |  | [optional] 
**PayPalOrderId** | Pointer to **NullableString** |  | [optional] 
**ApprovalUrl** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCreateCreditPayPalOrderResultDto

`func NewCreateCreditPayPalOrderResultDto() *CreateCreditPayPalOrderResultDto`

NewCreateCreditPayPalOrderResultDto instantiates a new CreateCreditPayPalOrderResultDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateCreditPayPalOrderResultDtoWithDefaults

`func NewCreateCreditPayPalOrderResultDtoWithDefaults() *CreateCreditPayPalOrderResultDto`

NewCreateCreditPayPalOrderResultDtoWithDefaults instantiates a new CreateCreditPayPalOrderResultDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrderId

`func (o *CreateCreditPayPalOrderResultDto) GetOrderId() string`

GetOrderId returns the OrderId field if non-nil, zero value otherwise.

### GetOrderIdOk

`func (o *CreateCreditPayPalOrderResultDto) GetOrderIdOk() (*string, bool)`

GetOrderIdOk returns a tuple with the OrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderId

`func (o *CreateCreditPayPalOrderResultDto) SetOrderId(v string)`

SetOrderId sets OrderId field to given value.

### HasOrderId

`func (o *CreateCreditPayPalOrderResultDto) HasOrderId() bool`

HasOrderId returns a boolean if a field has been set.

### GetPayPalOrderId

`func (o *CreateCreditPayPalOrderResultDto) GetPayPalOrderId() string`

GetPayPalOrderId returns the PayPalOrderId field if non-nil, zero value otherwise.

### GetPayPalOrderIdOk

`func (o *CreateCreditPayPalOrderResultDto) GetPayPalOrderIdOk() (*string, bool)`

GetPayPalOrderIdOk returns a tuple with the PayPalOrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayPalOrderId

`func (o *CreateCreditPayPalOrderResultDto) SetPayPalOrderId(v string)`

SetPayPalOrderId sets PayPalOrderId field to given value.

### HasPayPalOrderId

`func (o *CreateCreditPayPalOrderResultDto) HasPayPalOrderId() bool`

HasPayPalOrderId returns a boolean if a field has been set.

### SetPayPalOrderIdNil

`func (o *CreateCreditPayPalOrderResultDto) SetPayPalOrderIdNil(b bool)`

 SetPayPalOrderIdNil sets the value for PayPalOrderId to be an explicit nil

### UnsetPayPalOrderId
`func (o *CreateCreditPayPalOrderResultDto) UnsetPayPalOrderId()`

UnsetPayPalOrderId ensures that no value is present for PayPalOrderId, not even an explicit nil
### GetApprovalUrl

`func (o *CreateCreditPayPalOrderResultDto) GetApprovalUrl() string`

GetApprovalUrl returns the ApprovalUrl field if non-nil, zero value otherwise.

### GetApprovalUrlOk

`func (o *CreateCreditPayPalOrderResultDto) GetApprovalUrlOk() (*string, bool)`

GetApprovalUrlOk returns a tuple with the ApprovalUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApprovalUrl

`func (o *CreateCreditPayPalOrderResultDto) SetApprovalUrl(v string)`

SetApprovalUrl sets ApprovalUrl field to given value.

### HasApprovalUrl

`func (o *CreateCreditPayPalOrderResultDto) HasApprovalUrl() bool`

HasApprovalUrl returns a boolean if a field has been set.

### SetApprovalUrlNil

`func (o *CreateCreditPayPalOrderResultDto) SetApprovalUrlNil(b bool)`

 SetApprovalUrlNil sets the value for ApprovalUrl to be an explicit nil

### UnsetApprovalUrl
`func (o *CreateCreditPayPalOrderResultDto) UnsetApprovalUrl()`

UnsetApprovalUrl ensures that no value is present for ApprovalUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


