# # TemplateDef

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | The internal ID of this entity. |
**created** | **\DateTime** | The time this entity was created. |
**applicationId** | **int** | The ID of the Application that owns this entity. |
**title** | **string** | Campaigner-friendly name for the template that will be shown in the rule editor. |
**description** | **string** | A short description of the template that will be shown in the rule editor. | [optional]
**help** | **string** | Extended help text for the template. | [optional]
**category** | **string** | Used for grouping templates in the rule editor sidebar. |
**expr** | **mixed[]** | A Talang expression that contains variable bindings referring to args. |
**args** | [**\TalonOne\Client\Model\TemplateArgDef[]**](TemplateArgDef.md) | An array of argument definitions. |
**expose** | **bool** | A flag to control exposure in Rule Builder. | [optional] [default to false]
**name** | **string** | The template name used in Talang. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
