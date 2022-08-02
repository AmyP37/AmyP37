# Data_Journalism_Final_Project
This repository documents my analysis of the China College Entrance Examination Admission rate on birth year, college entrance examination year.

## Analysis 1: Which year has the most new born population?
__Data Analysis Process :__<br>
1. Created a pivot table for Birth year, Newborn Population.<br>
2. Calculated the sum of Newborn Population for each Birth Year. (using “Add Values” option).<br>
3. Make the order of the data decending, but make sure you are sorting the sum of values but not the birth year.<br>
<br/>
<img width="796" alt="截屏2022-07-31 下午5 58 02" src="https://user-images.githubusercontent.com/109766640/182053566-bf95f561-a7ab-41f3-802a-c5305abb75ad.png">



## Analysis 2 : What is the growth rate of the amount of people in the college entrance examnation year compared to the newborn population? Which college entrance year has the least growth?
__Data Analysis Process :__<br>
1. From the datasets, selected the the amount of people in the college entrance examnation year and the newborn population.
2. Created a new column and name it Participants_growth_rate. Then bring in the formula (number of participants minus the number of new students) divided by the number of new students in the first cell
3. Created a new pivot table and selected college examnation year into row and participants growth rate into value, and make the order descending.
<img width="769" alt="截屏2022-08-01 下午1 25 02" src="https://user-images.githubusercontent.com/109766640/182240841-2e401d3c-45ab-41b2-860c-7e8ab2d128b6.png">
<img width="1171" alt="截屏2022-08-01 下午1 55 45" src="https://user-images.githubusercontent.com/109766640/182245126-3366fb1b-eed8-4829-945d-94bb5db69996.png">



## Analysis 3 : What is the GDP growth rate compares to the participant's birth year and their examnation year.
__Data Analysis Process :__<br>
1. Create a new column and named it GDP_difference.
2. Use the GDP in college entrance examination year minus the GDP in participant's birth year.
3. create a pivot table and select the Birth Year and the College Entrance Year, make the order in descending, and it should come out the answer that between 2020 to 2002 has the most GDP difference.
<img width="1171" alt="截屏2022-08-01 下午4 28 13" src="https://user-images.githubusercontent.com/109766640/182261827-3258300c-c93b-474c-bd49-3f21223ba1b4.png">



## Analysis 4 : Which College Entrance Examnation year has the University admission expansion policy applied?
__Data Analysis Process :__<br>
1. Keep using the same pivot table that was created from the last analysis, but change the row to University admission expansion policy and College entrance examination year
2. Put University admission expansion policy to the filter function in pivot table
3. Selecting 1 as the only option in the filter function allows us to arrive at the year in which the university expansion policy was obtained
<img width="1173" alt="截屏2022-08-01 下午7 05 27" src="https://user-images.githubusercontent.com/109766640/182276171-7bbedb48-67e0-4028-9153-372b73baf94b.png">



## Analysis 5 : Which three birth year has the hight gross enrollment rate?
__Data Analysis Process :__<br>
1. Use the same paviot table from before.
2. drag birth year into row, then drag the gross enrollment rate into value.
3. make the order descending in the row, but make sure selected the gross enrollemnt rate before you do so.
<img width="1170" alt="截屏2022-08-01 下午7 31 19" src="https://user-images.githubusercontent.com/109766640/182279002-820c0ddd-1376-4afc-af22-3044c0f9d72f.png">



# Story Pitch : 
### _In the early days of China, the per capita gdp was not very high, which also directly affected the recruitment and acceptance rate of Chinese universities. Until the 1990s, the number of new students in China was much higher than the number of participants. After 2000, although the number of participants in the college entrance exams has slowly rebounded, the growth rate of participants still appears to be negative in the data. But does GDP play a role in the number of admissions? Does China's urban planning and development after the reform and opening up also affect the enrollment rate? And does China's family planning program also affect GDP and indirectly or directly affect enrollment rates?_<br/>
<br/>
