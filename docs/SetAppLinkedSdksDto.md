# SetAppLinkedSdksDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SdkIds** | Pointer to **[]string** | 要关联到应用的 SDK Id 列表（顺序保留）；空列表表示清除全部关联。 | [optional]

## Methods

### NewSetAppLinkedSdksDto

`func NewSetAppLinkedSdksDto() *SetAppLinkedSdksDto`

NewSetAppLinkedSdksDto instantiates a new SetAppLinkedSdksDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSetAppLinkedSdksDtoWithDefaults

`func NewSetAppLinkedSdksDtoWithDefaults() *SetAppLinkedSdksDto`

NewSetAppLinkedSdksDtoWithDefaults instantiates a new SetAppLinkedSdksDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSdkIds

`func (o *SetAppLinkedSdksDto) GetSdkIds() []string`

GetSdkIds returns the SdkIds field if non-nil, zero value otherwise.

### GetSdkIdsOk

`func (o *SetAppLinkedSdksDto) GetSdkIdsOk() (*[]string, bool)`

GetSdkIdsOk returns a tuple with the SdkIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSdkIds

`func (o *SetAppLinkedSdksDto) SetSdkIds(v []string)`

SetSdkIds sets SdkIds field to given value.

### HasSdkIds

`func (o *SetAppLinkedSdksDto) HasSdkIds() bool`

HasSdkIds returns a boolean if a field has been set.

### SetSdkIdsNil

`func (o *SetAppLinkedSdksDto) SetSdkIdsNil(b bool)`

 SetSdkIdsNil sets the value for SdkIds to be an explicit nil

### UnsetSdkIds
`func (o *SetAppLinkedSdksDto) UnsetSdkIds()`

UnsetSdkIds ensures that no value is present for SdkIds, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


