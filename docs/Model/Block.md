# Block

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this block. | [optional] [readonly]
**type** | **string** | Identifies the block variant and determines which additional properties are present in it. |
**tags** | **string[]** | Semantic labels attached to this block. | [optional] [readonly]
**operator** | **string** | An indicator of how the block compares its elements. |
**blocks** | [**\TalonOne\Client\Model\Block[]**](Block.md) | Child blocks evaluated according to the operator. |
**onFailure** | [**\TalonOne\Client\Model\Block[]**](Block.md) | Promotion blocks evaluated when this block fails or returns false. | [optional]
**onError** | **array<string,\TalonOne\Client\Model\Block[]>** | Named error handlers evaluated when a specific error occurs. | [optional]
**name** | **string** | A custom description recorded as the reason for the point deduction. |
**value** | [**\TalonOne\Client\Model\RedeemLoyaltyPointsBlock1Value**](RedeemLoyaltyPointsBlock1Value.md) |  |
**partial** | **bool** | When &#x60;true&#x60;, applies a partial points reward when the requested value exceeds the configured budget. |
**target** | [**\TalonOne\Client\Model\AwardLoyaltyPointsTarget**](AwardLoyaltyPointsTarget.md) |  |
**expression** | **mixed[]** | The raw Talang expression as an array. For a function call, the first element is the function name and subsequent elements are its arguments. For any other expression (for example a bare attribute path or a literal value), this is a single-element array containing that value. |
**notificationType** | **string** | The type of notification to display. |
**title** | **string** | The notification heading shown to the customer. |
**body** | **string** | The notification body text. Supports template placeholders (e.g. \&quot;{{$Session.Total}}\&quot;) evaluated at rule execution time. | [optional]
**sku** | **string** | The stock keeping unit of the item to award. |
**quantity** | **string** | The number of items to award. Supports template placeholders (e.g. \&quot;{{$Session.Total / 2}}\&quot;) for dynamic quantities. |
**giveawayPool** | [**\TalonOne\Client\Model\GiveawayPoolBlockReference**](GiveawayPoolBlockReference.md) | The giveaway pool from which an item is awarded. |
**profile** | **string** | The customer profile to add or remove from the audience. &#x60;Current&#x60; targets the customer in the current session; &#x60;Advocate&#x60; targets the person who invited their friend via referral program. |
**audience** | [**\TalonOne\Client\Model\AudienceBlockReference**](AudienceBlockReference.md) | The audience to add the customer to or remove them from. |
**program** | [**\TalonOne\Client\Model\RedeemLoyaltyPointsBlock1Program**](RedeemLoyaltyPointsBlock1Program.md) |  |
**subledger** | **string** | The name of the subledger to deduct points from. Can be empty if this block deducts from the loyalty program&#39;s main ledger instead of a subledger. |
**balance** | **string** | The type of balance to check:  - &#x60;current&#x60; is the sum of currently active points  - &#x60;pending&#x60; is the sum of pending points.  - &#x60;negative&#x60; is the sum of negative points.  - &#x60;tentativeCurrent&#x60; is the tentative points balance within the current open customer session. |
**redeem** | **bool** | When &#x60;true&#x60;, the referral code is redeemed. |
**achievement** | [**\TalonOne\Client\Model\AchievementBlockReference**](AchievementBlockReference.md) | The achievement to check for. |
**attribute** | [**\TalonOne\Client\Model\AttributeBlockReference**](AttributeBlockReference.md) | The attribute being updated. |
**webhook** | [**\TalonOne\Client\Model\WebhookBlockReference**](WebhookBlockReference.md) | The webhook to trigger. |
**params** | **array<string,mixed>** | The custom effect&#39;s parameters, in configured order. Each property name is the parameter&#39;s title, lowercased with spaces replaced by underscores (for example, &#x60;Order ID&#x60; becomes &#x60;order_id&#x60;); falls back to &#x60;param_0&#x60;, &#x60;param_1&#x60;, and so on if a title is blank or collides with another. | [optional]
**customEffect** | [**\TalonOne\Client\Model\CustomEffectBlockReference**](CustomEffectBlockReference.md) | The custom effect to trigger. |
**eventType** | **string** | The event type to check against. |
**matchers** | [**\TalonOne\Client\Model\Block[]**](Block.md) |  | [optional]
**action** | **string** | The limitable action to check. |
**campaignId** | [**\TalonOne\Client\Model\CreateReferralBlock1CampaignId**](CreateReferralBlock1CampaignId.md) |  |
**recipientId** | **string** | The integration ID of the customer that is allowed to redeem this coupon. |
**storeInSession** | **bool** | When &#x60;true&#x60;, the referral code is stored in the session. |
**usageLimit** | [**\TalonOne\Client\Model\CreateReferralBlock1UsageLimit**](CreateReferralBlock1UsageLimit.md) |  | [optional]
**discountLimit** | [**\TalonOne\Client\Model\CreateCouponBlock1DiscountLimit**](CreateCouponBlock1DiscountLimit.md) |  | [optional]
**startDate** | **mixed** | Timestamp at which the awarded points become active. Mutually exclusive with &#x60;awaitsActivation&#x60;. | [optional]
**expiryDate** | **mixed** | Timestamp at which the awarded points expire. Mutually exclusive with &#x60;validityDuration&#x60;. | [optional]
**attributes** | **mixed** | Custom attributes associated with this referral code. | [optional]
**validCharacters** | **string** | Characters used to generate the random parts of a code. | [optional]
**pattern** | **string** | The pattern used to generate codes, such as coupon codes, referral codes, and loyalty cards. The character &#x60;#&#x60; is a placeholder and is replaced by a random character from the &#x60;validCharacters&#x60; set. | [optional]
**friendId** | **string** | An optional integration ID of the friend&#39;s profile. |
**recipient** | **string** | The customer profile that receives the points. &#x60;Current&#x60; targets the customer in the current session; &#x60;Advocate&#x60; targets the person who invited their friend via referral program. |
**tier** | [**\TalonOne\Client\Model\TierBlockReference**](TierBlockReference.md) | The tier to check for. |
**awaitsActivation** | **bool** | When &#x60;true&#x60;, the awarded points require manual or delayed activation before becoming active. Mutually exclusive with &#x60;startDate&#x60;. | [optional]
**validityDuration** | **string** | Relative duration (e.g. &#x60;30D&#x60;) after which the awarded points expire. Mutually exclusive with &#x60;expiryDate&#x60;. | [optional]
**pendingDuration** | **string** | Relative duration (e.g. &#x60;3D&#x60;) the awarded points remain pending before activation. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
