# AppFeatureDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional]
**CreationTime** | Pointer to **time.Time** |  | [optional]
**CreatorId** | Pointer to **NullableString** |  | [optional]
**LastModificationTime** | Pointer to **NullableTime** |  | [optional]
**LastModifierId** | Pointer to **NullableString** |  | [optional]
**IsDeleted** | Pointer to **bool** |  | [optional]
**DeleterId** | Pointer to **NullableString** |  | [optional]
**DeletionTime** | Pointer to **NullableTime** |  | [optional]
**AppId** | Pointer to **string** | 所属应用ID | [optional]
**Name** | Pointer to **NullableString** | 功能名称（唯一标识，同一应用内唯一） | [optional]
**Sort** | Pointer to **int32** |  | [optional]
**FeatureLocales** | Pointer to [**[]AppFeatureLocaleDto**](AppFeatureLocaleDto.md) |  | [optional]

## Methods

### NewAppFeatureDto

`func NewAppFeatureDto() *AppFeatureDto`

NewAppFeatureDto instantiates a new AppFeatureDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAppFeatureDtoWithDefaults

`func NewAppFeatureDtoWithDefaults() *AppFeatureDto`

NewAppFeatureDtoWithDefaults instantiates a new AppFeatureDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AppFeatureDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AppFeatureDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AppFeatureDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AppFeatureDto) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreationTime

`func (o *AppFeatureDto) GetCreationTime() time.Time`

GetCreationTime returns the CreationTime field if non-nil, zero value otherwise.

### GetCreationTimeOk

`func (o *AppFeatureDto) GetCreationTimeOk() (*time.Time, bool)`

GetCreationTimeOk returns a tuple with the CreationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreationTime

`func (o *AppFeatureDto) SetCreationTime(v time.Time)`

SetCreationTime sets CreationTime field to given value.

### HasCreationTime

`func (o *AppFeatureDto) HasCreationTime() bool`

HasCreationTime returns a boolean if a field has been set.

### GetCreatorId

`func (o *AppFeatureDto) GetCreatorId() string`

GetCreatorId returns the CreatorId field if non-nil, zero value otherwise.

### GetCreatorIdOk

`func (o *AppFeatureDto) GetCreatorIdOk() (*string, bool)`

GetCreatorIdOk returns a tuple with the CreatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatorId

`func (o *AppFeatureDto) SetCreatorId(v string)`

SetCreatorId sets CreatorId field to given value.

### HasCreatorId

`func (o *AppFeatureDto) HasCreatorId() bool`

HasCreatorId returns a boolean if a field has been set.

### SetCreatorIdNil

`func (o *AppFeatureDto) SetCreatorIdNil(b bool)`

 SetCreatorIdNil sets the value for CreatorId to be an explicit nil

### UnsetCreatorId
`func (o *AppFeatureDto) UnsetCreatorId()`

UnsetCreatorId ensures that no value is present for CreatorId, not even an explicit nil
### GetLastModificationTime

`func (o *AppFeatureDto) GetLastModificationTime() time.Time`

GetLastModificationTime returns the LastModificationTime field if non-nil, zero value otherwise.

### GetLastModificationTimeOk

`func (o *AppFeatureDto) GetLastModificationTimeOk() (*time.Time, bool)`

GetLastModificationTimeOk returns a tuple with the LastModificationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModificationTime

`func (o *AppFeatureDto) SetLastModificationTime(v time.Time)`

SetLastModificationTime sets LastModificationTime field to given value.

### HasLastModificationTime

`func (o *AppFeatureDto) HasLastModificationTime() bool`

HasLastModificationTime returns a boolean if a field has been set.

### SetLastModificationTimeNil

`func (o *AppFeatureDto) SetLastModificationTimeNil(b bool)`

 SetLastModificationTimeNil sets the value for LastModificationTime to be an explicit nil

### UnsetLastModificationTime
`func (o *AppFeatureDto) UnsetLastModificationTime()`

UnsetLastModificationTime ensures that no value is present for LastModificationTime, not even an explicit nil
### GetLastModifierId

`func (o *AppFeatureDto) GetLastModifierId() string`

GetLastModifierId returns the LastModifierId field if non-nil, zero value otherwise.

### GetLastModifierIdOk

`func (o *AppFeatureDto) GetLastModifierIdOk() (*string, bool)`

GetLastModifierIdOk returns a tuple with the LastModifierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModifierId

`func (o *AppFeatureDto) SetLastModifierId(v string)`

SetLastModifierId sets LastModifierId field to given value.

### HasLastModifierId

`func (o *AppFeatureDto) HasLastModifierId() bool`

HasLastModifierId returns a boolean if a field has been set.

### SetLastModifierIdNil

`func (o *AppFeatureDto) SetLastModifierIdNil(b bool)`

 SetLastModifierIdNil sets the value for LastModifierId to be an explicit nil

