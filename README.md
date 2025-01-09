# Background
The goal of this project is to use what you know about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.
This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’. There are five different types of coupons -- less expensive restaurants (under 20), coffee houses, carry out & take away, bar, and more expensive restaurants (
20 - $50).

## Dataset
The dataset contains various features related to passengers, such as demographics, trip details, and coupon types. Key columns include:
- **destination**: Passenger's destination.
- **passenger**: Type of passenger (e.g., alone, with friends, family).
- **weather**: Weather conditions during the trip.
- **coupon**: Type of coupon offered.
- **expiration**: Time until the coupon expires.
- **age**: Age of the passenger.
- **maritalStatus**: Passenger's marital status.
- **Y**: Indicates whether the coupon was accepted (`1` for yes, `0` for no).

## Features Analyzed
1. **Demographics**
   - Age, marital status, and gender.
2. **Trip Details**
   - Destination, weather, and passenger type.
3. **Coupon Types**
   - Restaurant (<$20), Restaurant ($20-$50), Coffee House, Carry out & Takeaway, and Bar.
4. **Expiration Times**
   - Short-term vs. long-term validity.

## Observations

1. **Demographics**: Younger passengers are more likely to accept coupons.

2. **Marital Status**: Married passengers tend to accept coupons at higher rates.

3.  **Coupon Type**: Coupons for coffee houses have the highest acceptance rates.

4. **Passenger Context**: Passengers traveling with family are less likely to accept coupons.


