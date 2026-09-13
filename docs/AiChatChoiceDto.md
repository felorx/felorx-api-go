# AiChatChoiceDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Index** | Pointer to **int32** |  | [optional] 
**Message** | Pointer to [**AiChatMessageDto**](AiChatMessageDto.md) |  | [optional] 
**FinishReason** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewAiChatChoiceDto

`func NewAiChatChoiceDto() *AiChatChoiceDto`

NewAiChatChoiceDto instantiates a new AiChatChoiceDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiChatChoiceDtoWithDefaults

`func NewAiChatChoiceDtoWithDefaults() *AiChatChoiceDto`

NewAiChatChoiceDtoWithDefaults instantiates a new AiChatChoiceDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIndex

`func (o *AiChatChoiceDto) GetIndex() int32`

GetIndex returns the Index field if non-nil, zero value otherwise.

### GetIndexOk

`func (o *AiChatChoiceDto) GetIndexOk() (*int32, bool)`

GetIndexOk returns a tuple with the Index field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndex

`func (o *AiChatChoiceDto) SetIndex(v int32)`

SetIndex sets Index field to given value.

### HasIndex

`func (o *AiChatChoiceDto) HasIndex() bool`

HasIndex returns a boolean if a field has been set.

### GetMessage

`func (o *AiChatChoiceDto) GetMessage() AiChatMessageDto`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *AiChatChoiceDto) GetMessageOk() (*AiChatMessageDto, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *AiChatChoiceDto) SetMessage(v AiChatMessageDto)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *AiChatChoiceDto) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetFinishReason

`func (o *AiChatChoiceDto) GetFinishReason() string`

GetFinishReason returns the FinishReason field if non-nil, zero value otherwise.

### GetFinishReasonOk

`func (o *AiChatChoiceDto) GetFinishReasonOk() (*string, bool)`

GetFinishReasonOk returns a tuple with the FinishReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishReason

`func (o *AiChatChoiceDto) SetFinishReason(v string)`

SetFinishReason sets FinishReason field to given value.

### HasFinishReason

`func (o *AiChatChoiceDto) HasFinishReason() bool`

HasFinishReason returns a boolean if a field has been set.

### SetFinishReasonNil

`func (o *AiChatChoiceDto) SetFinishReasonNil(b bool)`

 SetFinishReasonNil sets the value for FinishReason to be an explicit nil

### UnsetFinishReason
`func (o *AiChatChoiceDto) UnsetFinishReason()`

UnsetFinishReason ensures that no value is present for FinishReason, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


