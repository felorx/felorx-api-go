# \MessageSourceCategoryAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetMessageSourceCategoryList**](MessageSourceCategoryAPI.md#GetMessageSourceCategoryList) | **Get** /api/app/message-source-category | 



## GetMessageSourceCategoryList

> []MessageSourceCategoryDto GetMessageSourceCategoryList(ctx).Execute()



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MessageSourceCategoryAPI.GetMessageSourceCategoryList(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessageSourceCategoryAPI.GetMessageSourceCategoryList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMessageSourceCategoryList`: []MessageSourceCategoryDto
	fmt.Fprintf(os.Stdout, "Response from `MessageSourceCategoryAPI.GetMessageSourceCategoryList`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetMessageSourceCategoryListRequest struct via the builder pattern


### Return type

[**[]MessageSourceCategoryDto**](MessageSourceCategoryDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

