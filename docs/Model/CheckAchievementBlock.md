# CheckAchievementBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this block. |
**type** | **string** | Identifies the block variant and determines which additional properties are present in it. |
**tags** | **string[]** | Semantic labels attached to this block. | [optional]
**operator** | **string** | The comparison operator applied to the achievement. |
**achievement** | [**\TalonOne\Client\Model\CheckAchievementBlock1Achievement**](CheckAchievementBlock1Achievement.md) |  |
**onFailure** | [**\TalonOne\Client\Model\PromotionBlock[]**](PromotionBlock.md) | Promotion blocks evaluated when this block fails or returns false. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
