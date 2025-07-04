# IStringValueType

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **NullableString** |  | [optional] [readonly] 
**Properties** | Pointer to **map[string]interface{}** |  | [optional] [readonly] 
**Validator** | Pointer to [**IValueValidator**](IValueValidator.md) |  | [optional] 

## Methods

### NewIStringValueType

`func NewIStringValueType() *IStringValueType`

NewIStringValueType instantiates a new IStringValueType object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIStringValueTypeWithDefaults

`func NewIStringValueTypeWithDefaults() *IStringValueType`

NewIStringValueTypeWithDefaults instantiates a new IStringValueType object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *IStringValueType) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *IStringValueType) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *IStringValueType) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *IStringValueType) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *IStringValueType) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *IStringValueType) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetProperties

`func (o *IStringValueType) GetProperties() map[string]interface{}`

GetProperties returns the Properties field if non-nil, zero value otherwise.

### GetPropertiesOk

`func (o *IStringValueType) GetPropertiesOk() (*map[string]interface{}, bool)`

GetPropertiesOk returns a tuple with the Properties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperties

`func (o *IStringValueType) SetProperties(v map[string]interface{})`

SetProperties sets Properties field to given value.

### HasProperties

`func (o *IStringValueType) HasProperties() bool`

HasProperties returns a boolean if a field has been set.

### SetPropertiesNil

`func (o *IStringValueType) SetPropertiesNil(b bool)`

 SetPropertiesNil sets the value for Properties to be an explicit nil

### UnsetProperties
`func (o *IStringValueType) UnsetProperties()`

UnsetProperties ensures that no value is present for Properties, not even an explicit nil
### GetValidator

`func (o *IStringValueType) GetValidator() IValueValidator`

GetValidator returns the Validator field if non-nil, zero value otherwise.

### GetValidatorOk

`func (o *IStringValueType) GetValidatorOk() (*IValueValidator, bool)`

GetValidatorOk returns a tuple with the Validator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidator

`func (o *IStringValueType) SetValidator(v IValueValidator)`

SetValidator sets Validator field to given value.

### HasValidator

`func (o *IStringValueType) HasValidator() bool`

HasValidator returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


