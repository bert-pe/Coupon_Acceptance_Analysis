Goal:
The goal of this project is to use visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.

The Context:
Imagine driving through town and a coupon is delivered to your cell phone for a restaurant near where you are driving. Would you accept that coupon and take a short detour to the restaurant? Would you accept the coupon but use it on a subsequent trip? Would you ignore the coupon entirely? 
What if the coupon was for a bar instead of a restaurant, or some other organisation?

Analysis in Jupyter Notebook:
The file called 5.1_Coupon_Analysis.ipynb contains the analysis. It was created by Berkeley/Emeritus with questions to explore in order for data analysis to be undertaken on a large data set.
The responses and the investigaton were conducted to allow showcasing of data analysis skills.


'Bar' attendance data:
# The regular bar attendance of more than 3 visits is the most significant
# predictor or whether a coupon for a bar will be accepted.


Investigation of all businesses, according to frequency of use:
# It is interesting to note the drop in coupon acceptance for the bar when 
# frequency is Greater than 8 times. Just going off the earlier investigation,
# we might have thought that high frequency is a good predictor.
# For greater restaurant usage then is greater coupon acceptance
# especially for the more expensive Restaurants (last graph)
# New Direction to investigate: 
# I want to further investigate 'Restaurant20To50'


# Noteworthy Patterns observed:

# 1. There is a very slight increase in coupon uptake when travelling
# in the same direction. Thie is very minimal.
# 2. When travelling with friends, there is a slight patten of higher
# coupon uptake.
# 3. Sunny gets more coupons accepted than rainy and snowing reduces
#   uptake in most cases.
# 4. There is a slight increase at 2pm compared to other times.
# 5. There is less uptake the greater the distance as shown by
#    toCoupon_GEQ15min and compared to toCoupon_GEQ25min
# 6. Having destination as 'No urgent place' generally sees higher uptake.


