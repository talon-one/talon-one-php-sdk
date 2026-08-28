# SelectorStep

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | A step discriminator of type &#x60;filter&#x60;. |
**predicate** | [**\TalonOne\Client\Model\Block**](Block.md) |  |
**fields** | [**\TalonOne\Client\Model\SortSelectorStepField[]**](SortSelectorStepField.md) | One or more fields to sort by, applied in order. Each field has its own direction. |
**operator** | **string** | The aggregation operator applied to the items produced by the preceding step: - &#x60;max&#x60;, &#x60;min&#x60;, and &#x60;sum&#x60; operate on numeric values. - &#x60;count&#x60; returns the number of items. - &#x60;empty&#x60; reports whether the list is empty. |
**from** | [**\TalonOne\Client\Model\SelectSelectorStepFrom**](SelectSelectorStepFrom.md) |  | [optional]
**to** | **int** | The end index for the &#x60;between&#x60; operator. The item at this index is not included. | [optional]
**count** | **int** | The maximum number of items to select for the &#x60;many&#x60; operator. | [optional]
**index** | **int** | The exact position of the item to select for the &#x60;one&#x60; operator. | [optional]
**partial** | **bool** | Indicates if the step returns fewer items than requested when the source list is shorter than the range needs. Always &#x60;true&#x60; for the &#x60;many&#x60; and &#x60;between&#x60; operators; not present for &#x60;one&#x60;, which fails instead of returning a partial result. | [optional]
**expression** | **string** | The attribute path each item is mapped to. |
**valueMap** | [**\TalonOne\Client\Model\SelectorValueMapRef**](SelectorValueMapRef.md) |  |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
