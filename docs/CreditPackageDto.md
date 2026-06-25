# CreditPackageDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional]
**AppId** | Pointer to **string** |  | [optional]
**Code** | Pointer to **NullableString** |  | [optional]
**Title** | Pointer to **NullableString** |  | [optional]
**Description** | Pointer to **NullableString** |  | [optional]
**Credits** | Pointer to **int32** |  | [optional]
**Amount** | Pointer to **float64** |  | [optional]
**Currency** | Pointer to **NullableString** |  | [optional]
**IsPopular** | Pointer to **bool** |  | [optional]
**StoreProductId** | Pointer to **NullableString** |  | [optional]

## Methods

### NewCreditPackageDto

`func NewCreditPackageDto() *CreditPackageDto`

NewCreditPackageDto instantiates a new CreditPackageDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreditPackageDtoWithDefaults

`func NewCreditPackageDtoWithDefaults() *CreditPackageDto`

NewCreditPackageDtoWithDefaults instantiates a new CreditPackageDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreditPackageDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreditPackageDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreditPackageDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CreditPackageDto) HasId() bool`

HasId returns a boolean if a field has been set.

### GetAppId

`func (o *CreditPackageDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *CreditPackageDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *CreditPackageDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *CreditPackageDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetCode

`func (o *CreditPackageDto) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *CreditPackageDto) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *CreditPackageDto) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *CreditPackageDto) HasCode() bool`

HasCode returns a boolean if a field has been set.

### SetCodeNil

`func (o *CreditPackageDto) SetCodeNil(b bool)`

 SetCodeNil sets the value for Code to be an explicit nil

### UnsetCode
`func (o *CreditPackageDto) UnsetCode()`

UnsetCode ensures that no value is present for Code, not even an explicit nil
### GetTitle

`func (o *CreditPackageDto) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CreditPackageDto) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CreditPackageDto) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *CreditPackageDto) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *CreditPackageDto) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *CreditPackageDto) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetDescription

`func (o *CreditPackageDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CreditPackageDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CreditPackageDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CreditPackageDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *CreditPackageDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *CreditPackageDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetCredits

`func (o *CreditPackageDto) GetCredits() int32`

GetCredits returns the Credits field if non-nil, zero value otherwise.

### GetCreditsOk

`func (o *CreditPackageDto) GetCreditsOk() (*int32, bool)`

GetCreditsOk returns a tuple with the Credits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredits

`func (o *CreditPackageDto) SetCredits(v int32)`

SetCredits sets Credits field to given value.

### HasCredits

`func (o *CreditPackageDto) HasCredits() bool`

HasCredits returns a boolean if a field has been set.

### GetAmount

`func (o *CreditPackageDto) GetAmount() float64`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *CreditPackageDto) GetAmountOk() (*float64, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *CreditPackageDto) SetAmount(v float64)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *CreditPackageDto) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetCurrency

`func (o *CreditPackageDto) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CreditPackageDto) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CreditPackageDto) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *CreditPackageDto) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *CreditPackageDto) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *CreditPackageDto) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetIsPopular

`func (o *CreditPackageDto) GetIsPopular() bool`

GetIsPopular returns the IsPopular field if non-nil, zero value otherwise.

### GetIsPopularOk

`func (o *CreditPackageDto) GetIsPopularOk() (*bool, bool)`

GetIsPopularOk returns a tuple with the IsPopular field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPopular

`func (o *CreditPackageDto) SetIsPopular(v bool)`

SetIsPopular sets IsPopular field to given value.

### HasIsPopular

`func (o *CreditPackageDto) HasIsPopular() bool`

HasIsPopular returns a boolean if a field has been set.

### GetStoreProductId

`func (o *CreditPackageDto) GetStoreProductId() string`

GetStoreProductId returns the StoreProductId field if non-nil, zero value otherwise.

### GetStoreProductIdOk

`func (o *CreditPackageDto) GetStoreProductIdOk() (*string, bool)`

GetStoreProductIdOk returns a tuple with the StoreProductId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoreProductId

`func (o *CreditPackageDto) SetStoreProductId(v string)`

SetStoreProductId sets StoreProductId field to given value.

### HasStoreProductId

`func (o *CreditPackageDto) HasStoreProductId() bool`

HasStoreProductId returns a boolean if a field has been set.

### SetStoreProductIdNil

`func (o *CreditPackageDto) SetStoreProductIdNil(b bool)`

 SetStoreProductIdNil sets the value for StoreProductId to be an explicit nil

### UnsetStoreProductId
`func (o *CreditPackageDto) UnsetStoreProductId()`

UnsetStoreProductId ensures that no value is present for StoreProductId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


