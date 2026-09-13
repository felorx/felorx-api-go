# TypeApiDescriptionModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BaseType** | Pointer to **NullableString** |  | [optional] 
**IsEnum** | Pointer to **bool** |  | [optional] 
**EnumNames** | Pointer to **[]string** |  | [optional] 
**EnumValues** | Pointer to **[]interface{}** |  | [optional] 
**GenericArguments** | Pointer to **[]string** |  | [optional] 
**Properties** | Pointer to [**[]PropertyApiDescriptionModel**](PropertyApiDescriptionModel.md) |  | [optional] 

## Methods

### NewTypeApiDescriptionModel

`func NewTypeApiDescriptionModel() *TypeApiDescriptionModel`

NewTypeApiDescriptionModel instantiates a new TypeApiDescriptionModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTypeApiDescriptionModelWithDefaults

`func NewTypeApiDescriptionModelWithDefaults() *TypeApiDescriptionModel`

NewTypeApiDescriptionModelWithDefaults instantiates a new TypeApiDescriptionModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBaseType

`func (o *TypeApiDescriptionModel) GetBaseType() string`

GetBaseType returns the BaseType field if non-nil, zero value otherwise.

### GetBaseTypeOk

`func (o *TypeApiDescriptionModel) GetBaseTypeOk() (*string, bool)`

GetBaseTypeOk returns a tuple with the BaseType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBaseType

`func (o *TypeApiDescriptionModel) SetBaseType(v string)`

SetBaseType sets BaseType field to given value.

### HasBaseType

`func (o *TypeApiDescriptionModel) HasBaseType() bool`

HasBaseType returns a boolean if a field has been set.

### SetBaseTypeNil

`func (o *TypeApiDescriptionModel) SetBaseTypeNil(b bool)`

 SetBaseTypeNil sets the value for BaseType to be an explicit nil

### UnsetBaseType
`func (o *TypeApiDescriptionModel) UnsetBaseType()`

UnsetBaseType ensures that no value is present for BaseType, not even an explicit nil
### GetIsEnum

`func (o *TypeApiDescriptionModel) GetIsEnum() bool`

GetIsEnum returns the IsEnum field if non-nil, zero value otherwise.

### GetIsEnumOk

`func (o *TypeApiDescriptionModel) GetIsEnumOk() (*bool, bool)`

GetIsEnumOk returns a tuple with the IsEnum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsEnum

`func (o *TypeApiDescriptionModel) SetIsEnum(v bool)`

SetIsEnum sets IsEnum field to given value.

### HasIsEnum

`func (o *TypeApiDescriptionModel) HasIsEnum() bool`

HasIsEnum returns a boolean if a field has been set.

### GetEnumNames

`func (o *TypeApiDescriptionModel) GetEnumNames() []string`

GetEnumNames returns the EnumNames field if non-nil, zero value otherwise.

### GetEnumNamesOk

`func (o *TypeApiDescriptionModel) GetEnumNamesOk() (*[]string, bool)`

GetEnumNamesOk returns a tuple with the EnumNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnumNames

`func (o *TypeApiDescriptionModel) SetEnumNames(v []string)`

SetEnumNames sets EnumNames field to given value.

### HasEnumNames

`func (o *TypeApiDescriptionModel) HasEnumNames() bool`

HasEnumNames returns a boolean if a field has been set.

### SetEnumNamesNil

`func (o *TypeApiDescriptionModel) SetEnumNamesNil(b bool)`

 SetEnumNamesNil sets the value for EnumNames to be an explicit nil

### UnsetEnumNames
`func (o *TypeApiDescriptionModel) UnsetEnumNames()`

UnsetEnumNames ensures that no value is present for EnumNames, not even an explicit nil
### GetEnumValues

`func (o *TypeApiDescriptionModel) GetEnumValues() []interface{}`

GetEnumValues returns the EnumValues field if non-nil, zero value otherwise.

### GetEnumValuesOk

`func (o *TypeApiDescriptionModel) GetEnumValuesOk() (*[]interface{}, bool)`

GetEnumValuesOk returns a tuple with the EnumValues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnumValues

`func (o *TypeApiDescriptionModel) SetEnumValues(v []interface{})`

SetEnumValues sets EnumValues field to given value.

### HasEnumValues

`func (o *TypeApiDescriptionModel) HasEnumValues() bool`

HasEnumValues returns a boolean if a field has been set.

### SetEnumValuesNil

`func (o *TypeApiDescriptionModel) SetEnumValuesNil(b bool)`

 SetEnumValuesNil sets the value for EnumValues to be an explicit nil

### UnsetEnumValues
`func (o *TypeApiDescriptionModel) UnsetEnumValues()`

UnsetEnumValues ensures that no value is present for EnumValues, not even an explicit nil
### GetGenericArguments

`func (o *TypeApiDescriptionModel) GetGenericArguments() []string`

GetGenericArguments returns the GenericArguments field if non-nil, zero value otherwise.

### GetGenericArgumentsOk

`func (o *TypeApiDescriptionModel) GetGenericArgumentsOk() (*[]string, bool)`

GetGenericArgumentsOk returns a tuple with the GenericArguments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenericArguments

`func (o *TypeApiDescriptionModel) SetGenericArguments(v []string)`

SetGenericArguments sets GenericArguments field to given value.

### HasGenericArguments

`func (o *TypeApiDescriptionModel) HasGenericArguments() bool`

HasGenericArguments returns a boolean if a field has been set.

### SetGenericArgumentsNil

`func (o *TypeApiDescriptionModel) SetGenericArgumentsNil(b bool)`

 SetGenericArgumentsNil sets the value for GenericArguments to be an explicit nil

### UnsetGenericArguments
`func (o *TypeApiDescriptionModel) UnsetGenericArguments()`

UnsetGenericArguments ensures that no value is present for GenericArguments, not even an explicit nil
### GetProperties

`func (o *TypeApiDescriptionModel) GetProperties() []PropertyApiDescriptionModel`

GetProperties returns the Properties field if non-nil, zero value otherwise.

### GetPropertiesOk

`func (o *TypeApiDescriptionModel) GetPropertiesOk() (*[]PropertyApiDescriptionModel, bool)`

GetPropertiesOk returns a tuple with the Properties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperties

`func (o *TypeApiDescriptionModel) SetProperties(v []PropertyApiDescriptionModel)`

SetProperties sets Properties field to given value.

### HasProperties

`func (o *TypeApiDescriptionModel) HasProperties() bool`

HasProperties returns a boolean if a field has been set.

### SetPropertiesNil

`func (o *TypeApiDescriptionModel) SetPropertiesNil(b bool)`

 SetPropertiesNil sets the value for Properties to be an explicit nil

### UnsetProperties
`func (o *TypeApiDescriptionModel) UnsetProperties()`

UnsetProperties ensures that no value is present for Properties, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


