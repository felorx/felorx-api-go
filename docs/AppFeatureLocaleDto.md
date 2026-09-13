# AppFeatureLocaleDto

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
**AppFeatureId** | Pointer to **string** |  | [optional] 
**AppLocaleId** | Pointer to **string** |  | [optional] 
**LangCode** | Pointer to **NullableString** | 冗余：方便客户端展示，取自关联的 AppLocale。 | [optional] 
**DisplayName** | Pointer to **NullableString** |  | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**Details** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewAppFeatureLocaleDto

`func NewAppFeatureLocaleDto() *AppFeatureLocaleDto`

NewAppFeatureLocaleDto instantiates a new AppFeatureLocaleDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAppFeatureLocaleDtoWithDefaults

`func NewAppFeatureLocaleDtoWithDefaults() *AppFeatureLocaleDto`

NewAppFeatureLocaleDtoWithDefaults instantiates a new AppFeatureLocaleDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AppFeatureLocaleDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AppFeatureLocaleDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AppFeatureLocaleDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AppFeatureLocaleDto) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreationTime

`func (o *AppFeatureLocaleDto) GetCreationTime() time.Time`

GetCreationTime returns the CreationTime field if non-nil, zero value otherwise.

### GetCreationTimeOk

`func (o *AppFeatureLocaleDto) GetCreationTimeOk() (*time.Time, bool)`

GetCreationTimeOk returns a tuple with the CreationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreationTime

`func (o *AppFeatureLocaleDto) SetCreationTime(v time.Time)`

SetCreationTime sets CreationTime field to given value.

### HasCreationTime

`func (o *AppFeatureLocaleDto) HasCreationTime() bool`

HasCreationTime returns a boolean if a field has been set.

### GetCreatorId

`func (o *AppFeatureLocaleDto) GetCreatorId() string`

GetCreatorId returns the CreatorId field if non-nil, zero value otherwise.

### GetCreatorIdOk

`func (o *AppFeatureLocaleDto) GetCreatorIdOk() (*string, bool)`

GetCreatorIdOk returns a tuple with the CreatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatorId

`func (o *AppFeatureLocaleDto) SetCreatorId(v string)`

SetCreatorId sets CreatorId field to given value.

### HasCreatorId

`func (o *AppFeatureLocaleDto) HasCreatorId() bool`

HasCreatorId returns a boolean if a field has been set.

### SetCreatorIdNil

`func (o *AppFeatureLocaleDto) SetCreatorIdNil(b bool)`

 SetCreatorIdNil sets the value for CreatorId to be an explicit nil

### UnsetCreatorId
`func (o *AppFeatureLocaleDto) UnsetCreatorId()`

UnsetCreatorId ensures that no value is present for CreatorId, not even an explicit nil
### GetLastModificationTime

`func (o *AppFeatureLocaleDto) GetLastModificationTime() time.Time`

GetLastModificationTime returns the LastModificationTime field if non-nil, zero value otherwise.

### GetLastModificationTimeOk

`func (o *AppFeatureLocaleDto) GetLastModificationTimeOk() (*time.Time, bool)`

GetLastModificationTimeOk returns a tuple with the LastModificationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModificationTime

`func (o *AppFeatureLocaleDto) SetLastModificationTime(v time.Time)`

SetLastModificationTime sets LastModificationTime field to given value.

### HasLastModificationTime

`func (o *AppFeatureLocaleDto) HasLastModificationTime() bool`

HasLastModificationTime returns a boolean if a field has been set.

### SetLastModificationTimeNil

`func (o *AppFeatureLocaleDto) SetLastModificationTimeNil(b bool)`

 SetLastModificationTimeNil sets the value for LastModificationTime to be an explicit nil

### UnsetLastModificationTime
`func (o *AppFeatureLocaleDto) UnsetLastModificationTime()`

UnsetLastModificationTime ensures that no value is present for LastModificationTime, not even an explicit nil
### GetLastModifierId

`func (o *AppFeatureLocaleDto) GetLastModifierId() string`

