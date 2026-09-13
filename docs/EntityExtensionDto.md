# EntityExtensionDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Properties** | Pointer to [**map[string]ExtensionPropertyDto**](ExtensionPropertyDto.md) |  | [optional] 
**Configuration** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewEntityExtensionDto

`func NewEntityExtensionDto() *EntityExtensionDto`

NewEntityExtensionDto instantiates a new EntityExtensionDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEntityExtensionDtoWithDefaults

`func NewEntityExtensionDtoWithDefaults() *EntityExtensionDto`

NewEntityExtensionDtoWithDefaults instantiates a new EntityExtensionDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProperties

`func (o *EntityExtensionDto) GetProperties() map[string]ExtensionPropertyDto`

GetProperties returns the Properties field if non-nil, zero value otherwise.

### GetPropertiesOk

`func (o *EntityExtensionDto) GetPropertiesOk() (*map[string]ExtensionPropertyDto, bool)`

GetPropertiesOk returns a tuple with the Properties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperties

`func (o *EntityExtensionDto) SetProperties(v map[string]ExtensionPropertyDto)`

SetProperties sets Properties field to given value.

### HasProperties

`func (o *EntityExtensionDto) HasProperties() bool`

HasProperties returns a boolean if a field has been set.

### SetPropertiesNil

`func (o *EntityExtensionDto) SetPropertiesNil(b bool)`

 SetPropertiesNil sets the value for Properties to be an explicit nil

### UnsetProperties
`func (o *EntityExtensionDto) UnsetProperties()`

UnsetProperties ensures that no value is present for Properties, not even an explicit nil
### GetConfiguration

`func (o *EntityExtensionDto) GetConfiguration() map[string]interface{}`

GetConfiguration returns the Configuration field if non-nil, zero value otherwise.

### GetConfigurationOk

`func (o *EntityExtensionDto) GetConfigurationOk() (*map[string]interface{}, bool)`

GetConfigurationOk returns a tuple with the Configuration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfiguration

`func (o *EntityExtensionDto) SetConfiguration(v map[string]interface{})`

SetConfiguration sets Configuration field to given value.

### HasConfiguration

`func (o *EntityExtensionDto) HasConfiguration() bool`

HasConfiguration returns a boolean if a field has been set.

### SetConfigurationNil

`func (o *EntityExtensionDto) SetConfigurationNil(b bool)`

 SetConfigurationNil sets the value for Configuration to be an explicit nil

### UnsetConfiguration
`func (o *EntityExtensionDto) UnsetConfiguration()`

UnsetConfiguration ensures that no value is present for Configuration, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


