# AppleVerifyReceiptResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Environment** | Pointer to **NullableString** |  | [optional]
**IsRetryable** | Pointer to **bool** |  | [optional]
**Status** | Pointer to **int32** | 订阅订单状态 | [optional]
**LatestReceiptInfo** | Pointer to [**[]LatestReceiptInfo**](LatestReceiptInfo.md) |  | [optional]
**LatestReceipt** | Pointer to **NullableString** |  | [optional]
**PendingRenewalInfo** | Pointer to [**[]PendingRenewalInfo**](PendingRenewalInfo.md) |  | [optional]
**Receipt** | Pointer to [**Receipt**](Receipt.md) |  | [optional]

## Methods

### NewAppleVerifyReceiptResult

`func NewAppleVerifyReceiptResult() *AppleVerifyReceiptResult`

NewAppleVerifyReceiptResult instantiates a new AppleVerifyReceiptResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAppleVerifyReceiptResultWithDefaults

`func NewAppleVerifyReceiptResultWithDefaults() *AppleVerifyReceiptResult`

NewAppleVerifyReceiptResultWithDefaults instantiates a new AppleVerifyReceiptResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnvironment

`func (o *AppleVerifyReceiptResult) GetEnvironment() string`

GetEnvironment returns the Environment field if non-nil, zero value otherwise.

### GetEnvironmentOk

`func (o *AppleVerifyReceiptResult) GetEnvironmentOk() (*string, bool)`

GetEnvironmentOk returns a tuple with the Environment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnvironment

`func (o *AppleVerifyReceiptResult) SetEnvironment(v string)`

SetEnvironment sets Environment field to given value.

### HasEnvironment

`func (o *AppleVerifyReceiptResult) HasEnvironment() bool`

HasEnvironment returns a boolean if a field has been set.

### SetEnvironmentNil

`func (o *AppleVerifyReceiptResult) SetEnvironmentNil(b bool)`

 SetEnvironmentNil sets the value for Environment to be an explicit nil

### UnsetEnvironment
`func (o *AppleVerifyReceiptResult) UnsetEnvironment()`

UnsetEnvironment ensures that no value is present for Environment, not even an explicit nil
### GetIsRetryable

`func (o *AppleVerifyReceiptResult) GetIsRetryable() bool`

GetIsRetryable returns the IsRetryable field if non-nil, zero value otherwise.

### GetIsRetryableOk

`func (o *AppleVerifyReceiptResult) GetIsRetryableOk() (*bool, bool)`

GetIsRetryableOk returns a tuple with the IsRetryable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsRetryable

`func (o *AppleVerifyReceiptResult) SetIsRetryable(v bool)`

SetIsRetryable sets IsRetryable field to given value.

### HasIsRetryable

`func (o *AppleVerifyReceiptResult) HasIsRetryable() bool`

HasIsRetryable returns a boolean if a field has been set.

### GetStatus

`func (o *AppleVerifyReceiptResult) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AppleVerifyReceiptResult) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AppleVerifyReceiptResult) SetStatus(v int32)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *AppleVerifyReceiptResult) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetLatestReceiptInfo

`func (o *AppleVerifyReceiptResult) GetLatestReceiptInfo() []LatestReceiptInfo`

GetLatestReceiptInfo returns the LatestReceiptInfo field if non-nil, zero value otherwise.

### GetLatestReceiptInfoOk

`func (o *AppleVerifyReceiptResult) GetLatestReceiptInfoOk() (*[]LatestReceiptInfo, bool)`

GetLatestReceiptInfoOk returns a tuple with the LatestReceiptInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestReceiptInfo

`func (o *AppleVerifyReceiptResult) SetLatestReceiptInfo(v []LatestReceiptInfo)`

SetLatestReceiptInfo sets LatestReceiptInfo field to given value.

### HasLatestReceiptInfo

`func (o *AppleVerifyReceiptResult) HasLatestReceiptInfo() bool`

HasLatestReceiptInfo returns a boolean if a field has been set.

### SetLatestReceiptInfoNil

`func (o *AppleVerifyReceiptResult) SetLatestReceiptInfoNil(b bool)`

 SetLatestReceiptInfoNil sets the value for LatestReceiptInfo to be an explicit nil

### UnsetLatestReceiptInfo
`func (o *AppleVerifyReceiptResult) UnsetLatestReceiptInfo()`

UnsetLatestReceiptInfo ensures that no value is present for LatestReceiptInfo, not even an explicit nil
### GetLatestReceipt

`func (o *AppleVerifyReceiptResult) GetLatestReceipt() string`

GetLatestReceipt returns the LatestReceipt field if non-nil, zero value otherwise.

### GetLatestReceiptOk

`func (o *AppleVerifyReceiptResult) GetLatestReceiptOk() (*string, bool)`

GetLatestReceiptOk returns a tuple with the LatestReceipt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestReceipt

`func (o *AppleVerifyReceiptResult) SetLatestReceipt(v string)`

SetLatestReceipt sets LatestReceipt field to given value.

### HasLatestReceipt

`func (o *AppleVerifyReceiptResult) HasLatestReceipt() bool`

HasLatestReceipt returns a boolean if a field has been set.

### SetLatestReceiptNil

`func (o *AppleVerifyReceiptResult) SetLatestReceiptNil(b bool)`

 SetLatestReceiptNil sets the value for LatestReceipt to be an explicit nil

### UnsetLatestReceipt
`func (o *AppleVerifyReceiptResult) UnsetLatestReceipt()`

UnsetLatestReceipt ensures that no value is present for LatestReceipt, not even an explicit nil
### GetPendingRenewalInfo

`func (o *AppleVerifyReceiptResult) GetPendingRenewalInfo() []PendingRenewalInfo`

GetPendingRenewalInfo returns the PendingRenewalInfo field if non-nil, zero value otherwise.

### GetPendingRenewalInfoOk

`func (o *AppleVerifyReceiptResult) GetPendingRenewalInfoOk() (*[]PendingRenewalInfo, bool)`

GetPendingRenewalInfoOk returns a tuple with the PendingRenewalInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPendingRenewalInfo

`func (o *AppleVerifyReceiptResult) SetPendingRenewalInfo(v []PendingRenewalInfo)`

SetPendingRenewalInfo sets PendingRenewalInfo field to given value.

### HasPendingRenewalInfo

`func (o *AppleVerifyReceiptResult) HasPendingRenewalInfo() bool`

HasPendingRenewalInfo returns a boolean if a field has been set.

### SetPendingRenewalInfoNil

`func (o *AppleVerifyReceiptResult) SetPendingRenewalInfoNil(b bool)`

 SetPendingRenewalInfoNil sets the value for PendingRenewalInfo to be an explicit nil

### UnsetPendingRenewalInfo
`func (o *AppleVerifyReceiptResult) UnsetPendingRenewalInfo()`

UnsetPendingRenewalInfo ensures that no value is present for PendingRenewalInfo, not even an explicit nil
### GetReceipt

`func (o *AppleVerifyReceiptResult) GetReceipt() Receipt`

GetReceipt returns the Receipt field if non-nil, zero value otherwise.

### GetReceiptOk

`func (o *AppleVerifyReceiptResult) GetReceiptOk() (*Receipt, bool)`

GetReceiptOk returns a tuple with the Receipt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceipt

`func (o *AppleVerifyReceiptResult) SetReceipt(v Receipt)`

SetReceipt sets Receipt field to given value.

### HasReceipt

`func (o *AppleVerifyReceiptResult) HasReceipt() bool`

HasReceipt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


