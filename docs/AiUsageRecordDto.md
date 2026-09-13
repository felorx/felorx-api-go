# AiUsageRecordDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**LogicalModel** | Pointer to **NullableString** |  | [optional] 
**ModelChargeKind** | Pointer to **NullableString** |  | [optional] 
**RuntimeChargeKind** | Pointer to **NullableString** |  | [optional] 
**InputTokens** | Pointer to **int64** |  | [optional] 
**OutputTokens** | Pointer to **int64** |  | [optional] 
**TotalTokens** | Pointer to **int64** |  | [optional] 
**RuntimeMilliseconds** | Pointer to **int64** |  | [optional] 
**ObservedAt** | Pointer to **time.Time** |  | [optional] 
**EstimatedModelCostMicrousd** | Pointer to **NullableInt64** |  | [optional] 
**EstimatedRuntimeCostMicrousd** | Pointer to **NullableInt64** |  | [optional] 
**PricingEffectiveAt** | Pointer to **NullableTime** |  | [optional] 
**PricingCapturedAt** | Pointer to **NullableTime** |  | [optional] 
**PricingSourceUrl** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewAiUsageRecordDto

`func NewAiUsageRecordDto() *AiUsageRecordDto`

NewAiUsageRecordDto instantiates a new AiUsageRecordDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiUsageRecordDtoWithDefaults

`func NewAiUsageRecordDtoWithDefaults() *AiUsageRecordDto`

