# ApplicationAuthConfigurationDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GrantedPolicies** | Pointer to **map[string]bool** |  | [optional] 

## Methods

### NewApplicationAuthConfigurationDto

`func NewApplicationAuthConfigurationDto() *ApplicationAuthConfigurationDto`

NewApplicationAuthConfigurationDto instantiates a new ApplicationAuthConfigurationDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApplicationAuthConfigurationDtoWithDefaults

`func NewApplicationAuthConfigurationDtoWithDefaults() *ApplicationAuthConfigurationDto`

NewApplicationAuthConfigurationDtoWithDefaults instantiates a new ApplicationAuthConfigurationDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGrantedPolicies

`func (o *ApplicationAuthConfigurationDto) GetGrantedPolicies() map[string]bool`

GetGrantedPolicies returns the GrantedPolicies field if non-nil, zero value otherwise.

### GetGrantedPoliciesOk

`func (o *ApplicationAuthConfigurationDto) GetGrantedPoliciesOk() (*map[string]bool, bool)`

GetGrantedPoliciesOk returns a tuple with the GrantedPolicies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrantedPolicies

`func (o *ApplicationAuthConfigurationDto) SetGrantedPolicies(v map[string]bool)`

SetGrantedPolicies sets GrantedPolicies field to given value.

### HasGrantedPolicies

`func (o *ApplicationAuthConfigurationDto) HasGrantedPolicies() bool`

HasGrantedPolicies returns a boolean if a field has been set.

### SetGrantedPoliciesNil

`func (o *ApplicationAuthConfigurationDto) SetGrantedPoliciesNil(b bool)`

 SetGrantedPoliciesNil sets the value for GrantedPolicies to be an explicit nil

### UnsetGrantedPolicies
`func (o *ApplicationAuthConfigurationDto) UnsetGrantedPolicies()`

UnsetGrantedPolicies ensures that no value is present for GrantedPolicies, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


