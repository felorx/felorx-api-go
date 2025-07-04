# MessageTemplateDto

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
**Description** | Pointer to **NullableString** |  | [optional] 
**LatestVersion** | Pointer to **int32** |  | [optional] 

## Methods

### NewMessageTemplateDto

`func NewMessageTemplateDto() *MessageTemplateDto`

NewMessageTemplateDto instantiates a new MessageTemplateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMessageTemplateDtoWithDefaults

`func NewMessageTemplateDtoWithDefaults() *MessageTemplateDto`

NewMessageTemplateDtoWithDefaults instantiates a new MessageTemplateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *MessageTemplateDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *MessageTemplateDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *MessageTemplateDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *MessageTemplateDto) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreationTime

`func (o *MessageTemplateDto) GetCreationTime() time.Time`

GetCreationTime returns the CreationTime field if non-nil, zero value otherwise.

### GetCreationTimeOk

`func (o *MessageTemplateDto) GetCreationTimeOk() (*time.Time, bool)`

GetCreationTimeOk returns a tuple with the CreationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreationTime

`func (o *MessageTemplateDto) SetCreationTime(v time.Time)`

SetCreationTime sets CreationTime field to given value.

### HasCreationTime

`func (o *MessageTemplateDto) HasCreationTime() bool`

HasCreationTime returns a boolean if a field has been set.

### GetCreatorId

`func (o *MessageTemplateDto) GetCreatorId() string`

GetCreatorId returns the CreatorId field if non-nil, zero value otherwise.

### GetCreatorIdOk

`func (o *MessageTemplateDto) GetCreatorIdOk() (*string, bool)`

GetCreatorIdOk returns a tuple with the CreatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatorId

`func (o *MessageTemplateDto) SetCreatorId(v string)`

SetCreatorId sets CreatorId field to given value.

### HasCreatorId

`func (o *MessageTemplateDto) HasCreatorId() bool`

HasCreatorId returns a boolean if a field has been set.

### SetCreatorIdNil

`func (o *MessageTemplateDto) SetCreatorIdNil(b bool)`

 SetCreatorIdNil sets the value for CreatorId to be an explicit nil

### UnsetCreatorId
`func (o *MessageTemplateDto) UnsetCreatorId()`

UnsetCreatorId ensures that no value is present for CreatorId, not even an explicit nil
### GetLastModificationTime

`func (o *MessageTemplateDto) GetLastModificationTime() time.Time`

GetLastModificationTime returns the LastModificationTime field if non-nil, zero value otherwise.

### GetLastModificationTimeOk

`func (o *MessageTemplateDto) GetLastModificationTimeOk() (*time.Time, bool)`

GetLastModificationTimeOk returns a tuple with the LastModificationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModificationTime

`func (o *MessageTemplateDto) SetLastModificationTime(v time.Time)`

SetLastModificationTime sets LastModificationTime field to given value.

### HasLastModificationTime

`func (o *MessageTemplateDto) HasLastModificationTime() bool`

HasLastModificationTime returns a boolean if a field has been set.

### SetLastModificationTimeNil

`func (o *MessageTemplateDto) SetLastModificationTimeNil(b bool)`

 SetLastModificationTimeNil sets the value for LastModificationTime to be an explicit nil

### UnsetLastModificationTime
`func (o *MessageTemplateDto) UnsetLastModificationTime()`

UnsetLastModificationTime ensures that no value is present for LastModificationTime, not even an explicit nil
### GetLastModifierId

`func (o *MessageTemplateDto) GetLastModifierId() string`

GetLastModifierId returns the LastModifierId field if non-nil, zero value otherwise.

### GetLastModifierIdOk

`func (o *MessageTemplateDto) GetLastModifierIdOk() (*string, bool)`

GetLastModifierIdOk returns a tuple with the LastModifierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModifierId

`func (o *MessageTemplateDto) SetLastModifierId(v string)`

SetLastModifierId sets LastModifierId field to given value.

### HasLastModifierId

`func (o *MessageTemplateDto) HasLastModifierId() bool`

HasLastModifierId returns a boolean if a field has been set.

