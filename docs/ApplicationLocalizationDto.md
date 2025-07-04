# ApplicationLocalizationDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Resources** | Pointer to [**map[string]ApplicationLocalizationResourceDto**](ApplicationLocalizationResourceDto.md) |  | [optional] 

## Methods

### NewApplicationLocalizationDto

`func NewApplicationLocalizationDto() *ApplicationLocalizationDto`

NewApplicationLocalizationDto instantiates a new ApplicationLocalizationDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApplicationLocalizationDtoWithDefaults

`func NewApplicationLocalizationDtoWithDefaults() *ApplicationLocalizationDto`

NewApplicationLocalizationDtoWithDefaults instantiates a new ApplicationLocalizationDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResources

`func (o *ApplicationLocalizationDto) GetResources() map[string]ApplicationLocalizationResourceDto`

GetResources returns the Resources field if non-nil, zero value otherwise.

### GetResourcesOk

`func (o *ApplicationLocalizationDto) GetResourcesOk() (*map[string]ApplicationLocalizationResourceDto, bool)`

GetResourcesOk returns a tuple with the Resources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResources

`func (o *ApplicationLocalizationDto) SetResources(v map[string]ApplicationLocalizationResourceDto)`

SetResources sets Resources field to given value.

### HasResources

`func (o *ApplicationLocalizationDto) HasResources() bool`

HasResources returns a boolean if a field has been set.

### SetResourcesNil

`func (o *ApplicationLocalizationDto) SetResourcesNil(b bool)`

 SetResourcesNil sets the value for Resources to be an explicit nil

### UnsetResources
`func (o *ApplicationLocalizationDto) UnsetResources()`

UnsetResources ensures that no value is present for Resources, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


