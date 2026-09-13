# InterfaceMethodApiDescriptionModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **NullableString** |  | [optional] 
**ParametersOnMethod** | Pointer to [**[]MethodParameterApiDescriptionModel**](MethodParameterApiDescriptionModel.md) |  | [optional] 
**ReturnValue** | Pointer to [**ReturnValueApiDescriptionModel**](ReturnValueApiDescriptionModel.md) |  | [optional] 

## Methods

### NewInterfaceMethodApiDescriptionModel

`func NewInterfaceMethodApiDescriptionModel() *InterfaceMethodApiDescriptionModel`

NewInterfaceMethodApiDescriptionModel instantiates a new InterfaceMethodApiDescriptionModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInterfaceMethodApiDescriptionModelWithDefaults

`func NewInterfaceMethodApiDescriptionModelWithDefaults() *InterfaceMethodApiDescriptionModel`

NewInterfaceMethodApiDescriptionModelWithDefaults instantiates a new InterfaceMethodApiDescriptionModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *InterfaceMethodApiDescriptionModel) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *InterfaceMethodApiDescriptionModel) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *InterfaceMethodApiDescriptionModel) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *InterfaceMethodApiDescriptionModel) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *InterfaceMethodApiDescriptionModel) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *InterfaceMethodApiDescriptionModel) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetParametersOnMethod

`func (o *InterfaceMethodApiDescriptionModel) GetParametersOnMethod() []MethodParameterApiDescriptionModel`

GetParametersOnMethod returns the ParametersOnMethod field if non-nil, zero value otherwise.

### GetParametersOnMethodOk

`func (o *InterfaceMethodApiDescriptionModel) GetParametersOnMethodOk() (*[]MethodParameterApiDescriptionModel, bool)`

GetParametersOnMethodOk returns a tuple with the ParametersOnMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParametersOnMethod

`func (o *InterfaceMethodApiDescriptionModel) SetParametersOnMethod(v []MethodParameterApiDescriptionModel)`

SetParametersOnMethod sets ParametersOnMethod field to given value.

### HasParametersOnMethod

`func (o *InterfaceMethodApiDescriptionModel) HasParametersOnMethod() bool`

HasParametersOnMethod returns a boolean if a field has been set.

### SetParametersOnMethodNil

`func (o *InterfaceMethodApiDescriptionModel) SetParametersOnMethodNil(b bool)`

 SetParametersOnMethodNil sets the value for ParametersOnMethod to be an explicit nil

### UnsetParametersOnMethod
`func (o *InterfaceMethodApiDescriptionModel) UnsetParametersOnMethod()`

UnsetParametersOnMethod ensures that no value is present for ParametersOnMethod, not even an explicit nil
### GetReturnValue

`func (o *InterfaceMethodApiDescriptionModel) GetReturnValue() ReturnValueApiDescriptionModel`

GetReturnValue returns the ReturnValue field if non-nil, zero value otherwise.

### GetReturnValueOk

`func (o *InterfaceMethodApiDescriptionModel) GetReturnValueOk() (*ReturnValueApiDescriptionModel, bool)`

GetReturnValueOk returns a tuple with the ReturnValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnValue

`func (o *InterfaceMethodApiDescriptionModel) SetReturnValue(v ReturnValueApiDescriptionModel)`

SetReturnValue sets ReturnValue field to given value.

### HasReturnValue

`func (o *InterfaceMethodApiDescriptionModel) HasReturnValue() bool`

HasReturnValue returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


