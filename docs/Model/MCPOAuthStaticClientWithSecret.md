# MCPOAuthStaticClientWithSecret

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**clientId** | **string** | Unique identifier for the OAuth2 client. |
**clientName** | **string** | Human-readable name for the OAuth2 client. |
**redirectUris** | **string[]** | List of allowed redirect URIs for the authorization code flow. |
**createdAt** | **\DateTime** | Timestamp of when the client was registered. |
**id** | **int** | Numeric ID of the OAuth client, used to delete it. |
**createdBy** | **int** | ID of the user who created the client. |
**expiryDate** | **\DateTime** | The date the client credentials expire. | [optional]
**clientSecret** | **string** | The generated client secret. Only returned once on creation. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