GetLastModifierId returns the LastModifierId field if non-nil, zero value otherwise.

### GetLastModifierIdOk

`func (o *AppFeatureLocaleDto) GetLastModifierIdOk() (*string, bool)`

GetLastModifierIdOk returns a tuple with the LastModifierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModifierId

`func (o *AppFeatureLocaleDto) SetLastModifierId(v string)`

SetLastModifierId sets LastModifierId field to given value.

### HasLastModifierId

`func (o *AppFeatureLocaleDto) HasLastModifierId() bool`

HasLastModifierId returns a boolean if a field has been set.

### SetLastModifierIdNil

`func (o *AppFeatureLocaleDto) SetLastModifierIdNil(b bool)`

 SetLastModifierIdNil sets the value for LastModifierId to be an explicit nil

### UnsetLastModifierId
`func (o *AppFeatureLocaleDto) UnsetLastModifierId()`

UnsetLastModifierId ensures that no value is present for LastModifierId, not even an explicit nil
### GetIsDeleted

`func (o *AppFeatureLocaleDto) GetIsDeleted() bool`

GetIsDeleted returns the IsDeleted field if non-nil, zero value otherwise.

### GetIsDeletedOk

`func (o *AppFeatureLocaleDto) GetIsDeletedOk() (*bool, bool)`

GetIsDeletedOk returns a tuple with the IsDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDeleted

`func (o *AppFeatureLocaleDto) SetIsDeleted(v bool)`

SetIsDeleted sets IsDeleted field to given value.

### HasIsDeleted

`func (o *AppFeatureLocaleDto) HasIsDeleted() bool`

HasIsDeleted returns a boolean if a field has been set.

### GetDeleterId

`func (o *AppFeatureLocaleDto) GetDeleterId() string`

GetDeleterId returns the DeleterId field if non-nil, zero value otherwise.

### GetDeleterIdOk

`func (o *AppFeatureLocaleDto) GetDeleterIdOk() (*string, bool)`

GetDeleterIdOk returns a tuple with the DeleterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleterId

`func (o *AppFeatureLocaleDto) SetDeleterId(v string)`

SetDeleterId sets DeleterId field to given value.

### HasDeleterId

`func (o *AppFeatureLocaleDto) HasDeleterId() bool`

HasDeleterId returns a boolean if a field has been set.

### SetDeleterIdNil

`func (o *AppFeatureLocaleDto) SetDeleterIdNil(b bool)`

 SetDeleterIdNil sets the value for DeleterId to be an explicit nil

### UnsetDeleterId
`func (o *AppFeatureLocaleDto) UnsetDeleterId()`

UnsetDeleterId ensures that no value is present for DeleterId, not even an explicit nil
### GetDeletionTime

`func (o *AppFeatureLocaleDto) GetDeletionTime() time.Time`

GetDeletionTime returns the DeletionTime field if non-nil, zero value otherwise.

### GetDeletionTimeOk

`func (o *AppFeatureLocaleDto) GetDeletionTimeOk() (*time.Time, bool)`

GetDeletionTimeOk returns a tuple with the DeletionTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletionTime

`func (o *AppFeatureLocaleDto) SetDeletionTime(v time.Time)`

SetDeletionTime sets DeletionTime field to given value.

### HasDeletionTime

`func (o *AppFeatureLocaleDto) HasDeletionTime() bool`

HasDeletionTime returns a boolean if a field has been set.

### SetDeletionTimeNil

`func (o *AppFeatureLocaleDto) SetDeletionTimeNil(b bool)`

 SetDeletionTimeNil sets the value for DeletionTime to be an explicit nil

### UnsetDeletionTime
`func (o *AppFeatureLocaleDto) UnsetDeletionTime()`

UnsetDeletionTime ensures that no value is present for DeletionTime, not even an explicit nil
### GetAppFeatureId

`func (o *AppFeatureLocaleDto) GetAppFeatureId() string`

GetAppFeatureId returns the AppFeatureId field if non-nil, zero value otherwise.

### GetAppFeatureIdOk

