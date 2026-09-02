# IntegrationUnlockRewardRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**integrationId** | **string** | The integration ID to assign to the created customer reward unlock. |
**profileIntegrationId** | **string** | The integration ID of the customer profile unlocking the reward. |
**cardIdentifier** | **string** | The identifier of the loyalty card unlocking the reward. When provided, the required points are deducted from the card&#39;s balance and the unlocked reward belongs to the card, which makes it available to all customer profiles linked to that card. The customer profile given in &#x60;profileIntegrationId&#x60; must be linked to the card, and the card must be active. | [optional]
**loyaltyProgramId** | **int** | The ID of the loyalty program from which points will be deducted. Required when the reward has &#x60;pointsRequired&#x60; configured. | [optional]
**subledgerId** | **string** | The ID of the subledger from which points will be deducted. Required when the reward has &#x60;pointsRequired&#x60; configured.  To specify the main ledger, provide an empty string (\&quot;\&quot;). | [optional]
**responseContent** | **string[]** | Determines which data is included in the response. Add any of the following optional values to the array to get that data in the response: &#x60;customerProfile&#x60;, &#x60;ruleFailureReasons&#x60;, &#x60;loyalty&#x60;. &#x60;effects&#x60; is always returned regardless of whether it is included here. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
