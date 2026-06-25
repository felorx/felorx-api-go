# \AppReleaseAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAppRelease**](AppReleaseAPI.md#CreateAppRelease) | **Post** /api/app/app-release | 创建新版本
[**DeleteAppReleaseById**](AppReleaseAPI.md#DeleteAppReleaseById) | **Delete** /api/app/app-release/{id} | 删除版本
[**GetAppReleaseById**](AppReleaseAPI.md#GetAppReleaseById) | **Get** /api/app/app-release/{id} | 获取版本
[**GetAppReleaseList**](AppReleaseAPI.md#GetAppReleaseList) | **Get** /api/app/app-release | 获取版本列表
[**GetLatest**](AppReleaseAPI.md#GetLatest) | **Get** /api/app/app-release/latest | 获取最新版本
[**GetListByDeveloper**](AppReleaseAPI.md#GetListByDeveloper) | **Get** /api/app/app-release/by-developer | 开发者获取版本列表（版本的创建者为当前用户）
[**UpdateAppRelease**](AppReleaseAPI.md#UpdateAppRelease) | **Put** /api/app/app-release/{id} | 更新版本



## CreateAppRelease

> AppReleaseDto CreateAppRelease(ctx).CreateOrUpdateAppReleaseDto(createOrUpdateAppReleaseDto).Execute()

创建新版本

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
	createOrUpdateAppReleaseDto := *openapiclient.NewCreateOrUpdateAppReleaseDto() // CreateOrUpdateAppReleaseDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppReleaseAPI.CreateAppRelease(context.Background()).CreateOrUpdateAppReleaseDto(createOrUpdateAppReleaseDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppReleaseAPI.CreateAppRelease``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAppRelease`: AppReleaseDto
	fmt.Fprintf(os.Stdout, "Response from `AppReleaseAPI.CreateAppRelease`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAppReleaseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createOrUpdateAppReleaseDto** | [**CreateOrUpdateAppReleaseDto**](CreateOrUpdateAppReleaseDto.md) |  |

### Return type

[**AppReleaseDto**](AppReleaseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteAppReleaseById

> DeleteAppReleaseById(ctx, id).Execute()

删除版本

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
	r, err := apiClient.AppReleaseAPI.DeleteAppReleaseById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppReleaseAPI.DeleteAppReleaseById``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteAppReleaseByIdRequest struct via the builder pattern


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


## GetAppReleaseById

> AppReleaseDto GetAppReleaseById(ctx, id).Execute()

获取版本

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
	resp, r, err := apiClient.AppReleaseAPI.GetAppReleaseById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppReleaseAPI.GetAppReleaseById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAppReleaseById`: AppReleaseDto
	fmt.Fprintf(os.Stdout, "Response from `AppReleaseAPI.GetAppReleaseById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiGetAppReleaseByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AppReleaseDto**](AppReleaseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAppReleaseList

> AppReleaseDtoPagedResultDto GetAppReleaseList(ctx).AppId(appId).Channel(channel).Platform(platform).Publisher(publisher).Sorting(sorting).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()

获取版本列表

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
	channel := openapiclient.ReleaseChannel("Internal") // ReleaseChannel |  (optional)
	platform := "platform_example" // string |  (optional)
	publisher := "publisher_example" // string |  (optional)
	sorting := "sorting_example" // string |  (optional)
	skipCount := int32(56) // int32 |  (optional)
	maxResultCount := int32(56) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppReleaseAPI.GetAppReleaseList(context.Background()).AppId(appId).Channel(channel).Platform(platform).Publisher(publisher).Sorting(sorting).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppReleaseAPI.GetAppReleaseList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAppReleaseList`: AppReleaseDtoPagedResultDto
	fmt.Fprintf(os.Stdout, "Response from `AppReleaseAPI.GetAppReleaseList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAppReleaseListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **appId** | **string** |  |
 **channel** | [**ReleaseChannel**](ReleaseChannel.md) |  |
 **platform** | **string** |  |
 **publisher** | **string** |  |
 **sorting** | **string** |  |
 **skipCount** | **int32** |  |
 **maxResultCount** | **int32** |  |

### Return type

[**AppReleaseDtoPagedResultDto**](AppReleaseDtoPagedResultDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetLatest

> AppReleaseDto GetLatest(ctx).AppName(appName).Platform(platform).ArtifactType(artifactType).Publisher(publisher).Execute()

获取最新版本

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
	appName := "appName_example" // string |  (optional)
	platform := "platform_example" // string |  (optional)
	artifactType := "artifactType_example" // string |  (optional)
	publisher := "publisher_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppReleaseAPI.GetLatest(context.Background()).AppName(appName).Platform(platform).ArtifactType(artifactType).Publisher(publisher).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppReleaseAPI.GetLatest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetLatest`: AppReleaseDto
	fmt.Fprintf(os.Stdout, "Response from `AppReleaseAPI.GetLatest`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetLatestRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **appName** | **string** |  |
 **platform** | **string** |  |
 **artifactType** | **string** |  |
 **publisher** | **string** |  |

### Return type

[**AppReleaseDto**](AppReleaseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetListByDeveloper

> AppReleaseDtoPagedResultDto GetListByDeveloper(ctx).AppId(appId).Channel(channel).Platform(platform).Publisher(publisher).Sorting(sorting).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()

开发者获取版本列表（版本的创建者为当前用户）

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
	channel := openapiclient.ReleaseChannel("Internal") // ReleaseChannel |  (optional)
	platform := "platform_example" // string |  (optional)
	publisher := "publisher_example" // string |  (optional)
	sorting := "sorting_example" // string |  (optional)
	skipCount := int32(56) // int32 |  (optional)
	maxResultCount := int32(56) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppReleaseAPI.GetListByDeveloper(context.Background()).AppId(appId).Channel(channel).Platform(platform).Publisher(publisher).Sorting(sorting).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppReleaseAPI.GetListByDeveloper``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetListByDeveloper`: AppReleaseDtoPagedResultDto
	fmt.Fprintf(os.Stdout, "Response from `AppReleaseAPI.GetListByDeveloper`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetListByDeveloperRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **appId** | **string** |  |
 **channel** | [**ReleaseChannel**](ReleaseChannel.md) |  |
 **platform** | **string** |  |
 **publisher** | **string** |  |
 **sorting** | **string** |  |
 **skipCount** | **int32** |  |
 **maxResultCount** | **int32** |  |

### Return type

[**AppReleaseDtoPagedResultDto**](AppReleaseDtoPagedResultDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAppRelease

> AppReleaseDto UpdateAppRelease(ctx, id).CreateOrUpdateAppReleaseDto(createOrUpdateAppReleaseDto).Execute()

更新版本

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
	createOrUpdateAppReleaseDto := *openapiclient.NewCreateOrUpdateAppReleaseDto() // CreateOrUpdateAppReleaseDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppReleaseAPI.UpdateAppRelease(context.Background(), id).CreateOrUpdateAppReleaseDto(createOrUpdateAppReleaseDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppReleaseAPI.UpdateAppRelease``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateAppRelease`: AppReleaseDto
	fmt.Fprintf(os.Stdout, "Response from `AppReleaseAPI.UpdateAppRelease`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAppReleaseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createOrUpdateAppReleaseDto** | [**CreateOrUpdateAppReleaseDto**](CreateOrUpdateAppReleaseDto.md) |  |

### Return type

[**AppReleaseDto**](AppReleaseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

