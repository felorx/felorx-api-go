# CreateOrUpdateAppLocaleDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppId** | Pointer to **string** |  | [optional]
**LangCode** | Pointer to **NullableString** |  | [optional]
**CountryCode** | Pointer to **NullableString** |  | [optional]
**Title** | Pointer to **NullableString** |  | [optional]
**Subtitle** | Pointer to **NullableString** |  | [optional]
**ShortDesc** | Pointer to **NullableString** |  | [optional]
**FullDesc** | Pointer to **NullableString** |  | [optional]
**Keywords** | Pointer to **NullableString** |  | [optional]
**PromoText** | Pointer to **NullableString** |  | [optional]
**SupportUrl** | Pointer to **NullableString** |  | [optional]
**PrivacyUrl** | Pointer to **NullableString** |  | [optional]
**ReleaseNote** | Pointer to **NullableString** |  | [optional]

## Methods

### NewCreateOrUpdateAppLocaleDto

`func NewCreateOrUpdateAppLocaleDto() *CreateOrUpdateAppLocaleDto`

NewCreateOrUpdateAppLocaleDto instantiates a new CreateOrUpdateAppLocaleDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateOrUpdateAppLocaleDtoWithDefaults

`func NewCreateOrUpdateAppLocaleDtoWithDefaults() *CreateOrUpdateAppLocaleDto`

NewCreateOrUpdateAppLocaleDtoWithDefaults instantiates a new CreateOrUpdateAppLocaleDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppId

`func (o *CreateOrUpdateAppLocaleDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *CreateOrUpdateAppLocaleDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *CreateOrUpdateAppLocaleDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *CreateOrUpdateAppLocaleDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetLangCode

`func (o *CreateOrUpdateAppLocaleDto) GetLangCode() string`

GetLangCode returns the LangCode field if non-nil, zero value otherwise.

### GetLangCodeOk

`func (o *CreateOrUpdateAppLocaleDto) GetLangCodeOk() (*string, bool)`

GetLangCodeOk returns a tuple with the LangCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLangCode

`func (o *CreateOrUpdateAppLocaleDto) SetLangCode(v string)`

SetLangCode sets LangCode field to given value.

### HasLangCode

`func (o *CreateOrUpdateAppLocaleDto) HasLangCode() bool`

HasLangCode returns a boolean if a field has been set.

### SetLangCodeNil

`func (o *CreateOrUpdateAppLocaleDto) SetLangCodeNil(b bool)`

 SetLangCodeNil sets the value for LangCode to be an explicit nil

### UnsetLangCode
`func (o *CreateOrUpdateAppLocaleDto) UnsetLangCode()`

UnsetLangCode ensures that no value is present for LangCode, not even an explicit nil
### GetCountryCode

`func (o *CreateOrUpdateAppLocaleDto) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *CreateOrUpdateAppLocaleDto) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *CreateOrUpdateAppLocaleDto) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *CreateOrUpdateAppLocaleDto) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.

### SetCountryCodeNil

`func (o *CreateOrUpdateAppLocaleDto) SetCountryCodeNil(b bool)`

 SetCountryCodeNil sets the value for CountryCode to be an explicit nil

### UnsetCountryCode
`func (o *CreateOrUpdateAppLocaleDto) UnsetCountryCode()`

UnsetCountryCode ensures that no value is present for CountryCode, not even an explicit nil
### GetTitle

