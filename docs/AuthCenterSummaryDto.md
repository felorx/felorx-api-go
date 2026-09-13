# AuthCenterSummaryDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Account** | Pointer to [**UserAuthProfileDto**](UserAuthProfileDto.md) |  | [optional] 
**DeviceCount** | Pointer to **int32** |  | [optional] 
**AuthorizedAppCount** | Pointer to **int32** |  | [optional] 

## Methods

### NewAuthCenterSummaryDto

`func NewAuthCenterSummaryDto() *AuthCenterSummaryDto`

NewAuthCenterSummaryDto instantiates a new AuthCenterSummaryDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAuthCenterSummaryDtoWithDefaults

`func NewAuthCenterSummaryDtoWithDefaults() *AuthCenterSummaryDto`

NewAuthCenterSummaryDtoWithDefaults instantiates a new AuthCenterSummaryDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccount

`func (o *AuthCenterSummaryDto) GetAccount() UserAuthProfileDto`

GetAccount returns the Account field if non-nil, zero value otherwise.

### GetAccountOk

`func (o *AuthCenterSummaryDto) GetAccountOk() (*UserAuthProfileDto, bool)`

GetAccountOk returns a tuple with the Account field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccount

`func (o *AuthCenterSummaryDto) SetAccount(v UserAuthProfileDto)`

SetAccount sets Account field to given value.

### HasAccount

`func (o *AuthCenterSummaryDto) HasAccount() bool`

HasAccount returns a boolean if a field has been set.

### GetDeviceCount

`func (o *AuthCenterSummaryDto) GetDeviceCount() int32`

GetDeviceCount returns the DeviceCount field if non-nil, zero value otherwise.

### GetDeviceCountOk

`func (o *AuthCenterSummaryDto) GetDeviceCountOk() (*int32, bool)`

GetDeviceCountOk returns a tuple with the DeviceCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceCount

`func (o *AuthCenterSummaryDto) SetDeviceCount(v int32)`

SetDeviceCount sets DeviceCount field to given value.

### HasDeviceCount

`func (o *AuthCenterSummaryDto) HasDeviceCount() bool`

HasDeviceCount returns a boolean if a field has been set.

### GetAuthorizedAppCount

`func (o *AuthCenterSummaryDto) GetAuthorizedAppCount() int32`

GetAuthorizedAppCount returns the AuthorizedAppCount field if non-nil, zero value otherwise.

### GetAuthorizedAppCountOk

`func (o *AuthCenterSummaryDto) GetAuthorizedAppCountOk() (*int32, bool)`

GetAuthorizedAppCountOk returns a tuple with the AuthorizedAppCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorizedAppCount

`func (o *AuthCenterSummaryDto) SetAuthorizedAppCount(v int32)`

SetAuthorizedAppCount sets AuthorizedAppCount field to given value.

### HasAuthorizedAppCount

`func (o *AuthCenterSummaryDto) HasAuthorizedAppCount() bool`

HasAuthorizedAppCount returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


