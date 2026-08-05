# EffectProps

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**value** | **float** | The current progress of the customer in the achievement. |
**id** | **int** | The id of the referral code that was redeemed. |
**rejectionReason** | **string** | The reason why the code was rejected.  - &#x60;AdvocateNotFound&#x60;: The advocate was not found. - &#x60;CampaignLimitReached&#x60;: The campaign-wide referral code redemption limit has been reached. - &#x60;EffectCouldNotBeApplied&#x60;: One of the effects in the campaign wasn&#39;t applied because a limit for that effect was reached (most common use case will be &#x60;setDiscount&#x60; can not be applied because a discount limit is reached). - &#x60;ProfileLimitReached&#x60;: The profile-specific referral code redemption limit has been reached. - &#x60;ReferralCustomerAlreadyReferred&#x60;: The friend is already referred. - &#x60;ReferralExpired&#x60;: The transferred referral code is expired. - &#x60;ReferralLimitReached&#x60;: The referral code redemption limit has been reached. - &#x60;ReferralNotFound&#x60;: The transferred referral code is wrong. - &#x60;ReferralPartOfNotRunningCampaign&#x60;: The campaign the referral code belongs to is currently not active. The campaign ID field shows the ID of that campaign. - &#x60;ReferralRecipientDoesNotMatch&#x60;: The given referral code value does not match the recipient. - &#x60;ReferralRecipientIdSameAsAdvocate&#x60;: The recipient (friend) has the same id as the advocate. - &#x60;ReferralRejectedByCondition&#x60;: The referral code is valid and in an active campaign, but there were other conditions in that campaign&#39;s rules that were not met. - &#x60;ReferralStartDateInFuture&#x60;: The transferred referral code isn&#39;t active yet. - &#x60;ReferralPartOfNotTriggeredCampaign&#x60;: The campaign the referral code belongs to was not triggered during evaluation (an exclusive or stackable campaign). The campaign ID field shows the ID of that campaign. |
**conditionIndex** | **int** | The index of the condition that caused the rejection of the referral. | [optional]
**effectIndex** | **int** | The index of the effect that caused the rejection of the referral. | [optional]
**details** | **string** | More details about the failure. | [optional]
**campaignExclusionReason** | **string** | The reason why the campaign the referral belongs to was excluded during [campaign evaluation](https://docs.talon.one/docs/product/applications/manage-campaign-evaluation), when &#x60;rejectionReason&#x60; was &#x60;CouponPartOfNotTriggeredCampaign&#x60;. Its possible values are:  - &#x60;CampaignGaveLowerDiscount&#x60;: The required campaign and referral conditions were met, but another campaign in a [Highest discount value](https://docs.talon.one/docs/product/applications/manage-campaign-evaluation#set-campaign-evaluation-mode) group offered a higher discount value. - &#x60;CampaignIsNotFirst&#x60;: The campaign was not evaluated because another campaign in a [First campaign](https://docs.talon.one/docs/product/applications/manage-campaign-evaluation#set-campaign-evaluation-mode) group was picked and evaluated first. - &#x60;CampaignNotInEvaluationSet&#x60;: The campaign did not meet other evaluation requirements, for example, because the referral is part of an archived campaign. | [optional]
**profileId** | **int** | The internal ID of the customer profile. |
**name** | **string** | The description of this discount. &#x60;#number&#x60; is appended to the name. It is equal to the &#x60;position&#x60; property. |
**scope** | **string** | The scope of the rolled back discount.  - For a discount per session, it can be one of &#x60;cartItems&#x60;, &#x60;additionalCosts&#x60; or &#x60;sessionTotal&#x60; - For a discount per item, it can be one of &#x60;price&#x60;, &#x60;additionalCosts&#x60; or &#x60;itemTotal&#x60; | [optional]
**desiredValue** | **float** | _[(Partial discounts enabled only)](https://docs.talon.one/docs/product/applications/manage-general-settings#partial-discounts)_. The monetary value of the discount to be applied to the additional cost without considering budget limitations. | [optional]
**position** | **float** | The index of the item in the &#x60;cartItem&#x60; object containing the additional cost that this discount applies to. |
**subPosition** | **float** | The index of the item unit in its line item. | [optional]
**totalDiscount** | **float** | _(Pro rata discounts only)_ The monetary value of the total effective discount | [optional]
**desiredTotalDiscount** | **float** | _(Pro rata discounts only)_ The monetary value of the total discount to be applied without considering budget limitations | [optional]
**bundleIndex** | **int** | The position of the bundle in a list of item bundles created from the same bundle definition. | [optional]
**bundleName** | **string** | The name of the bundle definition. | [optional]
**targetedItemPosition** | **float** | _(Discounting individual item in bundles only)_ The index of the targeted bundle item on which the applied discount is based. | [optional]
**targetedItemSubPosition** | **float** | _(Discounting individual item in bundles only)_ The sub-position of the targeted bundle item on which the applied discount is based. | [optional]
**excludedFromPriceHistory** | **bool** | When set to &#x60;true&#x60;, the applied discount is excluded from the item&#39;s price history. | [optional]
**additionalCostId** | **int** | The identifier of the additional cost to be discounted. |
**additionalCost** | **string** | The API name of the additional cost to be discounted. |
**webhookId** | **float** | The internal ID of the webhook. |
**webhookName** | **string** | The name of the webhook. |
**programId** | **int** | ID of the loyalty program that contains these points. |
**subLedgerId** | **string** | API name of the loyalty program subledger that contains these points. |
**recipientIntegrationId** | **string** | The integration ID of the customer that receives the giveaway. |
**startDate** | **\DateTime** | Timestamp at which the customer&#39;s progress started. |
**expiryDate** | **\DateTime** | The date after which the reimbursed points will expire. | [optional]
**transactionUUID** | **string** | The identifier of this loyalty point transaction. |
**cartItemPosition** | **float** | The index of the item in the cart item list to which the custom effect is applied. | [optional]
**cartItemSubPosition** | **float** | For cart items with quantity &gt; 1, the sub position indicates to which item unit the custom effect is applied. | [optional]
**cardIdentifier** | **string** | The identifier of the card from which these points were originally deducted. | [optional]
**awaitsActivation** | **bool** | Indicates whether the points have an action-based start date. This property is returned only for point transactions with an action-based start date. | [optional]
**validityDuration** | **string** | The duration for which the points remain active, calculated relative to their start date. | [optional]
**ruleTitle** | **string** | The title of the rule that triggered the tier upgrade. |
**previousTierName** | **string** | The name of the tier from which the user was upgraded. | [optional]
**newTierName** | **string** | The name of the tier to which the user has been upgraded. |
**sku** | **string** | SKU of the item that needs to be added. |
**desiredQuantity** | **int** | The original quantity in case a partial reward was applied. | [optional]
**notificationType** | **string** | The type of notification. |
**title** | **string** | The title of the notification. |
**body** | **string** | The body of the notification. |
**path** | **string** | The entity type and the attribute name. |
**description** | **string** | Description of the product bundle. |
**bundleAttributes** | **string[]** | The cart item attributes that determined which items are being bundled together. |
**itemsIndices** | **float[]** | The indices in the cart items array of the bundled items. |
**poolId** | **int** | The internal ID of the giveaway pool. |
**poolName** | **string** | The name of the giveaway pool. |
**giveawayId** | **int** | The internal ID of the giveaway. |
**code** | **string** | The giveaway code to be rewarded. |
**message** | **string** | The error message. |
**effectId** | **int** | The ID of the custom effect that was triggered. |
**payload** | **object** | The JSON payload of the custom effect. |
**couponValue** | **string** | The coupon code that was created. |
**profileIntegrationId** | **string** | The ID of the customer profile in the third-party integration platform. |
**isNewReservation** | **bool** | Indicates whether this is a new coupon reservation or not. |
**audienceId** | **int** | The internal ID of the audience. | [optional]
**audienceName** | **string** | The name of the audience. | [optional]
**achievementId** | **int** | The ID of the achievement. |
**achievementName** | **string** | The name of the achievement. |
**progressTrackerId** | **int** | The ID of the customer&#39;s progress tracker for this achievement.  For [on-completion achievements](https://docs.talon.one/docs/product/campaigns/achievements/achievements-overview#recurring-on-completion-achievements), this effect generates a unique ID for each iteration. |
**delta** | **float** | The value by which the customer&#39;s current progress in the achievement has increased. |
**target** | **float** | The target value to complete the achievement. |
**isJustCompleted** | **bool** | Indicates if the customer has completed the achievement in the current session. |
**decreaseProgressBy** | **float** | The value by which the customer&#39;s current progress in the achievement has decreased. |
**currentProgress** | **float** | The current progress of the customer in the achievement. |
**extensionDuration** | **string** | Time frame by which the expiry date extends.  The time format is either: - immediate, or - an **integer** followed by a letter indicating the time unit.  Examples: &#x60;immediate&#x60;, &#x60;30s&#x60;, &#x60;40m&#x60;, &#x60;1h&#x60;, &#x60;5D&#x60;, &#x60;7W&#x60;, &#x60;10M&#x60;, &#x60;15Y&#x60;.  Available units:  - &#x60;s&#x60;: seconds - &#x60;m&#x60;: minutes - &#x60;h&#x60;: hours - &#x60;D&#x60;: days - &#x60;W&#x60;: weeks - &#x60;M&#x60;: months - &#x60;Y&#x60;: years  You can round certain units up or down: - &#x60;_D&#x60; for rounding down days only. Signifies the start of the day. - &#x60;_U&#x60; for rounding up days, weeks, months and years. Signifies the end of the day, week, month or year. |
**affectedTransactions** | [**\TalonOne\Client\Model\LoyaltyLedgerEntryExpiryDateChange[]**](LoyaltyLedgerEntryExpiryDateChange.md) | List of transactions affected by the expiry date update. | [optional]
**newExpiryDate** | **\DateTime** | The specified expiry date and time for all active and pending point transactions in the loyalty program subledger. |
**endDate** | **\DateTime** | Timestamp at which this progress period ends.  Only returned for achievements that have a fixed end date. [On-completion achievements](https://docs.talon.one/docs/product/campaigns/achievements/achievements-overview#recurring-on-completion-achievements) have no end date. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
