# ObjectExtensionsDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Modules** | Pointer to [**map[string]ModuleExtensionDto**](ModuleExtensionDto.md) |  | [optional] 
**Enums** | Pointer to [**map[string]ExtensionEnumDto**](ExtensionEnumDto.md) |  | [optional] 

## Methods

### NewObjectExtensionsDto

`func NewObjectExtensionsDto() *ObjectExtensionsDto`

NewObjectExtensionsDto instantiates a new ObjectExtensionsDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewObjectExtensionsDtoWithDefaults

`func NewObjectExtensionsDtoWithDefaults() *ObjectExtensionsDto`

NewObjectExtensionsDtoWithDefaults instantiates a new ObjectExtensionsDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetModules

`func (o *ObjectExtensionsDto) GetModules() map[string]ModuleExtensionDto`

GetModules returns the Modules field if non-nil, zero value otherwise.

### GetModulesOk

`func (o *ObjectExtensionsDto) GetModulesOk() (*map[string]ModuleExtensionDto, bool)`

GetModulesOk returns a tuple with the Modules field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModules

`func (o *ObjectExtensionsDto) SetModules(v map[string]ModuleExtensionDto)`

SetModules sets Modules field to given value.

### HasModules

`func (o *ObjectExtensionsDto) HasModules() bool`

HasModules returns a boolean if a field has been set.

### SetModulesNil

`func (o *ObjectExtensionsDto) SetModulesNil(b bool)`

 SetModulesNil sets the value for Modules to be an explicit nil

### UnsetModules
`func (o *ObjectExtensionsDto) UnsetModules()`

UnsetModules ensures that no value is present for Modules, not even an explicit nil
### GetEnums

`func (o *ObjectExtensionsDto) GetEnums() map[string]ExtensionEnumDto`

GetEnums returns the Enums field if non-nil, zero value otherwise.

### GetEnumsOk

`func (o *ObjectExtensionsDto) GetEnumsOk() (*map[string]ExtensionEnumDto, bool)`

GetEnumsOk returns a tuple with the Enums field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnums

`func (o *ObjectExtensionsDto) SetEnums(v map[string]ExtensionEnumDto)`

SetEnums sets Enums field to given value.

### HasEnums

`func (o *ObjectExtensionsDto) HasEnums() bool`

HasEnums returns a boolean if a field has been set.

### SetEnumsNil

`func (o *ObjectExtensionsDto) SetEnumsNil(b bool)`

 SetEnumsNil sets the value for Enums to be an explicit nil

### UnsetEnums
`func (o *ObjectExtensionsDto) UnsetEnums()`

UnsetEnums ensures that no value is present for Enums, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


