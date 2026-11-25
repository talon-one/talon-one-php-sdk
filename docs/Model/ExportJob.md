# ExportJob

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | [**\TalonOne\Client\Model\ExportJobType**](ExportJobType.md) |  |
**args** | **array<string,mixed>** | Arguments for the exporter. Their structure depends on &#x60;type&#x60; and is validated by the service. |
**destination** | [**\TalonOne\Client\Model\ExportJobDestination[]**](ExportJobDestination.md) | Destinations for the export job. |
**cronSchedule** | **string** | Schedule in standard 5-field cron format. |
**timezone** | **string** | A string containing an IANA timezone descriptor. | [optional] [default to 'UTC']
**enabled** | **bool** | Whether the export job is enabled. | [optional] [default to false]
**allowConcurrentRuns** | **bool** | Whether to allow concurrent runs of the job. | [optional] [default to false]
**overrideFilename** | **string** | Filename that replaces the generated export filename, without extension. | [optional]
**id** | **int** | The internal ID of this entity. |
**accountId** | **int** | The ID of the account that owns this entity. |
**status** | [**\TalonOne\Client\Model\ExportJobStatus**](ExportJobStatus.md) |  |
**created** | **\DateTime** | The time this entity was created. |
**modified** | **\DateTime** | The time this entity was modified. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
