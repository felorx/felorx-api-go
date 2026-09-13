# FelorxResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Object** | **string** |  | 
**Model** | Pointer to **string** |  | [optional] 
**Status** | **string** |  | 
**Output** | **[]map[string]interface{}** |  | 
**CreatedAt** | Pointer to **int64** |  | [optional] 
**PreviousResponseId** | Pointer to **NullableString** |  | [optional] 
**Usage** | Pointer to [**FelorxResponseUsage**](FelorxResponseUsage.md) |  | [optional] 
**Error** | Pointer to **map[string]interface{}** |  | [optional] 
**IncompleteDetails** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewFelorxResponse

`func NewFelorxResponse(id string, object string, status string, output []map[string]interface{}, ) *FelorxResponse`

NewFelorxResponse instantiates a new FelorxResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFelorxResponseWithDefaults

`func NewFelorxResponseWithDefaults() *FelorxResponse`

NewFelorxResponseWithDefaults instantiates a new FelorxResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *FelorxResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *FelorxResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *FelorxResponse) SetId(v string)`

SetId sets Id field to given value.


### GetObject

`func (o *FelorxResponse) GetObject() string`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *FelorxResponse) GetObjectOk() (*string, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *FelorxResponse) SetObject(v string)`

SetObject sets Object field to given value.


### GetModel

`func (o *FelorxResponse) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *FelorxResponse) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *FelorxResponse) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *FelorxResponse) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetStatus

`func (o *FelorxResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *FelorxResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *FelorxResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetOutput

`func (o *FelorxResponse) GetOutput() []map[string]interface{}`

GetOutput returns the Output field if non-nil, zero value otherwise.

### GetOutputOk

`func (o *FelorxResponse) GetOutputOk() (*[]map[string]interface{}, bool)`

GetOutputOk returns a tuple with the Output field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutput

`func (o *FelorxResponse) SetOutput(v []map[string]interface{})`

SetOutput sets Output field to given value.


### GetCreatedAt

`func (o *FelorxResponse) GetCreatedAt() int64`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *FelorxResponse) GetCreatedAtOk() (*int64, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *FelorxResponse) SetCreatedAt(v int64)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *FelorxResponse) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetPreviousResponseId

`func (o *FelorxResponse) GetPreviousResponseId() string`

GetPreviousResponseId returns the PreviousResponseId field if non-nil, zero value otherwise.

### GetPreviousResponseIdOk

`func (o *FelorxResponse) GetPreviousResponseIdOk() (*string, bool)`

GetPreviousResponseIdOk returns a tuple with the PreviousResponseId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviousResponseId

`func (o *FelorxResponse) SetPreviousResponseId(v string)`

SetPreviousResponseId sets PreviousResponseId field to given value.

### HasPreviousResponseId

`func (o *FelorxResponse) HasPreviousResponseId() bool`

HasPreviousResponseId returns a boolean if a field has been set.

### SetPreviousResponseIdNil

`func (o *FelorxResponse) SetPreviousResponseIdNil(b bool)`

 SetPreviousResponseIdNil sets the value for PreviousResponseId to be an explicit nil

### UnsetPreviousResponseId
`func (o *FelorxResponse) UnsetPreviousResponseId()`

UnsetPreviousResponseId ensures that no value is present for PreviousResponseId, not even an explicit nil
### GetUsage

`func (o *FelorxResponse) GetUsage() FelorxResponseUsage`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *FelorxResponse) GetUsageOk() (*FelorxResponseUsage, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *FelorxResponse) SetUsage(v FelorxResponseUsage)`

SetUsage sets Usage field to given value.

### HasUsage

`func (o *FelorxResponse) HasUsage() bool`

HasUsage returns a boolean if a field has been set.

### GetError

`func (o *FelorxResponse) GetError() map[string]interface{}`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *FelorxResponse) GetErrorOk() (*map[string]interface{}, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *FelorxResponse) SetError(v map[string]interface{})`

SetError sets Error field to given value.

### HasError

`func (o *FelorxResponse) HasError() bool`

HasError returns a boolean if a field has been set.

### GetIncompleteDetails

`func (o *FelorxResponse) GetIncompleteDetails() map[string]interface{}`

GetIncompleteDetails returns the IncompleteDetails field if non-nil, zero value otherwise.

### GetIncompleteDetailsOk

`func (o *FelorxResponse) GetIncompleteDetailsOk() (*map[string]interface{}, bool)`

GetIncompleteDetailsOk returns a tuple with the IncompleteDetails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncompleteDetails

`func (o *FelorxResponse) SetIncompleteDetails(v map[string]interface{})`

SetIncompleteDetails sets IncompleteDetails field to given value.

### HasIncompleteDetails

`func (o *FelorxResponse) HasIncompleteDetails() bool`

HasIncompleteDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


