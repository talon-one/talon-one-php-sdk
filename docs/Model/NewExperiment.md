# # NewExperiment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**isVariantAssignmentExternal** | **bool** | The source of the assignment. - false - The assignment to the variant is handled internally by the Talon.Oneandled internally by the Talon.One. - true - The assignment to the variant handled externally. |
**activated** | **\DateTime** | The date and time the experiment was activated. | [optional]
**state** | **string** | A disabled experiment is not evaluated for rules or coupons. | [optional] [default to 'disabled']
**campaign** | [**\TalonOne\Client\Model\NewCampaign**](NewCampaign.md) |  |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
