# \StorageObjectAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetCdnDomains**](StorageObjectAPI.md#GetCdnDomains) | **Get** /api/app/storage-object/cdn-domains | 获取所有 CDN Domain 配置
[**GetFileCredential**](StorageObjectAPI.md#GetFileCredential) | **Get** /api/app/storage-object/file-credential | 
[**GetUserStorages**](StorageObjectAPI.md#GetUserStorages) | **Get** /api/app/storage-object/user-storages | 
[**PreSignUrl**](StorageObjectAPI.md#PreSignUrl) | **Post** /api/app/storage-object/pre-sign-url | 



## GetCdnDomains

> []CdnDomainDto GetCdnDomains(ctx).Execute()

获取所有 CDN Domain 配置

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
	resp, r, err := apiClient.StorageObjectAPI.GetCdnDomains(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StorageObjectAPI.GetCdnDomains``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCdnDomains`: []CdnDomainDto
	fmt.Fprintf(os.Stdout, "Response from `StorageObjectAPI.GetCdnDomains`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetCdnDomainsRequest struct via the builder pattern


### Return type

[**[]CdnDomainDto**](CdnDomainDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetFileCredential

> StorageObjectCredentials GetFileCredential(ctx).UserTotalSize(userTotalSize).RapidCode(rapidCode).Usage(usage).Key(key).Execute()



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
	userTotalSize := int64(789) // int64 |  (optional)
	rapidCode := "rapidCode_example" // string |  (optional)
	usage := "usage_example" // string |  (optional)
	key := "key_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StorageObjectAPI.GetFileCredential(context.Background()).UserTotalSize(userTotalSize).RapidCode(rapidCode).Usage(usage).Key(key).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StorageObjectAPI.GetFileCredential``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetFileCredential`: StorageObjectCredentials
	fmt.Fprintf(os.Stdout, "Response from `StorageObjectAPI.GetFileCredential`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetFileCredentialRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **userTotalSize** | **int64** |  | 
 **rapidCode** | **string** |  | 
 **usage** | **string** |  | 
 **key** | **string** |  | 

### Return type

[**StorageObjectCredentials**](StorageObjectCredentials.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUserStorages

> []UserStorageDto GetUserStorages(ctx).Execute()



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
	resp, r, err := apiClient.StorageObjectAPI.GetUserStorages(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StorageObjectAPI.GetUserStorages``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserStorages`: []UserStorageDto
	fmt.Fprintf(os.Stdout, "Response from `StorageObjectAPI.GetUserStorages`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetUserStoragesRequest struct via the builder pattern


### Return type

[**[]UserStorageDto**](UserStorageDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PreSignUrl

> string PreSignUrl(ctx).Bucket(bucket).Key(key).Execute()



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
	bucket := "bucket_example" // string |  (optional)
	key := "key_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StorageObjectAPI.PreSignUrl(context.Background()).Bucket(bucket).Key(key).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StorageObjectAPI.PreSignUrl``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PreSignUrl`: string
	fmt.Fprintf(os.Stdout, "Response from `StorageObjectAPI.PreSignUrl`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPreSignUrlRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bucket** | **string** |  | 
 **key** | **string** |  | 

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

