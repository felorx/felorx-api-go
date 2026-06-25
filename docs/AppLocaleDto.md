# AppLocaleDto

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

### NewAppLocaleDto

`func NewAppLocaleDto() *AppLocaleDto`

NewAppLocaleDto instantiates a new AppLocaleDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAppLocaleDtoWithDefaults

`func NewAppLocaleDtoWithDefaults() *AppLocaleDto`

NewAppLocaleDtoWithDefaults instantiates a new AppLocaleDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AppLocaleDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AppLocaleDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AppLocaleDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *AppLocaleDto) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCreationTime

`func (o *AppLocaleDto) GetCreationTime() time.Time`

GetCreationTime returns the CreationTime field if non-nil, zero value otherwise.

### GetCreationTimeOk

`func (o *AppLocaleDto) GetCreationTimeOk() (*time.Time, bool)`

GetCreationTimeOk returns a tuple with the CreationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreationTime

`func (o *AppLocaleDto) SetCreationTime(v time.Time)`

SetCreationTime sets CreationTime field to given value.

### HasCreationTime

`func (o *AppLocaleDto) HasCreationTime() bool`

HasCreationTime returns a boolean if a field has been set.

### GetCreatorId

`func (o *AppLocaleDto) GetCreatorId() string`

GetCreatorId returns the CreatorId field if non-nil, zero value otherwise.

### GetCreatorIdOk

`func (o *AppLocaleDto) GetCreatorIdOk() (*string, bool)`

GetCreatorIdOk returns a tuple with the CreatorId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatorId

`func (o *AppLocaleDto) SetCreatorId(v string)`

SetCreatorId sets CreatorId field to given value.

### HasCreatorId

`func (o *AppLocaleDto) HasCreatorId() bool`

HasCreatorId returns a boolean if a field has been set.

### SetCreatorIdNil

`func (o *AppLocaleDto) SetCreatorIdNil(b bool)`

 SetCreatorIdNil sets the value for CreatorId to be an explicit nil

### UnsetCreatorId
`func (o *AppLocaleDto) UnsetCreatorId()`

UnsetCreatorId ensures that no value is present for CreatorId, not even an explicit nil
### GetLastModificationTime

`func (o *AppLocaleDto) GetLastModificationTime() time.Time`

GetLastModificationTime returns the LastModificationTime field if non-nil, zero value otherwise.

### GetLastModificationTimeOk

`func (o *AppLocaleDto) GetLastModificationTimeOk() (*time.Time, bool)`

GetLastModificationTimeOk returns a tuple with the LastModificationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModificationTime

`func (o *AppLocaleDto) SetLastModificationTime(v time.Time)`

SetLastModificationTime sets LastModificationTime field to given value.

### HasLastModificationTime

`func (o *AppLocaleDto) HasLastModificationTime() bool`

HasLastModificationTime returns a boolean if a field has been set.

### SetLastModificationTimeNil

`func (o *AppLocaleDto) SetLastModificationTimeNil(b bool)`

 SetLastModificationTimeNil sets the value for LastModificationTime to be an explicit nil

### UnsetLastModificationTime
`func (o *AppLocaleDto) UnsetLastModificationTime()`

UnsetLastModificationTime ensures that no value is present for LastModificationTime, not even an explicit nil
### GetLastModifierId

`func (o *AppLocaleDto) GetLastModifierId() string`

GetLastModifierId returns the LastModifierId field if non-nil, zero value otherwise.

### GetLastModifierIdOk

`func (o *AppLocaleDto) GetLastModifierIdOk() (*string, bool)`

GetLastModifierIdOk returns a tuple with the LastModifierId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastModifierId

`func (o *AppLocaleDto) SetLastModifierId(v string)`

SetLastModifierId sets LastModifierId field to given value.

### HasLastModifierId

`func (o *AppLocaleDto) HasLastModifierId() bool`

HasLastModifierId returns a boolean if a field has been set.

### SetLastModifierIdNil

`func (o *AppLocaleDto) SetLastModifierIdNil(b bool)`

 SetLastModifierIdNil sets the value for LastModifierId to be an explicit nil

### UnsetLastModifierId
`func (o *AppLocaleDto) UnsetLastModifierId()`

