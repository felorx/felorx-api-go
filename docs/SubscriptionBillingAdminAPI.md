# \SubscriptionBillingAdminAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreatePlanPrice**](SubscriptionBillingAdminAPI.md#CreatePlanPrice) | **Post** /api/app/subscription-billing-admin/plan-prices |
[**DeletePlanPrice**](SubscriptionBillingAdminAPI.md#DeletePlanPrice) | **Delete** /api/app/subscription-billing-admin/plan-prices/{id} |
[**DeleteStoreMapping**](SubscriptionBillingAdminAPI.md#DeleteStoreMapping) | **Delete** /api/app/subscription-billing-admin/store-mappings/{id} |
[**GetPlanPrice**](SubscriptionBillingAdminAPI.md#GetPlanPrice) | **Get** /api/app/subscription-billing-admin/plan-prices/{id} |
[**GetPlanPricesByAppId**](SubscriptionBillingAdminAPI.md#GetPlanPricesByAppId) | **Get** /api/app/subscription-billing-admin/plan-prices/by-app-id/{appId} |
[**GetPlanPricesByPricingId**](SubscriptionBillingAdminAPI.md#GetPlanPricesByPricingId) | **Get** /api/app/subscription-billing-admin/plan-prices/by-pricing-id/{pricingId} |
[**GetStoreMappingsByAppId**](SubscriptionBillingAdminAPI.md#GetStoreMappingsByAppId) | **Get** /api/app/subscription-billing-admin/store-mappings/by-app-id/{appId} |
[**GetStoreMappingsByPlanPriceId**](SubscriptionBillingAdminAPI.md#GetStoreMappingsByPlanPriceId) | **Get** /api/app/subscription-billing-admin/store-mappings/by-plan-price-id/{planPriceId} |
[**UpdatePlanPrice**](SubscriptionBillingAdminAPI.md#UpdatePlanPrice) | **Put** /api/app/subscription-billing-admin/plan-prices/{id} |
[**UpsertStoreMapping**](SubscriptionBillingAdminAPI.md#UpsertStoreMapping) | **Post** /api/app/subscription-billing-admin/store-mappings/upsert |



## CreatePlanPrice

> AppPlanPriceDto CreatePlanPrice(ctx).CreateOrUpdateAppPlanPriceDto(createOrUpdateAppPlanPriceDto).Execute()



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
	createOrUpdateAppPlanPriceDto := *openapiclient.NewCreateOrUpdateAppPlanPriceDto() // CreateOrUpdateAppPlanPriceDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SubscriptionBillingAdminAPI.CreatePlanPrice(context.Background()).CreateOrUpdateAppPlanPriceDto(createOrUpdateAppPlanPriceDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionBillingAdminAPI.CreatePlanPrice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreatePlanPrice`: AppPlanPriceDto
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionBillingAdminAPI.CreatePlanPrice`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreatePlanPriceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createOrUpdateAppPlanPriceDto** | [**CreateOrUpdateAppPlanPriceDto**](CreateOrUpdateAppPlanPriceDto.md) |  |

### Return type

[**AppPlanPriceDto**](AppPlanPriceDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeletePlanPrice

> DeletePlanPrice(ctx, id).Execute()



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
	r, err := apiClient.SubscriptionBillingAdminAPI.DeletePlanPrice(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionBillingAdminAPI.DeletePlanPrice``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeletePlanPriceRequest struct via the builder pattern


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


## DeleteStoreMapping

> DeleteStoreMapping(ctx, id).Execute()



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
	r, err := apiClient.SubscriptionBillingAdminAPI.DeleteStoreMapping(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionBillingAdminAPI.DeleteStoreMapping``: %v\n", err)
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

Other parameters are passed through a pointer to a apiDeleteStoreMappingRequest struct via the builder pattern


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


## GetPlanPrice

> AppPlanPriceDto GetPlanPrice(ctx, id).Execute()



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
	resp, r, err := apiClient.SubscriptionBillingAdminAPI.GetPlanPrice(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionBillingAdminAPI.GetPlanPrice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPlanPrice`: AppPlanPriceDto
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionBillingAdminAPI.GetPlanPrice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiGetPlanPriceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AppPlanPriceDto**](AppPlanPriceDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPlanPricesByAppId

> []AppPlanPriceDto GetPlanPricesByAppId(ctx, appId).Execute()



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
	appId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SubscriptionBillingAdminAPI.GetPlanPricesByAppId(context.Background(), appId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionBillingAdminAPI.GetPlanPricesByAppId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPlanPricesByAppId`: []AppPlanPriceDto
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionBillingAdminAPI.GetPlanPricesByAppId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**appId** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiGetPlanPricesByAppIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]AppPlanPriceDto**](AppPlanPriceDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPlanPricesByPricingId

> []AppPlanPriceDto GetPlanPricesByPricingId(ctx, pricingId).Execute()



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
	pricingId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SubscriptionBillingAdminAPI.GetPlanPricesByPricingId(context.Background(), pricingId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionBillingAdminAPI.GetPlanPricesByPricingId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPlanPricesByPricingId`: []AppPlanPriceDto
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionBillingAdminAPI.GetPlanPricesByPricingId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**pricingId** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiGetPlanPricesByPricingIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]AppPlanPriceDto**](AppPlanPriceDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetStoreMappingsByAppId

> []StoreProductMappingDto GetStoreMappingsByAppId(ctx, appId).Execute()



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
	appId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SubscriptionBillingAdminAPI.GetStoreMappingsByAppId(context.Background(), appId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionBillingAdminAPI.GetStoreMappingsByAppId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetStoreMappingsByAppId`: []StoreProductMappingDto
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionBillingAdminAPI.GetStoreMappingsByAppId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**appId** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiGetStoreMappingsByAppIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]StoreProductMappingDto**](StoreProductMappingDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetStoreMappingsByPlanPriceId

> []StoreProductMappingDto GetStoreMappingsByPlanPriceId(ctx, planPriceId).Execute()



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
	planPriceId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SubscriptionBillingAdminAPI.GetStoreMappingsByPlanPriceId(context.Background(), planPriceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionBillingAdminAPI.GetStoreMappingsByPlanPriceId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetStoreMappingsByPlanPriceId`: []StoreProductMappingDto
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionBillingAdminAPI.GetStoreMappingsByPlanPriceId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**planPriceId** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiGetStoreMappingsByPlanPriceIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]StoreProductMappingDto**](StoreProductMappingDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdatePlanPrice

> AppPlanPriceDto UpdatePlanPrice(ctx, id).CreateOrUpdateAppPlanPriceDto(createOrUpdateAppPlanPriceDto).Execute()



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
	createOrUpdateAppPlanPriceDto := *openapiclient.NewCreateOrUpdateAppPlanPriceDto() // CreateOrUpdateAppPlanPriceDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SubscriptionBillingAdminAPI.UpdatePlanPrice(context.Background(), id).CreateOrUpdateAppPlanPriceDto(createOrUpdateAppPlanPriceDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionBillingAdminAPI.UpdatePlanPrice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdatePlanPrice`: AppPlanPriceDto
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionBillingAdminAPI.UpdatePlanPrice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiUpdatePlanPriceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createOrUpdateAppPlanPriceDto** | [**CreateOrUpdateAppPlanPriceDto**](CreateOrUpdateAppPlanPriceDto.md) |  |

### Return type

[**AppPlanPriceDto**](AppPlanPriceDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpsertStoreMapping

> StoreProductMappingDto UpsertStoreMapping(ctx).CreateOrUpdateStoreProductMappingDto(createOrUpdateStoreProductMappingDto).Execute()



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
	createOrUpdateStoreProductMappingDto := *openapiclient.NewCreateOrUpdateStoreProductMappingDto() // CreateOrUpdateStoreProductMappingDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SubscriptionBillingAdminAPI.UpsertStoreMapping(context.Background()).CreateOrUpdateStoreProductMappingDto(createOrUpdateStoreProductMappingDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionBillingAdminAPI.UpsertStoreMapping``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpsertStoreMapping`: StoreProductMappingDto
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionBillingAdminAPI.UpsertStoreMapping`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpsertStoreMappingRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createOrUpdateStoreProductMappingDto** | [**CreateOrUpdateStoreProductMappingDto**](CreateOrUpdateStoreProductMappingDto.md) |  |

### Return type

[**StoreProductMappingDto**](StoreProductMappingDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

