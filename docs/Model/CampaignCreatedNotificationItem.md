# # CampaignCreatedNotificationItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**event** | **string** | The type of the event. Can be one of the following: [&#39;campaign_state_changed&#39;, &#39;campaign_ruleset_changed&#39;, &#39;campaign_edited&#39;, &#39;campaign_created&#39;, &#39;campaign_deleted&#39;] |
**campaign** | [**\TalonOne\Client\Model\Campaign**](Campaign.md) | The campaign whose state changed. |
**ruleset** | [**\TalonOne\Client\Model\Ruleset**](Ruleset.md) | The current ruleset. | [optional]
**evaluationPosition** | [**\TalonOne\Client\Model\CampaignEvaluationPosition**](CampaignEvaluationPosition.md) | The campaign position within the evaluation tree. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
