# IntegrationHubEventRecord

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | ID of the event record. |
**flowId** | **int** | ID of the integration hub flow. |
**integrationName** | **string** | Name of the integration. | [optional]
**instanceName** | **string** | Name of the integration instance. | [optional]
**eventType** | [**\TalonOne\Client\Model\IntegrationHubEventType**](IntegrationHubEventType.md) |  |
**publishedAt** | **\DateTime** | Timestamp when the event was published. |
**processedAt** | **\DateTime** | Timestamp when the event was processed. | [optional]
**deliveredAt** | **\DateTime** | Timestamp when the event was delivered. | [optional]
**scheduledTo** | **\DateTime** | Timestamp after which the event is scheduled to be processed. |
**retry** | **int** | Number of delivery retries attempted. |
**payload** | **string** | The event payload as a formatted JSON string. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
