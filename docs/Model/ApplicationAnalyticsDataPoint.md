# # ApplicationAnalyticsDataPoint

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**startTime** | **\DateTime** | The start of the aggregation time frame in UTC. |
**endTime** | **\DateTime** | The end of the aggregation time frame in UTC. |
**totalRevenue** | [**\TalonOne\Client\Model\AnalyticsDataPoint**](AnalyticsDataPoint.md) | The total, pre-discount value of all items purchased in a customer session. | [optional]
**sessionsCount** | [**\TalonOne\Client\Model\AnalyticsDataPoint**](AnalyticsDataPoint.md) | The number of all closed sessions. The &#x60;influenced&#x60; value includes only sessions with at least one applied effect. | [optional]
**avgItemsPerSession** | [**\TalonOne\Client\Model\AnalyticsDataPoint**](AnalyticsDataPoint.md) | The number of items from sessions divided by the number of sessions. The &#x60;influenced&#x60; value includes only sessions with at least one applied effect. | [optional]
**avgSessionValue** | [**\TalonOne\Client\Model\AnalyticsDataPoint**](AnalyticsDataPoint.md) | The average customer session value, calculated by dividing the revenue value by the number of sessions. The &#x60;influenced&#x60; value includes only sessions with at least one applied effect. | [optional]
**totalDiscounts** | **float** | The total value of discounts given for cart items in influenced sessions. | [optional]
**couponsCount** | **float** | The number of times a coupon was successfully redeemed in influenced sessions. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
