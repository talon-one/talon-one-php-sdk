# # Giveaway

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | The internal ID of this entity. |
**created** | **\DateTime** | The time this entity was created. |
**code** | **string** | The code value of this giveaway. |
**poolId** | **int** | The ID of the pool to return giveaway codes from. |
**startDate** | **\DateTime** | Timestamp at which point the giveaway becomes valid. | [optional]
**endDate** | **\DateTime** | Timestamp at which point the giveaway becomes invalid. | [optional]
**attributes** | **object** | Arbitrary properties associated with this giveaway. | [optional]
**used** | **bool** | Indicates whether this giveaway code was given before. | [optional]
**importId** | **int** | The ID of the Import which created this giveaway. | [optional]
**profileIntegrationId** | **string** | The third-party integration ID of the customer profile that was awarded the giveaway, if the giveaway was awarded. | [optional]
**profileId** | **int** | The internal ID of the customer profile that was awarded the giveaway, if the giveaway was awarded and an internal ID exists. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
