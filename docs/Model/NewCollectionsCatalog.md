# # NewCollectionsCatalog

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**title** | **string** | The display name for the collection catalog. |
**description** | **string** | A longer, more detailed description of the collection catalog. | [optional]
**category** | **string** | Category used to group collection catalogs. | [optional] [default to 'custom']
**rules** | [**\TalonOne\Client\Model\CatalogRule[]**](CatalogRule.md) | Array of rules to store in this collection catalog. Rules should only contain title (no description, as description is at the collection catalog level). At least one rule or cart item filter is required. | [optional]
**cartItemFilters** | [**\TalonOne\Client\Model\CartItemFilterTemplate[]**](CartItemFilterTemplate.md) | Array of cart item filters to store in this collection catalog. If not provided, will be extracted from the rules. Cart item filters should only contain name (no description, as description is at the collection catalog level). | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
