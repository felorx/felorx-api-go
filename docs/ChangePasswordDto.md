# ChangePasswordDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | Pointer to **NullableString** |  | [optional]
**Password** | Pointer to **NullableString** |  | [optional]

## Methods

### NewChangePasswordDto

`func NewChangePasswordDto() *ChangePasswordDto`

NewChangePasswordDto instantiates a new ChangePasswordDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChangePasswordDtoWithDefaults

`func NewChangePasswordDtoWithDefaults() *ChangePasswordDto`

NewChangePasswordDtoWithDefaults instantiates a new ChangePasswordDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *ChangePasswordDto) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *ChangePasswordDto) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *ChangePasswordDto) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *ChangePasswordDto) HasCode() bool`

HasCode returns a boolean if a field has been set.

### SetCodeNil

`func (o *ChangePasswordDto) SetCodeNil(b bool)`

 SetCodeNil sets the value for Code to be an explicit nil

### UnsetCode
`func (o *ChangePasswordDto) UnsetCode()`

UnsetCode ensures that no value is present for Code, not even an explicit nil
### GetPassword

`func (o *ChangePasswordDto) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *ChangePasswordDto) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *ChangePasswordDto) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *ChangePasswordDto) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### SetPasswordNil

`func (o *ChangePasswordDto) SetPasswordNil(b bool)`

 SetPasswordNil sets the value for Password to be an explicit nil

### UnsetPassword
`func (o *ChangePasswordDto) UnsetPassword()`

UnsetPassword ensures that no value is present for Password, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


