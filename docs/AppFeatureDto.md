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
**Name** | Pointer to **NullableString** |  | [optional] 
**DisplayName** | Pointer to **NullableString** |  | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**Details** | Pointer to **NullableString** |  | [optional] 
**ScreenshotKeys** | Pointer to **NullableString** |  | [optional] 

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
### GetDisplayName

`func (o *AppFeatureDto) GetDisplayName() string`

GetDisplayName returns the DisplayName field if non-nil, zero value otherwise.

### GetDisplayNameOk

`func (o *AppFeatureDto) GetDisplayNameOk() (*string, bool)`

GetDisplayNameOk returns a tuple with the DisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayName

`func (o *AppFeatureDto) SetDisplayName(v string)`

SetDisplayName sets DisplayName field to given value.

### HasDisplayName

`func (o *AppFeatureDto) HasDisplayName() bool`

HasDisplayName returns a boolean if a field has been set.

### SetDisplayNameNil

`func (o *AppFeatureDto) SetDisplayNameNil(b bool)`

 SetDisplayNameNil sets the value for DisplayName to be an explicit nil

### UnsetDisplayName
`func (o *AppFeatureDto) UnsetDisplayName()`

UnsetDisplayName ensures that no value is present for DisplayName, not even an explicit nil
### GetDescription

`func (o *AppFeatureDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *AppFeatureDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *AppFeatureDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *AppFeatureDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *AppFeatureDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *AppFeatureDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetDetails

`func (o *AppFeatureDto) GetDetails() string`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *AppFeatureDto) GetDetailsOk() (*string, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *AppFeatureDto) SetDetails(v string)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *AppFeatureDto) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### SetDetailsNil

`func (o *AppFeatureDto) SetDetailsNil(b bool)`

 SetDetailsNil sets the value for Details to be an explicit nil

### UnsetDetails
`func (o *AppFeatureDto) UnsetDetails()`

UnsetDetails ensures that no value is present for Details, not even an explicit nil
### GetScreenshotKeys

`func (o *AppFeatureDto) GetScreenshotKeys() string`

GetScreenshotKeys returns the ScreenshotKeys field if non-nil, zero value otherwise.

### GetScreenshotKeysOk

`func (o *AppFeatureDto) GetScreenshotKeysOk() (*string, bool)`

GetScreenshotKeysOk returns a tuple with the ScreenshotKeys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScreenshotKeys

`func (o *AppFeatureDto) SetScreenshotKeys(v string)`

SetScreenshotKeys sets ScreenshotKeys field to given value.

### HasScreenshotKeys

`func (o *AppFeatureDto) HasScreenshotKeys() bool`

HasScreenshotKeys returns a boolean if a field has been set.

### SetScreenshotKeysNil

`func (o *AppFeatureDto) SetScreenshotKeysNil(b bool)`

 SetScreenshotKeysNil sets the value for ScreenshotKeys to be an explicit nil

### UnsetScreenshotKeys
`func (o *AppFeatureDto) UnsetScreenshotKeys()`

UnsetScreenshotKeys ensures that no value is present for ScreenshotKeys, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


