# AccountDeletionStatusDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RequestId** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **int32** |  | [optional] 
**AcceptedAt** | Pointer to **time.Time** |  | [optional] 
**RetainUntil** | Pointer to **time.Time** |  | [optional] 
**StartedAt** | Pointer to **NullableTime** |  | [optional] 
**CompletedAt** | Pointer to **NullableTime** |  | [optional] 
**LastAttemptAt** | Pointer to **NullableTime** |  | [optional] 
**AttemptCount** | Pointer to **int32** |  | [optional] 
**FailureCode** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewAccountDeletionStatusDto

`func NewAccountDeletionStatusDto() *AccountDeletionStatusDto`

NewAccountDeletionStatusDto instantiates a new AccountDeletionStatusDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountDeletionStatusDtoWithDefaults

`func NewAccountDeletionStatusDtoWithDefaults() *AccountDeletionStatusDto`

NewAccountDeletionStatusDtoWithDefaults instantiates a new AccountDeletionStatusDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRequestId

`func (o *AccountDeletionStatusDto) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *AccountDeletionStatusDto) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *AccountDeletionStatusDto) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *AccountDeletionStatusDto) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.

### GetStatus

`func (o *AccountDeletionStatusDto) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AccountDeletionStatusDto) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AccountDeletionStatusDto) SetStatus(v int32)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *AccountDeletionStatusDto) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetAcceptedAt

`func (o *AccountDeletionStatusDto) GetAcceptedAt() time.Time`

GetAcceptedAt returns the AcceptedAt field if non-nil, zero value otherwise.

### GetAcceptedAtOk

`func (o *AccountDeletionStatusDto) GetAcceptedAtOk() (*time.Time, bool)`

GetAcceptedAtOk returns a tuple with the AcceptedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcceptedAt

`func (o *AccountDeletionStatusDto) SetAcceptedAt(v time.Time)`

SetAcceptedAt sets AcceptedAt field to given value.

### HasAcceptedAt

`func (o *AccountDeletionStatusDto) HasAcceptedAt() bool`

HasAcceptedAt returns a boolean if a field has been set.

### GetRetainUntil

`func (o *AccountDeletionStatusDto) GetRetainUntil() time.Time`

GetRetainUntil returns the RetainUntil field if non-nil, zero value otherwise.

### GetRetainUntilOk

`func (o *AccountDeletionStatusDto) GetRetainUntilOk() (*time.Time, bool)`

GetRetainUntilOk returns a tuple with the RetainUntil field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetainUntil

`func (o *AccountDeletionStatusDto) SetRetainUntil(v time.Time)`

SetRetainUntil sets RetainUntil field to given value.

### HasRetainUntil

`func (o *AccountDeletionStatusDto) HasRetainUntil() bool`

HasRetainUntil returns a boolean if a field has been set.

### GetStartedAt

`func (o *AccountDeletionStatusDto) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *AccountDeletionStatusDto) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *AccountDeletionStatusDto) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.

### HasStartedAt

`func (o *AccountDeletionStatusDto) HasStartedAt() bool`

HasStartedAt returns a boolean if a field has been set.

### SetStartedAtNil

`func (o *AccountDeletionStatusDto) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *AccountDeletionStatusDto) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetCompletedAt

`func (o *AccountDeletionStatusDto) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *AccountDeletionStatusDto) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *AccountDeletionStatusDto) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *AccountDeletionStatusDto) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *AccountDeletionStatusDto) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *AccountDeletionStatusDto) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetLastAttemptAt

`func (o *AccountDeletionStatusDto) GetLastAttemptAt() time.Time`

GetLastAttemptAt returns the LastAttemptAt field if non-nil, zero value otherwise.

### GetLastAttemptAtOk

`func (o *AccountDeletionStatusDto) GetLastAttemptAtOk() (*time.Time, bool)`

GetLastAttemptAtOk returns a tuple with the LastAttemptAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastAttemptAt

`func (o *AccountDeletionStatusDto) SetLastAttemptAt(v time.Time)`

SetLastAttemptAt sets LastAttemptAt field to given value.

### HasLastAttemptAt

`func (o *AccountDeletionStatusDto) HasLastAttemptAt() bool`

HasLastAttemptAt returns a boolean if a field has been set.

### SetLastAttemptAtNil

`func (o *AccountDeletionStatusDto) SetLastAttemptAtNil(b bool)`

 SetLastAttemptAtNil sets the value for LastAttemptAt to be an explicit nil

### UnsetLastAttemptAt
`func (o *AccountDeletionStatusDto) UnsetLastAttemptAt()`

UnsetLastAttemptAt ensures that no value is present for LastAttemptAt, not even an explicit nil
### GetAttemptCount

`func (o *AccountDeletionStatusDto) GetAttemptCount() int32`

GetAttemptCount returns the AttemptCount field if non-nil, zero value otherwise.

### GetAttemptCountOk

`func (o *AccountDeletionStatusDto) GetAttemptCountOk() (*int32, bool)`

GetAttemptCountOk returns a tuple with the AttemptCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttemptCount

`func (o *AccountDeletionStatusDto) SetAttemptCount(v int32)`

SetAttemptCount sets AttemptCount field to given value.

### HasAttemptCount

`func (o *AccountDeletionStatusDto) HasAttemptCount() bool`

HasAttemptCount returns a boolean if a field has been set.

### GetFailureCode

`func (o *AccountDeletionStatusDto) GetFailureCode() string`

GetFailureCode returns the FailureCode field if non-nil, zero value otherwise.

### GetFailureCodeOk

`func (o *AccountDeletionStatusDto) GetFailureCodeOk() (*string, bool)`

GetFailureCodeOk returns a tuple with the FailureCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureCode

`func (o *AccountDeletionStatusDto) SetFailureCode(v string)`

SetFailureCode sets FailureCode field to given value.

### HasFailureCode

`func (o *AccountDeletionStatusDto) HasFailureCode() bool`

HasFailureCode returns a boolean if a field has been set.

### SetFailureCodeNil

`func (o *AccountDeletionStatusDto) SetFailureCodeNil(b bool)`

 SetFailureCodeNil sets the value for FailureCode to be an explicit nil

### UnsetFailureCode
`func (o *AccountDeletionStatusDto) UnsetFailureCode()`

UnsetFailureCode ensures that no value is present for FailureCode, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


