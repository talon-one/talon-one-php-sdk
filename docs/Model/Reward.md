# Reward

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | The internal ID of this entity. |
**created** | **\DateTime** | The time this entity was created. |
**accountId** | **int** | The ID of the account that owns this entity. |
**name** | **string** | The name of the reward. |
**apiName** | **string** | A unique identifier used to reference the reward in API integrations. |
**description** | **string** | A description of the reward. | [optional]
**applicationIds** | **int[]** | The IDs of the Applications this reward is connected to.   **Note**: Currently, a reward can only be connected to one Application. |
**status** | **string** | The status of the reward. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
