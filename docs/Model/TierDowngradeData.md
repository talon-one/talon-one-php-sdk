# # TierDowngradeData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**customerProfileID** | **string** | The integration ID of the customer profile whose tier was downgraded. |
**loyaltyProgramID** | **int** | The ID of the loyalty program. |
**subledgerID** | **string** | The ID of the subledger, when applicable. If this field is empty, the main ledger is used. | [default to '']
**currentTier** | **string** | The name of the customer&#39;s current tier. | [optional]
**currentPoints** | **float** | The number of points the customer had at the time of tier downgrade. |
**oldTier** | **string** | The name of the customer&#39;s previous tier. |
**tierExpirationDate** | **\DateTime** | The exact date and time the tier expires. | [optional]
**timestampOfTierChange** | **\DateTime** | The exact date and time the tier was changed. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
