# AwardGiveawayBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this block. | [optional] [readonly]
**type** | **string** | Identifies the block variant and determines which additional properties are present in it. |
**tags** | **string[]** | Semantic labels attached to this block. | [optional] [readonly]
**giveawayPool** | [**\TalonOne\Client\Model\GiveawayPoolReference**](GiveawayPoolReference.md) | The giveaway pool from which an item is awarded. |
**profile** | **string** | The customer profile to award the giveaway to. &#x60;Current&#x60; targets the customer in the current session; &#x60;Advocate&#x60; targets the person who invited their friend via referral program. |
**onFailure** | [**\TalonOne\Client\Model\Block[]**](Block.md) | Blocks evaluated when this block fails or returns false. | [optional]
**onError** | **array<string,\TalonOne\Client\Model\Block[]>** | Named error handlers evaluated when a specific error occurs. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
