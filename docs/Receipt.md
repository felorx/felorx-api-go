# Receipt

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ReceiptType** | Pointer to **NullableString** |  | [optional] 
**AdamId** | Pointer to **int64** |  | [optional] 
**AppItemId** | Pointer to **int64** |  | [optional] 
**BundleId** | Pointer to **NullableString** |  | [optional] 
**ApplicationVersion** | Pointer to **NullableString** |  | [optional] 
**DownloadId** | Pointer to **int64** |  | [optional] 
**VersionExternalIdentifier** | Pointer to **int32** |  | [optional] 
**ReceiptCreationDate** | Pointer to **NullableString** |  | [optional] 
**ReceiptCreationDateMs** | Pointer to **NullableString** |  | [optional] 
**ReceiptCreationDatePst** | Pointer to **NullableString** |  | [optional] 
**RequestDate** | Pointer to **NullableString** |  | [optional] 
**RequestDateMs** | Pointer to **NullableString** |  | [optional] 
**RequestDatePst** | Pointer to **NullableString** |  | [optional] 
**OriginalPurchaseDate** | Pointer to **NullableString** |  | [optional] 
**OriginalPurchaseDateMs** | Pointer to **NullableString** |  | [optional] 
**OriginalPurchaseDatePst** | Pointer to **NullableString** |  | [optional] 
**OriginalApplicationVersion** | Pointer to **NullableString** |  | [optional] 
**InApp** | Pointer to [**[]InApp**](InApp.md) |  | [optional] 

## Methods

### NewReceipt

`func NewReceipt() *Receipt`

NewReceipt instantiates a new Receipt object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReceiptWithDefaults

`func NewReceiptWithDefaults() *Receipt`

NewReceiptWithDefaults instantiates a new Receipt object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReceiptType

`func (o *Receipt) GetReceiptType() string`

GetReceiptType returns the ReceiptType field if non-nil, zero value otherwise.

### GetReceiptTypeOk

`func (o *Receipt) GetReceiptTypeOk() (*string, bool)`

GetReceiptTypeOk returns a tuple with the ReceiptType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiptType

`func (o *Receipt) SetReceiptType(v string)`

SetReceiptType sets ReceiptType field to given value.

### HasReceiptType

`func (o *Receipt) HasReceiptType() bool`

HasReceiptType returns a boolean if a field has been set.

### SetReceiptTypeNil

`func (o *Receipt) SetReceiptTypeNil(b bool)`

 SetReceiptTypeNil sets the value for ReceiptType to be an explicit nil

### UnsetReceiptType
`func (o *Receipt) UnsetReceiptType()`

UnsetReceiptType ensures that no value is present for ReceiptType, not even an explicit nil
### GetAdamId

`func (o *Receipt) GetAdamId() int64`

GetAdamId returns the AdamId field if non-nil, zero value otherwise.

### GetAdamIdOk

`func (o *Receipt) GetAdamIdOk() (*int64, bool)`

GetAdamIdOk returns a tuple with the AdamId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdamId

`func (o *Receipt) SetAdamId(v int64)`

SetAdamId sets AdamId field to given value.

### HasAdamId

`func (o *Receipt) HasAdamId() bool`

HasAdamId returns a boolean if a field has been set.

### GetAppItemId

`func (o *Receipt) GetAppItemId() int64`

GetAppItemId returns the AppItemId field if non-nil, zero value otherwise.

### GetAppItemIdOk

`func (o *Receipt) GetAppItemIdOk() (*int64, bool)`

GetAppItemIdOk returns a tuple with the AppItemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppItemId

`func (o *Receipt) SetAppItemId(v int64)`

SetAppItemId sets AppItemId field to given value.

### HasAppItemId

`func (o *Receipt) HasAppItemId() bool`

HasAppItemId returns a boolean if a field has been set.

### GetBundleId

`func (o *Receipt) GetBundleId() string`

