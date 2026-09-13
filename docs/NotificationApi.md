# \NotificationAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Bark**](NotificationAPI.md#Bark) | **Get** /api/app/notification/bark/{apiKey}/{message} | Bark 推送，兼容 Bark 推送协议  TODO: 验证 API KEY 功能, 添加[个人访问令牌]功能
[**GetNotificationList**](NotificationAPI.md#GetNotificationList) | **Get** /api/app/notification | 
[**Push**](NotificationAPI.md#Push) | **Post** /api/app/notification/push | 



## Bark

> Bark(ctx, apiKey, message).AutomaticallyCopy(automaticallyCopy).Copy(copy).Url(url).IsArchive(isArchive).Group(group).Icon(icon).Level(level).Execute()

Bark 推送，兼容 Bark 推送协议  TODO: 验证 API KEY 功能, 添加[个人访问令牌]功能

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/felorx/felorx-api-go"
)

func main() {
	apiKey := "apiKey_example" // string | Bark apiKey, 需要申请，注意不要泄露，泄露后产生安全问题请及时移除或禁用 apiKey
	message := "message_example" // string | 消息内容
	automaticallyCopy := int32(56) // int32 | 携带参数 automaticallyCopy=1， 收到推送时，推送内容会自动复制到粘贴板（如发现不能自动复制，可尝试重启一下手机） (optional) (default to 0)
	copy := "copy_example" // string | 携带copy参数， 则上面两种复制操作，将只复制copy参数的值 (optional)
	url := "url_example" // string | 点击推送将跳转到url的地址（发送时，URL参数需要编码） (optional)
	isArchive := "isArchive_example" // string | 指定是否需要保存推送信息到历史记录，1 为保存，其他值为不保存。\\n如果不指定这个参数，推送信息将按照APP内设置来决定是否保存。 (optional)
	group := "group_example" // string | 指定推送消息分组，可在历史记录中按分组查看推送。 (optional)
	icon := "icon_example" // string | 指定推送消息图标, icon (仅 iOS15 或以上支持） (optional)
	level := "level_example" // string | 设置时效性通知 active：不设置时的默认值，系统会立即亮屏显示通知。\\ntimeSensitive：时效性通知，可在专注状态下显示通知。\\npassive：仅将通知添加到通知列表，不会亮屏提醒 (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.NotificationAPI.Bark(context.Background(), apiKey, message).AutomaticallyCopy(automaticallyCopy).Copy(copy).Url(url).IsArchive(isArchive).Group(group).Icon(icon).Level(level).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NotificationAPI.Bark``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**apiKey** | **string** | Bark apiKey, 需要申请，注意不要泄露，泄露后产生安全问题请及时移除或禁用 apiKey | 
**message** | **string** | 消息内容 | 

### Other Parameters

Other parameters are passed through a pointer to a apiBarkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **automaticallyCopy** | **int32** | 携带参数 automaticallyCopy&#x3D;1， 收到推送时，推送内容会自动复制到粘贴板（如发现不能自动复制，可尝试重启一下手机） | [default to 0]
 **copy** | **string** | 携带copy参数， 则上面两种复制操作，将只复制copy参数的值 | 
 **url** | **string** | 点击推送将跳转到url的地址（发送时，URL参数需要编码） | 
 **isArchive** | **string** | 指定是否需要保存推送信息到历史记录，1 为保存，其他值为不保存。\\n如果不指定这个参数，推送信息将按照APP内设置来决定是否保存。 | 
 **group** | **string** | 指定推送消息分组，可在历史记录中按分组查看推送。 | 
 **icon** | **string** | 指定推送消息图标, icon (仅 iOS15 或以上支持） | 
 **level** | **string** | 设置时效性通知 active：不设置时的默认值，系统会立即亮屏显示通知。\\ntimeSensitive：时效性通知，可在专注状态下显示通知。\\npassive：仅将通知添加到通知列表，不会亮屏提醒 | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetNotificationList

> NotificationInfoDtoPagedResultDto GetNotificationList(ctx).Sorting(sorting).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/felorx/felorx-api-go"
)

func main() {
	sorting := "sorting_example" // string |  (optional)
	skipCount := int32(56) // int32 |  (optional)
	maxResultCount := int32(56) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NotificationAPI.GetNotificationList(context.Background()).Sorting(sorting).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NotificationAPI.GetNotificationList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetNotificationList`: NotificationInfoDtoPagedResultDto
	fmt.Fprintf(os.Stdout, "Response from `NotificationAPI.GetNotificationList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetNotificationListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sorting** | **string** |  | 
 **skipCount** | **int32** |  | 
 **maxResultCount** | **int32** |  | 

### Return type

[**NotificationInfoDtoPagedResultDto**](NotificationInfoDtoPagedResultDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## Push

> Push(ctx).CreatePushNotificationDto(createPushNotificationDto).Execute()



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/felorx/felorx-api-go"
)

func main() {
	createPushNotificationDto := *openapiclient.NewCreatePushNotificationDto() // CreatePushNotificationDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.NotificationAPI.Push(context.Background()).CreatePushNotificationDto(createPushNotificationDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NotificationAPI.Push``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPushRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createPushNotificationDto** | [**CreatePushNotificationDto**](CreatePushNotificationDto.md) |  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

