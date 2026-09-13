# AppAssetDto

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
**AppId** | Pointer to **string** |  | [optional] 
**AppLocaleId** | Pointer to **string** |  | [optional] 
**AppFeatureId** | Pointer to **NullableString** |  | [optional] 
**AssetType** | Pointer to [**AppAssetType**](AppAssetType.md) |  | [optional] 
**DeviceType** | Pointer to [**AppAssetDeviceType**](AppAssetDeviceType.md) |  | [optional] 
**Url** | Pointer to **NullableString** |  | [optional] 
**Sort** | Pointer to **int32** |  | [optional] 

## Methods

### NewAppAssetDto

`func NewAppAssetDto() *AppAssetDto`

NewAppAssetDto instantiates a new AppAssetDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAppAssetDtoWithDefaults

`func NewAppAssetDtoWithDefaults() *AppAssetDto`

NewAppAssetDtoWithDefaults instantiates a new AppAssetDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AppAssetDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AppAssetDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AppAssetDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AppAssetDto) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreationTime

`func (o *AppAssetDto) GetCreationTime() time.Time`

GetCreationTime returns the CreationTime field if non-nil, zero value otherwise.

### GetCreationTimeOk

`func (o *AppAssetDto) GetCreationTimeOk() (*time.Time, bool)`

GetCreationTimeOk returns a tuple with the CreationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreationTime

`func (o *AppAssetDto) SetCreationTime(v time.Time)`

SetCreationTime sets CreationTime field to given value.

### HasCreationTime

`func (o *AppAssetDto) HasCreationTime() bool`

HasCreationTime returns a boolean if a field has been set.

### GetCreatorId

`func (o *AppAssetDto) GetCreatorId() string`

GetCreatorId returns the CreatorId field if non-nil, zero value otherwise.

### GetCreatorIdOk

`func (o *AppAssetDto) GetCreatorIdOk() (*string, bool)`

GetCreatorIdOk returns a tuple with the CreatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatorId

`func (o *AppAssetDto) SetCreatorId(v string)`

SetCreatorId sets CreatorId field to given value.

### HasCreatorId

`func (o *AppAssetDto) HasCreatorId() bool`

HasCreatorId returns a boolean if a field has been set.

### SetCreatorIdNil

`func (o *AppAssetDto) SetCreatorIdNil(b bool)`

 SetCreatorIdNil sets the value for CreatorId to be an explicit nil

### UnsetCreatorId
`func (o *AppAssetDto) UnsetCreatorId()`

UnsetCreatorId ensures that no value is present for CreatorId, not even an explicit nil
### GetLastModificationTime

`func (o *AppAssetDto) GetLastModificationTime() time.Time`

GetLastModificationTime returns the LastModificationTime field if non-nil, zero value otherwise.

### GetLastModificationTimeOk

`func (o *AppAssetDto) GetLastModificationTimeOk() (*time.Time, bool)`

GetLastModificationTimeOk returns a tuple with the LastModificationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModificationTime

`func (o *AppAssetDto) SetLastModificationTime(v time.Time)`

SetLastModificationTime sets LastModificationTime field to given value.

### HasLastModificationTime

`func (o *AppAssetDto) HasLastModificationTime() bool`

HasLastModificationTime returns a boolean if a field has been set.

### SetLastModificationTimeNil

`func (o *AppAssetDto) SetLastModificationTimeNil(b bool)`

 SetLastModificationTimeNil sets the value for LastModificationTime to be an explicit nil

### UnsetLastModificationTime
`func (o *AppAssetDto) UnsetLastModificationTime()`

UnsetLastModificationTime ensures that no value is present for LastModificationTime, not even an explicit nil
### GetLastModifierId

`func (o *AppAssetDto) GetLastModifierId() string`

GetLastModifierId returns the LastModifierId field if non-nil, zero value otherwise.

### GetLastModifierIdOk

`func (o *AppAssetDto) GetLastModifierIdOk() (*string, bool)`

GetLastModifierIdOk returns a tuple with the LastModifierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModifierId

`func (o *AppAssetDto) SetLastModifierId(v string)`

SetLastModifierId sets LastModifierId field to given value.

### HasLastModifierId

`func (o *AppAssetDto) HasLastModifierId() bool`

HasLastModifierId returns a boolean if a field has been set.

### SetLastModifierIdNil

`func (o *AppAssetDto) SetLastModifierIdNil(b bool)`

 SetLastModifierIdNil sets the value for LastModifierId to be an explicit nil

### UnsetLastModifierId
`func (o *AppAssetDto) UnsetLastModifierId()`

UnsetLastModifierId ensures that no value is present for LastModifierId, not even an explicit nil
### GetIsDeleted

`func (o *AppAssetDto) GetIsDeleted() bool`

GetIsDeleted returns the IsDeleted field if non-nil, zero value otherwise.

### GetIsDeletedOk

`func (o *AppAssetDto) GetIsDeletedOk() (*bool, bool)`

GetIsDeletedOk returns a tuple with the IsDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDeleted

`func (o *AppAssetDto) SetIsDeleted(v bool)`

SetIsDeleted sets IsDeleted field to given value.

### HasIsDeleted

`func (o *AppAssetDto) HasIsDeleted() bool`

HasIsDeleted returns a boolean if a field has been set.

### GetDeleterId

`func (o *AppAssetDto) GetDeleterId() string`

GetDeleterId returns the DeleterId field if non-nil, zero value otherwise.

### GetDeleterIdOk

`func (o *AppAssetDto) GetDeleterIdOk() (*string, bool)`

GetDeleterIdOk returns a tuple with the DeleterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleterId

