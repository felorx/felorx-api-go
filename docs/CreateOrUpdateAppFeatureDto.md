# CreateOrUpdateAppFeatureDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppId** | Pointer to **string** |  | [optional]
**Name** | Pointer to **NullableString** |  | [optional]
**Sort** | Pointer to **int32** |  | [optional]
**FeatureLocales** | Pointer to [**[]CreateOrUpdateAppFeatureLocaleDto**](CreateOrUpdateAppFeatureLocaleDto.md) |  | [optional]

## Methods

### NewCreateOrUpdateAppFeatureDto

`func NewCreateOrUpdateAppFeatureDto() *CreateOrUpdateAppFeatureDto`

NewCreateOrUpdateAppFeatureDto instantiates a new CreateOrUpdateAppFeatureDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrUpdateAppFeatureDtoWithDefaults

`func NewCreateOrUpdateAppFeatureDtoWithDefaults() *CreateOrUpdateAppFeatureDto`

NewCreateOrUpdateAppFeatureDtoWithDefaults instantiates a new CreateOrUpdateAppFeatureDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppId

`func (o *CreateOrUpdateAppFeatureDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *CreateOrUpdateAppFeatureDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *CreateOrUpdateAppFeatureDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *CreateOrUpdateAppFeatureDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetName

`func (o *CreateOrUpdateAppFeatureDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateOrUpdateAppFeatureDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateOrUpdateAppFeatureDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CreateOrUpdateAppFeatureDto) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *CreateOrUpdateAppFeatureDto) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *CreateOrUpdateAppFeatureDto) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetSort

`func (o *CreateOrUpdateAppFeatureDto) GetSort() int32`

GetSort returns the Sort field if non-nil, zero value otherwise.

### GetSortOk

`func (o *CreateOrUpdateAppFeatureDto) GetSortOk() (*int32, bool)`

GetSortOk returns a tuple with the Sort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSort

`func (o *CreateOrUpdateAppFeatureDto) SetSort(v int32)`

SetSort sets Sort field to given value.

### HasSort

`func (o *CreateOrUpdateAppFeatureDto) HasSort() bool`

HasSort returns a boolean if a field has been set.

### GetFeatureLocales

`func (o *CreateOrUpdateAppFeatureDto) GetFeatureLocales() []CreateOrUpdateAppFeatureLocaleDto`

GetFeatureLocales returns the FeatureLocales field if non-nil, zero value otherwise.

### GetFeatureLocalesOk

`func (o *CreateOrUpdateAppFeatureDto) GetFeatureLocalesOk() (*[]CreateOrUpdateAppFeatureLocaleDto, bool)`

GetFeatureLocalesOk returns a tuple with the FeatureLocales field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatureLocales

`func (o *CreateOrUpdateAppFeatureDto) SetFeatureLocales(v []CreateOrUpdateAppFeatureLocaleDto)`

SetFeatureLocales sets FeatureLocales field to given value.

### HasFeatureLocales

`func (o *CreateOrUpdateAppFeatureDto) HasFeatureLocales() bool`

HasFeatureLocales returns a boolean if a field has been set.

### SetFeatureLocalesNil

`func (o *CreateOrUpdateAppFeatureDto) SetFeatureLocalesNil(b bool)`

 SetFeatureLocalesNil sets the value for FeatureLocales to be an explicit nil

### UnsetFeatureLocales
`func (o *CreateOrUpdateAppFeatureDto) UnsetFeatureLocales()`

UnsetFeatureLocales ensures that no value is present for FeatureLocales, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