`func (o *CreateOrUpdateAppLocaleDto) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CreateOrUpdateAppLocaleDto) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CreateOrUpdateAppLocaleDto) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *CreateOrUpdateAppLocaleDto) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *CreateOrUpdateAppLocaleDto) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *CreateOrUpdateAppLocaleDto) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetSubtitle

`func (o *CreateOrUpdateAppLocaleDto) GetSubtitle() string`

GetSubtitle returns the Subtitle field if non-nil, zero value otherwise.

### GetSubtitleOk

`func (o *CreateOrUpdateAppLocaleDto) GetSubtitleOk() (*string, bool)`

GetSubtitleOk returns a tuple with the Subtitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtitle

`func (o *CreateOrUpdateAppLocaleDto) SetSubtitle(v string)`

SetSubtitle sets Subtitle field to given value.

### HasSubtitle

`func (o *CreateOrUpdateAppLocaleDto) HasSubtitle() bool`

HasSubtitle returns a boolean if a field has been set.

### SetSubtitleNil

`func (o *CreateOrUpdateAppLocaleDto) SetSubtitleNil(b bool)`

 SetSubtitleNil sets the value for Subtitle to be an explicit nil

### UnsetSubtitle
`func (o *CreateOrUpdateAppLocaleDto) UnsetSubtitle()`

UnsetSubtitle ensures that no value is present for Subtitle, not even an explicit nil
### GetShortDesc

`func (o *CreateOrUpdateAppLocaleDto) GetShortDesc() string`

GetShortDesc returns the ShortDesc field if non-nil, zero value otherwise.

### GetShortDescOk

`func (o *CreateOrUpdateAppLocaleDto) GetShortDescOk() (*string, bool)`

GetShortDescOk returns a tuple with the ShortDesc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShortDesc

`func (o *CreateOrUpdateAppLocaleDto) SetShortDesc(v string)`

SetShortDesc sets ShortDesc field to given value.

### HasShortDesc

`func (o *CreateOrUpdateAppLocaleDto) HasShortDesc() bool`

HasShortDesc returns a boolean if a field has been set.

### SetShortDescNil

`func (o *CreateOrUpdateAppLocaleDto) SetShortDescNil(b bool)`

 SetShortDescNil sets the value for ShortDesc to be an explicit nil

### UnsetShortDesc
`func (o *CreateOrUpdateAppLocaleDto) UnsetShortDesc()`

UnsetShortDesc ensures that no value is present for ShortDesc, not even an explicit nil
### GetFullDesc

`func (o *CreateOrUpdateAppLocaleDto) GetFullDesc() string`

GetFullDesc returns the FullDesc field if non-nil, zero value otherwise.

### GetFullDescOk

`func (o *CreateOrUpdateAppLocaleDto) GetFullDescOk() (*string, bool)`

GetFullDescOk returns a tuple with the FullDesc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFullDesc

`func (o *CreateOrUpdateAppLocaleDto) SetFullDesc(v string)`

SetFullDesc sets FullDesc field to given value.

### HasFullDesc

`func (o *CreateOrUpdateAppLocaleDto) HasFullDesc() bool`

HasFullDesc returns a boolean if a field has been set.

### SetFullDescNil

`func (o *CreateOrUpdateAppLocaleDto) SetFullDescNil(b bool)`

 SetFullDescNil sets the value for FullDesc to be an explicit nil

### UnsetFullDesc
`func (o *CreateOrUpdateAppLocaleDto) UnsetFullDesc()`

UnsetFullDesc ensures that no value is present for FullDesc, not even an explicit nil
### GetKeywords

`func (o *CreateOrUpdateAppLocaleDto) GetKeywords() string`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *CreateOrUpdateAppLocaleDto) GetKeywordsOk() (*string, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *CreateOrUpdateAppLocaleDto) SetKeywords(v string)`

SetKeywords sets Keywords field to given value.

### HasKeywords

`func (o *CreateOrUpdateAppLocaleDto) HasKeywords() bool`

HasKeywords returns a boolean if a field has been set.

### SetKeywordsNil

`func (o *CreateOrUpdateAppLocaleDto) SetKeywordsNil(b bool)`

 SetKeywordsNil sets the value for Keywords to be an explicit nil

### UnsetKeywords
`func (o *CreateOrUpdateAppLocaleDto) UnsetKeywords()`

UnsetKeywords ensures that no value is present for Keywords, not even an explicit nil
### GetPromoText

`func (o *CreateOrUpdateAppLocaleDto) GetPromoText() string`

GetPromoText returns the PromoText field if non-nil, zero value otherwise.

### GetPromoTextOk

`func (o *CreateOrUpdateAppLocaleDto) GetPromoTextOk() (*string, bool)`

GetPromoTextOk returns a tuple with the PromoText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromoText

`func (o *CreateOrUpdateAppLocaleDto) SetPromoText(v string)`

