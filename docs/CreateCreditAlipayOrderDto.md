# CreateCreditAlipayOrderDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppId** | **string** |  |
**PackageId** | **string** |  |
**CheckoutMode** | Pointer to **NullableString** |  | [optional]
**ReturnUrl** | Pointer to **NullableString** |  | [optional]
**QuitUrl** | Pointer to **NullableString** |  | [optional]

## Methods

### NewCreateCreditAlipayOrderDto

`func NewCreateCreditAlipayOrderDto(appId string, packageId string, ) *CreateCreditAlipayOrderDto`

NewCreateCreditAlipayOrderDto instantiates a new CreateCreditAlipayOrderDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateCreditAlipayOrderDtoWithDefaults

`func NewCreateCreditAlipayOrderDtoWithDefaults() *CreateCreditAlipayOrderDto`

NewCreateCreditAlipayOrderDtoWithDefaults instantiates a new CreateCreditAlipayOrderDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppId

`func (o *CreateCreditAlipayOrderDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *CreateCreditAlipayOrderDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *CreateCreditAlipayOrderDto) SetAppId(v string)`

SetAppId sets AppId field to given value.


### GetPackageId

`func (o *CreateCreditAlipayOrderDto) GetPackageId() string`

GetPackageId returns the PackageId field if non-nil, zero value otherwise.

### GetPackageIdOk

`func (o *CreateCreditAlipayOrderDto) GetPackageIdOk() (*string, bool)`

GetPackageIdOk returns a tuple with the PackageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackageId

`func (o *CreateCreditAlipayOrderDto) SetPackageId(v string)`

SetPackageId sets PackageId field to given value.


### GetCheckoutMode

`func (o *CreateCreditAlipayOrderDto) GetCheckoutMode() string`

GetCheckoutMode returns the CheckoutMode field if non-nil, zero value otherwise.

### GetCheckoutModeOk

`func (o *CreateCreditAlipayOrderDto) GetCheckoutModeOk() (*string, bool)`

GetCheckoutModeOk returns a tuple with the CheckoutMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckoutMode

`func (o *CreateCreditAlipayOrderDto) SetCheckoutMode(v string)`

SetCheckoutMode sets CheckoutMode field to given value.

### HasCheckoutMode

`func (o *CreateCreditAlipayOrderDto) HasCheckoutMode() bool`

HasCheckoutMode returns a boolean if a field has been set.

### SetCheckoutModeNil

`func (o *CreateCreditAlipayOrderDto) SetCheckoutModeNil(b bool)`

 SetCheckoutModeNil sets the value for CheckoutMode to be an explicit nil

### UnsetCheckoutMode
`func (o *CreateCreditAlipayOrderDto) UnsetCheckoutMode()`

UnsetCheckoutMode ensures that no value is present for CheckoutMode, not even an explicit nil
### GetReturnUrl

`func (o *CreateCreditAlipayOrderDto) GetReturnUrl() string`

GetReturnUrl returns the ReturnUrl field if non-nil, zero value otherwise.

### GetReturnUrlOk

`func (o *CreateCreditAlipayOrderDto) GetReturnUrlOk() (*string, bool)`

GetReturnUrlOk returns a tuple with the ReturnUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnUrl

`func (o *CreateCreditAlipayOrderDto) SetReturnUrl(v string)`

SetReturnUrl sets ReturnUrl field to given value.

### HasReturnUrl

`func (o *CreateCreditAlipayOrderDto) HasReturnUrl() bool`

HasReturnUrl returns a boolean if a field has been set.

### SetReturnUrlNil

`func (o *CreateCreditAlipayOrderDto) SetReturnUrlNil(b bool)`

 SetReturnUrlNil sets the value for ReturnUrl to be an explicit nil

### UnsetReturnUrl
`func (o *CreateCreditAlipayOrderDto) UnsetReturnUrl()`

UnsetReturnUrl ensures that no value is present for ReturnUrl, not even an explicit nil
### GetQuitUrl

`func (o *CreateCreditAlipayOrderDto) GetQuitUrl() string`

GetQuitUrl returns the QuitUrl field if non-nil, zero value otherwise.

### GetQuitUrlOk

`func (o *CreateCreditAlipayOrderDto) GetQuitUrlOk() (*string, bool)`

GetQuitUrlOk returns a tuple with the QuitUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuitUrl

`func (o *CreateCreditAlipayOrderDto) SetQuitUrl(v string)`

SetQuitUrl sets QuitUrl field to given value.

### HasQuitUrl

`func (o *CreateCreditAlipayOrderDto) HasQuitUrl() bool`

HasQuitUrl returns a boolean if a field has been set.

### SetQuitUrlNil

`func (o *CreateCreditAlipayOrderDto) SetQuitUrlNil(b bool)`

 SetQuitUrlNil sets the value for QuitUrl to be an explicit nil

### UnsetQuitUrl
`func (o *CreateCreditAlipayOrderDto) UnsetQuitUrl()`

UnsetQuitUrl ensures that no value is present for QuitUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


