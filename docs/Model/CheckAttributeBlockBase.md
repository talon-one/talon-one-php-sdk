# CheckAttributeBlockBase

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this block. |
**type** | **string** | Identifies the block variant and determines which additional properties are present in it. |
**tags** | **string[]** | Semantic labels attached to this block. | [optional]
**operator** | **string** | The comparison operator applied to the attribute. |
**attribute** | **mixed** | The attribute path identifier (e.g. \&quot;$Session.Total\&quot;). |
**value** | **mixed** | The comparison value for scalar operators. | [optional]
**min** | **mixed** | The minimum value allowed for the &#x60;between&#x60; operator. | [optional]
**max** | **mixed** | The maximum value allowed for the &#x60;between&#x60; operator. | [optional]
**start** | **mixed** | The start value for the &#x60;within&#x60; operator. | [optional]
**end** | **mixed** | The end value for the &#x60;within&#x60; operator. | [optional]
**startInclusive** | **bool** | When &#x60;true&#x60;, the &#x60;start&#x60; value is included in the range for the &#x60;within&#x60; operator. | [optional]
**endInclusive** | **bool** | When &#x60;true&#x60;, the &#x60;end&#x60; value is included in the range for the &#x60;within&#x60; operator. | [optional]
**timezoneInsensitive** | **bool** | Indicates whether the &#x60;within&#x60; operator ignores time zones and compares the wall-clock time only. When &#x60;false&#x60;, time zones are taken into account. | [optional]
**values** | **mixed** | The set of values to match against for list operators. For location operators (&#x60;in&#x60;, &#x60;not(in)&#x60;), an array of objects with a &#x60;geometry&#x60; (see &#x60;GeoJSONGeometry&#x60;) and an optional &#x60;name&#x60;, or a string reference to a list attribute. | [optional]
**count** | **mixed** | The count threshold for &#x60;containsAtLeast&#x60; and &#x60;containsExactly&#x60; operators. | [optional]
**onFailure** | [**\TalonOne\Client\Model\Block[]**](Block.md) | Promotion blocks evaluated when this block fails or returns false. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