GetBundleId returns the BundleId field if non-nil, zero value otherwise.

### GetBundleIdOk

`func (o *Receipt) GetBundleIdOk() (*string, bool)`

GetBundleIdOk returns a tuple with the BundleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBundleId

`func (o *Receipt) SetBundleId(v string)`

SetBundleId sets BundleId field to given value.

### HasBundleId

`func (o *Receipt) HasBundleId() bool`

HasBundleId returns a boolean if a field has been set.

### SetBundleIdNil

`func (o *Receipt) SetBundleIdNil(b bool)`

 SetBundleIdNil sets the value for BundleId to be an explicit nil

### UnsetBundleId
`func (o *Receipt) UnsetBundleId()`

UnsetBundleId ensures that no value is present for BundleId, not even an explicit nil
### GetApplicationVersion

`func (o *Receipt) GetApplicationVersion() string`

GetApplicationVersion returns the ApplicationVersion field if non-nil, zero value otherwise.

### GetApplicationVersionOk

`func (o *Receipt) GetApplicationVersionOk() (*string, bool)`

GetApplicationVersionOk returns a tuple with the ApplicationVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApplicationVersion

`func (o *Receipt) SetApplicationVersion(v string)`

SetApplicationVersion sets ApplicationVersion field to given value.

### HasApplicationVersion

`func (o *Receipt) HasApplicationVersion() bool`

HasApplicationVersion returns a boolean if a field has been set.

### SetApplicationVersionNil

`func (o *Receipt) SetApplicationVersionNil(b bool)`

 SetApplicationVersionNil sets the value for ApplicationVersion to be an explicit nil

### UnsetApplicationVersion
`func (o *Receipt) UnsetApplicationVersion()`

UnsetApplicationVersion ensures that no value is present for ApplicationVersion, not even an explicit nil
### GetDownloadId

`func (o *Receipt) GetDownloadId() int64`

GetDownloadId returns the DownloadId field if non-nil, zero value otherwise.

### GetDownloadIdOk

`func (o *Receipt) GetDownloadIdOk() (*int64, bool)`

GetDownloadIdOk returns a tuple with the DownloadId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDownloadId

`func (o *Receipt) SetDownloadId(v int64)`

SetDownloadId sets DownloadId field to given value.

### HasDownloadId

`func (o *Receipt) HasDownloadId() bool`

HasDownloadId returns a boolean if a field has been set.

### GetVersionExternalIdentifier

`func (o *Receipt) GetVersionExternalIdentifier() int32`

GetVersionExternalIdentifier returns the VersionExternalIdentifier field if non-nil, zero value otherwise.

### GetVersionExternalIdentifierOk

`func (o *Receipt) GetVersionExternalIdentifierOk() (*int32, bool)`

GetVersionExternalIdentifierOk returns a tuple with the VersionExternalIdentifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersionExternalIdentifier

`func (o *Receipt) SetVersionExternalIdentifier(v int32)`

SetVersionExternalIdentifier sets VersionExternalIdentifier field to given value.

### HasVersionExternalIdentifier

`func (o *Receipt) HasVersionExternalIdentifier() bool`

HasVersionExternalIdentifier returns a boolean if a field has been set.

### GetReceiptCreationDate

`func (o *Receipt) GetReceiptCreationDate() string`

GetReceiptCreationDate returns the ReceiptCreationDate field if non-nil, zero value otherwise.

### GetReceiptCreationDateOk

`func (o *Receipt) GetReceiptCreationDateOk() (*string, bool)`

GetReceiptCreationDateOk returns a tuple with the ReceiptCreationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiptCreationDate

`func (o *Receipt) SetReceiptCreationDate(v string)`

SetReceiptCreationDate sets ReceiptCreationDate field to given value.

### HasReceiptCreationDate

`func (o *Receipt) HasReceiptCreationDate() bool`

HasReceiptCreationDate returns a boolean if a field has been set.

### SetReceiptCreationDateNil

