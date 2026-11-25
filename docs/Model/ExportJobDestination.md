# ExportJobDestination

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | Destination type can be Google Cloud Storage (gcs) or file. |
**compression** | **string** | Compression applied to the exported file. | [optional] [default to 'none']
**path** | **string** | Directory on the exporter host where the file is written. Required for file destinations; must be omitted for gcs. | [optional]
**bucket** | **string** | GCS bucket name for storage. Absent for file. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
