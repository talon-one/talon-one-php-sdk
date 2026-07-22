# UpdateAudienceMembershipBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** | Unique identifier for this block. |
**type** | **string** | Identifies the block variant and determines which additional properties are present in it. |
**tags** | **string[]** | Semantic labels attached to this block. | [optional]
**operator** | **string** | The action to perform. |
**profile** | **string** | The customer profile to add or remove from the audience. &#x60;Current&#x60; targets the customer in the current session; &#x60;Advocate&#x60; targets the person who invited their friend via referral program. |
**audience** | [**\TalonOne\Client\Model\UpdateAudienceMembershipBlock1Audience**](UpdateAudienceMembershipBlock1Audience.md) |  |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
