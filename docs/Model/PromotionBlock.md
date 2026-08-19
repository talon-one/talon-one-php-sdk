# PromotionBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this block. |
**type** | **string** | Identifies the block variant and determines which additional properties are present in it. |
**tags** | **string[]** | Semantic labels attached to this block. | [optional]
**operator** | **string** | An indicator of how the block compares its elements. |
**blocks** | [**\TalonOne\Client\Model\PromotionBlock[]**](PromotionBlock.md) | Child blocks evaluated according to the operator. |
**onFailure** | [**\TalonOne\Client\Model\PromotionBlock[]**](PromotionBlock.md) | Promotion blocks evaluated when this block fails or returns false. | [optional]
**onError** | **array<string,\TalonOne\Client\Model\PromotionBlock[]>** | Named error handlers evaluated when a specific error occurs. | [optional]
**name** | **string** | A custom description recorded as the reason for the point deduction. |
**value** | [**\TalonOne\Client\Model\RedeemLoyaltyPointsBlock1Value**](RedeemLoyaltyPointsBlock1Value.md) |  |
**partial** | **bool** | When set to &#x60;true&#x60;, applies a partial item reward if the remaining budget is insufficient to award the full reward. |
**target** | [**\TalonOne\Client\Model\TriggerCustomEffectBlock1Target**](TriggerCustomEffectBlock1Target.md) |  |
**expression** | **mixed[]** | The raw Talang expression as an array. For a function call, the first element is the function name and subsequent elements are its arguments. For any other expression (for example a bare attribute path or a literal value), this is a single-element array containing that value. |
**notificationType** | **string** | The type of notification to display. |
**title** | **string** | The notification heading shown to the customer. |
**body** | **string** | The notification body text. Supports template placeholders (e.g. \&quot;{{$Session.Total}}\&quot;) evaluated at rule execution time. | [optional]
**sku** | **string** | The stock keeping unit of the item to award. |
**quantity** | **string** | The number of items to award. Supports template placeholders (e.g. \&quot;{{$Session.Total / 2}}\&quot;) for dynamic quantities. |
**giveawayPool** | [**\TalonOne\Client\Model\AwardGiveawayBlock1GiveawayPool**](AwardGiveawayBlock1GiveawayPool.md) |  |
**profile** | **string** | The customer profile to add or remove from the audience. &#x60;Current&#x60; targets the customer in the current session; &#x60;Advocate&#x60; targets the person who invited their friend via referral program. |
**attribute** | [**\TalonOne\Client\Model\UpdateAttributeValueBlock1Attribute**](UpdateAttributeValueBlock1Attribute.md) |  |
**min** | **mixed** |  | [optional]
**max** | **mixed** |  | [optional]
**start** | **mixed** |  | [optional]
**end** | **mixed** |  | [optional]
**startInclusive** | **bool** | When &#x60;true&#x60;, the &#x60;start&#x60; value is included in the range for the &#x60;within&#x60; operator. | [optional]
**endInclusive** | **bool** | When &#x60;true&#x60;, the &#x60;end&#x60; value is included in the range for the &#x60;within&#x60; operator. | [optional]
**timezoneInsensitive** | **bool** | Indicates whether the &#x60;within&#x60; operator ignores time zones and compares the wall-clock time only. When &#x60;false&#x60;, time zones are taken into account. | [optional]
**values** | **mixed** |  | [optional]
**count** | **mixed** |  | [optional]
**audience** | [**\TalonOne\Client\Model\UpdateAudienceMembershipBlock1Audience**](UpdateAudienceMembershipBlock1Audience.md) |  |
**program** | [**\TalonOne\Client\Model\RedeemLoyaltyPointsBlock1Program**](RedeemLoyaltyPointsBlock1Program.md) |  |
**subledger** | **string** | The name of the subledger to deduct points from. Can be empty if this block deducts from the loyalty program&#39;s main ledger instead of a subledger. |
**balance** | **string** | The type of balance to check:  - &#x60;current&#x60; is the sum of currently active points  - &#x60;pending&#x60; is the sum of pending points.  - &#x60;negative&#x60; is the sum of negative points.  - &#x60;tentativeCurrent&#x60; is the tentative points balance within the current open customer session. |
**redeem** | **bool** | When &#x60;true&#x60;, the referral code is redeemed. |
**achievement** | [**\TalonOne\Client\Model\CheckAchievementBlock1Achievement**](CheckAchievementBlock1Achievement.md) |  |
**webhook** | [**\TalonOne\Client\Model\TriggerWebhookBlock1Webhook**](TriggerWebhookBlock1Webhook.md) |  |
**params** | **array<string,mixed>** | The custom effect&#39;s parameters, in configured order. Each property name is the parameter&#39;s title, lowercased with spaces replaced by underscores (for example, &#x60;Order ID&#x60; becomes &#x60;order_id&#x60;); falls back to &#x60;param_0&#x60;, &#x60;param_1&#x60;, and so on if a title is blank or collides with another. | [optional]
**customEffect** | [**\TalonOne\Client\Model\TriggerCustomEffectBlock1CustomEffect**](TriggerCustomEffectBlock1CustomEffect.md) |  |
**eventType** | **string** | The event type to check against. |
**matchers** | [**\TalonOne\Client\Model\PromotionBlock[]**](PromotionBlock.md) |  | [optional]
**action** | **string** | The limitable action to check. |
**campaignId** | [**\TalonOne\Client\Model\CreateReferralBlock1CampaignId**](CreateReferralBlock1CampaignId.md) |  |
**recipientId** | **string** | The integration ID of the customer that is allowed to redeem this coupon. |
**storeInSession** | **bool** | When &#x60;true&#x60;, the referral code is stored in the session. |
**usageLimit** | [**\TalonOne\Client\Model\CreateReferralBlock1UsageLimit**](CreateReferralBlock1UsageLimit.md) |  | [optional]
**discountLimit** | [**\TalonOne\Client\Model\CreateCouponBlock1DiscountLimit**](CreateCouponBlock1DiscountLimit.md) |  | [optional]
**startDate** | **mixed** |  | [optional]
**expiryDate** | **mixed** |  | [optional]
**attributes** | **mixed** |  | [optional]
**validCharacters** | **string** | Characters used to generate the random parts of a code. | [optional]
**pattern** | **string** | The pattern used to generate codes, such as coupon codes, referral codes, and loyalty cards. The character &#x60;#&#x60; is a placeholder and is replaced by a random character from the &#x60;validCharacters&#x60; set. | [optional]
**friendId** | **string** | An optional integration ID of the friend&#39;s profile. |
**tier** | [**\TalonOne\Client\Model\CheckTierBlock1Tier**](CheckTierBlock1Tier.md) |  |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