UnsetLastModifierId ensures that no value is present for LastModifierId, not even an explicit nil
### GetIsDeleted

`func (o *AppLocaleDto) GetIsDeleted() bool`

GetIsDeleted returns the IsDeleted field if non-nil, zero value otherwise.

### GetIsDeletedOk

`func (o *AppLocaleDto) GetIsDeletedOk() (*bool, bool)`

GetIsDeletedOk returns a tuple with the IsDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDeleted

`func (o *AppLocaleDto) SetIsDeleted(v bool)`

SetIsDeleted sets IsDeleted field to given value.

### HasIsDeleted

`func (o *AppLocaleDto) HasIsDeleted() bool`

HasIsDeleted returns a boolean if a field has been set.

### GetDeleterId

`func (o *AppLocaleDto) GetDeleterId() string`

GetDeleterId returns the DeleterId field if non-nil, zero value otherwise.

### GetDeleterIdOk

`func (o *AppLocaleDto) GetDeleterIdOk() (*string, bool)`

GetDeleterIdOk returns a tuple with the DeleterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleterId

`func (o *AppLocaleDto) SetDeleterId(v string)`

SetDeleterId sets DeleterId field to given value.

### HasDeleterId

`func (o *AppLocaleDto) HasDeleterId() bool`

HasDeleterId returns a boolean if a field has been set.

### SetDeleterIdNil

`func (o *AppLocaleDto) SetDeleterIdNil(b bool)`

 SetDeleterIdNil sets the value for DeleterId to be an explicit nil

### UnsetDeleterId
`func (o *AppLocaleDto) UnsetDeleterId()`

UnsetDeleterId ensures that no value is present for DeleterId, not even an explicit nil
### GetDeletionTime

`func (o *AppLocaleDto) GetDeletionTime() time.Time`

GetDeletionTime returns the DeletionTime field if non-nil, zero value otherwise.

### GetDeletionTimeOk

`func (o *AppLocaleDto) GetDeletionTimeOk() (*time.Time, bool)`

GetDeletionTimeOk returns a tuple with the DeletionTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletionTime

`func (o *AppLocaleDto) SetDeletionTime(v time.Time)`

SetDeletionTime sets DeletionTime field to given value.

### HasDeletionTime

`func (o *AppLocaleDto) HasDeletionTime() bool`

HasDeletionTime returns a boolean if a field has been set.

### SetDeletionTimeNil

`func (o *AppLocaleDto) SetDeletionTimeNil(b bool)`

 SetDeletionTimeNil sets the value for DeletionTime to be an explicit nil

### UnsetDeletionTime
`func (o *AppLocaleDto) UnsetDeletionTime()`

UnsetDeletionTime ensures that no value is present for DeletionTime, not even an explicit nil
### GetAppId

`func (o *AppLocaleDto) GetAppId() string`

GetAppId returns the AppId field if non-nil, zero value otherwise.

### GetAppIdOk

`func (o *AppLocaleDto) GetAppIdOk() (*string, bool)`

GetAppIdOk returns a tuple with the AppId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppId

`func (o *AppLocaleDto) SetAppId(v string)`

SetAppId sets AppId field to given value.

### HasAppId

`func (o *AppLocaleDto) HasAppId() bool`

HasAppId returns a boolean if a field has been set.

### GetLangCode

`func (o *AppLocaleDto) GetLangCode() string`

GetLangCode returns the LangCode field if non-nil, zero value otherwise.

### GetLangCodeOk

`func (o *AppLocaleDto) GetLangCodeOk() (*string, bool)`

GetLangCodeOk returns a tuple with the LangCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLangCode

`func (o *AppLocaleDto) SetLangCode(v string)`

SetLangCode sets LangCode field to given value.

### HasLangCode

`func (o *AppLocaleDto) HasLangCode() bool`

HasLangCode returns a boolean if a field has been set.

### SetLangCodeNil

`func (o *AppLocaleDto) SetLangCodeNil(b bool)`

 SetLangCodeNil sets the value for LangCode to be an explicit nil

### UnsetLangCode
`func (o *AppLocaleDto) UnsetLangCode()`

