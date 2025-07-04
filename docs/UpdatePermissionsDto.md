# UpdatePermissionsDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Permissions** | Pointer to [**[]UpdatePermissionDto**](UpdatePermissionDto.md) |  | [optional] 

## Methods

### NewUpdatePermissionsDto

`func NewUpdatePermissionsDto() *UpdatePermissionsDto`

NewUpdatePermissionsDto instantiates a new UpdatePermissionsDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdatePermissionsDtoWithDefaults

`func NewUpdatePermissionsDtoWithDefaults() *UpdatePermissionsDto`

NewUpdatePermissionsDtoWithDefaults instantiates a new UpdatePermissionsDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPermissions

`func (o *UpdatePermissionsDto) GetPermissions() []UpdatePermissionDto`

GetPermissions returns the Permissions field if non-nil, zero value otherwise.

### GetPermissionsOk

`func (o *UpdatePermissionsDto) GetPermissionsOk() (*[]UpdatePermissionDto, bool)`

GetPermissionsOk returns a tuple with the Permissions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPermissions

`func (o *UpdatePermissionsDto) SetPermissions(v []UpdatePermissionDto)`

SetPermissions sets Permissions field to given value.

### HasPermissions

`func (o *UpdatePermissionsDto) HasPermissions() bool`

HasPermissions returns a boolean if a field has been set.

### SetPermissionsNil

`func (o *UpdatePermissionsDto) SetPermissionsNil(b bool)`

 SetPermissionsNil sets the value for Permissions to be an explicit nil

### UnsetPermissions
`func (o *UpdatePermissionsDto) UnsetPermissions()`

UnsetPermissions ensures that no value is present for Permissions, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