`func (o *Receipt) SetReceiptCreationDateNil(b bool)`

 SetReceiptCreationDateNil sets the value for ReceiptCreationDate to be an explicit nil

### UnsetReceiptCreationDate
`func (o *Receipt) UnsetReceiptCreationDate()`

UnsetReceiptCreationDate ensures that no value is present for ReceiptCreationDate, not even an explicit nil
### GetReceiptCreationDateMs

`func (o *Receipt) GetReceiptCreationDateMs() string`

GetReceiptCreationDateMs returns the ReceiptCreationDateMs field if non-nil, zero value otherwise.

### GetReceiptCreationDateMsOk

`func (o *Receipt) GetReceiptCreationDateMsOk() (*string, bool)`

GetReceiptCreationDateMsOk returns a tuple with the ReceiptCreationDateMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiptCreationDateMs

`func (o *Receipt) SetReceiptCreationDateMs(v string)`

SetReceiptCreationDateMs sets ReceiptCreationDateMs field to given value.

### HasReceiptCreationDateMs

`func (o *Receipt) HasReceiptCreationDateMs() bool`

HasReceiptCreationDateMs returns a boolean if a field has been set.

### SetReceiptCreationDateMsNil

`func (o *Receipt) SetReceiptCreationDateMsNil(b bool)`

 SetReceiptCreationDateMsNil sets the value for ReceiptCreationDateMs to be an explicit nil

### UnsetReceiptCreationDateMs
`func (o *Receipt) UnsetReceiptCreationDateMs()`

UnsetReceiptCreationDateMs ensures that no value is present for ReceiptCreationDateMs, not even an explicit nil
### GetReceiptCreationDatePst

`func (o *Receipt) GetReceiptCreationDatePst() string`

GetReceiptCreationDatePst returns the ReceiptCreationDatePst field if non-nil, zero value otherwise.

### GetReceiptCreationDatePstOk

`func (o *Receipt) GetReceiptCreationDatePstOk() (*string, bool)`

GetReceiptCreationDatePstOk returns a tuple with the ReceiptCreationDatePst field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiptCreationDatePst

`func (o *Receipt) SetReceiptCreationDatePst(v string)`

SetReceiptCreationDatePst sets ReceiptCreationDatePst field to given value.

### HasReceiptCreationDatePst

`func (o *Receipt) HasReceiptCreationDatePst() bool`

HasReceiptCreationDatePst returns a boolean if a field has been set.

### SetReceiptCreationDatePstNil

`func (o *Receipt) SetReceiptCreationDatePstNil(b bool)`

 SetReceiptCreationDatePstNil sets the value for ReceiptCreationDatePst to be an explicit nil

### UnsetReceiptCreationDatePst
`func (o *Receipt) UnsetReceiptCreationDatePst()`

UnsetReceiptCreationDatePst ensures that no value is present for ReceiptCreationDatePst, not even an explicit nil
### GetRequestDate

`func (o *Receipt) GetRequestDate() string`

GetRequestDate returns the RequestDate field if non-nil, zero value otherwise.

### GetRequestDateOk

`func (o *Receipt) GetRequestDateOk() (*string, bool)`

GetRequestDateOk returns a tuple with the RequestDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestDate

`func (o *Receipt) SetRequestDate(v string)`

SetRequestDate sets RequestDate field to given value.

### HasRequestDate

`func (o *Receipt) HasRequestDate() bool`

HasRequestDate returns a boolean if a field has been set.

### SetRequestDateNil

`func (o *Receipt) SetRequestDateNil(b bool)`

 SetRequestDateNil sets the value for RequestDate to be an explicit nil

### UnsetRequestDate
`func (o *Receipt) UnsetRequestDate()`

UnsetRequestDate ensures that no value is present for RequestDate, not even an explicit nil
### GetRequestDateMs

`func (o *Receipt) GetRequestDateMs() string`

GetRequestDateMs returns the RequestDateMs field if non-nil, zero value otherwise.

