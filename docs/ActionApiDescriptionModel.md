# ActionApiDescriptionModel

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UniqueName** | Pointer to **NullableString** |  | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 
**HttpMethod** | Pointer to **NullableString** |  | [optional] 
**Url** | Pointer to **NullableString** |  | [optional] 
**SupportedVersions** | Pointer to **[]string** |  | [optional] 
**ParametersOnMethod** | Pointer to [**[]MethodParameterApiDescriptionModel**](MethodParameterApiDescriptionModel.md) |  | [optional] 
**Parameters** | Pointer to [**[]ParameterApiDescriptionModel**](ParameterApiDescriptionModel.md) |  | [optional] 
**ReturnValue** | Pointer to [**ReturnValueApiDescriptionModel**](ReturnValueApiDescriptionModel.md) |  | [optional] 
**AllowAnonymous** | Pointer to **NullableBool** |  | [optional] 
**ImplementFrom** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewActionApiDescriptionModel

`func NewActionApiDescriptionModel() *ActionApiDescriptionModel`

NewActionApiDescriptionModel instantiates a new ActionApiDescriptionModel object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewActionApiDescriptionModelWithDefaults

`func NewActionApiDescriptionModelWithDefaults() *ActionApiDescriptionModel`

NewActionApiDescriptionModelWithDefaults instantiates a new ActionApiDescriptionModel object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUniqueName

`func (o *ActionApiDescriptionModel) GetUniqueName() string`

GetUniqueName returns the UniqueName field if non-nil, zero value otherwise.

### GetUniqueNameOk

`func (o *ActionApiDescriptionModel) GetUniqueNameOk() (*string, bool)`

GetUniqueNameOk returns a tuple with the UniqueName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUniqueName

`func (o *ActionApiDescriptionModel) SetUniqueName(v string)`

SetUniqueName sets UniqueName field to given value.

### HasUniqueName

`func (o *ActionApiDescriptionModel) HasUniqueName() bool`

HasUniqueName returns a boolean if a field has been set.

### SetUniqueNameNil

`func (o *ActionApiDescriptionModel) SetUniqueNameNil(b bool)`

 SetUniqueNameNil sets the value for UniqueName to be an explicit nil

### UnsetUniqueName
`func (o *ActionApiDescriptionModel) UnsetUniqueName()`

UnsetUniqueName ensures that no value is present for UniqueName, not even an explicit nil
### GetName

`func (o *ActionApiDescriptionModel) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ActionApiDescriptionModel) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ActionApiDescriptionModel) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ActionApiDescriptionModel) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *ActionApiDescriptionModel) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *ActionApiDescriptionModel) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetHttpMethod

`func (o *ActionApiDescriptionModel) GetHttpMethod() string`

GetHttpMethod returns the HttpMethod field if non-nil, zero value otherwise.

### GetHttpMethodOk

`func (o *ActionApiDescriptionModel) GetHttpMethodOk() (*string, bool)`

GetHttpMethodOk returns a tuple with the HttpMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHttpMethod

`func (o *ActionApiDescriptionModel) SetHttpMethod(v string)`

SetHttpMethod sets HttpMethod field to given value.

### HasHttpMethod

`func (o *ActionApiDescriptionModel) HasHttpMethod() bool`

HasHttpMethod returns a boolean if a field has been set.

### SetHttpMethodNil

`func (o *ActionApiDescriptionModel) SetHttpMethodNil(b bool)`

 SetHttpMethodNil sets the value for HttpMethod to be an explicit nil

### UnsetHttpMethod
`func (o *ActionApiDescriptionModel) UnsetHttpMethod()`

UnsetHttpMethod ensures that no value is present for HttpMethod, not even an explicit nil
### GetUrl

`func (o *ActionApiDescriptionModel) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *ActionApiDescriptionModel) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *ActionApiDescriptionModel) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *ActionApiDescriptionModel) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### SetUrlNil

