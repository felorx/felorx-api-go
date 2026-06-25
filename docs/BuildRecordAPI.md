# \BuildRecordAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BuildRecordGetLatest**](BuildRecordAPI.md#BuildRecordGetLatest) | **Get** /api/app/build-record/latest/{appId} |
[**CreateBuildRecord**](BuildRecordAPI.md#CreateBuildRecord) | **Post** /api/app/build-record |
[**DeleteBuildRecordById**](BuildRecordAPI.md#DeleteBuildRecordById) | **Delete** /api/app/build-record/{id} |
[**GetBuildRecordById**](BuildRecordAPI.md#GetBuildRecordById) | **Get** /api/app/build-record/{id} |
[**GetBuildRecordList**](BuildRecordAPI.md#GetBuildRecordList) | **Get** /api/app/build-record |
[**GetByCiBuildId**](BuildRecordAPI.md#GetByCiBuildId) | **Get** /api/app/build-record/by-ci-build-id/{ciBuildId} |
[**MarkAsBuilding**](BuildRecordAPI.md#MarkAsBuilding) | **Post** /api/app/build-record/{id}/mark-as-building |
[**MarkAsCanceled**](BuildRecordAPI.md#MarkAsCanceled) | **Post** /api/app/build-record/{id}/mark-as-canceled |
[**MarkAsFailed**](BuildRecordAPI.md#MarkAsFailed) | **Post** /api/app/build-record/{id}/mark-as-failed |
[**MarkAsSucceeded**](BuildRecordAPI.md#MarkAsSucceeded) | **Post** /api/app/build-record/{id}/mark-as-succeeded |
[**UpdateBuildRecord**](BuildRecordAPI.md#UpdateBuildRecord) | **Put** /api/app/build-record/{id} |



## BuildRecordGetLatest

> BuildRecordDto BuildRecordGetLatest(ctx, appId).Platform(platform).Environment(environment).Execute()



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
	platform := openapiclient.AppPlatform("None") // AppPlatform |  (optional)
	environment := "environment_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BuildRecordAPI.BuildRecordGetLatest(context.Background(), appId).Platform(platform).Environment(environment).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BuildRecordAPI.BuildRecordGetLatest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BuildRecordGetLatest`: BuildRecordDto
	fmt.Fprintf(os.Stdout, "Response from `BuildRecordAPI.BuildRecordGetLatest`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**appId** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiBuildRecordGetLatestRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **platform** | [**AppPlatform**](AppPlatform.md) |  |
 **environment** | **string** |  |

### Return type

[**BuildRecordDto**](BuildRecordDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateBuildRecord

> BuildRecordDto CreateBuildRecord(ctx).CreateBuildRecordDto(createBuildRecordDto).Execute()



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
	createBuildRecordDto := *openapiclient.NewCreateBuildRecordDto("AppId_example", "Version_example", "Branch_example", "CommitHash_example", openapiclient.AppPlatform("None"), openapiclient.ArtifactType("Aab")) // CreateBuildRecordDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BuildRecordAPI.CreateBuildRecord(context.Background()).CreateBuildRecordDto(createBuildRecordDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BuildRecordAPI.CreateBuildRecord``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateBuildRecord`: BuildRecordDto
	fmt.Fprintf(os.Stdout, "Response from `BuildRecordAPI.CreateBuildRecord`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateBuildRecordRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createBuildRecordDto** | [**CreateBuildRecordDto**](CreateBuildRecordDto.md) |  |

### Return type

[**BuildRecordDto**](BuildRecordDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteBuildRecordById

> DeleteBuildRecordById(ctx, id).Execute()



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
	r, err := apiClient.BuildRecordAPI.DeleteBuildRecordById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BuildRecordAPI.DeleteBuildRecordById``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteBuildRecordByIdRequest struct via the builder pattern


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


## GetBuildRecordById

> BuildRecordDto GetBuildRecordById(ctx, id).Execute()



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
	resp, r, err := apiClient.BuildRecordAPI.GetBuildRecordById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BuildRecordAPI.GetBuildRecordById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetBuildRecordById`: BuildRecordDto
	fmt.Fprintf(os.Stdout, "Response from `BuildRecordAPI.GetBuildRecordById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiGetBuildRecordByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**BuildRecordDto**](BuildRecordDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetBuildRecordList

> BuildRecordDtoPagedResultDto GetBuildRecordList(ctx).AppId(appId).Status(status).Platform(platform).Environment(environment).Version(version).Branch(branch).Sorting(sorting).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()



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
	appId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 应用ID (optional)
	status := openapiclient.BuildStatus("Pending") // BuildStatus | 构建状态 (optional)
	platform := openapiclient.AppPlatform("None") // AppPlatform | 目标平台 (optional)
	environment := "environment_example" // string | 环境 (optional)
	version := "version_example" // string | 版本号 (optional)
	branch := "branch_example" // string | 分支名称 (optional)
	sorting := "sorting_example" // string |  (optional)
	skipCount := int32(56) // int32 |  (optional)
	maxResultCount := int32(56) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BuildRecordAPI.GetBuildRecordList(context.Background()).AppId(appId).Status(status).Platform(platform).Environment(environment).Version(version).Branch(branch).Sorting(sorting).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BuildRecordAPI.GetBuildRecordList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetBuildRecordList`: BuildRecordDtoPagedResultDto
	fmt.Fprintf(os.Stdout, "Response from `BuildRecordAPI.GetBuildRecordList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetBuildRecordListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **appId** | **string** | 应用ID |
 **status** | [**BuildStatus**](BuildStatus.md) | 构建状态 |
 **platform** | [**AppPlatform**](AppPlatform.md) | 目标平台 |
 **environment** | **string** | 环境 |
 **version** | **string** | 版本号 |
 **branch** | **string** | 分支名称 |
 **sorting** | **string** |  |
 **skipCount** | **int32** |  |
 **maxResultCount** | **int32** |  |

### Return type

[**BuildRecordDtoPagedResultDto**](BuildRecordDtoPagedResultDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetByCiBuildId

> BuildRecordDto GetByCiBuildId(ctx, ciBuildId).Execute()



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
	ciBuildId := "ciBuildId_example" // string |

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BuildRecordAPI.GetByCiBuildId(context.Background(), ciBuildId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BuildRecordAPI.GetByCiBuildId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetByCiBuildId`: BuildRecordDto
	fmt.Fprintf(os.Stdout, "Response from `BuildRecordAPI.GetByCiBuildId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**ciBuildId** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiGetByCiBuildIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**BuildRecordDto**](BuildRecordDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MarkAsBuilding

> BuildRecordDto MarkAsBuilding(ctx, id).Execute()



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
	resp, r, err := apiClient.BuildRecordAPI.MarkAsBuilding(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BuildRecordAPI.MarkAsBuilding``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MarkAsBuilding`: BuildRecordDto
	fmt.Fprintf(os.Stdout, "Response from `BuildRecordAPI.MarkAsBuilding`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiMarkAsBuildingRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**BuildRecordDto**](BuildRecordDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MarkAsCanceled

> BuildRecordDto MarkAsCanceled(ctx, id).Execute()



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
	resp, r, err := apiClient.BuildRecordAPI.MarkAsCanceled(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BuildRecordAPI.MarkAsCanceled``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MarkAsCanceled`: BuildRecordDto
	fmt.Fprintf(os.Stdout, "Response from `BuildRecordAPI.MarkAsCanceled`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiMarkAsCanceledRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**BuildRecordDto**](BuildRecordDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MarkAsFailed

> BuildRecordDto MarkAsFailed(ctx, id).ErrorMessage(errorMessage).Execute()



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
	errorMessage := "errorMessage_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BuildRecordAPI.MarkAsFailed(context.Background(), id).ErrorMessage(errorMessage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BuildRecordAPI.MarkAsFailed``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MarkAsFailed`: BuildRecordDto
	fmt.Fprintf(os.Stdout, "Response from `BuildRecordAPI.MarkAsFailed`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiMarkAsFailedRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **errorMessage** | **string** |  |

### Return type

[**BuildRecordDto**](BuildRecordDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MarkAsSucceeded

> BuildRecordDto MarkAsSucceeded(ctx, id).ArtifactUrl(artifactUrl).ArtifactSize(artifactSize).Execute()



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
	artifactUrl := "artifactUrl_example" // string |  (optional)
	artifactSize := int64(789) // int64 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BuildRecordAPI.MarkAsSucceeded(context.Background(), id).ArtifactUrl(artifactUrl).ArtifactSize(artifactSize).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BuildRecordAPI.MarkAsSucceeded``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MarkAsSucceeded`: BuildRecordDto
	fmt.Fprintf(os.Stdout, "Response from `BuildRecordAPI.MarkAsSucceeded`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiMarkAsSucceededRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **artifactUrl** | **string** |  |
 **artifactSize** | **int64** |  |

### Return type

[**BuildRecordDto**](BuildRecordDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateBuildRecord

> BuildRecordDto UpdateBuildRecord(ctx, id).UpdateBuildRecordDto(updateBuildRecordDto).Execute()



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
	updateBuildRecordDto := *openapiclient.NewUpdateBuildRecordDto(openapiclient.BuildStatus("Pending")) // UpdateBuildRecordDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.BuildRecordAPI.UpdateBuildRecord(context.Background(), id).UpdateBuildRecordDto(updateBuildRecordDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BuildRecordAPI.UpdateBuildRecord``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateBuildRecord`: BuildRecordDto
	fmt.Fprintf(os.Stdout, "Response from `BuildRecordAPI.UpdateBuildRecord`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateBuildRecordRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateBuildRecordDto** | [**UpdateBuildRecordDto**](UpdateBuildRecordDto.md) |  |

### Return type

[**BuildRecordDto**](BuildRecordDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

