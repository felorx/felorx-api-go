# \AppAssetAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAppAsset**](AppAssetAPI.md#CreateAppAsset) | **Post** /api/app/app-asset |
[**DeleteAppAssetById**](AppAssetAPI.md#DeleteAppAssetById) | **Delete** /api/app/app-asset/{id} |
[**GetListByAppLocaleId**](AppAssetAPI.md#GetListByAppLocaleId) | **Get** /api/app/app-asset/by-app-locale-id/{appLocaleId} |
[**UpdateAppAsset**](AppAssetAPI.md#UpdateAppAsset) | **Put** /api/app/app-asset/{id} |



## CreateAppAsset

> AppAssetDto CreateAppAsset(ctx).CreateOrUpdateAppAssetDto(createOrUpdateAppAssetDto).Execute()



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
	createOrUpdateAppAssetDto := *openapiclient.NewCreateOrUpdateAppAssetDto() // CreateOrUpdateAppAssetDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppAssetAPI.CreateAppAsset(context.Background()).CreateOrUpdateAppAssetDto(createOrUpdateAppAssetDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppAssetAPI.CreateAppAsset``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAppAsset`: AppAssetDto
	fmt.Fprintf(os.Stdout, "Response from `AppAssetAPI.CreateAppAsset`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAppAssetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createOrUpdateAppAssetDto** | [**CreateOrUpdateAppAssetDto**](CreateOrUpdateAppAssetDto.md) |  |

### Return type

[**AppAssetDto**](AppAssetDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteAppAssetById

> DeleteAppAssetById(ctx, id).Execute()



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
	r, err := apiClient.AppAssetAPI.DeleteAppAssetById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppAssetAPI.DeleteAppAssetById``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteAppAssetByIdRequest struct via the builder pattern


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


## GetListByAppLocaleId

> []AppAssetDto GetListByAppLocaleId(ctx, appLocaleId).Execute()



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
	appLocaleId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppAssetAPI.GetListByAppLocaleId(context.Background(), appLocaleId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppAssetAPI.GetListByAppLocaleId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetListByAppLocaleId`: []AppAssetDto
	fmt.Fprintf(os.Stdout, "Response from `AppAssetAPI.GetListByAppLocaleId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**appLocaleId** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiGetListByAppLocaleIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]AppAssetDto**](AppAssetDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAppAsset

> AppAssetDto UpdateAppAsset(ctx, id).CreateOrUpdateAppAssetDto(createOrUpdateAppAssetDto).Execute()



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
	createOrUpdateAppAssetDto := *openapiclient.NewCreateOrUpdateAppAssetDto() // CreateOrUpdateAppAssetDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppAssetAPI.UpdateAppAsset(context.Background(), id).CreateOrUpdateAppAssetDto(createOrUpdateAppAssetDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppAssetAPI.UpdateAppAsset``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateAppAsset`: AppAssetDto
	fmt.Fprintf(os.Stdout, "Response from `AppAssetAPI.UpdateAppAsset`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAppAssetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createOrUpdateAppAssetDto** | [**CreateOrUpdateAppAssetDto**](CreateOrUpdateAppAssetDto.md) |  |

### Return type

[**AppAssetDto**](AppAssetDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

