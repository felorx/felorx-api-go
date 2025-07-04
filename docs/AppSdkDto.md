# AppSdkDto

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
**Privacy** | Pointer to **NullableString** |  | [optional] 
**PrivacyUrl** | Pointer to **NullableString** |  | [optional] 
**HomePage** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewAppSdkDto

`func NewAppSdkDto() *AppSdkDto`

NewAppSdkDto instantiates a new AppSdkDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAppSdkDtoWithDefaults

`func NewAppSdkDtoWithDefaults() *AppSdkDto`

NewAppSdkDtoWithDefaults instantiates a new AppSdkDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AppSdkDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AppSdkDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AppSdkDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AppSdkDto) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreationTime

`func (o *AppSdkDto) GetCreationTime() time.Time`

GetCreationTime returns the CreationTime field if non-nil, zero value otherwise.

### GetCreationTimeOk

`func (o *AppSdkDto) GetCreationTimeOk() (*time.Time, bool)`

GetCreationTimeOk returns a tuple with the CreationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreationTime

`func (o *AppSdkDto) SetCreationTime(v time.Time)`

SetCreationTime sets CreationTime field to given value.

### HasCreationTime

`func (o *AppSdkDto) HasCreationTime() bool`

HasCreationTime returns a boolean if a field has been set.

### GetCreatorId

`func (o *AppSdkDto) GetCreatorId() string`

GetCreatorId returns the CreatorId field if non-nil, zero value otherwise.

### GetCreatorIdOk

`func (o *AppSdkDto) GetCreatorIdOk() (*string, bool)`

GetCreatorIdOk returns a tuple with the CreatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatorId

`func (o *AppSdkDto) SetCreatorId(v string)`

SetCreatorId sets CreatorId field to given value.

### HasCreatorId

`func (o *AppSdkDto) HasCreatorId() bool`

HasCreatorId returns a boolean if a field has been set.

### SetCreatorIdNil

`func (o *AppSdkDto) SetCreatorIdNil(b bool)`

 SetCreatorIdNil sets the value for CreatorId to be an explicit nil

### UnsetCreatorId
`func (o *AppSdkDto) UnsetCreatorId()`

UnsetCreatorId ensures that no value is present for CreatorId, not even an explicit nil
### GetLastModificationTime

`func (o *AppSdkDto) GetLastModificationTime() time.Time`

GetLastModificationTime returns the LastModificationTime field if non-nil, zero value otherwise.

### GetLastModificationTimeOk

`func (o *AppSdkDto) GetLastModificationTimeOk() (*time.Time, bool)`

GetLastModificationTimeOk returns a tuple with the LastModificationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModificationTime

`func (o *AppSdkDto) SetLastModificationTime(v time.Time)`

SetLastModificationTime sets LastModificationTime field to given value.

### HasLastModificationTime

`func (o *AppSdkDto) HasLastModificationTime() bool`

HasLastModificationTime returns a boolean if a field has been set.

### SetLastModificationTimeNil

`func (o *AppSdkDto) SetLastModificationTimeNil(b bool)`

 SetLastModificationTimeNil sets the value for LastModificationTime to be an explicit nil

### UnsetLastModificationTime
`func (o *AppSdkDto) UnsetLastModificationTime()`

UnsetLastModificationTime ensures that no value is present for LastModificationTime, not even an explicit nil
### GetLastModifierId

`func (o *AppSdkDto) GetLastModifierId() string`

GetLastModifierId returns the LastModifierId field if non-nil, zero value otherwise.

### GetLastModifierIdOk

`func (o *AppSdkDto) GetLastModifierIdOk() (*string, bool)`

GetLastModifierIdOk returns a tuple with the LastModifierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModifierId

`func (o *AppSdkDto) SetLastModifierId(v string)`

SetLastModifierId sets LastModifierId field to given value.

### HasLastModifierId

`func (o *AppSdkDto) HasLastModifierId() bool`

HasLastModifierId returns a boolean if a field has been set.

### SetLastModifierIdNil

`func (o *AppSdkDto) SetLastModifierIdNil(b bool)`

 SetLastModifierIdNil sets the value for LastModifierId to be an explicit nil

### UnsetLastModifierId
`func (o *AppSdkDto) UnsetLastModifierId()`

UnsetLastModifierId ensures that no value is present for LastModifierId, not even an explicit nil
### GetIsDeleted

`func (o *AppSdkDto) GetIsDeleted() bool`

GetIsDeleted returns the IsDeleted field if non-nil, zero value otherwise.

### GetIsDeletedOk

`func (o *AppSdkDto) GetIsDeletedOk() (*bool, bool)`

GetIsDeletedOk returns a tuple with the IsDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDeleted

`func (o *AppSdkDto) SetIsDeleted(v bool)`

SetIsDeleted sets IsDeleted field to given value.

### HasIsDeleted

`func (o *AppSdkDto) HasIsDeleted() bool`

HasIsDeleted returns a boolean if a field has been set.

### GetDeleterId

`func (o *AppSdkDto) GetDeleterId() string`

