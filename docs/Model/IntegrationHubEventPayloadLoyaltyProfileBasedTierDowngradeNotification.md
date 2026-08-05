# IntegrationHubEventPayloadLoyaltyProfileBasedTierDowngradeNotification

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**eventId** | **int** | The ID of the integration hub event. Return this value in the delivery-status callback to mark the event delivered or failed. |
**profileIntegrationID** | **string** |  |
**loyaltyProgramID** | **int** |  |
**loyaltyProgramName** | **string** | The name of the loyalty program. |
**subledgerID** | **string** |  |
**sourceOfEvent** | **string** |  |
**currentTier** | **string** | The name of the customer&#39;s current tier, or null if the customer was downgraded below all tiers. | [optional]
**currentPoints** | **float** |  |
**oldTier** | **string** |  | [optional]
**tierExpirationDate** | **\DateTime** |  | [optional]
**timestampOfTierChange** | **\DateTime** |  | [optional]
**publishedAt** | **\DateTime** | Timestamp when the event was published. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
