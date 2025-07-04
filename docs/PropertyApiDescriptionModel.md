# PropertyApiDescriptionModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **NullableString** |  | [optional] 
**JsonName** | Pointer to **NullableString** |  | [optional] 
**Type** | Pointer to **NullableString** |  | [optional] 
**TypeSimple** | Pointer to **NullableString** |  | [optional] 
**IsRequired** | Pointer to **bool** |  | [optional] 
**MinLength** | Pointer to **NullableInt32** |  | [optional] 
**MaxLength** | Pointer to **NullableInt32** |  | [optional] 
**Minimum** | Pointer to **NullableString** |  | [optional] 
**Maximum** | Pointer to **NullableString** |  | [optional] 
**Regex** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewPropertyApiDescriptionModel

`func NewPropertyApiDescriptionModel() *PropertyApiDescriptionModel`

NewPropertyApiDescriptionModel instantiates a new PropertyApiDescriptionModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPropertyApiDescriptionModelWithDefaults

`func NewPropertyApiDescriptionModelWithDefaults() *PropertyApiDescriptionModel`

NewPropertyApiDescriptionModelWithDefaults instantiates a new PropertyApiDescriptionModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *PropertyApiDescriptionModel) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PropertyApiDescriptionModel) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PropertyApiDescriptionModel) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *PropertyApiDescriptionModel) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *PropertyApiDescriptionModel) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *PropertyApiDescriptionModel) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetJsonName

`func (o *PropertyApiDescriptionModel) GetJsonName() string`

GetJsonName returns the JsonName field if non-nil, zero value otherwise.

### GetJsonNameOk

`func (o *PropertyApiDescriptionModel) GetJsonNameOk() (*string, bool)`

GetJsonNameOk returns a tuple with the JsonName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJsonName

`func (o *PropertyApiDescriptionModel) SetJsonName(v string)`

SetJsonName sets JsonName field to given value.

### HasJsonName

`func (o *PropertyApiDescriptionModel) HasJsonName() bool`

HasJsonName returns a boolean if a field has been set.

### SetJsonNameNil

`func (o *PropertyApiDescriptionModel) SetJsonNameNil(b bool)`

 SetJsonNameNil sets the value for JsonName to be an explicit nil

### UnsetJsonName
`func (o *PropertyApiDescriptionModel) UnsetJsonName()`

UnsetJsonName ensures that no value is present for JsonName, not even an explicit nil
### GetType

`func (o *PropertyApiDescriptionModel) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PropertyApiDescriptionModel) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PropertyApiDescriptionModel) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *PropertyApiDescriptionModel) HasType() bool`

HasType returns a boolean if a field has been set.

### SetTypeNil

`func (o *PropertyApiDescriptionModel) SetTypeNil(b bool)`

 SetTypeNil sets the value for Type to be an explicit nil

### UnsetType
`func (o *PropertyApiDescriptionModel) UnsetType()`

UnsetType ensures that no value is present for Type, not even an explicit nil
### GetTypeSimple

`func (o *PropertyApiDescriptionModel) GetTypeSimple() string`

GetTypeSimple returns the TypeSimple field if non-nil, zero value otherwise.

### GetTypeSimpleOk

`func (o *PropertyApiDescriptionModel) GetTypeSimpleOk() (*string, bool)`

GetTypeSimpleOk returns a tuple with the TypeSimple field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTypeSimple

`func (o *PropertyApiDescriptionModel) SetTypeSimple(v string)`

SetTypeSimple sets TypeSimple field to given value.

### HasTypeSimple

`func (o *PropertyApiDescriptionModel) HasTypeSimple() bool`

HasTypeSimple returns a boolean if a field has been set.

### SetTypeSimpleNil

`func (o *PropertyApiDescriptionModel) SetTypeSimpleNil(b bool)`

 SetTypeSimpleNil sets the value for TypeSimple to be an explicit nil

### UnsetTypeSimple
`func (o *PropertyApiDescriptionModel) UnsetTypeSimple()`

UnsetTypeSimple ensures that no value is present for TypeSimple, not even an explicit nil
### GetIsRequired

`func (o *PropertyApiDescriptionModel) GetIsRequired() bool`

GetIsRequired returns the IsRequired field if non-nil, zero value otherwise.

### GetIsRequiredOk

`func (o *PropertyApiDescriptionModel) GetIsRequiredOk() (*bool, bool)`

GetIsRequiredOk returns a tuple with the IsRequired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsRequired

`func (o *PropertyApiDescriptionModel) SetIsRequired(v bool)`

SetIsRequired sets IsRequired field to given value.

### HasIsRequired

`func (o *PropertyApiDescriptionModel) HasIsRequired() bool`

HasIsRequired returns a boolean if a field has been set.

### GetMinLength

`func (o *PropertyApiDescriptionModel) GetMinLength() int32`

