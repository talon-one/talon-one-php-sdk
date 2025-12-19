# # ManagementKey

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** | Name for management key. |
**expiryDate** | **\DateTime** | The date the management key expires. |
**endpoints** | [**\TalonOne\Client\Model\Endpoint[]**](Endpoint.md) | The list of endpoints that can be accessed with the key |
**allowedApplicationIds** | **int[]** | A list of Application IDs that you can access with the management key. An empty or missing list means the management key can be used for all Applications in the account. | [optional]
**id** | **int** | ID of the management key. |
**createdBy** | **int** | ID of the user who created it. |
**accountID** | **int** | ID of account the key is used for. |
**created** | **\DateTime** | The date the management key was created. |
**disabled** | **bool** | The management key is disabled (this property is set to &#x60;true&#x60;) when the user who created the key is disabled or deleted. | [optional]
**lastUsed** | **\DateTime** | The last time the management key was used. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
