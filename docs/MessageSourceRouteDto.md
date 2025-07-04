# MessageSourceRouteDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Title** | Pointer to **NullableString** |  | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**Path** | Pointer to **NullableString** |  | [optional] 
**SourceId** | Pointer to **string** |  | [optional] 
**Extra** | Pointer to **NullableString** |  | [optional] 
**Anticrawler** | Pointer to **bool** |  | [optional] 
**Radar** | Pointer to **bool** |  | [optional] 
**Rssbud** | Pointer to **bool** |  | [optional] 
**IsPublished** | Pointer to **bool** |  | [optional] 
**IconUrl** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewMessageSourceRouteDto

`func NewMessageSourceRouteDto() *MessageSourceRouteDto`

NewMessageSourceRouteDto instantiates a new MessageSourceRouteDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMessageSourceRouteDtoWithDefaults

`func NewMessageSourceRouteDtoWithDefaults() *MessageSourceRouteDto`

NewMessageSourceRouteDtoWithDefaults instantiates a new MessageSourceRouteDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTitle

`func (o *MessageSourceRouteDto) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *MessageSourceRouteDto) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *MessageSourceRouteDto) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *MessageSourceRouteDto) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *MessageSourceRouteDto) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *MessageSourceRouteDto) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetDescription

`func (o *MessageSourceRouteDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *MessageSourceRouteDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *MessageSourceRouteDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *MessageSourceRouteDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *MessageSourceRouteDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *MessageSourceRouteDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetPath

`func (o *MessageSourceRouteDto) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *MessageSourceRouteDto) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *MessageSourceRouteDto) SetPath(v string)`

SetPath sets Path field to given value.

### HasPath

`func (o *MessageSourceRouteDto) HasPath() bool`

HasPath returns a boolean if a field has been set.

### SetPathNil

`func (o *MessageSourceRouteDto) SetPathNil(b bool)`

 SetPathNil sets the value for Path to be an explicit nil

### UnsetPath
`func (o *MessageSourceRouteDto) UnsetPath()`

UnsetPath ensures that no value is present for Path, not even an explicit nil
### GetSourceId

`func (o *MessageSourceRouteDto) GetSourceId() string`

GetSourceId returns the SourceId field if non-nil, zero value otherwise.

### GetSourceIdOk

`func (o *MessageSourceRouteDto) GetSourceIdOk() (*string, bool)`

GetSourceIdOk returns a tuple with the SourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceId

`func (o *MessageSourceRouteDto) SetSourceId(v string)`

SetSourceId sets SourceId field to given value.

### HasSourceId

`func (o *MessageSourceRouteDto) HasSourceId() bool`

HasSourceId returns a boolean if a field has been set.

### GetExtra

`func (o *MessageSourceRouteDto) GetExtra() string`

GetExtra returns the Extra field if non-nil, zero value otherwise.

### GetExtraOk

`func (o *MessageSourceRouteDto) GetExtraOk() (*string, bool)`

GetExtraOk returns a tuple with the Extra field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtra

`func (o *MessageSourceRouteDto) SetExtra(v string)`

SetExtra sets Extra field to given value.

### HasExtra

`func (o *MessageSourceRouteDto) HasExtra() bool`

HasExtra returns a boolean if a field has been set.

### SetExtraNil

`func (o *MessageSourceRouteDto) SetExtraNil(b bool)`

 SetExtraNil sets the value for Extra to be an explicit nil

### UnsetExtra
`func (o *MessageSourceRouteDto) UnsetExtra()`

UnsetExtra ensures that no value is present for Extra, not even an explicit nil
### GetAnticrawler

`func (o *MessageSourceRouteDto) GetAnticrawler() bool`

GetAnticrawler returns the Anticrawler field if non-nil, zero value otherwise.

### GetAnticrawlerOk

`func (o *MessageSourceRouteDto) GetAnticrawlerOk() (*bool, bool)`

GetAnticrawlerOk returns a tuple with the Anticrawler field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnticrawler

`func (o *MessageSourceRouteDto) SetAnticrawler(v bool)`

SetAnticrawler sets Anticrawler field to given value.

### HasAnticrawler

`func (o *MessageSourceRouteDto) HasAnticrawler() bool`

HasAnticrawler returns a boolean if a field has been set.

### GetRadar

`func (o *MessageSourceRouteDto) GetRadar() bool`

GetRadar returns the Radar field if non-nil, zero value otherwise.

### GetRadarOk

`func (o *MessageSourceRouteDto) GetRadarOk() (*bool, bool)`

GetRadarOk returns a tuple with the Radar field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRadar

`func (o *MessageSourceRouteDto) SetRadar(v bool)`

SetRadar sets Radar field to given value.

### HasRadar

`func (o *MessageSourceRouteDto) HasRadar() bool`

HasRadar returns a boolean if a field has been set.

### GetRssbud

`func (o *MessageSourceRouteDto) GetRssbud() bool`

GetRssbud returns the Rssbud field if non-nil, zero value otherwise.

### GetRssbudOk

`func (o *MessageSourceRouteDto) GetRssbudOk() (*bool, bool)`

GetRssbudOk returns a tuple with the Rssbud field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRssbud

`func (o *MessageSourceRouteDto) SetRssbud(v bool)`

SetRssbud sets Rssbud field to given value.

### HasRssbud

`func (o *MessageSourceRouteDto) HasRssbud() bool`

HasRssbud returns a boolean if a field has been set.

### GetIsPublished

`func (o *MessageSourceRouteDto) GetIsPublished() bool`

GetIsPublished returns the IsPublished field if non-nil, zero value otherwise.

### GetIsPublishedOk

`func (o *MessageSourceRouteDto) GetIsPublishedOk() (*bool, bool)`

GetIsPublishedOk returns a tuple with the IsPublished field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPublished

`func (o *MessageSourceRouteDto) SetIsPublished(v bool)`

SetIsPublished sets IsPublished field to given value.

### HasIsPublished

`func (o *MessageSourceRouteDto) HasIsPublished() bool`

HasIsPublished returns a boolean if a field has been set.

### GetIconUrl

`func (o *MessageSourceRouteDto) GetIconUrl() string`

GetIconUrl returns the IconUrl field if non-nil, zero value otherwise.

### GetIconUrlOk

`func (o *MessageSourceRouteDto) GetIconUrlOk() (*string, bool)`

GetIconUrlOk returns a tuple with the IconUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIconUrl

`func (o *MessageSourceRouteDto) SetIconUrl(v string)`

SetIconUrl sets IconUrl field to given value.

### HasIconUrl

`func (o *MessageSourceRouteDto) HasIconUrl() bool`

HasIconUrl returns a boolean if a field has been set.

### SetIconUrlNil

`func (o *MessageSourceRouteDto) SetIconUrlNil(b bool)`

 SetIconUrlNil sets the value for IconUrl to be an explicit nil

### UnsetIconUrl
`func (o *MessageSourceRouteDto) UnsetIconUrl()`

UnsetIconUrl ensures that no value is present for IconUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