`func (o *ActionApiDescriptionModel) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *ActionApiDescriptionModel) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil
### GetSupportedVersions

`func (o *ActionApiDescriptionModel) GetSupportedVersions() []string`

GetSupportedVersions returns the SupportedVersions field if non-nil, zero value otherwise.

### GetSupportedVersionsOk

`func (o *ActionApiDescriptionModel) GetSupportedVersionsOk() (*[]string, bool)`

GetSupportedVersionsOk returns a tuple with the SupportedVersions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportedVersions

`func (o *ActionApiDescriptionModel) SetSupportedVersions(v []string)`

SetSupportedVersions sets SupportedVersions field to given value.

### HasSupportedVersions

`func (o *ActionApiDescriptionModel) HasSupportedVersions() bool`

HasSupportedVersions returns a boolean if a field has been set.

### SetSupportedVersionsNil

`func (o *ActionApiDescriptionModel) SetSupportedVersionsNil(b bool)`

 SetSupportedVersionsNil sets the value for SupportedVersions to be an explicit nil

### UnsetSupportedVersions
`func (o *ActionApiDescriptionModel) UnsetSupportedVersions()`

UnsetSupportedVersions ensures that no value is present for SupportedVersions, not even an explicit nil
### GetParametersOnMethod

`func (o *ActionApiDescriptionModel) GetParametersOnMethod() []MethodParameterApiDescriptionModel`

GetParametersOnMethod returns the ParametersOnMethod field if non-nil, zero value otherwise.

### GetParametersOnMethodOk

`func (o *ActionApiDescriptionModel) GetParametersOnMethodOk() (*[]MethodParameterApiDescriptionModel, bool)`

GetParametersOnMethodOk returns a tuple with the ParametersOnMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParametersOnMethod

`func (o *ActionApiDescriptionModel) SetParametersOnMethod(v []MethodParameterApiDescriptionModel)`

SetParametersOnMethod sets ParametersOnMethod field to given value.

### HasParametersOnMethod

`func (o *ActionApiDescriptionModel) HasParametersOnMethod() bool`

HasParametersOnMethod returns a boolean if a field has been set.

### SetParametersOnMethodNil

`func (o *ActionApiDescriptionModel) SetParametersOnMethodNil(b bool)`

 SetParametersOnMethodNil sets the value for ParametersOnMethod to be an explicit nil

### UnsetParametersOnMethod
`func (o *ActionApiDescriptionModel) UnsetParametersOnMethod()`

UnsetParametersOnMethod ensures that no value is present for ParametersOnMethod, not even an explicit nil
### GetParameters

`func (o *ActionApiDescriptionModel) GetParameters() []ParameterApiDescriptionModel`

GetParameters returns the Parameters field if non-nil, zero value otherwise.

### GetParametersOk

`func (o *ActionApiDescriptionModel) GetParametersOk() (*[]ParameterApiDescriptionModel, bool)`

GetParametersOk returns a tuple with the Parameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParameters

`func (o *ActionApiDescriptionModel) SetParameters(v []ParameterApiDescriptionModel)`

SetParameters sets Parameters field to given value.

### HasParameters

`func (o *ActionApiDescriptionModel) HasParameters() bool`

HasParameters returns a boolean if a field has been set.

### SetParametersNil

`func (o *ActionApiDescriptionModel) SetParametersNil(b bool)`

 SetParametersNil sets the value for Parameters to be an explicit nil

### UnsetParameters
`func (o *ActionApiDescriptionModel) UnsetParameters()`

UnsetParameters ensures that no value is present for Parameters, not even an explicit nil
### GetReturnValue

`func (o *ActionApiDescriptionModel) GetReturnValue() ReturnValueApiDescriptionModel`

GetReturnValue returns the ReturnValue field if non-nil, zero value otherwise.

### GetReturnValueOk

`func (o *ActionApiDescriptionModel) GetReturnValueOk() (*ReturnValueApiDescriptionModel, bool)`

GetReturnValueOk returns a tuple with the ReturnValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnValue

`func (o *ActionApiDescriptionModel) SetReturnValue(v ReturnValueApiDescriptionModel)`

SetReturnValue sets ReturnValue field to given value.

### HasReturnValue

`func (o *ActionApiDescriptionModel) HasReturnValue() bool`

HasReturnValue returns a boolean if a field has been set.

### GetAllowAnonymous

`func (o *ActionApiDescriptionModel) GetAllowAnonymous() bool`

GetAllowAnonymous returns the AllowAnonymous field if non-nil, zero value otherwise.

### GetAllowAnonymousOk

`func (o *ActionApiDescriptionModel) GetAllowAnonymousOk() (*bool, bool)`

GetAllowAnonymousOk returns a tuple with the AllowAnonymous field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowAnonymous

`func (o *ActionApiDescriptionModel) SetAllowAnonymous(v bool)`

SetAllowAnonymous sets AllowAnonymous field to given value.

### HasAllowAnonymous

`func (o *ActionApiDescriptionModel) HasAllowAnonymous() bool`

HasAllowAnonymous returns a boolean if a field has been set.

### SetAllowAnonymousNil

`func (o *ActionApiDescriptionModel) SetAllowAnonymousNil(b bool)`

 SetAllowAnonymousNil sets the value for AllowAnonymous to be an explicit nil

### UnsetAllowAnonymous
`func (o *ActionApiDescriptionModel) UnsetAllowAnonymous()`

UnsetAllowAnonymous ensures that no value is present for AllowAnonymous, not even an explicit nil
### GetImplementFrom

`func (o *ActionApiDescriptionModel) GetImplementFrom() string`

GetImplementFrom returns the ImplementFrom field if non-nil, zero value otherwise.

### GetImplementFromOk

`func (o *ActionApiDescriptionModel) GetImplementFromOk() (*string, bool)`

GetImplementFromOk returns a tuple with the ImplementFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImplementFrom

`func (o *ActionApiDescriptionModel) SetImplementFrom(v string)`

SetImplementFrom sets ImplementFrom field to given value.

### HasImplementFrom

`func (o *ActionApiDescriptionModel) HasImplementFrom() bool`

HasImplementFrom returns a boolean if a field has been set.

### SetImplementFromNil

`func (o *ActionApiDescriptionModel) SetImplementFromNil(b bool)`

 SetImplementFromNil sets the value for ImplementFrom to be an explicit nil

### UnsetImplementFrom
`func (o *ActionApiDescriptionModel) UnsetImplementFrom()`

UnsetImplementFrom ensures that no value is present for ImplementFrom, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


