Will a Customer Accept the Coupon?
Context

Imagine driving through town and a coupon is delivered to your cell phone for a restaraunt near where you are driving. Would you accept that coupon and take a short detour to the restaraunt? Would you accept the coupon but use it on a sunbsequent trip? Would you ignore the coupon entirely? What if the coupon was for a bar instead of a restaraunt? What about a coffee house? Would you accept a bar coupon with a minor passenger in the car? What about if it was just you and your partner in the car? Would weather impact the rate of acceptance? What about the time of day?

Obviously, proximity to the business is a factor on whether the coupon is delivered to the driver or not, but what are the factors that determine whether a driver accepts the coupon once it is delivered to them? How would you determine whether a driver is likely to accept a coupon?

Overview

The goal of this project is to use what you know about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.

Data cleaning has been completed. 
  The column "car" has too many rows of missing data so decide to keep it in the dataset. On the other hand, lower missing row count is in the colimns "Bar" and "RestaurantsLessThan20" so I will be removing na values from the dataset.
  
  Clean data visualization:
  ![download1](https://user-images.githubusercontent.com/16770936/199153990-e55ee48e-9424-48ff-b8af-1d9beb2ae06a.png)

  
  **What proportion of the total observations chose to accept the coupon?**
  
  Answer: 56.81 % of all coupons are accepted
    
  ![download2](https://user-images.githubusercontent.com/16770936/199155154-eb4a482a-5ebc-456a-91eb-5694c4d670d7.png)

  **What proportion of bar coupons were accepted?**
  
  Answer: 40.97 % of all bar coupons are accepted
 
 ![download3](https://user-images.githubusercontent.com/16770936/199155281-4f68b24e-68df-4857-ba9f-907af29e4240.png)

  **Compare the acceptance rate between those who went to a bar 3 or fewer times a month to those who went more.**
  
  Answer: 47.3 % of people that visited bar less than 3 times a month used the coupon while only 23.1 % people that vistis the bar more than 3 times a month is using the coupon
    
  **Compare the acceptance rate between drivers who go to a bar more than once a month and are over the age of 25 to the all others. Is there a difference?**
  
  Answer: 31.2 % of people older than 25 visit bar more than once a month and used the coupon while 62.2 % people that used coupon visited bar less then once per month
    
    
  ![download4](https://user-images.githubusercontent.com/16770936/199155364-97bd65b8-016e-42dd-92db-e50938423114.png)

  **Use the same process to compare the acceptance rate between drivers who go to bars more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry.**
  
  Answer: 28.7 % of people with the ocupation other than farming, fishing or forestry visit bar more than once a month without kids and used the coupon
    
   **Compare the acceptance rates between those drivers who:**
   
   **go to bars more than once a month, had passengers that were not a kid, and were not widowed**
   
   37.7 % of people with the ocupation other than farming, fishing or forestry visit bar more than once a month without kids and used the coupon
   
   **go to bars more than once a month and are under the age of 30**
   
   31.2 % of people older than 25 and visit bar more than once a month used the coupon
   
   **go to cheap restaurants more than 4 times a month and income is less than 50K.**
   
   Given group had, 382 rejected the coupon and 294 accepted for 0.43 % acceptance rate
   
   
   
  
**Conclusion**

**The passengers of the drivers were more likely friends, rather than children, and were classified as unemployed or students.**
