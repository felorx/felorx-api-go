# \AbpApplicationConfigurationAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAbpApplicationConfiguration**](AbpApplicationConfigurationAPI.md#GetAbpApplicationConfiguration) | **Get** /api/abp/application-configuration | 



## GetAbpApplicationConfiguration

> ApplicationConfigurationDto GetAbpApplicationConfiguration(ctx).IncludeLocalizationResources(includeLocalizationResources).Execute()



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
	includeLocalizationResources := true // bool |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AbpApplicationConfigurationAPI.GetAbpApplicationConfiguration(context.Background()).IncludeLocalizationResources(includeLocalizationResources).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AbpApplicationConfigurationAPI.GetAbpApplicationConfiguration``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAbpApplicationConfiguration`: ApplicationConfigurationDto
	fmt.Fprintf(os.Stdout, "Response from `AbpApplicationConfigurationAPI.GetAbpApplicationConfiguration`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAbpApplicationConfigurationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **includeLocalizationResources** | **bool** |  | 

### Return type

[**ApplicationConfigurationDto**](ApplicationConfigurationDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

