# \MessageTemplateReleaseAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateMessageTemplateRelease**](MessageTemplateReleaseAPI.md#CreateMessageTemplateRelease) | **Post** /api/app/message-template-release | 
[**GetMessageTemplateReleaseById**](MessageTemplateReleaseAPI.md#GetMessageTemplateReleaseById) | **Get** /api/app/message-template-release/{id} | 
[**GetMessageTemplateReleaseList**](MessageTemplateReleaseAPI.md#GetMessageTemplateReleaseList) | **Get** /api/app/message-template-release | 



## CreateMessageTemplateRelease

> MessageTemplateReleaseDto CreateMessageTemplateRelease(ctx).CreateMessageTemplateReleaseDto(createMessageTemplateReleaseDto).Execute()



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
	createMessageTemplateReleaseDto := *openapiclient.NewCreateMessageTemplateReleaseDto() // CreateMessageTemplateReleaseDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MessageTemplateReleaseAPI.CreateMessageTemplateRelease(context.Background()).CreateMessageTemplateReleaseDto(createMessageTemplateReleaseDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessageTemplateReleaseAPI.CreateMessageTemplateRelease``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateMessageTemplateRelease`: MessageTemplateReleaseDto
	fmt.Fprintf(os.Stdout, "Response from `MessageTemplateReleaseAPI.CreateMessageTemplateRelease`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateMessageTemplateReleaseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createMessageTemplateReleaseDto** | [**CreateMessageTemplateReleaseDto**](CreateMessageTemplateReleaseDto.md) |  | 

### Return type

[**MessageTemplateReleaseDto**](MessageTemplateReleaseDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetMessageTemplateReleaseById

> MessageTemplateReleaseDto GetMessageTemplateReleaseById(ctx, id).Execute()



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
	resp, r, err := apiClient.MessageTemplateReleaseAPI.GetMessageTemplateReleaseById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessageTemplateReleaseAPI.GetMessageTemplateReleaseById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMessageTemplateReleaseById`: MessageTemplateReleaseDto
	fmt.Fprintf(os.Stdout, "Response from `MessageTemplateReleaseAPI.GetMessageTemplateReleaseById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetMessageTemplateReleaseByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**MessageTemplateReleaseDto**](MessageTemplateReleaseDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetMessageTemplateReleaseList

> []MessageTemplateReleaseDto GetMessageTemplateReleaseList(ctx).TemplateId(templateId).Execute()



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
	templateId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MessageTemplateReleaseAPI.GetMessageTemplateReleaseList(context.Background()).TemplateId(templateId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessageTemplateReleaseAPI.GetMessageTemplateReleaseList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMessageTemplateReleaseList`: []MessageTemplateReleaseDto
	fmt.Fprintf(os.Stdout, "Response from `MessageTemplateReleaseAPI.GetMessageTemplateReleaseList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetMessageTemplateReleaseListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **templateId** | **string** |  | 

### Return type

[**[]MessageTemplateReleaseDto**](MessageTemplateReleaseDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

