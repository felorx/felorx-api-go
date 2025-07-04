# UpdateFeaturesDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Features** | Pointer to [**[]UpdateFeatureDto**](UpdateFeatureDto.md) |  | [optional] 

## Methods

### NewUpdateFeaturesDto

`func NewUpdateFeaturesDto() *UpdateFeaturesDto`

NewUpdateFeaturesDto instantiates a new UpdateFeaturesDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateFeaturesDtoWithDefaults

`func NewUpdateFeaturesDtoWithDefaults() *UpdateFeaturesDto`

NewUpdateFeaturesDtoWithDefaults instantiates a new UpdateFeaturesDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFeatures

`func (o *UpdateFeaturesDto) GetFeatures() []UpdateFeatureDto`

GetFeatures returns the Features field if non-nil, zero value otherwise.

### GetFeaturesOk

`func (o *UpdateFeaturesDto) GetFeaturesOk() (*[]UpdateFeatureDto, bool)`

GetFeaturesOk returns a tuple with the Features field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatures

`func (o *UpdateFeaturesDto) SetFeatures(v []UpdateFeatureDto)`

SetFeatures sets Features field to given value.

### HasFeatures

`func (o *UpdateFeaturesDto) HasFeatures() bool`

HasFeatures returns a boolean if a field has been set.

### SetFeaturesNil

`func (o *UpdateFeaturesDto) SetFeaturesNil(b bool)`

 SetFeaturesNil sets the value for Features to be an explicit nil

### UnsetFeatures
`func (o *UpdateFeaturesDto) UnsetFeatures()`

UnsetFeatures ensures that no value is present for Features, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


