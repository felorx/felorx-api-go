# CreditAccountDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppId** | Pointer to **string** |  | [optional]
**Balance** | Pointer to **int32** |  | [optional]
**RecentLedger** | Pointer to [**[]CreditLedgerEntryDto**](CreditLedgerEntryDto.md) |  | [optional]

## Methods

### NewCreditAccountDto

`func NewCreditAccountDto() *CreditAccountDto`

NewCreditAccountDto instantiates a new CreditAccountDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreditAccountDtoWithDefaults

`func NewCreditAccountDtoWithDefaults() *CreditAccountDto`

NewCreditAccountDtoWithDefaults instantiates a new CreditAccountDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppId

`func (o *CreditAccountDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *CreditAccountDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *CreditAccountDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *CreditAccountDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetBalance

`func (o *CreditAccountDto) GetBalance() int32`

GetBalance returns the Balance field if non-nil, zero value otherwise.

### GetBalanceOk

`func (o *CreditAccountDto) GetBalanceOk() (*int32, bool)`

GetBalanceOk returns a tuple with the Balance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBalance

`func (o *CreditAccountDto) SetBalance(v int32)`

SetBalance sets Balance field to given value.

### HasBalance

`func (o *CreditAccountDto) HasBalance() bool`

HasBalance returns a boolean if a field has been set.

### GetRecentLedger

`func (o *CreditAccountDto) GetRecentLedger() []CreditLedgerEntryDto`

GetRecentLedger returns the RecentLedger field if non-nil, zero value otherwise.

### GetRecentLedgerOk

`func (o *CreditAccountDto) GetRecentLedgerOk() (*[]CreditLedgerEntryDto, bool)`

GetRecentLedgerOk returns a tuple with the RecentLedger field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecentLedger

`func (o *CreditAccountDto) SetRecentLedger(v []CreditLedgerEntryDto)`

SetRecentLedger sets RecentLedger field to given value.

### HasRecentLedger

`func (o *CreditAccountDto) HasRecentLedger() bool`

HasRecentLedger returns a boolean if a field has been set.

### SetRecentLedgerNil

`func (o *CreditAccountDto) SetRecentLedgerNil(b bool)`

 SetRecentLedgerNil sets the value for RecentLedger to be an explicit nil

### UnsetRecentLedger
`func (o *CreditAccountDto) UnsetRecentLedger()`

UnsetRecentLedger ensures that no value is present for RecentLedger, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


