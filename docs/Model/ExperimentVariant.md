# ExperimentVariant

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | The internal ID of this entity. |
**created** | **\DateTime** | The time this entity was created. |
**name** | **string** |  |
**experimentId** | **int** |  | [optional]
**ruleset** | [**\TalonOne\Client\Model\Ruleset**](Ruleset.md) |  | [optional]
**weight** | **int** |  | [optional]
**isPrimary** | **bool** | **Deprecated.** Use &#x60;order&#x60; instead. Indicates whether this is the primary variant. This is computed as &#x60;order &#x3D;&#x3D; 0&#x60;. | [optional]
**order** | **int** | The position of this variant in the experiment. The variant with &#x60;order: 0&#x60; is the primary variant. | [optional]
**audienceId** | **int** | The ID of the audience this variant targets. Only used when the experiment &#x60;assignmentType&#x60; is &#x60;audience&#x60;. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