`func (o *AppAssetDto) SetDeleterId(v string)`

SetDeleterId sets DeleterId field to given value.

### HasDeleterId

`func (o *AppAssetDto) HasDeleterId() bool`

HasDeleterId returns a boolean if a field has been set.

### SetDeleterIdNil

`func (o *AppAssetDto) SetDeleterIdNil(b bool)`

 SetDeleterIdNil sets the value for DeleterId to be an explicit nil

### UnsetDeleterId
`func (o *AppAssetDto) UnsetDeleterId()`

UnsetDeleterId ensures that no value is present for DeleterId, not even an explicit nil
### GetDeletionTime

`func (o *AppAssetDto) GetDeletionTime() time.Time`

GetDeletionTime returns the DeletionTime field if non-nil, zero value otherwise.

### GetDeletionTimeOk

`func (o *AppAssetDto) GetDeletionTimeOk() (*time.Time, bool)`

GetDeletionTimeOk returns a tuple with the DeletionTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletionTime

`func (o *AppAssetDto) SetDeletionTime(v time.Time)`

SetDeletionTime sets DeletionTime field to given value.

### HasDeletionTime

`func (o *AppAssetDto) HasDeletionTime() bool`

HasDeletionTime returns a boolean if a field has been set.

### SetDeletionTimeNil

`func (o *AppAssetDto) SetDeletionTimeNil(b bool)`

 SetDeletionTimeNil sets the value for DeletionTime to be an explicit nil

### UnsetDeletionTime
`func (o *AppAssetDto) UnsetDeletionTime()`

UnsetDeletionTime ensures that no value is present for DeletionTime, not even an explicit nil
### GetAppId

`func (o *AppAssetDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *AppAssetDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *AppAssetDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *AppAssetDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetAppLocaleId

`func (o *AppAssetDto) GetAppLocaleId() string`

GetAppLocaleId returns the AppLocaleId field if non-nil, zero value otherwise.

### GetAppLocaleIdOk

`func (o *AppAssetDto) GetAppLocaleIdOk() (*string, bool)`

GetAppLocaleIdOk returns a tuple with the AppLocaleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppLocaleId

`func (o *AppAssetDto) SetAppLocaleId(v string)`

SetAppLocaleId sets AppLocaleId field to given value.

### HasAppLocaleId

`func (o *AppAssetDto) HasAppLocaleId() bool`

HasAppLocaleId returns a boolean if a field has been set.

### GetAppFeatureId

`func (o *AppAssetDto) GetAppFeatureId() string`

GetAppFeatureId returns the AppFeatureId field if non-nil, zero value otherwise.

### GetAppFeatureIdOk

`func (o *AppAssetDto) GetAppFeatureIdOk() (*string, bool)`

GetAppFeatureIdOk returns a tuple with the AppFeatureId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppFeatureId

`func (o *AppAssetDto) SetAppFeatureId(v string)`

SetAppFeatureId sets AppFeatureId field to given value.

### HasAppFeatureId

`func (o *AppAssetDto) HasAppFeatureId() bool`

HasAppFeatureId returns a boolean if a field has been set.

### SetAppFeatureIdNil

`func (o *AppAssetDto) SetAppFeatureIdNil(b bool)`

 SetAppFeatureIdNil sets the value for AppFeatureId to be an explicit nil

### UnsetAppFeatureId
`func (o *AppAssetDto) UnsetAppFeatureId()`

UnsetAppFeatureId ensures that no value is present for AppFeatureId, not even an explicit nil
### GetAssetType

`func (o *AppAssetDto) GetAssetType() AppAssetType`

GetAssetType returns the AssetType field if non-nil, zero value otherwise.

### GetAssetTypeOk

`func (o *AppAssetDto) GetAssetTypeOk() (*AppAssetType, bool)`

GetAssetTypeOk returns a tuple with the AssetType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetType

`func (o *AppAssetDto) SetAssetType(v AppAssetType)`

SetAssetType sets AssetType field to given value.

### HasAssetType

`func (o *AppAssetDto) HasAssetType() bool`

HasAssetType returns a boolean if a field has been set.

### GetDeviceType

`func (o *AppAssetDto) GetDeviceType() AppAssetDeviceType`

GetDeviceType returns the DeviceType field if non-nil, zero value otherwise.

### GetDeviceTypeOk

`func (o *AppAssetDto) GetDeviceTypeOk() (*AppAssetDeviceType, bool)`

GetDeviceTypeOk returns a tuple with the DeviceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceType

`func (o *AppAssetDto) SetDeviceType(v AppAssetDeviceType)`

SetDeviceType sets DeviceType field to given value.

### HasDeviceType

`func (o *AppAssetDto) HasDeviceType() bool`

HasDeviceType returns a boolean if a field has been set.

### GetUrl

`func (o *AppAssetDto) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *AppAssetDto) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *AppAssetDto) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *AppAssetDto) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### SetUrlNil

`func (o *AppAssetDto) SetUrlNil(b bool)`

 SetUrlNil sets the value for Url to be an explicit nil

### UnsetUrl
`func (o *AppAssetDto) UnsetUrl()`

UnsetUrl ensures that no value is present for Url, not even an explicit nil
### GetSort

`func (o *AppAssetDto) GetSort() int32`

GetSort returns the Sort field if non-nil, zero value otherwise.

### GetSortOk

`func (o *AppAssetDto) GetSortOk() (*int32, bool)`

GetSortOk returns a tuple with the Sort field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSort

`func (o *AppAssetDto) SetSort(v int32)`

SetSort sets Sort field to given value.

### HasSort

`func (o *AppAssetDto) HasSort() bool`

HasSort returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


