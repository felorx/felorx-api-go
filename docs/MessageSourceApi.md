# \MessageSourceAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateMessageSource**](MessageSourceAPI.md#CreateMessageSource) | **Post** /api/app/message-source | 
[**DeleteMessageSourceById**](MessageSourceAPI.md#DeleteMessageSourceById) | **Delete** /api/app/message-source/{id} | 
[**GetMessageSourceById**](MessageSourceAPI.md#GetMessageSourceById) | **Get** /api/app/message-source/{id} | 
[**GetMessageSourceList**](MessageSourceAPI.md#GetMessageSourceList) | **Get** /api/app/message-source | 
[**UpdateMessageSource**](MessageSourceAPI.md#UpdateMessageSource) | **Put** /api/app/message-source/{id} | 



## CreateMessageSource

> CreateUpdateMessageSourceDto CreateMessageSource(ctx).CreateUpdateMessageSourceDto(createUpdateMessageSourceDto).Execute()



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
	createUpdateMessageSourceDto := *openapiclient.NewCreateUpdateMessageSourceDto() // CreateUpdateMessageSourceDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MessageSourceAPI.CreateMessageSource(context.Background()).CreateUpdateMessageSourceDto(createUpdateMessageSourceDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessageSourceAPI.CreateMessageSource``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateMessageSource`: CreateUpdateMessageSourceDto
	fmt.Fprintf(os.Stdout, "Response from `MessageSourceAPI.CreateMessageSource`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateMessageSourceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createUpdateMessageSourceDto** | [**CreateUpdateMessageSourceDto**](CreateUpdateMessageSourceDto.md) |  | 

### Return type

[**CreateUpdateMessageSourceDto**](CreateUpdateMessageSourceDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteMessageSourceById

> DeleteMessageSourceById(ctx, id).Execute()



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
	r, err := apiClient.MessageSourceAPI.DeleteMessageSourceById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessageSourceAPI.DeleteMessageSourceById``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteMessageSourceByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetMessageSourceById

> MessageSourceDto GetMessageSourceById(ctx, id).Execute()



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
	resp, r, err := apiClient.MessageSourceAPI.GetMessageSourceById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessageSourceAPI.GetMessageSourceById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMessageSourceById`: MessageSourceDto
	fmt.Fprintf(os.Stdout, "Response from `MessageSourceAPI.GetMessageSourceById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetMessageSourceByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**MessageSourceDto**](MessageSourceDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetMessageSourceList

> []MessageSourceDto GetMessageSourceList(ctx).CategoryId(categoryId).Execute()



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
	categoryId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MessageSourceAPI.GetMessageSourceList(context.Background()).CategoryId(categoryId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessageSourceAPI.GetMessageSourceList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMessageSourceList`: []MessageSourceDto
	fmt.Fprintf(os.Stdout, "Response from `MessageSourceAPI.GetMessageSourceList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetMessageSourceListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **categoryId** | **string** |  | 

### Return type

[**[]MessageSourceDto**](MessageSourceDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateMessageSource

> CreateUpdateMessageSourceDto UpdateMessageSource(ctx, id).CreateUpdateMessageSourceDto(createUpdateMessageSourceDto).Execute()



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
	createUpdateMessageSourceDto := *openapiclient.NewCreateUpdateMessageSourceDto() // CreateUpdateMessageSourceDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MessageSourceAPI.UpdateMessageSource(context.Background(), id).CreateUpdateMessageSourceDto(createUpdateMessageSourceDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessageSourceAPI.UpdateMessageSource``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateMessageSource`: CreateUpdateMessageSourceDto
	fmt.Fprintf(os.Stdout, "Response from `MessageSourceAPI.UpdateMessageSource`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateMessageSourceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createUpdateMessageSourceDto** | [**CreateUpdateMessageSourceDto**](CreateUpdateMessageSourceDto.md) |  | 

### Return type

[**CreateUpdateMessageSourceDto**](CreateUpdateMessageSourceDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