### UnsetLastModifierId
`func (o *AppFeatureDto) UnsetLastModifierId()`

UnsetLastModifierId ensures that no value is present for LastModifierId, not even an explicit nil
### GetIsDeleted

`func (o *AppFeatureDto) GetIsDeleted() bool`

GetIsDeleted returns the IsDeleted field if non-nil, zero value otherwise.

### GetIsDeletedOk

`func (o *AppFeatureDto) GetIsDeletedOk() (*bool, bool)`

GetIsDeletedOk returns a tuple with the IsDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDeleted

`func (o *AppFeatureDto) SetIsDeleted(v bool)`

SetIsDeleted sets IsDeleted field to given value.

### HasIsDeleted

`func (o *AppFeatureDto) HasIsDeleted() bool`

HasIsDeleted returns a boolean if a field has been set.

### GetDeleterId

`func (o *AppFeatureDto) GetDeleterId() string`

GetDeleterId returns the DeleterId field if non-nil, zero value otherwise.

### GetDeleterIdOk

`func (o *AppFeatureDto) GetDeleterIdOk() (*string, bool)`

GetDeleterIdOk returns a tuple with the DeleterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleterId

`func (o *AppFeatureDto) SetDeleterId(v string)`

SetDeleterId sets DeleterId field to given value.

### HasDeleterId

`func (o *AppFeatureDto) HasDeleterId() bool`

HasDeleterId returns a boolean if a field has been set.

### SetDeleterIdNil

`func (o *AppFeatureDto) SetDeleterIdNil(b bool)`

 SetDeleterIdNil sets the value for DeleterId to be an explicit nil

### UnsetDeleterId
`func (o *AppFeatureDto) UnsetDeleterId()`

UnsetDeleterId ensures that no value is present for DeleterId, not even an explicit nil
### GetDeletionTime

`func (o *AppFeatureDto) GetDeletionTime() time.Time`

GetDeletionTime returns the DeletionTime field if non-nil, zero value otherwise.

### GetDeletionTimeOk

`func (o *AppFeatureDto) GetDeletionTimeOk() (*time.Time, bool)`

GetDeletionTimeOk returns a tuple with the DeletionTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletionTime

`func (o *AppFeatureDto) SetDeletionTime(v time.Time)`

SetDeletionTime sets DeletionTime field to given value.

### HasDeletionTime

`func (o *AppFeatureDto) HasDeletionTime() bool`

HasDeletionTime returns a boolean if a field has been set.

### SetDeletionTimeNil

`func (o *AppFeatureDto) SetDeletionTimeNil(b bool)`

 SetDeletionTimeNil sets the value for DeletionTime to be an explicit nil

### UnsetDeletionTime
`func (o *AppFeatureDto) UnsetDeletionTime()`

UnsetDeletionTime ensures that no value is present for DeletionTime, not even an explicit nil
### GetAppId

`func (o *AppFeatureDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *AppFeatureDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *AppFeatureDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *AppFeatureDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetName

`func (o *AppFeatureDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AppFeatureDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AppFeatureDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *AppFeatureDto) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *AppFeatureDto) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *AppFeatureDto) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetSort

`func (o *AppFeatureDto) GetSort() int32`

GetSort returns the Sort field if non-nil, zero value otherwise.

### GetSortOk

`func (o *AppFeatureDto) GetSortOk() (*int32, bool)`

GetSortOk returns a tuple with the Sort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSort

`func (o *AppFeatureDto) SetSort(v int32)`

SetSort sets Sort field to given value.

### HasSort

`func (o *AppFeatureDto) HasSort() bool`

HasSort returns a boolean if a field has been set.

### GetFeatureLocales

`func (o *AppFeatureDto) GetFeatureLocales() []AppFeatureLocaleDto`

GetFeatureLocales returns the FeatureLocales field if non-nil, zero value otherwise.

### GetFeatureLocalesOk

`func (o *AppFeatureDto) GetFeatureLocalesOk() (*[]AppFeatureLocaleDto, bool)`

GetFeatureLocalesOk returns a tuple with the FeatureLocales field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatureLocales

`func (o *AppFeatureDto) SetFeatureLocales(v []AppFeatureLocaleDto)`

SetFeatureLocales sets FeatureLocales field to given value.

### HasFeatureLocales

`func (o *AppFeatureDto) HasFeatureLocales() bool`

HasFeatureLocales returns a boolean if a field has been set.

### SetFeatureLocalesNil

`func (o *AppFeatureDto) SetFeatureLocalesNil(b bool)`

 SetFeatureLocalesNil sets the value for FeatureLocales to be an explicit nil

### UnsetFeatureLocales
`func (o *AppFeatureDto) UnsetFeatureLocales()`

UnsetFeatureLocales ensures that no value is present for FeatureLocales, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


