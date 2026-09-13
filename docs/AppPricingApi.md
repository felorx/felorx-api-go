# \AppPricingAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAppPricing**](AppPricingAPI.md#CreateAppPricing) | **Post** /api/app/app-pricing | 
[**DeleteAppPricingById**](AppPricingAPI.md#DeleteAppPricingById) | **Delete** /api/app/app-pricing/{id} | 
[**GetAppPricingById**](AppPricingAPI.md#GetAppPricingById) | **Get** /api/app/app-pricing/{id} | 获取单条定价方案详情，允许匿名访问（与列表/商店展示一致）
[**GetAppPricingList**](AppPricingAPI.md#GetAppPricingList) | **Get** /api/app/app-pricing | 分页获取定价方案列表，允许匿名访问
[**GetListByAppIdGetApiAppAppPricingByAppIdAppId**](AppPricingAPI.md#GetListByAppIdGetApiAppAppPricingByAppIdAppId) | **Get** /api/app/app-pricing/by-app-id/{appId} | 获取应用定价方案列表，允许匿名访问供未登录用户查看订阅计划
[**GetPricingItemsByAppId**](AppPricingAPI.md#GetPricingItemsByAppId) | **Get** /api/app/app-pricing/pricing-items-by-app-id/{appId} | 获取应用定价功能项定义（与客户端「功能对比」行一致），允许匿名访问供官网等场景展示
[**UpdateAppPricing**](AppPricingAPI.md#UpdateAppPricing) | **Put** /api/app/app-pricing/{id} | 



## CreateAppPricing

> AppPricingDto CreateAppPricing(ctx).CreateOrUpdateAppPricingDto(createOrUpdateAppPricingDto).Execute()



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
	createOrUpdateAppPricingDto := *openapiclient.NewCreateOrUpdateAppPricingDto() // CreateOrUpdateAppPricingDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppPricingAPI.CreateAppPricing(context.Background()).CreateOrUpdateAppPricingDto(createOrUpdateAppPricingDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppPricingAPI.CreateAppPricing``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAppPricing`: AppPricingDto
	fmt.Fprintf(os.Stdout, "Response from `AppPricingAPI.CreateAppPricing`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAppPricingRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createOrUpdateAppPricingDto** | [**CreateOrUpdateAppPricingDto**](CreateOrUpdateAppPricingDto.md) |  | 

### Return type

[**AppPricingDto**](AppPricingDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteAppPricingById

> DeleteAppPricingById(ctx, id).Execute()



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
	r, err := apiClient.AppPricingAPI.DeleteAppPricingById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppPricingAPI.DeleteAppPricingById``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteAppPricingByIdRequest struct via the builder pattern


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


## GetAppPricingById

> AppPricingDto GetAppPricingById(ctx, id).Execute()

获取单条定价方案详情，允许匿名访问（与列表/商店展示一致）

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
	resp, r, err := apiClient.AppPricingAPI.GetAppPricingById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppPricingAPI.GetAppPricingById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAppPricingById`: AppPricingDto
	fmt.Fprintf(os.Stdout, "Response from `AppPricingAPI.GetAppPricingById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAppPricingByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AppPricingDto**](AppPricingDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAppPricingList

> AppPricingDtoPagedResultDto GetAppPricingList(ctx).Sorting(sorting).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()

分页获取定价方案列表，允许匿名访问

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
	resp, r, err := apiClient.AppPricingAPI.GetAppPricingList(context.Background()).Sorting(sorting).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppPricingAPI.GetAppPricingList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAppPricingList`: AppPricingDtoPagedResultDto
	fmt.Fprintf(os.Stdout, "Response from `AppPricingAPI.GetAppPricingList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAppPricingListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sorting** | **string** |  | 
 **skipCount** | **int32** |  | 
 **maxResultCount** | **int32** |  | 

### Return type

[**AppPricingDtoPagedResultDto**](AppPricingDtoPagedResultDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetListByAppIdGetApiAppAppPricingByAppIdAppId

> []AppPricingDto GetListByAppIdGetApiAppAppPricingByAppIdAppId(ctx, appId).Execute()

获取应用定价方案列表，允许匿名访问供未登录用户查看订阅计划

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
	appId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppPricingAPI.GetListByAppIdGetApiAppAppPricingByAppIdAppId(context.Background(), appId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppPricingAPI.GetListByAppIdGetApiAppAppPricingByAppIdAppId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetListByAppIdGetApiAppAppPricingByAppIdAppId`: []AppPricingDto
	fmt.Fprintf(os.Stdout, "Response from `AppPricingAPI.GetListByAppIdGetApiAppAppPricingByAppIdAppId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**appId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetListByAppIdGetApiAppAppPricingByAppIdAppIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]AppPricingDto**](AppPricingDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPricingItemsByAppId

> []AppPricingItemDto GetPricingItemsByAppId(ctx, appId).Execute()

获取应用定价功能项定义（与客户端「功能对比」行一致），允许匿名访问供官网等场景展示

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
	appId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppPricingAPI.GetPricingItemsByAppId(context.Background(), appId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppPricingAPI.GetPricingItemsByAppId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPricingItemsByAppId`: []AppPricingItemDto
	fmt.Fprintf(os.Stdout, "Response from `AppPricingAPI.GetPricingItemsByAppId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**appId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPricingItemsByAppIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]AppPricingItemDto**](AppPricingItemDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAppPricing

> AppPricingDto UpdateAppPricing(ctx, id).CreateOrUpdateAppPricingDto(createOrUpdateAppPricingDto).Execute()



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
	createOrUpdateAppPricingDto := *openapiclient.NewCreateOrUpdateAppPricingDto() // CreateOrUpdateAppPricingDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppPricingAPI.UpdateAppPricing(context.Background(), id).CreateOrUpdateAppPricingDto(createOrUpdateAppPricingDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppPricingAPI.UpdateAppPricing``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateAppPricing`: AppPricingDto
	fmt.Fprintf(os.Stdout, "Response from `AppPricingAPI.UpdateAppPricing`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAppPricingRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createOrUpdateAppPricingDto** | [**CreateOrUpdateAppPricingDto**](CreateOrUpdateAppPricingDto.md) |  | 

### Return type

[**AppPricingDto**](AppPricingDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

