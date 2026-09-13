# VerifyPasswordResetTokenInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UserId** | Pointer to **string** |  | [optional] 
**ResetToken** | **string** |  | 

## Methods

### NewVerifyPasswordResetTokenInput

`func NewVerifyPasswordResetTokenInput(resetToken string, ) *VerifyPasswordResetTokenInput`

NewVerifyPasswordResetTokenInput instantiates a new VerifyPasswordResetTokenInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVerifyPasswordResetTokenInputWithDefaults

`func NewVerifyPasswordResetTokenInputWithDefaults() *VerifyPasswordResetTokenInput`

NewVerifyPasswordResetTokenInputWithDefaults instantiates a new VerifyPasswordResetTokenInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUserId

`func (o *VerifyPasswordResetTokenInput) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *VerifyPasswordResetTokenInput) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *VerifyPasswordResetTokenInput) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *VerifyPasswordResetTokenInput) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetResetToken

`func (o *VerifyPasswordResetTokenInput) GetResetToken() string`

GetResetToken returns the ResetToken field if non-nil, zero value otherwise.

### GetResetTokenOk

`func (o *VerifyPasswordResetTokenInput) GetResetTokenOk() (*string, bool)`

GetResetTokenOk returns a tuple with the ResetToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResetToken

`func (o *VerifyPasswordResetTokenInput) SetResetToken(v string)`

SetResetToken sets ResetToken field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