### GetRequestDateMsOk

`func (o *Receipt) GetRequestDateMsOk() (*string, bool)`

GetRequestDateMsOk returns a tuple with the RequestDateMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestDateMs

`func (o *Receipt) SetRequestDateMs(v string)`

SetRequestDateMs sets RequestDateMs field to given value.

### HasRequestDateMs

`func (o *Receipt) HasRequestDateMs() bool`

HasRequestDateMs returns a boolean if a field has been set.

### SetRequestDateMsNil

`func (o *Receipt) SetRequestDateMsNil(b bool)`

 SetRequestDateMsNil sets the value for RequestDateMs to be an explicit nil

### UnsetRequestDateMs
`func (o *Receipt) UnsetRequestDateMs()`

UnsetRequestDateMs ensures that no value is present for RequestDateMs, not even an explicit nil
### GetRequestDatePst

`func (o *Receipt) GetRequestDatePst() string`

GetRequestDatePst returns the RequestDatePst field if non-nil, zero value otherwise.

### GetRequestDatePstOk

`func (o *Receipt) GetRequestDatePstOk() (*string, bool)`

GetRequestDatePstOk returns a tuple with the RequestDatePst field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestDatePst

`func (o *Receipt) SetRequestDatePst(v string)`

SetRequestDatePst sets RequestDatePst field to given value.

### HasRequestDatePst

`func (o *Receipt) HasRequestDatePst() bool`

HasRequestDatePst returns a boolean if a field has been set.

### SetRequestDatePstNil

`func (o *Receipt) SetRequestDatePstNil(b bool)`

 SetRequestDatePstNil sets the value for RequestDatePst to be an explicit nil

### UnsetRequestDatePst
`func (o *Receipt) UnsetRequestDatePst()`

UnsetRequestDatePst ensures that no value is present for RequestDatePst, not even an explicit nil
### GetOriginalPurchaseDate

`func (o *Receipt) GetOriginalPurchaseDate() string`

GetOriginalPurchaseDate returns the OriginalPurchaseDate field if non-nil, zero value otherwise.

### GetOriginalPurchaseDateOk

`func (o *Receipt) GetOriginalPurchaseDateOk() (*string, bool)`

GetOriginalPurchaseDateOk returns a tuple with the OriginalPurchaseDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalPurchaseDate

`func (o *Receipt) SetOriginalPurchaseDate(v string)`

SetOriginalPurchaseDate sets OriginalPurchaseDate field to given value.

### HasOriginalPurchaseDate

`func (o *Receipt) HasOriginalPurchaseDate() bool`

HasOriginalPurchaseDate returns a boolean if a field has been set.

### SetOriginalPurchaseDateNil

`func (o *Receipt) SetOriginalPurchaseDateNil(b bool)`

 SetOriginalPurchaseDateNil sets the value for OriginalPurchaseDate to be an explicit nil

### UnsetOriginalPurchaseDate
`func (o *Receipt) UnsetOriginalPurchaseDate()`

UnsetOriginalPurchaseDate ensures that no value is present for OriginalPurchaseDate, not even an explicit nil
### GetOriginalPurchaseDateMs

`func (o *Receipt) GetOriginalPurchaseDateMs() string`

GetOriginalPurchaseDateMs returns the OriginalPurchaseDateMs field if non-nil, zero value otherwise.

### GetOriginalPurchaseDateMsOk

`func (o *Receipt) GetOriginalPurchaseDateMsOk() (*string, bool)`

GetOriginalPurchaseDateMsOk returns a tuple with the OriginalPurchaseDateMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalPurchaseDateMs

`func (o *Receipt) SetOriginalPurchaseDateMs(v string)`

SetOriginalPurchaseDateMs sets OriginalPurchaseDateMs field to given value.

### HasOriginalPurchaseDateMs

`func (o *Receipt) HasOriginalPurchaseDateMs() bool`

