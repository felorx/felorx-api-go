# SetDefaultAiModelDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ModelId** | Pointer to **string** |  | [optional]
**Capability** | Pointer to [**AiCapability**](AiCapability.md) |  | [optional]

## Methods

### NewSetDefaultAiModelDto

`func NewSetDefaultAiModelDto() *SetDefaultAiModelDto`

NewSetDefaultAiModelDto instantiates a new SetDefaultAiModelDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSetDefaultAiModelDtoWithDefaults

`func NewSetDefaultAiModelDtoWithDefaults() *SetDefaultAiModelDto`

NewSetDefaultAiModelDtoWithDefaults instantiates a new SetDefaultAiModelDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetModelId

`func (o *SetDefaultAiModelDto) GetModelId() string`

GetModelId returns the ModelId field if non-nil, zero value otherwise.

### GetModelIdOk

`func (o *SetDefaultAiModelDto) GetModelIdOk() (*string, bool)`

GetModelIdOk returns a tuple with the ModelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelId

`func (o *SetDefaultAiModelDto) SetModelId(v string)`

SetModelId sets ModelId field to given value.

### HasModelId

`func (o *SetDefaultAiModelDto) HasModelId() bool`

HasModelId returns a boolean if a field has been set.

### GetCapability

`func (o *SetDefaultAiModelDto) GetCapability() AiCapability`

GetCapability returns the Capability field if non-nil, zero value otherwise.

### GetCapabilityOk

`func (o *SetDefaultAiModelDto) GetCapabilityOk() (*AiCapability, bool)`

GetCapabilityOk returns a tuple with the Capability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapability

`func (o *SetDefaultAiModelDto) SetCapability(v AiCapability)`

SetCapability sets Capability field to given value.

### HasCapability

`func (o *SetDefaultAiModelDto) HasCapability() bool`

HasCapability returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


