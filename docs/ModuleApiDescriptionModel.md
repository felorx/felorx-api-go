# ModuleApiDescriptionModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RootPath** | Pointer to **NullableString** |  | [optional] 
**RemoteServiceName** | Pointer to **NullableString** |  | [optional] 
**Controllers** | Pointer to [**map[string]ControllerApiDescriptionModel**](ControllerApiDescriptionModel.md) |  | [optional] 

## Methods

### NewModuleApiDescriptionModel

`func NewModuleApiDescriptionModel() *ModuleApiDescriptionModel`

NewModuleApiDescriptionModel instantiates a new ModuleApiDescriptionModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewModuleApiDescriptionModelWithDefaults

`func NewModuleApiDescriptionModelWithDefaults() *ModuleApiDescriptionModel`

NewModuleApiDescriptionModelWithDefaults instantiates a new ModuleApiDescriptionModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRootPath

`func (o *ModuleApiDescriptionModel) GetRootPath() string`

GetRootPath returns the RootPath field if non-nil, zero value otherwise.

### GetRootPathOk

`func (o *ModuleApiDescriptionModel) GetRootPathOk() (*string, bool)`

GetRootPathOk returns a tuple with the RootPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRootPath

`func (o *ModuleApiDescriptionModel) SetRootPath(v string)`

SetRootPath sets RootPath field to given value.

### HasRootPath

`func (o *ModuleApiDescriptionModel) HasRootPath() bool`

HasRootPath returns a boolean if a field has been set.

### SetRootPathNil

`func (o *ModuleApiDescriptionModel) SetRootPathNil(b bool)`

 SetRootPathNil sets the value for RootPath to be an explicit nil

### UnsetRootPath
`func (o *ModuleApiDescriptionModel) UnsetRootPath()`

UnsetRootPath ensures that no value is present for RootPath, not even an explicit nil
### GetRemoteServiceName

`func (o *ModuleApiDescriptionModel) GetRemoteServiceName() string`

GetRemoteServiceName returns the RemoteServiceName field if non-nil, zero value otherwise.

### GetRemoteServiceNameOk

`func (o *ModuleApiDescriptionModel) GetRemoteServiceNameOk() (*string, bool)`

GetRemoteServiceNameOk returns a tuple with the RemoteServiceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemoteServiceName

`func (o *ModuleApiDescriptionModel) SetRemoteServiceName(v string)`

SetRemoteServiceName sets RemoteServiceName field to given value.

### HasRemoteServiceName

`func (o *ModuleApiDescriptionModel) HasRemoteServiceName() bool`

HasRemoteServiceName returns a boolean if a field has been set.

### SetRemoteServiceNameNil

`func (o *ModuleApiDescriptionModel) SetRemoteServiceNameNil(b bool)`

 SetRemoteServiceNameNil sets the value for RemoteServiceName to be an explicit nil

### UnsetRemoteServiceName
`func (o *ModuleApiDescriptionModel) UnsetRemoteServiceName()`

UnsetRemoteServiceName ensures that no value is present for RemoteServiceName, not even an explicit nil
### GetControllers

`func (o *ModuleApiDescriptionModel) GetControllers() map[string]ControllerApiDescriptionModel`

GetControllers returns the Controllers field if non-nil, zero value otherwise.

### GetControllersOk

`func (o *ModuleApiDescriptionModel) GetControllersOk() (*map[string]ControllerApiDescriptionModel, bool)`

GetControllersOk returns a tuple with the Controllers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControllers

`func (o *ModuleApiDescriptionModel) SetControllers(v map[string]ControllerApiDescriptionModel)`

SetControllers sets Controllers field to given value.

### HasControllers

`func (o *ModuleApiDescriptionModel) HasControllers() bool`

HasControllers returns a boolean if a field has been set.

### SetControllersNil

`func (o *ModuleApiDescriptionModel) SetControllersNil(b bool)`

 SetControllersNil sets the value for Controllers to be an explicit nil

### UnsetControllers
`func (o *ModuleApiDescriptionModel) UnsetControllers()`

UnsetControllers ensures that no value is present for Controllers, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


