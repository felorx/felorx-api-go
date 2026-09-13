# AiProviderDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**CreationTime** | Pointer to **time.Time** |  | [optional] 
**CreatorId** | Pointer to **NullableString** |  | [optional] 
**LastModificationTime** | Pointer to **NullableTime** |  | [optional] 
**LastModifierId** | Pointer to **NullableString** |  | [optional] 
**IsDeleted** | Pointer to **bool** |  | [optional] 
**DeleterId** | Pointer to **NullableString** |  | [optional] 
**DeletionTime** | Pointer to **NullableTime** |  | [optional] 
**VerifiedCapabilities** | Pointer to [**[]AiCapability**](AiCapability.md) |  | [optional] 
**CapabilityCertificateVersion** | Pointer to **NullableString** |  | [optional] 
**CapabilityTestedAt** | Pointer to **NullableTime** |  | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 
**DisplayName** | Pointer to **NullableString** |  | [optional] 
**ProviderType** | Pointer to [**AiProviderType**](AiProviderType.md) |  | [optional] 
**BaseUrl** | Pointer to **NullableString** |  | [optional] 
**Region** | Pointer to **NullableString** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**Capabilities** | Pointer to [**[]AiCapability**](AiCapability.md) |  | [optional] 
**SecretConfigured** | Pointer to **bool** |  | [optional] 
**Metadata** | Pointer to **map[string]string** |  | [optional] 
**Models** | Pointer to [**[]AiModelDto**](AiModelDto.md) |  | [optional] 

## Methods

### NewAiProviderDto

`func NewAiProviderDto() *AiProviderDto`

NewAiProviderDto instantiates a new AiProviderDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiProviderDtoWithDefaults

`func NewAiProviderDtoWithDefaults() *AiProviderDto`

NewAiProviderDtoWithDefaults instantiates a new AiProviderDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AiProviderDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AiProviderDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AiProviderDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AiProviderDto) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreationTime

`func (o *AiProviderDto) GetCreationTime() time.Time`

GetCreationTime returns the CreationTime field if non-nil, zero value otherwise.

### GetCreationTimeOk

`func (o *AiProviderDto) GetCreationTimeOk() (*time.Time, bool)`

GetCreationTimeOk returns a tuple with the CreationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreationTime

`func (o *AiProviderDto) SetCreationTime(v time.Time)`

SetCreationTime sets CreationTime field to given value.

### HasCreationTime

`func (o *AiProviderDto) HasCreationTime() bool`

HasCreationTime returns a boolean if a field has been set.

### GetCreatorId

`func (o *AiProviderDto) GetCreatorId() string`

GetCreatorId returns the CreatorId field if non-nil, zero value otherwise.

### GetCreatorIdOk

`func (o *AiProviderDto) GetCreatorIdOk() (*string, bool)`

GetCreatorIdOk returns a tuple with the CreatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatorId

`func (o *AiProviderDto) SetCreatorId(v string)`

SetCreatorId sets CreatorId field to given value.

### HasCreatorId

`func (o *AiProviderDto) HasCreatorId() bool`

HasCreatorId returns a boolean if a field has been set.

### SetCreatorIdNil

`func (o *AiProviderDto) SetCreatorIdNil(b bool)`

 SetCreatorIdNil sets the value for CreatorId to be an explicit nil

### UnsetCreatorId
`func (o *AiProviderDto) UnsetCreatorId()`

UnsetCreatorId ensures that no value is present for CreatorId, not even an explicit nil
### GetLastModificationTime

`func (o *AiProviderDto) GetLastModificationTime() time.Time`

GetLastModificationTime returns the LastModificationTime field if non-nil, zero value otherwise.

### GetLastModificationTimeOk

`func (o *AiProviderDto) GetLastModificationTimeOk() (*time.Time, bool)`

GetLastModificationTimeOk returns a tuple with the LastModificationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModificationTime

`func (o *AiProviderDto) SetLastModificationTime(v time.Time)`

SetLastModificationTime sets LastModificationTime field to given value.

### HasLastModificationTime

`func (o *AiProviderDto) HasLastModificationTime() bool`

HasLastModificationTime returns a boolean if a field has been set.

### SetLastModificationTimeNil

`func (o *AiProviderDto) SetLastModificationTimeNil(b bool)`

 SetLastModificationTimeNil sets the value for LastModificationTime to be an explicit nil

### UnsetLastModificationTime
`func (o *AiProviderDto) UnsetLastModificationTime()`

UnsetLastModificationTime ensures that no value is present for LastModificationTime, not even an explicit nil
### GetLastModifierId

`func (o *AiProviderDto) GetLastModifierId() string`

