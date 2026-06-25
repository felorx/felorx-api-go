# ApiKeyDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional]
**Name** | Pointer to **NullableString** |  | [optional]
**Key** | Pointer to **NullableString** |  | [optional]
**Active** | Pointer to **bool** |  | [optional]
**ExpireAt** | Pointer to **NullableTime** |  | [optional]

## Methods

### NewApiKeyDto

`func NewApiKeyDto() *ApiKeyDto`

NewApiKeyDto instantiates a new ApiKeyDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApiKeyDtoWithDefaults

`func NewApiKeyDtoWithDefaults() *ApiKeyDto`

NewApiKeyDtoWithDefaults instantiates a new ApiKeyDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ApiKeyDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ApiKeyDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ApiKeyDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ApiKeyDto) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *ApiKeyDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ApiKeyDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ApiKeyDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ApiKeyDto) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *ApiKeyDto) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *ApiKeyDto) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetKey

`func (o *ApiKeyDto) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *ApiKeyDto) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *ApiKeyDto) SetKey(v string)`

SetKey sets Key field to given value.

### HasKey

`func (o *ApiKeyDto) HasKey() bool`

HasKey returns a boolean if a field has been set.

### SetKeyNil

`func (o *ApiKeyDto) SetKeyNil(b bool)`

 SetKeyNil sets the value for Key to be an explicit nil

### UnsetKey
`func (o *ApiKeyDto) UnsetKey()`

UnsetKey ensures that no value is present for Key, not even an explicit nil
### GetActive

`func (o *ApiKeyDto) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *ApiKeyDto) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *ApiKeyDto) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *ApiKeyDto) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetExpireAt

`func (o *ApiKeyDto) GetExpireAt() time.Time`

GetExpireAt returns the ExpireAt field if non-nil, zero value otherwise.

### GetExpireAtOk

`func (o *ApiKeyDto) GetExpireAtOk() (*time.Time, bool)`

GetExpireAtOk returns a tuple with the ExpireAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpireAt

`func (o *ApiKeyDto) SetExpireAt(v time.Time)`

SetExpireAt sets ExpireAt field to given value.

### HasExpireAt

`func (o *ApiKeyDto) HasExpireAt() bool`

HasExpireAt returns a boolean if a field has been set.

### SetExpireAtNil

`func (o *ApiKeyDto) SetExpireAtNil(b bool)`

 SetExpireAtNil sets the value for ExpireAt to be an explicit nil

### UnsetExpireAt
`func (o *ApiKeyDto) UnsetExpireAt()`

UnsetExpireAt ensures that no value is present for ExpireAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


