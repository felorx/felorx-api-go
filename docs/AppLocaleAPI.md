# \AppLocaleAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAppLocale**](AppLocaleAPI.md#CreateAppLocale) | **Post** /api/app/app-locale |
[**DeleteAppLocaleById**](AppLocaleAPI.md#DeleteAppLocaleById) | **Delete** /api/app/app-locale/{id} |
[**GetListByAppId**](AppLocaleAPI.md#GetListByAppId) | **Get** /api/app/app-locale/by-app-id/{appId} |
[**UpdateAppLocale**](AppLocaleAPI.md#UpdateAppLocale) | **Put** /api/app/app-locale/{id} |



## CreateAppLocale

> AppLocaleDto CreateAppLocale(ctx).CreateOrUpdateAppLocaleDto(createOrUpdateAppLocaleDto).Execute()



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
	createOrUpdateAppLocaleDto := *openapiclient.NewCreateOrUpdateAppLocaleDto() // CreateOrUpdateAppLocaleDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppLocaleAPI.CreateAppLocale(context.Background()).CreateOrUpdateAppLocaleDto(createOrUpdateAppLocaleDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppLocaleAPI.CreateAppLocale``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAppLocale`: AppLocaleDto
	fmt.Fprintf(os.Stdout, "Response from `AppLocaleAPI.CreateAppLocale`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAppLocaleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createOrUpdateAppLocaleDto** | [**CreateOrUpdateAppLocaleDto**](CreateOrUpdateAppLocaleDto.md) |  |

### Return type

[**AppLocaleDto**](AppLocaleDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteAppLocaleById

> DeleteAppLocaleById(ctx, id).Execute()



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
	r, err := apiClient.AppLocaleAPI.DeleteAppLocaleById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppLocaleAPI.DeleteAppLocaleById``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteAppLocaleByIdRequest struct via the builder pattern


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


## GetListByAppId

> []AppLocaleDto GetListByAppId(ctx, appId).Execute()



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
	resp, r, err := apiClient.AppLocaleAPI.GetListByAppId(context.Background(), appId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppLocaleAPI.GetListByAppId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetListByAppId`: []AppLocaleDto
	fmt.Fprintf(os.Stdout, "Response from `AppLocaleAPI.GetListByAppId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**appId** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiGetListByAppIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]AppLocaleDto**](AppLocaleDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAppLocale

> AppLocaleDto UpdateAppLocale(ctx, id).CreateOrUpdateAppLocaleDto(createOrUpdateAppLocaleDto).Execute()



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
	createOrUpdateAppLocaleDto := *openapiclient.NewCreateOrUpdateAppLocaleDto() // CreateOrUpdateAppLocaleDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppLocaleAPI.UpdateAppLocale(context.Background(), id).CreateOrUpdateAppLocaleDto(createOrUpdateAppLocaleDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppLocaleAPI.UpdateAppLocale``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateAppLocale`: AppLocaleDto
	fmt.Fprintf(os.Stdout, "Response from `AppLocaleAPI.UpdateAppLocale`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAppLocaleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createOrUpdateAppLocaleDto** | [**CreateOrUpdateAppLocaleDto**](CreateOrUpdateAppLocaleDto.md) |  |

### Return type

[**AppLocaleDto**](AppLocaleDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

