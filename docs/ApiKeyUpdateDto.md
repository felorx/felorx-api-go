# ApiKeyUpdateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Active** | Pointer to **bool** |  | [optional] 
**ExpireAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewApiKeyUpdateDto

`func NewApiKeyUpdateDto(name string, ) *ApiKeyUpdateDto`

NewApiKeyUpdateDto instantiates a new ApiKeyUpdateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApiKeyUpdateDtoWithDefaults

`func NewApiKeyUpdateDtoWithDefaults() *ApiKeyUpdateDto`

NewApiKeyUpdateDtoWithDefaults instantiates a new ApiKeyUpdateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ApiKeyUpdateDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ApiKeyUpdateDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ApiKeyUpdateDto) SetName(v string)`

SetName sets Name field to given value.


### GetActive

`func (o *ApiKeyUpdateDto) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *ApiKeyUpdateDto) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *ApiKeyUpdateDto) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *ApiKeyUpdateDto) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetExpireAt

`func (o *ApiKeyUpdateDto) GetExpireAt() time.Time`

GetExpireAt returns the ExpireAt field if non-nil, zero value otherwise.

### GetExpireAtOk

`func (o *ApiKeyUpdateDto) GetExpireAtOk() (*time.Time, bool)`

GetExpireAtOk returns a tuple with the ExpireAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpireAt

`func (o *ApiKeyUpdateDto) SetExpireAt(v time.Time)`

SetExpireAt sets ExpireAt field to given value.

### HasExpireAt

`func (o *ApiKeyUpdateDto) HasExpireAt() bool`

HasExpireAt returns a boolean if a field has been set.

### SetExpireAtNil

`func (o *ApiKeyUpdateDto) SetExpireAtNil(b bool)`

 SetExpireAtNil sets the value for ExpireAt to be an explicit nil

### UnsetExpireAt
`func (o *ApiKeyUpdateDto) UnsetExpireAt()`

UnsetExpireAt ensures that no value is present for ExpireAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


