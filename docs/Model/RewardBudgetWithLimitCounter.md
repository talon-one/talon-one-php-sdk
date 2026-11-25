# RewardBudgetWithLimitCounter

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | The internal ID of this entity. |
**created** | **\DateTime** | The time this entity was created. |
**rewardId** | **int** | The ID of the reward this budget applies to. |
**metric** | **string** | The customer action that counts towards the budget. |
**scope** | **string** | The type of count that the budget keeps of how many times the reward has  been unlocked.  - &#x60;perReward&#x60;: Counts how many times the reward has been unlocked by all customers. - &#x60;perProfile&#x60;: Counts how many times each customer profile has unlocked the reward. |
**period** | **string** | The time frame after which the budget count resets to &#x60;0&#x60;. If you select &#x60;overall&#x60;, the budget never resets.  The count resets at the start of each calendar time frame, not on the day the budget was created. For example, a &#x60;monthly&#x60; budget created on 20 October counts each time the reward is unlocked from 20 to 31 October. On 1 November,  resets to &#x60;0&#x60;. |
**limit** | **int** | The maximum number of times the reward can be unlocked in the time frame. |
**limitCounter** | [**\TalonOne\Client\Model\RewardBudgetLimitCounter[]**](RewardBudgetLimitCounter.md) | The count of times the reward has been unlocked in the current period, and how many times it can still be unlocked before the limit is reached. It is only returned for budgets with the &#x60;perReward&#x60; scope, because every customer profile has their own count in a &#x60;perProfile&#x60; budget.  The count is stored for each Application. A reward is connected to one Application, so the list always has exactly one item. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
