# \TenantAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateTenant**](TenantAPI.md#CreateTenant) | **Post** /api/multi-tenancy/tenants | 
[**DeleteDefaultConnectionString**](TenantAPI.md#DeleteDefaultConnectionString) | **Delete** /api/multi-tenancy/tenants/{id}/default-connection-string | 
[**DeleteTenantById**](TenantAPI.md#DeleteTenantById) | **Delete** /api/multi-tenancy/tenants/{id} | 
[**GetDefaultConnectionString**](TenantAPI.md#GetDefaultConnectionString) | **Get** /api/multi-tenancy/tenants/{id}/default-connection-string | 
[**GetTenantById**](TenantAPI.md#GetTenantById) | **Get** /api/multi-tenancy/tenants/{id} | 
[**GetTenantList**](TenantAPI.md#GetTenantList) | **Get** /api/multi-tenancy/tenants | 
[**UpdateDefaultConnectionString**](TenantAPI.md#UpdateDefaultConnectionString) | **Put** /api/multi-tenancy/tenants/{id}/default-connection-string | 
[**UpdateTenant**](TenantAPI.md#UpdateTenant) | **Put** /api/multi-tenancy/tenants/{id} | 



## CreateTenant

> TenantDto CreateTenant(ctx).TenantCreateDto(tenantCreateDto).Execute()



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
	tenantCreateDto := *openapiclient.NewTenantCreateDto("Name_example", "AdminEmailAddress_example", "AdminPassword_example") // TenantCreateDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TenantAPI.CreateTenant(context.Background()).TenantCreateDto(tenantCreateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TenantAPI.CreateTenant``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateTenant`: TenantDto
	fmt.Fprintf(os.Stdout, "Response from `TenantAPI.CreateTenant`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateTenantRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **tenantCreateDto** | [**TenantCreateDto**](TenantCreateDto.md) |  | 

### Return type

[**TenantDto**](TenantDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteDefaultConnectionString

> DeleteDefaultConnectionString(ctx, id).Execute()



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
	r, err := apiClient.TenantAPI.DeleteDefaultConnectionString(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TenantAPI.DeleteDefaultConnectionString``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteDefaultConnectionStringRequest struct via the builder pattern


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


## DeleteTenantById

> DeleteTenantById(ctx, id).Execute()



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
	r, err := apiClient.TenantAPI.DeleteTenantById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TenantAPI.DeleteTenantById``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteTenantByIdRequest struct via the builder pattern


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


## GetDefaultConnectionString

> string GetDefaultConnectionString(ctx, id).Execute()



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
	resp, r, err := apiClient.TenantAPI.GetDefaultConnectionString(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TenantAPI.GetDefaultConnectionString``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDefaultConnectionString`: string
	fmt.Fprintf(os.Stdout, "Response from `TenantAPI.GetDefaultConnectionString`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDefaultConnectionStringRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**string**

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTenantById

> TenantDto GetTenantById(ctx, id).Execute()



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
	resp, r, err := apiClient.TenantAPI.GetTenantById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TenantAPI.GetTenantById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTenantById`: TenantDto
	fmt.Fprintf(os.Stdout, "Response from `TenantAPI.GetTenantById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetTenantByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**TenantDto**](TenantDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTenantList

> TenantDtoPagedResultDto GetTenantList(ctx).Filter(filter).Sorting(sorting).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()



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
	filter := "filter_example" // string |  (optional)
	sorting := "sorting_example" // string |  (optional)
	skipCount := int32(56) // int32 |  (optional)
	maxResultCount := int32(56) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TenantAPI.GetTenantList(context.Background()).Filter(filter).Sorting(sorting).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TenantAPI.GetTenantList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTenantList`: TenantDtoPagedResultDto
	fmt.Fprintf(os.Stdout, "Response from `TenantAPI.GetTenantList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetTenantListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **string** |  | 
 **sorting** | **string** |  | 
 **skipCount** | **int32** |  | 
 **maxResultCount** | **int32** |  | 

### Return type

[**TenantDtoPagedResultDto**](TenantDtoPagedResultDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateDefaultConnectionString

> UpdateDefaultConnectionString(ctx, id).DefaultConnectionString(defaultConnectionString).Execute()



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
	defaultConnectionString := "defaultConnectionString_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.TenantAPI.UpdateDefaultConnectionString(context.Background(), id).DefaultConnectionString(defaultConnectionString).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TenantAPI.UpdateDefaultConnectionString``: %v\n", err)
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

Other parameters are passed through a pointer to a apiUpdateDefaultConnectionStringRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **defaultConnectionString** | **string** |  | 

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


## UpdateTenant

> TenantDto UpdateTenant(ctx, id).TenantUpdateDto(tenantUpdateDto).Execute()



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
	tenantUpdateDto := *openapiclient.NewTenantUpdateDto("Name_example") // TenantUpdateDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TenantAPI.UpdateTenant(context.Background(), id).TenantUpdateDto(tenantUpdateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TenantAPI.UpdateTenant``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateTenant`: TenantDto
	fmt.Fprintf(os.Stdout, "Response from `TenantAPI.UpdateTenant`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateTenantRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **tenantUpdateDto** | [**TenantUpdateDto**](TenantUpdateDto.md) |  | 

### Return type

[**TenantDto**](TenantDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

