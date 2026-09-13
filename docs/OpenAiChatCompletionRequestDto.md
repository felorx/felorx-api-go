# OpenAiChatCompletionRequestDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Model** | Pointer to **NullableString** |  | [optional] 
**Provider** | Pointer to **NullableString** |  | [optional] 
**Messages** | Pointer to [**[]AiChatMessageDto**](AiChatMessageDto.md) |  | [optional] 
**Temperature** | Pointer to **NullableFloat64** |  | [optional] 
**TopP** | Pointer to **NullableFloat64** |  | [optional] 
**MaxTokens** | Pointer to **NullableInt32** |  | [optional] 
**Stream** | Pointer to **bool** |  | [optional] 
**Metadata** | Pointer to **map[string]string** |  | [optional] 

## Methods

### NewOpenAiChatCompletionRequestDto

`func NewOpenAiChatCompletionRequestDto() *OpenAiChatCompletionRequestDto`

NewOpenAiChatCompletionRequestDto instantiates a new OpenAiChatCompletionRequestDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOpenAiChatCompletionRequestDtoWithDefaults

`func NewOpenAiChatCompletionRequestDtoWithDefaults() *OpenAiChatCompletionRequestDto`

NewOpenAiChatCompletionRequestDtoWithDefaults instantiates a new OpenAiChatCompletionRequestDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetModel

`func (o *OpenAiChatCompletionRequestDto) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *OpenAiChatCompletionRequestDto) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *OpenAiChatCompletionRequestDto) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *OpenAiChatCompletionRequestDto) HasModel() bool`

HasModel returns a boolean if a field has been set.

### SetModelNil

`func (o *OpenAiChatCompletionRequestDto) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *OpenAiChatCompletionRequestDto) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetProvider

`func (o *OpenAiChatCompletionRequestDto) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *OpenAiChatCompletionRequestDto) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *OpenAiChatCompletionRequestDto) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *OpenAiChatCompletionRequestDto) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### SetProviderNil

`func (o *OpenAiChatCompletionRequestDto) SetProviderNil(b bool)`

 SetProviderNil sets the value for Provider to be an explicit nil

### UnsetProvider
`func (o *OpenAiChatCompletionRequestDto) UnsetProvider()`

UnsetProvider ensures that no value is present for Provider, not even an explicit nil
### GetMessages

`func (o *OpenAiChatCompletionRequestDto) GetMessages() []AiChatMessageDto`

GetMessages returns the Messages field if non-nil, zero value otherwise.

### GetMessagesOk

`func (o *OpenAiChatCompletionRequestDto) GetMessagesOk() (*[]AiChatMessageDto, bool)`

GetMessagesOk returns a tuple with the Messages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessages

`func (o *OpenAiChatCompletionRequestDto) SetMessages(v []AiChatMessageDto)`

SetMessages sets Messages field to given value.

### HasMessages

`func (o *OpenAiChatCompletionRequestDto) HasMessages() bool`

HasMessages returns a boolean if a field has been set.

### SetMessagesNil

`func (o *OpenAiChatCompletionRequestDto) SetMessagesNil(b bool)`

 SetMessagesNil sets the value for Messages to be an explicit nil

### UnsetMessages
`func (o *OpenAiChatCompletionRequestDto) UnsetMessages()`

UnsetMessages ensures that no value is present for Messages, not even an explicit nil
### GetTemperature

`func (o *OpenAiChatCompletionRequestDto) GetTemperature() float64`

GetTemperature returns the Temperature field if non-nil, zero value otherwise.

### GetTemperatureOk

`func (o *OpenAiChatCompletionRequestDto) GetTemperatureOk() (*float64, bool)`

GetTemperatureOk returns a tuple with the Temperature field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemperature

`func (o *OpenAiChatCompletionRequestDto) SetTemperature(v float64)`

SetTemperature sets Temperature field to given value.

### HasTemperature

`func (o *OpenAiChatCompletionRequestDto) HasTemperature() bool`

HasTemperature returns a boolean if a field has been set.

### SetTemperatureNil

`func (o *OpenAiChatCompletionRequestDto) SetTemperatureNil(b bool)`

 SetTemperatureNil sets the value for Temperature to be an explicit nil

### UnsetTemperature
`func (o *OpenAiChatCompletionRequestDto) UnsetTemperature()`

UnsetTemperature ensures that no value is present for Temperature, not even an explicit nil
### GetTopP

`func (o *OpenAiChatCompletionRequestDto) GetTopP() float64`

GetTopP returns the TopP field if non-nil, zero value otherwise.

### GetTopPOk

`func (o *OpenAiChatCompletionRequestDto) GetTopPOk() (*float64, bool)`

GetTopPOk returns a tuple with the TopP field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopP

`func (o *OpenAiChatCompletionRequestDto) SetTopP(v float64)`

SetTopP sets TopP field to given value.

### HasTopP

`func (o *OpenAiChatCompletionRequestDto) HasTopP() bool`

HasTopP returns a boolean if a field has been set.

### SetTopPNil

`func (o *OpenAiChatCompletionRequestDto) SetTopPNil(b bool)`

 SetTopPNil sets the value for TopP to be an explicit nil

### UnsetTopP
`func (o *OpenAiChatCompletionRequestDto) UnsetTopP()`

UnsetTopP ensures that no value is present for TopP, not even an explicit nil
### GetMaxTokens

`func (o *OpenAiChatCompletionRequestDto) GetMaxTokens() int32`

GetMaxTokens returns the MaxTokens field if non-nil, zero value otherwise.

### GetMaxTokensOk

`func (o *OpenAiChatCompletionRequestDto) GetMaxTokensOk() (*int32, bool)`

GetMaxTokensOk returns a tuple with the MaxTokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxTokens

`func (o *OpenAiChatCompletionRequestDto) SetMaxTokens(v int32)`

SetMaxTokens sets MaxTokens field to given value.

### HasMaxTokens

`func (o *OpenAiChatCompletionRequestDto) HasMaxTokens() bool`

HasMaxTokens returns a boolean if a field has been set.

### SetMaxTokensNil

`func (o *OpenAiChatCompletionRequestDto) SetMaxTokensNil(b bool)`

 SetMaxTokensNil sets the value for MaxTokens to be an explicit nil

### UnsetMaxTokens
`func (o *OpenAiChatCompletionRequestDto) UnsetMaxTokens()`

UnsetMaxTokens ensures that no value is present for MaxTokens, not even an explicit nil
### GetStream

`func (o *OpenAiChatCompletionRequestDto) GetStream() bool`

GetStream returns the Stream field if non-nil, zero value otherwise.

### GetStreamOk

`func (o *OpenAiChatCompletionRequestDto) GetStreamOk() (*bool, bool)`

GetStreamOk returns a tuple with the Stream field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStream

`func (o *OpenAiChatCompletionRequestDto) SetStream(v bool)`

SetStream sets Stream field to given value.

### HasStream

`func (o *OpenAiChatCompletionRequestDto) HasStream() bool`

HasStream returns a boolean if a field has been set.

### GetMetadata

`func (o *OpenAiChatCompletionRequestDto) GetMetadata() map[string]string`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *OpenAiChatCompletionRequestDto) GetMetadataOk() (*map[string]string, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *OpenAiChatCompletionRequestDto) SetMetadata(v map[string]string)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *OpenAiChatCompletionRequestDto) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *OpenAiChatCompletionRequestDto) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *OpenAiChatCompletionRequestDto) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


