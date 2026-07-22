# UpdateAchievementProgressBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this block. |
**type** | **string** | Identifies the block variant and determines which additional properties are present in it. |
**tags** | **string[]** | Semantic labels attached to this block. | [optional]
**operator** | **string** |  |
**value** | **string** | The value to update the progress by. Supports template placeholders (e.g. \&quot;{{$Session.Total / 2}}\&quot;) for dynamic quantities. |
**achievement** | [**\TalonOne\Client\Model\UpdateAchievementProgressBlock1Achievement**](UpdateAchievementProgressBlock1Achievement.md) |  |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
