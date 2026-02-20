# # PrismaticEventPayloadLoyaltyProfileBasedNotification

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**profileIntegrationID** | **string** |  |
**loyaltyProgramID** | **int** |  |
**subledgerID** | **string** |  |
**sourceOfEvent** | **string** |  |
**employeeName** | **string** |  | [optional]
**userID** | **int** |  | [optional]
**currentPoints** | **float** |  |
**actions** | [**\TalonOne\Client\Model\PrismaticEventPayloadLoyaltyProfileBasedPointsChangedNotificationAction[]**](PrismaticEventPayloadLoyaltyProfileBasedPointsChangedNotificationAction.md) |  | [optional]
**publishedAt** | **\DateTime** | Timestamp when the event was published. |
**currentTier** | **string** |  | [optional]
**oldTier** | **string** |  | [optional]
**tierExpirationDate** | **\DateTime** |  | [optional]
**timestampOfTierChange** | **\DateTime** |  | [optional]
**pointsRequiredToTheNextTier** | **float** |  | [optional]
**nextTier** | **string** |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
