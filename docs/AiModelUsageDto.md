# AiModelUsageDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ChargeKind** | Pointer to **NullableString** |  | [optional] 
**RequestCount** | Pointer to **int64** |  | [optional] 
**InputTokens** | Pointer to **int64** |  | [optional] 
**CachedInputTokens** | Pointer to **int64** |  | [optional] 
**OutputTokens** | Pointer to **int64** |  | [optional] 
**ReasoningTokens** | Pointer to **int64** |  | [optional] 
**TotalTokens** | Pointer to **int64** |  | [optional] 
**PricedRequestCount** | Pointer to **int64** |  | [optional] 
**UnpricedRequestCount** | Pointer to **int64** |  | [optional] 
**EstimatedCostMicrousd** | Pointer to **int64** |  | [optional] 

## Methods

### NewAiModelUsageDto

`func NewAiModelUsageDto() *AiModelUsageDto`

NewAiModelUsageDto instantiates a new AiModelUsageDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiModelUsageDtoWithDefaults

`func NewAiModelUsageDtoWithDefaults() *AiModelUsageDto`

NewAiModelUsageDtoWithDefaults instantiates a new AiModelUsageDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetChargeKind

`func (o *AiModelUsageDto) GetChargeKind() string`

GetChargeKind returns the ChargeKind field if non-nil, zero value otherwise.

### GetChargeKindOk

`func (o *AiModelUsageDto) GetChargeKindOk() (*string, bool)`

GetChargeKindOk returns a tuple with the ChargeKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChargeKind

`func (o *AiModelUsageDto) SetChargeKind(v string)`

SetChargeKind sets ChargeKind field to given value.

### HasChargeKind

`func (o *AiModelUsageDto) HasChargeKind() bool`

HasChargeKind returns a boolean if a field has been set.

### SetChargeKindNil

`func (o *AiModelUsageDto) SetChargeKindNil(b bool)`

 SetChargeKindNil sets the value for ChargeKind to be an explicit nil

### UnsetChargeKind
`func (o *AiModelUsageDto) UnsetChargeKind()`

UnsetChargeKind ensures that no value is present for ChargeKind, not even an explicit nil
### GetRequestCount

`func (o *AiModelUsageDto) GetRequestCount() int64`

GetRequestCount returns the RequestCount field if non-nil, zero value otherwise.

### GetRequestCountOk

`func (o *AiModelUsageDto) GetRequestCountOk() (*int64, bool)`

GetRequestCountOk returns a tuple with the RequestCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestCount

`func (o *AiModelUsageDto) SetRequestCount(v int64)`

SetRequestCount sets RequestCount field to given value.

### HasRequestCount

`func (o *AiModelUsageDto) HasRequestCount() bool`

HasRequestCount returns a boolean if a field has been set.

### GetInputTokens

`func (o *AiModelUsageDto) GetInputTokens() int64`

GetInputTokens returns the InputTokens field if non-nil, zero value otherwise.

### GetInputTokensOk

`func (o *AiModelUsageDto) GetInputTokensOk() (*int64, bool)`

GetInputTokensOk returns a tuple with the InputTokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputTokens

`func (o *AiModelUsageDto) SetInputTokens(v int64)`

SetInputTokens sets InputTokens field to given value.

### HasInputTokens

`func (o *AiModelUsageDto) HasInputTokens() bool`

HasInputTokens returns a boolean if a field has been set.

### GetCachedInputTokens

`func (o *AiModelUsageDto) GetCachedInputTokens() int64`

GetCachedInputTokens returns the CachedInputTokens field if non-nil, zero value otherwise.

### GetCachedInputTokensOk

`func (o *AiModelUsageDto) GetCachedInputTokensOk() (*int64, bool)`

GetCachedInputTokensOk returns a tuple with the CachedInputTokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCachedInputTokens

`func (o *AiModelUsageDto) SetCachedInputTokens(v int64)`

SetCachedInputTokens sets CachedInputTokens field to given value.

### HasCachedInputTokens

`func (o *AiModelUsageDto) HasCachedInputTokens() bool`

HasCachedInputTokens returns a boolean if a field has been set.

### GetOutputTokens

`func (o *AiModelUsageDto) GetOutputTokens() int64`

GetOutputTokens returns the OutputTokens field if non-nil, zero value otherwise.

