# ChangePasswordInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CurrentPassword** | Pointer to **NullableString** |  | [optional] 
**NewPassword** | **string** |  | 

## Methods

### NewChangePasswordInput

`func NewChangePasswordInput(newPassword string, ) *ChangePasswordInput`

NewChangePasswordInput instantiates a new ChangePasswordInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChangePasswordInputWithDefaults

`func NewChangePasswordInputWithDefaults() *ChangePasswordInput`

NewChangePasswordInputWithDefaults instantiates a new ChangePasswordInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrentPassword

`func (o *ChangePasswordInput) GetCurrentPassword() string`

GetCurrentPassword returns the CurrentPassword field if non-nil, zero value otherwise.

### GetCurrentPasswordOk

`func (o *ChangePasswordInput) GetCurrentPasswordOk() (*string, bool)`

GetCurrentPasswordOk returns a tuple with the CurrentPassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentPassword

`func (o *ChangePasswordInput) SetCurrentPassword(v string)`

SetCurrentPassword sets CurrentPassword field to given value.

### HasCurrentPassword

`func (o *ChangePasswordInput) HasCurrentPassword() bool`

HasCurrentPassword returns a boolean if a field has been set.

### SetCurrentPasswordNil

`func (o *ChangePasswordInput) SetCurrentPasswordNil(b bool)`

 SetCurrentPasswordNil sets the value for CurrentPassword to be an explicit nil

### UnsetCurrentPassword
`func (o *ChangePasswordInput) UnsetCurrentPassword()`

UnsetCurrentPassword ensures that no value is present for CurrentPassword, not even an explicit nil
### GetNewPassword

`func (o *ChangePasswordInput) GetNewPassword() string`

GetNewPassword returns the NewPassword field if non-nil, zero value otherwise.

### GetNewPasswordOk

`func (o *ChangePasswordInput) GetNewPasswordOk() (*string, bool)`

GetNewPasswordOk returns a tuple with the NewPassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewPassword

`func (o *ChangePasswordInput) SetNewPassword(v string)`

SetNewPassword sets NewPassword field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


