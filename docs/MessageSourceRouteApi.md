# \MessageSourceRouteAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateMessageSourceRoute**](MessageSourceRouteAPI.md#CreateMessageSourceRoute) | **Post** /api/app/message-source-route | 
[**DeleteMessageSourceRouteById**](MessageSourceRouteAPI.md#DeleteMessageSourceRouteById) | **Delete** /api/app/message-source-route/{id} | 
[**GetMessageSourceRouteById**](MessageSourceRouteAPI.md#GetMessageSourceRouteById) | **Get** /api/app/message-source-route/{id} | 
[**GetMessageSourceRouteList**](MessageSourceRouteAPI.md#GetMessageSourceRouteList) | **Get** /api/app/message-source-route | 
[**UpdateMessageSourceRoute**](MessageSourceRouteAPI.md#UpdateMessageSourceRoute) | **Put** /api/app/message-source-route/{id} | 



## CreateMessageSourceRoute

> CreateMessageSourceRoute(ctx).CreateUpdateMessageSourceRouteDto(createUpdateMessageSourceRouteDto).Execute()



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
	createUpdateMessageSourceRouteDto := *openapiclient.NewCreateUpdateMessageSourceRouteDto() // CreateUpdateMessageSourceRouteDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.MessageSourceRouteAPI.CreateMessageSourceRoute(context.Background()).CreateUpdateMessageSourceRouteDto(createUpdateMessageSourceRouteDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessageSourceRouteAPI.CreateMessageSourceRoute``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateMessageSourceRouteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createUpdateMessageSourceRouteDto** | [**CreateUpdateMessageSourceRouteDto**](CreateUpdateMessageSourceRouteDto.md) |  | 

### Return type

 (empty response body)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteMessageSourceRouteById

> DeleteMessageSourceRouteById(ctx, id).Execute()



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
	r, err := apiClient.MessageSourceRouteAPI.DeleteMessageSourceRouteById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessageSourceRouteAPI.DeleteMessageSourceRouteById``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteMessageSourceRouteByIdRequest struct via the builder pattern


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


## GetMessageSourceRouteById

> MessageSourceRouteDto GetMessageSourceRouteById(ctx, id).Execute()



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
	resp, r, err := apiClient.MessageSourceRouteAPI.GetMessageSourceRouteById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessageSourceRouteAPI.GetMessageSourceRouteById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMessageSourceRouteById`: MessageSourceRouteDto
	fmt.Fprintf(os.Stdout, "Response from `MessageSourceRouteAPI.GetMessageSourceRouteById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetMessageSourceRouteByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**MessageSourceRouteDto**](MessageSourceRouteDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetMessageSourceRouteList

> []MessageSourceRouteDto GetMessageSourceRouteList(ctx).SourceId(sourceId).Execute()



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
	sourceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MessageSourceRouteAPI.GetMessageSourceRouteList(context.Background()).SourceId(sourceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessageSourceRouteAPI.GetMessageSourceRouteList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMessageSourceRouteList`: []MessageSourceRouteDto
	fmt.Fprintf(os.Stdout, "Response from `MessageSourceRouteAPI.GetMessageSourceRouteList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetMessageSourceRouteListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sourceId** | **string** |  | 

### Return type

[**[]MessageSourceRouteDto**](MessageSourceRouteDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateMessageSourceRoute

> UpdateMessageSourceRoute(ctx, id).CreateUpdateMessageSourceRouteDto(createUpdateMessageSourceRouteDto).Execute()



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
	createUpdateMessageSourceRouteDto := *openapiclient.NewCreateUpdateMessageSourceRouteDto() // CreateUpdateMessageSourceRouteDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.MessageSourceRouteAPI.UpdateMessageSourceRoute(context.Background(), id).CreateUpdateMessageSourceRouteDto(createUpdateMessageSourceRouteDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessageSourceRouteAPI.UpdateMessageSourceRoute``: %v\n", err)
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

Other parameters are passed through a pointer to a apiUpdateMessageSourceRouteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createUpdateMessageSourceRouteDto** | [**CreateUpdateMessageSourceRouteDto**](CreateUpdateMessageSourceRouteDto.md) |  | 

### Return type

 (empty response body)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

