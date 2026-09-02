# UpdateAttributeValueBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this block. | [optional] [readonly]
**type** | **string** | Identifies the block variant and determines which additional properties are present in it. |
**tags** | **string[]** | Semantic labels attached to this block. | [optional]
**operator** | **string** | The update operation applied to the attribute. |
**attribute** | [**\TalonOne\Client\Model\UpdateAttributeValueBlock1Attribute**](UpdateAttributeValueBlock1Attribute.md) |  |
**value** | **mixed** | The value of the attribute. Omitted when operator is set to &#x60;toggle&#x60;. | [optional]
**target** | [**\TalonOne\Client\Model\UpdateAttributeValueBlock1Target**](UpdateAttributeValueBlock1Target.md) |  |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