GetLastModifierId returns the LastModifierId field if non-nil, zero value otherwise.

### GetLastModifierIdOk

`func (o *AiProviderDto) GetLastModifierIdOk() (*string, bool)`

GetLastModifierIdOk returns a tuple with the LastModifierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModifierId

`func (o *AiProviderDto) SetLastModifierId(v string)`

SetLastModifierId sets LastModifierId field to given value.

### HasLastModifierId

`func (o *AiProviderDto) HasLastModifierId() bool`

HasLastModifierId returns a boolean if a field has been set.

### SetLastModifierIdNil

`func (o *AiProviderDto) SetLastModifierIdNil(b bool)`

 SetLastModifierIdNil sets the value for LastModifierId to be an explicit nil

### UnsetLastModifierId
`func (o *AiProviderDto) UnsetLastModifierId()`

UnsetLastModifierId ensures that no value is present for LastModifierId, not even an explicit nil
### GetIsDeleted

`func (o *AiProviderDto) GetIsDeleted() bool`

GetIsDeleted returns the IsDeleted field if non-nil, zero value otherwise.

### GetIsDeletedOk

`func (o *AiProviderDto) GetIsDeletedOk() (*bool, bool)`

GetIsDeletedOk returns a tuple with the IsDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDeleted

`func (o *AiProviderDto) SetIsDeleted(v bool)`

SetIsDeleted sets IsDeleted field to given value.

### HasIsDeleted

`func (o *AiProviderDto) HasIsDeleted() bool`

HasIsDeleted returns a boolean if a field has been set.

### GetDeleterId

`func (o *AiProviderDto) GetDeleterId() string`

GetDeleterId returns the DeleterId field if non-nil, zero value otherwise.

### GetDeleterIdOk

`func (o *AiProviderDto) GetDeleterIdOk() (*string, bool)`

GetDeleterIdOk returns a tuple with the DeleterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleterId

`func (o *AiProviderDto) SetDeleterId(v string)`

SetDeleterId sets DeleterId field to given value.

### HasDeleterId

`func (o *AiProviderDto) HasDeleterId() bool`

HasDeleterId returns a boolean if a field has been set.

### SetDeleterIdNil

`func (o *AiProviderDto) SetDeleterIdNil(b bool)`

 SetDeleterIdNil sets the value for DeleterId to be an explicit nil

### UnsetDeleterId
`func (o *AiProviderDto) UnsetDeleterId()`

UnsetDeleterId ensures that no value is present for DeleterId, not even an explicit nil
### GetDeletionTime

`func (o *AiProviderDto) GetDeletionTime() time.Time`

GetDeletionTime returns the DeletionTime field if non-nil, zero value otherwise.

### GetDeletionTimeOk

`func (o *AiProviderDto) GetDeletionTimeOk() (*time.Time, bool)`

GetDeletionTimeOk returns a tuple with the DeletionTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletionTime

`func (o *AiProviderDto) SetDeletionTime(v time.Time)`

SetDeletionTime sets DeletionTime field to given value.

### HasDeletionTime

`func (o *AiProviderDto) HasDeletionTime() bool`

HasDeletionTime returns a boolean if a field has been set.

### SetDeletionTimeNil

`func (o *AiProviderDto) SetDeletionTimeNil(b bool)`

 SetDeletionTimeNil sets the value for DeletionTime to be an explicit nil

### UnsetDeletionTime
`func (o *AiProviderDto) UnsetDeletionTime()`

UnsetDeletionTime ensures that no value is present for DeletionTime, not even an explicit nil
### GetVerifiedCapabilities

`func (o *AiProviderDto) GetVerifiedCapabilities() []AiCapability`

GetVerifiedCapabilities returns the VerifiedCapabilities field if non-nil, zero value otherwise.

### GetVerifiedCapabilitiesOk

`func (o *AiProviderDto) GetVerifiedCapabilitiesOk() (*[]AiCapability, bool)`

GetVerifiedCapabilitiesOk returns a tuple with the VerifiedCapabilities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerifiedCapabilities

`func (o *AiProviderDto) SetVerifiedCapabilities(v []AiCapability)`

SetVerifiedCapabilities sets VerifiedCapabilities field to given value.

### HasVerifiedCapabilities

`func (o *AiProviderDto) HasVerifiedCapabilities() bool`

HasVerifiedCapabilities returns a boolean if a field has been set.

### SetVerifiedCapabilitiesNil

`func (o *AiProviderDto) SetVerifiedCapabilitiesNil(b bool)`

 SetVerifiedCapabilitiesNil sets the value for VerifiedCapabilities to be an explicit nil

