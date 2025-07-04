# \SubscriptionAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AppleNotifications**](SubscriptionAPI.md#AppleNotifications) | **Post** /api/app/subscription/apple-notifications | 苹果订阅 Callback 地址
[**CreateOrder**](SubscriptionAPI.md#CreateOrder) | **Post** /api/app/subscription/order | 
[**GetSubscriptionById**](SubscriptionAPI.md#GetSubscriptionById) | **Get** /api/app/subscription | 
[**VerifyReceipt**](SubscriptionAPI.md#VerifyReceipt) | **Post** /api/app/subscription/verify-receipt | 



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
	openapiclient "github.com/puupee/puupee-api-go"
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

[oauth2](../README.md#oauth2)

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
	openapiclient "github.com/puupee/puupee-api-go"
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

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
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
	openapiclient "github.com/puupee/puupee-api-go"
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

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
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
	openapiclient "github.com/puupee/puupee-api-go"
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

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

