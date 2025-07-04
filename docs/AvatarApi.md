# \AvatarAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAvatar**](AvatarAPI.md#CreateAvatar) | **Post** /api/app/avatar | 
[**GetCredentials**](AvatarAPI.md#GetCredentials) | **Get** /api/app/avatar/credentials | 



## CreateAvatar

> AvatarDto CreateAvatar(ctx).CreateAvatarDto(createAvatarDto).Execute()



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
	createAvatarDto := *openapiclient.NewCreateAvatarDto() // CreateAvatarDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AvatarAPI.CreateAvatar(context.Background()).CreateAvatarDto(createAvatarDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AvatarAPI.CreateAvatar``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAvatar`: AvatarDto
	fmt.Fprintf(os.Stdout, "Response from `AvatarAPI.CreateAvatar`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAvatarRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createAvatarDto** | [**CreateAvatarDto**](CreateAvatarDto.md) |  | 

### Return type

[**AvatarDto**](AvatarDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCredentials

> StorageObjectCredentials GetCredentials(ctx).Key(key).Execute()



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
	key := "key_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AvatarAPI.GetCredentials(context.Background()).Key(key).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AvatarAPI.GetCredentials``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCredentials`: StorageObjectCredentials
	fmt.Fprintf(os.Stdout, "Response from `AvatarAPI.GetCredentials`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetCredentialsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **key** | **string** |  | 

### Return type

[**StorageObjectCredentials**](StorageObjectCredentials.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

