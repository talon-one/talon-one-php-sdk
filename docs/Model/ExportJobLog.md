# ExportJobLog

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | The internal ID of this entity. |
**exportJobId** | **int** | The internal ID of the connected export job. |
**type** | [**\TalonOne\Client\Model\ExportJobType**](ExportJobType.md) |  |
**result** | [**\TalonOne\Client\Model\ExportJobLogResult**](ExportJobLogResult.md) |  |
**filename** | **string** | Name of the exported file, without extension. |
**log** | **string** | The log text. |
**startedAt** | **\DateTime** | Time when the export job run started. |
**finishedAt** | **\DateTime** | Time when the export job run finished. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
