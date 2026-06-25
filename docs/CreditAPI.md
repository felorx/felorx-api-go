# \CreditAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAlipayOrder**](CreditAPI.md#CreateAlipayOrder) | **Post** /api/app/credit/alipay-order |
[**CreatePayPalOrder**](CreditAPI.md#CreatePayPalOrder) | **Post** /api/app/credit/pay-pal-order |
[**CreditGetAccount**](CreditAPI.md#CreditGetAccount) | **Get** /api/app/credit/account/{appId} |
[**GetPackages**](CreditAPI.md#GetPackages) | **Get** /api/app/credit/packages/{appId} |
[**Refund**](CreditAPI.md#Refund) | **Post** /api/app/credit/refund |
[**Spend**](CreditAPI.md#Spend) | **Post** /api/app/credit/spend |



## CreateAlipayOrder

> CreateCreditAlipayOrderResultDto CreateAlipayOrder(ctx).CreateCreditAlipayOrderDto(createCreditAlipayOrderDto).Execute()



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
	createCreditAlipayOrderDto := *openapiclient.NewCreateCreditAlipayOrderDto("AppId_example", "PackageId_example") // CreateCreditAlipayOrderDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CreditAPI.CreateAlipayOrder(context.Background()).CreateCreditAlipayOrderDto(createCreditAlipayOrderDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CreditAPI.CreateAlipayOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAlipayOrder`: CreateCreditAlipayOrderResultDto
	fmt.Fprintf(os.Stdout, "Response from `CreditAPI.CreateAlipayOrder`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAlipayOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createCreditAlipayOrderDto** | [**CreateCreditAlipayOrderDto**](CreateCreditAlipayOrderDto.md) |  |

### Return type

[**CreateCreditAlipayOrderResultDto**](CreateCreditAlipayOrderResultDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreatePayPalOrder

> CreateCreditPayPalOrderResultDto CreatePayPalOrder(ctx).CreateCreditPayPalOrderDto(createCreditPayPalOrderDto).Execute()



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
	createCreditPayPalOrderDto := *openapiclient.NewCreateCreditPayPalOrderDto("AppId_example", "PackageId_example") // CreateCreditPayPalOrderDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CreditAPI.CreatePayPalOrder(context.Background()).CreateCreditPayPalOrderDto(createCreditPayPalOrderDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CreditAPI.CreatePayPalOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreatePayPalOrder`: CreateCreditPayPalOrderResultDto
	fmt.Fprintf(os.Stdout, "Response from `CreditAPI.CreatePayPalOrder`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreatePayPalOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createCreditPayPalOrderDto** | [**CreateCreditPayPalOrderDto**](CreateCreditPayPalOrderDto.md) |  |

### Return type

[**CreateCreditPayPalOrderResultDto**](CreateCreditPayPalOrderResultDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreditGetAccount

> CreditAccountDto CreditGetAccount(ctx, appId).Execute()



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
	resp, r, err := apiClient.CreditAPI.CreditGetAccount(context.Background(), appId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CreditAPI.CreditGetAccount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreditGetAccount`: CreditAccountDto
	fmt.Fprintf(os.Stdout, "Response from `CreditAPI.CreditGetAccount`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**appId** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiCreditGetAccountRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**CreditAccountDto**](CreditAccountDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPackages

> []CreditPackageDto GetPackages(ctx, appId).Execute()



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
	resp, r, err := apiClient.CreditAPI.GetPackages(context.Background(), appId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CreditAPI.GetPackages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPackages`: []CreditPackageDto
	fmt.Fprintf(os.Stdout, "Response from `CreditAPI.GetPackages`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**appId** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiGetPackagesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]CreditPackageDto**](CreditPackageDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## Refund

> AdjustCreditsResultDto Refund(ctx).AdjustCreditsDto(adjustCreditsDto).Execute()



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
	adjustCreditsDto := *openapiclient.NewAdjustCreditsDto("AppId_example", "ReferenceId_example", "Description_example") // AdjustCreditsDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CreditAPI.Refund(context.Background()).AdjustCreditsDto(adjustCreditsDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CreditAPI.Refund``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Refund`: AdjustCreditsResultDto
	fmt.Fprintf(os.Stdout, "Response from `CreditAPI.Refund`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRefundRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **adjustCreditsDto** | [**AdjustCreditsDto**](AdjustCreditsDto.md) |  |

### Return type

[**AdjustCreditsResultDto**](AdjustCreditsResultDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## Spend

> AdjustCreditsResultDto Spend(ctx).AdjustCreditsDto(adjustCreditsDto).Execute()



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
	adjustCreditsDto := *openapiclient.NewAdjustCreditsDto("AppId_example", "ReferenceId_example", "Description_example") // AdjustCreditsDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CreditAPI.Spend(context.Background()).AdjustCreditsDto(adjustCreditsDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CreditAPI.Spend``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Spend`: AdjustCreditsResultDto
	fmt.Fprintf(os.Stdout, "Response from `CreditAPI.Spend`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSpendRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **adjustCreditsDto** | [**AdjustCreditsDto**](AdjustCreditsDto.md) |  |

### Return type

[**AdjustCreditsResultDto**](AdjustCreditsResultDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

