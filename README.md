# MLAI-practical-assignment-5.1
Analysis of coupon performance: Will a Customer Accept the Coupon?

Findings:
* Overall coupon conversion rate: 57%
* Bar coupons conversion rate: 41%
  * Users that had > 3 bar visits conversion rate: 77%, for users that had <= 3 bar visits: 37%
  * Generally similar performance based on 1 or more bar visits/month
  * Additional analysis on Bar coupons show that bar frequency was consistently a strong indicator for conversion
* Independent investigation: Does an income threshold of $50K impact coupon conversion for cheaper vs. expensive restaurants?
  * Income does not seem to affect coupon conversion for cheap restaurants.  Both perform at ~70%, which seems to be very good. $50K may not be a good threshold, further analysis recommended for the largest coupon offering: cheaper restaurants.
  * Income does not seem to affect coupon conversion for expensive restaurants.  Both perform at ~43%.
  * Coupons for lower priced restaurants perform +60% better than more expensive restaurant coupons: 70% vs. 43%.  Based on an income threshold of +/- $50K there was little difference to coupon performance for restaurant coupons.

Additional detail:
* 12,684 data records: Bar coupons made up 2017 records
* "car" field was mostly null and was excluded from any analysis (prompt 2 and 3)
* Only 3 temperature values in the data: 30, 55, 80