### SetLastModifierIdNil

`func (o *MessageTemplateDto) SetLastModifierIdNil(b bool)`

 SetLastModifierIdNil sets the value for LastModifierId to be an explicit nil

### UnsetLastModifierId
`func (o *MessageTemplateDto) UnsetLastModifierId()`

UnsetLastModifierId ensures that no value is present for LastModifierId, not even an explicit nil
### GetIsDeleted

`func (o *MessageTemplateDto) GetIsDeleted() bool`

GetIsDeleted returns the IsDeleted field if non-nil, zero value otherwise.

### GetIsDeletedOk

`func (o *MessageTemplateDto) GetIsDeletedOk() (*bool, bool)`

GetIsDeletedOk returns a tuple with the IsDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDeleted

`func (o *MessageTemplateDto) SetIsDeleted(v bool)`

SetIsDeleted sets IsDeleted field to given value.

### HasIsDeleted

`func (o *MessageTemplateDto) HasIsDeleted() bool`

HasIsDeleted returns a boolean if a field has been set.

### GetDeleterId

`func (o *MessageTemplateDto) GetDeleterId() string`

GetDeleterId returns the DeleterId field if non-nil, zero value otherwise.

### GetDeleterIdOk

`func (o *MessageTemplateDto) GetDeleterIdOk() (*string, bool)`

GetDeleterIdOk returns a tuple with the DeleterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleterId

`func (o *MessageTemplateDto) SetDeleterId(v string)`

SetDeleterId sets DeleterId field to given value.

### HasDeleterId

`func (o *MessageTemplateDto) HasDeleterId() bool`

HasDeleterId returns a boolean if a field has been set.

### SetDeleterIdNil

`func (o *MessageTemplateDto) SetDeleterIdNil(b bool)`

 SetDeleterIdNil sets the value for DeleterId to be an explicit nil

### UnsetDeleterId
`func (o *MessageTemplateDto) UnsetDeleterId()`

UnsetDeleterId ensures that no value is present for DeleterId, not even an explicit nil
### GetDeletionTime

`func (o *MessageTemplateDto) GetDeletionTime() time.Time`

GetDeletionTime returns the DeletionTime field if non-nil, zero value otherwise.

### GetDeletionTimeOk

`func (o *MessageTemplateDto) GetDeletionTimeOk() (*time.Time, bool)`

GetDeletionTimeOk returns a tuple with the DeletionTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletionTime

`func (o *MessageTemplateDto) SetDeletionTime(v time.Time)`

SetDeletionTime sets DeletionTime field to given value.

### HasDeletionTime

`func (o *MessageTemplateDto) HasDeletionTime() bool`

HasDeletionTime returns a boolean if a field has been set.

### SetDeletionTimeNil

`func (o *MessageTemplateDto) SetDeletionTimeNil(b bool)`

 SetDeletionTimeNil sets the value for DeletionTime to be an explicit nil

### UnsetDeletionTime
`func (o *MessageTemplateDto) UnsetDeletionTime()`

UnsetDeletionTime ensures that no value is present for DeletionTime, not even an explicit nil
### GetName

`func (o *MessageTemplateDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *MessageTemplateDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *MessageTemplateDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *MessageTemplateDto) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *MessageTemplateDto) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *MessageTemplateDto) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetDescription

`func (o *MessageTemplateDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *MessageTemplateDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *MessageTemplateDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *MessageTemplateDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *MessageTemplateDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *MessageTemplateDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetLatestVersion

`func (o *MessageTemplateDto) GetLatestVersion() int32`

GetLatestVersion returns the LatestVersion field if non-nil, zero value otherwise.

### GetLatestVersionOk

`func (o *MessageTemplateDto) GetLatestVersionOk() (*int32, bool)`

GetLatestVersionOk returns a tuple with the LatestVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestVersion

`func (o *MessageTemplateDto) SetLatestVersion(v int32)`

SetLatestVersion sets LatestVersion field to given value.

### HasLatestVersion

`func (o *MessageTemplateDto) HasLatestVersion() bool`

HasLatestVersion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