UnsetLangCode ensures that no value is present for LangCode, not even an explicit nil
### GetCountryCode

`func (o *AppLocaleDto) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *AppLocaleDto) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *AppLocaleDto) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *AppLocaleDto) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.

### SetCountryCodeNil

`func (o *AppLocaleDto) SetCountryCodeNil(b bool)`

 SetCountryCodeNil sets the value for CountryCode to be an explicit nil

### UnsetCountryCode
`func (o *AppLocaleDto) UnsetCountryCode()`

UnsetCountryCode ensures that no value is present for CountryCode, not even an explicit nil
### GetTitle

`func (o *AppLocaleDto) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *AppLocaleDto) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *AppLocaleDto) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *AppLocaleDto) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *AppLocaleDto) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *AppLocaleDto) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetSubtitle

`func (o *AppLocaleDto) GetSubtitle() string`

GetSubtitle returns the Subtitle field if non-nil, zero value otherwise.

### GetSubtitleOk

`func (o *AppLocaleDto) GetSubtitleOk() (*string, bool)`

GetSubtitleOk returns a tuple with the Subtitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtitle

`func (o *AppLocaleDto) SetSubtitle(v string)`

SetSubtitle sets Subtitle field to given value.

### HasSubtitle

`func (o *AppLocaleDto) HasSubtitle() bool`

HasSubtitle returns a boolean if a field has been set.

### SetSubtitleNil

`func (o *AppLocaleDto) SetSubtitleNil(b bool)`

 SetSubtitleNil sets the value for Subtitle to be an explicit nil

### UnsetSubtitle
`func (o *AppLocaleDto) UnsetSubtitle()`

UnsetSubtitle ensures that no value is present for Subtitle, not even an explicit nil
### GetShortDesc

`func (o *AppLocaleDto) GetShortDesc() string`

GetShortDesc returns the ShortDesc field if non-nil, zero value otherwise.

### GetShortDescOk

`func (o *AppLocaleDto) GetShortDescOk() (*string, bool)`

GetShortDescOk returns a tuple with the ShortDesc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShortDesc

`func (o *AppLocaleDto) SetShortDesc(v string)`

SetShortDesc sets ShortDesc field to given value.

### HasShortDesc

`func (o *AppLocaleDto) HasShortDesc() bool`

HasShortDesc returns a boolean if a field has been set.

### SetShortDescNil

`func (o *AppLocaleDto) SetShortDescNil(b bool)`

 SetShortDescNil sets the value for ShortDesc to be an explicit nil

### UnsetShortDesc
`func (o *AppLocaleDto) UnsetShortDesc()`

UnsetShortDesc ensures that no value is present for ShortDesc, not even an explicit nil
### GetFullDesc

`func (o *AppLocaleDto) GetFullDesc() string`

GetFullDesc returns the FullDesc field if non-nil, zero value otherwise.

### GetFullDescOk

`func (o *AppLocaleDto) GetFullDescOk() (*string, bool)`

GetFullDescOk returns a tuple with the FullDesc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFullDesc

`func (o *AppLocaleDto) SetFullDesc(v string)`

SetFullDesc sets FullDesc field to given value.

### HasFullDesc

`func (o *AppLocaleDto) HasFullDesc() bool`

HasFullDesc returns a boolean if a field has been set.

### SetFullDescNil

`func (o *AppLocaleDto) SetFullDescNil(b bool)`

 SetFullDescNil sets the value for FullDesc to be an explicit nil

### UnsetFullDesc
`func (o *AppLocaleDto) UnsetFullDesc()`

UnsetFullDesc ensures that no value is present for FullDesc, not even an explicit nil
### GetKeywords

