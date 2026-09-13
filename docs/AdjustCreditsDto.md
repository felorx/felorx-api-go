# AdjustCreditsDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppId** | **string** |  | 
**Amount** | Pointer to **int32** |  | [optional] 
**ReferenceId** | **string** |  | 
**Description** | **string** |  | 

## Methods

### NewAdjustCreditsDto

`func NewAdjustCreditsDto(appId string, referenceId string, description string, ) *AdjustCreditsDto`

NewAdjustCreditsDto instantiates a new AdjustCreditsDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAdjustCreditsDtoWithDefaults

`func NewAdjustCreditsDtoWithDefaults() *AdjustCreditsDto`

NewAdjustCreditsDtoWithDefaults instantiates a new AdjustCreditsDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppId

`func (o *AdjustCreditsDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *AdjustCreditsDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *AdjustCreditsDto) SetAppId(v string)`

SetAppId sets AppId field to given value.


### GetAmount

`func (o *AdjustCreditsDto) GetAmount() int32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *AdjustCreditsDto) GetAmountOk() (*int32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *AdjustCreditsDto) SetAmount(v int32)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *AdjustCreditsDto) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetReferenceId

`func (o *AdjustCreditsDto) GetReferenceId() string`

GetReferenceId returns the ReferenceId field if non-nil, zero value otherwise.

### GetReferenceIdOk

`func (o *AdjustCreditsDto) GetReferenceIdOk() (*string, bool)`

GetReferenceIdOk returns a tuple with the ReferenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceId

`func (o *AdjustCreditsDto) SetReferenceId(v string)`

SetReferenceId sets ReferenceId field to given value.


### GetDescription

`func (o *AdjustCreditsDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *AdjustCreditsDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *AdjustCreditsDto) SetDescription(v string)`

SetDescription sets Description field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


