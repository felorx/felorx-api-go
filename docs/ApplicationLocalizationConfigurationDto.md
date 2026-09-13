# ApplicationLocalizationConfigurationDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Values** | Pointer to **map[string]map[string]string** |  | [optional] 
**Resources** | Pointer to [**map[string]ApplicationLocalizationResourceDto**](ApplicationLocalizationResourceDto.md) |  | [optional] 
**Languages** | Pointer to [**[]LanguageInfo**](LanguageInfo.md) |  | [optional] 
**CurrentCulture** | Pointer to [**CurrentCultureDto**](CurrentCultureDto.md) |  | [optional] 
**DefaultResourceName** | Pointer to **NullableString** |  | [optional] 
**LanguagesMap** | Pointer to [**map[string][]NameValue**](array.md) |  | [optional] 
**LanguageFilesMap** | Pointer to [**map[string][]NameValue**](array.md) |  | [optional] 

## Methods

### NewApplicationLocalizationConfigurationDto

`func NewApplicationLocalizationConfigurationDto() *ApplicationLocalizationConfigurationDto`

NewApplicationLocalizationConfigurationDto instantiates a new ApplicationLocalizationConfigurationDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApplicationLocalizationConfigurationDtoWithDefaults

`func NewApplicationLocalizationConfigurationDtoWithDefaults() *ApplicationLocalizationConfigurationDto`

NewApplicationLocalizationConfigurationDtoWithDefaults instantiates a new ApplicationLocalizationConfigurationDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetValues

`func (o *ApplicationLocalizationConfigurationDto) GetValues() map[string]map[string]string`

GetValues returns the Values field if non-nil, zero value otherwise.

### GetValuesOk

`func (o *ApplicationLocalizationConfigurationDto) GetValuesOk() (*map[string]map[string]string, bool)`

GetValuesOk returns a tuple with the Values field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValues

`func (o *ApplicationLocalizationConfigurationDto) SetValues(v map[string]map[string]string)`

SetValues sets Values field to given value.

### HasValues

`func (o *ApplicationLocalizationConfigurationDto) HasValues() bool`

HasValues returns a boolean if a field has been set.

### SetValuesNil

`func (o *ApplicationLocalizationConfigurationDto) SetValuesNil(b bool)`

 SetValuesNil sets the value for Values to be an explicit nil

### UnsetValues
`func (o *ApplicationLocalizationConfigurationDto) UnsetValues()`

UnsetValues ensures that no value is present for Values, not even an explicit nil
### GetResources

`func (o *ApplicationLocalizationConfigurationDto) GetResources() map[string]ApplicationLocalizationResourceDto`

GetResources returns the Resources field if non-nil, zero value otherwise.

### GetResourcesOk

`func (o *ApplicationLocalizationConfigurationDto) GetResourcesOk() (*map[string]ApplicationLocalizationResourceDto, bool)`

GetResourcesOk returns a tuple with the Resources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResources

`func (o *ApplicationLocalizationConfigurationDto) SetResources(v map[string]ApplicationLocalizationResourceDto)`

SetResources sets Resources field to given value.

### HasResources

`func (o *ApplicationLocalizationConfigurationDto) HasResources() bool`

HasResources returns a boolean if a field has been set.

### SetResourcesNil

`func (o *ApplicationLocalizationConfigurationDto) SetResourcesNil(b bool)`

 SetResourcesNil sets the value for Resources to be an explicit nil

### UnsetResources
`func (o *ApplicationLocalizationConfigurationDto) UnsetResources()`

UnsetResources ensures that no value is present for Resources, not even an explicit nil
### GetLanguages

`func (o *ApplicationLocalizationConfigurationDto) GetLanguages() []LanguageInfo`

GetLanguages returns the Languages field if non-nil, zero value otherwise.

### GetLanguagesOk

`func (o *ApplicationLocalizationConfigurationDto) GetLanguagesOk() (*[]LanguageInfo, bool)`

GetLanguagesOk returns a tuple with the Languages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguages

`func (o *ApplicationLocalizationConfigurationDto) SetLanguages(v []LanguageInfo)`

SetLanguages sets Languages field to given value.

### HasLanguages

`func (o *ApplicationLocalizationConfigurationDto) HasLanguages() bool`

HasLanguages returns a boolean if a field has been set.

### SetLanguagesNil

`func (o *ApplicationLocalizationConfigurationDto) SetLanguagesNil(b bool)`

 SetLanguagesNil sets the value for Languages to be an explicit nil

### UnsetLanguages
`func (o *ApplicationLocalizationConfigurationDto) UnsetLanguages()`

UnsetLanguages ensures that no value is present for Languages, not even an explicit nil
### GetCurrentCulture

