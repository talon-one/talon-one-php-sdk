# AwardDiscountBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this block. | [optional] [readonly]
**type** | **string** | Identifies the block variant and determines which additional properties are present in it. |
**tags** | **string[]** | Semantic labels attached to this block. | [optional] [readonly]
**name** | **string** | The human-readable label attached to the discount. |
**value** | [**\TalonOne\Client\Model\AwardDiscountBlock1Value**](AwardDiscountBlock1Value.md) |  |
**partial** | **bool** | Whether to apply a partial discount when the requested value exceeds the configured budget. |
**target** | [**\TalonOne\Client\Model\AwardDiscountTarget**](AwardDiscountTarget.md) |  |
**excludedFromPriceHistory** | **bool** | When set to &#x60;true&#x60;, the applied discount is excluded from the item&#39;s [price history](https://docs.talon.one/docs/dev/integration-guides/best-prior-price#price-history). | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
