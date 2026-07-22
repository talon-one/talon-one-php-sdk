# BaseNotificationPolicy

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** | The name of the notification. |
**triggers** | [**\TalonOne\Client\Model\TierWillDowngradeNotificationTrigger[]**](TierWillDowngradeNotificationTrigger.md) |  |
**batchingEnabled** | **bool** | Indicates whether batching is activated. | [optional] [default to true]
**batchSize** | **int** | The required size of each batch of data. This value applies only when &#x60;batchingEnabled&#x60; is &#x60;true&#x60;. | [optional] [default to 1000]
**scopes** | **string[]** |  |
**includeData** | **bool** | Indicates whether to include all generated coupons. If &#x60;false&#x60;, only the &#x60;batchId&#x60; of the generated coupons is included. | [optional]
**aheadOfDaysTrigger** | **int** | The number of days in advance that strikethrough pricing updates should be sent. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
