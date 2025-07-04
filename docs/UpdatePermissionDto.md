# UpdatePermissionDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **NullableString** |  | [optional] 
**IsGranted** | Pointer to **bool** |  | [optional] 

## Methods

### NewUpdatePermissionDto

`func NewUpdatePermissionDto() *UpdatePermissionDto`

NewUpdatePermissionDto instantiates a new UpdatePermissionDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdatePermissionDtoWithDefaults

`func NewUpdatePermissionDtoWithDefaults() *UpdatePermissionDto`

NewUpdatePermissionDtoWithDefaults instantiates a new UpdatePermissionDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdatePermissionDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdatePermissionDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdatePermissionDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdatePermissionDto) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *UpdatePermissionDto) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *UpdatePermissionDto) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetIsGranted

`func (o *UpdatePermissionDto) GetIsGranted() bool`

GetIsGranted returns the IsGranted field if non-nil, zero value otherwise.

### GetIsGrantedOk

`func (o *UpdatePermissionDto) GetIsGrantedOk() (*bool, bool)`

GetIsGrantedOk returns a tuple with the IsGranted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsGranted

`func (o *UpdatePermissionDto) SetIsGranted(v bool)`

SetIsGranted sets IsGranted field to given value.

### HasIsGranted

`func (o *UpdatePermissionDto) HasIsGranted() bool`

HasIsGranted returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


