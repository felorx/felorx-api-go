# \AppSdkAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAppSdk**](AppSdkAPI.md#CreateAppSdk) | **Post** /api/app/app-sdk | 
[**DeleteAppSdkById**](AppSdkAPI.md#DeleteAppSdkById) | **Delete** /api/app/app-sdk/{id} | 
[**GetAppSdkList**](AppSdkAPI.md#GetAppSdkList) | **Get** /api/app/app-sdk | 
[**UpdateAppSdk**](AppSdkAPI.md#UpdateAppSdk) | **Put** /api/app/app-sdk/{id} | 



## CreateAppSdk

> AppSdkDto CreateAppSdk(ctx).CreateOrUpdateAppSdkDto(createOrUpdateAppSdkDto).Execute()



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
	createOrUpdateAppSdkDto := *openapiclient.NewCreateOrUpdateAppSdkDto() // CreateOrUpdateAppSdkDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppSdkAPI.CreateAppSdk(context.Background()).CreateOrUpdateAppSdkDto(createOrUpdateAppSdkDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppSdkAPI.CreateAppSdk``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAppSdk`: AppSdkDto
	fmt.Fprintf(os.Stdout, "Response from `AppSdkAPI.CreateAppSdk`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAppSdkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createOrUpdateAppSdkDto** | [**CreateOrUpdateAppSdkDto**](CreateOrUpdateAppSdkDto.md) |  | 

### Return type

[**AppSdkDto**](AppSdkDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteAppSdkById

> DeleteAppSdkById(ctx, id).Execute()



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
	r, err := apiClient.AppSdkAPI.DeleteAppSdkById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppSdkAPI.DeleteAppSdkById``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteAppSdkByIdRequest struct via the builder pattern


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


## GetAppSdkList

> AppSdkDtoPagedResultDto GetAppSdkList(ctx).Filter(filter).Sorting(sorting).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()



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
	filter := "filter_example" // string | 关键词：匹配名称、描述、隐私说明、主页等字段（包含匹配）。 (optional)
	sorting := "sorting_example" // string |  (optional)
	skipCount := int32(56) // int32 |  (optional)
	maxResultCount := int32(56) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppSdkAPI.GetAppSdkList(context.Background()).Filter(filter).Sorting(sorting).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppSdkAPI.GetAppSdkList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAppSdkList`: AppSdkDtoPagedResultDto
	fmt.Fprintf(os.Stdout, "Response from `AppSdkAPI.GetAppSdkList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAppSdkListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **string** | 关键词：匹配名称、描述、隐私说明、主页等字段（包含匹配）。 | 
 **sorting** | **string** |  | 
 **skipCount** | **int32** |  | 
 **maxResultCount** | **int32** |  | 

### Return type

[**AppSdkDtoPagedResultDto**](AppSdkDtoPagedResultDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAppSdk

> AppSdkDto UpdateAppSdk(ctx, id).CreateOrUpdateAppSdkDto(createOrUpdateAppSdkDto).Execute()



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
	createOrUpdateAppSdkDto := *openapiclient.NewCreateOrUpdateAppSdkDto() // CreateOrUpdateAppSdkDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppSdkAPI.UpdateAppSdk(context.Background(), id).CreateOrUpdateAppSdkDto(createOrUpdateAppSdkDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppSdkAPI.UpdateAppSdk``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateAppSdk`: AppSdkDto
	fmt.Fprintf(os.Stdout, "Response from `AppSdkAPI.UpdateAppSdk`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAppSdkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createOrUpdateAppSdkDto** | [**CreateOrUpdateAppSdkDto**](CreateOrUpdateAppSdkDto.md) |  | 

### Return type

[**AppSdkDto**](AppSdkDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

