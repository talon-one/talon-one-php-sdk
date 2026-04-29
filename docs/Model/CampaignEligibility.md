# CampaignEligibility

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | Unique ID of Campaign. |
**applicationId** | **int** | The ID of the Application that owns this entity. |
**name** | **string** | The name of the campaign. |
**description** | **string** | A detailed description of the campaign. | [optional]
**startTime** | **\DateTime** | Timestamp when the campaign will become active. | [optional]
**endTime** | **\DateTime** | Timestamp when the campaign will become inactive. | [optional]
**attributes** | **object** | Arbitrary properties associated with this campaign. | [optional]
**state** | **string** | The state of the campaign. | [default to 'enabled']
**tags** | **string[]** | A list of tags for the campaign. |
**features** | **string[]** | The features enabled in this campaign. |
**rules** | [**\TalonOne\Client\Model\RuleMetadata[]**](RuleMetadata.md) | A list of rules containing customer-facing details of the rewards defined in the campaign. | [optional]
**eligibility** | [**\TalonOne\Client\Model\CampaignEligibilityDetails[]**](CampaignEligibilityDetails.md) | The customer&#39;s eligibility for each campaign in the current customer session. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
