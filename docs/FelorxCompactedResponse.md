# FelorxCompactedResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Object** | **string** |  | 
**CreatedAt** | **int64** |  | 
**Output** | **[]map[string]interface{}** |  | 
**Usage** | [**FelorxResponseUsage**](FelorxResponseUsage.md) |  | 

## Methods

### NewFelorxCompactedResponse

`func NewFelorxCompactedResponse(id string, object string, createdAt int64, output []map[string]interface{}, usage FelorxResponseUsage, ) *FelorxCompactedResponse`

NewFelorxCompactedResponse instantiates a new FelorxCompactedResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFelorxCompactedResponseWithDefaults

`func NewFelorxCompactedResponseWithDefaults() *FelorxCompactedResponse`

NewFelorxCompactedResponseWithDefaults instantiates a new FelorxCompactedResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *FelorxCompactedResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *FelorxCompactedResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *FelorxCompactedResponse) SetId(v string)`

SetId sets Id field to given value.


### GetObject

`func (o *FelorxCompactedResponse) GetObject() string`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *FelorxCompactedResponse) GetObjectOk() (*string, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *FelorxCompactedResponse) SetObject(v string)`

SetObject sets Object field to given value.


### GetCreatedAt

`func (o *FelorxCompactedResponse) GetCreatedAt() int64`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *FelorxCompactedResponse) GetCreatedAtOk() (*int64, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *FelorxCompactedResponse) SetCreatedAt(v int64)`

SetCreatedAt sets CreatedAt field to given value.


### GetOutput

`func (o *FelorxCompactedResponse) GetOutput() []map[string]interface{}`

GetOutput returns the Output field if non-nil, zero value otherwise.

### GetOutputOk

`func (o *FelorxCompactedResponse) GetOutputOk() (*[]map[string]interface{}, bool)`

GetOutputOk returns a tuple with the Output field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutput

`func (o *FelorxCompactedResponse) SetOutput(v []map[string]interface{})`

SetOutput sets Output field to given value.


### GetUsage

`func (o *FelorxCompactedResponse) GetUsage() FelorxResponseUsage`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *FelorxCompactedResponse) GetUsageOk() (*FelorxResponseUsage, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *FelorxCompactedResponse) SetUsage(v FelorxResponseUsage)`

SetUsage sets Usage field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


