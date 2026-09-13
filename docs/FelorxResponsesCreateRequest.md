# FelorxResponsesCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Model** | Pointer to **string** |  | [optional] 
**Input** | Pointer to [**FelorxResponseInput**](FelorxResponseInput.md) |  | [optional] 
**Instructions** | Pointer to **string** |  | [optional] 
**PreviousResponseId** | Pointer to **string** |  | [optional] 
**Tools** | Pointer to [**[]FelorxResponsesCountRequestToolsInner**](FelorxResponsesCountRequestToolsInner.md) |  | [optional] 
**ToolChoice** | Pointer to [**FelorxResponseToolChoice**](FelorxResponseToolChoice.md) |  | [optional] 
**ParallelToolCalls** | Pointer to **bool** |  | [optional] 
**Reasoning** | Pointer to **map[string]interface{}** |  | [optional] 
**Text** | Pointer to **map[string]interface{}** |  | [optional] 
**Truncation** | Pointer to **string** |  | [optional] 
**Stream** | Pointer to **bool** |  | [optional] 
**Store** | Pointer to **bool** |  | [optional] 
**Background** | Pointer to **bool** |  | [optional] 
**MaxOutputTokens** | Pointer to **int32** |  | [optional] 
**Temperature** | Pointer to **float32** |  | [optional] 
**TopP** | Pointer to **float32** |  | [optional] 
**Metadata** | Pointer to **map[string]interface{}** |  | [optional] 
**ServiceTier** | Pointer to **string** |  | [optional] 
**PromptCacheKey** | Pointer to **string** |  | [optional] 
**PromptCacheRetention** | Pointer to **string** |  | [optional] 

## Methods

### NewFelorxResponsesCreateRequest

`func NewFelorxResponsesCreateRequest() *FelorxResponsesCreateRequest`

NewFelorxResponsesCreateRequest instantiates a new FelorxResponsesCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFelorxResponsesCreateRequestWithDefaults

`func NewFelorxResponsesCreateRequestWithDefaults() *FelorxResponsesCreateRequest`

NewFelorxResponsesCreateRequestWithDefaults instantiates a new FelorxResponsesCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetModel

`func (o *FelorxResponsesCreateRequest) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *FelorxResponsesCreateRequest) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *FelorxResponsesCreateRequest) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *FelorxResponsesCreateRequest) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetInput

`func (o *FelorxResponsesCreateRequest) GetInput() FelorxResponseInput`

GetInput returns the Input field if non-nil, zero value otherwise.

### GetInputOk

`func (o *FelorxResponsesCreateRequest) GetInputOk() (*FelorxResponseInput, bool)`

GetInputOk returns a tuple with the Input field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInput

`func (o *FelorxResponsesCreateRequest) SetInput(v FelorxResponseInput)`

SetInput sets Input field to given value.

### HasInput

`func (o *FelorxResponsesCreateRequest) HasInput() bool`

HasInput returns a boolean if a field has been set.

### GetInstructions

`func (o *FelorxResponsesCreateRequest) GetInstructions() string`

GetInstructions returns the Instructions field if non-nil, zero value otherwise.

### GetInstructionsOk

`func (o *FelorxResponsesCreateRequest) GetInstructionsOk() (*string, bool)`

GetInstructionsOk returns a tuple with the Instructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstructions

`func (o *FelorxResponsesCreateRequest) SetInstructions(v string)`

SetInstructions sets Instructions field to given value.

### HasInstructions

`func (o *FelorxResponsesCreateRequest) HasInstructions() bool`

HasInstructions returns a boolean if a field has been set.

### GetPreviousResponseId

`func (o *FelorxResponsesCreateRequest) GetPreviousResponseId() string`

GetPreviousResponseId returns the PreviousResponseId field if non-nil, zero value otherwise.

### GetPreviousResponseIdOk

`func (o *FelorxResponsesCreateRequest) GetPreviousResponseIdOk() (*string, bool)`

GetPreviousResponseIdOk returns a tuple with the PreviousResponseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviousResponseId

`func (o *FelorxResponsesCreateRequest) SetPreviousResponseId(v string)`

SetPreviousResponseId sets PreviousResponseId field to given value.

### HasPreviousResponseId

`func (o *FelorxResponsesCreateRequest) HasPreviousResponseId() bool`

HasPreviousResponseId returns a boolean if a field has been set.

### GetTools

`func (o *FelorxResponsesCreateRequest) GetTools() []FelorxResponsesCountRequestToolsInner`

GetTools returns the Tools field if non-nil, zero value otherwise.

### GetToolsOk

`func (o *FelorxResponsesCreateRequest) GetToolsOk() (*[]FelorxResponsesCountRequestToolsInner, bool)`

GetToolsOk returns a tuple with the Tools field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTools

`func (o *FelorxResponsesCreateRequest) SetTools(v []FelorxResponsesCountRequestToolsInner)`

SetTools sets Tools field to given value.

### HasTools

`func (o *FelorxResponsesCreateRequest) HasTools() bool`

HasTools returns a boolean if a field has been set.

### GetToolChoice

`func (o *FelorxResponsesCreateRequest) GetToolChoice() FelorxResponseToolChoice`

GetToolChoice returns the ToolChoice field if non-nil, zero value otherwise.

### GetToolChoiceOk

`func (o *FelorxResponsesCreateRequest) GetToolChoiceOk() (*FelorxResponseToolChoice, bool)`

GetToolChoiceOk returns a tuple with the ToolChoice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolChoice

`func (o *FelorxResponsesCreateRequest) SetToolChoice(v FelorxResponseToolChoice)`

SetToolChoice sets ToolChoice field to given value.

### HasToolChoice

`func (o *FelorxResponsesCreateRequest) HasToolChoice() bool`

HasToolChoice returns a boolean if a field has been set.

### GetParallelToolCalls

`func (o *FelorxResponsesCreateRequest) GetParallelToolCalls() bool`

GetParallelToolCalls returns the ParallelToolCalls field if non-nil, zero value otherwise.

### GetParallelToolCallsOk

`func (o *FelorxResponsesCreateRequest) GetParallelToolCallsOk() (*bool, bool)`

GetParallelToolCallsOk returns a tuple with the ParallelToolCalls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParallelToolCalls

`func (o *FelorxResponsesCreateRequest) SetParallelToolCalls(v bool)`

SetParallelToolCalls sets ParallelToolCalls field to given value.

### HasParallelToolCalls

`func (o *FelorxResponsesCreateRequest) HasParallelToolCalls() bool`

HasParallelToolCalls returns a boolean if a field has been set.

### GetReasoning

`func (o *FelorxResponsesCreateRequest) GetReasoning() map[string]interface{}`

GetReasoning returns the Reasoning field if non-nil, zero value otherwise.

### GetReasoningOk

`func (o *FelorxResponsesCreateRequest) GetReasoningOk() (*map[string]interface{}, bool)`

GetReasoningOk returns a tuple with the Reasoning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReasoning

`func (o *FelorxResponsesCreateRequest) SetReasoning(v map[string]interface{})`

SetReasoning sets Reasoning field to given value.

### HasReasoning

`func (o *FelorxResponsesCreateRequest) HasReasoning() bool`

HasReasoning returns a boolean if a field has been set.

### GetText

`func (o *FelorxResponsesCreateRequest) GetText() map[string]interface{}`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *FelorxResponsesCreateRequest) GetTextOk() (*map[string]interface{}, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *FelorxResponsesCreateRequest) SetText(v map[string]interface{})`

