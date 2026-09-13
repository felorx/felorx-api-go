# AiModelDto

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
**ProviderId** | Pointer to **string** |  | [optional] 
**RouteName** | Pointer to **NullableString** |  | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 
**DisplayName** | Pointer to **NullableString** |  | [optional] 
**Capabilities** | Pointer to [**[]AiCapability**](AiCapability.md) |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**IsDefault** | Pointer to **bool** |  | [optional] 
**DefaultParameters** | Pointer to **map[string]string** |  | [optional] 

## Methods

### NewAiModelDto

`func NewAiModelDto() *AiModelDto`

NewAiModelDto instantiates a new AiModelDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelDtoWithDefaults

`func NewAiModelDtoWithDefaults() *AiModelDto`

NewAiModelDtoWithDefaults instantiates a new AiModelDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AiModelDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AiModelDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AiModelDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AiModelDto) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreationTime

`func (o *AiModelDto) GetCreationTime() time.Time`

GetCreationTime returns the CreationTime field if non-nil, zero value otherwise.

### GetCreationTimeOk

`func (o *AiModelDto) GetCreationTimeOk() (*time.Time, bool)`

GetCreationTimeOk returns a tuple with the CreationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreationTime

`func (o *AiModelDto) SetCreationTime(v time.Time)`

SetCreationTime sets CreationTime field to given value.

### HasCreationTime

`func (o *AiModelDto) HasCreationTime() bool`

HasCreationTime returns a boolean if a field has been set.

### GetCreatorId

`func (o *AiModelDto) GetCreatorId() string`

GetCreatorId returns the CreatorId field if non-nil, zero value otherwise.

### GetCreatorIdOk

`func (o *AiModelDto) GetCreatorIdOk() (*string, bool)`

GetCreatorIdOk returns a tuple with the CreatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatorId

`func (o *AiModelDto) SetCreatorId(v string)`

SetCreatorId sets CreatorId field to given value.

### HasCreatorId

`func (o *AiModelDto) HasCreatorId() bool`

HasCreatorId returns a boolean if a field has been set.

### SetCreatorIdNil

`func (o *AiModelDto) SetCreatorIdNil(b bool)`

 SetCreatorIdNil sets the value for CreatorId to be an explicit nil

### UnsetCreatorId
`func (o *AiModelDto) UnsetCreatorId()`

UnsetCreatorId ensures that no value is present for CreatorId, not even an explicit nil
### GetLastModificationTime

`func (o *AiModelDto) GetLastModificationTime() time.Time`

GetLastModificationTime returns the LastModificationTime field if non-nil, zero value otherwise.

### GetLastModificationTimeOk

`func (o *AiModelDto) GetLastModificationTimeOk() (*time.Time, bool)`

GetLastModificationTimeOk returns a tuple with the LastModificationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModificationTime

`func (o *AiModelDto) SetLastModificationTime(v time.Time)`

SetLastModificationTime sets LastModificationTime field to given value.

### HasLastModificationTime

`func (o *AiModelDto) HasLastModificationTime() bool`

HasLastModificationTime returns a boolean if a field has been set.

### SetLastModificationTimeNil

`func (o *AiModelDto) SetLastModificationTimeNil(b bool)`

 SetLastModificationTimeNil sets the value for LastModificationTime to be an explicit nil

### UnsetLastModificationTime
`func (o *AiModelDto) UnsetLastModificationTime()`

UnsetLastModificationTime ensures that no value is present for LastModificationTime, not even an explicit nil
### GetLastModifierId

`func (o *AiModelDto) GetLastModifierId() string`

GetLastModifierId returns the LastModifierId field if non-nil, zero value otherwise.

### GetLastModifierIdOk

`func (o *AiModelDto) GetLastModifierIdOk() (*string, bool)`

GetLastModifierIdOk returns a tuple with the LastModifierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModifierId

`func (o *AiModelDto) SetLastModifierId(v string)`

SetLastModifierId sets LastModifierId field to given value.

### HasLastModifierId

`func (o *AiModelDto) HasLastModifierId() bool`

