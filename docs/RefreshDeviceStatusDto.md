# RefreshDeviceStatusDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Token** | Pointer to **NullableString** |  | [optional]
**Status** | Pointer to [**DeviceStatus**](DeviceStatus.md) |  | [optional]

## Methods

### NewRefreshDeviceStatusDto

`func NewRefreshDeviceStatusDto() *RefreshDeviceStatusDto`

NewRefreshDeviceStatusDto instantiates a new RefreshDeviceStatusDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRefreshDeviceStatusDtoWithDefaults

`func NewRefreshDeviceStatusDtoWithDefaults() *RefreshDeviceStatusDto`

NewRefreshDeviceStatusDtoWithDefaults instantiates a new RefreshDeviceStatusDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetToken

`func (o *RefreshDeviceStatusDto) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *RefreshDeviceStatusDto) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *RefreshDeviceStatusDto) SetToken(v string)`

SetToken sets Token field to given value.

### HasToken

`func (o *RefreshDeviceStatusDto) HasToken() bool`

HasToken returns a boolean if a field has been set.

### SetTokenNil

`func (o *RefreshDeviceStatusDto) SetTokenNil(b bool)`

 SetTokenNil sets the value for Token to be an explicit nil

### UnsetToken
`func (o *RefreshDeviceStatusDto) UnsetToken()`

UnsetToken ensures that no value is present for Token, not even an explicit nil
### GetStatus

`func (o *RefreshDeviceStatusDto) GetStatus() DeviceStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RefreshDeviceStatusDto) GetStatusOk() (*DeviceStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RefreshDeviceStatusDto) SetStatus(v DeviceStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *RefreshDeviceStatusDto) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


