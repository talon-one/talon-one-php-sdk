# # CollectionsCatalog

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **int** | The internal ID of this collection. |
**accountId** | **int** | The ID of the account that owns this collection. |
**applicationId** | **int** | The ID of the Application that owns this collection. |
**title** | **string** | A short description of the collection catalog. |
**description** | **string** | A longer, more detailed description of the collection catalog. | [optional]
**category** | **string** | Category used to group collection catalogs. |
**source** | **string** | Indicates whether the collection is custom or shipped by Talon.One. |
**rules** | [**\TalonOne\Client\Model\CatalogRule[]**](CatalogRule.md) | Array of rule templates in this collection catalog. Rules only contain title (no description, as description is at the collection catalog level). |
**cartItemFilters** | [**\TalonOne\Client\Model\CartItemFilterTemplate[]**](CartItemFilterTemplate.md) | Array of cart item filter templates in this collection catalog. Cart item filters only contain name (no description, as description is at the collection catalog level). |
**created** | **\DateTime** | Timestamp when the collection was created. |
**createdBy** | **int** | ID of the user who created the collection. |
**modified** | **\DateTime** | Timestamp when the collection was last updated. | [optional]
**modifiedBy** | **int** | ID of the user who last updated the collection. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
