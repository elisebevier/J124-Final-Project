# J124-Final-Project: Childhood Poverty and Food Assistance in U.S. States
## By Elise Bevier 
### Data Analysis Process
* Down Load datasets from [Kaggle](https://www.kaggle.com/datasets/jpmiller/publicassistance)  
*The following are questions answered though my data analysis process.*
**Question 1:** Which state has the highest percentage of Children living below the poverty line?

**Step by Step Answer**
1. First Compile data on poverty estimate from [Kaggle](https://www.kaggle.com/datasets/jpmiller/publicassistance) and Data from [Data Center- Kids Count](https://datacenter.kidscount.org/data/tables/101-child-population-by-age-group#detailed/2/2-53/false/870,573,869,36,868/4693/419 ) into the same sheet. I simply copy and pasted the colums into the same google sheet.
<img width="1406" alt="Screen Shot 2022-08-08 at 9 55 36 PM" src="https://user-images.githubusercontent.com/109987594/183568370-71eea47b-6921-426c-88c6-dba92febb8d9.png">
2. using the multiply funtion get the percentage of children living below the poverty line 
<img width="1383" alt="Screen Shot 2022-08-08 at 9 55 52 PM" src="https://user-images.githubusercontent.com/109987594/183568568-cce18602-de44-4241-a37a-0237ba586a69.png">
3. Create Pivot table using the percentage colums as values and sort the values in descending order.
[Find that Mississippi has the highest poverty level]<img width="1415" alt="Screen Shot 2022-08-08 at 10 06 31 PM" src="https://user-images.githubusercontent.com/109987594/183569286-54d00935-eb32-48e4-a1ed-72790ded50d8.png">

**Question 2:** In the whole United states what percentage of children living below the poverty line participate in food assistance programs?

**Step by Step Answer**
1. Using the Vlookup funtion create a sheet that combine the average participation from each year and the number of children living below the poverty line in each state.
<img width="450" alt="Screen Shot 2022-08-08 at 11 02 55 PM" src="https://user-images.githubusercontent.com/109987594/183576187-e514614d-3778-47fb-8c7d-98bdebe7d656.png">
2. Using the sum funtction total the avage participation for each year and the poverty estimate for people under the age of 18. 
<img width="104" alt="Screen Shot 2022-08-08 at 11 08 44 PM" src="https://user-images.githubusercontent.com/109987594/183577062-3da3f4b7-d507-4928-b335-8b291e9bea2a.png">
<img width="111" alt="Screen Shot 2022-08-08 at 11 05 02 PM" src="https://user-images.githubusercontent.com/109987594/183576707-4f6392f8-ff71-4e26-90fd-a3fadc7f583a.png">
Then using those cells, use the multiply funtion to find the percentage
<img width="196" alt="Screen Shot 2022-08-08 at 11 08 55 PM" src="https://user-images.githubusercontent.com/109987594/183576986-60b87267-af09-43e1-9d2a-5259720934a5.png">

Which is 46.7%<img width="122" alt="Screen Shot 2022-08-08 at 11 10 36 PM" src="https://user-images.githubusercontent.com/109987594/183577293-5fd50911-a729-4864-88c3-c465eab930b7.png">

**Question 3:** Which State has the highest cumulative food cost?

**Step by Step Answer**
1. Create a spreadsheet using data from Kaggle about the cumulative food cost for each state
<img width="740" alt="Screen Shot 2022-08-08 at 11 29 26 PM" src="https://user-images.githubusercontent.com/109987594/183580072-2c6577e1-0753-4ba1-9490-f3aa6e802c9c.png">
2. Create a pivot table using the state as the rows and the food costs as the values and sort values in descending order. 
 
 The state with the highest cumulative food cost is California<img width="887" alt="Screen Shot 2022-08-08 at 11 29 13 PM" src="https://user-images.githubusercontent.com/109987594/183580421-1fd9f04f-ee0f-4a50-84b4-15a41d54018a.png">

**Question 4:** Did food cost increase or decrease in the states with lowest food cumulative food costs from 2013-2016?

**Step By Step Answer**
1. Using that same pivot table from question 3, I sorted the values in ascending order.
2. looking at the bottom ten states for food costs, I found that all saw a decrease in food costs.
<img width="548" alt="Screen Shot 2022-08-08 at 11 58 58 PM" src="https://user-images.githubusercontent.com/109987594/183585049-0c79e7cd-cd5b-4a1f-b87a-04de70ef26ba.png">

**Question 5:** Which state had the highest percentage of children living below the poverty line particiating in food assistance programs?

**Step By Step Answer**
1. using the vlookup funtion, create a sheet that joins together the amount of child participants and the number of children living below the poverty line in each state.
<img width="1346" alt="Screen Shot 2022-08-09 at 12 10 16 AM" src="https://user-images.githubusercontent.com/109987594/183587287-d71c8243-0451-4c84-aaf5-2b4f94fbe025.png">
2. Using the Multiply funtion, find the percentage of for each year.
<img width="450" alt="Screen Shot 2022-08-09 at 12 13 37 AM" src="https://user-images.githubusercontent.com/109987594/183587610-8aa53c56-a187-4853-bad5-10455332ca65.png">
3. Create a pivot table and arrange the values in decsending order 
<img width="450" alt="Screen Shot 2022-08-09 at 12 13 37 AM" src="https://user-images.githubusercontent.com/109987594/183587978-1fd5599f-7318-4ff5-adc8-cbd137fbad28.png">
See that Vermont has the highest percentage. 
