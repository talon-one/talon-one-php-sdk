# # LoyaltyProgramLedgers

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | The internal ID of loyalty program. |
**title** | **string** | Visible name of loyalty program. |
**name** | **string** | Internal name of loyalty program. |
**joinDate** | **\DateTime** | The date on which the customer joined the loyalty program in RFC3339.  **Note**: This is in the loyalty program&#39;s time zone. | [optional]
**ledger** | [**\TalonOne\Client\Model\LedgerInfo**](LedgerInfo.md) | Information about the main ledger in the loyalty program. |
**subLedgers** | [**array<string,\TalonOne\Client\Model\LedgerInfo>**](LedgerInfo.md) | A map containing information about each loyalty subledger. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