NewAiUsageRecordDtoWithDefaults instantiates a new AiUsageRecordDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AiUsageRecordDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AiUsageRecordDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AiUsageRecordDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AiUsageRecordDto) HasId() bool`

HasId returns a boolean if a field has been set.

### GetLogicalModel

`func (o *AiUsageRecordDto) GetLogicalModel() string`

GetLogicalModel returns the LogicalModel field if non-nil, zero value otherwise.

### GetLogicalModelOk

`func (o *AiUsageRecordDto) GetLogicalModelOk() (*string, bool)`

GetLogicalModelOk returns a tuple with the LogicalModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogicalModel

`func (o *AiUsageRecordDto) SetLogicalModel(v string)`

SetLogicalModel sets LogicalModel field to given value.

### HasLogicalModel

`func (o *AiUsageRecordDto) HasLogicalModel() bool`

HasLogicalModel returns a boolean if a field has been set.

### SetLogicalModelNil

`func (o *AiUsageRecordDto) SetLogicalModelNil(b bool)`

 SetLogicalModelNil sets the value for LogicalModel to be an explicit nil

### UnsetLogicalModel
`func (o *AiUsageRecordDto) UnsetLogicalModel()`

UnsetLogicalModel ensures that no value is present for LogicalModel, not even an explicit nil
### GetModelChargeKind

`func (o *AiUsageRecordDto) GetModelChargeKind() string`

GetModelChargeKind returns the ModelChargeKind field if non-nil, zero value otherwise.

### GetModelChargeKindOk

`func (o *AiUsageRecordDto) GetModelChargeKindOk() (*string, bool)`

GetModelChargeKindOk returns a tuple with the ModelChargeKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelChargeKind

`func (o *AiUsageRecordDto) SetModelChargeKind(v string)`

SetModelChargeKind sets ModelChargeKind field to given value.

### HasModelChargeKind

`func (o *AiUsageRecordDto) HasModelChargeKind() bool`

HasModelChargeKind returns a boolean if a field has been set.

### SetModelChargeKindNil

`func (o *AiUsageRecordDto) SetModelChargeKindNil(b bool)`

 SetModelChargeKindNil sets the value for ModelChargeKind to be an explicit nil

### UnsetModelChargeKind
`func (o *AiUsageRecordDto) UnsetModelChargeKind()`

UnsetModelChargeKind ensures that no value is present for ModelChargeKind, not even an explicit nil
### GetRuntimeChargeKind

`func (o *AiUsageRecordDto) GetRuntimeChargeKind() string`

GetRuntimeChargeKind returns the RuntimeChargeKind field if non-nil, zero value otherwise.

### GetRuntimeChargeKindOk

`func (o *AiUsageRecordDto) GetRuntimeChargeKindOk() (*string, bool)`

GetRuntimeChargeKindOk returns a tuple with the RuntimeChargeKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuntimeChargeKind

`func (o *AiUsageRecordDto) SetRuntimeChargeKind(v string)`

SetRuntimeChargeKind sets RuntimeChargeKind field to given value.

### HasRuntimeChargeKind

`func (o *AiUsageRecordDto) HasRuntimeChargeKind() bool`

HasRuntimeChargeKind returns a boolean if a field has been set.

### SetRuntimeChargeKindNil

`func (o *AiUsageRecordDto) SetRuntimeChargeKindNil(b bool)`

 SetRuntimeChargeKindNil sets the value for RuntimeChargeKind to be an explicit nil

### UnsetRuntimeChargeKind
`func (o *AiUsageRecordDto) UnsetRuntimeChargeKind()`

UnsetRuntimeChargeKind ensures that no value is present for RuntimeChargeKind, not even an explicit nil
### GetInputTokens

`func (o *AiUsageRecordDto) GetInputTokens() int64`

GetInputTokens returns the InputTokens field if non-nil, zero value otherwise.

### GetInputTokensOk

`func (o *AiUsageRecordDto) GetInputTokensOk() (*int64, bool)`

GetInputTokensOk returns a tuple with the InputTokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputTokens

`func (o *AiUsageRecordDto) SetInputTokens(v int64)`

SetInputTokens sets InputTokens field to given value.

### HasInputTokens

`func (o *AiUsageRecordDto) HasInputTokens() bool`

HasInputTokens returns a boolean if a field has been set.

### GetOutputTokens

`func (o *AiUsageRecordDto) GetOutputTokens() int64`

GetOutputTokens returns the OutputTokens field if non-nil, zero value otherwise.

### GetOutputTokensOk

`func (o *AiUsageRecordDto) GetOutputTokensOk() (*int64, bool)`

GetOutputTokensOk returns a tuple with the OutputTokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputTokens

`func (o *AiUsageRecordDto) SetOutputTokens(v int64)`

SetOutputTokens sets OutputTokens field to given value.

### HasOutputTokens

`func (o *AiUsageRecordDto) HasOutputTokens() bool`

HasOutputTokens returns a boolean if a field has been set.

### GetTotalTokens

`func (o *AiUsageRecordDto) GetTotalTokens() int64`

GetTotalTokens returns the TotalTokens field if non-nil, zero value otherwise.

### GetTotalTokensOk

`func (o *AiUsageRecordDto) GetTotalTokensOk() (*int64, bool)`

GetTotalTokensOk returns a tuple with the TotalTokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalTokens

`func (o *AiUsageRecordDto) SetTotalTokens(v int64)`

SetTotalTokens sets TotalTokens field to given value.

### HasTotalTokens

`func (o *AiUsageRecordDto) HasTotalTokens() bool`

HasTotalTokens returns a boolean if a field has been set.

### GetRuntimeMilliseconds

`func (o *AiUsageRecordDto) GetRuntimeMilliseconds() int64`

GetRuntimeMilliseconds returns the RuntimeMilliseconds field if non-nil, zero value otherwise.

### GetRuntimeMillisecondsOk

`func (o *AiUsageRecordDto) GetRuntimeMillisecondsOk() (*int64, bool)`

GetRuntimeMillisecondsOk returns a tuple with the RuntimeMilliseconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuntimeMilliseconds

`func (o *AiUsageRecordDto) SetRuntimeMilliseconds(v int64)`

SetRuntimeMilliseconds sets RuntimeMilliseconds field to given value.

### HasRuntimeMilliseconds

`func (o *AiUsageRecordDto) HasRuntimeMilliseconds() bool`

HasRuntimeMilliseconds returns a boolean if a field has been set.

### GetObservedAt

`func (o *AiUsageRecordDto) GetObservedAt() time.Time`

GetObservedAt returns the ObservedAt field if non-nil, zero value otherwise.

### GetObservedAtOk

`func (o *AiUsageRecordDto) GetObservedAtOk() (*time.Time, bool)`

GetObservedAtOk returns a tuple with the ObservedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObservedAt

`func (o *AiUsageRecordDto) SetObservedAt(v time.Time)`

SetObservedAt sets ObservedAt field to given value.

### HasObservedAt

`func (o *AiUsageRecordDto) HasObservedAt() bool`

HasObservedAt returns a boolean if a field has been set.

### GetEstimatedModelCostMicrousd

`func (o *AiUsageRecordDto) GetEstimatedModelCostMicrousd() int64`

GetEstimatedModelCostMicrousd returns the EstimatedModelCostMicrousd field if non-nil, zero value otherwise.

### GetEstimatedModelCostMicrousdOk

`func (o *AiUsageRecordDto) GetEstimatedModelCostMicrousdOk() (*int64, bool)`

GetEstimatedModelCostMicrousdOk returns a tuple with the EstimatedModelCostMicrousd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedModelCostMicrousd

`func (o *AiUsageRecordDto) SetEstimatedModelCostMicrousd(v int64)`

SetEstimatedModelCostMicrousd sets EstimatedModelCostMicrousd field to given value.

### HasEstimatedModelCostMicrousd

`func (o *AiUsageRecordDto) HasEstimatedModelCostMicrousd() bool`

HasEstimatedModelCostMicrousd returns a boolean if a field has been set.

### SetEstimatedModelCostMicrousdNil

`func (o *AiUsageRecordDto) SetEstimatedModelCostMicrousdNil(b bool)`

 SetEstimatedModelCostMicrousdNil sets the value for EstimatedModelCostMicrousd to be an explicit nil

### UnsetEstimatedModelCostMicrousd
`func (o *AiUsageRecordDto) UnsetEstimatedModelCostMicrousd()`

UnsetEstimatedModelCostMicrousd ensures that no value is present for EstimatedModelCostMicrousd, not even an explicit nil
### GetEstimatedRuntimeCostMicrousd

`func (o *AiUsageRecordDto) GetEstimatedRuntimeCostMicrousd() int64`

GetEstimatedRuntimeCostMicrousd returns the EstimatedRuntimeCostMicrousd field if non-nil, zero value otherwise.

### GetEstimatedRuntimeCostMicrousdOk

`func (o *AiUsageRecordDto) GetEstimatedRuntimeCostMicrousdOk() (*int64, bool)`

GetEstimatedRuntimeCostMicrousdOk returns a tuple with the EstimatedRuntimeCostMicrousd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedRuntimeCostMicrousd

`func (o *AiUsageRecordDto) SetEstimatedRuntimeCostMicrousd(v int64)`

SetEstimatedRuntimeCostMicrousd sets EstimatedRuntimeCostMicrousd field to given value.

### HasEstimatedRuntimeCostMicrousd

`func (o *AiUsageRecordDto) HasEstimatedRuntimeCostMicrousd() bool`

HasEstimatedRuntimeCostMicrousd returns a boolean if a field has been set.

### SetEstimatedRuntimeCostMicrousdNil

`func (o *AiUsageRecordDto) SetEstimatedRuntimeCostMicrousdNil(b bool)`

 SetEstimatedRuntimeCostMicrousdNil sets the value for EstimatedRuntimeCostMicrousd to be an explicit nil

### UnsetEstimatedRuntimeCostMicrousd
`func (o *AiUsageRecordDto) UnsetEstimatedRuntimeCostMicrousd()`

UnsetEstimatedRuntimeCostMicrousd ensures that no value is present for EstimatedRuntimeCostMicrousd, not even an explicit nil
### GetPricingEffectiveAt

`func (o *AiUsageRecordDto) GetPricingEffectiveAt() time.Time`

GetPricingEffectiveAt returns the PricingEffectiveAt field if non-nil, zero value otherwise.

### GetPricingEffectiveAtOk

`func (o *AiUsageRecordDto) GetPricingEffectiveAtOk() (*time.Time, bool)`

GetPricingEffectiveAtOk returns a tuple with the PricingEffectiveAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPricingEffectiveAt

`func (o *AiUsageRecordDto) SetPricingEffectiveAt(v time.Time)`

SetPricingEffectiveAt sets PricingEffectiveAt field to given value.

### HasPricingEffectiveAt

`func (o *AiUsageRecordDto) HasPricingEffectiveAt() bool`

HasPricingEffectiveAt returns a boolean if a field has been set.

### SetPricingEffectiveAtNil

`func (o *AiUsageRecordDto) SetPricingEffectiveAtNil(b bool)`

 SetPricingEffectiveAtNil sets the value for PricingEffectiveAt to be an explicit nil

### UnsetPricingEffectiveAt
`func (o *AiUsageRecordDto) UnsetPricingEffectiveAt()`

UnsetPricingEffectiveAt ensures that no value is present for PricingEffectiveAt, not even an explicit nil
### GetPricingCapturedAt

`func (o *AiUsageRecordDto) GetPricingCapturedAt() time.Time`

GetPricingCapturedAt returns the PricingCapturedAt field if non-nil, zero value otherwise.

### GetPricingCapturedAtOk

`func (o *AiUsageRecordDto) GetPricingCapturedAtOk() (*time.Time, bool)`

GetPricingCapturedAtOk returns a tuple with the PricingCapturedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPricingCapturedAt

`func (o *AiUsageRecordDto) SetPricingCapturedAt(v time.Time)`

SetPricingCapturedAt sets PricingCapturedAt field to given value.

### HasPricingCapturedAt

`func (o *AiUsageRecordDto) HasPricingCapturedAt() bool`

HasPricingCapturedAt returns a boolean if a field has been set.

### SetPricingCapturedAtNil

`func (o *AiUsageRecordDto) SetPricingCapturedAtNil(b bool)`

 SetPricingCapturedAtNil sets the value for PricingCapturedAt to be an explicit nil

### UnsetPricingCapturedAt
`func (o *AiUsageRecordDto) UnsetPricingCapturedAt()`

UnsetPricingCapturedAt ensures that no value is present for PricingCapturedAt, not even an explicit nil
### GetPricingSourceUrl

`func (o *AiUsageRecordDto) GetPricingSourceUrl() string`

GetPricingSourceUrl returns the PricingSourceUrl field if non-nil, zero value otherwise.

### GetPricingSourceUrlOk

`func (o *AiUsageRecordDto) GetPricingSourceUrlOk() (*string, bool)`

GetPricingSourceUrlOk returns a tuple with the PricingSourceUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPricingSourceUrl

`func (o *AiUsageRecordDto) SetPricingSourceUrl(v string)`

SetPricingSourceUrl sets PricingSourceUrl field to given value.

### HasPricingSourceUrl

`func (o *AiUsageRecordDto) HasPricingSourceUrl() bool`

HasPricingSourceUrl returns a boolean if a field has been set.

### SetPricingSourceUrlNil

`func (o *AiUsageRecordDto) SetPricingSourceUrlNil(b bool)`

 SetPricingSourceUrlNil sets the value for PricingSourceUrl to be an explicit nil

### UnsetPricingSourceUrl
`func (o *AiUsageRecordDto) UnsetPricingSourceUrl()`

UnsetPricingSourceUrl ensures that no value is present for PricingSourceUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


