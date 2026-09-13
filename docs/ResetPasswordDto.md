# ResetPasswordDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UserId** | Pointer to **string** |  | [optional] 
**ResetToken** | **string** |  | 
**Password** | **string** |  | 

## Methods

### NewResetPasswordDto

`func NewResetPasswordDto(resetToken string, password string, ) *ResetPasswordDto`

NewResetPasswordDto instantiates a new ResetPasswordDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResetPasswordDtoWithDefaults

`func NewResetPasswordDtoWithDefaults() *ResetPasswordDto`

NewResetPasswordDtoWithDefaults instantiates a new ResetPasswordDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUserId

`func (o *ResetPasswordDto) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *ResetPasswordDto) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *ResetPasswordDto) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *ResetPasswordDto) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetResetToken

`func (o *ResetPasswordDto) GetResetToken() string`

GetResetToken returns the ResetToken field if non-nil, zero value otherwise.

### GetResetTokenOk

`func (o *ResetPasswordDto) GetResetTokenOk() (*string, bool)`

GetResetTokenOk returns a tuple with the ResetToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResetToken

`func (o *ResetPasswordDto) SetResetToken(v string)`

SetResetToken sets ResetToken field to given value.


### GetPassword

`func (o *ResetPasswordDto) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *ResetPasswordDto) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *ResetPasswordDto) SetPassword(v string)`

SetPassword sets Password field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


