# \AppFeedbackAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAppFeedback**](AppFeedbackAPI.md#CreateAppFeedback) | **Post** /api/app/app-feedback | 创建反馈（允许匿名用户提交）
[**DeleteAppFeedbackById**](AppFeedbackAPI.md#DeleteAppFeedbackById) | **Delete** /api/app/app-feedback/{id} |
[**GetAppFeedbackById**](AppFeedbackAPI.md#GetAppFeedbackById) | **Get** /api/app/app-feedback/{id} |
[**GetAppFeedbackList**](AppFeedbackAPI.md#GetAppFeedbackList) | **Get** /api/app/app-feedback |
[**MarkAsProcessed**](AppFeedbackAPI.md#MarkAsProcessed) | **Post** /api/app/app-feedback/{id}/mark-as-processed |
[**Reply**](AppFeedbackAPI.md#Reply) | **Post** /api/app/app-feedback/{id}/reply |



## CreateAppFeedback

> AppFeedbackDto CreateAppFeedback(ctx).CreateAppFeedbackDto(createAppFeedbackDto).Execute()

创建反馈（允许匿名用户提交）

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
	createAppFeedbackDto := *openapiclient.NewCreateAppFeedbackDto("AppId_example", "Content_example", openapiclient.AppFeedbackType("Issue")) // CreateAppFeedbackDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppFeedbackAPI.CreateAppFeedback(context.Background()).CreateAppFeedbackDto(createAppFeedbackDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppFeedbackAPI.CreateAppFeedback``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAppFeedback`: AppFeedbackDto
	fmt.Fprintf(os.Stdout, "Response from `AppFeedbackAPI.CreateAppFeedback`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAppFeedbackRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createAppFeedbackDto** | [**CreateAppFeedbackDto**](CreateAppFeedbackDto.md) |  |

### Return type

[**AppFeedbackDto**](AppFeedbackDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteAppFeedbackById

> DeleteAppFeedbackById(ctx, id).Execute()



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AppFeedbackAPI.DeleteAppFeedbackById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppFeedbackAPI.DeleteAppFeedbackById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteAppFeedbackByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


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


## GetAppFeedbackById

> AppFeedbackDto GetAppFeedbackById(ctx, id).Execute()



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppFeedbackAPI.GetAppFeedbackById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppFeedbackAPI.GetAppFeedbackById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAppFeedbackById`: AppFeedbackDto
	fmt.Fprintf(os.Stdout, "Response from `AppFeedbackAPI.GetAppFeedbackById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiGetAppFeedbackByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AppFeedbackDto**](AppFeedbackDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAppFeedbackList

> AppFeedbackDtoPagedResultDto GetAppFeedbackList(ctx).AppId(appId).Type_(type_).Status(status).Sorting(sorting).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()



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
	appId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 应用ID（必填，只有应用创建者可以查看） (optional)
	type_ := openapiclient.AppFeedbackType("Issue") // AppFeedbackType | 反馈类型 (optional)
	status := openapiclient.AppFeedbackStatus("Pending") // AppFeedbackStatus | 反馈状态 (optional)
	sorting := "sorting_example" // string |  (optional)
	skipCount := int32(56) // int32 |  (optional)
	maxResultCount := int32(56) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppFeedbackAPI.GetAppFeedbackList(context.Background()).AppId(appId).Type_(type_).Status(status).Sorting(sorting).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppFeedbackAPI.GetAppFeedbackList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAppFeedbackList`: AppFeedbackDtoPagedResultDto
	fmt.Fprintf(os.Stdout, "Response from `AppFeedbackAPI.GetAppFeedbackList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAppFeedbackListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **appId** | **string** | 应用ID（必填，只有应用创建者可以查看） |
 **type_** | [**AppFeedbackType**](AppFeedbackType.md) | 反馈类型 |
 **status** | [**AppFeedbackStatus**](AppFeedbackStatus.md) | 反馈状态 |
 **sorting** | **string** |  |
 **skipCount** | **int32** |  |
 **maxResultCount** | **int32** |  |

### Return type

[**AppFeedbackDtoPagedResultDto**](AppFeedbackDtoPagedResultDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MarkAsProcessed

> AppFeedbackDto MarkAsProcessed(ctx, id).Execute()



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppFeedbackAPI.MarkAsProcessed(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppFeedbackAPI.MarkAsProcessed``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MarkAsProcessed`: AppFeedbackDto
	fmt.Fprintf(os.Stdout, "Response from `AppFeedbackAPI.MarkAsProcessed`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiMarkAsProcessedRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AppFeedbackDto**](AppFeedbackDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## Reply

> AppFeedbackDto Reply(ctx, id).ReplyAppFeedbackDto(replyAppFeedbackDto).Execute()



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |
	replyAppFeedbackDto := *openapiclient.NewReplyAppFeedbackDto("Reply_example") // ReplyAppFeedbackDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppFeedbackAPI.Reply(context.Background(), id).ReplyAppFeedbackDto(replyAppFeedbackDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppFeedbackAPI.Reply``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Reply`: AppFeedbackDto
	fmt.Fprintf(os.Stdout, "Response from `AppFeedbackAPI.Reply`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiReplyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **replyAppFeedbackDto** | [**ReplyAppFeedbackDto**](ReplyAppFeedbackDto.md) |  |

### Return type

[**AppFeedbackDto**](AppFeedbackDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

