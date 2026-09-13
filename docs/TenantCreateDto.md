# TenantCreateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExtraProperties** | Pointer to **map[string]interface{}** |  | [optional] [readonly] 
**Name** | **string** |  | 
**AdminEmailAddress** | **string** |  | 
**AdminPassword** | **string** |  | 

## Methods

### NewTenantCreateDto

`func NewTenantCreateDto(name string, adminEmailAddress string, adminPassword string, ) *TenantCreateDto`

NewTenantCreateDto instantiates a new TenantCreateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTenantCreateDtoWithDefaults

`func NewTenantCreateDtoWithDefaults() *TenantCreateDto`

NewTenantCreateDtoWithDefaults instantiates a new TenantCreateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExtraProperties

`func (o *TenantCreateDto) GetExtraProperties() map[string]interface{}`

GetExtraProperties returns the ExtraProperties field if non-nil, zero value otherwise.

### GetExtraPropertiesOk

`func (o *TenantCreateDto) GetExtraPropertiesOk() (*map[string]interface{}, bool)`

GetExtraPropertiesOk returns a tuple with the ExtraProperties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtraProperties

`func (o *TenantCreateDto) SetExtraProperties(v map[string]interface{})`

SetExtraProperties sets ExtraProperties field to given value.

### HasExtraProperties

`func (o *TenantCreateDto) HasExtraProperties() bool`

HasExtraProperties returns a boolean if a field has been set.

### SetExtraPropertiesNil

`func (o *TenantCreateDto) SetExtraPropertiesNil(b bool)`

 SetExtraPropertiesNil sets the value for ExtraProperties to be an explicit nil

### UnsetExtraProperties
`func (o *TenantCreateDto) UnsetExtraProperties()`

UnsetExtraProperties ensures that no value is present for ExtraProperties, not even an explicit nil
### GetName

`func (o *TenantCreateDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *TenantCreateDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *TenantCreateDto) SetName(v string)`

SetName sets Name field to given value.


### GetAdminEmailAddress

`func (o *TenantCreateDto) GetAdminEmailAddress() string`

GetAdminEmailAddress returns the AdminEmailAddress field if non-nil, zero value otherwise.

### GetAdminEmailAddressOk

`func (o *TenantCreateDto) GetAdminEmailAddressOk() (*string, bool)`

GetAdminEmailAddressOk returns a tuple with the AdminEmailAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdminEmailAddress

`func (o *TenantCreateDto) SetAdminEmailAddress(v string)`

SetAdminEmailAddress sets AdminEmailAddress field to given value.


### GetAdminPassword

`func (o *TenantCreateDto) GetAdminPassword() string`

GetAdminPassword returns the AdminPassword field if non-nil, zero value otherwise.

### GetAdminPasswordOk

`func (o *TenantCreateDto) GetAdminPasswordOk() (*string, bool)`

GetAdminPasswordOk returns a tuple with the AdminPassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdminPassword

`func (o *TenantCreateDto) SetAdminPassword(v string)`

SetAdminPassword sets AdminPassword field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


