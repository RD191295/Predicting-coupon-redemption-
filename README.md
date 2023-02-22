# AI Student of the Year - ML Challenge[2023] By Machine Hack [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Atcold/pytorch-Deep-Learning/master)


## Introduction :
  Historical data utilised in producing coupons over several weeks is known for the task. One coupon, for example, applies to a single product. Furthermore, orders are still generated in response to the generation, including information on which coupons have been used and the overall basket value of each transaction. Using this data, a model for predicting coupon redemption and the total basket value should be learned. The target attributes "coupon 1 Used", "coupon2Used", and "coupon3Used" are described with the value "0" for coupons not redeemed and the value "1" for coupons redeemed. 

  The submission file should contain only one attribute, “CouponCombination”. It contains the decimal conversion of the combination of  "coupon1Used", "coupon2Used", and "coupon3Used". For example, if a customer uses coupons 1 and 3. The data representation for this condition would be “coupon 1 Used” reflects 1, “coupon 2 Used” reflects 0, and “coupon 3 Used” reflects 1. So in binary, this combination would represent 101. When converted to decimal format, it would be 5. Refer to the below table.

## Data :
 1. Train: 4237 x 33
 2. Test: 1816 x 33

## Data Dictionary:
Output feature: coupon{n}Used: Indicator for the coupon which is redeemed 0 (did not redeem) and 1(did redeem).

## Input feature:
  1. orderID : Order unique identification number
  2. orderTime : The time of order placed
  3. userID : The unique identification number of the customer
  4. couponID{n} : Identifier for the coupon, “n” ranges from 1 to 3
  5. price{n} : Current price of the coupon, “n” ranges from 1 to 3
  6. basePrice{n} : Original price of the coupon, “n” ranges from 1 to 3, “n” ranges from 1 to 3
  7. reward{n} : Score value for the value-added of the product of the retailer, “n” ranges from 1 to 3
  8. premiumProduct{n} : Indicator whether the coupon product is a premium product, “n” ranges from 1 to 3
  9. brand{n} : Brand of the coupon product, “n” ranges from 1 to 3
  10. productGroup{n} : Product line of the coupon product
  11. categoryIDs{n} : Identifier of the categories of the coupon product
  12. CouponCombination: It is a multiclass category which contains information about the decimal representation of the coupon redeemed.
