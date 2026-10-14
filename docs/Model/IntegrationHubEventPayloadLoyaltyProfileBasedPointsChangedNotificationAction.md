# IntegrationHubEventPayloadLoyaltyProfileBasedPointsChangedNotificationAction

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**amount** | **float** |  |
**reason** | **string** |  | [optional]
**operation** | **string** |  |
**startDate** | **\DateTime** |  | [optional]
**expiryDate** | **\DateTime** |  | [optional]
**transactionUUID** | **string** | The identifier of the transaction in the loyalty ledger. |
**created** | **\DateTime** | The timestamp when the loyalty transaction occurred. | [optional]
**awaitsActivation** | **bool** | Indicates whether the points have an action-based start date. This property is returned only for point transactions with an action-based start date. | [optional]
**validityDuration** | **string** | The duration for which the points remain active, relative to the activation date.  **Note**: This only applies to points for which &#x60;AwaitsActivation&#x60; is &#x60;true&#x60; and &#x60;ExpiryDate&#x60; is not set. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