HasLastModifierId returns a boolean if a field has been set.

### SetLastModifierIdNil

`func (o *AiModelDto) SetLastModifierIdNil(b bool)`

 SetLastModifierIdNil sets the value for LastModifierId to be an explicit nil

### UnsetLastModifierId
`func (o *AiModelDto) UnsetLastModifierId()`

UnsetLastModifierId ensures that no value is present for LastModifierId, not even an explicit nil
### GetIsDeleted

`func (o *AiModelDto) GetIsDeleted() bool`

GetIsDeleted returns the IsDeleted field if non-nil, zero value otherwise.

### GetIsDeletedOk

`func (o *AiModelDto) GetIsDeletedOk() (*bool, bool)`

GetIsDeletedOk returns a tuple with the IsDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDeleted

`func (o *AiModelDto) SetIsDeleted(v bool)`

SetIsDeleted sets IsDeleted field to given value.

### HasIsDeleted

`func (o *AiModelDto) HasIsDeleted() bool`

HasIsDeleted returns a boolean if a field has been set.

### GetDeleterId

`func (o *AiModelDto) GetDeleterId() string`

GetDeleterId returns the DeleterId field if non-nil, zero value otherwise.

### GetDeleterIdOk

`func (o *AiModelDto) GetDeleterIdOk() (*string, bool)`

GetDeleterIdOk returns a tuple with the DeleterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleterId

`func (o *AiModelDto) SetDeleterId(v string)`

SetDeleterId sets DeleterId field to given value.

### HasDeleterId

`func (o *AiModelDto) HasDeleterId() bool`

HasDeleterId returns a boolean if a field has been set.

### SetDeleterIdNil

`func (o *AiModelDto) SetDeleterIdNil(b bool)`

 SetDeleterIdNil sets the value for DeleterId to be an explicit nil

### UnsetDeleterId
`func (o *AiModelDto) UnsetDeleterId()`

UnsetDeleterId ensures that no value is present for DeleterId, not even an explicit nil
### GetDeletionTime

`func (o *AiModelDto) GetDeletionTime() time.Time`

GetDeletionTime returns the DeletionTime field if non-nil, zero value otherwise.

### GetDeletionTimeOk

`func (o *AiModelDto) GetDeletionTimeOk() (*time.Time, bool)`

GetDeletionTimeOk returns a tuple with the DeletionTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletionTime

`func (o *AiModelDto) SetDeletionTime(v time.Time)`

SetDeletionTime sets DeletionTime field to given value.

### HasDeletionTime

`func (o *AiModelDto) HasDeletionTime() bool`

HasDeletionTime returns a boolean if a field has been set.

### SetDeletionTimeNil

`func (o *AiModelDto) SetDeletionTimeNil(b bool)`

 SetDeletionTimeNil sets the value for DeletionTime to be an explicit nil

### UnsetDeletionTime
`func (o *AiModelDto) UnsetDeletionTime()`

UnsetDeletionTime ensures that no value is present for DeletionTime, not even an explicit nil
### GetVerifiedCapabilities

`func (o *AiModelDto) GetVerifiedCapabilities() []AiCapability`

GetVerifiedCapabilities returns the VerifiedCapabilities field if non-nil, zero value otherwise.

### GetVerifiedCapabilitiesOk

`func (o *AiModelDto) GetVerifiedCapabilitiesOk() (*[]AiCapability, bool)`

GetVerifiedCapabilitiesOk returns a tuple with the VerifiedCapabilities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVerifiedCapabilities

`func (o *AiModelDto) SetVerifiedCapabilities(v []AiCapability)`

SetVerifiedCapabilities sets VerifiedCapabilities field to given value.

### HasVerifiedCapabilities

`func (o *AiModelDto) HasVerifiedCapabilities() bool`

HasVerifiedCapabilities returns a boolean if a field has been set.

### SetVerifiedCapabilitiesNil

`func (o *AiModelDto) SetVerifiedCapabilitiesNil(b bool)`

 SetVerifiedCapabilitiesNil sets the value for VerifiedCapabilities to be an explicit nil

