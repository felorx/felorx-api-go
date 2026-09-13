# SendTestEmailInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SenderEmailAddress** | **string** |  | 
**TargetEmailAddress** | **string** |  | 
**Subject** | **string** |  | 
**Body** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewSendTestEmailInput

`func NewSendTestEmailInput(senderEmailAddress string, targetEmailAddress string, subject string, ) *SendTestEmailInput`

NewSendTestEmailInput instantiates a new SendTestEmailInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSendTestEmailInputWithDefaults

`func NewSendTestEmailInputWithDefaults() *SendTestEmailInput`

NewSendTestEmailInputWithDefaults instantiates a new SendTestEmailInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSenderEmailAddress

`func (o *SendTestEmailInput) GetSenderEmailAddress() string`

GetSenderEmailAddress returns the SenderEmailAddress field if non-nil, zero value otherwise.

### GetSenderEmailAddressOk

`func (o *SendTestEmailInput) GetSenderEmailAddressOk() (*string, bool)`

GetSenderEmailAddressOk returns a tuple with the SenderEmailAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSenderEmailAddress

`func (o *SendTestEmailInput) SetSenderEmailAddress(v string)`

SetSenderEmailAddress sets SenderEmailAddress field to given value.


### GetTargetEmailAddress

`func (o *SendTestEmailInput) GetTargetEmailAddress() string`

GetTargetEmailAddress returns the TargetEmailAddress field if non-nil, zero value otherwise.

### GetTargetEmailAddressOk

`func (o *SendTestEmailInput) GetTargetEmailAddressOk() (*string, bool)`

GetTargetEmailAddressOk returns a tuple with the TargetEmailAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetEmailAddress

`func (o *SendTestEmailInput) SetTargetEmailAddress(v string)`

SetTargetEmailAddress sets TargetEmailAddress field to given value.


### GetSubject

`func (o *SendTestEmailInput) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *SendTestEmailInput) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *SendTestEmailInput) SetSubject(v string)`

SetSubject sets Subject field to given value.


### GetBody

`func (o *SendTestEmailInput) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *SendTestEmailInput) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *SendTestEmailInput) SetBody(v string)`

SetBody sets Body field to given value.

### HasBody

`func (o *SendTestEmailInput) HasBody() bool`

HasBody returns a boolean if a field has been set.

### SetBodyNil

`func (o *SendTestEmailInput) SetBodyNil(b bool)`

 SetBodyNil sets the value for Body to be an explicit nil

### UnsetBody
`func (o *SendTestEmailInput) UnsetBody()`

UnsetBody ensures that no value is present for Body, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


