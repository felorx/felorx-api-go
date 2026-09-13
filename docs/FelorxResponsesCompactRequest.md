# FelorxResponsesCompactRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Model** | Pointer to **string** |  | [optional] 
**Input** | Pointer to [**FelorxResponseInput**](FelorxResponseInput.md) |  | [optional] 
**Instructions** | Pointer to **string** |  | [optional] 
**PreviousResponseId** | Pointer to **string** |  | [optional] 
**PromptCacheKey** | Pointer to **string** |  | [optional] 
**PromptCacheOptions** | Pointer to **map[string]interface{}** |  | [optional] 
**PromptCacheRetention** | Pointer to **string** |  | [optional] 
**ServiceTier** | Pointer to **string** |  | [optional] 

## Methods

### NewFelorxResponsesCompactRequest

`func NewFelorxResponsesCompactRequest() *FelorxResponsesCompactRequest`

NewFelorxResponsesCompactRequest instantiates a new FelorxResponsesCompactRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFelorxResponsesCompactRequestWithDefaults

`func NewFelorxResponsesCompactRequestWithDefaults() *FelorxResponsesCompactRequest`

NewFelorxResponsesCompactRequestWithDefaults instantiates a new FelorxResponsesCompactRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetModel

`func (o *FelorxResponsesCompactRequest) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *FelorxResponsesCompactRequest) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *FelorxResponsesCompactRequest) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *FelorxResponsesCompactRequest) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetInput

`func (o *FelorxResponsesCompactRequest) GetInput() FelorxResponseInput`

GetInput returns the Input field if non-nil, zero value otherwise.

### GetInputOk

`func (o *FelorxResponsesCompactRequest) GetInputOk() (*FelorxResponseInput, bool)`

GetInputOk returns a tuple with the Input field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInput

`func (o *FelorxResponsesCompactRequest) SetInput(v FelorxResponseInput)`

SetInput sets Input field to given value.

### HasInput

`func (o *FelorxResponsesCompactRequest) HasInput() bool`

HasInput returns a boolean if a field has been set.

### GetInstructions

`func (o *FelorxResponsesCompactRequest) GetInstructions() string`

GetInstructions returns the Instructions field if non-nil, zero value otherwise.

### GetInstructionsOk

`func (o *FelorxResponsesCompactRequest) GetInstructionsOk() (*string, bool)`

GetInstructionsOk returns a tuple with the Instructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstructions

`func (o *FelorxResponsesCompactRequest) SetInstructions(v string)`

SetInstructions sets Instructions field to given value.

### HasInstructions

`func (o *FelorxResponsesCompactRequest) HasInstructions() bool`

HasInstructions returns a boolean if a field has been set.

### GetPreviousResponseId

`func (o *FelorxResponsesCompactRequest) GetPreviousResponseId() string`

GetPreviousResponseId returns the PreviousResponseId field if non-nil, zero value otherwise.

### GetPreviousResponseIdOk

`func (o *FelorxResponsesCompactRequest) GetPreviousResponseIdOk() (*string, bool)`

GetPreviousResponseIdOk returns a tuple with the PreviousResponseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviousResponseId

`func (o *FelorxResponsesCompactRequest) SetPreviousResponseId(v string)`

SetPreviousResponseId sets PreviousResponseId field to given value.

### HasPreviousResponseId

`func (o *FelorxResponsesCompactRequest) HasPreviousResponseId() bool`

HasPreviousResponseId returns a boolean if a field has been set.

### GetPromptCacheKey

`func (o *FelorxResponsesCompactRequest) GetPromptCacheKey() string`

GetPromptCacheKey returns the PromptCacheKey field if non-nil, zero value otherwise.

### GetPromptCacheKeyOk

`func (o *FelorxResponsesCompactRequest) GetPromptCacheKeyOk() (*string, bool)`

GetPromptCacheKeyOk returns a tuple with the PromptCacheKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptCacheKey

`func (o *FelorxResponsesCompactRequest) SetPromptCacheKey(v string)`

SetPromptCacheKey sets PromptCacheKey field to given value.

### HasPromptCacheKey

`func (o *FelorxResponsesCompactRequest) HasPromptCacheKey() bool`

HasPromptCacheKey returns a boolean if a field has been set.

### GetPromptCacheOptions

`func (o *FelorxResponsesCompactRequest) GetPromptCacheOptions() map[string]interface{}`

GetPromptCacheOptions returns the PromptCacheOptions field if non-nil, zero value otherwise.

### GetPromptCacheOptionsOk

`func (o *FelorxResponsesCompactRequest) GetPromptCacheOptionsOk() (*map[string]interface{}, bool)`

GetPromptCacheOptionsOk returns a tuple with the PromptCacheOptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptCacheOptions

`func (o *FelorxResponsesCompactRequest) SetPromptCacheOptions(v map[string]interface{})`

SetPromptCacheOptions sets PromptCacheOptions field to given value.

### HasPromptCacheOptions

`func (o *FelorxResponsesCompactRequest) HasPromptCacheOptions() bool`

HasPromptCacheOptions returns a boolean if a field has been set.

### GetPromptCacheRetention

`func (o *FelorxResponsesCompactRequest) GetPromptCacheRetention() string`

GetPromptCacheRetention returns the PromptCacheRetention field if non-nil, zero value otherwise.

### GetPromptCacheRetentionOk

`func (o *FelorxResponsesCompactRequest) GetPromptCacheRetentionOk() (*string, bool)`

GetPromptCacheRetentionOk returns a tuple with the PromptCacheRetention field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptCacheRetention

`func (o *FelorxResponsesCompactRequest) SetPromptCacheRetention(v string)`

SetPromptCacheRetention sets PromptCacheRetention field to given value.

### HasPromptCacheRetention

`func (o *FelorxResponsesCompactRequest) HasPromptCacheRetention() bool`

HasPromptCacheRetention returns a boolean if a field has been set.

### GetServiceTier

`func (o *FelorxResponsesCompactRequest) GetServiceTier() string`

GetServiceTier returns the ServiceTier field if non-nil, zero value otherwise.

### GetServiceTierOk

`func (o *FelorxResponsesCompactRequest) GetServiceTierOk() (*string, bool)`

GetServiceTierOk returns a tuple with the ServiceTier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceTier

`func (o *FelorxResponsesCompactRequest) SetServiceTier(v string)`

SetServiceTier sets ServiceTier field to given value.

### HasServiceTier

`func (o *FelorxResponsesCompactRequest) HasServiceTier() bool`

HasServiceTier returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


