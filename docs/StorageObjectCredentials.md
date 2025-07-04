# StorageObjectCredentials

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**StorageClass** | Pointer to **NullableString** |  | [optional] 
**EndPoint** | Pointer to **NullableString** |  | [optional] 
**Protocal** | Pointer to **NullableString** |  | [optional] 
**BucketName** | Pointer to **NullableString** |  | [optional] 
**RegionId** | Pointer to **NullableString** |  | [optional] 
**SecurityToken** | Pointer to **NullableString** |  | [optional] 
**AccessKeyId** | Pointer to **NullableString** |  | [optional] 
**AccessKeySecret** | Pointer to **NullableString** |  | [optional] 
**Expiration** | Pointer to **NullableString** |  | [optional] 
**ExpiredTime** | Pointer to **int64** |  | [optional] 
**AppId** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewStorageObjectCredentials

`func NewStorageObjectCredentials() *StorageObjectCredentials`

NewStorageObjectCredentials instantiates a new StorageObjectCredentials object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStorageObjectCredentialsWithDefaults

`func NewStorageObjectCredentialsWithDefaults() *StorageObjectCredentials`

NewStorageObjectCredentialsWithDefaults instantiates a new StorageObjectCredentials object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStorageClass

`func (o *StorageObjectCredentials) GetStorageClass() string`

GetStorageClass returns the StorageClass field if non-nil, zero value otherwise.

### GetStorageClassOk

`func (o *StorageObjectCredentials) GetStorageClassOk() (*string, bool)`

GetStorageClassOk returns a tuple with the StorageClass field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStorageClass

`func (o *StorageObjectCredentials) SetStorageClass(v string)`

SetStorageClass sets StorageClass field to given value.

### HasStorageClass

`func (o *StorageObjectCredentials) HasStorageClass() bool`

HasStorageClass returns a boolean if a field has been set.

### SetStorageClassNil

`func (o *StorageObjectCredentials) SetStorageClassNil(b bool)`

 SetStorageClassNil sets the value for StorageClass to be an explicit nil

### UnsetStorageClass
`func (o *StorageObjectCredentials) UnsetStorageClass()`

UnsetStorageClass ensures that no value is present for StorageClass, not even an explicit nil
### GetEndPoint

`func (o *StorageObjectCredentials) GetEndPoint() string`

GetEndPoint returns the EndPoint field if non-nil, zero value otherwise.

### GetEndPointOk

`func (o *StorageObjectCredentials) GetEndPointOk() (*string, bool)`

GetEndPointOk returns a tuple with the EndPoint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndPoint

`func (o *StorageObjectCredentials) SetEndPoint(v string)`

SetEndPoint sets EndPoint field to given value.

### HasEndPoint

`func (o *StorageObjectCredentials) HasEndPoint() bool`

HasEndPoint returns a boolean if a field has been set.

### SetEndPointNil

`func (o *StorageObjectCredentials) SetEndPointNil(b bool)`

 SetEndPointNil sets the value for EndPoint to be an explicit nil

### UnsetEndPoint
`func (o *StorageObjectCredentials) UnsetEndPoint()`

UnsetEndPoint ensures that no value is present for EndPoint, not even an explicit nil
### GetProtocal

`func (o *StorageObjectCredentials) GetProtocal() string`

GetProtocal returns the Protocal field if non-nil, zero value otherwise.

### GetProtocalOk

`func (o *StorageObjectCredentials) GetProtocalOk() (*string, bool)`

GetProtocalOk returns a tuple with the Protocal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProtocal

`func (o *StorageObjectCredentials) SetProtocal(v string)`

SetProtocal sets Protocal field to given value.

### HasProtocal

`func (o *StorageObjectCredentials) HasProtocal() bool`

HasProtocal returns a boolean if a field has been set.

### SetProtocalNil

`func (o *StorageObjectCredentials) SetProtocalNil(b bool)`

 SetProtocalNil sets the value for Protocal to be an explicit nil

### UnsetProtocal
`func (o *StorageObjectCredentials) UnsetProtocal()`

UnsetProtocal ensures that no value is present for Protocal, not even an explicit nil
### GetBucketName

`func (o *StorageObjectCredentials) GetBucketName() string`

GetBucketName returns the BucketName field if non-nil, zero value otherwise.

### GetBucketNameOk

`func (o *StorageObjectCredentials) GetBucketNameOk() (*string, bool)`

GetBucketNameOk returns a tuple with the BucketName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBucketName

`func (o *StorageObjectCredentials) SetBucketName(v string)`

SetBucketName sets BucketName field to given value.

### HasBucketName

`func (o *StorageObjectCredentials) HasBucketName() bool`

HasBucketName returns a boolean if a field has been set.

### SetBucketNameNil

`func (o *StorageObjectCredentials) SetBucketNameNil(b bool)`

 SetBucketNameNil sets the value for BucketName to be an explicit nil

### UnsetBucketName
`func (o *StorageObjectCredentials) UnsetBucketName()`

UnsetBucketName ensures that no value is present for BucketName, not even an explicit nil
### GetRegionId

`func (o *StorageObjectCredentials) GetRegionId() string`

GetRegionId returns the RegionId field if non-nil, zero value otherwise.

### GetRegionIdOk

`func (o *StorageObjectCredentials) GetRegionIdOk() (*string, bool)`

GetRegionIdOk returns a tuple with the RegionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegionId

`func (o *StorageObjectCredentials) SetRegionId(v string)`

SetRegionId sets RegionId field to given value.

### HasRegionId

`func (o *StorageObjectCredentials) HasRegionId() bool`

HasRegionId returns a boolean if a field has been set.

### SetRegionIdNil

