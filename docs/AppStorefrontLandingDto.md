# AppStorefrontLandingDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Hero** | Pointer to [**AppStorefrontHeroDto**](AppStorefrontHeroDto.md) |  | [optional]
**Features** | Pointer to [**[]AppStorefrontFeatureBlockDto**](AppStorefrontFeatureBlockDto.md) |  | [optional]

## Methods

### NewAppStorefrontLandingDto

`func NewAppStorefrontLandingDto() *AppStorefrontLandingDto`

NewAppStorefrontLandingDto instantiates a new AppStorefrontLandingDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAppStorefrontLandingDtoWithDefaults

`func NewAppStorefrontLandingDtoWithDefaults() *AppStorefrontLandingDto`

NewAppStorefrontLandingDtoWithDefaults instantiates a new AppStorefrontLandingDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHero

`func (o *AppStorefrontLandingDto) GetHero() AppStorefrontHeroDto`

GetHero returns the Hero field if non-nil, zero value otherwise.

### GetHeroOk

`func (o *AppStorefrontLandingDto) GetHeroOk() (*AppStorefrontHeroDto, bool)`

GetHeroOk returns a tuple with the Hero field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHero

`func (o *AppStorefrontLandingDto) SetHero(v AppStorefrontHeroDto)`

SetHero sets Hero field to given value.

### HasHero

`func (o *AppStorefrontLandingDto) HasHero() bool`

HasHero returns a boolean if a field has been set.

### GetFeatures

`func (o *AppStorefrontLandingDto) GetFeatures() []AppStorefrontFeatureBlockDto`

GetFeatures returns the Features field if non-nil, zero value otherwise.

### GetFeaturesOk

`func (o *AppStorefrontLandingDto) GetFeaturesOk() (*[]AppStorefrontFeatureBlockDto, bool)`

GetFeaturesOk returns a tuple with the Features field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatures

`func (o *AppStorefrontLandingDto) SetFeatures(v []AppStorefrontFeatureBlockDto)`

SetFeatures sets Features field to given value.

### HasFeatures

`func (o *AppStorefrontLandingDto) HasFeatures() bool`

HasFeatures returns a boolean if a field has been set.

### SetFeaturesNil

`func (o *AppStorefrontLandingDto) SetFeaturesNil(b bool)`

 SetFeaturesNil sets the value for Features to be an explicit nil

### UnsetFeatures
`func (o *AppStorefrontLandingDto) UnsetFeatures()`

UnsetFeatures ensures that no value is present for Features, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


