# AccountDeletionStatusQueryDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RequestId** | Pointer to **string** |  | [optional] 
**StatusToken** | **string** |  | 

## Methods

### NewAccountDeletionStatusQueryDto

`func NewAccountDeletionStatusQueryDto(statusToken string, ) *AccountDeletionStatusQueryDto`

NewAccountDeletionStatusQueryDto instantiates a new AccountDeletionStatusQueryDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountDeletionStatusQueryDtoWithDefaults

`func NewAccountDeletionStatusQueryDtoWithDefaults() *AccountDeletionStatusQueryDto`

NewAccountDeletionStatusQueryDtoWithDefaults instantiates a new AccountDeletionStatusQueryDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRequestId

`func (o *AccountDeletionStatusQueryDto) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *AccountDeletionStatusQueryDto) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *AccountDeletionStatusQueryDto) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *AccountDeletionStatusQueryDto) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.

### GetStatusToken

`func (o *AccountDeletionStatusQueryDto) GetStatusToken() string`

GetStatusToken returns the StatusToken field if non-nil, zero value otherwise.

### GetStatusTokenOk

`func (o *AccountDeletionStatusQueryDto) GetStatusTokenOk() (*string, bool)`

GetStatusTokenOk returns a tuple with the StatusToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusToken

`func (o *AccountDeletionStatusQueryDto) SetStatusToken(v string)`

SetStatusToken sets StatusToken field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


