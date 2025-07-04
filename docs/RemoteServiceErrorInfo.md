# RemoteServiceErrorInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | Pointer to **NullableString** |  | [optional] 
**Message** | Pointer to **NullableString** |  | [optional] 
**Details** | Pointer to **NullableString** |  | [optional] 
**Data** | Pointer to **map[string]interface{}** |  | [optional] 
**ValidationErrors** | Pointer to [**[]RemoteServiceValidationErrorInfo**](RemoteServiceValidationErrorInfo.md) |  | [optional] 

## Methods

### NewRemoteServiceErrorInfo

`func NewRemoteServiceErrorInfo() *RemoteServiceErrorInfo`

NewRemoteServiceErrorInfo instantiates a new RemoteServiceErrorInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRemoteServiceErrorInfoWithDefaults

`func NewRemoteServiceErrorInfoWithDefaults() *RemoteServiceErrorInfo`

NewRemoteServiceErrorInfoWithDefaults instantiates a new RemoteServiceErrorInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *RemoteServiceErrorInfo) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *RemoteServiceErrorInfo) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *RemoteServiceErrorInfo) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *RemoteServiceErrorInfo) HasCode() bool`

HasCode returns a boolean if a field has been set.

### SetCodeNil

`func (o *RemoteServiceErrorInfo) SetCodeNil(b bool)`

 SetCodeNil sets the value for Code to be an explicit nil

### UnsetCode
`func (o *RemoteServiceErrorInfo) UnsetCode()`

UnsetCode ensures that no value is present for Code, not even an explicit nil
### GetMessage

`func (o *RemoteServiceErrorInfo) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *RemoteServiceErrorInfo) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *RemoteServiceErrorInfo) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *RemoteServiceErrorInfo) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### SetMessageNil

`func (o *RemoteServiceErrorInfo) SetMessageNil(b bool)`

 SetMessageNil sets the value for Message to be an explicit nil

### UnsetMessage
`func (o *RemoteServiceErrorInfo) UnsetMessage()`

UnsetMessage ensures that no value is present for Message, not even an explicit nil
### GetDetails

`func (o *RemoteServiceErrorInfo) GetDetails() string`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *RemoteServiceErrorInfo) GetDetailsOk() (*string, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *RemoteServiceErrorInfo) SetDetails(v string)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *RemoteServiceErrorInfo) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### SetDetailsNil

`func (o *RemoteServiceErrorInfo) SetDetailsNil(b bool)`

 SetDetailsNil sets the value for Details to be an explicit nil

### UnsetDetails
`func (o *RemoteServiceErrorInfo) UnsetDetails()`

UnsetDetails ensures that no value is present for Details, not even an explicit nil
### GetData

`func (o *RemoteServiceErrorInfo) GetData() map[string]interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *RemoteServiceErrorInfo) GetDataOk() (*map[string]interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *RemoteServiceErrorInfo) SetData(v map[string]interface{})`

SetData sets Data field to given value.

### HasData

`func (o *RemoteServiceErrorInfo) HasData() bool`

HasData returns a boolean if a field has been set.

### SetDataNil

`func (o *RemoteServiceErrorInfo) SetDataNil(b bool)`

 SetDataNil sets the value for Data to be an explicit nil

### UnsetData
`func (o *RemoteServiceErrorInfo) UnsetData()`

UnsetData ensures that no value is present for Data, not even an explicit nil
### GetValidationErrors

`func (o *RemoteServiceErrorInfo) GetValidationErrors() []RemoteServiceValidationErrorInfo`

GetValidationErrors returns the ValidationErrors field if non-nil, zero value otherwise.

### GetValidationErrorsOk

`func (o *RemoteServiceErrorInfo) GetValidationErrorsOk() (*[]RemoteServiceValidationErrorInfo, bool)`

GetValidationErrorsOk returns a tuple with the ValidationErrors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidationErrors

`func (o *RemoteServiceErrorInfo) SetValidationErrors(v []RemoteServiceValidationErrorInfo)`

SetValidationErrors sets ValidationErrors field to given value.

### HasValidationErrors

`func (o *RemoteServiceErrorInfo) HasValidationErrors() bool`

HasValidationErrors returns a boolean if a field has been set.

### SetValidationErrorsNil

`func (o *RemoteServiceErrorInfo) SetValidationErrorsNil(b bool)`

 SetValidationErrorsNil sets the value for ValidationErrors to be an explicit nil

### UnsetValidationErrors
`func (o *RemoteServiceErrorInfo) UnsetValidationErrors()`

UnsetValidationErrors ensures that no value is present for ValidationErrors, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


