# UnlockRewardEffectProps

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**integrationId** | **string** | The integration ID assigned to the customer reward unlock. |
**rewardId** | **int** | The internal ID of the reward that was unlocked. |
**applicationId** | **int** | The internal ID of the application the reward belongs to. |
**profileIntegrationId** | **string** | The integration ID of the customer profile that unlocked the reward. |
**unlockedAt** | **\DateTime** | The time the reward was unlocked. |
**cardIdentifier** | **string** | The identifier of the loyalty card that unlocked the reward. Only returned when the reward was unlocked with a loyalty card, in which case the reward belongs to the card and is available to all customer profiles linked to it. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
