# StrikethroughCheckAttributeBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this block. |
**type** | **string** | Identifies the block variant and determines which additional properties are present in it. |
**tags** | **string[]** | Semantic labels attached to this block. | [optional]
**operator** | **string** | The comparison operator applied to the attribute. |
**attribute** | **string** | The attribute path identifier (e.g. \&quot;$Session.Total\&quot;). |
**value** | **mixed** |  | [optional]
**min** | **mixed** |  | [optional]
**max** | **mixed** |  | [optional]
**values** | **mixed** |  | [optional]
**count** | **mixed** |  | [optional]
**onFailure** | [**\TalonOne\Client\Model\StrikethroughBlock[]**](StrikethroughBlock.md) | Strikethrough blocks evaluated when this block fails or returns false. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
