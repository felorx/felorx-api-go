# TestAiProviderDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Capability** | Pointer to [**AiCapability**](AiCapability.md) |  | [optional]
**Prompt** | Pointer to **NullableString** |  | [optional]
**ImageUrl** | Pointer to **NullableString** |  | [optional]

## Methods

### NewTestAiProviderDto

`func NewTestAiProviderDto() *TestAiProviderDto`

NewTestAiProviderDto instantiates a new TestAiProviderDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTestAiProviderDtoWithDefaults

`func NewTestAiProviderDtoWithDefaults() *TestAiProviderDto`

NewTestAiProviderDtoWithDefaults instantiates a new TestAiProviderDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCapability

`func (o *TestAiProviderDto) GetCapability() AiCapability`

GetCapability returns the Capability field if non-nil, zero value otherwise.

### GetCapabilityOk

`func (o *TestAiProviderDto) GetCapabilityOk() (*AiCapability, bool)`

GetCapabilityOk returns a tuple with the Capability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapability

`func (o *TestAiProviderDto) SetCapability(v AiCapability)`

SetCapability sets Capability field to given value.

### HasCapability

`func (o *TestAiProviderDto) HasCapability() bool`

HasCapability returns a boolean if a field has been set.

### GetPrompt

`func (o *TestAiProviderDto) GetPrompt() string`

GetPrompt returns the Prompt field if non-nil, zero value otherwise.

### GetPromptOk

`func (o *TestAiProviderDto) GetPromptOk() (*string, bool)`

GetPromptOk returns a tuple with the Prompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrompt

`func (o *TestAiProviderDto) SetPrompt(v string)`

SetPrompt sets Prompt field to given value.

### HasPrompt

`func (o *TestAiProviderDto) HasPrompt() bool`

HasPrompt returns a boolean if a field has been set.

### SetPromptNil

`func (o *TestAiProviderDto) SetPromptNil(b bool)`

 SetPromptNil sets the value for Prompt to be an explicit nil

### UnsetPrompt
`func (o *TestAiProviderDto) UnsetPrompt()`

UnsetPrompt ensures that no value is present for Prompt, not even an explicit nil
### GetImageUrl

`func (o *TestAiProviderDto) GetImageUrl() string`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *TestAiProviderDto) GetImageUrlOk() (*string, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *TestAiProviderDto) SetImageUrl(v string)`

SetImageUrl sets ImageUrl field to given value.

### HasImageUrl

`func (o *TestAiProviderDto) HasImageUrl() bool`

HasImageUrl returns a boolean if a field has been set.

### SetImageUrlNil

`func (o *TestAiProviderDto) SetImageUrlNil(b bool)`

 SetImageUrlNil sets the value for ImageUrl to be an explicit nil

### UnsetImageUrl
`func (o *TestAiProviderDto) UnsetImageUrl()`

UnsetImageUrl ensures that no value is present for ImageUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


