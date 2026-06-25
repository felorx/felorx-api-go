# \AppFeatureAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAppFeature**](AppFeatureAPI.md#CreateAppFeature) | **Post** /api/app/app-feature |
[**DeleteAppFeatureById**](AppFeatureAPI.md#DeleteAppFeatureById) | **Delete** /api/app/app-feature/{id} |
[**GetAppFeatureList**](AppFeatureAPI.md#GetAppFeatureList) | **Get** /api/app/app-feature |
[**UpdateAppFeature**](AppFeatureAPI.md#UpdateAppFeature) | **Put** /api/app/app-feature/{id} |



## CreateAppFeature

> AppFeatureDto CreateAppFeature(ctx).CreateOrUpdateAppFeatureDto(createOrUpdateAppFeatureDto).Execute()



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
	createOrUpdateAppFeatureDto := *openapiclient.NewCreateOrUpdateAppFeatureDto() // CreateOrUpdateAppFeatureDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppFeatureAPI.CreateAppFeature(context.Background()).CreateOrUpdateAppFeatureDto(createOrUpdateAppFeatureDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppFeatureAPI.CreateAppFeature``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAppFeature`: AppFeatureDto
	fmt.Fprintf(os.Stdout, "Response from `AppFeatureAPI.CreateAppFeature`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAppFeatureRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createOrUpdateAppFeatureDto** | [**CreateOrUpdateAppFeatureDto**](CreateOrUpdateAppFeatureDto.md) |  |

### Return type

[**AppFeatureDto**](AppFeatureDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteAppFeatureById

> DeleteAppFeatureById(ctx, id).Execute()



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
	r, err := apiClient.AppFeatureAPI.DeleteAppFeatureById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppFeatureAPI.DeleteAppFeatureById``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteAppFeatureByIdRequest struct via the builder pattern


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


## GetAppFeatureList

> AppFeatureDtoPagedResultDto GetAppFeatureList(ctx).AppId(appId).Sorting(sorting).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()



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
	sorting := "sorting_example" // string |  (optional)
	skipCount := int32(56) // int32 |  (optional)
	maxResultCount := int32(56) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppFeatureAPI.GetAppFeatureList(context.Background()).AppId(appId).Sorting(sorting).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppFeatureAPI.GetAppFeatureList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAppFeatureList`: AppFeatureDtoPagedResultDto
	fmt.Fprintf(os.Stdout, "Response from `AppFeatureAPI.GetAppFeatureList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAppFeatureListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **appId** | **string** |  |
 **sorting** | **string** |  |
 **skipCount** | **int32** |  |
 **maxResultCount** | **int32** |  |

### Return type

[**AppFeatureDtoPagedResultDto**](AppFeatureDtoPagedResultDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAppFeature

> AppFeatureDto UpdateAppFeature(ctx, id).CreateOrUpdateAppFeatureDto(createOrUpdateAppFeatureDto).Execute()



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
	createOrUpdateAppFeatureDto := *openapiclient.NewCreateOrUpdateAppFeatureDto() // CreateOrUpdateAppFeatureDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppFeatureAPI.UpdateAppFeature(context.Background(), id).CreateOrUpdateAppFeatureDto(createOrUpdateAppFeatureDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppFeatureAPI.UpdateAppFeature``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateAppFeature`: AppFeatureDto
	fmt.Fprintf(os.Stdout, "Response from `AppFeatureAPI.UpdateAppFeature`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAppFeatureRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createOrUpdateAppFeatureDto** | [**CreateOrUpdateAppFeatureDto**](CreateOrUpdateAppFeatureDto.md) |  |

### Return type

[**AppFeatureDto**](AppFeatureDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

