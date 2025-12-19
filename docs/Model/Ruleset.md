# # Ruleset

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | The internal ID of this entity. |
**created** | **\DateTime** | The time this entity was created. |
**userId** | **int** | The ID of the user associated with this entity. |
**rules** | [**\TalonOne\Client\Model\Rule[]**](Rule.md) | Set of rules to apply. |
**strikethroughRules** | [**\TalonOne\Client\Model\Rule[]**](Rule.md) | Set of rules to apply for strikethrough. | [optional]
**bindings** | [**\TalonOne\Client\Model\Binding[]**](Binding.md) | An array that provides objects with variable names (name) and talang expressions to whose result they are bound (expression) during rule evaluation. The order of the evaluation is decided by the position in the array. |
**rbVersion** | **string** | The version of the rulebuilder used to create this ruleset. | [optional]
**activate** | **bool** | Indicates whether this created ruleset should be activated for the campaign that owns it. | [optional]
**campaignId** | **int** | The ID of the campaign that owns this entity. | [optional]
**templateId** | **int** | The ID of the campaign template that owns this entity. | [optional]
**activatedAt** | **\DateTime** | Timestamp indicating when this Ruleset was activated. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
