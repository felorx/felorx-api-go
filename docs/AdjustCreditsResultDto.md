# AdjustCreditsResultDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Balance** | Pointer to **int32** |  | [optional]
**LedgerEntry** | Pointer to [**CreditLedgerEntryDto**](CreditLedgerEntryDto.md) |  | [optional]

## Methods

### NewAdjustCreditsResultDto

`func NewAdjustCreditsResultDto() *AdjustCreditsResultDto`

NewAdjustCreditsResultDto instantiates a new AdjustCreditsResultDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAdjustCreditsResultDtoWithDefaults

`func NewAdjustCreditsResultDtoWithDefaults() *AdjustCreditsResultDto`

NewAdjustCreditsResultDtoWithDefaults instantiates a new AdjustCreditsResultDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBalance

`func (o *AdjustCreditsResultDto) GetBalance() int32`

GetBalance returns the Balance field if non-nil, zero value otherwise.

### GetBalanceOk

`func (o *AdjustCreditsResultDto) GetBalanceOk() (*int32, bool)`

GetBalanceOk returns a tuple with the Balance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBalance

`func (o *AdjustCreditsResultDto) SetBalance(v int32)`

SetBalance sets Balance field to given value.

### HasBalance

`func (o *AdjustCreditsResultDto) HasBalance() bool`

HasBalance returns a boolean if a field has been set.

### GetLedgerEntry

`func (o *AdjustCreditsResultDto) GetLedgerEntry() CreditLedgerEntryDto`

GetLedgerEntry returns the LedgerEntry field if non-nil, zero value otherwise.

### GetLedgerEntryOk

`func (o *AdjustCreditsResultDto) GetLedgerEntryOk() (*CreditLedgerEntryDto, bool)`

GetLedgerEntryOk returns a tuple with the LedgerEntry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLedgerEntry

`func (o *AdjustCreditsResultDto) SetLedgerEntry(v CreditLedgerEntryDto)`

SetLedgerEntry sets LedgerEntry field to given value.

### HasLedgerEntry

`func (o *AdjustCreditsResultDto) HasLedgerEntry() bool`

HasLedgerEntry returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