SetPromoText sets PromoText field to given value.

### HasPromoText

`func (o *CreateOrUpdateAppLocaleDto) HasPromoText() bool`

HasPromoText returns a boolean if a field has been set.

### SetPromoTextNil

`func (o *CreateOrUpdateAppLocaleDto) SetPromoTextNil(b bool)`

 SetPromoTextNil sets the value for PromoText to be an explicit nil

### UnsetPromoText
`func (o *CreateOrUpdateAppLocaleDto) UnsetPromoText()`

UnsetPromoText ensures that no value is present for PromoText, not even an explicit nil
### GetSupportUrl

`func (o *CreateOrUpdateAppLocaleDto) GetSupportUrl() string`

GetSupportUrl returns the SupportUrl field if non-nil, zero value otherwise.

### GetSupportUrlOk

`func (o *CreateOrUpdateAppLocaleDto) GetSupportUrlOk() (*string, bool)`

GetSupportUrlOk returns a tuple with the SupportUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportUrl

`func (o *CreateOrUpdateAppLocaleDto) SetSupportUrl(v string)`

SetSupportUrl sets SupportUrl field to given value.

### HasSupportUrl

`func (o *CreateOrUpdateAppLocaleDto) HasSupportUrl() bool`

HasSupportUrl returns a boolean if a field has been set.

### SetSupportUrlNil

`func (o *CreateOrUpdateAppLocaleDto) SetSupportUrlNil(b bool)`

 SetSupportUrlNil sets the value for SupportUrl to be an explicit nil

### UnsetSupportUrl
`func (o *CreateOrUpdateAppLocaleDto) UnsetSupportUrl()`

UnsetSupportUrl ensures that no value is present for SupportUrl, not even an explicit nil
### GetPrivacyUrl

`func (o *CreateOrUpdateAppLocaleDto) GetPrivacyUrl() string`

GetPrivacyUrl returns the PrivacyUrl field if non-nil, zero value otherwise.

### GetPrivacyUrlOk

`func (o *CreateOrUpdateAppLocaleDto) GetPrivacyUrlOk() (*string, bool)`

GetPrivacyUrlOk returns a tuple with the PrivacyUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivacyUrl

`func (o *CreateOrUpdateAppLocaleDto) SetPrivacyUrl(v string)`

SetPrivacyUrl sets PrivacyUrl field to given value.

### HasPrivacyUrl

`func (o *CreateOrUpdateAppLocaleDto) HasPrivacyUrl() bool`

HasPrivacyUrl returns a boolean if a field has been set.

### SetPrivacyUrlNil

`func (o *CreateOrUpdateAppLocaleDto) SetPrivacyUrlNil(b bool)`

 SetPrivacyUrlNil sets the value for PrivacyUrl to be an explicit nil

### UnsetPrivacyUrl
`func (o *CreateOrUpdateAppLocaleDto) UnsetPrivacyUrl()`

UnsetPrivacyUrl ensures that no value is present for PrivacyUrl, not even an explicit nil
### GetReleaseNote

`func (o *CreateOrUpdateAppLocaleDto) GetReleaseNote() string`

GetReleaseNote returns the ReleaseNote field if non-nil, zero value otherwise.

### GetReleaseNoteOk

`func (o *CreateOrUpdateAppLocaleDto) GetReleaseNoteOk() (*string, bool)`

GetReleaseNoteOk returns a tuple with the ReleaseNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseNote

`func (o *CreateOrUpdateAppLocaleDto) SetReleaseNote(v string)`

SetReleaseNote sets ReleaseNote field to given value.

### HasReleaseNote

`func (o *CreateOrUpdateAppLocaleDto) HasReleaseNote() bool`

HasReleaseNote returns a boolean if a field has been set.

### SetReleaseNoteNil

`func (o *CreateOrUpdateAppLocaleDto) SetReleaseNoteNil(b bool)`

 SetReleaseNoteNil sets the value for ReleaseNote to be an explicit nil

### UnsetReleaseNote
`func (o *CreateOrUpdateAppLocaleDto) UnsetReleaseNote()`

UnsetReleaseNote ensures that no value is present for ReleaseNote, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


