# AwardLoyaltyPointsBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this block. | [optional] [readonly]
**type** | **string** | Identifies the block variant and determines which additional properties are present in it. |
**tags** | **string[]** | Semantic labels attached to this block. | [optional] [readonly]
**name** | **string** | The human-readable label attached to the awarded points. |
**program** | [**\TalonOne\Client\Model\AwardLoyaltyPointsBlock1Program**](AwardLoyaltyPointsBlock1Program.md) |  |
**recipient** | **string** | The customer profile that receives the points. &#x60;Current&#x60; targets the customer in the current session; &#x60;Advocate&#x60; targets the person who invited their friend via referral program. |
**subledger** | **string** | The name of the subledger to add points to. Can be empty if this block adds points to the loyalty program&#39;s main ledger instead of a subledger. |
**target** | [**\TalonOne\Client\Model\AwardLoyaltyPointsTarget**](AwardLoyaltyPointsTarget.md) |  |
**value** | [**\TalonOne\Client\Model\AwardLoyaltyPointsBlock1Value**](AwardLoyaltyPointsBlock1Value.md) |  |
**partial** | **bool** | When &#x60;true&#x60;, applies a partial points reward when the requested value exceeds the configured budget. | [optional]
**awaitsActivation** | **bool** | When &#x60;true&#x60;, the awarded points require manual or delayed activation before becoming active. Mutually exclusive with &#x60;startDate&#x60;. | [optional]
**startDate** | **mixed** | Timestamp at which the awarded points become active. Mutually exclusive with &#x60;awaitsActivation&#x60;. | [optional]
**validityDuration** | **string** | Relative duration (e.g. &#x60;30D&#x60;) after which the awarded points expire. Mutually exclusive with &#x60;expiryDate&#x60;. | [optional]
**expiryDate** | **mixed** | Timestamp at which the awarded points expire. Mutually exclusive with &#x60;validityDuration&#x60;. | [optional]
**pendingDuration** | **string** | Relative duration (e.g. &#x60;3D&#x60;) the awarded points remain pending before activation. | [optional]
**onFailure** | [**\TalonOne\Client\Model\Block[]**](Block.md) | Promotion blocks evaluated when this block fails or returns false. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
