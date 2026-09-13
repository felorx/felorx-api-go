# ApplicationApiDescriptionModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Modules** | Pointer to [**map[string]ModuleApiDescriptionModel**](ModuleApiDescriptionModel.md) |  | [optional] 
**Types** | Pointer to [**map[string]TypeApiDescriptionModel**](TypeApiDescriptionModel.md) |  | [optional] 

## Methods

### NewApplicationApiDescriptionModel

`func NewApplicationApiDescriptionModel() *ApplicationApiDescriptionModel`

NewApplicationApiDescriptionModel instantiates a new ApplicationApiDescriptionModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApplicationApiDescriptionModelWithDefaults

`func NewApplicationApiDescriptionModelWithDefaults() *ApplicationApiDescriptionModel`

NewApplicationApiDescriptionModelWithDefaults instantiates a new ApplicationApiDescriptionModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetModules

`func (o *ApplicationApiDescriptionModel) GetModules() map[string]ModuleApiDescriptionModel`

GetModules returns the Modules field if non-nil, zero value otherwise.

### GetModulesOk

`func (o *ApplicationApiDescriptionModel) GetModulesOk() (*map[string]ModuleApiDescriptionModel, bool)`

GetModulesOk returns a tuple with the Modules field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModules

`func (o *ApplicationApiDescriptionModel) SetModules(v map[string]ModuleApiDescriptionModel)`

SetModules sets Modules field to given value.

### HasModules

`func (o *ApplicationApiDescriptionModel) HasModules() bool`

HasModules returns a boolean if a field has been set.

### SetModulesNil

`func (o *ApplicationApiDescriptionModel) SetModulesNil(b bool)`

 SetModulesNil sets the value for Modules to be an explicit nil

### UnsetModules
`func (o *ApplicationApiDescriptionModel) UnsetModules()`

UnsetModules ensures that no value is present for Modules, not even an explicit nil
### GetTypes

`func (o *ApplicationApiDescriptionModel) GetTypes() map[string]TypeApiDescriptionModel`

GetTypes returns the Types field if non-nil, zero value otherwise.

### GetTypesOk

`func (o *ApplicationApiDescriptionModel) GetTypesOk() (*map[string]TypeApiDescriptionModel, bool)`

GetTypesOk returns a tuple with the Types field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTypes

`func (o *ApplicationApiDescriptionModel) SetTypes(v map[string]TypeApiDescriptionModel)`

SetTypes sets Types field to given value.

### HasTypes

`func (o *ApplicationApiDescriptionModel) HasTypes() bool`

HasTypes returns a boolean if a field has been set.

### SetTypesNil

`func (o *ApplicationApiDescriptionModel) SetTypesNil(b bool)`

 SetTypesNil sets the value for Types to be an explicit nil

### UnsetTypes
`func (o *ApplicationApiDescriptionModel) UnsetTypes()`

UnsetTypes ensures that no value is present for Types, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


