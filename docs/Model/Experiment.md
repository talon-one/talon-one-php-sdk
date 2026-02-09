# # Experiment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | The internal ID of this entity. |
**created** | **\DateTime** | The time this entity was created. |
**applicationId** | **int** | The ID of the Application that owns this entity. |
**isVariantAssignmentExternal** | **bool** | The source of the assignment. - false - The assignment to the variant is handled internally by the Talon.Oneandled internally by the Talon.One. - true - The assignment to the variant handled externally. | [optional]
**campaign** | [**\TalonOne\Client\Model\Campaign**](Campaign.md) |  | [optional]
**activated** | **\DateTime** | The date and time the experiment was activated. | [optional]
**state** | **string** | A disabled experiment is not evaluated for rules or coupons. | [optional] [default to 'disabled']
**variants** | [**\TalonOne\Client\Model\ExperimentVariant[]**](ExperimentVariant.md) |  | [optional]
**deletedat** | **\DateTime** | The date and time the experiment was deleted. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
