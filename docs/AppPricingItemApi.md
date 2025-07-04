# \AppPricingItemAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAppPricingItem**](AppPricingItemAPI.md#CreateAppPricingItem) | **Post** /api/app/app-pricing-item | 
[**DeleteAppPricingItemById**](AppPricingItemAPI.md#DeleteAppPricingItemById) | **Delete** /api/app/app-pricing-item/{id} | 
[**GetAppPricingItemById**](AppPricingItemAPI.md#GetAppPricingItemById) | **Get** /api/app/app-pricing-item/{id} | 
[**GetAppPricingItemList**](AppPricingItemAPI.md#GetAppPricingItemList) | **Get** /api/app/app-pricing-item | 
[**UpdateAppPricingItem**](AppPricingItemAPI.md#UpdateAppPricingItem) | **Put** /api/app/app-pricing-item/{id} | 



## CreateAppPricingItem

> AppPricingItemDto CreateAppPricingItem(ctx).CreateOrUpdateAppPricingItemDto(createOrUpdateAppPricingItemDto).Execute()



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/puupee/puupee-api-go"
)

func main() {
	createOrUpdateAppPricingItemDto := *openapiclient.NewCreateOrUpdateAppPricingItemDto() // CreateOrUpdateAppPricingItemDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppPricingItemAPI.CreateAppPricingItem(context.Background()).CreateOrUpdateAppPricingItemDto(createOrUpdateAppPricingItemDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppPricingItemAPI.CreateAppPricingItem``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAppPricingItem`: AppPricingItemDto
	fmt.Fprintf(os.Stdout, "Response from `AppPricingItemAPI.CreateAppPricingItem`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAppPricingItemRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createOrUpdateAppPricingItemDto** | [**CreateOrUpdateAppPricingItemDto**](CreateOrUpdateAppPricingItemDto.md) |  | 

### Return type

[**AppPricingItemDto**](AppPricingItemDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteAppPricingItemById

> DeleteAppPricingItemById(ctx, id).Execute()



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/puupee/puupee-api-go"
)

func main() {
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AppPricingItemAPI.DeleteAppPricingItemById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppPricingItemAPI.DeleteAppPricingItemById``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteAppPricingItemByIdRequest struct via the builder pattern


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


## GetAppPricingItemById

> AppPricingItemDto GetAppPricingItemById(ctx, id).Execute()



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/puupee/puupee-api-go"
)

func main() {
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppPricingItemAPI.GetAppPricingItemById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppPricingItemAPI.GetAppPricingItemById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAppPricingItemById`: AppPricingItemDto
	fmt.Fprintf(os.Stdout, "Response from `AppPricingItemAPI.GetAppPricingItemById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAppPricingItemByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AppPricingItemDto**](AppPricingItemDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAppPricingItemList

> []AppPricingItemDto GetAppPricingItemList(ctx).Execute()



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/puupee/puupee-api-go"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppPricingItemAPI.GetAppPricingItemList(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppPricingItemAPI.GetAppPricingItemList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAppPricingItemList`: []AppPricingItemDto
	fmt.Fprintf(os.Stdout, "Response from `AppPricingItemAPI.GetAppPricingItemList`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetAppPricingItemListRequest struct via the builder pattern


### Return type

[**[]AppPricingItemDto**](AppPricingItemDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAppPricingItem

> AppPricingItemDto UpdateAppPricingItem(ctx, id).CreateOrUpdateAppPricingItemDto(createOrUpdateAppPricingItemDto).Execute()



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/puupee/puupee-api-go"
)

func main() {
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	createOrUpdateAppPricingItemDto := *openapiclient.NewCreateOrUpdateAppPricingItemDto() // CreateOrUpdateAppPricingItemDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppPricingItemAPI.UpdateAppPricingItem(context.Background(), id).CreateOrUpdateAppPricingItemDto(createOrUpdateAppPricingItemDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppPricingItemAPI.UpdateAppPricingItem``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateAppPricingItem`: AppPricingItemDto
	fmt.Fprintf(os.Stdout, "Response from `AppPricingItemAPI.UpdateAppPricingItem`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAppPricingItemRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createOrUpdateAppPricingItemDto** | [**CreateOrUpdateAppPricingItemDto**](CreateOrUpdateAppPricingItemDto.md) |  | 

### Return type

[**AppPricingItemDto**](AppPricingItemDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

