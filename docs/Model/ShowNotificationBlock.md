# ShowNotificationBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this block. |
**type** | **string** | Identifies the block variant and determines which additional properties are present in it. |
**tags** | **string[]** | Semantic labels attached to this block. | [optional]
**notificationType** | **string** | The type of notification to display. |
**title** | **string** | The notification heading shown to the customer. |
**body** | **string** | The notification body text. Supports template placeholders (e.g. \&quot;{{$Session.Total}}\&quot;) evaluated at rule execution time. | [optional]
**onFailure** | [**\TalonOne\Client\Model\Block[]**](Block.md) | Blocks evaluated when this block fails or returns false. | [optional]
**onError** | **array<string,\TalonOne\Client\Model\Block[]>** | Named error handlers evaluated when a specific error occurs. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