### UnsetVerifiedCapabilities
`func (o *AiModelDto) UnsetVerifiedCapabilities()`

UnsetVerifiedCapabilities ensures that no value is present for VerifiedCapabilities, not even an explicit nil
### GetCapabilityCertificateVersion

`func (o *AiModelDto) GetCapabilityCertificateVersion() string`

GetCapabilityCertificateVersion returns the CapabilityCertificateVersion field if non-nil, zero value otherwise.

### GetCapabilityCertificateVersionOk

`func (o *AiModelDto) GetCapabilityCertificateVersionOk() (*string, bool)`

GetCapabilityCertificateVersionOk returns a tuple with the CapabilityCertificateVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapabilityCertificateVersion

`func (o *AiModelDto) SetCapabilityCertificateVersion(v string)`

SetCapabilityCertificateVersion sets CapabilityCertificateVersion field to given value.

### HasCapabilityCertificateVersion

`func (o *AiModelDto) HasCapabilityCertificateVersion() bool`

HasCapabilityCertificateVersion returns a boolean if a field has been set.

### SetCapabilityCertificateVersionNil

`func (o *AiModelDto) SetCapabilityCertificateVersionNil(b bool)`

 SetCapabilityCertificateVersionNil sets the value for CapabilityCertificateVersion to be an explicit nil

### UnsetCapabilityCertificateVersion
`func (o *AiModelDto) UnsetCapabilityCertificateVersion()`

UnsetCapabilityCertificateVersion ensures that no value is present for CapabilityCertificateVersion, not even an explicit nil
### GetCapabilityTestedAt

`func (o *AiModelDto) GetCapabilityTestedAt() time.Time`

GetCapabilityTestedAt returns the CapabilityTestedAt field if non-nil, zero value otherwise.

### GetCapabilityTestedAtOk

`func (o *AiModelDto) GetCapabilityTestedAtOk() (*time.Time, bool)`

GetCapabilityTestedAtOk returns a tuple with the CapabilityTestedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapabilityTestedAt

`func (o *AiModelDto) SetCapabilityTestedAt(v time.Time)`

SetCapabilityTestedAt sets CapabilityTestedAt field to given value.

### HasCapabilityTestedAt

`func (o *AiModelDto) HasCapabilityTestedAt() bool`

HasCapabilityTestedAt returns a boolean if a field has been set.

### SetCapabilityTestedAtNil

`func (o *AiModelDto) SetCapabilityTestedAtNil(b bool)`

 SetCapabilityTestedAtNil sets the value for CapabilityTestedAt to be an explicit nil

### UnsetCapabilityTestedAt
`func (o *AiModelDto) UnsetCapabilityTestedAt()`

UnsetCapabilityTestedAt ensures that no value is present for CapabilityTestedAt, not even an explicit nil
### GetProviderId

`func (o *AiModelDto) GetProviderId() string`

GetProviderId returns the ProviderId field if non-nil, zero value otherwise.

### GetProviderIdOk

`func (o *AiModelDto) GetProviderIdOk() (*string, bool)`

GetProviderIdOk returns a tuple with the ProviderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderId

`func (o *AiModelDto) SetProviderId(v string)`

SetProviderId sets ProviderId field to given value.

### HasProviderId

`func (o *AiModelDto) HasProviderId() bool`

HasProviderId returns a boolean if a field has been set.

### GetRouteName

`func (o *AiModelDto) GetRouteName() string`

GetRouteName returns the RouteName field if non-nil, zero value otherwise.

### GetRouteNameOk

`func (o *AiModelDto) GetRouteNameOk() (*string, bool)`

GetRouteNameOk returns a tuple with the RouteName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouteName

`func (o *AiModelDto) SetRouteName(v string)`

SetRouteName sets RouteName field to given value.

### HasRouteName

`func (o *AiModelDto) HasRouteName() bool`

HasRouteName returns a boolean if a field has been set.

### SetRouteNameNil

`func (o *AiModelDto) SetRouteNameNil(b bool)`

 SetRouteNameNil sets the value for RouteName to be an explicit nil