`func (o *StorageObjectCredentials) SetRegionIdNil(b bool)`

 SetRegionIdNil sets the value for RegionId to be an explicit nil

### UnsetRegionId
`func (o *StorageObjectCredentials) UnsetRegionId()`

UnsetRegionId ensures that no value is present for RegionId, not even an explicit nil
### GetSecurityToken

`func (o *StorageObjectCredentials) GetSecurityToken() string`

GetSecurityToken returns the SecurityToken field if non-nil, zero value otherwise.

### GetSecurityTokenOk

`func (o *StorageObjectCredentials) GetSecurityTokenOk() (*string, bool)`

GetSecurityTokenOk returns a tuple with the SecurityToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecurityToken

`func (o *StorageObjectCredentials) SetSecurityToken(v string)`

SetSecurityToken sets SecurityToken field to given value.

### HasSecurityToken

`func (o *StorageObjectCredentials) HasSecurityToken() bool`

HasSecurityToken returns a boolean if a field has been set.

### SetSecurityTokenNil

`func (o *StorageObjectCredentials) SetSecurityTokenNil(b bool)`

 SetSecurityTokenNil sets the value for SecurityToken to be an explicit nil

### UnsetSecurityToken
`func (o *StorageObjectCredentials) UnsetSecurityToken()`

UnsetSecurityToken ensures that no value is present for SecurityToken, not even an explicit nil
### GetAccessKeyId

`func (o *StorageObjectCredentials) GetAccessKeyId() string`

GetAccessKeyId returns the AccessKeyId field if non-nil, zero value otherwise.

### GetAccessKeyIdOk

`func (o *StorageObjectCredentials) GetAccessKeyIdOk() (*string, bool)`

GetAccessKeyIdOk returns a tuple with the AccessKeyId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessKeyId

`func (o *StorageObjectCredentials) SetAccessKeyId(v string)`

SetAccessKeyId sets AccessKeyId field to given value.

### HasAccessKeyId

`func (o *StorageObjectCredentials) HasAccessKeyId() bool`

HasAccessKeyId returns a boolean if a field has been set.

### SetAccessKeyIdNil

`func (o *StorageObjectCredentials) SetAccessKeyIdNil(b bool)`

 SetAccessKeyIdNil sets the value for AccessKeyId to be an explicit nil

### UnsetAccessKeyId
`func (o *StorageObjectCredentials) UnsetAccessKeyId()`

UnsetAccessKeyId ensures that no value is present for AccessKeyId, not even an explicit nil
### GetAccessKeySecret

`func (o *StorageObjectCredentials) GetAccessKeySecret() string`

GetAccessKeySecret returns the AccessKeySecret field if non-nil, zero value otherwise.

### GetAccessKeySecretOk

`func (o *StorageObjectCredentials) GetAccessKeySecretOk() (*string, bool)`

GetAccessKeySecretOk returns a tuple with the AccessKeySecret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessKeySecret

`func (o *StorageObjectCredentials) SetAccessKeySecret(v string)`

SetAccessKeySecret sets AccessKeySecret field to given value.

### HasAccessKeySecret

`func (o *StorageObjectCredentials) HasAccessKeySecret() bool`

HasAccessKeySecret returns a boolean if a field has been set.

### SetAccessKeySecretNil

`func (o *StorageObjectCredentials) SetAccessKeySecretNil(b bool)`

 SetAccessKeySecretNil sets the value for AccessKeySecret to be an explicit nil

### UnsetAccessKeySecret
`func (o *StorageObjectCredentials) UnsetAccessKeySecret()`

UnsetAccessKeySecret ensures that no value is present for AccessKeySecret, not even an explicit nil
### GetExpiration

`func (o *StorageObjectCredentials) GetExpiration() string`

GetExpiration returns the Expiration field if non-nil, zero value otherwise.

### GetExpirationOk

`func (o *StorageObjectCredentials) GetExpirationOk() (*string, bool)`

GetExpirationOk returns a tuple with the Expiration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiration

`func (o *StorageObjectCredentials) SetExpiration(v string)`

SetExpiration sets Expiration field to given value.

### HasExpiration

`func (o *StorageObjectCredentials) HasExpiration() bool`

HasExpiration returns a boolean if a field has been set.

### SetExpirationNil

`func (o *StorageObjectCredentials) SetExpirationNil(b bool)`

 SetExpirationNil sets the value for Expiration to be an explicit nil

### UnsetExpiration
`func (o *StorageObjectCredentials) UnsetExpiration()`

UnsetExpiration ensures that no value is present for Expiration, not even an explicit nil
### GetExpiredTime

`func (o *StorageObjectCredentials) GetExpiredTime() int64`

GetExpiredTime returns the ExpiredTime field if non-nil, zero value otherwise.

### GetExpiredTimeOk

`func (o *StorageObjectCredentials) GetExpiredTimeOk() (*int64, bool)`

GetExpiredTimeOk returns a tuple with the ExpiredTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiredTime

`func (o *StorageObjectCredentials) SetExpiredTime(v int64)`

SetExpiredTime sets ExpiredTime field to given value.

### HasExpiredTime

`func (o *StorageObjectCredentials) HasExpiredTime() bool`

HasExpiredTime returns a boolean if a field has been set.

### GetAppId

`func (o *StorageObjectCredentials) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *StorageObjectCredentials) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *StorageObjectCredentials) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *StorageObjectCredentials) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### SetAppIdNil

`func (o *StorageObjectCredentials) SetAppIdNil(b bool)`

 SetAppIdNil sets the value for AppId to be an explicit nil

### UnsetAppId
`func (o *StorageObjectCredentials) UnsetAppId()`

UnsetAppId ensures that no value is present for AppId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


