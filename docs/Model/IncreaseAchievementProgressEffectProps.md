# IncreaseAchievementProgressEffectProps

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**achievementId** | **int** | The internal ID of the achievement. |
**achievementName** | **string** | The name of the achievement. |
**progressTrackerId** | **int** | The internal ID of the customer progress tracker. For [on-completion achievements](https://docs.talon.one/docs/product/campaigns/achievements/achievements-overview#recurring-on-completion-achievements), this effect generates a unique ID for each iteration. | [optional]
**delta** | **float** | The value by which the customer&#39;s current progress in the achievement has increased. |
**value** | **float** | The current progress of the customer in the achievement. |
**target** | **float** | The target value to complete the achievement. |
**isJustCompleted** | **bool** | Indicates if the customer has completed the achievement in the current session. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
