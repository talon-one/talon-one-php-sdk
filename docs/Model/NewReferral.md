# # NewReferral

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**startDate** | **\DateTime** | Timestamp at which point the referral code becomes valid. | [optional]
**expiryDate** | **\DateTime** | Expiration date of the referral code. Referral never expires if this is omitted. | [optional]
**usageLimit** | **int** | The number of times a referral code can be used. &#x60;0&#x60; means no limit but any campaign usage limits will still apply. | [optional]
**campaignId** | **int** | ID of the campaign from which the referral received the referral code. |
**advocateProfileIntegrationId** | **string** | The Integration ID of the Advocate&#39;s Profile. |
**friendProfileIntegrationId** | **string** | An optional Integration ID of the Friend&#39;s Profile. | [optional]
**attributes** | **object** | Arbitrary properties associated with this item. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
