# RegisterDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExtraProperties** | Pointer to **map[string]interface{}** |  | [optional] [readonly] 
**UserName** | **string** |  | 
**EmailAddress** | **string** |  | 
**Password** | **string** |  | 
**AppName** | **string** |  | 

## Methods

### NewRegisterDto

`func NewRegisterDto(userName string, emailAddress string, password string, appName string, ) *RegisterDto`

NewRegisterDto instantiates a new RegisterDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRegisterDtoWithDefaults

`func NewRegisterDtoWithDefaults() *RegisterDto`

NewRegisterDtoWithDefaults instantiates a new RegisterDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExtraProperties

`func (o *RegisterDto) GetExtraProperties() map[string]interface{}`

GetExtraProperties returns the ExtraProperties field if non-nil, zero value otherwise.

### GetExtraPropertiesOk

`func (o *RegisterDto) GetExtraPropertiesOk() (*map[string]interface{}, bool)`

GetExtraPropertiesOk returns a tuple with the ExtraProperties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtraProperties

`func (o *RegisterDto) SetExtraProperties(v map[string]interface{})`

SetExtraProperties sets ExtraProperties field to given value.

### HasExtraProperties

`func (o *RegisterDto) HasExtraProperties() bool`

HasExtraProperties returns a boolean if a field has been set.

### SetExtraPropertiesNil

`func (o *RegisterDto) SetExtraPropertiesNil(b bool)`

 SetExtraPropertiesNil sets the value for ExtraProperties to be an explicit nil

### UnsetExtraProperties
`func (o *RegisterDto) UnsetExtraProperties()`

UnsetExtraProperties ensures that no value is present for ExtraProperties, not even an explicit nil
### GetUserName

`func (o *RegisterDto) GetUserName() string`

GetUserName returns the UserName field if non-nil, zero value otherwise.

### GetUserNameOk

`func (o *RegisterDto) GetUserNameOk() (*string, bool)`

GetUserNameOk returns a tuple with the UserName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserName

`func (o *RegisterDto) SetUserName(v string)`

SetUserName sets UserName field to given value.


### GetEmailAddress

`func (o *RegisterDto) GetEmailAddress() string`

GetEmailAddress returns the EmailAddress field if non-nil, zero value otherwise.

### GetEmailAddressOk

`func (o *RegisterDto) GetEmailAddressOk() (*string, bool)`

GetEmailAddressOk returns a tuple with the EmailAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailAddress

`func (o *RegisterDto) SetEmailAddress(v string)`

SetEmailAddress sets EmailAddress field to given value.


### GetPassword

`func (o *RegisterDto) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *RegisterDto) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *RegisterDto) SetPassword(v string)`

SetPassword sets Password field to given value.


### GetAppName

`func (o *RegisterDto) GetAppName() string`

GetAppName returns the AppName field if non-nil, zero value otherwise.

### GetAppNameOk

`func (o *RegisterDto) GetAppNameOk() (*string, bool)`

GetAppNameOk returns a tuple with the AppName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppName

`func (o *RegisterDto) SetAppName(v string)`

SetAppName sets AppName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


