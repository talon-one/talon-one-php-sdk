# UpdateLoyaltyPointsExpiryBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this block. | [optional] [readonly]
**type** | **string** | Identifies the block variant and determines which additional properties are present in it. |
**tags** | **string[]** | Semantic labels attached to this block. | [optional] [readonly]
**operator** | **string** | &#x60;setTo&#x60; sets the expiry to an exact date; &#x60;laterBy&#x60; extends the current expiry by a relative duration. |
**program** | [**\TalonOne\Client\Model\UpdateLoyaltyPointsExpiryBlock1Program**](UpdateLoyaltyPointsExpiryBlock1Program.md) |  |
**recipient** | **string** | The customer profile whose points are affected. &#x60;Current&#x60; targets the customer in the current session; &#x60;Advocate&#x60; targets the person who invited their friend via referral program. |
**subledger** | **string** | The name of the subledger whose points&#39; expiry is changed. Can be empty if this block targets the loyalty program&#39;s main ledger instead of a subledger. |
**value** | **mixed** | An absolute expiry date (ISO 8601) when &#x60;operator&#x60; is &#x60;setTo&#x60;, or a relative duration (e.g. &#x60;30D&#x60;) when &#x60;operator&#x60; is &#x60;laterBy&#x60;. |
**onFailure** | [**\TalonOne\Client\Model\Block[]**](Block.md) | Blocks evaluated when this block fails or returns false. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