### GetOutputTokensOk

`func (o *AiModelUsageDto) GetOutputTokensOk() (*int64, bool)`

GetOutputTokensOk returns a tuple with the OutputTokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputTokens

`func (o *AiModelUsageDto) SetOutputTokens(v int64)`

SetOutputTokens sets OutputTokens field to given value.

### HasOutputTokens

`func (o *AiModelUsageDto) HasOutputTokens() bool`

HasOutputTokens returns a boolean if a field has been set.

### GetReasoningTokens

`func (o *AiModelUsageDto) GetReasoningTokens() int64`

GetReasoningTokens returns the ReasoningTokens field if non-nil, zero value otherwise.

### GetReasoningTokensOk

`func (o *AiModelUsageDto) GetReasoningTokensOk() (*int64, bool)`

GetReasoningTokensOk returns a tuple with the ReasoningTokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReasoningTokens

`func (o *AiModelUsageDto) SetReasoningTokens(v int64)`

SetReasoningTokens sets ReasoningTokens field to given value.

### HasReasoningTokens

`func (o *AiModelUsageDto) HasReasoningTokens() bool`

HasReasoningTokens returns a boolean if a field has been set.

### GetTotalTokens

`func (o *AiModelUsageDto) GetTotalTokens() int64`

GetTotalTokens returns the TotalTokens field if non-nil, zero value otherwise.

### GetTotalTokensOk

`func (o *AiModelUsageDto) GetTotalTokensOk() (*int64, bool)`

GetTotalTokensOk returns a tuple with the TotalTokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalTokens

`func (o *AiModelUsageDto) SetTotalTokens(v int64)`

SetTotalTokens sets TotalTokens field to given value.

### HasTotalTokens

`func (o *AiModelUsageDto) HasTotalTokens() bool`

HasTotalTokens returns a boolean if a field has been set.

### GetPricedRequestCount

`func (o *AiModelUsageDto) GetPricedRequestCount() int64`

GetPricedRequestCount returns the PricedRequestCount field if non-nil, zero value otherwise.

### GetPricedRequestCountOk

`func (o *AiModelUsageDto) GetPricedRequestCountOk() (*int64, bool)`

GetPricedRequestCountOk returns a tuple with the PricedRequestCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPricedRequestCount

`func (o *AiModelUsageDto) SetPricedRequestCount(v int64)`

SetPricedRequestCount sets PricedRequestCount field to given value.

### HasPricedRequestCount

`func (o *AiModelUsageDto) HasPricedRequestCount() bool`

HasPricedRequestCount returns a boolean if a field has been set.

### GetUnpricedRequestCount

`func (o *AiModelUsageDto) GetUnpricedRequestCount() int64`

GetUnpricedRequestCount returns the UnpricedRequestCount field if non-nil, zero value otherwise.

### GetUnpricedRequestCountOk

`func (o *AiModelUsageDto) GetUnpricedRequestCountOk() (*int64, bool)`

GetUnpricedRequestCountOk returns a tuple with the UnpricedRequestCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnpricedRequestCount

`func (o *AiModelUsageDto) SetUnpricedRequestCount(v int64)`

SetUnpricedRequestCount sets UnpricedRequestCount field to given value.

### HasUnpricedRequestCount

`func (o *AiModelUsageDto) HasUnpricedRequestCount() bool`

HasUnpricedRequestCount returns a boolean if a field has been set.

### GetEstimatedCostMicrousd

`func (o *AiModelUsageDto) GetEstimatedCostMicrousd() int64`

GetEstimatedCostMicrousd returns the EstimatedCostMicrousd field if non-nil, zero value otherwise.

### GetEstimatedCostMicrousdOk

`func (o *AiModelUsageDto) GetEstimatedCostMicrousdOk() (*int64, bool)`

GetEstimatedCostMicrousdOk returns a tuple with the EstimatedCostMicrousd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedCostMicrousd

`func (o *AiModelUsageDto) SetEstimatedCostMicrousd(v int64)`

SetEstimatedCostMicrousd sets EstimatedCostMicrousd field to given value.

### HasEstimatedCostMicrousd

`func (o *AiModelUsageDto) HasEstimatedCostMicrousd() bool`

HasEstimatedCostMicrousd returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


