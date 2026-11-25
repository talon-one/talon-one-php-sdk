# OutboundLogs

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**nextCursor** | **string** | Cursor for the next page of results. Omitted when there are no more results. | [optional]
**data** | [**\TalonOne\Client\Model\OutboundLogsDataInner[]**](OutboundLogsDataInner.md) | List of outbound log entries. The &#x60;type&#x60; field determines the kind of entry. When an error ends the response, an &#x60;OutboundLogStreamErrorEntry&#x60; is the last item and the response is incomplete. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
