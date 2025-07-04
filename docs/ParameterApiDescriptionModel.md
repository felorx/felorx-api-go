# ParameterApiDescriptionModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NameOnMethod** | Pointer to **NullableString** |  | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 
**JsonName** | Pointer to **NullableString** |  | [optional] 
**Type** | Pointer to **NullableString** |  | [optional] 
**TypeSimple** | Pointer to **NullableString** |  | [optional] 
**IsOptional** | Pointer to **bool** |  | [optional] 
**DefaultValue** | Pointer to **interface{}** |  | [optional] 
**ConstraintTypes** | Pointer to **[]string** |  | [optional] 
**BindingSourceId** | Pointer to **NullableString** |  | [optional] 
**DescriptorName** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewParameterApiDescriptionModel

`func NewParameterApiDescriptionModel() *ParameterApiDescriptionModel`

NewParameterApiDescriptionModel instantiates a new ParameterApiDescriptionModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewParameterApiDescriptionModelWithDefaults

`func NewParameterApiDescriptionModelWithDefaults() *ParameterApiDescriptionModel`

NewParameterApiDescriptionModelWithDefaults instantiates a new ParameterApiDescriptionModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNameOnMethod

`func (o *ParameterApiDescriptionModel) GetNameOnMethod() string`

GetNameOnMethod returns the NameOnMethod field if non-nil, zero value otherwise.

### GetNameOnMethodOk

`func (o *ParameterApiDescriptionModel) GetNameOnMethodOk() (*string, bool)`

GetNameOnMethodOk returns a tuple with the NameOnMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNameOnMethod

`func (o *ParameterApiDescriptionModel) SetNameOnMethod(v string)`

SetNameOnMethod sets NameOnMethod field to given value.

### HasNameOnMethod

`func (o *ParameterApiDescriptionModel) HasNameOnMethod() bool`

HasNameOnMethod returns a boolean if a field has been set.

### SetNameOnMethodNil

`func (o *ParameterApiDescriptionModel) SetNameOnMethodNil(b bool)`

 SetNameOnMethodNil sets the value for NameOnMethod to be an explicit nil

### UnsetNameOnMethod
`func (o *ParameterApiDescriptionModel) UnsetNameOnMethod()`

UnsetNameOnMethod ensures that no value is present for NameOnMethod, not even an explicit nil
### GetName

