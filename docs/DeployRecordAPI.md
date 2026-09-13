# \DeployRecordAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateDeployRecord**](DeployRecordAPI.md#CreateDeployRecord) | **Post** /api/app/deploy-record | 
[**DeleteDeployRecordById**](DeployRecordAPI.md#DeleteDeployRecordById) | **Delete** /api/app/deploy-record/{id} | 
[**GetByCiDeployId**](DeployRecordAPI.md#GetByCiDeployId) | **Get** /api/app/deploy-record/by-ci-deploy-id/{ciDeployId} | 
[**GetDeployRecordById**](DeployRecordAPI.md#GetDeployRecordById) | **Get** /api/app/deploy-record/{id} | 
[**GetDeployRecordList**](DeployRecordAPI.md#GetDeployRecordList) | **Get** /api/app/deploy-record | 
[**GetLatestGetApiAppDeployRecordLatestAppId**](DeployRecordAPI.md#GetLatestGetApiAppDeployRecordLatestAppId) | **Get** /api/app/deploy-record/latest/{appId} | 
[**GetListByBuildRecordId**](DeployRecordAPI.md#GetListByBuildRecordId) | **Get** /api/app/deploy-record/by-build-record-id/{buildRecordId} | 
[**MarkAsCanceledPostApiAppDeployRecordIdMarkAsCanceled**](DeployRecordAPI.md#MarkAsCanceledPostApiAppDeployRecordIdMarkAsCanceled) | **Post** /api/app/deploy-record/{id}/mark-as-canceled | 
[**MarkAsDeploying**](DeployRecordAPI.md#MarkAsDeploying) | **Post** /api/app/deploy-record/{id}/mark-as-deploying | 
[**MarkAsFailedPostApiAppDeployRecordIdMarkAsFailed**](DeployRecordAPI.md#MarkAsFailedPostApiAppDeployRecordIdMarkAsFailed) | **Post** /api/app/deploy-record/{id}/mark-as-failed | 
[**MarkAsSucceededPostApiAppDeployRecordIdMarkAsSucceeded**](DeployRecordAPI.md#MarkAsSucceededPostApiAppDeployRecordIdMarkAsSucceeded) | **Post** /api/app/deploy-record/{id}/mark-as-succeeded | 
[**UpdateDeployRecord**](DeployRecordAPI.md#UpdateDeployRecord) | **Put** /api/app/deploy-record/{id} | 



## CreateDeployRecord

> DeployRecordDto CreateDeployRecord(ctx).CreateDeployRecordDto(createDeployRecordDto).Execute()



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
	createDeployRecordDto := *openapiclient.NewCreateDeployRecordDto("AppId_example", "BuildRecordId_example", "Version_example", openapiclient.AppPlatform("None"), "Environment_example") // CreateDeployRecordDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeployRecordAPI.CreateDeployRecord(context.Background()).CreateDeployRecordDto(createDeployRecordDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeployRecordAPI.CreateDeployRecord``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateDeployRecord`: DeployRecordDto
	fmt.Fprintf(os.Stdout, "Response from `DeployRecordAPI.CreateDeployRecord`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateDeployRecordRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createDeployRecordDto** | [**CreateDeployRecordDto**](CreateDeployRecordDto.md) |  | 

### Return type

[**DeployRecordDto**](DeployRecordDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteDeployRecordById

> DeleteDeployRecordById(ctx, id).Execute()



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
	r, err := apiClient.DeployRecordAPI.DeleteDeployRecordById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeployRecordAPI.DeleteDeployRecordById``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteDeployRecordByIdRequest struct via the builder pattern


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


## GetByCiDeployId

> DeployRecordDto GetByCiDeployId(ctx, ciDeployId).Execute()



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
	ciDeployId := "ciDeployId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeployRecordAPI.GetByCiDeployId(context.Background(), ciDeployId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeployRecordAPI.GetByCiDeployId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetByCiDeployId`: DeployRecordDto
	fmt.Fprintf(os.Stdout, "Response from `DeployRecordAPI.GetByCiDeployId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**ciDeployId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetByCiDeployIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DeployRecordDto**](DeployRecordDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDeployRecordById

> DeployRecordDto GetDeployRecordById(ctx, id).Execute()



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
	resp, r, err := apiClient.DeployRecordAPI.GetDeployRecordById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeployRecordAPI.GetDeployRecordById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeployRecordById`: DeployRecordDto
	fmt.Fprintf(os.Stdout, "Response from `DeployRecordAPI.GetDeployRecordById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDeployRecordByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DeployRecordDto**](DeployRecordDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDeployRecordList

> DeployRecordDtoPagedResultDto GetDeployRecordList(ctx).AppId(appId).Status(status).Platform(platform).Environment(environment).Version(version).BuildRecordId(buildRecordId).Sorting(sorting).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()



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
	status := openapiclient.DeployStatus("Pending") // DeployStatus | 部署状态 (optional)
	platform := openapiclient.AppPlatform("None") // AppPlatform | 目标平台 (optional)
	environment := "environment_example" // string | 部署环境 (optional)
	version := "version_example" // string | 版本号 (optional)
	buildRecordId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 构建记录ID (optional)
	sorting := "sorting_example" // string |  (optional)
	skipCount := int32(56) // int32 |  (optional)
	maxResultCount := int32(56) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeployRecordAPI.GetDeployRecordList(context.Background()).AppId(appId).Status(status).Platform(platform).Environment(environment).Version(version).BuildRecordId(buildRecordId).Sorting(sorting).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeployRecordAPI.GetDeployRecordList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDeployRecordList`: DeployRecordDtoPagedResultDto
	fmt.Fprintf(os.Stdout, "Response from `DeployRecordAPI.GetDeployRecordList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetDeployRecordListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **appId** | **string** | 应用ID | 
 **status** | [**DeployStatus**](DeployStatus.md) | 部署状态 | 
 **platform** | [**AppPlatform**](AppPlatform.md) | 目标平台 | 
 **environment** | **string** | 部署环境 | 
 **version** | **string** | 版本号 | 
 **buildRecordId** | **string** | 构建记录ID | 
 **sorting** | **string** |  | 
 **skipCount** | **int32** |  | 
 **maxResultCount** | **int32** |  | 

### Return type

[**DeployRecordDtoPagedResultDto**](DeployRecordDtoPagedResultDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetLatestGetApiAppDeployRecordLatestAppId

> DeployRecordDto GetLatestGetApiAppDeployRecordLatestAppId(ctx, appId).Platform(platform).Environment(environment).Execute()



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
	resp, r, err := apiClient.DeployRecordAPI.GetLatestGetApiAppDeployRecordLatestAppId(context.Background(), appId).Platform(platform).Environment(environment).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeployRecordAPI.GetLatestGetApiAppDeployRecordLatestAppId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetLatestGetApiAppDeployRecordLatestAppId`: DeployRecordDto
	fmt.Fprintf(os.Stdout, "Response from `DeployRecordAPI.GetLatestGetApiAppDeployRecordLatestAppId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**appId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetLatestGetApiAppDeployRecordLatestAppIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **platform** | [**AppPlatform**](AppPlatform.md) |  | 
 **environment** | **string** |  | 

### Return type

[**DeployRecordDto**](DeployRecordDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetListByBuildRecordId

> []DeployRecordDto GetListByBuildRecordId(ctx, buildRecordId).Execute()



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
	buildRecordId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeployRecordAPI.GetListByBuildRecordId(context.Background(), buildRecordId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeployRecordAPI.GetListByBuildRecordId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetListByBuildRecordId`: []DeployRecordDto
	fmt.Fprintf(os.Stdout, "Response from `DeployRecordAPI.GetListByBuildRecordId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**buildRecordId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetListByBuildRecordIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]DeployRecordDto**](DeployRecordDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MarkAsCanceledPostApiAppDeployRecordIdMarkAsCanceled

> DeployRecordDto MarkAsCanceledPostApiAppDeployRecordIdMarkAsCanceled(ctx, id).Execute()



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
	resp, r, err := apiClient.DeployRecordAPI.MarkAsCanceledPostApiAppDeployRecordIdMarkAsCanceled(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeployRecordAPI.MarkAsCanceledPostApiAppDeployRecordIdMarkAsCanceled``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MarkAsCanceledPostApiAppDeployRecordIdMarkAsCanceled`: DeployRecordDto
	fmt.Fprintf(os.Stdout, "Response from `DeployRecordAPI.MarkAsCanceledPostApiAppDeployRecordIdMarkAsCanceled`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiMarkAsCanceledPostApiAppDeployRecordIdMarkAsCanceledRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DeployRecordDto**](DeployRecordDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MarkAsDeploying

> DeployRecordDto MarkAsDeploying(ctx, id).Execute()



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
	resp, r, err := apiClient.DeployRecordAPI.MarkAsDeploying(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeployRecordAPI.MarkAsDeploying``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MarkAsDeploying`: DeployRecordDto
	fmt.Fprintf(os.Stdout, "Response from `DeployRecordAPI.MarkAsDeploying`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiMarkAsDeployingRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DeployRecordDto**](DeployRecordDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MarkAsFailedPostApiAppDeployRecordIdMarkAsFailed

> DeployRecordDto MarkAsFailedPostApiAppDeployRecordIdMarkAsFailed(ctx, id).ErrorMessage(errorMessage).Execute()



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
	resp, r, err := apiClient.DeployRecordAPI.MarkAsFailedPostApiAppDeployRecordIdMarkAsFailed(context.Background(), id).ErrorMessage(errorMessage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeployRecordAPI.MarkAsFailedPostApiAppDeployRecordIdMarkAsFailed``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MarkAsFailedPostApiAppDeployRecordIdMarkAsFailed`: DeployRecordDto
	fmt.Fprintf(os.Stdout, "Response from `DeployRecordAPI.MarkAsFailedPostApiAppDeployRecordIdMarkAsFailed`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiMarkAsFailedPostApiAppDeployRecordIdMarkAsFailedRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **errorMessage** | **string** |  | 

### Return type

[**DeployRecordDto**](DeployRecordDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MarkAsSucceededPostApiAppDeployRecordIdMarkAsSucceeded

> DeployRecordDto MarkAsSucceededPostApiAppDeployRecordIdMarkAsSucceeded(ctx, id).DeployUrl(deployUrl).Execute()



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
	deployUrl := "deployUrl_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeployRecordAPI.MarkAsSucceededPostApiAppDeployRecordIdMarkAsSucceeded(context.Background(), id).DeployUrl(deployUrl).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeployRecordAPI.MarkAsSucceededPostApiAppDeployRecordIdMarkAsSucceeded``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MarkAsSucceededPostApiAppDeployRecordIdMarkAsSucceeded`: DeployRecordDto
	fmt.Fprintf(os.Stdout, "Response from `DeployRecordAPI.MarkAsSucceededPostApiAppDeployRecordIdMarkAsSucceeded`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiMarkAsSucceededPostApiAppDeployRecordIdMarkAsSucceededRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **deployUrl** | **string** |  | 

### Return type

[**DeployRecordDto**](DeployRecordDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateDeployRecord

> DeployRecordDto UpdateDeployRecord(ctx, id).UpdateDeployRecordDto(updateDeployRecordDto).Execute()



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
	updateDeployRecordDto := *openapiclient.NewUpdateDeployRecordDto(openapiclient.DeployStatus("Pending")) // UpdateDeployRecordDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeployRecordAPI.UpdateDeployRecord(context.Background(), id).UpdateDeployRecordDto(updateDeployRecordDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeployRecordAPI.UpdateDeployRecord``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateDeployRecord`: DeployRecordDto
	fmt.Fprintf(os.Stdout, "Response from `DeployRecordAPI.UpdateDeployRecord`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateDeployRecordRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateDeployRecordDto** | [**UpdateDeployRecordDto**](UpdateDeployRecordDto.md) |  | 

### Return type

[**DeployRecordDto**](DeployRecordDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

