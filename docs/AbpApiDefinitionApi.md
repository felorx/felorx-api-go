# \AbpApiDefinitionAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAbpApiDefinition**](AbpApiDefinitionAPI.md#GetAbpApiDefinition) | **Get** /api/abp/api-definition | 



## GetAbpApiDefinition

> ApplicationApiDescriptionModel GetAbpApiDefinition(ctx).IncludeTypes(includeTypes).Execute()



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
	includeTypes := true // bool |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AbpApiDefinitionAPI.GetAbpApiDefinition(context.Background()).IncludeTypes(includeTypes).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AbpApiDefinitionAPI.GetAbpApiDefinition``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAbpApiDefinition`: ApplicationApiDescriptionModel
	fmt.Fprintf(os.Stdout, "Response from `AbpApiDefinitionAPI.GetAbpApiDefinition`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAbpApiDefinitionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **includeTypes** | **bool** |  | 

### Return type

[**ApplicationApiDescriptionModel**](ApplicationApiDescriptionModel.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

