# \ResponsesAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CancelResponse**](ResponsesAPI.md#CancelResponse) | **Post** /api/ai/v1/responses/{id}/cancel | 
[**CancelResponseLegacy**](ResponsesAPI.md#CancelResponseLegacy) | **Post** /api/ai/openai/responses/{id}/cancel | 
[**CompactResponse**](ResponsesAPI.md#CompactResponse) | **Post** /api/ai/v1/responses/compact | 
[**CompactResponseLegacy**](ResponsesAPI.md#CompactResponseLegacy) | **Post** /api/ai/openai/responses/compact | 
[**CountResponseInputTokens**](ResponsesAPI.md#CountResponseInputTokens) | **Post** /api/ai/v1/responses/input_tokens | 
[**CountResponseInputTokensLegacy**](ResponsesAPI.md#CountResponseInputTokensLegacy) | **Post** /api/ai/openai/responses/input_tokens | 
[**CreateResponse**](ResponsesAPI.md#CreateResponse) | **Post** /api/ai/v1/responses | 
[**CreateResponseLegacy**](ResponsesAPI.md#CreateResponseLegacy) | **Post** /api/ai/openai/responses | 
[**DeleteResponse**](ResponsesAPI.md#DeleteResponse) | **Delete** /api/ai/v1/responses/{id} | 
[**DeleteResponseLegacy**](ResponsesAPI.md#DeleteResponseLegacy) | **Delete** /api/ai/openai/responses/{id} | 
[**ListResponseInputItems**](ResponsesAPI.md#ListResponseInputItems) | **Get** /api/ai/v1/responses/{id}/input_items | 
[**ListResponseInputItemsLegacy**](ResponsesAPI.md#ListResponseInputItemsLegacy) | **Get** /api/ai/openai/responses/{id}/input_items | 
[**RetrieveResponse**](ResponsesAPI.md#RetrieveResponse) | **Get** /api/ai/v1/responses/{id} | 
[**RetrieveResponseLegacy**](ResponsesAPI.md#RetrieveResponseLegacy) | **Get** /api/ai/openai/responses/{id} | 



## CancelResponse

> FelorxResponse CancelResponse(ctx, id).XFelorxAiProvider(xFelorxAiProvider).Execute()





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
	id := "id_example" // string | 
	xFelorxAiProvider := "xFelorxAiProvider_example" // string | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ResponsesAPI.CancelResponse(context.Background(), id).XFelorxAiProvider(xFelorxAiProvider).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResponsesAPI.CancelResponse``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CancelResponse`: FelorxResponse
	fmt.Fprintf(os.Stdout, "Response from `ResponsesAPI.CancelResponse`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCancelResponseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xFelorxAiProvider** | **string** | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. | 

### Return type

[**FelorxResponse**](FelorxResponse.md)

### Authorization

[FelorxBearer](../README.md#FelorxBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CancelResponseLegacy

> FelorxResponse CancelResponseLegacy(ctx, id).XFelorxAiProvider(xFelorxAiProvider).Execute()





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
	id := "id_example" // string | 
	xFelorxAiProvider := "xFelorxAiProvider_example" // string | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ResponsesAPI.CancelResponseLegacy(context.Background(), id).XFelorxAiProvider(xFelorxAiProvider).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResponsesAPI.CancelResponseLegacy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CancelResponseLegacy`: FelorxResponse
	fmt.Fprintf(os.Stdout, "Response from `ResponsesAPI.CancelResponseLegacy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCancelResponseLegacyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xFelorxAiProvider** | **string** | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. | 

### Return type

[**FelorxResponse**](FelorxResponse.md)

### Authorization

[FelorxBearer](../README.md#FelorxBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CompactResponse

> FelorxCompactedResponse CompactResponse(ctx).FelorxResponsesCompactRequest(felorxResponsesCompactRequest).XFelorxAiProvider(xFelorxAiProvider).Execute()





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
	felorxResponsesCompactRequest := *openapiclient.NewFelorxResponsesCompactRequest() // FelorxResponsesCompactRequest | JSON object, at most 8 MiB. Duplicate property names are rejected.
	xFelorxAiProvider := "xFelorxAiProvider_example" // string | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ResponsesAPI.CompactResponse(context.Background()).FelorxResponsesCompactRequest(felorxResponsesCompactRequest).XFelorxAiProvider(xFelorxAiProvider).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResponsesAPI.CompactResponse``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CompactResponse`: FelorxCompactedResponse
	fmt.Fprintf(os.Stdout, "Response from `ResponsesAPI.CompactResponse`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCompactResponseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **felorxResponsesCompactRequest** | [**FelorxResponsesCompactRequest**](FelorxResponsesCompactRequest.md) | JSON object, at most 8 MiB. Duplicate property names are rejected. | 
 **xFelorxAiProvider** | **string** | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. | 

### Return type

[**FelorxCompactedResponse**](FelorxCompactedResponse.md)

### Authorization

[FelorxBearer](../README.md#FelorxBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CompactResponseLegacy

> FelorxCompactedResponse CompactResponseLegacy(ctx).FelorxResponsesCompactRequest(felorxResponsesCompactRequest).XFelorxAiProvider(xFelorxAiProvider).Execute()





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
	felorxResponsesCompactRequest := *openapiclient.NewFelorxResponsesCompactRequest() // FelorxResponsesCompactRequest | JSON object, at most 8 MiB. Duplicate property names are rejected.
	xFelorxAiProvider := "xFelorxAiProvider_example" // string | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ResponsesAPI.CompactResponseLegacy(context.Background()).FelorxResponsesCompactRequest(felorxResponsesCompactRequest).XFelorxAiProvider(xFelorxAiProvider).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResponsesAPI.CompactResponseLegacy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CompactResponseLegacy`: FelorxCompactedResponse
	fmt.Fprintf(os.Stdout, "Response from `ResponsesAPI.CompactResponseLegacy`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCompactResponseLegacyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **felorxResponsesCompactRequest** | [**FelorxResponsesCompactRequest**](FelorxResponsesCompactRequest.md) | JSON object, at most 8 MiB. Duplicate property names are rejected. | 
 **xFelorxAiProvider** | **string** | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. | 

### Return type

[**FelorxCompactedResponse**](FelorxCompactedResponse.md)

### Authorization

[FelorxBearer](../README.md#FelorxBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CountResponseInputTokens

> FelorxResponseInputTokens CountResponseInputTokens(ctx).FelorxResponsesCountRequest(felorxResponsesCountRequest).XFelorxAiProvider(xFelorxAiProvider).Execute()





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
	felorxResponsesCountRequest := *openapiclient.NewFelorxResponsesCountRequest() // FelorxResponsesCountRequest | JSON object, at most 8 MiB. Duplicate property names are rejected.
	xFelorxAiProvider := "xFelorxAiProvider_example" // string | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ResponsesAPI.CountResponseInputTokens(context.Background()).FelorxResponsesCountRequest(felorxResponsesCountRequest).XFelorxAiProvider(xFelorxAiProvider).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResponsesAPI.CountResponseInputTokens``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CountResponseInputTokens`: FelorxResponseInputTokens
	fmt.Fprintf(os.Stdout, "Response from `ResponsesAPI.CountResponseInputTokens`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCountResponseInputTokensRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **felorxResponsesCountRequest** | [**FelorxResponsesCountRequest**](FelorxResponsesCountRequest.md) | JSON object, at most 8 MiB. Duplicate property names are rejected. | 
 **xFelorxAiProvider** | **string** | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. | 

### Return type

[**FelorxResponseInputTokens**](FelorxResponseInputTokens.md)

### Authorization

[FelorxBearer](../README.md#FelorxBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CountResponseInputTokensLegacy

> FelorxResponseInputTokens CountResponseInputTokensLegacy(ctx).FelorxResponsesCountRequest(felorxResponsesCountRequest).XFelorxAiProvider(xFelorxAiProvider).Execute()





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
	felorxResponsesCountRequest := *openapiclient.NewFelorxResponsesCountRequest() // FelorxResponsesCountRequest | JSON object, at most 8 MiB. Duplicate property names are rejected.
	xFelorxAiProvider := "xFelorxAiProvider_example" // string | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ResponsesAPI.CountResponseInputTokensLegacy(context.Background()).FelorxResponsesCountRequest(felorxResponsesCountRequest).XFelorxAiProvider(xFelorxAiProvider).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResponsesAPI.CountResponseInputTokensLegacy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CountResponseInputTokensLegacy`: FelorxResponseInputTokens
	fmt.Fprintf(os.Stdout, "Response from `ResponsesAPI.CountResponseInputTokensLegacy`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCountResponseInputTokensLegacyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **felorxResponsesCountRequest** | [**FelorxResponsesCountRequest**](FelorxResponsesCountRequest.md) | JSON object, at most 8 MiB. Duplicate property names are rejected. | 
 **xFelorxAiProvider** | **string** | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. | 

### Return type

[**FelorxResponseInputTokens**](FelorxResponseInputTokens.md)

### Authorization

[FelorxBearer](../README.md#FelorxBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateResponse

> FelorxResponse CreateResponse(ctx).FelorxResponsesCreateRequest(felorxResponsesCreateRequest).XFelorxAiProvider(xFelorxAiProvider).Execute()





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
	felorxResponsesCreateRequest := *openapiclient.NewFelorxResponsesCreateRequest() // FelorxResponsesCreateRequest | JSON object, at most 8 MiB. Duplicate property names are rejected.
	xFelorxAiProvider := "xFelorxAiProvider_example" // string | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ResponsesAPI.CreateResponse(context.Background()).FelorxResponsesCreateRequest(felorxResponsesCreateRequest).XFelorxAiProvider(xFelorxAiProvider).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResponsesAPI.CreateResponse``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateResponse`: FelorxResponse
	fmt.Fprintf(os.Stdout, "Response from `ResponsesAPI.CreateResponse`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateResponseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **felorxResponsesCreateRequest** | [**FelorxResponsesCreateRequest**](FelorxResponsesCreateRequest.md) | JSON object, at most 8 MiB. Duplicate property names are rejected. | 
 **xFelorxAiProvider** | **string** | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. | 

### Return type

[**FelorxResponse**](FelorxResponse.md)

### Authorization

[FelorxBearer](../README.md#FelorxBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, text/event-stream

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateResponseLegacy

> FelorxResponse CreateResponseLegacy(ctx).FelorxResponsesCreateRequest(felorxResponsesCreateRequest).XFelorxAiProvider(xFelorxAiProvider).Execute()





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
	felorxResponsesCreateRequest := *openapiclient.NewFelorxResponsesCreateRequest() // FelorxResponsesCreateRequest | JSON object, at most 8 MiB. Duplicate property names are rejected.
	xFelorxAiProvider := "xFelorxAiProvider_example" // string | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ResponsesAPI.CreateResponseLegacy(context.Background()).FelorxResponsesCreateRequest(felorxResponsesCreateRequest).XFelorxAiProvider(xFelorxAiProvider).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResponsesAPI.CreateResponseLegacy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateResponseLegacy`: FelorxResponse
	fmt.Fprintf(os.Stdout, "Response from `ResponsesAPI.CreateResponseLegacy`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateResponseLegacyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **felorxResponsesCreateRequest** | [**FelorxResponsesCreateRequest**](FelorxResponsesCreateRequest.md) | JSON object, at most 8 MiB. Duplicate property names are rejected. | 
 **xFelorxAiProvider** | **string** | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. | 

### Return type

[**FelorxResponse**](FelorxResponse.md)

### Authorization

[FelorxBearer](../README.md#FelorxBearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, text/event-stream

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteResponse

> FelorxDeletedResponse DeleteResponse(ctx, id).XFelorxAiProvider(xFelorxAiProvider).Execute()





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
	id := "id_example" // string | 
	xFelorxAiProvider := "xFelorxAiProvider_example" // string | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ResponsesAPI.DeleteResponse(context.Background(), id).XFelorxAiProvider(xFelorxAiProvider).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResponsesAPI.DeleteResponse``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteResponse`: FelorxDeletedResponse
	fmt.Fprintf(os.Stdout, "Response from `ResponsesAPI.DeleteResponse`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteResponseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xFelorxAiProvider** | **string** | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. | 

### Return type

[**FelorxDeletedResponse**](FelorxDeletedResponse.md)

### Authorization

[FelorxBearer](../README.md#FelorxBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteResponseLegacy

> FelorxDeletedResponse DeleteResponseLegacy(ctx, id).XFelorxAiProvider(xFelorxAiProvider).Execute()





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
	id := "id_example" // string | 
	xFelorxAiProvider := "xFelorxAiProvider_example" // string | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ResponsesAPI.DeleteResponseLegacy(context.Background(), id).XFelorxAiProvider(xFelorxAiProvider).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResponsesAPI.DeleteResponseLegacy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteResponseLegacy`: FelorxDeletedResponse
	fmt.Fprintf(os.Stdout, "Response from `ResponsesAPI.DeleteResponseLegacy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteResponseLegacyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xFelorxAiProvider** | **string** | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. | 

### Return type

[**FelorxDeletedResponse**](FelorxDeletedResponse.md)

### Authorization

[FelorxBearer](../README.md#FelorxBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListResponseInputItems

> FelorxResponseInputItems ListResponseInputItems(ctx, id).After(after).Limit(limit).Order(order).XFelorxAiProvider(xFelorxAiProvider).Execute()





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
	id := "id_example" // string | 
	after := "after_example" // string |  (optional)
	limit := int32(56) // int32 |  (optional)
	order := "order_example" // string |  (optional)
	xFelorxAiProvider := "xFelorxAiProvider_example" // string | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ResponsesAPI.ListResponseInputItems(context.Background(), id).After(after).Limit(limit).Order(order).XFelorxAiProvider(xFelorxAiProvider).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResponsesAPI.ListResponseInputItems``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListResponseInputItems`: FelorxResponseInputItems
	fmt.Fprintf(os.Stdout, "Response from `ResponsesAPI.ListResponseInputItems`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListResponseInputItemsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **after** | **string** |  | 
 **limit** | **int32** |  | 
 **order** | **string** |  | 
 **xFelorxAiProvider** | **string** | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. | 

### Return type

[**FelorxResponseInputItems**](FelorxResponseInputItems.md)

### Authorization

[FelorxBearer](../README.md#FelorxBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListResponseInputItemsLegacy

> FelorxResponseInputItems ListResponseInputItemsLegacy(ctx, id).After(after).Limit(limit).Order(order).XFelorxAiProvider(xFelorxAiProvider).Execute()





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
	id := "id_example" // string | 
	after := "after_example" // string |  (optional)
	limit := int32(56) // int32 |  (optional)
	order := "order_example" // string |  (optional)
	xFelorxAiProvider := "xFelorxAiProvider_example" // string | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ResponsesAPI.ListResponseInputItemsLegacy(context.Background(), id).After(after).Limit(limit).Order(order).XFelorxAiProvider(xFelorxAiProvider).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResponsesAPI.ListResponseInputItemsLegacy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListResponseInputItemsLegacy`: FelorxResponseInputItems
	fmt.Fprintf(os.Stdout, "Response from `ResponsesAPI.ListResponseInputItemsLegacy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListResponseInputItemsLegacyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **after** | **string** |  | 
 **limit** | **int32** |  | 
 **order** | **string** |  | 
 **xFelorxAiProvider** | **string** | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. | 

### Return type

[**FelorxResponseInputItems**](FelorxResponseInputItems.md)

### Authorization

[FelorxBearer](../README.md#FelorxBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RetrieveResponse

> FelorxResponse RetrieveResponse(ctx, id).XFelorxAiProvider(xFelorxAiProvider).Execute()





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
	id := "id_example" // string | 
	xFelorxAiProvider := "xFelorxAiProvider_example" // string | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ResponsesAPI.RetrieveResponse(context.Background(), id).XFelorxAiProvider(xFelorxAiProvider).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResponsesAPI.RetrieveResponse``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RetrieveResponse`: FelorxResponse
	fmt.Fprintf(os.Stdout, "Response from `ResponsesAPI.RetrieveResponse`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRetrieveResponseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xFelorxAiProvider** | **string** | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. | 

### Return type

[**FelorxResponse**](FelorxResponse.md)

### Authorization

[FelorxBearer](../README.md#FelorxBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RetrieveResponseLegacy

> FelorxResponse RetrieveResponseLegacy(ctx, id).XFelorxAiProvider(xFelorxAiProvider).Execute()





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
	id := "id_example" // string | 
	xFelorxAiProvider := "xFelorxAiProvider_example" // string | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ResponsesAPI.RetrieveResponseLegacy(context.Background(), id).XFelorxAiProvider(xFelorxAiProvider).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ResponsesAPI.RetrieveResponseLegacy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RetrieveResponseLegacy`: FelorxResponse
	fmt.Fprintf(os.Stdout, "Response from `ResponsesAPI.RetrieveResponseLegacy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRetrieveResponseLegacyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xFelorxAiProvider** | **string** | Optional server-configured provider ID or name. Stored responses remain bound to their original provider. | 

### Return type

[**FelorxResponse**](FelorxResponse.md)

### Authorization

[FelorxBearer](../README.md#FelorxBearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

