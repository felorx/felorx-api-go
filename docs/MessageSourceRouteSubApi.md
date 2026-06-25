# \MessageSourceRouteSubAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateMessageSourceRouteSub**](MessageSourceRouteSubAPI.md#CreateMessageSourceRouteSub) | **Post** /api/app/message-source-route-sub |
[**DeleteMessageSourceRouteSubById**](MessageSourceRouteSubAPI.md#DeleteMessageSourceRouteSubById) | **Delete** /api/app/message-source-route-sub/{id} |
[**GetMessageSourceRouteSubById**](MessageSourceRouteSubAPI.md#GetMessageSourceRouteSubById) | **Get** /api/app/message-source-route-sub/{id} |
[**GetMessageSourceRouteSubList**](MessageSourceRouteSubAPI.md#GetMessageSourceRouteSubList) | **Get** /api/app/message-source-route-sub |
[**UpdateMessageSourceRouteSub**](MessageSourceRouteSubAPI.md#UpdateMessageSourceRouteSub) | **Put** /api/app/message-source-route-sub/{id} |



## CreateMessageSourceRouteSub

> CreateMessageSourceRouteSub(ctx).CreateUpdateMessageSourceRouteSubDto(createUpdateMessageSourceRouteSubDto).Execute()



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
	createUpdateMessageSourceRouteSubDto := *openapiclient.NewCreateUpdateMessageSourceRouteSubDto() // CreateUpdateMessageSourceRouteSubDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.MessageSourceRouteSubAPI.CreateMessageSourceRouteSub(context.Background()).CreateUpdateMessageSourceRouteSubDto(createUpdateMessageSourceRouteSubDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessageSourceRouteSubAPI.CreateMessageSourceRouteSub``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateMessageSourceRouteSubRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createUpdateMessageSourceRouteSubDto** | [**CreateUpdateMessageSourceRouteSubDto**](CreateUpdateMessageSourceRouteSubDto.md) |  |

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteMessageSourceRouteSubById

> DeleteMessageSourceRouteSubById(ctx, id).Execute()



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
	r, err := apiClient.MessageSourceRouteSubAPI.DeleteMessageSourceRouteSubById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessageSourceRouteSubAPI.DeleteMessageSourceRouteSubById``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteMessageSourceRouteSubByIdRequest struct via the builder pattern


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


## GetMessageSourceRouteSubById

> MessageSourceRouteSubDto GetMessageSourceRouteSubById(ctx, id).Execute()



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
	resp, r, err := apiClient.MessageSourceRouteSubAPI.GetMessageSourceRouteSubById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessageSourceRouteSubAPI.GetMessageSourceRouteSubById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMessageSourceRouteSubById`: MessageSourceRouteSubDto
	fmt.Fprintf(os.Stdout, "Response from `MessageSourceRouteSubAPI.GetMessageSourceRouteSubById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiGetMessageSourceRouteSubByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**MessageSourceRouteSubDto**](MessageSourceRouteSubDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetMessageSourceRouteSubList

> []MessageSourceRouteSubDto GetMessageSourceRouteSubList(ctx).Execute()



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
	resp, r, err := apiClient.MessageSourceRouteSubAPI.GetMessageSourceRouteSubList(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessageSourceRouteSubAPI.GetMessageSourceRouteSubList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMessageSourceRouteSubList`: []MessageSourceRouteSubDto
	fmt.Fprintf(os.Stdout, "Response from `MessageSourceRouteSubAPI.GetMessageSourceRouteSubList`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetMessageSourceRouteSubListRequest struct via the builder pattern


### Return type

[**[]MessageSourceRouteSubDto**](MessageSourceRouteSubDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateMessageSourceRouteSub

> UpdateMessageSourceRouteSub(ctx, id).CreateUpdateMessageSourceRouteSubDto(createUpdateMessageSourceRouteSubDto).Execute()



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
	createUpdateMessageSourceRouteSubDto := *openapiclient.NewCreateUpdateMessageSourceRouteSubDto() // CreateUpdateMessageSourceRouteSubDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.MessageSourceRouteSubAPI.UpdateMessageSourceRouteSub(context.Background(), id).CreateUpdateMessageSourceRouteSubDto(createUpdateMessageSourceRouteSubDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MessageSourceRouteSubAPI.UpdateMessageSourceRouteSub``: %v\n", err)
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

Other parameters are passed through a pointer to a apiUpdateMessageSourceRouteSubRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createUpdateMessageSourceRouteSubDto** | [**CreateUpdateMessageSourceRouteSubDto**](CreateUpdateMessageSourceRouteSubDto.md) |  |

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

