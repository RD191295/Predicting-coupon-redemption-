# AI Student of the Year - ML Challenge[2023] By Machine Hack
# Predicting-coupon-redemption [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Atcold/pytorch-Deep-Learning/master)


Historical data utilised in producing coupons over several weeks is known for the task. One coupon, for example, applies to a single product. Furthermore, orders are still generated in response to the generation, including information on which coupons have been used and the overall basket value of each transaction. Using this data, a model for predicting coupon redemption and the total basket value should be learned. The target attributes "coupon 1 Used", "coupon2Used", and "coupon3Used" are described with the value "0" for coupons not redeemed and the value "1" for coupons redeemed. 

The submission file should contain only one attribute, “CouponCombination”. It contains the decimal conversion of the combination of  "coupon1Used", "coupon2Used", and "coupon3Used". For example, if a customer uses coupons 1 and 3. The data representation for this condition would be “coupon 1 Used” reflects 1, “coupon 2 Used” reflects 0, and “coupon 3 Used” reflects 1. So in binary, this combination would represent 101. When converted to decimal format, it would be 5. Refer to the below table.
