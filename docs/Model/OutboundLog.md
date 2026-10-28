# OutboundLog

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**uuid** | **string** | UUID of the outbound message. |
**notificationId** | **int** | ID of the notification that triggered the outbound message. | [optional]
**notificationName** | **string** | Name of the notification that triggered the outbound message. | [optional]
**webhookId** | **int** | ID of the webhook that triggered the outbound message. | [optional]
**webhookName** | **string** | Name of the webhook that triggered the outbound message. | [optional]
**notificationType** | **string** | Type of notification that triggered the outbound message. |
**applicationId** | **int** | ID of the Application associated with the outbound message. | [optional]
**loyaltyProgramId** | **int** | ID of the loyalty program associated with the outbound message. | [optional]
**request** | [**\TalonOne\Client\Model\OutboundLogRequest**](OutboundLogRequest.md) |  | [optional]
**createdAt** | **\DateTime** | Timestamp when the log was created. |
**processingTimeMs** | **int** | Time in milliseconds between sending the outbound request and receiving the response. |
**response** | [**\TalonOne\Client\Model\OutboundLogResponse**](OutboundLogResponse.md) |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