`func (o *ApplicationLocalizationConfigurationDto) GetCurrentCulture() CurrentCultureDto`

GetCurrentCulture returns the CurrentCulture field if non-nil, zero value otherwise.

### GetCurrentCultureOk

`func (o *ApplicationLocalizationConfigurationDto) GetCurrentCultureOk() (*CurrentCultureDto, bool)`

GetCurrentCultureOk returns a tuple with the CurrentCulture field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentCulture

`func (o *ApplicationLocalizationConfigurationDto) SetCurrentCulture(v CurrentCultureDto)`

SetCurrentCulture sets CurrentCulture field to given value.

### HasCurrentCulture

`func (o *ApplicationLocalizationConfigurationDto) HasCurrentCulture() bool`

HasCurrentCulture returns a boolean if a field has been set.

### GetDefaultResourceName

`func (o *ApplicationLocalizationConfigurationDto) GetDefaultResourceName() string`

GetDefaultResourceName returns the DefaultResourceName field if non-nil, zero value otherwise.

### GetDefaultResourceNameOk

`func (o *ApplicationLocalizationConfigurationDto) GetDefaultResourceNameOk() (*string, bool)`

GetDefaultResourceNameOk returns a tuple with the DefaultResourceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultResourceName

`func (o *ApplicationLocalizationConfigurationDto) SetDefaultResourceName(v string)`

SetDefaultResourceName sets DefaultResourceName field to given value.

### HasDefaultResourceName

`func (o *ApplicationLocalizationConfigurationDto) HasDefaultResourceName() bool`

HasDefaultResourceName returns a boolean if a field has been set.

### SetDefaultResourceNameNil

`func (o *ApplicationLocalizationConfigurationDto) SetDefaultResourceNameNil(b bool)`

 SetDefaultResourceNameNil sets the value for DefaultResourceName to be an explicit nil

### UnsetDefaultResourceName
`func (o *ApplicationLocalizationConfigurationDto) UnsetDefaultResourceName()`

UnsetDefaultResourceName ensures that no value is present for DefaultResourceName, not even an explicit nil
### GetLanguagesMap

`func (o *ApplicationLocalizationConfigurationDto) GetLanguagesMap() map[string][]NameValue`

GetLanguagesMap returns the LanguagesMap field if non-nil, zero value otherwise.

### GetLanguagesMapOk

`func (o *ApplicationLocalizationConfigurationDto) GetLanguagesMapOk() (*map[string][]NameValue, bool)`

GetLanguagesMapOk returns a tuple with the LanguagesMap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguagesMap

`func (o *ApplicationLocalizationConfigurationDto) SetLanguagesMap(v map[string][]NameValue)`

SetLanguagesMap sets LanguagesMap field to given value.

### HasLanguagesMap

`func (o *ApplicationLocalizationConfigurationDto) HasLanguagesMap() bool`

HasLanguagesMap returns a boolean if a field has been set.

### SetLanguagesMapNil

`func (o *ApplicationLocalizationConfigurationDto) SetLanguagesMapNil(b bool)`

 SetLanguagesMapNil sets the value for LanguagesMap to be an explicit nil

### UnsetLanguagesMap
`func (o *ApplicationLocalizationConfigurationDto) UnsetLanguagesMap()`

UnsetLanguagesMap ensures that no value is present for LanguagesMap, not even an explicit nil
### GetLanguageFilesMap

`func (o *ApplicationLocalizationConfigurationDto) GetLanguageFilesMap() map[string][]NameValue`

GetLanguageFilesMap returns the LanguageFilesMap field if non-nil, zero value otherwise.

### GetLanguageFilesMapOk

`func (o *ApplicationLocalizationConfigurationDto) GetLanguageFilesMapOk() (*map[string][]NameValue, bool)`

GetLanguageFilesMapOk returns a tuple with the LanguageFilesMap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguageFilesMap

`func (o *ApplicationLocalizationConfigurationDto) SetLanguageFilesMap(v map[string][]NameValue)`

SetLanguageFilesMap sets LanguageFilesMap field to given value.

### HasLanguageFilesMap

`func (o *ApplicationLocalizationConfigurationDto) HasLanguageFilesMap() bool`

HasLanguageFilesMap returns a boolean if a field has been set.

### SetLanguageFilesMapNil

`func (o *ApplicationLocalizationConfigurationDto) SetLanguageFilesMapNil(b bool)`

 SetLanguageFilesMapNil sets the value for LanguageFilesMap to be an explicit nil

### UnsetLanguageFilesMap
`func (o *ApplicationLocalizationConfigurationDto) UnsetLanguageFilesMap()`

UnsetLanguageFilesMap ensures that no value is present for LanguageFilesMap, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


