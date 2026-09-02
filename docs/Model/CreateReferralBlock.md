# CreateReferralBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this block. | [optional] [readonly]
**type** | **string** | Identifies the block variant and determines which additional properties are present in it. |
**tags** | **string[]** | Semantic labels attached to this block. | [optional] [readonly]
**campaignId** | [**\TalonOne\Client\Model\CreateReferralBlock1CampaignId**](CreateReferralBlock1CampaignId.md) |  |
**friendId** | **string** | An optional integration ID of the friend&#39;s profile. |
**storeInSession** | **bool** | When &#x60;true&#x60;, the referral code is stored in the session. |
**usageLimit** | [**\TalonOne\Client\Model\CreateReferralBlock1UsageLimit**](CreateReferralBlock1UsageLimit.md) |  | [optional]
**startDate** | **mixed** | Timestamp at which point the referral code becomes valid. | [optional]
**expiryDate** | **mixed** | Expiration date of the referral code. Referral code never expires if this is omitted. | [optional]
**attributes** | **mixed** | Custom attributes associated with this referral code. | [optional]
**validCharacters** | **string** | Characters used to generate the random parts of a code. | [optional]
**pattern** | **string** | The pattern used to generate codes, such as coupon codes, referral codes, and loyalty cards. The character &#x60;#&#x60; is a placeholder and is replaced by a random character from the &#x60;validCharacters&#x60; set. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
