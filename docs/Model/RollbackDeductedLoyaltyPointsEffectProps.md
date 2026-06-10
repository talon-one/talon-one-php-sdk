# RollbackDeductedLoyaltyPointsEffectProps

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**programId** | **int** | The ID of the loyalty program where these points were reimbursed. |
**subLedgerId** | **string** | The ID of the subledger within the loyalty program where these points were reimbursed. |
**value** | **float** | The amount of points that were reimbursed. |
**recipientIntegrationId** | **string** | The user for whom these points were reimbursed. |
**startDate** | **\DateTime** | The date after which the reimbursed points will be valid. | [optional]
**expiryDate** | **\DateTime** | The date after which the reimbursed points will expire. | [optional]
**transactionUUID** | **string** | The identifier of this loyalty point transaction. |
**cardIdentifier** | **string** | The identifier of the card from which these points were originally deducted. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
