# ModuleExtensionDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Entities** | Pointer to [**map[string]EntityExtensionDto**](EntityExtensionDto.md) |  | [optional] 
**Configuration** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewModuleExtensionDto

`func NewModuleExtensionDto() *ModuleExtensionDto`

NewModuleExtensionDto instantiates a new ModuleExtensionDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewModuleExtensionDtoWithDefaults

`func NewModuleExtensionDtoWithDefaults() *ModuleExtensionDto`

NewModuleExtensionDtoWithDefaults instantiates a new ModuleExtensionDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEntities

`func (o *ModuleExtensionDto) GetEntities() map[string]EntityExtensionDto`

GetEntities returns the Entities field if non-nil, zero value otherwise.

### GetEntitiesOk

`func (o *ModuleExtensionDto) GetEntitiesOk() (*map[string]EntityExtensionDto, bool)`

GetEntitiesOk returns a tuple with the Entities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntities

`func (o *ModuleExtensionDto) SetEntities(v map[string]EntityExtensionDto)`

SetEntities sets Entities field to given value.

### HasEntities

`func (o *ModuleExtensionDto) HasEntities() bool`

HasEntities returns a boolean if a field has been set.

### SetEntitiesNil

`func (o *ModuleExtensionDto) SetEntitiesNil(b bool)`

 SetEntitiesNil sets the value for Entities to be an explicit nil

### UnsetEntities
`func (o *ModuleExtensionDto) UnsetEntities()`

UnsetEntities ensures that no value is present for Entities, not even an explicit nil
### GetConfiguration

`func (o *ModuleExtensionDto) GetConfiguration() map[string]interface{}`

GetConfiguration returns the Configuration field if non-nil, zero value otherwise.

### GetConfigurationOk

`func (o *ModuleExtensionDto) GetConfigurationOk() (*map[string]interface{}, bool)`

GetConfigurationOk returns a tuple with the Configuration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfiguration

`func (o *ModuleExtensionDto) SetConfiguration(v map[string]interface{})`

SetConfiguration sets Configuration field to given value.

### HasConfiguration

`func (o *ModuleExtensionDto) HasConfiguration() bool`

HasConfiguration returns a boolean if a field has been set.

### SetConfigurationNil

`func (o *ModuleExtensionDto) SetConfigurationNil(b bool)`

 SetConfigurationNil sets the value for Configuration to be an explicit nil

### UnsetConfiguration
`func (o *ModuleExtensionDto) UnsetConfiguration()`

UnsetConfiguration ensures that no value is present for Configuration, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


