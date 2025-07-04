# \ProfileAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ChangePassword**](ProfileAPI.md#ChangePassword) | **Post** /api/account/my-profile/change-password | 
[**GetProfile**](ProfileAPI.md#GetProfile) | **Get** /api/account/my-profile | 
[**UpdateProfile**](ProfileAPI.md#UpdateProfile) | **Put** /api/account/my-profile | 



## ChangePassword

> ChangePassword(ctx).ChangePasswordInput(changePasswordInput).Execute()



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
	changePasswordInput := *openapiclient.NewChangePasswordInput("NewPassword_example") // ChangePasswordInput |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ProfileAPI.ChangePassword(context.Background()).ChangePasswordInput(changePasswordInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProfileAPI.ChangePassword``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiChangePasswordRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **changePasswordInput** | [**ChangePasswordInput**](ChangePasswordInput.md) |  | 

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


## GetProfile

> ProfileDto GetProfile(ctx).Execute()



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
	resp, r, err := apiClient.ProfileAPI.GetProfile(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProfileAPI.GetProfile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProfile`: ProfileDto
	fmt.Fprintf(os.Stdout, "Response from `ProfileAPI.GetProfile`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetProfileRequest struct via the builder pattern


### Return type

[**ProfileDto**](ProfileDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateProfile

> ProfileDto UpdateProfile(ctx).UpdateProfileDto(updateProfileDto).Execute()



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
	updateProfileDto := *openapiclient.NewUpdateProfileDto() // UpdateProfileDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProfileAPI.UpdateProfile(context.Background()).UpdateProfileDto(updateProfileDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProfileAPI.UpdateProfile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateProfile`: ProfileDto
	fmt.Fprintf(os.Stdout, "Response from `ProfileAPI.UpdateProfile`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateProfileRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **updateProfileDto** | [**UpdateProfileDto**](UpdateProfileDto.md) |  | 

### Return type

[**ProfileDto**](ProfileDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

