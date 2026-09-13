# \AiProviderAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAiProvider**](AiProviderAPI.md#CreateAiProvider) | **Post** /api/app/ai-provider | 
[**DeleteAiProviderById**](AiProviderAPI.md#DeleteAiProviderById) | **Delete** /api/app/ai-provider/{id} | 
[**GetAiProviderById**](AiProviderAPI.md#GetAiProviderById) | **Get** /api/app/ai-provider/{id} | 
[**GetAiProviderList**](AiProviderAPI.md#GetAiProviderList) | **Get** /api/app/ai-provider | 
[**SetDefaultModelPostApiAppAiProviderSetDefaultModel**](AiProviderAPI.md#SetDefaultModelPostApiAppAiProviderSetDefaultModel) | **Post** /api/app/ai-provider/set-default-model | 
[**SetEnabledPostApiAppAiProviderIdSetEnabled**](AiProviderAPI.md#SetEnabledPostApiAppAiProviderIdSetEnabled) | **Post** /api/app/ai-provider/{id}/set-enabled | 
[**TestPostApiAppAiProviderIdTest**](AiProviderAPI.md#TestPostApiAppAiProviderIdTest) | **Post** /api/app/ai-provider/{id}/test | 
[**UpdateAiProvider**](AiProviderAPI.md#UpdateAiProvider) | **Put** /api/app/ai-provider/{id} | 



## CreateAiProvider

> AiProviderDto CreateAiProvider(ctx).CreateOrUpdateAiProviderDto(createOrUpdateAiProviderDto).Execute()



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
	createOrUpdateAiProviderDto := *openapiclient.NewCreateOrUpdateAiProviderDto() // CreateOrUpdateAiProviderDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiProviderAPI.CreateAiProvider(context.Background()).CreateOrUpdateAiProviderDto(createOrUpdateAiProviderDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiProviderAPI.CreateAiProvider``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAiProvider`: AiProviderDto
	fmt.Fprintf(os.Stdout, "Response from `AiProviderAPI.CreateAiProvider`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAiProviderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createOrUpdateAiProviderDto** | [**CreateOrUpdateAiProviderDto**](CreateOrUpdateAiProviderDto.md) |  | 

### Return type

[**AiProviderDto**](AiProviderDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteAiProviderById

> DeleteAiProviderById(ctx, id).Execute()



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
	r, err := apiClient.AiProviderAPI.DeleteAiProviderById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiProviderAPI.DeleteAiProviderById``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteAiProviderByIdRequest struct via the builder pattern


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


## GetAiProviderById

> AiProviderDto GetAiProviderById(ctx, id).Execute()



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
	resp, r, err := apiClient.AiProviderAPI.GetAiProviderById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiProviderAPI.GetAiProviderById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAiProviderById`: AiProviderDto
	fmt.Fprintf(os.Stdout, "Response from `AiProviderAPI.GetAiProviderById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAiProviderByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AiProviderDto**](AiProviderDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAiProviderList

> AiProviderDtoPagedResultDto GetAiProviderList(ctx).Filter(filter).ProviderType(providerType).Capability(capability).Enabled(enabled).Sorting(sorting).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()



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
	filter := "filter_example" // string |  (optional)
	providerType := openapiclient.AiProviderType("Mock") // AiProviderType |  (optional)
	capability := openapiclient.AiCapability("Chat") // AiCapability |  (optional)
	enabled := true // bool |  (optional)
	sorting := "sorting_example" // string |  (optional)
	skipCount := int32(56) // int32 |  (optional)
	maxResultCount := int32(56) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiProviderAPI.GetAiProviderList(context.Background()).Filter(filter).ProviderType(providerType).Capability(capability).Enabled(enabled).Sorting(sorting).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiProviderAPI.GetAiProviderList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAiProviderList`: AiProviderDtoPagedResultDto
	fmt.Fprintf(os.Stdout, "Response from `AiProviderAPI.GetAiProviderList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAiProviderListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **string** |  | 
 **providerType** | [**AiProviderType**](AiProviderType.md) |  | 
 **capability** | [**AiCapability**](AiCapability.md) |  | 
 **enabled** | **bool** |  | 
 **sorting** | **string** |  | 
 **skipCount** | **int32** |  | 
 **maxResultCount** | **int32** |  | 

### Return type

[**AiProviderDtoPagedResultDto**](AiProviderDtoPagedResultDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetDefaultModelPostApiAppAiProviderSetDefaultModel

> AiProviderDto SetDefaultModelPostApiAppAiProviderSetDefaultModel(ctx).SetDefaultAiModelDto(setDefaultAiModelDto).Execute()



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
	setDefaultAiModelDto := *openapiclient.NewSetDefaultAiModelDto() // SetDefaultAiModelDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiProviderAPI.SetDefaultModelPostApiAppAiProviderSetDefaultModel(context.Background()).SetDefaultAiModelDto(setDefaultAiModelDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiProviderAPI.SetDefaultModelPostApiAppAiProviderSetDefaultModel``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetDefaultModelPostApiAppAiProviderSetDefaultModel`: AiProviderDto
	fmt.Fprintf(os.Stdout, "Response from `AiProviderAPI.SetDefaultModelPostApiAppAiProviderSetDefaultModel`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSetDefaultModelPostApiAppAiProviderSetDefaultModelRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **setDefaultAiModelDto** | [**SetDefaultAiModelDto**](SetDefaultAiModelDto.md) |  | 

### Return type

[**AiProviderDto**](AiProviderDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetEnabledPostApiAppAiProviderIdSetEnabled

> AiProviderDto SetEnabledPostApiAppAiProviderIdSetEnabled(ctx, id).SetAiProviderEnabledDto(setAiProviderEnabledDto).Execute()



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
	setAiProviderEnabledDto := *openapiclient.NewSetAiProviderEnabledDto() // SetAiProviderEnabledDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiProviderAPI.SetEnabledPostApiAppAiProviderIdSetEnabled(context.Background(), id).SetAiProviderEnabledDto(setAiProviderEnabledDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiProviderAPI.SetEnabledPostApiAppAiProviderIdSetEnabled``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetEnabledPostApiAppAiProviderIdSetEnabled`: AiProviderDto
	fmt.Fprintf(os.Stdout, "Response from `AiProviderAPI.SetEnabledPostApiAppAiProviderIdSetEnabled`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiSetEnabledPostApiAppAiProviderIdSetEnabledRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **setAiProviderEnabledDto** | [**SetAiProviderEnabledDto**](SetAiProviderEnabledDto.md) |  | 

### Return type

[**AiProviderDto**](AiProviderDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TestPostApiAppAiProviderIdTest

> AiProviderDto TestPostApiAppAiProviderIdTest(ctx, id).TestAiProviderDto(testAiProviderDto).Execute()



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
	testAiProviderDto := *openapiclient.NewTestAiProviderDto() // TestAiProviderDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiProviderAPI.TestPostApiAppAiProviderIdTest(context.Background(), id).TestAiProviderDto(testAiProviderDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiProviderAPI.TestPostApiAppAiProviderIdTest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TestPostApiAppAiProviderIdTest`: AiProviderDto
	fmt.Fprintf(os.Stdout, "Response from `AiProviderAPI.TestPostApiAppAiProviderIdTest`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiTestPostApiAppAiProviderIdTestRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **testAiProviderDto** | [**TestAiProviderDto**](TestAiProviderDto.md) |  | 

### Return type

[**AiProviderDto**](AiProviderDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAiProvider

> AiProviderDto UpdateAiProvider(ctx, id).CreateOrUpdateAiProviderDto(createOrUpdateAiProviderDto).Execute()



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
	createOrUpdateAiProviderDto := *openapiclient.NewCreateOrUpdateAiProviderDto() // CreateOrUpdateAiProviderDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiProviderAPI.UpdateAiProvider(context.Background(), id).CreateOrUpdateAiProviderDto(createOrUpdateAiProviderDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiProviderAPI.UpdateAiProvider``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateAiProvider`: AiProviderDto
	fmt.Fprintf(os.Stdout, "Response from `AiProviderAPI.UpdateAiProvider`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAiProviderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createOrUpdateAiProviderDto** | [**CreateOrUpdateAiProviderDto**](CreateOrUpdateAiProviderDto.md) |  | 

### Return type

[**AiProviderDto**](AiProviderDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

