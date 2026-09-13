# \RemotePairingAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**IssueAssertion**](RemotePairingAPI.md#IssueAssertion) | **Post** /api/app/remote-pairing/issue-assertion | 
[**VerifyAssertion**](RemotePairingAPI.md#VerifyAssertion) | **Post** /api/app/remote-pairing/verify-assertion | 



## IssueAssertion

> RemotePairingAssertionDto IssueAssertion(ctx).RemotePairingBindingDto(remotePairingBindingDto).Execute()



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
	remotePairingBindingDto := *openapiclient.NewRemotePairingBindingDto("HostId_example", "ChallengeId_example", "ControllerId_example", "WorkspaceId_example", "AccountHash_example") // RemotePairingBindingDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RemotePairingAPI.IssueAssertion(context.Background()).RemotePairingBindingDto(remotePairingBindingDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RemotePairingAPI.IssueAssertion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `IssueAssertion`: RemotePairingAssertionDto
	fmt.Fprintf(os.Stdout, "Response from `RemotePairingAPI.IssueAssertion`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiIssueAssertionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **remotePairingBindingDto** | [**RemotePairingBindingDto**](RemotePairingBindingDto.md) |  | 

### Return type

[**RemotePairingAssertionDto**](RemotePairingAssertionDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## VerifyAssertion

> RemotePairingVerificationDto VerifyAssertion(ctx).VerifyRemotePairingAssertionDto(verifyRemotePairingAssertionDto).Execute()



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
	verifyRemotePairingAssertionDto := *openapiclient.NewVerifyRemotePairingAssertionDto("HostId_example", "ChallengeId_example", "ControllerId_example", "WorkspaceId_example", "AccountHash_example", "Assertion_example") // VerifyRemotePairingAssertionDto |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RemotePairingAPI.VerifyAssertion(context.Background()).VerifyRemotePairingAssertionDto(verifyRemotePairingAssertionDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RemotePairingAPI.VerifyAssertion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `VerifyAssertion`: RemotePairingVerificationDto
	fmt.Fprintf(os.Stdout, "Response from `RemotePairingAPI.VerifyAssertion`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiVerifyAssertionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **verifyRemotePairingAssertionDto** | [**VerifyRemotePairingAssertionDto**](VerifyRemotePairingAssertionDto.md) |  | 

### Return type

[**RemotePairingVerificationDto**](RemotePairingVerificationDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json, text/json, application/*+json
- **Accept**: text/plain, application/json, text/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

