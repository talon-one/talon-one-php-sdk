# BestPriorPrice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | The ID of the historical price. |
**sku** | **string** | sku |
**observedAt** | **\DateTime** | The date and time when the price was observed. |
**contextIds** | **string[]** | The identifiers of the relevant context at the time the price was observed. Includes the context IDs of any price adjustments and of the campaigns that influenced the final price. |
**price** | **float** | Price of the item. |
**metadata** | [**\TalonOne\Client\Model\BestPriorPriceMetadata**](BestPriorPriceMetadata.md) |  |
**target** | [**\TalonOne\Client\Model\LabelTarget**](LabelTarget.md) |  |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