`func (o *AppFeatureLocaleDto) GetAppFeatureIdOk() (*string, bool)`

GetAppFeatureIdOk returns a tuple with the AppFeatureId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppFeatureId

`func (o *AppFeatureLocaleDto) SetAppFeatureId(v string)`

SetAppFeatureId sets AppFeatureId field to given value.

### HasAppFeatureId

`func (o *AppFeatureLocaleDto) HasAppFeatureId() bool`

HasAppFeatureId returns a boolean if a field has been set.

### GetAppLocaleId

`func (o *AppFeatureLocaleDto) GetAppLocaleId() string`

GetAppLocaleId returns the AppLocaleId field if non-nil, zero value otherwise.

### GetAppLocaleIdOk

`func (o *AppFeatureLocaleDto) GetAppLocaleIdOk() (*string, bool)`

GetAppLocaleIdOk returns a tuple with the AppLocaleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppLocaleId

`func (o *AppFeatureLocaleDto) SetAppLocaleId(v string)`

SetAppLocaleId sets AppLocaleId field to given value.

### HasAppLocaleId

`func (o *AppFeatureLocaleDto) HasAppLocaleId() bool`

HasAppLocaleId returns a boolean if a field has been set.

### GetLangCode

`func (o *AppFeatureLocaleDto) GetLangCode() string`

GetLangCode returns the LangCode field if non-nil, zero value otherwise.

### GetLangCodeOk

`func (o *AppFeatureLocaleDto) GetLangCodeOk() (*string, bool)`

GetLangCodeOk returns a tuple with the LangCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLangCode

`func (o *AppFeatureLocaleDto) SetLangCode(v string)`

SetLangCode sets LangCode field to given value.

### HasLangCode

`func (o *AppFeatureLocaleDto) HasLangCode() bool`

HasLangCode returns a boolean if a field has been set.

### SetLangCodeNil

`func (o *AppFeatureLocaleDto) SetLangCodeNil(b bool)`

 SetLangCodeNil sets the value for LangCode to be an explicit nil

### UnsetLangCode
`func (o *AppFeatureLocaleDto) UnsetLangCode()`

UnsetLangCode ensures that no value is present for LangCode, not even an explicit nil
### GetDisplayName

`func (o *AppFeatureLocaleDto) GetDisplayName() string`

GetDisplayName returns the DisplayName field if non-nil, zero value otherwise.

### GetDisplayNameOk

`func (o *AppFeatureLocaleDto) GetDisplayNameOk() (*string, bool)`

GetDisplayNameOk returns a tuple with the DisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayName

`func (o *AppFeatureLocaleDto) SetDisplayName(v string)`

SetDisplayName sets DisplayName field to given value.

### HasDisplayName

`func (o *AppFeatureLocaleDto) HasDisplayName() bool`

HasDisplayName returns a boolean if a field has been set.

### SetDisplayNameNil

`func (o *AppFeatureLocaleDto) SetDisplayNameNil(b bool)`

 SetDisplayNameNil sets the value for DisplayName to be an explicit nil

### UnsetDisplayName
`func (o *AppFeatureLocaleDto) UnsetDisplayName()`

UnsetDisplayName ensures that no value is present for DisplayName, not even an explicit nil
### GetDescription

`func (o *AppFeatureLocaleDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *AppFeatureLocaleDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *AppFeatureLocaleDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *AppFeatureLocaleDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *AppFeatureLocaleDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *AppFeatureLocaleDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetDetails

`func (o *AppFeatureLocaleDto) GetDetails() string`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *AppFeatureLocaleDto) GetDetailsOk() (*string, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *AppFeatureLocaleDto) SetDetails(v string)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *AppFeatureLocaleDto) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### SetDetailsNil

`func (o *AppFeatureLocaleDto) SetDetailsNil(b bool)`

 SetDetailsNil sets the value for Details to be an explicit nil

### UnsetDetails
`func (o *AppFeatureLocaleDto) UnsetDetails()`

UnsetDetails ensures that no value is present for Details, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


