# History

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | The ID of the price record. |
**observedAt** | **\DateTime** | The date and time from which the price record is effective. |
**contextIds** | **string[]** | The identifiers of the relevant context (the sales events, e.g. \&quot;Spring Sale\&quot;, \&quot;Summer Sale\&quot;) at the time from which the price record is effective. Includes the context IDs of any price adjustments and of the campaigns that influenced the final price. |
**price** | **float** | Price of the item. |
**metadata** | [**\TalonOne\Client\Model\BestPriorPriceMetadata**](BestPriorPriceMetadata.md) |  |
**target** | [**\TalonOne\Client\Model\LabelTarget**](LabelTarget.md) |  |
**excludedAt** | **\DateTime** | The date and time when the price record was excluded. | [optional]
**exclusionReason** | **string** | The reason for excluding this price record. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