GetDeleterId returns the DeleterId field if non-nil, zero value otherwise.

### GetDeleterIdOk

`func (o *AppSdkDto) GetDeleterIdOk() (*string, bool)`

GetDeleterIdOk returns a tuple with the DeleterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleterId

`func (o *AppSdkDto) SetDeleterId(v string)`

SetDeleterId sets DeleterId field to given value.

### HasDeleterId

`func (o *AppSdkDto) HasDeleterId() bool`

HasDeleterId returns a boolean if a field has been set.

### SetDeleterIdNil

`func (o *AppSdkDto) SetDeleterIdNil(b bool)`

 SetDeleterIdNil sets the value for DeleterId to be an explicit nil

### UnsetDeleterId
`func (o *AppSdkDto) UnsetDeleterId()`

UnsetDeleterId ensures that no value is present for DeleterId, not even an explicit nil
### GetDeletionTime

`func (o *AppSdkDto) GetDeletionTime() time.Time`

GetDeletionTime returns the DeletionTime field if non-nil, zero value otherwise.

### GetDeletionTimeOk

`func (o *AppSdkDto) GetDeletionTimeOk() (*time.Time, bool)`

GetDeletionTimeOk returns a tuple with the DeletionTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletionTime

`func (o *AppSdkDto) SetDeletionTime(v time.Time)`

SetDeletionTime sets DeletionTime field to given value.

### HasDeletionTime

`func (o *AppSdkDto) HasDeletionTime() bool`

HasDeletionTime returns a boolean if a field has been set.

### SetDeletionTimeNil

`func (o *AppSdkDto) SetDeletionTimeNil(b bool)`

 SetDeletionTimeNil sets the value for DeletionTime to be an explicit nil

### UnsetDeletionTime
`func (o *AppSdkDto) UnsetDeletionTime()`

UnsetDeletionTime ensures that no value is present for DeletionTime, not even an explicit nil
### GetName

`func (o *AppSdkDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AppSdkDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AppSdkDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *AppSdkDto) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *AppSdkDto) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *AppSdkDto) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetDescription

`func (o *AppSdkDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *AppSdkDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *AppSdkDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *AppSdkDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *AppSdkDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *AppSdkDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetPrivacy

`func (o *AppSdkDto) GetPrivacy() string`

GetPrivacy returns the Privacy field if non-nil, zero value otherwise.

### GetPrivacyOk

`func (o *AppSdkDto) GetPrivacyOk() (*string, bool)`

GetPrivacyOk returns a tuple with the Privacy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivacy

`func (o *AppSdkDto) SetPrivacy(v string)`

SetPrivacy sets Privacy field to given value.

### HasPrivacy

`func (o *AppSdkDto) HasPrivacy() bool`

HasPrivacy returns a boolean if a field has been set.

### SetPrivacyNil

`func (o *AppSdkDto) SetPrivacyNil(b bool)`

 SetPrivacyNil sets the value for Privacy to be an explicit nil

### UnsetPrivacy
`func (o *AppSdkDto) UnsetPrivacy()`

UnsetPrivacy ensures that no value is present for Privacy, not even an explicit nil
### GetPrivacyUrl

`func (o *AppSdkDto) GetPrivacyUrl() string`

GetPrivacyUrl returns the PrivacyUrl field if non-nil, zero value otherwise.

### GetPrivacyUrlOk

`func (o *AppSdkDto) GetPrivacyUrlOk() (*string, bool)`

GetPrivacyUrlOk returns a tuple with the PrivacyUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivacyUrl

`func (o *AppSdkDto) SetPrivacyUrl(v string)`

SetPrivacyUrl sets PrivacyUrl field to given value.

### HasPrivacyUrl

`func (o *AppSdkDto) HasPrivacyUrl() bool`

HasPrivacyUrl returns a boolean if a field has been set.

### SetPrivacyUrlNil

`func (o *AppSdkDto) SetPrivacyUrlNil(b bool)`

 SetPrivacyUrlNil sets the value for PrivacyUrl to be an explicit nil

### UnsetPrivacyUrl
`func (o *AppSdkDto) UnsetPrivacyUrl()`

UnsetPrivacyUrl ensures that no value is present for PrivacyUrl, not even an explicit nil
### GetHomePage

`func (o *AppSdkDto) GetHomePage() string`

GetHomePage returns the HomePage field if non-nil, zero value otherwise.

### GetHomePageOk

`func (o *AppSdkDto) GetHomePageOk() (*string, bool)`

GetHomePageOk returns a tuple with the HomePage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHomePage

`func (o *AppSdkDto) SetHomePage(v string)`

SetHomePage sets HomePage field to given value.

### HasHomePage

`func (o *AppSdkDto) HasHomePage() bool`

HasHomePage returns a boolean if a field has been set.

### SetHomePageNil

`func (o *AppSdkDto) SetHomePageNil(b bool)`

 SetHomePageNil sets the value for HomePage to be an explicit nil

### UnsetHomePage
`func (o *AppSdkDto) UnsetHomePage()`

UnsetHomePage ensures that no value is present for HomePage, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


