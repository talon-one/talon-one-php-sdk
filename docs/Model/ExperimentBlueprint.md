# ExperimentBlueprint

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | The internal ID of this experiment blueprint. |
**accountId** | **int** | The ID of the account that owns this experiment blueprint. |
**applicationId** | **int** | The ID of the Application that owns this experiment blueprint. |
**title** | **string** | A short description of the experiment blueprint. |
**description** | **string** | A longer, more detailed description of the experiment blueprint. | [optional]
**category** | **string** | Category used to group experiment blueprints. |
**source** | **string** | Indicates whether the experiment blueprint is custom or shipped by Talon.One. |
**variants** | [**\TalonOne\Client\Model\ExperimentBlueprintVariant[]**](ExperimentBlueprintVariant.md) | Array of experiment variant templates in this experiment blueprint. Variants only contain name, weight, ruleset and the primary flag. |
**cartItemFilters** | [**\TalonOne\Client\Model\CartItemFilterTemplate[]**](CartItemFilterTemplate.md) | Array of cart item filter templates in this experiment blueprint. Cart item filters only contain name (no description, as description is at the experiment blueprint level). |
**created** | **\DateTime** | Timestamp when the experiment blueprint was created. |
**createdBy** | **int** | ID of the user who created the experiment blueprint. |
**modified** | **\DateTime** | Timestamp when the experiment blueprint was last updated. | [optional]
**modifiedBy** | **int** | ID of the user who last updated the experiment blueprint. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
