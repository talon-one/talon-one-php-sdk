# CheckReferralBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this block. | [optional] [readonly]
**type** | **string** | A block discriminator of type &#x60;checkReferral&#x60;. |
**tags** | **string[]** | Semantic labels attached to this block. | [optional] [readonly]
**redeem** | **bool** | When &#x60;true&#x60;, the referral code is redeemed. |
**onFailure** | [**\TalonOne\Client\Model\Block[]**](Block.md) | Promotion blocks evaluated when this block fails or returns false. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