GetMinLength returns the MinLength field if non-nil, zero value otherwise.

### GetMinLengthOk

`func (o *PropertyApiDescriptionModel) GetMinLengthOk() (*int32, bool)`

GetMinLengthOk returns a tuple with the MinLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinLength

`func (o *PropertyApiDescriptionModel) SetMinLength(v int32)`

SetMinLength sets MinLength field to given value.

### HasMinLength

`func (o *PropertyApiDescriptionModel) HasMinLength() bool`

HasMinLength returns a boolean if a field has been set.

### SetMinLengthNil

`func (o *PropertyApiDescriptionModel) SetMinLengthNil(b bool)`

 SetMinLengthNil sets the value for MinLength to be an explicit nil

### UnsetMinLength
`func (o *PropertyApiDescriptionModel) UnsetMinLength()`

UnsetMinLength ensures that no value is present for MinLength, not even an explicit nil
### GetMaxLength

`func (o *PropertyApiDescriptionModel) GetMaxLength() int32`

GetMaxLength returns the MaxLength field if non-nil, zero value otherwise.

### GetMaxLengthOk

`func (o *PropertyApiDescriptionModel) GetMaxLengthOk() (*int32, bool)`

GetMaxLengthOk returns a tuple with the MaxLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxLength

`func (o *PropertyApiDescriptionModel) SetMaxLength(v int32)`

SetMaxLength sets MaxLength field to given value.

### HasMaxLength

`func (o *PropertyApiDescriptionModel) HasMaxLength() bool`

HasMaxLength returns a boolean if a field has been set.

### SetMaxLengthNil

`func (o *PropertyApiDescriptionModel) SetMaxLengthNil(b bool)`

 SetMaxLengthNil sets the value for MaxLength to be an explicit nil

### UnsetMaxLength
`func (o *PropertyApiDescriptionModel) UnsetMaxLength()`

UnsetMaxLength ensures that no value is present for MaxLength, not even an explicit nil
### GetMinimum

`func (o *PropertyApiDescriptionModel) GetMinimum() string`

GetMinimum returns the Minimum field if non-nil, zero value otherwise.

### GetMinimumOk

`func (o *PropertyApiDescriptionModel) GetMinimumOk() (*string, bool)`

GetMinimumOk returns a tuple with the Minimum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinimum

`func (o *PropertyApiDescriptionModel) SetMinimum(v string)`

SetMinimum sets Minimum field to given value.

### HasMinimum

`func (o *PropertyApiDescriptionModel) HasMinimum() bool`

HasMinimum returns a boolean if a field has been set.

### SetMinimumNil

`func (o *PropertyApiDescriptionModel) SetMinimumNil(b bool)`

 SetMinimumNil sets the value for Minimum to be an explicit nil

### UnsetMinimum
`func (o *PropertyApiDescriptionModel) UnsetMinimum()`

UnsetMinimum ensures that no value is present for Minimum, not even an explicit nil
### GetMaximum

`func (o *PropertyApiDescriptionModel) GetMaximum() string`

GetMaximum returns the Maximum field if non-nil, zero value otherwise.

### GetMaximumOk

`func (o *PropertyApiDescriptionModel) GetMaximumOk() (*string, bool)`

GetMaximumOk returns a tuple with the Maximum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaximum

`func (o *PropertyApiDescriptionModel) SetMaximum(v string)`

SetMaximum sets Maximum field to given value.

### HasMaximum

`func (o *PropertyApiDescriptionModel) HasMaximum() bool`

HasMaximum returns a boolean if a field has been set.

### SetMaximumNil

`func (o *PropertyApiDescriptionModel) SetMaximumNil(b bool)`

 SetMaximumNil sets the value for Maximum to be an explicit nil

### UnsetMaximum
`func (o *PropertyApiDescriptionModel) UnsetMaximum()`

UnsetMaximum ensures that no value is present for Maximum, not even an explicit nil
### GetRegex

`func (o *PropertyApiDescriptionModel) GetRegex() string`

GetRegex returns the Regex field if non-nil, zero value otherwise.

### GetRegexOk

`func (o *PropertyApiDescriptionModel) GetRegexOk() (*string, bool)`

GetRegexOk returns a tuple with the Regex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegex

`func (o *PropertyApiDescriptionModel) SetRegex(v string)`

SetRegex sets Regex field to given value.

### HasRegex

`func (o *PropertyApiDescriptionModel) HasRegex() bool`

HasRegex returns a boolean if a field has been set.

### SetRegexNil

`func (o *PropertyApiDescriptionModel) SetRegexNil(b bool)`

 SetRegexNil sets the value for Regex to be an explicit nil

### UnsetRegex
`func (o *PropertyApiDescriptionModel) UnsetRegex()`

UnsetRegex ensures that no value is present for Regex, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


