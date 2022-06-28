# Dataset
The dataset describes different driving scenarios, including the destination, current time, weather, passenger, etc., and then asks people whether they will accept the coupon if they are the driver. Answers given that the users will drive there “right away” or “later before the coupon expires” are labeled as “Y = 1”, and answers “no, I do not want the coupon” are labeled as “Y = 0”. There are five different types of coupons—less expensive restaurants (under $20), coffee houses, carry out and take away, bars, and more expensive restaurants ($20–$50).

# Report and Findings
1- The dataset is quit big, rich with information, and indicates which drivers accepted a coupon and which have not accepted the coupons.
All data columns exists except the following columns which have missing or NaN values (the count of rows with such missing data is given below)

-------------------------------
Bar                       107

RestaurantLessThan20      130

CarryAway                 151

Restaurant20To50          189

CoffeeHouse               217

car                       12576

----------------------------

2- For any missing data, we willed it up with the string "-1"

3- We found that about 56.84% of all drivers accepted the coupon given to them.

4- The coupon "Coffee House" is the highest accepted coupon while the coupon "Restaurant (20-50)" is the least accepted.

5- With the temperature as a factor, coupons are accepted the most when the temperature is 80 degrees

6- When the coupon is "Bar", driver accepted it with acceptance rate of 41%

7- Acceptance rate of a coupon is 81.31% among those drivers who went to a bar 3 or fewer times a month

8- Acceptance rate of a coupon is 69.52% among those drivers who go to a bar more than once a month and are over the age of 25. this is a different acceptance rate than pervious item.

9- Acceptance rate of a coupon is 71.32% among those drivers who go to bars more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry. This almost the same acceptance rate as previous item

10- Acceptance rate of a coupon is 68.73% among those drivers who:
- go to bars more than once a month, had passengers that were not a kid, and were not widowed OR
- go to bars more than once a month and are under the age of 30 OR
- go to cheap restaurants more than 4 times a month and income is less than 50K.

11- To hypothesize about bar coupons, those drivers who went to bar 3 or fewer times a month have higher acceptance rate of the coupon than others (compare Item 7 to Item 8,9,10 above)

12- Highest acceptance rate of a coupon is when the weather is Sunny (5989 drivers accepted the coupon when the weather is Sunny) while lowest acceptance rate (62 drivers only) for those whose Marital status is Widowed.

13- Drivers with income of $37499 have the highest acceptance rate of a coupon (1194 drivers accepted it) while those with income of $87499 have the lowest acceptance rate (only 414 drivers accepted it)

# Recommendation
1- Distribute coupons to low-income people as those tends to accept it

2- Distribute coupons in  Sunny day , as drivers tends to use it on this weather
