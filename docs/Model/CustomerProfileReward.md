# CustomerProfileReward

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | The ID of the customer reward instance. A customer profile can have multiple instances of the same reward. |
**rewardId** | **int** | The ID of the reward this instance belongs to. |
**rewardName** | **string** | The name of the reward. |
**status** | **string** | The status of the customer reward: - &#x60;unlocked&#x60;: The reward is available for use. - &#x60;used&#x60;: The reward has been used. |
**unlockedAt** | **\DateTime** | The date and time when the reward was unlocked. |
**unlockedByIntegrationId** | **string** | The integration ID of the customer profile that unlocked the reward.   For rewards unlocked with a loyalty card, this can be any customer profile  linked to that loyalty card. | [optional]
**usedAt** | **\DateTime** | The date and time when the reward was used. | [optional]
**usedByIntegrationId** | **string** | The integration ID of the customer profile that used the reward.   For rewards unlocked with a loyalty card, this can be any customer profile  linked to that loyalty card.   Only returned when the reward has been used. | [optional]
**loyaltyProgramId** | **int** | The ID of the loyalty program that the loyalty card belongs to. Only returned for rewards unlocked with a loyalty card. | [optional]
**loyaltyCardIdentifier** | **string** | The identifier of the loyalty card that the reward was unlocked with. Only returned for rewards unlocked with a loyalty card. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
