# # Picklist

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | The internal ID of this entity. |
**created** | **\DateTime** | The time this entity was created. |
**type** | **string** | The type of allowed values in the picklist. If the type &#x60;time&#x60; is chosen, it must be an RFC3339 timestamp string. |
**values** | **string[]** | The list of allowed values provided by this picklist. |
**modifiedBy** | **int** | ID of the user who last updated this effect if available. | [optional]
**createdBy** | **int** | ID of the user who created this effect. |
**accountId** | **int** | The ID of the account that owns this entity. | [optional]
**imported** | **bool** | Imported flag shows that a picklist is imported by a CSV file or not | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
