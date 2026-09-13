# \OpenAiCompatibleChatAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreatePostApiAiV1ChatCompletions**](OpenAiCompatibleChatAPI.md#CreatePostApiAiV1ChatCompletions) | **Post** /api/ai/v1/chat/completions | 



## CreatePostApiAiV1ChatCompletions

> AiChatCompletionDto CreatePostApiAiV1ChatCompletions(ctx).OpenAiChatCompletionRequestDto(openAiChatCompletionRequestDto).Execute()



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
	openAiChatCompletionRequestDto := *openapiclient.NewOpenAiChatCompletionRequestDto() // OpenAiChatCompletionRequestDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.OpenAiCompatibleChatAPI.CreatePostApiAiV1ChatCompletions(context.Background()).OpenAiChatCompletionRequestDto(openAiChatCompletionRequestDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OpenAiCompatibleChatAPI.CreatePostApiAiV1ChatCompletions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreatePostApiAiV1ChatCompletions`: AiChatCompletionDto
	fmt.Fprintf(os.Stdout, "Response from `OpenAiCompatibleChatAPI.CreatePostApiAiV1ChatCompletions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreatePostApiAiV1ChatCompletionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **openAiChatCompletionRequestDto** | [**OpenAiChatCompletionRequestDto**](OpenAiChatCompletionRequestDto.md) |  | 

### Return type

[**AiChatCompletionDto**](AiChatCompletionDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

