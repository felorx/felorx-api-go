# BindDeviceDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Token** | Pointer to **NullableString** |  | [optional] 
**IsPhysicalDevice** | Pointer to **bool** |  | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 
**Platform** | Pointer to [**AppPlatform**](AppPlatform.md) |  | [optional] 
**Brand** | Pointer to **NullableString** |  | [optional] 
**SystemVersion** | Pointer to **NullableString** |  | [optional] 
**AppName** | Pointer to **NullableString** | 发起绑定的应用名。服务端优先使用访问令牌中的可信 app_name 声明。 | [optional] 

## Methods

### NewBindDeviceDto

`func NewBindDeviceDto() *BindDeviceDto`

NewBindDeviceDto instantiates a new BindDeviceDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBindDeviceDtoWithDefaults

`func NewBindDeviceDtoWithDefaults() *BindDeviceDto`

NewBindDeviceDtoWithDefaults instantiates a new BindDeviceDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetToken

`func (o *BindDeviceDto) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *BindDeviceDto) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *BindDeviceDto) SetToken(v string)`

SetToken sets Token field to given value.

### HasToken

`func (o *BindDeviceDto) HasToken() bool`

HasToken returns a boolean if a field has been set.

### SetTokenNil

`func (o *BindDeviceDto) SetTokenNil(b bool)`

 SetTokenNil sets the value for Token to be an explicit nil

### UnsetToken
`func (o *BindDeviceDto) UnsetToken()`

UnsetToken ensures that no value is present for Token, not even an explicit nil
### GetIsPhysicalDevice

`func (o *BindDeviceDto) GetIsPhysicalDevice() bool`

GetIsPhysicalDevice returns the IsPhysicalDevice field if non-nil, zero value otherwise.

### GetIsPhysicalDeviceOk

`func (o *BindDeviceDto) GetIsPhysicalDeviceOk() (*bool, bool)`

GetIsPhysicalDeviceOk returns a tuple with the IsPhysicalDevice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPhysicalDevice

`func (o *BindDeviceDto) SetIsPhysicalDevice(v bool)`

SetIsPhysicalDevice sets IsPhysicalDevice field to given value.

### HasIsPhysicalDevice

`func (o *BindDeviceDto) HasIsPhysicalDevice() bool`

HasIsPhysicalDevice returns a boolean if a field has been set.

### GetName

`func (o *BindDeviceDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *BindDeviceDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *BindDeviceDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *BindDeviceDto) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *BindDeviceDto) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *BindDeviceDto) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetPlatform

`func (o *BindDeviceDto) GetPlatform() AppPlatform`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *BindDeviceDto) GetPlatformOk() (*AppPlatform, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *BindDeviceDto) SetPlatform(v AppPlatform)`

SetPlatform sets Platform field to given value.

### HasPlatform

`func (o *BindDeviceDto) HasPlatform() bool`

HasPlatform returns a boolean if a field has been set.

### GetBrand

`func (o *BindDeviceDto) GetBrand() string`

GetBrand returns the Brand field if non-nil, zero value otherwise.

### GetBrandOk

`func (o *BindDeviceDto) GetBrandOk() (*string, bool)`

GetBrandOk returns a tuple with the Brand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrand

`func (o *BindDeviceDto) SetBrand(v string)`

SetBrand sets Brand field to given value.

### HasBrand

`func (o *BindDeviceDto) HasBrand() bool`

HasBrand returns a boolean if a field has been set.

### SetBrandNil

`func (o *BindDeviceDto) SetBrandNil(b bool)`

 SetBrandNil sets the value for Brand to be an explicit nil

### UnsetBrand
`func (o *BindDeviceDto) UnsetBrand()`

UnsetBrand ensures that no value is present for Brand, not even an explicit nil
### GetSystemVersion

`func (o *BindDeviceDto) GetSystemVersion() string`

GetSystemVersion returns the SystemVersion field if non-nil, zero value otherwise.

### GetSystemVersionOk

`func (o *BindDeviceDto) GetSystemVersionOk() (*string, bool)`

GetSystemVersionOk returns a tuple with the SystemVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemVersion

`func (o *BindDeviceDto) SetSystemVersion(v string)`

SetSystemVersion sets SystemVersion field to given value.

### HasSystemVersion

`func (o *BindDeviceDto) HasSystemVersion() bool`

HasSystemVersion returns a boolean if a field has been set.

### SetSystemVersionNil

`func (o *BindDeviceDto) SetSystemVersionNil(b bool)`

 SetSystemVersionNil sets the value for SystemVersion to be an explicit nil

### UnsetSystemVersion
`func (o *BindDeviceDto) UnsetSystemVersion()`

UnsetSystemVersion ensures that no value is present for SystemVersion, not even an explicit nil
### GetAppName

`func (o *BindDeviceDto) GetAppName() string`

GetAppName returns the AppName field if non-nil, zero value otherwise.

### GetAppNameOk

`func (o *BindDeviceDto) GetAppNameOk() (*string, bool)`

GetAppNameOk returns a tuple with the AppName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppName

`func (o *BindDeviceDto) SetAppName(v string)`

SetAppName sets AppName field to given value.

### HasAppName

`func (o *BindDeviceDto) HasAppName() bool`

HasAppName returns a boolean if a field has been set.

### SetAppNameNil

`func (o *BindDeviceDto) SetAppNameNil(b bool)`

 SetAppNameNil sets the value for AppName to be an explicit nil

### UnsetAppName
`func (o *BindDeviceDto) UnsetAppName()`

UnsetAppName ensures that no value is present for AppName, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


