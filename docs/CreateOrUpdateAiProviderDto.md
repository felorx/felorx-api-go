# CreateOrUpdateAiProviderDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **NullableString** |  | [optional] 
**DisplayName** | Pointer to **NullableString** |  | [optional] 
**ProviderType** | Pointer to [**AiProviderType**](AiProviderType.md) |  | [optional] 
**BaseUrl** | Pointer to **NullableString** |  | [optional] 
**Region** | Pointer to **NullableString** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**Capabilities** | Pointer to [**[]AiCapability**](AiCapability.md) |  | [optional] 
**Secret** | Pointer to **NullableString** |  | [optional] 
**ClearSecret** | Pointer to **bool** |  | [optional] 
**Metadata** | Pointer to **map[string]string** |  | [optional] 
**Models** | Pointer to [**[]CreateOrUpdateAiModelDto**](CreateOrUpdateAiModelDto.md) |  | [optional] 

## Methods

### NewCreateOrUpdateAiProviderDto

`func NewCreateOrUpdateAiProviderDto() *CreateOrUpdateAiProviderDto`

NewCreateOrUpdateAiProviderDto instantiates a new CreateOrUpdateAiProviderDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrUpdateAiProviderDtoWithDefaults

`func NewCreateOrUpdateAiProviderDtoWithDefaults() *CreateOrUpdateAiProviderDto`

NewCreateOrUpdateAiProviderDtoWithDefaults instantiates a new CreateOrUpdateAiProviderDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateOrUpdateAiProviderDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateOrUpdateAiProviderDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateOrUpdateAiProviderDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CreateOrUpdateAiProviderDto) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *CreateOrUpdateAiProviderDto) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *CreateOrUpdateAiProviderDto) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetDisplayName

`func (o *CreateOrUpdateAiProviderDto) GetDisplayName() string`

GetDisplayName returns the DisplayName field if non-nil, zero value otherwise.

### GetDisplayNameOk

`func (o *CreateOrUpdateAiProviderDto) GetDisplayNameOk() (*string, bool)`

GetDisplayNameOk returns a tuple with the DisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayName

`func (o *CreateOrUpdateAiProviderDto) SetDisplayName(v string)`

SetDisplayName sets DisplayName field to given value.

### HasDisplayName

`func (o *CreateOrUpdateAiProviderDto) HasDisplayName() bool`

HasDisplayName returns a boolean if a field has been set.

### SetDisplayNameNil

`func (o *CreateOrUpdateAiProviderDto) SetDisplayNameNil(b bool)`

 SetDisplayNameNil sets the value for DisplayName to be an explicit nil

### UnsetDisplayName
`func (o *CreateOrUpdateAiProviderDto) UnsetDisplayName()`

UnsetDisplayName ensures that no value is present for DisplayName, not even an explicit nil
### GetProviderType

`func (o *CreateOrUpdateAiProviderDto) GetProviderType() AiProviderType`

GetProviderType returns the ProviderType field if non-nil, zero value otherwise.

### GetProviderTypeOk

`func (o *CreateOrUpdateAiProviderDto) GetProviderTypeOk() (*AiProviderType, bool)`

GetProviderTypeOk returns a tuple with the ProviderType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderType

`func (o *CreateOrUpdateAiProviderDto) SetProviderType(v AiProviderType)`

SetProviderType sets ProviderType field to given value.

### HasProviderType

`func (o *CreateOrUpdateAiProviderDto) HasProviderType() bool`

HasProviderType returns a boolean if a field has been set.

### GetBaseUrl

`func (o *CreateOrUpdateAiProviderDto) GetBaseUrl() string`

GetBaseUrl returns the BaseUrl field if non-nil, zero value otherwise.

### GetBaseUrlOk

`func (o *CreateOrUpdateAiProviderDto) GetBaseUrlOk() (*string, bool)`

GetBaseUrlOk returns a tuple with the BaseUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseUrl

`func (o *CreateOrUpdateAiProviderDto) SetBaseUrl(v string)`

SetBaseUrl sets BaseUrl field to given value.

### HasBaseUrl

`func (o *CreateOrUpdateAiProviderDto) HasBaseUrl() bool`

HasBaseUrl returns a boolean if a field has been set.

### SetBaseUrlNil

`func (o *CreateOrUpdateAiProviderDto) SetBaseUrlNil(b bool)`

 SetBaseUrlNil sets the value for BaseUrl to be an explicit nil

### UnsetBaseUrl
`func (o *CreateOrUpdateAiProviderDto) UnsetBaseUrl()`

UnsetBaseUrl ensures that no value is present for BaseUrl, not even an explicit nil
### GetRegion

