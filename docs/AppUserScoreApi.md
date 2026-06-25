# \AppUserScoreAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAppUserScore**](AppUserScoreAPI.md#CreateAppUserScore) | **Post** /api/app/app-user-score |



## CreateAppUserScore

> AppUserScoreDto CreateAppUserScore(ctx).CreateOrUpdateAppUserScoreDto(createOrUpdateAppUserScoreDto).Execute()



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
	createOrUpdateAppUserScoreDto := *openapiclient.NewCreateOrUpdateAppUserScoreDto() // CreateOrUpdateAppUserScoreDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppUserScoreAPI.CreateAppUserScore(context.Background()).CreateOrUpdateAppUserScoreDto(createOrUpdateAppUserScoreDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppUserScoreAPI.CreateAppUserScore``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAppUserScore`: AppUserScoreDto
	fmt.Fprintf(os.Stdout, "Response from `AppUserScoreAPI.CreateAppUserScore`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAppUserScoreRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createOrUpdateAppUserScoreDto** | [**CreateOrUpdateAppUserScoreDto**](CreateOrUpdateAppUserScoreDto.md) |  |

### Return type

[**AppUserScoreDto**](AppUserScoreDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

