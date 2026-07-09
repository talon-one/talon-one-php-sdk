# RiskDetail

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | The internal ID of this entity. |
**created** | **\DateTime** | The time this entity was created. |
**notificationId** | **int** | The ID of the risk notification rule that flagged this risk. |
**featureDate** | **\DateTime** | The date of the activity data in which this risk was detected. The anomaly detection pipeline scores complete 24-hour cycles, so this is always the day before the risk was reported, not the reporting date itself. |
**groupKey** | **string** | The Application group this risk was detected in. Contains the Application ID, or &#x60;__GLOBAL__&#x60; for metrics that are not grouped by Application. |
**applicationId** | **int** | The ID of the Application this risk belongs to. Absent for global metrics. | [optional]
**status** | **string** | The triage lifecycle status of this risk. |
**criticality** | **string** | The critical classification bucket of this risk. |
**entity** | **string** | The entity type the risk was detected in. |
**activity** | **string** | The activity metric the risk was detected in. |
**timeFrame** | **string** | The rolling time window of the risk evaluation. |
**reportedDate** | **\DateTime** | The time the ML service reported this risk. |
**affectedEntityCount** | **int** | The total number of entities affected by this risk. |
**description** | **string** | Human-readable description of the detected anomaly. | [optional]
**modified** | **\DateTime** | Timestamp of the most recent update. |
**affectedEntities** | [**\TalonOne\Client\Model\RiskAffectedEntityItem[]**](RiskAffectedEntityItem.md) | The affected entities with the highest severity ratios, in descending order. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
