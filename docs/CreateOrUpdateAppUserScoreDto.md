# CreateOrUpdateAppUserScoreDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppId** | Pointer to **NullableString** |  | [optional] 
**Score** | Pointer to **int32** |  | [optional] 
**Comment** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCreateOrUpdateAppUserScoreDto

`func NewCreateOrUpdateAppUserScoreDto() *CreateOrUpdateAppUserScoreDto`

NewCreateOrUpdateAppUserScoreDto instantiates a new CreateOrUpdateAppUserScoreDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrUpdateAppUserScoreDtoWithDefaults

`func NewCreateOrUpdateAppUserScoreDtoWithDefaults() *CreateOrUpdateAppUserScoreDto`

NewCreateOrUpdateAppUserScoreDtoWithDefaults instantiates a new CreateOrUpdateAppUserScoreDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppId

`func (o *CreateOrUpdateAppUserScoreDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *CreateOrUpdateAppUserScoreDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *CreateOrUpdateAppUserScoreDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *CreateOrUpdateAppUserScoreDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### SetAppIdNil

`func (o *CreateOrUpdateAppUserScoreDto) SetAppIdNil(b bool)`

 SetAppIdNil sets the value for AppId to be an explicit nil

### UnsetAppId
`func (o *CreateOrUpdateAppUserScoreDto) UnsetAppId()`

UnsetAppId ensures that no value is present for AppId, not even an explicit nil
### GetScore

`func (o *CreateOrUpdateAppUserScoreDto) GetScore() int32`

GetScore returns the Score field if non-nil, zero value otherwise.

### GetScoreOk

`func (o *CreateOrUpdateAppUserScoreDto) GetScoreOk() (*int32, bool)`

GetScoreOk returns a tuple with the Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScore

`func (o *CreateOrUpdateAppUserScoreDto) SetScore(v int32)`

SetScore sets Score field to given value.

### HasScore

`func (o *CreateOrUpdateAppUserScoreDto) HasScore() bool`

HasScore returns a boolean if a field has been set.

### GetComment

`func (o *CreateOrUpdateAppUserScoreDto) GetComment() string`

GetComment returns the Comment field if non-nil, zero value otherwise.

### GetCommentOk

`func (o *CreateOrUpdateAppUserScoreDto) GetCommentOk() (*string, bool)`

GetCommentOk returns a tuple with the Comment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComment

`func (o *CreateOrUpdateAppUserScoreDto) SetComment(v string)`

SetComment sets Comment field to given value.

### HasComment

`func (o *CreateOrUpdateAppUserScoreDto) HasComment() bool`

HasComment returns a boolean if a field has been set.

### SetCommentNil

`func (o *CreateOrUpdateAppUserScoreDto) SetCommentNil(b bool)`

 SetCommentNil sets the value for Comment to be an explicit nil

### UnsetComment
`func (o *CreateOrUpdateAppUserScoreDto) UnsetComment()`

UnsetComment ensures that no value is present for Comment, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


