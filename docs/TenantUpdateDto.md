# TenantUpdateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExtraProperties** | Pointer to **map[string]interface{}** |  | [optional] [readonly] 
**Name** | **string** |  | 
**ConcurrencyStamp** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewTenantUpdateDto

`func NewTenantUpdateDto(name string, ) *TenantUpdateDto`

NewTenantUpdateDto instantiates a new TenantUpdateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTenantUpdateDtoWithDefaults

`func NewTenantUpdateDtoWithDefaults() *TenantUpdateDto`

NewTenantUpdateDtoWithDefaults instantiates a new TenantUpdateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExtraProperties

`func (o *TenantUpdateDto) GetExtraProperties() map[string]interface{}`

GetExtraProperties returns the ExtraProperties field if non-nil, zero value otherwise.

### GetExtraPropertiesOk

`func (o *TenantUpdateDto) GetExtraPropertiesOk() (*map[string]interface{}, bool)`

GetExtraPropertiesOk returns a tuple with the ExtraProperties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtraProperties

`func (o *TenantUpdateDto) SetExtraProperties(v map[string]interface{})`

SetExtraProperties sets ExtraProperties field to given value.

### HasExtraProperties

`func (o *TenantUpdateDto) HasExtraProperties() bool`

HasExtraProperties returns a boolean if a field has been set.

### SetExtraPropertiesNil

`func (o *TenantUpdateDto) SetExtraPropertiesNil(b bool)`

 SetExtraPropertiesNil sets the value for ExtraProperties to be an explicit nil

### UnsetExtraProperties
`func (o *TenantUpdateDto) UnsetExtraProperties()`

UnsetExtraProperties ensures that no value is present for ExtraProperties, not even an explicit nil
### GetName

`func (o *TenantUpdateDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *TenantUpdateDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *TenantUpdateDto) SetName(v string)`

SetName sets Name field to given value.


### GetConcurrencyStamp

`func (o *TenantUpdateDto) GetConcurrencyStamp() string`

GetConcurrencyStamp returns the ConcurrencyStamp field if non-nil, zero value otherwise.

### GetConcurrencyStampOk

`func (o *TenantUpdateDto) GetConcurrencyStampOk() (*string, bool)`

GetConcurrencyStampOk returns a tuple with the ConcurrencyStamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConcurrencyStamp

`func (o *TenantUpdateDto) SetConcurrencyStamp(v string)`

SetConcurrencyStamp sets ConcurrencyStamp field to given value.

### HasConcurrencyStamp

`func (o *TenantUpdateDto) HasConcurrencyStamp() bool`

HasConcurrencyStamp returns a boolean if a field has been set.

### SetConcurrencyStampNil

`func (o *TenantUpdateDto) SetConcurrencyStampNil(b bool)`

 SetConcurrencyStampNil sets the value for ConcurrencyStamp to be an explicit nil

### UnsetConcurrencyStamp
`func (o *TenantUpdateDto) UnsetConcurrencyStamp()`

UnsetConcurrencyStamp ensures that no value is present for ConcurrencyStamp, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


