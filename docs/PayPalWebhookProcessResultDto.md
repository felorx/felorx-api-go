# PayPalWebhookProcessResultDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EventType** | Pointer to **NullableString** |  | [optional]
**ResourceId** | Pointer to **NullableString** |  | [optional]
**Processed** | Pointer to **bool** |  | [optional]

## Methods

### NewPayPalWebhookProcessResultDto

`func NewPayPalWebhookProcessResultDto() *PayPalWebhookProcessResultDto`

NewPayPalWebhookProcessResultDto instantiates a new PayPalWebhookProcessResultDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPayPalWebhookProcessResultDtoWithDefaults

`func NewPayPalWebhookProcessResultDtoWithDefaults() *PayPalWebhookProcessResultDto`

NewPayPalWebhookProcessResultDtoWithDefaults instantiates a new PayPalWebhookProcessResultDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEventType

`func (o *PayPalWebhookProcessResultDto) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *PayPalWebhookProcessResultDto) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *PayPalWebhookProcessResultDto) SetEventType(v string)`

SetEventType sets EventType field to given value.

### HasEventType

`func (o *PayPalWebhookProcessResultDto) HasEventType() bool`

HasEventType returns a boolean if a field has been set.

### SetEventTypeNil

`func (o *PayPalWebhookProcessResultDto) SetEventTypeNil(b bool)`

 SetEventTypeNil sets the value for EventType to be an explicit nil

### UnsetEventType
`func (o *PayPalWebhookProcessResultDto) UnsetEventType()`

UnsetEventType ensures that no value is present for EventType, not even an explicit nil
### GetResourceId

`func (o *PayPalWebhookProcessResultDto) GetResourceId() string`

GetResourceId returns the ResourceId field if non-nil, zero value otherwise.

### GetResourceIdOk

`func (o *PayPalWebhookProcessResultDto) GetResourceIdOk() (*string, bool)`

GetResourceIdOk returns a tuple with the ResourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResourceId

`func (o *PayPalWebhookProcessResultDto) SetResourceId(v string)`

SetResourceId sets ResourceId field to given value.

### HasResourceId

`func (o *PayPalWebhookProcessResultDto) HasResourceId() bool`

HasResourceId returns a boolean if a field has been set.

### SetResourceIdNil

`func (o *PayPalWebhookProcessResultDto) SetResourceIdNil(b bool)`

 SetResourceIdNil sets the value for ResourceId to be an explicit nil

### UnsetResourceId
`func (o *PayPalWebhookProcessResultDto) UnsetResourceId()`

UnsetResourceId ensures that no value is present for ResourceId, not even an explicit nil
### GetProcessed

`func (o *PayPalWebhookProcessResultDto) GetProcessed() bool`

GetProcessed returns the Processed field if non-nil, zero value otherwise.

### GetProcessedOk

`func (o *PayPalWebhookProcessResultDto) GetProcessedOk() (*bool, bool)`

GetProcessedOk returns a tuple with the Processed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessed

`func (o *PayPalWebhookProcessResultDto) SetProcessed(v bool)`

SetProcessed sets Processed field to given value.

### HasProcessed

`func (o *PayPalWebhookProcessResultDto) HasProcessed() bool`

HasProcessed returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