`func (o *CreateOrUpdateAiProviderDto) GetRegion() string`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *CreateOrUpdateAiProviderDto) GetRegionOk() (*string, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *CreateOrUpdateAiProviderDto) SetRegion(v string)`

SetRegion sets Region field to given value.

### HasRegion

`func (o *CreateOrUpdateAiProviderDto) HasRegion() bool`

HasRegion returns a boolean if a field has been set.

### SetRegionNil

`func (o *CreateOrUpdateAiProviderDto) SetRegionNil(b bool)`

 SetRegionNil sets the value for Region to be an explicit nil

### UnsetRegion
`func (o *CreateOrUpdateAiProviderDto) UnsetRegion()`

UnsetRegion ensures that no value is present for Region, not even an explicit nil
### GetEnabled

`func (o *CreateOrUpdateAiProviderDto) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CreateOrUpdateAiProviderDto) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CreateOrUpdateAiProviderDto) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *CreateOrUpdateAiProviderDto) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetCapabilities

`func (o *CreateOrUpdateAiProviderDto) GetCapabilities() []AiCapability`

GetCapabilities returns the Capabilities field if non-nil, zero value otherwise.

### GetCapabilitiesOk

`func (o *CreateOrUpdateAiProviderDto) GetCapabilitiesOk() (*[]AiCapability, bool)`

GetCapabilitiesOk returns a tuple with the Capabilities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapabilities

`func (o *CreateOrUpdateAiProviderDto) SetCapabilities(v []AiCapability)`

SetCapabilities sets Capabilities field to given value.

### HasCapabilities

`func (o *CreateOrUpdateAiProviderDto) HasCapabilities() bool`

HasCapabilities returns a boolean if a field has been set.

### SetCapabilitiesNil

`func (o *CreateOrUpdateAiProviderDto) SetCapabilitiesNil(b bool)`

 SetCapabilitiesNil sets the value for Capabilities to be an explicit nil

### UnsetCapabilities
`func (o *CreateOrUpdateAiProviderDto) UnsetCapabilities()`

UnsetCapabilities ensures that no value is present for Capabilities, not even an explicit nil
### GetSecret

`func (o *CreateOrUpdateAiProviderDto) GetSecret() string`

GetSecret returns the Secret field if non-nil, zero value otherwise.

### GetSecretOk

`func (o *CreateOrUpdateAiProviderDto) GetSecretOk() (*string, bool)`

GetSecretOk returns a tuple with the Secret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecret

`func (o *CreateOrUpdateAiProviderDto) SetSecret(v string)`

SetSecret sets Secret field to given value.

### HasSecret

`func (o *CreateOrUpdateAiProviderDto) HasSecret() bool`

HasSecret returns a boolean if a field has been set.

### SetSecretNil

`func (o *CreateOrUpdateAiProviderDto) SetSecretNil(b bool)`

 SetSecretNil sets the value for Secret to be an explicit nil

### UnsetSecret
`func (o *CreateOrUpdateAiProviderDto) UnsetSecret()`

UnsetSecret ensures that no value is present for Secret, not even an explicit nil
### GetClearSecret

`func (o *CreateOrUpdateAiProviderDto) GetClearSecret() bool`

GetClearSecret returns the ClearSecret field if non-nil, zero value otherwise.

### GetClearSecretOk

`func (o *CreateOrUpdateAiProviderDto) GetClearSecretOk() (*bool, bool)`

GetClearSecretOk returns a tuple with the ClearSecret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClearSecret

`func (o *CreateOrUpdateAiProviderDto) SetClearSecret(v bool)`

SetClearSecret sets ClearSecret field to given value.

### HasClearSecret

`func (o *CreateOrUpdateAiProviderDto) HasClearSecret() bool`

HasClearSecret returns a boolean if a field has been set.

### GetMetadata

`func (o *CreateOrUpdateAiProviderDto) GetMetadata() map[string]string`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *CreateOrUpdateAiProviderDto) GetMetadataOk() (*map[string]string, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *CreateOrUpdateAiProviderDto) SetMetadata(v map[string]string)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *CreateOrUpdateAiProviderDto) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *CreateOrUpdateAiProviderDto) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *CreateOrUpdateAiProviderDto) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetModels

`func (o *CreateOrUpdateAiProviderDto) GetModels() []CreateOrUpdateAiModelDto`

GetModels returns the Models field if non-nil, zero value otherwise.

### GetModelsOk

`func (o *CreateOrUpdateAiProviderDto) GetModelsOk() (*[]CreateOrUpdateAiModelDto, bool)`

GetModelsOk returns a tuple with the Models field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModels

`func (o *CreateOrUpdateAiProviderDto) SetModels(v []CreateOrUpdateAiModelDto)`

SetModels sets Models field to given value.

### HasModels

`func (o *CreateOrUpdateAiProviderDto) HasModels() bool`

HasModels returns a boolean if a field has been set.

### SetModelsNil

`func (o *CreateOrUpdateAiProviderDto) SetModelsNil(b bool)`

 SetModelsNil sets the value for Models to be an explicit nil

### UnsetModels
`func (o *CreateOrUpdateAiProviderDto) UnsetModels()`

UnsetModels ensures that no value is present for Models, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