HasOriginalPurchaseDateMs returns a boolean if a field has been set.

### SetOriginalPurchaseDateMsNil

`func (o *Receipt) SetOriginalPurchaseDateMsNil(b bool)`

 SetOriginalPurchaseDateMsNil sets the value for OriginalPurchaseDateMs to be an explicit nil

### UnsetOriginalPurchaseDateMs
`func (o *Receipt) UnsetOriginalPurchaseDateMs()`

UnsetOriginalPurchaseDateMs ensures that no value is present for OriginalPurchaseDateMs, not even an explicit nil
### GetOriginalPurchaseDatePst

`func (o *Receipt) GetOriginalPurchaseDatePst() string`

GetOriginalPurchaseDatePst returns the OriginalPurchaseDatePst field if non-nil, zero value otherwise.

### GetOriginalPurchaseDatePstOk

`func (o *Receipt) GetOriginalPurchaseDatePstOk() (*string, bool)`

GetOriginalPurchaseDatePstOk returns a tuple with the OriginalPurchaseDatePst field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalPurchaseDatePst

`func (o *Receipt) SetOriginalPurchaseDatePst(v string)`

SetOriginalPurchaseDatePst sets OriginalPurchaseDatePst field to given value.

### HasOriginalPurchaseDatePst

`func (o *Receipt) HasOriginalPurchaseDatePst() bool`

HasOriginalPurchaseDatePst returns a boolean if a field has been set.

### SetOriginalPurchaseDatePstNil

`func (o *Receipt) SetOriginalPurchaseDatePstNil(b bool)`

 SetOriginalPurchaseDatePstNil sets the value for OriginalPurchaseDatePst to be an explicit nil

### UnsetOriginalPurchaseDatePst
`func (o *Receipt) UnsetOriginalPurchaseDatePst()`

UnsetOriginalPurchaseDatePst ensures that no value is present for OriginalPurchaseDatePst, not even an explicit nil
### GetOriginalApplicationVersion

`func (o *Receipt) GetOriginalApplicationVersion() string`

GetOriginalApplicationVersion returns the OriginalApplicationVersion field if non-nil, zero value otherwise.

### GetOriginalApplicationVersionOk

`func (o *Receipt) GetOriginalApplicationVersionOk() (*string, bool)`

GetOriginalApplicationVersionOk returns a tuple with the OriginalApplicationVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalApplicationVersion

`func (o *Receipt) SetOriginalApplicationVersion(v string)`

SetOriginalApplicationVersion sets OriginalApplicationVersion field to given value.

### HasOriginalApplicationVersion

`func (o *Receipt) HasOriginalApplicationVersion() bool`

HasOriginalApplicationVersion returns a boolean if a field has been set.

### SetOriginalApplicationVersionNil

`func (o *Receipt) SetOriginalApplicationVersionNil(b bool)`

 SetOriginalApplicationVersionNil sets the value for OriginalApplicationVersion to be an explicit nil

### UnsetOriginalApplicationVersion
`func (o *Receipt) UnsetOriginalApplicationVersion()`

UnsetOriginalApplicationVersion ensures that no value is present for OriginalApplicationVersion, not even an explicit nil
### GetInApp

`func (o *Receipt) GetInApp() []InApp`

GetInApp returns the InApp field if non-nil, zero value otherwise.

### GetInAppOk

`func (o *Receipt) GetInAppOk() (*[]InApp, bool)`

GetInAppOk returns a tuple with the InApp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInApp

`func (o *Receipt) SetInApp(v []InApp)`

SetInApp sets InApp field to given value.

### HasInApp

`func (o *Receipt) HasInApp() bool`

HasInApp returns a boolean if a field has been set.

### SetInAppNil

`func (o *Receipt) SetInAppNil(b bool)`

 SetInAppNil sets the value for InApp to be an explicit nil

### UnsetInApp
`func (o *Receipt) UnsetInApp()`

UnsetInApp ensures that no value is present for InApp, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


