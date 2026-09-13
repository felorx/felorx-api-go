# FelorxResponsesCountRequest

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
**Personality** | Pointer to **string** |  | [optional] 

## Methods

### NewFelorxResponsesCountRequest

`func NewFelorxResponsesCountRequest() *FelorxResponsesCountRequest`

NewFelorxResponsesCountRequest instantiates a new FelorxResponsesCountRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFelorxResponsesCountRequestWithDefaults

`func NewFelorxResponsesCountRequestWithDefaults() *FelorxResponsesCountRequest`

NewFelorxResponsesCountRequestWithDefaults instantiates a new FelorxResponsesCountRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetModel

`func (o *FelorxResponsesCountRequest) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *FelorxResponsesCountRequest) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *FelorxResponsesCountRequest) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *FelorxResponsesCountRequest) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetInput

`func (o *FelorxResponsesCountRequest) GetInput() FelorxResponseInput`

GetInput returns the Input field if non-nil, zero value otherwise.

### GetInputOk

`func (o *FelorxResponsesCountRequest) GetInputOk() (*FelorxResponseInput, bool)`

GetInputOk returns a tuple with the Input field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInput

`func (o *FelorxResponsesCountRequest) SetInput(v FelorxResponseInput)`

SetInput sets Input field to given value.

### HasInput

`func (o *FelorxResponsesCountRequest) HasInput() bool`

HasInput returns a boolean if a field has been set.

### GetInstructions

`func (o *FelorxResponsesCountRequest) GetInstructions() string`

GetInstructions returns the Instructions field if non-nil, zero value otherwise.

### GetInstructionsOk

`func (o *FelorxResponsesCountRequest) GetInstructionsOk() (*string, bool)`

GetInstructionsOk returns a tuple with the Instructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstructions

`func (o *FelorxResponsesCountRequest) SetInstructions(v string)`

SetInstructions sets Instructions field to given value.

### HasInstructions

`func (o *FelorxResponsesCountRequest) HasInstructions() bool`

HasInstructions returns a boolean if a field has been set.

### GetPreviousResponseId

`func (o *FelorxResponsesCountRequest) GetPreviousResponseId() string`

GetPreviousResponseId returns the PreviousResponseId field if non-nil, zero value otherwise.

### GetPreviousResponseIdOk

`func (o *FelorxResponsesCountRequest) GetPreviousResponseIdOk() (*string, bool)`

GetPreviousResponseIdOk returns a tuple with the PreviousResponseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviousResponseId

`func (o *FelorxResponsesCountRequest) SetPreviousResponseId(v string)`

SetPreviousResponseId sets PreviousResponseId field to given value.

### HasPreviousResponseId

`func (o *FelorxResponsesCountRequest) HasPreviousResponseId() bool`

HasPreviousResponseId returns a boolean if a field has been set.

### GetTools

`func (o *FelorxResponsesCountRequest) GetTools() []FelorxResponsesCountRequestToolsInner`

GetTools returns the Tools field if non-nil, zero value otherwise.

### GetToolsOk

`func (o *FelorxResponsesCountRequest) GetToolsOk() (*[]FelorxResponsesCountRequestToolsInner, bool)`

GetToolsOk returns a tuple with the Tools field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTools

`func (o *FelorxResponsesCountRequest) SetTools(v []FelorxResponsesCountRequestToolsInner)`

SetTools sets Tools field to given value.

### HasTools

`func (o *FelorxResponsesCountRequest) HasTools() bool`

HasTools returns a boolean if a field has been set.

### GetToolChoice

`func (o *FelorxResponsesCountRequest) GetToolChoice() FelorxResponseToolChoice`

GetToolChoice returns the ToolChoice field if non-nil, zero value otherwise.

### GetToolChoiceOk

`func (o *FelorxResponsesCountRequest) GetToolChoiceOk() (*FelorxResponseToolChoice, bool)`

GetToolChoiceOk returns a tuple with the ToolChoice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolChoice

`func (o *FelorxResponsesCountRequest) SetToolChoice(v FelorxResponseToolChoice)`

SetToolChoice sets ToolChoice field to given value.

### HasToolChoice

`func (o *FelorxResponsesCountRequest) HasToolChoice() bool`

HasToolChoice returns a boolean if a field has been set.

### GetParallelToolCalls

`func (o *FelorxResponsesCountRequest) GetParallelToolCalls() bool`

GetParallelToolCalls returns the ParallelToolCalls field if non-nil, zero value otherwise.

### GetParallelToolCallsOk

`func (o *FelorxResponsesCountRequest) GetParallelToolCallsOk() (*bool, bool)`

GetParallelToolCallsOk returns a tuple with the ParallelToolCalls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParallelToolCalls

`func (o *FelorxResponsesCountRequest) SetParallelToolCalls(v bool)`

SetParallelToolCalls sets ParallelToolCalls field to given value.

### HasParallelToolCalls

`func (o *FelorxResponsesCountRequest) HasParallelToolCalls() bool`

HasParallelToolCalls returns a boolean if a field has been set.

### GetReasoning

`func (o *FelorxResponsesCountRequest) GetReasoning() map[string]interface{}`

GetReasoning returns the Reasoning field if non-nil, zero value otherwise.

### GetReasoningOk

`func (o *FelorxResponsesCountRequest) GetReasoningOk() (*map[string]interface{}, bool)`

GetReasoningOk returns a tuple with the Reasoning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReasoning

`func (o *FelorxResponsesCountRequest) SetReasoning(v map[string]interface{})`

SetReasoning sets Reasoning field to given value.

### HasReasoning

`func (o *FelorxResponsesCountRequest) HasReasoning() bool`

HasReasoning returns a boolean if a field has been set.

### GetText

`func (o *FelorxResponsesCountRequest) GetText() map[string]interface{}`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *FelorxResponsesCountRequest) GetTextOk() (*map[string]interface{}, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *FelorxResponsesCountRequest) SetText(v map[string]interface{})`

SetText sets Text field to given value.

### HasText

`func (o *FelorxResponsesCountRequest) HasText() bool`

HasText returns a boolean if a field has been set.

### GetTruncation

`func (o *FelorxResponsesCountRequest) GetTruncation() string`

GetTruncation returns the Truncation field if non-nil, zero value otherwise.

### GetTruncationOk

`func (o *FelorxResponsesCountRequest) GetTruncationOk() (*string, bool)`

GetTruncationOk returns a tuple with the Truncation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruncation

`func (o *FelorxResponsesCountRequest) SetTruncation(v string)`

SetTruncation sets Truncation field to given value.

### HasTruncation

`func (o *FelorxResponsesCountRequest) HasTruncation() bool`

HasTruncation returns a boolean if a field has been set.

### GetPersonality

`func (o *FelorxResponsesCountRequest) GetPersonality() string`

GetPersonality returns the Personality field if non-nil, zero value otherwise.

### GetPersonalityOk

`func (o *FelorxResponsesCountRequest) GetPersonalityOk() (*string, bool)`

GetPersonalityOk returns a tuple with the Personality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersonality

`func (o *FelorxResponsesCountRequest) SetPersonality(v string)`

SetPersonality sets Personality field to given value.

### HasPersonality

`func (o *FelorxResponsesCountRequest) HasPersonality() bool`

HasPersonality returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


