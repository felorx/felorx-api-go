# CreateCreditPayPalOrderDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppId** | **string** |  | 
**PackageId** | **string** |  | 
**ReturnUrl** | Pointer to **NullableString** |  | [optional] 
**CancelUrl** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCreateCreditPayPalOrderDto

`func NewCreateCreditPayPalOrderDto(appId string, packageId string, ) *CreateCreditPayPalOrderDto`

NewCreateCreditPayPalOrderDto instantiates a new CreateCreditPayPalOrderDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateCreditPayPalOrderDtoWithDefaults

`func NewCreateCreditPayPalOrderDtoWithDefaults() *CreateCreditPayPalOrderDto`

NewCreateCreditPayPalOrderDtoWithDefaults instantiates a new CreateCreditPayPalOrderDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppId

`func (o *CreateCreditPayPalOrderDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *CreateCreditPayPalOrderDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *CreateCreditPayPalOrderDto) SetAppId(v string)`

SetAppId sets AppId field to given value.


### GetPackageId

`func (o *CreateCreditPayPalOrderDto) GetPackageId() string`

GetPackageId returns the PackageId field if non-nil, zero value otherwise.

### GetPackageIdOk

`func (o *CreateCreditPayPalOrderDto) GetPackageIdOk() (*string, bool)`

GetPackageIdOk returns a tuple with the PackageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackageId

`func (o *CreateCreditPayPalOrderDto) SetPackageId(v string)`

SetPackageId sets PackageId field to given value.


### GetReturnUrl

`func (o *CreateCreditPayPalOrderDto) GetReturnUrl() string`

GetReturnUrl returns the ReturnUrl field if non-nil, zero value otherwise.

### GetReturnUrlOk

`func (o *CreateCreditPayPalOrderDto) GetReturnUrlOk() (*string, bool)`

GetReturnUrlOk returns a tuple with the ReturnUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnUrl

`func (o *CreateCreditPayPalOrderDto) SetReturnUrl(v string)`

SetReturnUrl sets ReturnUrl field to given value.

### HasReturnUrl

`func (o *CreateCreditPayPalOrderDto) HasReturnUrl() bool`

HasReturnUrl returns a boolean if a field has been set.

### SetReturnUrlNil

`func (o *CreateCreditPayPalOrderDto) SetReturnUrlNil(b bool)`

 SetReturnUrlNil sets the value for ReturnUrl to be an explicit nil

### UnsetReturnUrl
`func (o *CreateCreditPayPalOrderDto) UnsetReturnUrl()`

UnsetReturnUrl ensures that no value is present for ReturnUrl, not even an explicit nil
### GetCancelUrl

`func (o *CreateCreditPayPalOrderDto) GetCancelUrl() string`

GetCancelUrl returns the CancelUrl field if non-nil, zero value otherwise.

### GetCancelUrlOk

`func (o *CreateCreditPayPalOrderDto) GetCancelUrlOk() (*string, bool)`

GetCancelUrlOk returns a tuple with the CancelUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCancelUrl

`func (o *CreateCreditPayPalOrderDto) SetCancelUrl(v string)`

SetCancelUrl sets CancelUrl field to given value.

### HasCancelUrl

`func (o *CreateCreditPayPalOrderDto) HasCancelUrl() bool`

HasCancelUrl returns a boolean if a field has been set.

### SetCancelUrlNil

`func (o *CreateCreditPayPalOrderDto) SetCancelUrlNil(b bool)`

 SetCancelUrlNil sets the value for CancelUrl to be an explicit nil

### UnsetCancelUrl
`func (o *CreateCreditPayPalOrderDto) UnsetCancelUrl()`

UnsetCancelUrl ensures that no value is present for CancelUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


