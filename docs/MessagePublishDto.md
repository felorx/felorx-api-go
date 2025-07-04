# MessagePublishDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Title** | Pointer to **NullableString** |  | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**AppId** | Pointer to **string** |  | [optional] 
**Template** | Pointer to **NullableString** | 模板名称, 包含版本号  puupee/wechat-app-msg?version&#x3D;1 微信应用消息模板  puupee/wechat-official-msg?version&#x3D;2 微信公众号消息模板 | [optional] 
**Data** | Pointer to **map[string]interface{}** | JSON格式数据 | [optional] 

## Methods

### NewMessagePublishDto

`func NewMessagePublishDto() *MessagePublishDto`

NewMessagePublishDto instantiates a new MessagePublishDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMessagePublishDtoWithDefaults

`func NewMessagePublishDtoWithDefaults() *MessagePublishDto`

NewMessagePublishDtoWithDefaults instantiates a new MessagePublishDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTitle

`func (o *MessagePublishDto) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *MessagePublishDto) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *MessagePublishDto) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *MessagePublishDto) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *MessagePublishDto) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *MessagePublishDto) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetDescription

`func (o *MessagePublishDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *MessagePublishDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *MessagePublishDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *MessagePublishDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *MessagePublishDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *MessagePublishDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetAppId

`func (o *MessagePublishDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *MessagePublishDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *MessagePublishDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *MessagePublishDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetTemplate

`func (o *MessagePublishDto) GetTemplate() string`

GetTemplate returns the Template field if non-nil, zero value otherwise.

### GetTemplateOk

`func (o *MessagePublishDto) GetTemplateOk() (*string, bool)`

GetTemplateOk returns a tuple with the Template field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplate

`func (o *MessagePublishDto) SetTemplate(v string)`

SetTemplate sets Template field to given value.

### HasTemplate

`func (o *MessagePublishDto) HasTemplate() bool`

HasTemplate returns a boolean if a field has been set.

### SetTemplateNil

`func (o *MessagePublishDto) SetTemplateNil(b bool)`

 SetTemplateNil sets the value for Template to be an explicit nil

### UnsetTemplate
`func (o *MessagePublishDto) UnsetTemplate()`

UnsetTemplate ensures that no value is present for Template, not even an explicit nil
### GetData

`func (o *MessagePublishDto) GetData() map[string]interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *MessagePublishDto) GetDataOk() (*map[string]interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *MessagePublishDto) SetData(v map[string]interface{})`

SetData sets Data field to given value.

### HasData

`func (o *MessagePublishDto) HasData() bool`

HasData returns a boolean if a field has been set.

### SetDataNil

`func (o *MessagePublishDto) SetDataNil(b bool)`

 SetDataNil sets the value for Data to be an explicit nil

### UnsetData
`func (o *MessagePublishDto) UnsetData()`

UnsetData ensures that no value is present for Data, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


