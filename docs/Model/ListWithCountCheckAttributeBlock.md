# ListWithCountCheckAttributeBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this block. | [optional] [readonly]
**type** | **string** | A block discriminator of type &#x60;checkAttribute&#x60;. |
**tags** | **string[]** | Semantic labels attached to this block. | [optional] [readonly]
**operator** | **string** | The list membership operator with a count threshold applied to the attribute. |
**attribute** | **mixed** | The attribute path identifier (e.g. \&quot;$Session.Total\&quot;). |
**value** | **mixed** | The comparison value for scalar operators. | [optional]
**min** | **mixed** | The minimum value allowed for the &#x60;between&#x60; operator. | [optional]
**max** | **mixed** | The maximum value allowed for the &#x60;between&#x60; operator. | [optional]
**start** | **mixed** | The start value for the &#x60;within&#x60; operator. | [optional]
**end** | **mixed** | The end value for the &#x60;within&#x60; operator. | [optional]
**startInclusive** | **bool** | When &#x60;true&#x60;, the &#x60;start&#x60; value is included in the range for the &#x60;within&#x60; operator. | [optional]
**endInclusive** | **bool** | When &#x60;true&#x60;, the &#x60;end&#x60; value is included in the range for the &#x60;within&#x60; operator. | [optional]
**timezoneInsensitive** | **bool** | Indicates whether the &#x60;within&#x60; operator ignores time zones and compares the wall-clock time only. When &#x60;false&#x60;, time zones are taken into account. | [optional]
**values** | **mixed** | The set of values to match against. |
**count** | **mixed** | The count threshold for this operator. |
**onFailure** | [**\TalonOne\Client\Model\Block[]**](Block.md) | Promotion blocks evaluated when this block fails or returns false. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
