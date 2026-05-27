# IntegrationHubEventPayloadLoyaltyProfileBasedTierUpgradeNotification

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**profileIntegrationID** | **string** |  |
**loyaltyProgramID** | **int** |  |
**loyaltyProgramName** | **string** | The name of the loyalty program. |
**subledgerID** | **string** |  |
**sourceOfEvent** | **string** |  |
**currentTier** | **string** | The name of the customer&#39;s current tier. |
**currentPoints** | **float** |  |
**oldTier** | **string** |  | [optional]
**pointsRequiredToTheNextTier** | **float** |  | [optional]
**nextTier** | **string** |  | [optional]
**tierExpirationDate** | **\DateTime** |  | [optional]
**timestampOfTierChange** | **\DateTime** |  | [optional]
**publishedAt** | **\DateTime** | Timestamp when the event was published. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
