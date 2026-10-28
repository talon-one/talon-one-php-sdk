# OutboundMessage

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
**firstLogAt** | **\DateTime** | Timestamp of the first log entry for this message. |
**lastLogAt** | **\DateTime** | Timestamp of the last log entry for this message. |
**lastResponseCode** | **int** | HTTP status code from the latest response. | [optional]
**status** | **string** |  |
**retryCount** | **int** | Number of retries. | [optional]
**responses** | [**\TalonOne\Client\Model\OutboundMessageResponse[]**](OutboundMessageResponse.md) | Log entries for this message. One entry per delivery attempt. Empty when &#x60;includeLogs&#x3D;false&#x60;. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
