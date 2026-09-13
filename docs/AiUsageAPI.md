# \AiUsageAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetRecords**](AiUsageAPI.md#GetRecords) | **Get** /api/ai/usage/records | 
[**GetSummaryGetApiAiUsageSummary**](AiUsageAPI.md#GetSummaryGetApiAiUsageSummary) | **Get** /api/ai/usage/summary | 



## GetRecords

> AiUsageRecordDtoPagedResultDto GetRecords(ctx).From(from).To(to).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/felorx/felorx-api-go"
)

func main() {
	from := time.Now() // time.Time |  (optional)
	to := time.Now() // time.Time |  (optional)
	skipCount := int32(56) // int32 |  (optional) (default to 0)
	maxResultCount := int32(56) // int32 |  (optional) (default to 20)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiUsageAPI.GetRecords(context.Background()).From(from).To(to).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiUsageAPI.GetRecords``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetRecords`: AiUsageRecordDtoPagedResultDto
	fmt.Fprintf(os.Stdout, "Response from `AiUsageAPI.GetRecords`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetRecordsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **from** | **time.Time** |  | 
 **to** | **time.Time** |  | 
 **skipCount** | **int32** |  | [default to 0]
 **maxResultCount** | **int32** |  | [default to 20]

### Return type

[**AiUsageRecordDtoPagedResultDto**](AiUsageRecordDtoPagedResultDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSummaryGetApiAiUsageSummary

> AiUsageSummaryDto GetSummaryGetApiAiUsageSummary(ctx).From(from).To(to).Execute()



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/felorx/felorx-api-go"
)

func main() {
	from := time.Now() // time.Time |  (optional)
	to := time.Now() // time.Time |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiUsageAPI.GetSummaryGetApiAiUsageSummary(context.Background()).From(from).To(to).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiUsageAPI.GetSummaryGetApiAiUsageSummary``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSummaryGetApiAiUsageSummary`: AiUsageSummaryDto
	fmt.Fprintf(os.Stdout, "Response from `AiUsageAPI.GetSummaryGetApiAiUsageSummary`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetSummaryGetApiAiUsageSummaryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **from** | **time.Time** |  | 
 **to** | **time.Time** |  | 

### Return type

[**AiUsageSummaryDto**](AiUsageSummaryDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

