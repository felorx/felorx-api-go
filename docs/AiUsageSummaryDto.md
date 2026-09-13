# AiUsageSummaryDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**From** | Pointer to **time.Time** |  | [optional] 
**To** | Pointer to **time.Time** |  | [optional] 
**ModelUsages** | Pointer to [**[]AiModelUsageDto**](AiModelUsageDto.md) |  | [optional] 
**RuntimeUsages** | Pointer to **[]interface{}** |  | [optional] 

## Methods

### NewAiUsageSummaryDto

`func NewAiUsageSummaryDto() *AiUsageSummaryDto`

NewAiUsageSummaryDto instantiates a new AiUsageSummaryDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiUsageSummaryDtoWithDefaults

`func NewAiUsageSummaryDtoWithDefaults() *AiUsageSummaryDto`

NewAiUsageSummaryDtoWithDefaults instantiates a new AiUsageSummaryDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFrom

`func (o *AiUsageSummaryDto) GetFrom() time.Time`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *AiUsageSummaryDto) GetFromOk() (*time.Time, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *AiUsageSummaryDto) SetFrom(v time.Time)`

SetFrom sets From field to given value.

### HasFrom

`func (o *AiUsageSummaryDto) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *AiUsageSummaryDto) GetTo() time.Time`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *AiUsageSummaryDto) GetToOk() (*time.Time, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *AiUsageSummaryDto) SetTo(v time.Time)`

SetTo sets To field to given value.

### HasTo

`func (o *AiUsageSummaryDto) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetModelUsages

`func (o *AiUsageSummaryDto) GetModelUsages() []AiModelUsageDto`

GetModelUsages returns the ModelUsages field if non-nil, zero value otherwise.

### GetModelUsagesOk

`func (o *AiUsageSummaryDto) GetModelUsagesOk() (*[]AiModelUsageDto, bool)`

GetModelUsagesOk returns a tuple with the ModelUsages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelUsages

`func (o *AiUsageSummaryDto) SetModelUsages(v []AiModelUsageDto)`

SetModelUsages sets ModelUsages field to given value.

### HasModelUsages

`func (o *AiUsageSummaryDto) HasModelUsages() bool`

HasModelUsages returns a boolean if a field has been set.

### SetModelUsagesNil

`func (o *AiUsageSummaryDto) SetModelUsagesNil(b bool)`

 SetModelUsagesNil sets the value for ModelUsages to be an explicit nil

### UnsetModelUsages
`func (o *AiUsageSummaryDto) UnsetModelUsages()`

UnsetModelUsages ensures that no value is present for ModelUsages, not even an explicit nil
### GetRuntimeUsages

`func (o *AiUsageSummaryDto) GetRuntimeUsages() []interface{}`

GetRuntimeUsages returns the RuntimeUsages field if non-nil, zero value otherwise.

### GetRuntimeUsagesOk

`func (o *AiUsageSummaryDto) GetRuntimeUsagesOk() (*[]interface{}, bool)`

GetRuntimeUsagesOk returns a tuple with the RuntimeUsages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRuntimeUsages

`func (o *AiUsageSummaryDto) SetRuntimeUsages(v []interface{})`

SetRuntimeUsages sets RuntimeUsages field to given value.

### HasRuntimeUsages

`func (o *AiUsageSummaryDto) HasRuntimeUsages() bool`

HasRuntimeUsages returns a boolean if a field has been set.

### SetRuntimeUsagesNil

`func (o *AiUsageSummaryDto) SetRuntimeUsagesNil(b bool)`

 SetRuntimeUsagesNil sets the value for RuntimeUsages to be an explicit nil

### UnsetRuntimeUsages
`func (o *AiUsageSummaryDto) UnsetRuntimeUsages()`

UnsetRuntimeUsages ensures that no value is present for RuntimeUsages, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


