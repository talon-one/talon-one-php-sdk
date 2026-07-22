# StrikethroughBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this block. |
**type** | **string** | Identifies the block variant and determines which additional properties are present in it. |
**tags** | **string[]** | Semantic labels attached to this block. | [optional]
**operator** | **string** | The comparison operator applied to the attribute. |
**blocks** | [**\TalonOne\Client\Model\StrikethroughBlock[]**](StrikethroughBlock.md) | Child blocks evaluated according to the operator. |
**onFailure** | [**\TalonOne\Client\Model\StrikethroughBlock[]**](StrikethroughBlock.md) | Strikethrough blocks evaluated when this block fails or returns false. | [optional]
**onError** | **array<string,\TalonOne\Client\Model\StrikethroughBlock[]>** | Named error handlers evaluated when a specific error occurs. | [optional]
**expression** | **mixed[]** | The raw Talang expression as an array. For a function call, the first element is the function name and subsequent elements are its arguments. For any other expression (for example a bare attribute path or a literal value), this is a single-element array containing that value. |
**attribute** | **string** | The attribute path identifier (e.g. \&quot;$Session.Total\&quot;). |
**value** | **mixed** |  | [optional]
**min** | **mixed** |  | [optional]
**max** | **mixed** |  | [optional]
**values** | **mixed** |  | [optional]
**count** | **mixed** |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
