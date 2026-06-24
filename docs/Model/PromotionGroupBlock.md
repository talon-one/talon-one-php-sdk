# PromotionGroupBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this block. |
**type** | **string** | Identifies the block variant and determines which additional properties are present in it. |
**tags** | **string[]** | Semantic labels attached to this block. | [optional]
**operator** | **string** | Logical operator applied across child blocks. &#x60;all&#x60; requires every child to pass, &#x60;atLeastOne&#x60; requires at least one, &#x60;none&#x60; requires all to fail. |
**blocks** | **mixed[]** | Child blocks evaluated according to the operator. |
**onFailure** | **mixed[]** | Promotion blocks evaluated when this block fails or returns false. | [optional]
**onError** | **array<string,mixed[]>** | Named error handlers evaluated when a specific error occurs. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
