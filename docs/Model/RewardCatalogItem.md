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
**validityDuration** | **string** | The duration for which the customer rewards unlocked from this reward remain active, relative to when the customer reward was unlocked.  The time format is an **integer** followed by one letter indicating the time unit.  Examples: &#x60;30m&#x60;, &#x60;1h&#x60;, &#x60;5D&#x60;, &#x60;7W&#x60;, &#x60;10M&#x60;, &#x60;15Y&#x60;.  Available units:  - &#x60;m&#x60;: minutes - &#x60;h&#x60;: hours - &#x60;D&#x60;: days - &#x60;W&#x60;: weeks - &#x60;M&#x60;: months - &#x60;Y&#x60;: years  Certain units can be rounded up or down: - &#x60;_D&#x60; for rounding down days only. Signifies the start of the day. - &#x60;_U&#x60; for rounding up days, weeks, months and years. Signifies the end of the day, week, month or year.  This field is not returned in combination with &#x60;expiryDate&#x60;. If both &#x60;validityDuration&#x60; and &#x60;expiryDate&#x60; are not returned, customer rewards have unlimited validity. | [optional]
**expiryDate** | **\DateTime** | Expiry date of the customer rewards unlocked from this reward. Customer rewards never expire if this is omitted and &#x60;validityDuration&#x60; is not set.  **Note:** - This field is not returned in combination with &#x60;validityDuration&#x60;. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
