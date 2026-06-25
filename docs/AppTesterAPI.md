# \AppTesterAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CheckIsAppTester**](AppTesterAPI.md#CheckIsAppTester) | **Post** /api/app/app-tester/check-is-app-tester | 检查用户是否是内测用户
[**CreateAppTester**](AppTesterAPI.md#CreateAppTester) | **Post** /api/app/app-tester | 创建内测用户
[**DeleteAppTesterById**](AppTesterAPI.md#DeleteAppTesterById) | **Delete** /api/app/app-tester/{id} | 删除内测用户
[**GetAppTesterById**](AppTesterAPI.md#GetAppTesterById) | **Get** /api/app/app-tester/{id} | 获取内测用户
[**GetAppTesterList**](AppTesterAPI.md#GetAppTesterList) | **Get** /api/app/app-tester | 获取内测用户列表
[**UpdateAppTester**](AppTesterAPI.md#UpdateAppTester) | **Put** /api/app/app-tester/{id} | 更新内测用户



## CheckIsAppTester

> bool CheckIsAppTester(ctx).AppId(appId).UserId(userId).Execute()

检查用户是否是内测用户

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
	appId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppTesterAPI.CheckIsAppTester(context.Background()).AppId(appId).UserId(userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppTesterAPI.CheckIsAppTester``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CheckIsAppTester`: bool
	fmt.Fprintf(os.Stdout, "Response from `AppTesterAPI.CheckIsAppTester`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCheckIsAppTesterRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **appId** | **string** |  | 
 **userId** | **string** |  | 

### Return type

**bool**

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateAppTester

> AppTesterDto CreateAppTester(ctx).CreateUpdateAppTesterDto(createUpdateAppTesterDto).Execute()

创建内测用户

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
	createUpdateAppTesterDto := *openapiclient.NewCreateUpdateAppTesterDto() // CreateUpdateAppTesterDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppTesterAPI.CreateAppTester(context.Background()).CreateUpdateAppTesterDto(createUpdateAppTesterDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppTesterAPI.CreateAppTester``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAppTester`: AppTesterDto
	fmt.Fprintf(os.Stdout, "Response from `AppTesterAPI.CreateAppTester`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAppTesterRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createUpdateAppTesterDto** | [**CreateUpdateAppTesterDto**](CreateUpdateAppTesterDto.md) |  | 

### Return type

[**AppTesterDto**](AppTesterDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteAppTesterById

> DeleteAppTesterById(ctx, id).Execute()

删除内测用户

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
	r, err := apiClient.AppTesterAPI.DeleteAppTesterById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppTesterAPI.DeleteAppTesterById``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteAppTesterByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAppTesterById

> AppTesterDto GetAppTesterById(ctx, id).Execute()

获取内测用户

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
	resp, r, err := apiClient.AppTesterAPI.GetAppTesterById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppTesterAPI.GetAppTesterById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAppTesterById`: AppTesterDto
	fmt.Fprintf(os.Stdout, "Response from `AppTesterAPI.GetAppTesterById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAppTesterByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AppTesterDto**](AppTesterDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAppTesterList

> AppTesterDtoPagedResultDto GetAppTesterList(ctx).Sorting(sorting).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()

获取内测用户列表

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
	resp, r, err := apiClient.AppTesterAPI.GetAppTesterList(context.Background()).Sorting(sorting).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppTesterAPI.GetAppTesterList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAppTesterList`: AppTesterDtoPagedResultDto
	fmt.Fprintf(os.Stdout, "Response from `AppTesterAPI.GetAppTesterList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAppTesterListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sorting** | **string** |  | 
 **skipCount** | **int32** |  | 
 **maxResultCount** | **int32** |  | 

### Return type

[**AppTesterDtoPagedResultDto**](AppTesterDtoPagedResultDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAppTester

> AppTesterDto UpdateAppTester(ctx, id).CreateUpdateAppTesterDto(createUpdateAppTesterDto).Execute()

更新内测用户

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
	createUpdateAppTesterDto := *openapiclient.NewCreateUpdateAppTesterDto() // CreateUpdateAppTesterDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppTesterAPI.UpdateAppTester(context.Background(), id).CreateUpdateAppTesterDto(createUpdateAppTesterDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppTesterAPI.UpdateAppTester``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateAppTester`: AppTesterDto
	fmt.Fprintf(os.Stdout, "Response from `AppTesterAPI.UpdateAppTester`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAppTesterRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createUpdateAppTesterDto** | [**CreateUpdateAppTesterDto**](CreateUpdateAppTesterDto.md) |  | 

### Return type

[**AppTesterDto**](AppTesterDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

