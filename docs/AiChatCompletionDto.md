# AiChatCompletionDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **NullableString** |  | [optional] 
**Object** | Pointer to **NullableString** |  | [optional] 
**Created** | Pointer to **int64** |  | [optional] 
**Model** | Pointer to **NullableString** |  | [optional] 
**Choices** | Pointer to [**[]AiChatChoiceDto**](AiChatChoiceDto.md) |  | [optional] 
**Usage** | Pointer to [**AiUsageDto**](AiUsageDto.md) |  | [optional] 

## Methods

### NewAiChatCompletionDto

`func NewAiChatCompletionDto() *AiChatCompletionDto`

NewAiChatCompletionDto instantiates a new AiChatCompletionDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAiChatCompletionDtoWithDefaults

`func NewAiChatCompletionDtoWithDefaults() *AiChatCompletionDto`

NewAiChatCompletionDtoWithDefaults instantiates a new AiChatCompletionDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AiChatCompletionDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AiChatCompletionDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AiChatCompletionDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AiChatCompletionDto) HasId() bool`

HasId returns a boolean if a field has been set.

### SetIdNil

`func (o *AiChatCompletionDto) SetIdNil(b bool)`

 SetIdNil sets the value for Id to be an explicit nil

### UnsetId
`func (o *AiChatCompletionDto) UnsetId()`

UnsetId ensures that no value is present for Id, not even an explicit nil
### GetObject

`func (o *AiChatCompletionDto) GetObject() string`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *AiChatCompletionDto) GetObjectOk() (*string, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *AiChatCompletionDto) SetObject(v string)`

SetObject sets Object field to given value.

### HasObject

`func (o *AiChatCompletionDto) HasObject() bool`

HasObject returns a boolean if a field has been set.

### SetObjectNil

`func (o *AiChatCompletionDto) SetObjectNil(b bool)`

 SetObjectNil sets the value for Object to be an explicit nil

### UnsetObject
`func (o *AiChatCompletionDto) UnsetObject()`

UnsetObject ensures that no value is present for Object, not even an explicit nil
### GetCreated

`func (o *AiChatCompletionDto) GetCreated() int64`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *AiChatCompletionDto) GetCreatedOk() (*int64, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *AiChatCompletionDto) SetCreated(v int64)`

SetCreated sets Created field to given value.

### HasCreated

`func (o *AiChatCompletionDto) HasCreated() bool`

HasCreated returns a boolean if a field has been set.

### GetModel

`func (o *AiChatCompletionDto) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AiChatCompletionDto) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AiChatCompletionDto) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *AiChatCompletionDto) HasModel() bool`

HasModel returns a boolean if a field has been set.

### SetModelNil

`func (o *AiChatCompletionDto) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *AiChatCompletionDto) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetChoices

`func (o *AiChatCompletionDto) GetChoices() []AiChatChoiceDto`

GetChoices returns the Choices field if non-nil, zero value otherwise.

### GetChoicesOk

`func (o *AiChatCompletionDto) GetChoicesOk() (*[]AiChatChoiceDto, bool)`

GetChoicesOk returns a tuple with the Choices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChoices

`func (o *AiChatCompletionDto) SetChoices(v []AiChatChoiceDto)`

SetChoices sets Choices field to given value.

### HasChoices

`func (o *AiChatCompletionDto) HasChoices() bool`

HasChoices returns a boolean if a field has been set.

### SetChoicesNil

`func (o *AiChatCompletionDto) SetChoicesNil(b bool)`

 SetChoicesNil sets the value for Choices to be an explicit nil

### UnsetChoices
`func (o *AiChatCompletionDto) UnsetChoices()`

UnsetChoices ensures that no value is present for Choices, not even an explicit nil
### GetUsage

`func (o *AiChatCompletionDto) GetUsage() AiUsageDto`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *AiChatCompletionDto) GetUsageOk() (*AiUsageDto, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *AiChatCompletionDto) SetUsage(v AiUsageDto)`

SetUsage sets Usage field to given value.

### HasUsage

`func (o *AiChatCompletionDto) HasUsage() bool`

HasUsage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


