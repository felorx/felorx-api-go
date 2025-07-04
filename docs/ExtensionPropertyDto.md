# ExtensionPropertyDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **NullableString** |  | [optional] 
**TypeSimple** | Pointer to **NullableString** |  | [optional] 
**DisplayName** | Pointer to [**LocalizableStringDto**](LocalizableStringDto.md) |  | [optional] 
**Api** | Pointer to [**ExtensionPropertyApiDto**](ExtensionPropertyApiDto.md) |  | [optional] 
**Ui** | Pointer to [**ExtensionPropertyUiDto**](ExtensionPropertyUiDto.md) |  | [optional] 
**Attributes** | Pointer to [**[]ExtensionPropertyAttributeDto**](ExtensionPropertyAttributeDto.md) |  | [optional] 
**Configuration** | Pointer to **map[string]interface{}** |  | [optional] 
**DefaultValue** | Pointer to **interface{}** |  | [optional] 

## Methods

### NewExtensionPropertyDto

`func NewExtensionPropertyDto() *ExtensionPropertyDto`

NewExtensionPropertyDto instantiates a new ExtensionPropertyDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExtensionPropertyDtoWithDefaults

`func NewExtensionPropertyDtoWithDefaults() *ExtensionPropertyDto`

NewExtensionPropertyDtoWithDefaults instantiates a new ExtensionPropertyDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ExtensionPropertyDto) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ExtensionPropertyDto) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ExtensionPropertyDto) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ExtensionPropertyDto) HasType() bool`

HasType returns a boolean if a field has been set.

### SetTypeNil

`func (o *ExtensionPropertyDto) SetTypeNil(b bool)`

 SetTypeNil sets the value for Type to be an explicit nil

### UnsetType
`func (o *ExtensionPropertyDto) UnsetType()`

UnsetType ensures that no value is present for Type, not even an explicit nil
### GetTypeSimple

`func (o *ExtensionPropertyDto) GetTypeSimple() string`

GetTypeSimple returns the TypeSimple field if non-nil, zero value otherwise.

### GetTypeSimpleOk

`func (o *ExtensionPropertyDto) GetTypeSimpleOk() (*string, bool)`

GetTypeSimpleOk returns a tuple with the TypeSimple field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTypeSimple

`func (o *ExtensionPropertyDto) SetTypeSimple(v string)`

SetTypeSimple sets TypeSimple field to given value.

### HasTypeSimple

`func (o *ExtensionPropertyDto) HasTypeSimple() bool`

HasTypeSimple returns a boolean if a field has been set.

### SetTypeSimpleNil

`func (o *ExtensionPropertyDto) SetTypeSimpleNil(b bool)`

 SetTypeSimpleNil sets the value for TypeSimple to be an explicit nil

### UnsetTypeSimple
`func (o *ExtensionPropertyDto) UnsetTypeSimple()`

UnsetTypeSimple ensures that no value is present for TypeSimple, not even an explicit nil
### GetDisplayName

`func (o *ExtensionPropertyDto) GetDisplayName() LocalizableStringDto`

GetDisplayName returns the DisplayName field if non-nil, zero value otherwise.

### GetDisplayNameOk

`func (o *ExtensionPropertyDto) GetDisplayNameOk() (*LocalizableStringDto, bool)`

GetDisplayNameOk returns a tuple with the DisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayName

`func (o *ExtensionPropertyDto) SetDisplayName(v LocalizableStringDto)`

SetDisplayName sets DisplayName field to given value.

### HasDisplayName

`func (o *ExtensionPropertyDto) HasDisplayName() bool`

HasDisplayName returns a boolean if a field has been set.

### GetApi

`func (o *ExtensionPropertyDto) GetApi() ExtensionPropertyApiDto`

GetApi returns the Api field if non-nil, zero value otherwise.

### GetApiOk

`func (o *ExtensionPropertyDto) GetApiOk() (*ExtensionPropertyApiDto, bool)`

GetApiOk returns a tuple with the Api field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApi

`func (o *ExtensionPropertyDto) SetApi(v ExtensionPropertyApiDto)`

SetApi sets Api field to given value.

### HasApi

`func (o *ExtensionPropertyDto) HasApi() bool`

HasApi returns a boolean if a field has been set.

### GetUi

`func (o *ExtensionPropertyDto) GetUi() ExtensionPropertyUiDto`

GetUi returns the Ui field if non-nil, zero value otherwise.

### GetUiOk

`func (o *ExtensionPropertyDto) GetUiOk() (*ExtensionPropertyUiDto, bool)`

GetUiOk returns a tuple with the Ui field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUi

`func (o *ExtensionPropertyDto) SetUi(v ExtensionPropertyUiDto)`

SetUi sets Ui field to given value.

### HasUi

`func (o *ExtensionPropertyDto) HasUi() bool`

HasUi returns a boolean if a field has been set.

### GetAttributes

`func (o *ExtensionPropertyDto) GetAttributes() []ExtensionPropertyAttributeDto`

GetAttributes returns the Attributes field if non-nil, zero value otherwise.

### GetAttributesOk

`func (o *ExtensionPropertyDto) GetAttributesOk() (*[]ExtensionPropertyAttributeDto, bool)`

GetAttributesOk returns a tuple with the Attributes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttributes

`func (o *ExtensionPropertyDto) SetAttributes(v []ExtensionPropertyAttributeDto)`

SetAttributes sets Attributes field to given value.

### HasAttributes

`func (o *ExtensionPropertyDto) HasAttributes() bool`

HasAttributes returns a boolean if a field has been set.

### SetAttributesNil

`func (o *ExtensionPropertyDto) SetAttributesNil(b bool)`

 SetAttributesNil sets the value for Attributes to be an explicit nil

### UnsetAttributes
`func (o *ExtensionPropertyDto) UnsetAttributes()`

UnsetAttributes ensures that no value is present for Attributes, not even an explicit nil
### GetConfiguration

`func (o *ExtensionPropertyDto) GetConfiguration() map[string]interface{}`

GetConfiguration returns the Configuration field if non-nil, zero value otherwise.

### GetConfigurationOk

`func (o *ExtensionPropertyDto) GetConfigurationOk() (*map[string]interface{}, bool)`

GetConfigurationOk returns a tuple with the Configuration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfiguration

`func (o *ExtensionPropertyDto) SetConfiguration(v map[string]interface{})`

SetConfiguration sets Configuration field to given value.

### HasConfiguration

`func (o *ExtensionPropertyDto) HasConfiguration() bool`

HasConfiguration returns a boolean if a field has been set.

### SetConfigurationNil

`func (o *ExtensionPropertyDto) SetConfigurationNil(b bool)`

 SetConfigurationNil sets the value for Configuration to be an explicit nil

### UnsetConfiguration
`func (o *ExtensionPropertyDto) UnsetConfiguration()`

UnsetConfiguration ensures that no value is present for Configuration, not even an explicit nil
### GetDefaultValue

`func (o *ExtensionPropertyDto) GetDefaultValue() interface{}`

GetDefaultValue returns the DefaultValue field if non-nil, zero value otherwise.

### GetDefaultValueOk

`func (o *ExtensionPropertyDto) GetDefaultValueOk() (*interface{}, bool)`

GetDefaultValueOk returns a tuple with the DefaultValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultValue

`func (o *ExtensionPropertyDto) SetDefaultValue(v interface{})`

SetDefaultValue sets DefaultValue field to given value.

### HasDefaultValue

`func (o *ExtensionPropertyDto) HasDefaultValue() bool`

HasDefaultValue returns a boolean if a field has been set.

### SetDefaultValueNil

`func (o *ExtensionPropertyDto) SetDefaultValueNil(b bool)`

 SetDefaultValueNil sets the value for DefaultValue to be an explicit nil

### UnsetDefaultValue
`func (o *ExtensionPropertyDto) UnsetDefaultValue()`

UnsetDefaultValue ensures that no value is present for DefaultValue, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


