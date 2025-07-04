# IdentityRoleCreateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExtraProperties** | Pointer to **map[string]interface{}** |  | [optional] [readonly] 
**Name** | **string** |  | 
**IsDefault** | Pointer to **bool** |  | [optional] 
**IsPublic** | Pointer to **bool** |  | [optional] 

## Methods

### NewIdentityRoleCreateDto

`func NewIdentityRoleCreateDto(name string, ) *IdentityRoleCreateDto`

NewIdentityRoleCreateDto instantiates a new IdentityRoleCreateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIdentityRoleCreateDtoWithDefaults

`func NewIdentityRoleCreateDtoWithDefaults() *IdentityRoleCreateDto`

NewIdentityRoleCreateDtoWithDefaults instantiates a new IdentityRoleCreateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExtraProperties

`func (o *IdentityRoleCreateDto) GetExtraProperties() map[string]interface{}`

GetExtraProperties returns the ExtraProperties field if non-nil, zero value otherwise.

### GetExtraPropertiesOk

`func (o *IdentityRoleCreateDto) GetExtraPropertiesOk() (*map[string]interface{}, bool)`

GetExtraPropertiesOk returns a tuple with the ExtraProperties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtraProperties

`func (o *IdentityRoleCreateDto) SetExtraProperties(v map[string]interface{})`

SetExtraProperties sets ExtraProperties field to given value.

### HasExtraProperties

`func (o *IdentityRoleCreateDto) HasExtraProperties() bool`

HasExtraProperties returns a boolean if a field has been set.

### SetExtraPropertiesNil

`func (o *IdentityRoleCreateDto) SetExtraPropertiesNil(b bool)`

 SetExtraPropertiesNil sets the value for ExtraProperties to be an explicit nil

### UnsetExtraProperties
`func (o *IdentityRoleCreateDto) UnsetExtraProperties()`

UnsetExtraProperties ensures that no value is present for ExtraProperties, not even an explicit nil
### GetName

`func (o *IdentityRoleCreateDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *IdentityRoleCreateDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *IdentityRoleCreateDto) SetName(v string)`

SetName sets Name field to given value.


### GetIsDefault

`func (o *IdentityRoleCreateDto) GetIsDefault() bool`

GetIsDefault returns the IsDefault field if non-nil, zero value otherwise.

### GetIsDefaultOk

`func (o *IdentityRoleCreateDto) GetIsDefaultOk() (*bool, bool)`

GetIsDefaultOk returns a tuple with the IsDefault field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDefault

`func (o *IdentityRoleCreateDto) SetIsDefault(v bool)`

SetIsDefault sets IsDefault field to given value.

### HasIsDefault

`func (o *IdentityRoleCreateDto) HasIsDefault() bool`

HasIsDefault returns a boolean if a field has been set.

### GetIsPublic

`func (o *IdentityRoleCreateDto) GetIsPublic() bool`

GetIsPublic returns the IsPublic field if non-nil, zero value otherwise.

### GetIsPublicOk

`func (o *IdentityRoleCreateDto) GetIsPublicOk() (*bool, bool)`

GetIsPublicOk returns a tuple with the IsPublic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPublic

`func (o *IdentityRoleCreateDto) SetIsPublic(v bool)`

SetIsPublic sets IsPublic field to given value.

### HasIsPublic

`func (o *IdentityRoleCreateDto) HasIsPublic() bool`

HasIsPublic returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


