# # CreateManagementKey

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** | Name for management key. |
**expiryDate** | **\DateTime** | The date the management key expires. |
**endpoints** | [**\TalonOne\Client\Model\Endpoint[]**](Endpoint.md) | The list of endpoints that can be accessed with the key |
**allowedApplicationIds** | **int[]** | A list of Application IDs that you can access with the management key. An empty or missing list means the management key can be used for all Applications in the account. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
