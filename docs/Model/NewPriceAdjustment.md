# NewPriceAdjustment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**priceType** | **string** | The price type (e.g. the price for members only) to apply to a given SKU. |
**price** | **float** | The value of the price type applied to the SKU. When set to &#x60;null&#x60;, the defined price type no longer applies to the SKU. | [optional]
**referenceId** | **string** | A unique reference identifier, e.g. a UUID. |
**calculatedAt** | **\DateTime** | The time at which this price was calculated. If provided, this is used to determine the most recent price adjustment to choose if price adjustments overlap. Defaults to internal creation time if not provided. | [optional]
**effectiveFrom** | **\DateTime** | The date and time from which the price adjustment is effective.  **Note**: If no timeframe is defined, the price adjustment is applied immediately and is effective until another, more recent, price adjustment is synced with the catalog. | [optional]
**effectiveUntil** | **\DateTime** | The date and time until which the price adjustment is effective.  **Note**: If no timeframe is defined, the price adjustment is applied immediately and is effective until another, more recent, price adjustment is synced with the catalog. | [optional]
**contextId** | **string** | Identifier of the context of this price adjustment (the sales event, e.g. \&quot;Summer Sale\&quot;). | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
