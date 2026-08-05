# IntegrationHubPaginatedEventPayloadDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**eventId** | **int** | The ID of the integration hub event. Return this value in the delivery-status callback to mark the event delivered or failed. |
**profileIntegrationID** | **string** |  |
**loyaltyProgramID** | **int** |  |
**loyaltyProgramName** | **string** | The name of the loyalty program. |
**subledgerID** | **string** |  |
**sourceOfEvent** | **string** |  |
**currentTier** | **string** | The name of the customer&#39;s current tier. |
**sessionIntegrationID** | **string** | The integration ID of the session through which the points were earned or lost. Only set when the change results from a rule engine execution; empty otherwise. | [optional]
**employeeName** | **string** |  |
**userID** | **int** |  | [optional]
**currentPoints** | **float** |  |
**actions** | [**\TalonOne\Client\Model\IntegrationHubEventPayloadLoyaltyProfileBasedPointsChangedNotificationAction[]**](IntegrationHubEventPayloadLoyaltyProfileBasedPointsChangedNotificationAction.md) |  | [optional]
**publishedAt** | **\DateTime** | Timestamp when the event was published. |
**oldTier** | **string** |  | [optional]
**tierExpirationDate** | **\DateTime** |  | [optional]
**timestampOfTierChange** | **\DateTime** |  | [optional]
**pointsRequiredToTheNextTier** | **float** |  | [optional]
**nextTier** | **string** |  | [optional]
**id** | **int** |  |
**created** | **\DateTime** |  |
**campaignId** | **int** |  |
**value** | **string** |  |
**usageLimit** | **int** |  |
**discountLimit** | **float** |  | [optional]
**reservationLimit** | **int** |  | [optional]
**startDate** | **\DateTime** |  | [optional]
**expiryDate** | **\DateTime** |  | [optional]
**usageCounter** | **int** |  |
**discountCounter** | **float** |  | [optional]
**discountRemainder** | **float** |  | [optional]
**referralId** | **int** |  | [optional]
**recipientIntegrationId** | **string** |  | [optional]
**importId** | **int** |  | [optional]
**batchId** | **string** |  | [optional]
**attributes** | **object** |  | [optional]
**limits** | [**\TalonOne\Client\Model\IntegrationHubEventPayloadCouponBasedNotificationsLimits[]**](IntegrationHubEventPayloadCouponBasedNotificationsLimits.md) |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
