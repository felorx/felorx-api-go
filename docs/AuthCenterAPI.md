# \AuthCenterAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAuthorizedApps**](AuthCenterAPI.md#GetAuthorizedApps) | **Get** /api/app/auth-center/authorized-apps | 
[**GetSummaryGetApiAppAuthCenterSummary**](AuthCenterAPI.md#GetSummaryGetApiAppAuthCenterSummary) | **Get** /api/app/auth-center/summary | 
[**RevokeAuthorizedApp**](AuthCenterAPI.md#RevokeAuthorizedApp) | **Post** /api/app/auth-center/revoke-authorized-app/{clientId} | 



## GetAuthorizedApps

> []AuthorizedAppDto GetAuthorizedApps(ctx).Execute()



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
	resp, r, err := apiClient.AuthCenterAPI.GetAuthorizedApps(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthCenterAPI.GetAuthorizedApps``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAuthorizedApps`: []AuthorizedAppDto
	fmt.Fprintf(os.Stdout, "Response from `AuthCenterAPI.GetAuthorizedApps`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetAuthorizedAppsRequest struct via the builder pattern


### Return type

[**[]AuthorizedAppDto**](AuthorizedAppDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSummaryGetApiAppAuthCenterSummary

> AuthCenterSummaryDto GetSummaryGetApiAppAuthCenterSummary(ctx).Execute()



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
	resp, r, err := apiClient.AuthCenterAPI.GetSummaryGetApiAppAuthCenterSummary(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthCenterAPI.GetSummaryGetApiAppAuthCenterSummary``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSummaryGetApiAppAuthCenterSummary`: AuthCenterSummaryDto
	fmt.Fprintf(os.Stdout, "Response from `AuthCenterAPI.GetSummaryGetApiAppAuthCenterSummary`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetSummaryGetApiAppAuthCenterSummaryRequest struct via the builder pattern


### Return type

[**AuthCenterSummaryDto**](AuthCenterSummaryDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RevokeAuthorizedApp

> RevokeAuthorizedApp(ctx, clientId).Execute()



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
	clientId := "clientId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AuthCenterAPI.RevokeAuthorizedApp(context.Background(), clientId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthCenterAPI.RevokeAuthorizedApp``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**clientId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRevokeAuthorizedAppRequest struct via the builder pattern


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

