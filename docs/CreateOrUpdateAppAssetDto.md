# CreateOrUpdateAppAssetDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppId** | Pointer to **string** |  | [optional]
**AppLocaleId** | Pointer to **string** |  | [optional]
**AppFeatureId** | Pointer to **NullableString** |  | [optional]
**AssetType** | Pointer to [**AppAssetType**](AppAssetType.md) |  | [optional]
**DeviceType** | Pointer to [**AppAssetDeviceType**](AppAssetDeviceType.md) |  | [optional]
**Url** | Pointer to **NullableString** |  | [optional]
**Sort** | Pointer to **int32** |  | [optional]

## Methods

### NewCreateOrUpdateAppAssetDto

`func NewCreateOrUpdateAppAssetDto() *CreateOrUpdateAppAssetDto`

NewCreateOrUpdateAppAssetDto instantiates a new CreateOrUpdateAppAssetDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrUpdateAppAssetDtoWithDefaults

`func NewCreateOrUpdateAppAssetDtoWithDefaults() *CreateOrUpdateAppAssetDto`

NewCreateOrUpdateAppAssetDtoWithDefaults instantiates a new CreateOrUpdateAppAssetDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppId

`func (o *CreateOrUpdateAppAssetDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *CreateOrUpdateAppAssetDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *CreateOrUpdateAppAssetDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *CreateOrUpdateAppAssetDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetAppLocaleId

`func (o *CreateOrUpdateAppAssetDto) GetAppLocaleId() string`

GetAppLocaleId returns the AppLocaleId field if non-nil, zero value otherwise.

### GetAppLocaleIdOk

`func (o *CreateOrUpdateAppAssetDto) GetAppLocaleIdOk() (*string, bool)`

GetAppLocaleIdOk returns a tuple with the AppLocaleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppLocaleId

`func (o *CreateOrUpdateAppAssetDto) SetAppLocaleId(v string)`

SetAppLocaleId sets AppLocaleId field to given value.

### HasAppLocaleId

`func (o *CreateOrUpdateAppAssetDto) HasAppLocaleId() bool`

HasAppLocaleId returns a boolean if a field has been set.

### GetAppFeatureId

`func (o *CreateOrUpdateAppAssetDto) GetAppFeatureId() string`

GetAppFeatureId returns the AppFeatureId field if non-nil, zero value otherwise.

### GetAppFeatureIdOk

`func (o *CreateOrUpdateAppAssetDto) GetAppFeatureIdOk() (*string, bool)`

GetAppFeatureIdOk returns a tuple with the AppFeatureId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppFeatureId

`func (o *CreateOrUpdateAppAssetDto) SetAppFeatureId(v string)`

SetAppFeatureId sets AppFeatureId field to given value.

### HasAppFeatureId

`func (o *CreateOrUpdateAppAssetDto) HasAppFeatureId() bool`

HasAppFeatureId returns a boolean if a field has been set.

### SetAppFeatureIdNil

`func (o *CreateOrUpdateAppAssetDto) SetAppFeatureIdNil(b bool)`

 SetAppFeatureIdNil sets the value for AppFeatureId to be an explicit nil

### UnsetAppFeatureId
`func (o *CreateOrUpdateAppAssetDto) UnsetAppFeatureId()`

UnsetAppFeatureId ensures that no value is present for AppFeatureId, not even an explicit nil
### GetAssetType

`func (o *CreateOrUpdateAppAssetDto) GetAssetType() AppAssetType`

GetAssetType returns the AssetType field if non-nil, zero value otherwise.

### GetAssetTypeOk

`func (o *CreateOrUpdateAppAssetDto) GetAssetTypeOk() (*AppAssetType, bool)`

GetAssetTypeOk returns a tuple with the AssetType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetType

`func (o *CreateOrUpdateAppAssetDto) SetAssetType(v AppAssetType)`

SetAssetType sets AssetType field to given value.

### HasAssetType

`func (o *CreateOrUpdateAppAssetDto) HasAssetType() bool`

HasAssetType returns a boolean if a field has been set.

### GetDeviceType

`func (o *CreateOrUpdateAppAssetDto) GetDeviceType() AppAssetDeviceType`

GetDeviceType returns the DeviceType field if non-nil, zero value otherwise.

### GetDeviceTypeOk

`func (o *CreateOrUpdateAppAssetDto) GetDeviceTypeOk() (*AppAssetDeviceType, bool)`

GetDeviceTypeOk returns a tuple with the DeviceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceType

`func (o *CreateOrUpdateAppAssetDto) SetDeviceType(v AppAssetDeviceType)`

SetDeviceType sets DeviceType field to given value.

### HasDeviceType

`func (o *CreateOrUpdateAppAssetDto) HasDeviceType() bool`

HasDeviceType returns a boolean if a field has been set.

### GetUrl

`func (o *CreateOrUpdateAppAssetDto) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *CreateOrUpdateAppAssetDto) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *CreateOrUpdateAppAssetDto) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *CreateOrUpdateAppAssetDto) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### SetUrlNil

`func (o *CreateOrUpdateAppAssetDto) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *CreateOrUpdateAppAssetDto) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil
### GetSort

`func (o *CreateOrUpdateAppAssetDto) GetSort() int32`

GetSort returns the Sort field if non-nil, zero value otherwise.

### GetSortOk

`func (o *CreateOrUpdateAppAssetDto) GetSortOk() (*int32, bool)`

GetSortOk returns a tuple with the Sort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSort

`func (o *CreateOrUpdateAppAssetDto) SetSort(v int32)`

SetSort sets Sort field to given value.

### HasSort

`func (o *CreateOrUpdateAppAssetDto) HasSort() bool`

HasSort returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


