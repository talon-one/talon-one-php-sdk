# LoyaltyCardBatch

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**numberOfCards** | **int** | Number of loyalty cards in the batch. |
**batchId** | **string** | ID of the loyalty card batch. | [optional]
**status** | **string** | Status of the loyalty cards in the batch. | [optional] [default to 'active']
**attributes** | **object** | Set values for the [custom attributes](https://docs.talon.one/docs/dev/concepts/attributes#custom-attributes) of a loyalty card. These attributes must be created in the Campaign Manager before their values can be updated through this endpoint. | [optional]
**cardCodeSettings** | [**\TalonOne\Client\Model\CodeGeneratorSettings**](CodeGeneratorSettings.md) |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
