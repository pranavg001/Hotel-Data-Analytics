# Hotel-Data-Analytics

Understanding the problem:
The problem is to increase the revenue generated.

Data Collection:
We have got the 5 datasets which contains dimension and fact tables.

Data Exploration:
1. Read all the csv files.
2. Explore all the dataframes to understand the data using various methods or properties.

Data Cleaning:
1. We have performed the cleaning to remove the negative values, check for the outliers on revenue generated & revenue realized columns.
2. To remove the outliers ,we used 3 standard deviation method to get the higher limit.
3. Checked for the na values in all columns , if there is any fillna values.

Data Transformation:
1. we have created the column by calculating occupancy percentage,i.e successful bookings/capacity

Insights Generation:
1.Average occupancy rate in each of room categories
2.average occupancy rate per city.
3.When was the occupancy better? Weekday or Weekend?
4.In the month of June, what is the occupancy for different cities
5.we have appended the new data of august using concat function.
5.Revenue realized per city.
6.Print month by month revenue.
7.Pie chart for revenue realized per booking.

These insights are retrieved using merge , groupby functions of pandas.
