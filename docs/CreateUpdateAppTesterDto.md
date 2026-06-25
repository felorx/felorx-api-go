# CreateUpdateAppTesterDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppId** | Pointer to **string** | 应用ID | [optional]
**UserId** | Pointer to **string** | 用户ID | [optional]
**IsEnabled** | Pointer to **bool** | 是否启用 | [optional]

## Methods

### NewCreateUpdateAppTesterDto

`func NewCreateUpdateAppTesterDto() *CreateUpdateAppTesterDto`

NewCreateUpdateAppTesterDto instantiates a new CreateUpdateAppTesterDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateUpdateAppTesterDtoWithDefaults

`func NewCreateUpdateAppTesterDtoWithDefaults() *CreateUpdateAppTesterDto`

NewCreateUpdateAppTesterDtoWithDefaults instantiates a new CreateUpdateAppTesterDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppId

`func (o *CreateUpdateAppTesterDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *CreateUpdateAppTesterDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *CreateUpdateAppTesterDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *CreateUpdateAppTesterDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetUserId

`func (o *CreateUpdateAppTesterDto) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *CreateUpdateAppTesterDto) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *CreateUpdateAppTesterDto) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *CreateUpdateAppTesterDto) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### GetIsEnabled

`func (o *CreateUpdateAppTesterDto) GetIsEnabled() bool`

GetIsEnabled returns the IsEnabled field if non-nil, zero value otherwise.

### GetIsEnabledOk

`func (o *CreateUpdateAppTesterDto) GetIsEnabledOk() (*bool, bool)`

GetIsEnabledOk returns a tuple with the IsEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsEnabled

`func (o *CreateUpdateAppTesterDto) SetIsEnabled(v bool)`

SetIsEnabled sets IsEnabled field to given value.

### HasIsEnabled

`func (o *CreateUpdateAppTesterDto) HasIsEnabled() bool`

HasIsEnabled returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


