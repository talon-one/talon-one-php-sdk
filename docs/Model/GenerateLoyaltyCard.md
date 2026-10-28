# GenerateLoyaltyCard

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**status** | **string** | Status of the loyalty card. | [optional] [default to 'active']
**customerProfileIds** | **string[]** | Integration IDs of the customer profiles linked to the card. | [optional]
**cardIdentifier** | **string** | The identifier of the loyalty card, which must match the regular expression &#x60;^[A-Za-z0-9._%+@-]+$&#x60;. | [optional]
**attributes** | **object** | Set values for the [custom attributes](https://docs.talon.one/docs/dev/concepts/attributes#custom-attributes) of a loyalty card. These attributes must be created in the Campaign Manager before their values can be updated through this endpoint. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
