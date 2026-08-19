# RulesetV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Internal ID of this entity. |
**created** | **\DateTime** | The time this entity was created. |
**userId** | **int** | The ID of the user that created this ruleset. |
**campaignId** | **int** | The ID of the campaign that owns this entity. | [optional]
**templateId** | **int** | The ID of the campaign template that owns this entity. | [optional]
**activatedAt** | **\DateTime** | Timestamp indicating when this ruleset was activated. | [optional]
**promotionRules** | [**\TalonOne\Client\Model\PromotionRuleV2[]**](PromotionRuleV2.md) | Set of promotion rules. |
**strikethroughRules** | [**\TalonOne\Client\Model\StrikethroughRuleV2[]**](StrikethroughRuleV2.md) | Set of strikethrough rules. |
**selectors** | [**\TalonOne\Client\Model\Selector[]**](Selector.md) | Variable bindings of type selector. | [optional]
**bundles** | [**\TalonOne\Client\Model\Bundle[]**](Bundle.md) | Variable bindings of type bundle. | [optional]
**parameters** | [**\TalonOne\Client\Model\TemplateParameter[]**](TemplateParameter.md) | Variable bindings of type template parameter. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
