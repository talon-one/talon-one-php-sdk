# PromotionBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this block. |
**type** | **string** | Identifies the block variant and determines which additional properties are present in it. |
**tags** | **string[]** | Semantic labels attached to this block. | [optional]
**operator** | **string** | The update operation applied to the attribute. |
**blocks** | [**\TalonOne\Client\Model\PromotionBlock[]**](PromotionBlock.md) | Child blocks evaluated according to the operator. |
**onFailure** | [**\TalonOne\Client\Model\PromotionBlock[]**](PromotionBlock.md) | Promotion blocks evaluated when this block fails or returns false. | [optional]
**onError** | **array<string,\TalonOne\Client\Model\PromotionBlock[]>** | Named error handlers evaluated when a specific error occurs. | [optional]
**expression** | **mixed[]** | The raw Talang expression as an array. For a function call, the first element is the function name and subsequent elements are its arguments. For any other expression (for example a bare attribute path or a literal value), this is a single-element array containing that value. |
**notificationType** | **string** | The type of notification to display. |
**title** | **string** | The notification heading shown to the customer. |
**body** | **string** | The notification body text. Supports template placeholders (e.g. \&quot;{{$Session.Total}}\&quot;) evaluated at rule execution time. | [optional]
**sku** | **string** | The stock keeping unit of the item to award. |
**name** | **string** | The display name of the item to award. |
**quantity** | **string** | The number of items to award. Supports template placeholders (e.g. \&quot;{{$Session.Total / 2}}\&quot;) for dynamic quantities. |
**partial** | **bool** | When set to &#x60;true&#x60;, applies a partial item reward if the remaining budget is insufficient to award the full reward. | [optional]
**giveawayPool** | [**\TalonOne\Client\Model\AwardGiveawayBlock1GiveawayPool**](AwardGiveawayBlock1GiveawayPool.md) |  |
**profile** | **string** | The customer profile to add or remove from the audience. &#x60;Current&#x60; targets the customer in the current session; &#x60;Advocate&#x60; targets the person who invited their friend via referral program. |
**attribute** | [**\TalonOne\Client\Model\UpdateAttributeValueBlock1Attribute**](UpdateAttributeValueBlock1Attribute.md) |  |
**value** | **mixed** |  |
**min** | **mixed** |  | [optional]
**max** | **mixed** |  | [optional]
**values** | **mixed** |  | [optional]
**count** | **mixed** |  | [optional]
**audience** | [**\TalonOne\Client\Model\UpdateAudienceMembershipBlock1Audience**](UpdateAudienceMembershipBlock1Audience.md) |  |
**redeem** | **bool** | When &#x60;true&#x60;, the referral code is redeemed. |
**achievement** | [**\TalonOne\Client\Model\UpdateAchievementProgressBlock1Achievement**](UpdateAchievementProgressBlock1Achievement.md) |  |
**target** | [**\TalonOne\Client\Model\UpdateAttributeValueBlock1Target**](UpdateAttributeValueBlock1Target.md) |  |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
