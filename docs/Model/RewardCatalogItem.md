# RewardCatalogItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | The unique ID of the reward. |
**name** | **string** | The customer-facing name of the reward. |
**description** | **string** | The customer-facing description of the reward. | [optional]
**pointsRequired** | [**\TalonOne\Client\Model\RewardPointsRequired[]**](RewardPointsRequired.md) | The loyalty points required to activate the reward. | [optional]
**rule** | [**\TalonOne\Client\Model\RuleMetadata**](RuleMetadata.md) | Customer-facing rule metadata for the reward. |
**eligibility** | [**\TalonOne\Client\Model\RewardEligibility**](RewardEligibility.md) | The customer&#39;s eligibility for the reward. Returned only when the request includes a &#x60;profileIntegrationId&#x60; or &#x60;loyaltyCardId&#x60;. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
