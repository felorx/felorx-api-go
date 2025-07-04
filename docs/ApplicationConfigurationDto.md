# ApplicationConfigurationDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Localization** | Pointer to [**ApplicationLocalizationConfigurationDto**](ApplicationLocalizationConfigurationDto.md) |  | [optional] 
**Auth** | Pointer to [**ApplicationAuthConfigurationDto**](ApplicationAuthConfigurationDto.md) |  | [optional] 
**Setting** | Pointer to [**ApplicationSettingConfigurationDto**](ApplicationSettingConfigurationDto.md) |  | [optional] 
**CurrentUser** | Pointer to [**CurrentUserDto**](CurrentUserDto.md) |  | [optional] 
**Features** | Pointer to [**ApplicationFeatureConfigurationDto**](ApplicationFeatureConfigurationDto.md) |  | [optional] 
**GlobalFeatures** | Pointer to [**ApplicationGlobalFeatureConfigurationDto**](ApplicationGlobalFeatureConfigurationDto.md) |  | [optional] 
**MultiTenancy** | Pointer to [**MultiTenancyInfoDto**](MultiTenancyInfoDto.md) |  | [optional] 
**CurrentTenant** | Pointer to [**CurrentTenantDto**](CurrentTenantDto.md) |  | [optional] 
**Timing** | Pointer to [**TimingDto**](TimingDto.md) |  | [optional] 
**Clock** | Pointer to [**ClockDto**](ClockDto.md) |  | [optional] 
**ObjectExtensions** | Pointer to [**ObjectExtensionsDto**](ObjectExtensionsDto.md) |  | [optional] 
**ExtraProperties** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewApplicationConfigurationDto

`func NewApplicationConfigurationDto() *ApplicationConfigurationDto`

NewApplicationConfigurationDto instantiates a new ApplicationConfigurationDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApplicationConfigurationDtoWithDefaults

`func NewApplicationConfigurationDtoWithDefaults() *ApplicationConfigurationDto`

NewApplicationConfigurationDtoWithDefaults instantiates a new ApplicationConfigurationDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLocalization

`func (o *ApplicationConfigurationDto) GetLocalization() ApplicationLocalizationConfigurationDto`

GetLocalization returns the Localization field if non-nil, zero value otherwise.

### GetLocalizationOk

`func (o *ApplicationConfigurationDto) GetLocalizationOk() (*ApplicationLocalizationConfigurationDto, bool)`

GetLocalizationOk returns a tuple with the Localization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocalization

`func (o *ApplicationConfigurationDto) SetLocalization(v ApplicationLocalizationConfigurationDto)`

SetLocalization sets Localization field to given value.

### HasLocalization

`func (o *ApplicationConfigurationDto) HasLocalization() bool`

HasLocalization returns a boolean if a field has been set.

### GetAuth

`func (o *ApplicationConfigurationDto) GetAuth() ApplicationAuthConfigurationDto`

GetAuth returns the Auth field if non-nil, zero value otherwise.

### GetAuthOk

`func (o *ApplicationConfigurationDto) GetAuthOk() (*ApplicationAuthConfigurationDto, bool)`

GetAuthOk returns a tuple with the Auth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuth

`func (o *ApplicationConfigurationDto) SetAuth(v ApplicationAuthConfigurationDto)`

SetAuth sets Auth field to given value.

### HasAuth

`func (o *ApplicationConfigurationDto) HasAuth() bool`

HasAuth returns a boolean if a field has been set.

### GetSetting

`func (o *ApplicationConfigurationDto) GetSetting() ApplicationSettingConfigurationDto`

GetSetting returns the Setting field if non-nil, zero value otherwise.

### GetSettingOk

`func (o *ApplicationConfigurationDto) GetSettingOk() (*ApplicationSettingConfigurationDto, bool)`

GetSettingOk returns a tuple with the Setting field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSetting

`func (o *ApplicationConfigurationDto) SetSetting(v ApplicationSettingConfigurationDto)`

SetSetting sets Setting field to given value.

### HasSetting

`func (o *ApplicationConfigurationDto) HasSetting() bool`

HasSetting returns a boolean if a field has been set.

### GetCurrentUser

`func (o *ApplicationConfigurationDto) GetCurrentUser() CurrentUserDto`

GetCurrentUser returns the CurrentUser field if non-nil, zero value otherwise.

### GetCurrentUserOk

`func (o *ApplicationConfigurationDto) GetCurrentUserOk() (*CurrentUserDto, bool)`

GetCurrentUserOk returns a tuple with the CurrentUser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentUser

`func (o *ApplicationConfigurationDto) SetCurrentUser(v CurrentUserDto)`

SetCurrentUser sets CurrentUser field to given value.

### HasCurrentUser

`func (o *ApplicationConfigurationDto) HasCurrentUser() bool`

HasCurrentUser returns a boolean if a field has been set.

### GetFeatures

`func (o *ApplicationConfigurationDto) GetFeatures() ApplicationFeatureConfigurationDto`

GetFeatures returns the Features field if non-nil, zero value otherwise.

### GetFeaturesOk

`func (o *ApplicationConfigurationDto) GetFeaturesOk() (*ApplicationFeatureConfigurationDto, bool)`

GetFeaturesOk returns a tuple with the Features field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatures

`func (o *ApplicationConfigurationDto) SetFeatures(v ApplicationFeatureConfigurationDto)`

SetFeatures sets Features field to given value.

### HasFeatures

`func (o *ApplicationConfigurationDto) HasFeatures() bool`

HasFeatures returns a boolean if a field has been set.

### GetGlobalFeatures

