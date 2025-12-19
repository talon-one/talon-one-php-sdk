# # CouponConstraints

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**usageLimit** | **int** | The number of times the coupon code can be redeemed. &#x60;0&#x60; means unlimited redemptions but any campaign usage limits will still apply. | [optional]
**discountLimit** | **float** | The total discount value that the code can give. Typically used to represent a gift card value. | [optional]
**reservationLimit** | **int** | The number of reservations that can be made with this coupon code. | [optional]
**startDate** | **\DateTime** | Timestamp at which point the coupon becomes valid. | [optional]
**expiryDate** | **\DateTime** | Expiration date of the coupon. Coupon never expires if this is omitted. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
