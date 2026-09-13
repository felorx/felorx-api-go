# SendVerificationCodeDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CodeSender** | Pointer to **NullableString** | 验证码发送器 暂时支持: SMS: 手机短信验证码 | [optional] 
**Account** | Pointer to **NullableString** | 验证码接受者, 用户账户 | [optional] 
**Purpose** | Pointer to **NullableString** | 验证码用途 | [optional] 

## Methods

### NewSendVerificationCodeDto

`func NewSendVerificationCodeDto() *SendVerificationCodeDto`

NewSendVerificationCodeDto instantiates a new SendVerificationCodeDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSendVerificationCodeDtoWithDefaults

`func NewSendVerificationCodeDtoWithDefaults() *SendVerificationCodeDto`

NewSendVerificationCodeDtoWithDefaults instantiates a new SendVerificationCodeDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCodeSender

`func (o *SendVerificationCodeDto) GetCodeSender() string`

GetCodeSender returns the CodeSender field if non-nil, zero value otherwise.

### GetCodeSenderOk

`func (o *SendVerificationCodeDto) GetCodeSenderOk() (*string, bool)`

GetCodeSenderOk returns a tuple with the CodeSender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCodeSender

`func (o *SendVerificationCodeDto) SetCodeSender(v string)`

SetCodeSender sets CodeSender field to given value.

### HasCodeSender

`func (o *SendVerificationCodeDto) HasCodeSender() bool`

HasCodeSender returns a boolean if a field has been set.

### SetCodeSenderNil

`func (o *SendVerificationCodeDto) SetCodeSenderNil(b bool)`

 SetCodeSenderNil sets the value for CodeSender to be an explicit nil

### UnsetCodeSender
`func (o *SendVerificationCodeDto) UnsetCodeSender()`

UnsetCodeSender ensures that no value is present for CodeSender, not even an explicit nil
### GetAccount

`func (o *SendVerificationCodeDto) GetAccount() string`

GetAccount returns the Account field if non-nil, zero value otherwise.

### GetAccountOk

`func (o *SendVerificationCodeDto) GetAccountOk() (*string, bool)`

GetAccountOk returns a tuple with the Account field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccount

`func (o *SendVerificationCodeDto) SetAccount(v string)`

SetAccount sets Account field to given value.

### HasAccount

`func (o *SendVerificationCodeDto) HasAccount() bool`

HasAccount returns a boolean if a field has been set.

### SetAccountNil

`func (o *SendVerificationCodeDto) SetAccountNil(b bool)`

 SetAccountNil sets the value for Account to be an explicit nil

### UnsetAccount
`func (o *SendVerificationCodeDto) UnsetAccount()`

UnsetAccount ensures that no value is present for Account, not even an explicit nil
### GetPurpose

`func (o *SendVerificationCodeDto) GetPurpose() string`

GetPurpose returns the Purpose field if non-nil, zero value otherwise.

### GetPurposeOk

`func (o *SendVerificationCodeDto) GetPurposeOk() (*string, bool)`

GetPurposeOk returns a tuple with the Purpose field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurpose

`func (o *SendVerificationCodeDto) SetPurpose(v string)`

SetPurpose sets Purpose field to given value.

### HasPurpose

`func (o *SendVerificationCodeDto) HasPurpose() bool`

HasPurpose returns a boolean if a field has been set.

### SetPurposeNil

`func (o *SendVerificationCodeDto) SetPurposeNil(b bool)`

 SetPurposeNil sets the value for Purpose to be an explicit nil

### UnsetPurpose
`func (o *SendVerificationCodeDto) UnsetPurpose()`

UnsetPurpose ensures that no value is present for Purpose, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