`func (o *ParameterApiDescriptionModel) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ParameterApiDescriptionModel) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ParameterApiDescriptionModel) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ParameterApiDescriptionModel) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *ParameterApiDescriptionModel) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *ParameterApiDescriptionModel) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetJsonName

`func (o *ParameterApiDescriptionModel) GetJsonName() string`

GetJsonName returns the JsonName field if non-nil, zero value otherwise.

### GetJsonNameOk

`func (o *ParameterApiDescriptionModel) GetJsonNameOk() (*string, bool)`

GetJsonNameOk returns a tuple with the JsonName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJsonName

`func (o *ParameterApiDescriptionModel) SetJsonName(v string)`

SetJsonName sets JsonName field to given value.

### HasJsonName

`func (o *ParameterApiDescriptionModel) HasJsonName() bool`

HasJsonName returns a boolean if a field has been set.

### SetJsonNameNil

`func (o *ParameterApiDescriptionModel) SetJsonNameNil(b bool)`

 SetJsonNameNil sets the value for JsonName to be an explicit nil

### UnsetJsonName
`func (o *ParameterApiDescriptionModel) UnsetJsonName()`

UnsetJsonName ensures that no value is present for JsonName, not even an explicit nil
### GetType

`func (o *ParameterApiDescriptionModel) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ParameterApiDescriptionModel) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ParameterApiDescriptionModel) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ParameterApiDescriptionModel) HasType() bool`

HasType returns a boolean if a field has been set.

### SetTypeNil

`func (o *ParameterApiDescriptionModel) SetTypeNil(b bool)`

 SetTypeNil sets the value for Type to be an explicit nil

### UnsetType
`func (o *ParameterApiDescriptionModel) UnsetType()`

UnsetType ensures that no value is present for Type, not even an explicit nil
### GetTypeSimple

`func (o *ParameterApiDescriptionModel) GetTypeSimple() string`

GetTypeSimple returns the TypeSimple field if non-nil, zero value otherwise.

### GetTypeSimpleOk

`func (o *ParameterApiDescriptionModel) GetTypeSimpleOk() (*string, bool)`

GetTypeSimpleOk returns a tuple with the TypeSimple field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTypeSimple

`func (o *ParameterApiDescriptionModel) SetTypeSimple(v string)`

SetTypeSimple sets TypeSimple field to given value.

### HasTypeSimple

`func (o *ParameterApiDescriptionModel) HasTypeSimple() bool`

HasTypeSimple returns a boolean if a field has been set.

### SetTypeSimpleNil

`func (o *ParameterApiDescriptionModel) SetTypeSimpleNil(b bool)`

 SetTypeSimpleNil sets the value for TypeSimple to be an explicit nil

### UnsetTypeSimple
`func (o *ParameterApiDescriptionModel) UnsetTypeSimple()`

UnsetTypeSimple ensures that no value is present for TypeSimple, not even an explicit nil
### GetIsOptional

`func (o *ParameterApiDescriptionModel) GetIsOptional() bool`

GetIsOptional returns the IsOptional field if non-nil, zero value otherwise.

### GetIsOptionalOk

`func (o *ParameterApiDescriptionModel) GetIsOptionalOk() (*bool, bool)`

GetIsOptionalOk returns a tuple with the IsOptional field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsOptional

`func (o *ParameterApiDescriptionModel) SetIsOptional(v bool)`

SetIsOptional sets IsOptional field to given value.

### HasIsOptional

`func (o *ParameterApiDescriptionModel) HasIsOptional() bool`

HasIsOptional returns a boolean if a field has been set.

### GetDefaultValue

`func (o *ParameterApiDescriptionModel) GetDefaultValue() interface{}`

GetDefaultValue returns the DefaultValue field if non-nil, zero value otherwise.

### GetDefaultValueOk

`func (o *ParameterApiDescriptionModel) GetDefaultValueOk() (*interface{}, bool)`

GetDefaultValueOk returns a tuple with the DefaultValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultValue

`func (o *ParameterApiDescriptionModel) SetDefaultValue(v interface{})`

SetDefaultValue sets DefaultValue field to given value.

### HasDefaultValue

`func (o *ParameterApiDescriptionModel) HasDefaultValue() bool`

HasDefaultValue returns a boolean if a field has been set.

### SetDefaultValueNil

`func (o *ParameterApiDescriptionModel) SetDefaultValueNil(b bool)`

 SetDefaultValueNil sets the value for DefaultValue to be an explicit nil

### UnsetDefaultValue
`func (o *ParameterApiDescriptionModel) UnsetDefaultValue()`

UnsetDefaultValue ensures that no value is present for DefaultValue, not even an explicit nil
### GetConstraintTypes

`func (o *ParameterApiDescriptionModel) GetConstraintTypes() []string`

GetConstraintTypes returns the ConstraintTypes field if non-nil, zero value otherwise.

### GetConstraintTypesOk

`func (o *ParameterApiDescriptionModel) GetConstraintTypesOk() (*[]string, bool)`

GetConstraintTypesOk returns a tuple with the ConstraintTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConstraintTypes

`func (o *ParameterApiDescriptionModel) SetConstraintTypes(v []string)`

SetConstraintTypes sets ConstraintTypes field to given value.

### HasConstraintTypes

`func (o *ParameterApiDescriptionModel) HasConstraintTypes() bool`

HasConstraintTypes returns a boolean if a field has been set.

### SetConstraintTypesNil

`func (o *ParameterApiDescriptionModel) SetConstraintTypesNil(b bool)`

 SetConstraintTypesNil sets the value for ConstraintTypes to be an explicit nil

### UnsetConstraintTypes
`func (o *ParameterApiDescriptionModel) UnsetConstraintTypes()`

UnsetConstraintTypes ensures that no value is present for ConstraintTypes, not even an explicit nil
### GetBindingSourceId

`func (o *ParameterApiDescriptionModel) GetBindingSourceId() string`

GetBindingSourceId returns the BindingSourceId field if non-nil, zero value otherwise.

### GetBindingSourceIdOk

`func (o *ParameterApiDescriptionModel) GetBindingSourceIdOk() (*string, bool)`

GetBindingSourceIdOk returns a tuple with the BindingSourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBindingSourceId

`func (o *ParameterApiDescriptionModel) SetBindingSourceId(v string)`

SetBindingSourceId sets BindingSourceId field to given value.

### HasBindingSourceId

`func (o *ParameterApiDescriptionModel) HasBindingSourceId() bool`

HasBindingSourceId returns a boolean if a field has been set.

### SetBindingSourceIdNil

`func (o *ParameterApiDescriptionModel) SetBindingSourceIdNil(b bool)`

 SetBindingSourceIdNil sets the value for BindingSourceId to be an explicit nil

### UnsetBindingSourceId
`func (o *ParameterApiDescriptionModel) UnsetBindingSourceId()`

UnsetBindingSourceId ensures that no value is present for BindingSourceId, not even an explicit nil
### GetDescriptorName

`func (o *ParameterApiDescriptionModel) GetDescriptorName() string`

GetDescriptorName returns the DescriptorName field if non-nil, zero value otherwise.

### GetDescriptorNameOk

`func (o *ParameterApiDescriptionModel) GetDescriptorNameOk() (*string, bool)`

GetDescriptorNameOk returns a tuple with the DescriptorName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescriptorName

`func (o *ParameterApiDescriptionModel) SetDescriptorName(v string)`

SetDescriptorName sets DescriptorName field to given value.

### HasDescriptorName

`func (o *ParameterApiDescriptionModel) HasDescriptorName() bool`

HasDescriptorName returns a boolean if a field has been set.

### SetDescriptorNameNil

`func (o *ParameterApiDescriptionModel) SetDescriptorNameNil(b bool)`

 SetDescriptorNameNil sets the value for DescriptorName to be an explicit nil

### UnsetDescriptorName
`func (o *ParameterApiDescriptionModel) UnsetDescriptorName()`

UnsetDescriptorName ensures that no value is present for DescriptorName, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


