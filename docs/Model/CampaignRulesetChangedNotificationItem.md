# # CampaignRulesetChangedNotificationItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**event** | **string** | The type of the event. Can be one of the following: [&#39;campaign_state_changed&#39;, &#39;campaign_ruleset_changed&#39;, &#39;campaign_edited&#39;, &#39;campaign_created&#39;, &#39;campaign_deleted&#39;] |
**campaign** | **mixed** | The campaign whose state changed. |
**oldRuleset** | [**\TalonOne\Client\Model\Ruleset**](Ruleset.md) | The old ruleset, if the ruleset was changed. | [optional]
**ruleset** | [**\TalonOne\Client\Model\Ruleset**](Ruleset.md) | The current ruleset. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
