# TimeZone

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Iana** | Pointer to [**IanaTimeZone**](IanaTimeZone.md) |  | [optional] 
**Windows** | Pointer to [**WindowsTimeZone**](WindowsTimeZone.md) |  | [optional] 

## Methods

### NewTimeZone

`func NewTimeZone() *TimeZone`

NewTimeZone instantiates a new TimeZone object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTimeZoneWithDefaults

`func NewTimeZoneWithDefaults() *TimeZone`

NewTimeZoneWithDefaults instantiates a new TimeZone object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIana

`func (o *TimeZone) GetIana() IanaTimeZone`

GetIana returns the Iana field if non-nil, zero value otherwise.

### GetIanaOk

`func (o *TimeZone) GetIanaOk() (*IanaTimeZone, bool)`

GetIanaOk returns a tuple with the Iana field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIana

`func (o *TimeZone) SetIana(v IanaTimeZone)`

SetIana sets Iana field to given value.

### HasIana

`func (o *TimeZone) HasIana() bool`

HasIana returns a boolean if a field has been set.

### GetWindows

`func (o *TimeZone) GetWindows() WindowsTimeZone`

GetWindows returns the Windows field if non-nil, zero value otherwise.

### GetWindowsOk

`func (o *TimeZone) GetWindowsOk() (*WindowsTimeZone, bool)`

GetWindowsOk returns a tuple with the Windows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindows

`func (o *TimeZone) SetWindows(v WindowsTimeZone)`

SetWindows sets Windows field to given value.

### HasWindows

`func (o *TimeZone) HasWindows() bool`

HasWindows returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


