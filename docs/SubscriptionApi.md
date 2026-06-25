# \SubscriptionAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AlipayNotify**](SubscriptionAPI.md#AlipayNotify) | **Post** /api/app/alipay/notify | 支付宝异步通知。成功时必须返回纯文本 success，否则支付宝会重试通知。
[**AppleNotifications**](SubscriptionAPI.md#AppleNotifications) | **Post** /api/app/subscription/apple-notifications | 苹果订阅 Callback 地址
[**CapturePayPalOrder**](SubscriptionAPI.md#CapturePayPalOrder) | **Post** /api/app/subscription/capture-pay-pal-order | 捕获 PayPal 订单并完成订阅
[**CreateOrder**](SubscriptionAPI.md#CreateOrder) | **Post** /api/app/subscription/order |
[**GetPlanPrices**](SubscriptionAPI.md#GetPlanPrices) | **Get** /api/app/subscription/plan-prices/by-app-id/{appId} | 获取应用对客户端开放的订阅售卖价格。
[**GetSubscriptionById**](SubscriptionAPI.md#GetSubscriptionById) | **Get** /api/app/subscription |
[**GetSubscriptionList**](SubscriptionAPI.md#GetSubscriptionList) | **Get** /api/app/subscription/list | 获取用户订阅列表，每个应用只返回最新的一条订阅记录（含有效和已过期的）
[**PayPalReturn**](SubscriptionAPI.md#PayPalReturn) | **Get** /api/app/paypal/notify | PayPal 浏览器审批后的返回入口。用于桌面/移动 App 跳转外部浏览器时免网站登录完成确认。
[**PayPalWebhook**](SubscriptionAPI.md#PayPalWebhook) | **Post** /api/app/paypal/notify | PayPal webhook. Configure PayPal:WebhookId to enable signature verification.
[**SubscriptionCreateAlipayOrder**](SubscriptionAPI.md#SubscriptionCreateAlipayOrder) | **Post** /api/app/subscription/alipay-order | 创建支付宝一次性支付订单
[**SubscriptionCreatePayPalOrder**](SubscriptionAPI.md#SubscriptionCreatePayPalOrder) | **Post** /api/app/subscription/pay-pal-order | 创建 PayPal 订单
[**VerifyReceipt**](SubscriptionAPI.md#VerifyReceipt) | **Post** /api/app/subscription/verify-receipt |



## AlipayNotify

> string AlipayNotify(ctx).Execute()

支付宝异步通知。成功时必须返回纯文本 success，否则支付宝会重试通知。

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
	resp, r, err := apiClient.SubscriptionAPI.AlipayNotify(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionAPI.AlipayNotify``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AlipayNotify`: string
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionAPI.AlipayNotify`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiAlipayNotifyRequest struct via the builder pattern


### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## AppleNotifications

> AppleNotifications(ctx).AppleNotificaionDto(appleNotificaionDto).Execute()

苹果订阅 Callback 地址

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
	appleNotificaionDto := *openapiclient.NewAppleNotificaionDto() // AppleNotificaionDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SubscriptionAPI.AppleNotifications(context.Background()).AppleNotificaionDto(appleNotificaionDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionAPI.AppleNotifications``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAppleNotificationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **appleNotificaionDto** | [**AppleNotificaionDto**](AppleNotificaionDto.md) |  |

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


## CapturePayPalOrder

> SubscriptionDto CapturePayPalOrder(ctx).CapturePayPalOrderDto(capturePayPalOrderDto).Execute()

捕获 PayPal 订单并完成订阅

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
	capturePayPalOrderDto := *openapiclient.NewCapturePayPalOrderDto() // CapturePayPalOrderDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SubscriptionAPI.CapturePayPalOrder(context.Background()).CapturePayPalOrderDto(capturePayPalOrderDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionAPI.CapturePayPalOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CapturePayPalOrder`: SubscriptionDto
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionAPI.CapturePayPalOrder`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCapturePayPalOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **capturePayPalOrderDto** | [**CapturePayPalOrderDto**](CapturePayPalOrderDto.md) |  |

### Return type

[**SubscriptionDto**](SubscriptionDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateOrder

> SubscriptionOrderDto CreateOrder(ctx).CreateOrGetSubscriptionOrderDto(createOrGetSubscriptionOrderDto).Execute()



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
	createOrGetSubscriptionOrderDto := *openapiclient.NewCreateOrGetSubscriptionOrderDto() // CreateOrGetSubscriptionOrderDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SubscriptionAPI.CreateOrder(context.Background()).CreateOrGetSubscriptionOrderDto(createOrGetSubscriptionOrderDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionAPI.CreateOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateOrder`: SubscriptionOrderDto
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionAPI.CreateOrder`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createOrGetSubscriptionOrderDto** | [**CreateOrGetSubscriptionOrderDto**](CreateOrGetSubscriptionOrderDto.md) |  |

### Return type

[**SubscriptionOrderDto**](SubscriptionOrderDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPlanPrices

> []AppPlanPriceDto GetPlanPrices(ctx, appId).Execute()

获取应用对客户端开放的订阅售卖价格。

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
	resp, r, err := apiClient.SubscriptionAPI.GetPlanPrices(context.Background(), appId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionAPI.GetPlanPrices``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPlanPrices`: []AppPlanPriceDto
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionAPI.GetPlanPrices`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**appId** | **string** |  |

### Other Parameters

Other parameters are passed through a pointer to a apiGetPlanPricesRequest struct via the builder pattern


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


## GetSubscriptionById

> SubscriptionDto GetSubscriptionById(ctx).AppId(appId).Execute()



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
	appId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SubscriptionAPI.GetSubscriptionById(context.Background()).AppId(appId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionAPI.GetSubscriptionById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSubscriptionById`: SubscriptionDto
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionAPI.GetSubscriptionById`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetSubscriptionByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **appId** | **string** |  |

### Return type

[**SubscriptionDto**](SubscriptionDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSubscriptionList

> []SubscriptionDto GetSubscriptionList(ctx).Execute()

获取用户订阅列表，每个应用只返回最新的一条订阅记录（含有效和已过期的）

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
	resp, r, err := apiClient.SubscriptionAPI.GetSubscriptionList(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionAPI.GetSubscriptionList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSubscriptionList`: []SubscriptionDto
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionAPI.GetSubscriptionList`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetSubscriptionListRequest struct via the builder pattern


### Return type

[**[]SubscriptionDto**](SubscriptionDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PayPalReturn

> PayPalReturn(ctx).Token(token).SubscriptionId(subscriptionId).Execute()

PayPal 浏览器审批后的返回入口。用于桌面/移动 App 跳转外部浏览器时免网站登录完成确认。

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
	token := "token_example" // string |  (optional)
	subscriptionId := "subscriptionId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SubscriptionAPI.PayPalReturn(context.Background()).Token(token).SubscriptionId(subscriptionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionAPI.PayPalReturn``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPayPalReturnRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **token** | **string** |  |
 **subscriptionId** | **string** |  |

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


## PayPalWebhook

> PayPalWebhookProcessResultDto PayPalWebhook(ctx).Execute()

PayPal webhook. Configure PayPal:WebhookId to enable signature verification.

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
	resp, r, err := apiClient.SubscriptionAPI.PayPalWebhook(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionAPI.PayPalWebhook``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PayPalWebhook`: PayPalWebhookProcessResultDto
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionAPI.PayPalWebhook`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiPayPalWebhookRequest struct via the builder pattern


### Return type

[**PayPalWebhookProcessResultDto**](PayPalWebhookProcessResultDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SubscriptionCreateAlipayOrder

> CreateAlipayOrderResultDto SubscriptionCreateAlipayOrder(ctx).CreateAlipayOrderDto(createAlipayOrderDto).Execute()

创建支付宝一次性支付订单

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
	createAlipayOrderDto := *openapiclient.NewCreateAlipayOrderDto() // CreateAlipayOrderDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SubscriptionAPI.SubscriptionCreateAlipayOrder(context.Background()).CreateAlipayOrderDto(createAlipayOrderDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionAPI.SubscriptionCreateAlipayOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SubscriptionCreateAlipayOrder`: CreateAlipayOrderResultDto
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionAPI.SubscriptionCreateAlipayOrder`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSubscriptionCreateAlipayOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createAlipayOrderDto** | [**CreateAlipayOrderDto**](CreateAlipayOrderDto.md) |  |

### Return type

[**CreateAlipayOrderResultDto**](CreateAlipayOrderResultDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SubscriptionCreatePayPalOrder

> CreatePayPalOrderResultDto SubscriptionCreatePayPalOrder(ctx).CreatePayPalOrderDto(createPayPalOrderDto).Execute()

创建 PayPal 订单

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
	createPayPalOrderDto := *openapiclient.NewCreatePayPalOrderDto() // CreatePayPalOrderDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SubscriptionAPI.SubscriptionCreatePayPalOrder(context.Background()).CreatePayPalOrderDto(createPayPalOrderDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionAPI.SubscriptionCreatePayPalOrder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SubscriptionCreatePayPalOrder`: CreatePayPalOrderResultDto
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionAPI.SubscriptionCreatePayPalOrder`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSubscriptionCreatePayPalOrderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createPayPalOrderDto** | [**CreatePayPalOrderDto**](CreatePayPalOrderDto.md) |  |

### Return type

[**CreatePayPalOrderResultDto**](CreatePayPalOrderResultDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## VerifyReceipt

> VerifyReceiptResult VerifyReceipt(ctx).VerifyReceiptDto(verifyReceiptDto).Execute()



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
	verifyReceiptDto := *openapiclient.NewVerifyReceiptDto("OrderId_example", "ReceiptData_example", openapiclient.AppPlatform("None"), "DeviceToken_example") // VerifyReceiptDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SubscriptionAPI.VerifyReceipt(context.Background()).VerifyReceiptDto(verifyReceiptDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionAPI.VerifyReceipt``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `VerifyReceipt`: VerifyReceiptResult
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionAPI.VerifyReceipt`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiVerifyReceiptRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **verifyReceiptDto** | [**VerifyReceiptDto**](VerifyReceiptDto.md) |  |

### Return type

[**VerifyReceiptResult**](VerifyReceiptResult.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

