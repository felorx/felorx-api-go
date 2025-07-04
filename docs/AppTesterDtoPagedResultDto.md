# AppTesterDtoPagedResultDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | Pointer to [**[]AppTesterDto**](AppTesterDto.md) |  | [optional] 
**TotalCount** | Pointer to **int64** |  | [optional] 

## Methods

### NewAppTesterDtoPagedResultDto

`func NewAppTesterDtoPagedResultDto() *AppTesterDtoPagedResultDto`

NewAppTesterDtoPagedResultDto instantiates a new AppTesterDtoPagedResultDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAppTesterDtoPagedResultDtoWithDefaults

`func NewAppTesterDtoPagedResultDtoWithDefaults() *AppTesterDtoPagedResultDto`

NewAppTesterDtoPagedResultDtoWithDefaults instantiates a new AppTesterDtoPagedResultDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetItems

`func (o *AppTesterDtoPagedResultDto) GetItems() []AppTesterDto`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *AppTesterDtoPagedResultDto) GetItemsOk() (*[]AppTesterDto, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *AppTesterDtoPagedResultDto) SetItems(v []AppTesterDto)`

SetItems sets Items field to given value.

### HasItems

`func (o *AppTesterDtoPagedResultDto) HasItems() bool`

HasItems returns a boolean if a field has been set.

### SetItemsNil

`func (o *AppTesterDtoPagedResultDto) SetItemsNil(b bool)`

 SetItemsNil sets the value for Items to be an explicit nil

### UnsetItems
`func (o *AppTesterDtoPagedResultDto) UnsetItems()`

UnsetItems ensures that no value is present for Items, not even an explicit nil
### GetTotalCount

`func (o *AppTesterDtoPagedResultDto) GetTotalCount() int64`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *AppTesterDtoPagedResultDto) GetTotalCountOk() (*int64, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *AppTesterDtoPagedResultDto) SetTotalCount(v int64)`

SetTotalCount sets TotalCount field to given value.

### HasTotalCount

`func (o *AppTesterDtoPagedResultDto) HasTotalCount() bool`

HasTotalCount returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


