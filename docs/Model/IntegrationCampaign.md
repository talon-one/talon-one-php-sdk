# # IntegrationCampaign

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**applicationId** | **int** | The ID of the Application that owns this entity. |
**id** | **int** | Unique ID of Campaign. |
**name** | **string** | A user-facing name for this campaign. |
**description** | **string** | A detailed description of the campaign. | [optional]
**startTime** | **\DateTime** | Timestamp when the campaign will become active. | [optional]
**endTime** | **\DateTime** | Timestamp when the campaign will become inactive. | [optional]
**attributes** | **object** | Arbitrary properties associated with this campaign. | [optional]
**state** | **string** | The state of the campaign. | [default to 'enabled']
**tags** | **string[]** | A list of tags for the campaign. |
**features** | **string[]** | The features enabled in this campaign. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
