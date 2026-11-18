# CustomerInventory

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**profile** | [**\TalonOne\Client\Model\CustomerProfile**](CustomerProfile.md) |  | [optional]
**loyalty** | [**\TalonOne\Client\Model\Loyalty**](Loyalty.md) |  | [optional]
**referrals** | [**\TalonOne\Client\Model\InventoryReferral[]**](InventoryReferral.md) |  | [optional]
**coupons** | [**\TalonOne\Client\Model\InventoryCoupon[]**](InventoryCoupon.md) | The coupons reserved by this profile. This array includes hard and soft reservations. | [optional]
**giveaways** | [**\TalonOne\Client\Model\Giveaway[]**](Giveaway.md) |  | [optional]
**achievements** | [**\TalonOne\Client\Model\AchievementProgressWithDefinition[]**](AchievementProgressWithDefinition.md) | The customer&#39;s progress in each achievement they have participated in.  Only achievements the customer has started are included, whether they  are in progress, completed, or expired. Recurring achievements can appear  more than once, once per iteration. | [optional]
**rewards** | [**\TalonOne\Client\Model\RewardWithUnlocks[]**](RewardWithUnlocks.md) | The rewards that the customer has unlocked but not used. Expired customer rewards are not returned. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
