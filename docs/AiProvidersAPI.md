# \AiProvidersAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AiProvidersSetDefaultModel**](AiProvidersAPI.md#AiProvidersSetDefaultModel) | **Post** /api/ai/providers/default-model |
[**AiProvidersSetEnabled**](AiProvidersAPI.md#AiProvidersSetEnabled) | **Post** /api/ai/providers/{id}/enabled |
[**AiProvidersTest**](AiProvidersAPI.md#AiProvidersTest) | **Post** /api/ai/providers/{id}/test |
[**Create**](AiProvidersAPI.md#Create) | **Post** /api/ai/providers |
[**DeleteById**](AiProvidersAPI.md#DeleteById) | **Delete** /api/ai/providers/{id} |
[**GetById**](AiProvidersAPI.md#GetById) | **Get** /api/ai/providers/{id} |
[**GetList**](AiProvidersAPI.md#GetList) | **Get** /api/ai/providers |
[**Update**](AiProvidersAPI.md#Update) | **Put** /api/ai/providers/{id} |



## AiProvidersSetDefaultModel

> AiProviderDto AiProvidersSetDefaultModel(ctx).SetDefaultAiModelDto(setDefaultAiModelDto).Execute()



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
	setDefaultAiModelDto := *openapiclient.NewSetDefaultAiModelDto() // SetDefaultAiModelDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiProvidersAPI.AiProvidersSetDefaultModel(context.Background()).SetDefaultAiModelDto(setDefaultAiModelDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiProvidersAPI.AiProvidersSetDefaultModel``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AiProvidersSetDefaultModel`: AiProviderDto
	fmt.Fprintf(os.Stdout, "Response from `AiProvidersAPI.AiProvidersSetDefaultModel`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAiProvidersSetDefaultModelRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **setDefaultAiModelDto** | [**SetDefaultAiModelDto**](SetDefaultAiModelDto.md) |  |

### Return type

[**AiProviderDto**](AiProviderDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AiProvidersSetEnabled

> AiProviderDto AiProvidersSetEnabled(ctx, id).SetAiProviderEnabledDto(setAiProviderEnabledDto).Execute()



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
	setAiProviderEnabledDto := *openapiclient.NewSetAiProviderEnabledDto() // SetAiProviderEnabledDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiProvidersAPI.AiProvidersSetEnabled(context.Background(), id).SetAiProviderEnabledDto(setAiProviderEnabledDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiProvidersAPI.AiProvidersSetEnabled``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AiProvidersSetEnabled`: AiProviderDto
	fmt.Fprintf(os.Stdout, "Response from `AiProvidersAPI.AiProvidersSetEnabled`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiAiProvidersSetEnabledRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **setAiProviderEnabledDto** | [**SetAiProviderEnabledDto**](SetAiProviderEnabledDto.md) |  |

### Return type

[**AiProviderDto**](AiProviderDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AiProvidersTest

> AiProviderDto AiProvidersTest(ctx, id).TestAiProviderDto(testAiProviderDto).Execute()



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
	testAiProviderDto := *openapiclient.NewTestAiProviderDto() // TestAiProviderDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiProvidersAPI.AiProvidersTest(context.Background(), id).TestAiProviderDto(testAiProviderDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiProvidersAPI.AiProvidersTest``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AiProvidersTest`: AiProviderDto
	fmt.Fprintf(os.Stdout, "Response from `AiProvidersAPI.AiProvidersTest`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiAiProvidersTestRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **testAiProviderDto** | [**TestAiProviderDto**](TestAiProviderDto.md) |  |

### Return type

[**AiProviderDto**](AiProviderDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## Create

> AiProviderDto Create(ctx).CreateOrUpdateAiProviderDto(createOrUpdateAiProviderDto).Execute()



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
	createOrUpdateAiProviderDto := *openapiclient.NewCreateOrUpdateAiProviderDto() // CreateOrUpdateAiProviderDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiProvidersAPI.Create(context.Background()).CreateOrUpdateAiProviderDto(createOrUpdateAiProviderDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiProvidersAPI.Create``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Create`: AiProviderDto
	fmt.Fprintf(os.Stdout, "Response from `AiProvidersAPI.Create`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createOrUpdateAiProviderDto** | [**CreateOrUpdateAiProviderDto**](CreateOrUpdateAiProviderDto.md) |  |

### Return type

[**AiProviderDto**](AiProviderDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteById

> DeleteById(ctx, id).Execute()



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
	r, err := apiClient.AiProvidersAPI.DeleteById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiProvidersAPI.DeleteById``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetById

> AiProviderDto GetById(ctx, id).Execute()



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
	resp, r, err := apiClient.AiProvidersAPI.GetById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiProvidersAPI.GetById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetById`: AiProviderDto
	fmt.Fprintf(os.Stdout, "Response from `AiProvidersAPI.GetById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiGetByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AiProviderDto**](AiProviderDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetList

> AiProviderDtoPagedResultDto GetList(ctx).Filter(filter).ProviderType(providerType).ProviderType2(providerType2).Capability(capability).Enabled(enabled).SkipCount(skipCount).MaxResultCount(maxResultCount).Sorting(sorting).Execute()



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
	filter := "filter_example" // string |  (optional)
	providerType := openapiclient.AiProviderType("Mock") // AiProviderType |  (optional)
	providerType2 := openapiclient.AiProviderType("Mock") // AiProviderType |  (optional)
	capability := openapiclient.AiCapability("Chat") // AiCapability |  (optional)
	enabled := true // bool |  (optional)
	skipCount := int32(56) // int32 |  (optional) (default to 0)
	maxResultCount := int32(56) // int32 |  (optional) (default to 10)
	sorting := "sorting_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiProvidersAPI.GetList(context.Background()).Filter(filter).ProviderType(providerType).ProviderType2(providerType2).Capability(capability).Enabled(enabled).SkipCount(skipCount).MaxResultCount(maxResultCount).Sorting(sorting).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiProvidersAPI.GetList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetList`: AiProviderDtoPagedResultDto
	fmt.Fprintf(os.Stdout, "Response from `AiProvidersAPI.GetList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **string** |  |
 **providerType** | [**AiProviderType**](AiProviderType.md) |  |
 **providerType2** | [**AiProviderType**](AiProviderType.md) |  |
 **capability** | [**AiCapability**](AiCapability.md) |  |
 **enabled** | **bool** |  |
 **skipCount** | **int32** |  | [default to 0]
 **maxResultCount** | **int32** |  | [default to 10]
 **sorting** | **string** |  |

### Return type

[**AiProviderDtoPagedResultDto**](AiProviderDtoPagedResultDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## Update

> AiProviderDto Update(ctx, id).CreateOrUpdateAiProviderDto(createOrUpdateAiProviderDto).Execute()



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
	createOrUpdateAiProviderDto := *openapiclient.NewCreateOrUpdateAiProviderDto() // CreateOrUpdateAiProviderDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AiProvidersAPI.Update(context.Background(), id).CreateOrUpdateAiProviderDto(createOrUpdateAiProviderDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AiProvidersAPI.Update``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Update`: AiProviderDto
	fmt.Fprintf(os.Stdout, "Response from `AiProvidersAPI.Update`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createOrUpdateAiProviderDto** | [**CreateOrUpdateAiProviderDto**](CreateOrUpdateAiProviderDto.md) |  |

### Return type

[**AiProviderDto**](AiProviderDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

