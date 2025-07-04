# MessageSourceCategoryDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**Title** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewMessageSourceCategoryDto

`func NewMessageSourceCategoryDto() *MessageSourceCategoryDto`

NewMessageSourceCategoryDto instantiates a new MessageSourceCategoryDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMessageSourceCategoryDtoWithDefaults

`func NewMessageSourceCategoryDtoWithDefaults() *MessageSourceCategoryDto`

NewMessageSourceCategoryDtoWithDefaults instantiates a new MessageSourceCategoryDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *MessageSourceCategoryDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *MessageSourceCategoryDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *MessageSourceCategoryDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *MessageSourceCategoryDto) HasId() bool`

HasId returns a boolean if a field has been set.

### GetTitle

`func (o *MessageSourceCategoryDto) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *MessageSourceCategoryDto) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *MessageSourceCategoryDto) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *MessageSourceCategoryDto) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *MessageSourceCategoryDto) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *MessageSourceCategoryDto) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


