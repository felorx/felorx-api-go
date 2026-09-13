# \FeaturesAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DeleteFeatures**](FeaturesAPI.md#DeleteFeatures) | **Delete** /api/feature-management/features | 
[**GetFeatures**](FeaturesAPI.md#GetFeatures) | **Get** /api/feature-management/features | 
[**UpdateFeatures**](FeaturesAPI.md#UpdateFeatures) | **Put** /api/feature-management/features | 



## DeleteFeatures

> DeleteFeatures(ctx).ProviderName(providerName).ProviderKey(providerKey).Execute()



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
	providerName := "providerName_example" // string |  (optional)
	providerKey := "providerKey_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.FeaturesAPI.DeleteFeatures(context.Background()).ProviderName(providerName).ProviderKey(providerKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FeaturesAPI.DeleteFeatures``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDeleteFeaturesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **providerName** | **string** |  | 
 **providerKey** | **string** |  | 

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


## GetFeatures

> GetFeatureListResultDto GetFeatures(ctx).ProviderName(providerName).ProviderKey(providerKey).Execute()



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
	providerName := "providerName_example" // string |  (optional)
	providerKey := "providerKey_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FeaturesAPI.GetFeatures(context.Background()).ProviderName(providerName).ProviderKey(providerKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FeaturesAPI.GetFeatures``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetFeatures`: GetFeatureListResultDto
	fmt.Fprintf(os.Stdout, "Response from `FeaturesAPI.GetFeatures`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetFeaturesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **providerName** | **string** |  | 
 **providerKey** | **string** |  | 

### Return type

[**GetFeatureListResultDto**](GetFeatureListResultDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateFeatures

> UpdateFeatures(ctx).ProviderName(providerName).ProviderKey(providerKey).UpdateFeaturesDto(updateFeaturesDto).Execute()



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
	providerName := "providerName_example" // string |  (optional)
	providerKey := "providerKey_example" // string |  (optional)
	updateFeaturesDto := *openapiclient.NewUpdateFeaturesDto() // UpdateFeaturesDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.FeaturesAPI.UpdateFeatures(context.Background()).ProviderName(providerName).ProviderKey(providerKey).UpdateFeaturesDto(updateFeaturesDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FeaturesAPI.UpdateFeatures``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateFeaturesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **providerName** | **string** |  | 
 **providerKey** | **string** |  | 
 **updateFeaturesDto** | [**UpdateFeaturesDto**](UpdateFeaturesDto.md) |  | 

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