### UnsetVerifiedCapabilities
`func (o *AiProviderDto) UnsetVerifiedCapabilities()`

UnsetVerifiedCapabilities ensures that no value is present for VerifiedCapabilities, not even an explicit nil
### GetCapabilityCertificateVersion

`func (o *AiProviderDto) GetCapabilityCertificateVersion() string`

GetCapabilityCertificateVersion returns the CapabilityCertificateVersion field if non-nil, zero value otherwise.

### GetCapabilityCertificateVersionOk

`func (o *AiProviderDto) GetCapabilityCertificateVersionOk() (*string, bool)`

GetCapabilityCertificateVersionOk returns a tuple with the CapabilityCertificateVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapabilityCertificateVersion

`func (o *AiProviderDto) SetCapabilityCertificateVersion(v string)`

SetCapabilityCertificateVersion sets CapabilityCertificateVersion field to given value.

### HasCapabilityCertificateVersion

`func (o *AiProviderDto) HasCapabilityCertificateVersion() bool`

HasCapabilityCertificateVersion returns a boolean if a field has been set.

### SetCapabilityCertificateVersionNil

`func (o *AiProviderDto) SetCapabilityCertificateVersionNil(b bool)`

 SetCapabilityCertificateVersionNil sets the value for CapabilityCertificateVersion to be an explicit nil

### UnsetCapabilityCertificateVersion
`func (o *AiProviderDto) UnsetCapabilityCertificateVersion()`

UnsetCapabilityCertificateVersion ensures that no value is present for CapabilityCertificateVersion, not even an explicit nil
### GetCapabilityTestedAt

`func (o *AiProviderDto) GetCapabilityTestedAt() time.Time`

GetCapabilityTestedAt returns the CapabilityTestedAt field if non-nil, zero value otherwise.

### GetCapabilityTestedAtOk

`func (o *AiProviderDto) GetCapabilityTestedAtOk() (*time.Time, bool)`

GetCapabilityTestedAtOk returns a tuple with the CapabilityTestedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapabilityTestedAt

`func (o *AiProviderDto) SetCapabilityTestedAt(v time.Time)`

SetCapabilityTestedAt sets CapabilityTestedAt field to given value.

### HasCapabilityTestedAt

`func (o *AiProviderDto) HasCapabilityTestedAt() bool`

HasCapabilityTestedAt returns a boolean if a field has been set.

### SetCapabilityTestedAtNil

`func (o *AiProviderDto) SetCapabilityTestedAtNil(b bool)`

 SetCapabilityTestedAtNil sets the value for CapabilityTestedAt to be an explicit nil

### UnsetCapabilityTestedAt
`func (o *AiProviderDto) UnsetCapabilityTestedAt()`

UnsetCapabilityTestedAt ensures that no value is present for CapabilityTestedAt, not even an explicit nil
### GetName

