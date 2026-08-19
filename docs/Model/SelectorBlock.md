# SelectorBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this block. |
**type** | **string** | A block discriminator of type &#x60;group&#x60;. |
**tags** | **string[]** | Semantic labels attached to this block. | [optional]
**operator** | **string** | Logical operator applied across child blocks. &#x60;all&#x60; requires every child to pass, &#x60;atLeastOne&#x60; requires at least one, &#x60;none&#x60; requires all to fail. |
**blocks** | [**\TalonOne\Client\Model\SelectorBlock[]**](SelectorBlock.md) | Child predicate blocks evaluated according to the operator. |
**expression** | **mixed[]** | The raw Talang expression as an array. For a function call, the first element is the function name and subsequent elements are its arguments. For any other expression (for example a bare attribute path or a literal value), this is a single-element array containing that value. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