### UnsetRouteName
`func (o *AiModelDto) UnsetRouteName()`

UnsetRouteName ensures that no value is present for RouteName, not even an explicit nil
### GetName

`func (o *AiModelDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AiModelDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AiModelDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *AiModelDto) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *AiModelDto) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *AiModelDto) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetDisplayName

`func (o *AiModelDto) GetDisplayName() string`

GetDisplayName returns the DisplayName field if non-nil, zero value otherwise.

### GetDisplayNameOk

`func (o *AiModelDto) GetDisplayNameOk() (*string, bool)`

GetDisplayNameOk returns a tuple with the DisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayName

`func (o *AiModelDto) SetDisplayName(v string)`

SetDisplayName sets DisplayName field to given value.

### HasDisplayName

`func (o *AiModelDto) HasDisplayName() bool`

HasDisplayName returns a boolean if a field has been set.

### SetDisplayNameNil

`func (o *AiModelDto) SetDisplayNameNil(b bool)`

 SetDisplayNameNil sets the value for DisplayName to be an explicit nil

### UnsetDisplayName
`func (o *AiModelDto) UnsetDisplayName()`

UnsetDisplayName ensures that no value is present for DisplayName, not even an explicit nil
### GetCapabilities

`func (o *AiModelDto) GetCapabilities() []AiCapability`

GetCapabilities returns the Capabilities field if non-nil, zero value otherwise.

### GetCapabilitiesOk

`func (o *AiModelDto) GetCapabilitiesOk() (*[]AiCapability, bool)`

GetCapabilitiesOk returns a tuple with the Capabilities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapabilities

`func (o *AiModelDto) SetCapabilities(v []AiCapability)`

SetCapabilities sets Capabilities field to given value.

### HasCapabilities

`func (o *AiModelDto) HasCapabilities() bool`

HasCapabilities returns a boolean if a field has been set.

### SetCapabilitiesNil

`func (o *AiModelDto) SetCapabilitiesNil(b bool)`

 SetCapabilitiesNil sets the value for Capabilities to be an explicit nil

### UnsetCapabilities
`func (o *AiModelDto) UnsetCapabilities()`

UnsetCapabilities ensures that no value is present for Capabilities, not even an explicit nil
### GetEnabled

`func (o *AiModelDto) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *AiModelDto) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *AiModelDto) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *AiModelDto) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetIsDefault

`func (o *AiModelDto) GetIsDefault() bool`

GetIsDefault returns the IsDefault field if non-nil, zero value otherwise.

### GetIsDefaultOk

`func (o *AiModelDto) GetIsDefaultOk() (*bool, bool)`

GetIsDefaultOk returns a tuple with the IsDefault field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDefault

`func (o *AiModelDto) SetIsDefault(v bool)`

SetIsDefault sets IsDefault field to given value.

### HasIsDefault

`func (o *AiModelDto) HasIsDefault() bool`

HasIsDefault returns a boolean if a field has been set.

### GetDefaultParameters

`func (o *AiModelDto) GetDefaultParameters() map[string]string`

GetDefaultParameters returns the DefaultParameters field if non-nil, zero value otherwise.

### GetDefaultParametersOk

`func (o *AiModelDto) GetDefaultParametersOk() (*map[string]string, bool)`

GetDefaultParametersOk returns a tuple with the DefaultParameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultParameters

`func (o *AiModelDto) SetDefaultParameters(v map[string]string)`

SetDefaultParameters sets DefaultParameters field to given value.

### HasDefaultParameters

`func (o *AiModelDto) HasDefaultParameters() bool`

HasDefaultParameters returns a boolean if a field has been set.

### SetDefaultParametersNil

`func (o *AiModelDto) SetDefaultParametersNil(b bool)`

 SetDefaultParametersNil sets the value for DefaultParameters to be an explicit nil

### UnsetDefaultParameters
`func (o *AiModelDto) UnsetDefaultParameters()`

UnsetDefaultParameters ensures that no value is present for DefaultParameters, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