`func (o *AiProviderDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AiProviderDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AiProviderDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *AiProviderDto) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *AiProviderDto) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *AiProviderDto) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetDisplayName

`func (o *AiProviderDto) GetDisplayName() string`

GetDisplayName returns the DisplayName field if non-nil, zero value otherwise.

### GetDisplayNameOk

`func (o *AiProviderDto) GetDisplayNameOk() (*string, bool)`

GetDisplayNameOk returns a tuple with the DisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayName

`func (o *AiProviderDto) SetDisplayName(v string)`

SetDisplayName sets DisplayName field to given value.

### HasDisplayName

`func (o *AiProviderDto) HasDisplayName() bool`

HasDisplayName returns a boolean if a field has been set.

### SetDisplayNameNil

`func (o *AiProviderDto) SetDisplayNameNil(b bool)`

 SetDisplayNameNil sets the value for DisplayName to be an explicit nil

### UnsetDisplayName
`func (o *AiProviderDto) UnsetDisplayName()`

UnsetDisplayName ensures that no value is present for DisplayName, not even an explicit nil
### GetProviderType

`func (o *AiProviderDto) GetProviderType() AiProviderType`

GetProviderType returns the ProviderType field if non-nil, zero value otherwise.

### GetProviderTypeOk

`func (o *AiProviderDto) GetProviderTypeOk() (*AiProviderType, bool)`

GetProviderTypeOk returns a tuple with the ProviderType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderType

`func (o *AiProviderDto) SetProviderType(v AiProviderType)`

SetProviderType sets ProviderType field to given value.

### HasProviderType

`func (o *AiProviderDto) HasProviderType() bool`

HasProviderType returns a boolean if a field has been set.

### GetBaseUrl

`func (o *AiProviderDto) GetBaseUrl() string`

GetBaseUrl returns the BaseUrl field if non-nil, zero value otherwise.

### GetBaseUrlOk

`func (o *AiProviderDto) GetBaseUrlOk() (*string, bool)`

GetBaseUrlOk returns a tuple with the BaseUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseUrl

`func (o *AiProviderDto) SetBaseUrl(v string)`

SetBaseUrl sets BaseUrl field to given value.

### HasBaseUrl

`func (o *AiProviderDto) HasBaseUrl() bool`

HasBaseUrl returns a boolean if a field has been set.

### SetBaseUrlNil

`func (o *AiProviderDto) SetBaseUrlNil(b bool)`

 SetBaseUrlNil sets the value for BaseUrl to be an explicit nil

### UnsetBaseUrl
`func (o *AiProviderDto) UnsetBaseUrl()`

UnsetBaseUrl ensures that no value is present for BaseUrl, not even an explicit nil
### GetRegion

`func (o *AiProviderDto) GetRegion() string`

GetRegion returns the Region field if non-nil, zero value otherwise.

### GetRegionOk

`func (o *AiProviderDto) GetRegionOk() (*string, bool)`

GetRegionOk returns a tuple with the Region field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegion

`func (o *AiProviderDto) SetRegion(v string)`

SetRegion sets Region field to given value.

### HasRegion

`func (o *AiProviderDto) HasRegion() bool`

HasRegion returns a boolean if a field has been set.

### SetRegionNil

`func (o *AiProviderDto) SetRegionNil(b bool)`

 SetRegionNil sets the value for Region to be an explicit nil

### UnsetRegion
`func (o *AiProviderDto) UnsetRegion()`

UnsetRegion ensures that no value is present for Region, not even an explicit nil
### GetEnabled

`func (o *AiProviderDto) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *AiProviderDto) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *AiProviderDto) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *AiProviderDto) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetCapabilities

`func (o *AiProviderDto) GetCapabilities() []AiCapability`

GetCapabilities returns the Capabilities field if non-nil, zero value otherwise.

### GetCapabilitiesOk

`func (o *AiProviderDto) GetCapabilitiesOk() (*[]AiCapability, bool)`

GetCapabilitiesOk returns a tuple with the Capabilities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapabilities

`func (o *AiProviderDto) SetCapabilities(v []AiCapability)`

SetCapabilities sets Capabilities field to given value.

### HasCapabilities

`func (o *AiProviderDto) HasCapabilities() bool`

HasCapabilities returns a boolean if a field has been set.

### SetCapabilitiesNil

`func (o *AiProviderDto) SetCapabilitiesNil(b bool)`

 SetCapabilitiesNil sets the value for Capabilities to be an explicit nil

### UnsetCapabilities
`func (o *AiProviderDto) UnsetCapabilities()`

UnsetCapabilities ensures that no value is present for Capabilities, not even an explicit nil
### GetSecretConfigured

`func (o *AiProviderDto) GetSecretConfigured() bool`

GetSecretConfigured returns the SecretConfigured field if non-nil, zero value otherwise.

### GetSecretConfiguredOk

`func (o *AiProviderDto) GetSecretConfiguredOk() (*bool, bool)`

GetSecretConfiguredOk returns a tuple with the SecretConfigured field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecretConfigured

`func (o *AiProviderDto) SetSecretConfigured(v bool)`

SetSecretConfigured sets SecretConfigured field to given value.

### HasSecretConfigured

`func (o *AiProviderDto) HasSecretConfigured() bool`

HasSecretConfigured returns a boolean if a field has been set.

### GetMetadata

`func (o *AiProviderDto) GetMetadata() map[string]string`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *AiProviderDto) GetMetadataOk() (*map[string]string, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *AiProviderDto) SetMetadata(v map[string]string)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *AiProviderDto) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *AiProviderDto) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *AiProviderDto) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetModels

`func (o *AiProviderDto) GetModels() []AiModelDto`

GetModels returns the Models field if non-nil, zero value otherwise.

### GetModelsOk

`func (o *AiProviderDto) GetModelsOk() (*[]AiModelDto, bool)`

GetModelsOk returns a tuple with the Models field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModels

`func (o *AiProviderDto) SetModels(v []AiModelDto)`

SetModels sets Models field to given value.

### HasModels

`func (o *AiProviderDto) HasModels() bool`

HasModels returns a boolean if a field has been set.

### SetModelsNil

`func (o *AiProviderDto) SetModelsNil(b bool)`

 SetModelsNil sets the value for Models to be an explicit nil

### UnsetModels
`func (o *AiProviderDto) UnsetModels()`

UnsetModels ensures that no value is present for Models, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