SetText sets Text field to given value.

### HasText

`func (o *FelorxResponsesCreateRequest) HasText() bool`

HasText returns a boolean if a field has been set.

### GetTruncation

`func (o *FelorxResponsesCreateRequest) GetTruncation() string`

GetTruncation returns the Truncation field if non-nil, zero value otherwise.

### GetTruncationOk

`func (o *FelorxResponsesCreateRequest) GetTruncationOk() (*string, bool)`

GetTruncationOk returns a tuple with the Truncation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruncation

`func (o *FelorxResponsesCreateRequest) SetTruncation(v string)`

SetTruncation sets Truncation field to given value.

### HasTruncation

`func (o *FelorxResponsesCreateRequest) HasTruncation() bool`

HasTruncation returns a boolean if a field has been set.

### GetStream

`func (o *FelorxResponsesCreateRequest) GetStream() bool`

GetStream returns the Stream field if non-nil, zero value otherwise.

### GetStreamOk

`func (o *FelorxResponsesCreateRequest) GetStreamOk() (*bool, bool)`

GetStreamOk returns a tuple with the Stream field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStream

`func (o *FelorxResponsesCreateRequest) SetStream(v bool)`

SetStream sets Stream field to given value.

### HasStream

`func (o *FelorxResponsesCreateRequest) HasStream() bool`

HasStream returns a boolean if a field has been set.

### GetStore

`func (o *FelorxResponsesCreateRequest) GetStore() bool`

GetStore returns the Store field if non-nil, zero value otherwise.

### GetStoreOk

`func (o *FelorxResponsesCreateRequest) GetStoreOk() (*bool, bool)`

GetStoreOk returns a tuple with the Store field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStore

`func (o *FelorxResponsesCreateRequest) SetStore(v bool)`

SetStore sets Store field to given value.

### HasStore

`func (o *FelorxResponsesCreateRequest) HasStore() bool`

HasStore returns a boolean if a field has been set.

### GetBackground

`func (o *FelorxResponsesCreateRequest) GetBackground() bool`

GetBackground returns the Background field if non-nil, zero value otherwise.

### GetBackgroundOk

`func (o *FelorxResponsesCreateRequest) GetBackgroundOk() (*bool, bool)`

