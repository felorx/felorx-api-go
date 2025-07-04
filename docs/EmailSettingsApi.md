# \EmailSettingsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetEmailSettings**](EmailSettingsAPI.md#GetEmailSettings) | **Get** /api/setting-management/emailing | 
[**SendTestEmail**](EmailSettingsAPI.md#SendTestEmail) | **Post** /api/setting-management/emailing/send-test-email | 
[**UpdateEmailSettings**](EmailSettingsAPI.md#UpdateEmailSettings) | **Post** /api/setting-management/emailing | 



## GetEmailSettings

> EmailSettingsDto GetEmailSettings(ctx).Execute()



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.EmailSettingsAPI.GetEmailSettings(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EmailSettingsAPI.GetEmailSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetEmailSettings`: EmailSettingsDto
	fmt.Fprintf(os.Stdout, "Response from `EmailSettingsAPI.GetEmailSettings`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetEmailSettingsRequest struct via the builder pattern


### Return type

[**EmailSettingsDto**](EmailSettingsDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SendTestEmail

> SendTestEmail(ctx).SendTestEmailInput(sendTestEmailInput).Execute()



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
	sendTestEmailInput := *openapiclient.NewSendTestEmailInput("SenderEmailAddress_example", "TargetEmailAddress_example", "Subject_example") // SendTestEmailInput |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EmailSettingsAPI.SendTestEmail(context.Background()).SendTestEmailInput(sendTestEmailInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EmailSettingsAPI.SendTestEmail``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSendTestEmailRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sendTestEmailInput** | [**SendTestEmailInput**](SendTestEmailInput.md) |  | 

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


## UpdateEmailSettings

> UpdateEmailSettings(ctx).UpdateEmailSettingsDto(updateEmailSettingsDto).Execute()



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
	updateEmailSettingsDto := *openapiclient.NewUpdateEmailSettingsDto("DefaultFromAddress_example", "DefaultFromDisplayName_example") // UpdateEmailSettingsDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.EmailSettingsAPI.UpdateEmailSettings(context.Background()).UpdateEmailSettingsDto(updateEmailSettingsDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `EmailSettingsAPI.UpdateEmailSettings``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateEmailSettingsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **updateEmailSettingsDto** | [**UpdateEmailSettingsDto**](UpdateEmailSettingsDto.md) |  | 

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

