# CreateCouponBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this block. |
**type** | **string** | Identifies the block variant and determines which additional properties are present in it. |
**tags** | **string[]** | Semantic labels attached to this block. | [optional]
**campaignId** | [**\TalonOne\Client\Model\CreateCouponBlock1CampaignId**](CreateCouponBlock1CampaignId.md) |  |
**recipientId** | **string** | The integration ID of the customer that is allowed to redeem this coupon. |
**storeInSession** | **bool** | When &#x60;true&#x60;, the coupon is stored in the session. |
**usageLimit** | [**\TalonOne\Client\Model\CreateCouponBlock1UsageLimit**](CreateCouponBlock1UsageLimit.md) |  | [optional]
**discountLimit** | [**\TalonOne\Client\Model\CreateCouponBlock1DiscountLimit**](CreateCouponBlock1DiscountLimit.md) |  | [optional]
**startDate** | **mixed** |  | [optional]
**expiryDate** | **mixed** |  | [optional]
**attributes** | **mixed** |  | [optional]
**validCharacters** | **string** | Characters used to generate the random parts of a code. | [optional]
**pattern** | **string** | The pattern used to generate codes, such as coupon codes, referral codes, and loyalty cards. The character &#x60;#&#x60; is a placeholder and is replaced by a random character from the &#x60;validCharacters&#x60; set. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
