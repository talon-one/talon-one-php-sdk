# CheckAttributeBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this block. |
**type** | **string** | A block discriminator of type &#x60;checkAttribute&#x60;. |
**tags** | **string[]** | Semantic labels attached to this block. | [optional]
**operator** | **string** | The comparison operator applied to the attribute. |
**attribute** | **mixed** |  |
**value** | **mixed** |  | [optional]
**min** | **mixed** |  | [optional]
**max** | **mixed** |  | [optional]
**start** | **mixed** |  | [optional]
**end** | **mixed** |  | [optional]
**startInclusive** | **bool** | When &#x60;true&#x60;, the &#x60;start&#x60; value is included in the range for the &#x60;within&#x60; operator. | [optional]
**endInclusive** | **bool** | When &#x60;true&#x60;, the &#x60;end&#x60; value is included in the range for the &#x60;within&#x60; operator. | [optional]
**timezoneInsensitive** | **bool** | Indicates whether the &#x60;within&#x60; operator ignores time zones and compares the wall-clock time only. When &#x60;false&#x60;, time zones are taken into account. | [optional]
**values** | **mixed** |  | [optional]
**count** | **mixed** |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
