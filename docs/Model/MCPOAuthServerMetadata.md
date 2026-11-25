# MCPOAuthServerMetadata

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**issuer** | **string** | The authorization server&#39;s issuer identifier (its base URL). |
**authorizationEndpoint** | **string** | URL of the authorization endpoint. |
**tokenEndpoint** | **string** | URL of the token endpoint. |
**registrationEndpoint** | **string** | URL of the client registration endpoint. |
**responseTypesSupported** | **string[]** | List of supported OAuth2 response types. |
**grantTypesSupported** | **string[]** | List of supported OAuth2 grant types. |
**codeChallengeMethodsSupported** | **string[]** | List of supported PKCE code challenge methods. |
**tokenEndpointAuthMethodsSupported** | **string[]** | List of supported client authentication methods at the token endpoint. Public clients use &#x60;none&#x60;; confidential clients use &#x60;client_secret_post&#x60; or &#x60;client_secret_basic&#x60;. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
