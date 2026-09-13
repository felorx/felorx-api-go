# RemotePairingAssertionDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Assertion** | Pointer to **NullableString** |  | [optional] 
**ExpiresAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewRemotePairingAssertionDto

`func NewRemotePairingAssertionDto() *RemotePairingAssertionDto`

NewRemotePairingAssertionDto instantiates a new RemotePairingAssertionDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRemotePairingAssertionDtoWithDefaults

`func NewRemotePairingAssertionDtoWithDefaults() *RemotePairingAssertionDto`

NewRemotePairingAssertionDtoWithDefaults instantiates a new RemotePairingAssertionDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssertion

`func (o *RemotePairingAssertionDto) GetAssertion() string`

GetAssertion returns the Assertion field if non-nil, zero value otherwise.

### GetAssertionOk

`func (o *RemotePairingAssertionDto) GetAssertionOk() (*string, bool)`

GetAssertionOk returns a tuple with the Assertion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssertion

`func (o *RemotePairingAssertionDto) SetAssertion(v string)`

SetAssertion sets Assertion field to given value.

### HasAssertion

`func (o *RemotePairingAssertionDto) HasAssertion() bool`

HasAssertion returns a boolean if a field has been set.

### SetAssertionNil

`func (o *RemotePairingAssertionDto) SetAssertionNil(b bool)`

 SetAssertionNil sets the value for Assertion to be an explicit nil

### UnsetAssertion
`func (o *RemotePairingAssertionDto) UnsetAssertion()`

UnsetAssertion ensures that no value is present for Assertion, not even an explicit nil
### GetExpiresAt

`func (o *RemotePairingAssertionDto) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *RemotePairingAssertionDto) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *RemotePairingAssertionDto) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *RemotePairingAssertionDto) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