`func (o *AppLocaleDto) GetKeywords() string`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *AppLocaleDto) GetKeywordsOk() (*string, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *AppLocaleDto) SetKeywords(v string)`

SetKeywords sets Keywords field to given value.

### HasKeywords

`func (o *AppLocaleDto) HasKeywords() bool`

HasKeywords returns a boolean if a field has been set.

### SetKeywordsNil

`func (o *AppLocaleDto) SetKeywordsNil(b bool)`

 SetKeywordsNil sets the value for Keywords to be an explicit nil

### UnsetKeywords
`func (o *AppLocaleDto) UnsetKeywords()`

UnsetKeywords ensures that no value is present for Keywords, not even an explicit nil
### GetPromoText

`func (o *AppLocaleDto) GetPromoText() string`

GetPromoText returns the PromoText field if non-nil, zero value otherwise.

### GetPromoTextOk

`func (o *AppLocaleDto) GetPromoTextOk() (*string, bool)`

GetPromoTextOk returns a tuple with the PromoText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromoText

`func (o *AppLocaleDto) SetPromoText(v string)`

SetPromoText sets PromoText field to given value.

### HasPromoText

`func (o *AppLocaleDto) HasPromoText() bool`

HasPromoText returns a boolean if a field has been set.

### SetPromoTextNil

`func (o *AppLocaleDto) SetPromoTextNil(b bool)`

 SetPromoTextNil sets the value for PromoText to be an explicit nil

### UnsetPromoText
`func (o *AppLocaleDto) UnsetPromoText()`

UnsetPromoText ensures that no value is present for PromoText, not even an explicit nil
### GetSupportUrl

`func (o *AppLocaleDto) GetSupportUrl() string`

GetSupportUrl returns the SupportUrl field if non-nil, zero value otherwise.

### GetSupportUrlOk

`func (o *AppLocaleDto) GetSupportUrlOk() (*string, bool)`

GetSupportUrlOk returns a tuple with the SupportUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportUrl

`func (o *AppLocaleDto) SetSupportUrl(v string)`

SetSupportUrl sets SupportUrl field to given value.

### HasSupportUrl

`func (o *AppLocaleDto) HasSupportUrl() bool`

HasSupportUrl returns a boolean if a field has been set.

### SetSupportUrlNil

`func (o *AppLocaleDto) SetSupportUrlNil(b bool)`

 SetSupportUrlNil sets the value for SupportUrl to be an explicit nil

### UnsetSupportUrl
`func (o *AppLocaleDto) UnsetSupportUrl()`

UnsetSupportUrl ensures that no value is present for SupportUrl, not even an explicit nil
### GetPrivacyUrl

`func (o *AppLocaleDto) GetPrivacyUrl() string`

GetPrivacyUrl returns the PrivacyUrl field if non-nil, zero value otherwise.

### GetPrivacyUrlOk

`func (o *AppLocaleDto) GetPrivacyUrlOk() (*string, bool)`

GetPrivacyUrlOk returns a tuple with the PrivacyUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivacyUrl

`func (o *AppLocaleDto) SetPrivacyUrl(v string)`

SetPrivacyUrl sets PrivacyUrl field to given value.

### HasPrivacyUrl

`func (o *AppLocaleDto) HasPrivacyUrl() bool`

HasPrivacyUrl returns a boolean if a field has been set.

### SetPrivacyUrlNil

`func (o *AppLocaleDto) SetPrivacyUrlNil(b bool)`

 SetPrivacyUrlNil sets the value for PrivacyUrl to be an explicit nil

### UnsetPrivacyUrl
`func (o *AppLocaleDto) UnsetPrivacyUrl()`

UnsetPrivacyUrl ensures that no value is present for PrivacyUrl, not even an explicit nil
### GetReleaseNote

`func (o *AppLocaleDto) GetReleaseNote() string`

GetReleaseNote returns the ReleaseNote field if non-nil, zero value otherwise.

### GetReleaseNoteOk

`func (o *AppLocaleDto) GetReleaseNoteOk() (*string, bool)`

GetReleaseNoteOk returns a tuple with the ReleaseNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseNote

`func (o *AppLocaleDto) SetReleaseNote(v string)`

SetReleaseNote sets ReleaseNote field to given value.

### HasReleaseNote

`func (o *AppLocaleDto) HasReleaseNote() bool`

HasReleaseNote returns a boolean if a field has been set.

### SetReleaseNoteNil

`func (o *AppLocaleDto) SetReleaseNoteNil(b bool)`

 SetReleaseNoteNil sets the value for ReleaseNote to be an explicit nil

### UnsetReleaseNote
`func (o *AppLocaleDto) UnsetReleaseNote()`

UnsetReleaseNote ensures that no value is present for ReleaseNote, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


