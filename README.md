# swiggy_revenue_using_Google_Sheets
We have Raw_data of swiggy orders.
Now lets do some transformations:
1.how many unique iteams where sold?
=unique(range, [by_column], [exactly_once])
2. count the unique value?
=countunique( select coloumn)
3. create new row day of week.
=weekday( select column)
1=Sunday
2=Monday
7=Saturday

By using column we can find which day of week has more sales.
4. give a dropdown where if we select the city it gives total revenue?
1st take the uniques values so that we can create the dropdown.
Go to day=ta and data validation cick on Add rule and dropdown from range and now select the unique city coloumn.

Now we can use 
=sumif(range, criteria, [sum_range])
Range we can provide unique cities and in criteria  select the dropdown menu finally in sum_range select the price column.
5. now lets create pivot  table and do dat visuvalisation.