`func (o *ApplicationConfigurationDto) GetGlobalFeatures() ApplicationGlobalFeatureConfigurationDto`

GetGlobalFeatures returns the GlobalFeatures field if non-nil, zero value otherwise.

### GetGlobalFeaturesOk

`func (o *ApplicationConfigurationDto) GetGlobalFeaturesOk() (*ApplicationGlobalFeatureConfigurationDto, bool)`

GetGlobalFeaturesOk returns a tuple with the GlobalFeatures field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGlobalFeatures

`func (o *ApplicationConfigurationDto) SetGlobalFeatures(v ApplicationGlobalFeatureConfigurationDto)`

SetGlobalFeatures sets GlobalFeatures field to given value.

### HasGlobalFeatures

`func (o *ApplicationConfigurationDto) HasGlobalFeatures() bool`

HasGlobalFeatures returns a boolean if a field has been set.

### GetMultiTenancy

`func (o *ApplicationConfigurationDto) GetMultiTenancy() MultiTenancyInfoDto`

GetMultiTenancy returns the MultiTenancy field if non-nil, zero value otherwise.

### GetMultiTenancyOk

`func (o *ApplicationConfigurationDto) GetMultiTenancyOk() (*MultiTenancyInfoDto, bool)`

GetMultiTenancyOk returns a tuple with the MultiTenancy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMultiTenancy

`func (o *ApplicationConfigurationDto) SetMultiTenancy(v MultiTenancyInfoDto)`

SetMultiTenancy sets MultiTenancy field to given value.

### HasMultiTenancy

`func (o *ApplicationConfigurationDto) HasMultiTenancy() bool`

HasMultiTenancy returns a boolean if a field has been set.

### GetCurrentTenant

`func (o *ApplicationConfigurationDto) GetCurrentTenant() CurrentTenantDto`

GetCurrentTenant returns the CurrentTenant field if non-nil, zero value otherwise.

### GetCurrentTenantOk

`func (o *ApplicationConfigurationDto) GetCurrentTenantOk() (*CurrentTenantDto, bool)`

GetCurrentTenantOk returns a tuple with the CurrentTenant field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentTenant

`func (o *ApplicationConfigurationDto) SetCurrentTenant(v CurrentTenantDto)`

SetCurrentTenant sets CurrentTenant field to given value.

### HasCurrentTenant

`func (o *ApplicationConfigurationDto) HasCurrentTenant() bool`

HasCurrentTenant returns a boolean if a field has been set.

### GetTiming

`func (o *ApplicationConfigurationDto) GetTiming() TimingDto`

GetTiming returns the Timing field if non-nil, zero value otherwise.

### GetTimingOk

`func (o *ApplicationConfigurationDto) GetTimingOk() (*TimingDto, bool)`

GetTimingOk returns a tuple with the Timing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTiming

`func (o *ApplicationConfigurationDto) SetTiming(v TimingDto)`

SetTiming sets Timing field to given value.

### HasTiming

`func (o *ApplicationConfigurationDto) HasTiming() bool`

HasTiming returns a boolean if a field has been set.

### GetClock

`func (o *ApplicationConfigurationDto) GetClock() ClockDto`

GetClock returns the Clock field if non-nil, zero value otherwise.

### GetClockOk

`func (o *ApplicationConfigurationDto) GetClockOk() (*ClockDto, bool)`

GetClockOk returns a tuple with the Clock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClock

`func (o *ApplicationConfigurationDto) SetClock(v ClockDto)`

SetClock sets Clock field to given value.

### HasClock

`func (o *ApplicationConfigurationDto) HasClock() bool`

HasClock returns a boolean if a field has been set.

### GetObjectExtensions

`func (o *ApplicationConfigurationDto) GetObjectExtensions() ObjectExtensionsDto`

GetObjectExtensions returns the ObjectExtensions field if non-nil, zero value otherwise.

### GetObjectExtensionsOk

`func (o *ApplicationConfigurationDto) GetObjectExtensionsOk() (*ObjectExtensionsDto, bool)`

GetObjectExtensionsOk returns a tuple with the ObjectExtensions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObjectExtensions

`func (o *ApplicationConfigurationDto) SetObjectExtensions(v ObjectExtensionsDto)`

SetObjectExtensions sets ObjectExtensions field to given value.

### HasObjectExtensions

`func (o *ApplicationConfigurationDto) HasObjectExtensions() bool`

HasObjectExtensions returns a boolean if a field has been set.

### GetExtraProperties

`func (o *ApplicationConfigurationDto) GetExtraProperties() map[string]interface{}`

GetExtraProperties returns the ExtraProperties field if non-nil, zero value otherwise.

### GetExtraPropertiesOk

`func (o *ApplicationConfigurationDto) GetExtraPropertiesOk() (*map[string]interface{}, bool)`

GetExtraPropertiesOk returns a tuple with the ExtraProperties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtraProperties

`func (o *ApplicationConfigurationDto) SetExtraProperties(v map[string]interface{})`

SetExtraProperties sets ExtraProperties field to given value.

### HasExtraProperties

`func (o *ApplicationConfigurationDto) HasExtraProperties() bool`

HasExtraProperties returns a boolean if a field has been set.

### SetExtraPropertiesNil

`func (o *ApplicationConfigurationDto) SetExtraPropertiesNil(b bool)`

 SetExtraPropertiesNil sets the value for ExtraProperties to be an explicit nil

### UnsetExtraProperties
`func (o *ApplicationConfigurationDto) UnsetExtraProperties()`

UnsetExtraProperties ensures that no value is present for ExtraProperties, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


