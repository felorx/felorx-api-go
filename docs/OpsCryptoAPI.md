# \OpsCryptoAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetVault**](OpsCryptoAPI.md#GetVault) | **Get** /api/app/ops-crypto/vault |
[**PutVault**](OpsCryptoAPI.md#PutVault) | **Put** /api/app/ops-crypto/vault |



## GetVault

> OpsCryptoVaultDto GetVault(ctx).Execute()



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
	resp, r, err := apiClient.OpsCryptoAPI.GetVault(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OpsCryptoAPI.GetVault``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVault`: OpsCryptoVaultDto
	fmt.Fprintf(os.Stdout, "Response from `OpsCryptoAPI.GetVault`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetVaultRequest struct via the builder pattern


### Return type

[**OpsCryptoVaultDto**](OpsCryptoVaultDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PutVault

> PutVault(ctx).OpsCryptoVaultDto(opsCryptoVaultDto).Execute()



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
	opsCryptoVaultDto := *openapiclient.NewOpsCryptoVaultDto() // OpsCryptoVaultDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.OpsCryptoAPI.PutVault(context.Background()).OpsCryptoVaultDto(opsCryptoVaultDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OpsCryptoAPI.PutVault``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPutVaultRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **opsCryptoVaultDto** | [**OpsCryptoVaultDto**](OpsCryptoVaultDto.md) |  |

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

