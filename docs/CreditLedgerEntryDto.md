# CreditLedgerEntryDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**Amount** | Pointer to **int32** |  | [optional] 
**BalanceAfter** | Pointer to **int32** |  | [optional] 
**Type** | Pointer to **NullableString** |  | [optional] 
**ReferenceId** | Pointer to **NullableString** |  | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**CreationTime** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewCreditLedgerEntryDto

`func NewCreditLedgerEntryDto() *CreditLedgerEntryDto`

NewCreditLedgerEntryDto instantiates a new CreditLedgerEntryDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreditLedgerEntryDtoWithDefaults

`func NewCreditLedgerEntryDtoWithDefaults() *CreditLedgerEntryDto`

NewCreditLedgerEntryDtoWithDefaults instantiates a new CreditLedgerEntryDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreditLedgerEntryDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreditLedgerEntryDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreditLedgerEntryDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CreditLedgerEntryDto) HasId() bool`

HasId returns a boolean if a field has been set.

### GetAmount

`func (o *CreditLedgerEntryDto) GetAmount() int32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *CreditLedgerEntryDto) GetAmountOk() (*int32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *CreditLedgerEntryDto) SetAmount(v int32)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *CreditLedgerEntryDto) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetBalanceAfter

`func (o *CreditLedgerEntryDto) GetBalanceAfter() int32`

GetBalanceAfter returns the BalanceAfter field if non-nil, zero value otherwise.

### GetBalanceAfterOk

`func (o *CreditLedgerEntryDto) GetBalanceAfterOk() (*int32, bool)`

GetBalanceAfterOk returns a tuple with the BalanceAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBalanceAfter

`func (o *CreditLedgerEntryDto) SetBalanceAfter(v int32)`

SetBalanceAfter sets BalanceAfter field to given value.

### HasBalanceAfter

`func (o *CreditLedgerEntryDto) HasBalanceAfter() bool`

HasBalanceAfter returns a boolean if a field has been set.

### GetType

`func (o *CreditLedgerEntryDto) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *CreditLedgerEntryDto) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *CreditLedgerEntryDto) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *CreditLedgerEntryDto) HasType() bool`

HasType returns a boolean if a field has been set.

### SetTypeNil

`func (o *CreditLedgerEntryDto) SetTypeNil(b bool)`

 SetTypeNil sets the value for Type to be an explicit nil

### UnsetType
`func (o *CreditLedgerEntryDto) UnsetType()`

UnsetType ensures that no value is present for Type, not even an explicit nil
### GetReferenceId

`func (o *CreditLedgerEntryDto) GetReferenceId() string`

GetReferenceId returns the ReferenceId field if non-nil, zero value otherwise.

### GetReferenceIdOk

`func (o *CreditLedgerEntryDto) GetReferenceIdOk() (*string, bool)`

GetReferenceIdOk returns a tuple with the ReferenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceId

`func (o *CreditLedgerEntryDto) SetReferenceId(v string)`

SetReferenceId sets ReferenceId field to given value.

### HasReferenceId

`func (o *CreditLedgerEntryDto) HasReferenceId() bool`

HasReferenceId returns a boolean if a field has been set.

### SetReferenceIdNil

`func (o *CreditLedgerEntryDto) SetReferenceIdNil(b bool)`

 SetReferenceIdNil sets the value for ReferenceId to be an explicit nil

### UnsetReferenceId
`func (o *CreditLedgerEntryDto) UnsetReferenceId()`

UnsetReferenceId ensures that no value is present for ReferenceId, not even an explicit nil
### GetDescription

`func (o *CreditLedgerEntryDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreditLedgerEntryDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreditLedgerEntryDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreditLedgerEntryDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *CreditLedgerEntryDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *CreditLedgerEntryDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetCreationTime

`func (o *CreditLedgerEntryDto) GetCreationTime() time.Time`

GetCreationTime returns the CreationTime field if non-nil, zero value otherwise.

### GetCreationTimeOk

`func (o *CreditLedgerEntryDto) GetCreationTimeOk() (*time.Time, bool)`

GetCreationTimeOk returns a tuple with the CreationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreationTime

`func (o *CreditLedgerEntryDto) SetCreationTime(v time.Time)`

SetCreationTime sets CreationTime field to given value.

### HasCreationTime

`func (o *CreditLedgerEntryDto) HasCreationTime() bool`

HasCreationTime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


