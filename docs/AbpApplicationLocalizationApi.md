# \AbpApplicationLocalizationAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAbpApplicationLocalization**](AbpApplicationLocalizationAPI.md#GetAbpApplicationLocalization) | **Get** /api/abp/application-localization |



## GetAbpApplicationLocalization

> ApplicationLocalizationDto GetAbpApplicationLocalization(ctx).CultureName(cultureName).OnlyDynamics(onlyDynamics).Execute()



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
	cultureName := "cultureName_example" // string |
	onlyDynamics := true // bool |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AbpApplicationLocalizationAPI.GetAbpApplicationLocalization(context.Background()).CultureName(cultureName).OnlyDynamics(onlyDynamics).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AbpApplicationLocalizationAPI.GetAbpApplicationLocalization``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAbpApplicationLocalization`: ApplicationLocalizationDto
	fmt.Fprintf(os.Stdout, "Response from `AbpApplicationLocalizationAPI.GetAbpApplicationLocalization`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAbpApplicationLocalizationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **cultureName** | **string** |  |
 **onlyDynamics** | **bool** |  |

### Return type

[**ApplicationLocalizationDto**](ApplicationLocalizationDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

