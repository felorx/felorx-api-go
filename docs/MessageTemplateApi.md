# \MessageTemplateAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateMessageTemplate**](MessageTemplateAPI.md#CreateMessageTemplate) | **Post** /api/app/message-template | 
[**DeleteMessageTemplateById**](MessageTemplateAPI.md#DeleteMessageTemplateById) | **Delete** /api/app/message-template/{id} | 
[**GetMessageTemplateById**](MessageTemplateAPI.md#GetMessageTemplateById) | **Get** /api/app/message-template/{id} | 
[**GetMessageTemplateList**](MessageTemplateAPI.md#GetMessageTemplateList) | **Get** /api/app/message-template | 
[**UpdateMessageTemplate**](MessageTemplateAPI.md#UpdateMessageTemplate) | **Put** /api/app/message-template/{id} | 



## CreateMessageTemplate

> MessageTemplateDto CreateMessageTemplate(ctx).CreateOrUpdateMessageTemplateDto(createOrUpdateMessageTemplateDto).Execute()



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
	createOrUpdateMessageTemplateDto := *openapiclient.NewCreateOrUpdateMessageTemplateDto() // CreateOrUpdateMessageTemplateDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MessageTemplateAPI.CreateMessageTemplate(context.Background()).CreateOrUpdateMessageTemplateDto(createOrUpdateMessageTemplateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessageTemplateAPI.CreateMessageTemplate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateMessageTemplate`: MessageTemplateDto
	fmt.Fprintf(os.Stdout, "Response from `MessageTemplateAPI.CreateMessageTemplate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateMessageTemplateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createOrUpdateMessageTemplateDto** | [**CreateOrUpdateMessageTemplateDto**](CreateOrUpdateMessageTemplateDto.md) |  | 

### Return type

[**MessageTemplateDto**](MessageTemplateDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteMessageTemplateById

> DeleteMessageTemplateById(ctx, id).Execute()



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.MessageTemplateAPI.DeleteMessageTemplateById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessageTemplateAPI.DeleteMessageTemplateById``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteMessageTemplateByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetMessageTemplateById

> MessageTemplateDto GetMessageTemplateById(ctx, id).Execute()



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MessageTemplateAPI.GetMessageTemplateById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessageTemplateAPI.GetMessageTemplateById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMessageTemplateById`: MessageTemplateDto
	fmt.Fprintf(os.Stdout, "Response from `MessageTemplateAPI.GetMessageTemplateById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetMessageTemplateByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**MessageTemplateDto**](MessageTemplateDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetMessageTemplateList

> []MessageTemplateDto GetMessageTemplateList(ctx).Execute()



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
	resp, r, err := apiClient.MessageTemplateAPI.GetMessageTemplateList(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessageTemplateAPI.GetMessageTemplateList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMessageTemplateList`: []MessageTemplateDto
	fmt.Fprintf(os.Stdout, "Response from `MessageTemplateAPI.GetMessageTemplateList`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetMessageTemplateListRequest struct via the builder pattern


### Return type

[**[]MessageTemplateDto**](MessageTemplateDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateMessageTemplate

> MessageTemplateDto UpdateMessageTemplate(ctx, id).CreateOrUpdateMessageTemplateDto(createOrUpdateMessageTemplateDto).Execute()



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	createOrUpdateMessageTemplateDto := *openapiclient.NewCreateOrUpdateMessageTemplateDto() // CreateOrUpdateMessageTemplateDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MessageTemplateAPI.UpdateMessageTemplate(context.Background(), id).CreateOrUpdateMessageTemplateDto(createOrUpdateMessageTemplateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessageTemplateAPI.UpdateMessageTemplate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateMessageTemplate`: MessageTemplateDto
	fmt.Fprintf(os.Stdout, "Response from `MessageTemplateAPI.UpdateMessageTemplate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateMessageTemplateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createOrUpdateMessageTemplateDto** | [**CreateOrUpdateMessageTemplateDto**](CreateOrUpdateMessageTemplateDto.md) |  | 

### Return type

[**MessageTemplateDto**](MessageTemplateDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

