# CreateOrUpdateAiModelDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RouteName** | Pointer to **NullableString** |  | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 
**DisplayName** | Pointer to **NullableString** |  | [optional] 
**Capabilities** | Pointer to [**[]AiCapability**](AiCapability.md) |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**IsDefault** | Pointer to **bool** |  | [optional] 
**DefaultParameters** | Pointer to **map[string]string** |  | [optional] 

## Methods

### NewCreateOrUpdateAiModelDto

`func NewCreateOrUpdateAiModelDto() *CreateOrUpdateAiModelDto`

NewCreateOrUpdateAiModelDto instantiates a new CreateOrUpdateAiModelDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrUpdateAiModelDtoWithDefaults

`func NewCreateOrUpdateAiModelDtoWithDefaults() *CreateOrUpdateAiModelDto`

NewCreateOrUpdateAiModelDtoWithDefaults instantiates a new CreateOrUpdateAiModelDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRouteName

`func (o *CreateOrUpdateAiModelDto) GetRouteName() string`

GetRouteName returns the RouteName field if non-nil, zero value otherwise.

### GetRouteNameOk

`func (o *CreateOrUpdateAiModelDto) GetRouteNameOk() (*string, bool)`

GetRouteNameOk returns a tuple with the RouteName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouteName

`func (o *CreateOrUpdateAiModelDto) SetRouteName(v string)`

SetRouteName sets RouteName field to given value.

### HasRouteName

`func (o *CreateOrUpdateAiModelDto) HasRouteName() bool`

HasRouteName returns a boolean if a field has been set.

### SetRouteNameNil

`func (o *CreateOrUpdateAiModelDto) SetRouteNameNil(b bool)`

 SetRouteNameNil sets the value for RouteName to be an explicit nil

### UnsetRouteName
`func (o *CreateOrUpdateAiModelDto) UnsetRouteName()`

UnsetRouteName ensures that no value is present for RouteName, not even an explicit nil
### GetName

`func (o *CreateOrUpdateAiModelDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateOrUpdateAiModelDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateOrUpdateAiModelDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CreateOrUpdateAiModelDto) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *CreateOrUpdateAiModelDto) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *CreateOrUpdateAiModelDto) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetDisplayName

`func (o *CreateOrUpdateAiModelDto) GetDisplayName() string`

GetDisplayName returns the DisplayName field if non-nil, zero value otherwise.

### GetDisplayNameOk

`func (o *CreateOrUpdateAiModelDto) GetDisplayNameOk() (*string, bool)`

GetDisplayNameOk returns a tuple with the DisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayName

`func (o *CreateOrUpdateAiModelDto) SetDisplayName(v string)`

SetDisplayName sets DisplayName field to given value.

### HasDisplayName

`func (o *CreateOrUpdateAiModelDto) HasDisplayName() bool`

HasDisplayName returns a boolean if a field has been set.

### SetDisplayNameNil

`func (o *CreateOrUpdateAiModelDto) SetDisplayNameNil(b bool)`

 SetDisplayNameNil sets the value for DisplayName to be an explicit nil

### UnsetDisplayName
`func (o *CreateOrUpdateAiModelDto) UnsetDisplayName()`

UnsetDisplayName ensures that no value is present for DisplayName, not even an explicit nil
### GetCapabilities

`func (o *CreateOrUpdateAiModelDto) GetCapabilities() []AiCapability`

GetCapabilities returns the Capabilities field if non-nil, zero value otherwise.

### GetCapabilitiesOk

`func (o *CreateOrUpdateAiModelDto) GetCapabilitiesOk() (*[]AiCapability, bool)`

GetCapabilitiesOk returns a tuple with the Capabilities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapabilities

`func (o *CreateOrUpdateAiModelDto) SetCapabilities(v []AiCapability)`

SetCapabilities sets Capabilities field to given value.

### HasCapabilities

`func (o *CreateOrUpdateAiModelDto) HasCapabilities() bool`

HasCapabilities returns a boolean if a field has been set.

### SetCapabilitiesNil

`func (o *CreateOrUpdateAiModelDto) SetCapabilitiesNil(b bool)`

 SetCapabilitiesNil sets the value for Capabilities to be an explicit nil

### UnsetCapabilities
`func (o *CreateOrUpdateAiModelDto) UnsetCapabilities()`

UnsetCapabilities ensures that no value is present for Capabilities, not even an explicit nil
### GetEnabled

`func (o *CreateOrUpdateAiModelDto) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CreateOrUpdateAiModelDto) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CreateOrUpdateAiModelDto) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *CreateOrUpdateAiModelDto) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetIsDefault

`func (o *CreateOrUpdateAiModelDto) GetIsDefault() bool`

GetIsDefault returns the IsDefault field if non-nil, zero value otherwise.

### GetIsDefaultOk

`func (o *CreateOrUpdateAiModelDto) GetIsDefaultOk() (*bool, bool)`

GetIsDefaultOk returns a tuple with the IsDefault field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDefault

`func (o *CreateOrUpdateAiModelDto) SetIsDefault(v bool)`

SetIsDefault sets IsDefault field to given value.

### HasIsDefault

`func (o *CreateOrUpdateAiModelDto) HasIsDefault() bool`

HasIsDefault returns a boolean if a field has been set.

### GetDefaultParameters

`func (o *CreateOrUpdateAiModelDto) GetDefaultParameters() map[string]string`

GetDefaultParameters returns the DefaultParameters field if non-nil, zero value otherwise.

### GetDefaultParametersOk

`func (o *CreateOrUpdateAiModelDto) GetDefaultParametersOk() (*map[string]string, bool)`

GetDefaultParametersOk returns a tuple with the DefaultParameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultParameters

`func (o *CreateOrUpdateAiModelDto) SetDefaultParameters(v map[string]string)`

SetDefaultParameters sets DefaultParameters field to given value.

### HasDefaultParameters

`func (o *CreateOrUpdateAiModelDto) HasDefaultParameters() bool`

HasDefaultParameters returns a boolean if a field has been set.

### SetDefaultParametersNil

`func (o *CreateOrUpdateAiModelDto) SetDefaultParametersNil(b bool)`

 SetDefaultParametersNil sets the value for DefaultParameters to be an explicit nil

### UnsetDefaultParameters
`func (o *CreateOrUpdateAiModelDto) UnsetDefaultParameters()`

UnsetDefaultParameters ensures that no value is present for DefaultParameters, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


