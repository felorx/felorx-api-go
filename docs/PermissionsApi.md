# \PermissionsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetPermissions**](PermissionsAPI.md#GetPermissions) | **Get** /api/permission-management/permissions | 
[**UpdatePermissions**](PermissionsAPI.md#UpdatePermissions) | **Put** /api/permission-management/permissions | 



## GetPermissions

> GetPermissionListResultDto GetPermissions(ctx).ProviderName(providerName).ProviderKey(providerKey).Execute()



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
	providerName := "providerName_example" // string |  (optional)
	providerKey := "providerKey_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PermissionsAPI.GetPermissions(context.Background()).ProviderName(providerName).ProviderKey(providerKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PermissionsAPI.GetPermissions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPermissions`: GetPermissionListResultDto
	fmt.Fprintf(os.Stdout, "Response from `PermissionsAPI.GetPermissions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetPermissionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **providerName** | **string** |  | 
 **providerKey** | **string** |  | 

### Return type

[**GetPermissionListResultDto**](GetPermissionListResultDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdatePermissions

> UpdatePermissions(ctx).ProviderName(providerName).ProviderKey(providerKey).UpdatePermissionsDto(updatePermissionsDto).Execute()



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
	providerName := "providerName_example" // string |  (optional)
	providerKey := "providerKey_example" // string |  (optional)
	updatePermissionsDto := *openapiclient.NewUpdatePermissionsDto() // UpdatePermissionsDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.PermissionsAPI.UpdatePermissions(context.Background()).ProviderName(providerName).ProviderKey(providerKey).UpdatePermissionsDto(updatePermissionsDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PermissionsAPI.UpdatePermissions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdatePermissionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **providerName** | **string** |  | 
 **providerKey** | **string** |  | 
 **updatePermissionsDto** | [**UpdatePermissionsDto**](UpdatePermissionsDto.md) |  | 

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

