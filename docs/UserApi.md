# \UserAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateIdentityUser**](UserAPI.md#CreateIdentityUser) | **Post** /api/identity/users | 
[**DeleteIdentityUserById**](UserAPI.md#DeleteIdentityUserById) | **Delete** /api/identity/users/{id} | 
[**FindByEmail**](UserAPI.md#FindByEmail) | **Get** /api/identity/users/by-email/{email} | 
[**FindByUsername**](UserAPI.md#FindByUsername) | **Get** /api/identity/users/by-username/{userName} | 
[**GetAssignableRoles**](UserAPI.md#GetAssignableRoles) | **Get** /api/identity/users/assignable-roles | 
[**GetIdentityUserById**](UserAPI.md#GetIdentityUserById) | **Get** /api/identity/users/{id} | 
[**GetIdentityUserList**](UserAPI.md#GetIdentityUserList) | **Get** /api/identity/users | 
[**GetRoles**](UserAPI.md#GetRoles) | **Get** /api/identity/users/{id}/roles | 
[**UpdateIdentityUser**](UserAPI.md#UpdateIdentityUser) | **Put** /api/identity/users/{id} | 
[**UpdateRoles**](UserAPI.md#UpdateRoles) | **Put** /api/identity/users/{id}/roles | 



## CreateIdentityUser

> IdentityUserDto CreateIdentityUser(ctx).IdentityUserCreateDto(identityUserCreateDto).Execute()



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
	identityUserCreateDto := *openapiclient.NewIdentityUserCreateDto("UserName_example", "Email_example", "Password_example") // IdentityUserCreateDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserAPI.CreateIdentityUser(context.Background()).IdentityUserCreateDto(identityUserCreateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserAPI.CreateIdentityUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateIdentityUser`: IdentityUserDto
	fmt.Fprintf(os.Stdout, "Response from `UserAPI.CreateIdentityUser`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateIdentityUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **identityUserCreateDto** | [**IdentityUserCreateDto**](IdentityUserCreateDto.md) |  | 

### Return type

[**IdentityUserDto**](IdentityUserDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteIdentityUserById

> DeleteIdentityUserById(ctx, id).Execute()



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.UserAPI.DeleteIdentityUserById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserAPI.DeleteIdentityUserById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteIdentityUserByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FindByEmail

> IdentityUserDto FindByEmail(ctx, email).Execute()



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
	email := "email_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserAPI.FindByEmail(context.Background(), email).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserAPI.FindByEmail``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FindByEmail`: IdentityUserDto
	fmt.Fprintf(os.Stdout, "Response from `UserAPI.FindByEmail`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**email** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiFindByEmailRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**IdentityUserDto**](IdentityUserDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FindByUsername

> IdentityUserDto FindByUsername(ctx, userName).Execute()



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
	userName := "userName_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserAPI.FindByUsername(context.Background(), userName).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserAPI.FindByUsername``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FindByUsername`: IdentityUserDto
	fmt.Fprintf(os.Stdout, "Response from `UserAPI.FindByUsername`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**userName** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiFindByUsernameRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**IdentityUserDto**](IdentityUserDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAssignableRoles

> IdentityRoleDtoListResultDto GetAssignableRoles(ctx).Execute()



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
	resp, r, err := apiClient.UserAPI.GetAssignableRoles(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserAPI.GetAssignableRoles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAssignableRoles`: IdentityRoleDtoListResultDto
	fmt.Fprintf(os.Stdout, "Response from `UserAPI.GetAssignableRoles`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetAssignableRolesRequest struct via the builder pattern


### Return type

[**IdentityRoleDtoListResultDto**](IdentityRoleDtoListResultDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetIdentityUserById

> IdentityUserDto GetIdentityUserById(ctx, id).Execute()



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserAPI.GetIdentityUserById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserAPI.GetIdentityUserById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetIdentityUserById`: IdentityUserDto
	fmt.Fprintf(os.Stdout, "Response from `UserAPI.GetIdentityUserById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetIdentityUserByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**IdentityUserDto**](IdentityUserDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetIdentityUserList

> IdentityUserDtoPagedResultDto GetIdentityUserList(ctx).Filter(filter).Sorting(sorting).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()



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
	filter := "filter_example" // string |  (optional)
	sorting := "sorting_example" // string |  (optional)
	skipCount := int32(56) // int32 |  (optional)
	maxResultCount := int32(56) // int32 |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserAPI.GetIdentityUserList(context.Background()).Filter(filter).Sorting(sorting).SkipCount(skipCount).MaxResultCount(maxResultCount).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserAPI.GetIdentityUserList``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetIdentityUserList`: IdentityUserDtoPagedResultDto
	fmt.Fprintf(os.Stdout, "Response from `UserAPI.GetIdentityUserList`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetIdentityUserListRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **filter** | **string** |  | 
 **sorting** | **string** |  | 
 **skipCount** | **int32** |  | 
 **maxResultCount** | **int32** |  | 

### Return type

[**IdentityUserDtoPagedResultDto**](IdentityUserDtoPagedResultDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRoles

> IdentityRoleDtoListResultDto GetRoles(ctx, id).Execute()



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserAPI.GetRoles(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserAPI.GetRoles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetRoles`: IdentityRoleDtoListResultDto
	fmt.Fprintf(os.Stdout, "Response from `UserAPI.GetRoles`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetRolesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**IdentityRoleDtoListResultDto**](IdentityRoleDtoListResultDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateIdentityUser

> IdentityUserDto UpdateIdentityUser(ctx, id).IdentityUserUpdateDto(identityUserUpdateDto).Execute()



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	identityUserUpdateDto := *openapiclient.NewIdentityUserUpdateDto("UserName_example", "Email_example") // IdentityUserUpdateDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UserAPI.UpdateIdentityUser(context.Background(), id).IdentityUserUpdateDto(identityUserUpdateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserAPI.UpdateIdentityUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateIdentityUser`: IdentityUserDto
	fmt.Fprintf(os.Stdout, "Response from `UserAPI.UpdateIdentityUser`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateIdentityUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **identityUserUpdateDto** | [**IdentityUserUpdateDto**](IdentityUserUpdateDto.md) |  | 

### Return type

[**IdentityUserDto**](IdentityUserDto.md)

### Authorization

[oauth2](../README.md#oauth2)

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateRoles

> UpdateRoles(ctx, id).IdentityUserUpdateRolesDto(identityUserUpdateRolesDto).Execute()



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	identityUserUpdateRolesDto := *openapiclient.NewIdentityUserUpdateRolesDto([]string{"RoleNames_example"}) // IdentityUserUpdateRolesDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.UserAPI.UpdateRoles(context.Background(), id).IdentityUserUpdateRolesDto(identityUserUpdateRolesDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UserAPI.UpdateRoles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateRolesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **identityUserUpdateRolesDto** | [**IdentityUserUpdateRolesDto**](IdentityUserUpdateRolesDto.md) |  | 

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