GetBackgroundOk returns a tuple with the Background field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackground

`func (o *FelorxResponsesCreateRequest) SetBackground(v bool)`

SetBackground sets Background field to given value.

### HasBackground

`func (o *FelorxResponsesCreateRequest) HasBackground() bool`

HasBackground returns a boolean if a field has been set.

### GetMaxOutputTokens

`func (o *FelorxResponsesCreateRequest) GetMaxOutputTokens() int32`

GetMaxOutputTokens returns the MaxOutputTokens field if non-nil, zero value otherwise.

### GetMaxOutputTokensOk

`func (o *FelorxResponsesCreateRequest) GetMaxOutputTokensOk() (*int32, bool)`

GetMaxOutputTokensOk returns a tuple with the MaxOutputTokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxOutputTokens

`func (o *FelorxResponsesCreateRequest) SetMaxOutputTokens(v int32)`

SetMaxOutputTokens sets MaxOutputTokens field to given value.

### HasMaxOutputTokens

`func (o *FelorxResponsesCreateRequest) HasMaxOutputTokens() bool`

HasMaxOutputTokens returns a boolean if a field has been set.

### GetTemperature

`func (o *FelorxResponsesCreateRequest) GetTemperature() float32`

GetTemperature returns the Temperature field if non-nil, zero value otherwise.

### GetTemperatureOk

`func (o *FelorxResponsesCreateRequest) GetTemperatureOk() (*float32, bool)`

GetTemperatureOk returns a tuple with the Temperature field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemperature

`func (o *FelorxResponsesCreateRequest) SetTemperature(v float32)`

SetTemperature sets Temperature field to given value.

### HasTemperature

`func (o *FelorxResponsesCreateRequest) HasTemperature() bool`

HasTemperature returns a boolean if a field has been set.

### GetTopP

`func (o *FelorxResponsesCreateRequest) GetTopP() float32`

GetTopP returns the TopP field if non-nil, zero value otherwise.

### GetTopPOk

`func (o *FelorxResponsesCreateRequest) GetTopPOk() (*float32, bool)`

GetTopPOk returns a tuple with the TopP field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopP

`func (o *FelorxResponsesCreateRequest) SetTopP(v float32)`

SetTopP sets TopP field to given value.

### HasTopP

`func (o *FelorxResponsesCreateRequest) HasTopP() bool`

HasTopP returns a boolean if a field has been set.

### GetMetadata

`func (o *FelorxResponsesCreateRequest) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *FelorxResponsesCreateRequest) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *FelorxResponsesCreateRequest) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *FelorxResponsesCreateRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetServiceTier

`func (o *FelorxResponsesCreateRequest) GetServiceTier() string`

GetServiceTier returns the ServiceTier field if non-nil, zero value otherwise.

### GetServiceTierOk

`func (o *FelorxResponsesCreateRequest) GetServiceTierOk() (*string, bool)`

GetServiceTierOk returns a tuple with the ServiceTier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceTier

`func (o *FelorxResponsesCreateRequest) SetServiceTier(v string)`

SetServiceTier sets ServiceTier field to given value.

### HasServiceTier

`func (o *FelorxResponsesCreateRequest) HasServiceTier() bool`

HasServiceTier returns a boolean if a field has been set.

### GetPromptCacheKey

`func (o *FelorxResponsesCreateRequest) GetPromptCacheKey() string`

GetPromptCacheKey returns the PromptCacheKey field if non-nil, zero value otherwise.

### GetPromptCacheKeyOk

`func (o *FelorxResponsesCreateRequest) GetPromptCacheKeyOk() (*string, bool)`

GetPromptCacheKeyOk returns a tuple with the PromptCacheKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptCacheKey

`func (o *FelorxResponsesCreateRequest) SetPromptCacheKey(v string)`

SetPromptCacheKey sets PromptCacheKey field to given value.

### HasPromptCacheKey

`func (o *FelorxResponsesCreateRequest) HasPromptCacheKey() bool`

HasPromptCacheKey returns a boolean if a field has been set.

### GetPromptCacheRetention

`func (o *FelorxResponsesCreateRequest) GetPromptCacheRetention() string`

GetPromptCacheRetention returns the PromptCacheRetention field if non-nil, zero value otherwise.

### GetPromptCacheRetentionOk

`func (o *FelorxResponsesCreateRequest) GetPromptCacheRetentionOk() (*string, bool)`

GetPromptCacheRetentionOk returns a tuple with the PromptCacheRetention field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptCacheRetention

`func (o *FelorxResponsesCreateRequest) SetPromptCacheRetention(v string)`

SetPromptCacheRetention sets PromptCacheRetention field to given value.

### HasPromptCacheRetention

`func (o *FelorxResponsesCreateRequest) HasPromptCacheRetention() bool`

HasPromptCacheRetention returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


