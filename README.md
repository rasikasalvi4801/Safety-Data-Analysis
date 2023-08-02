## Safety-Data-Analysis
Analysis and Dashboard presenting the injury data over three years.

# Problem Statement: 
1. Define proper metrics
2. Create a dashboard for the safety data analysing the accidents and the relative costs.
3. Propose Insights

# Dataset: 
The dataset used for this task was presented by https://www.contextures.com/xlsampledata01.html

#Data Cleaning/Preparation:
1. The Safety dataset which has 13 columns and 514 rows of observation
2. Formatted the date column and extracted the year from it.

# Questions to be answered: 
1. What was the Year Wise Injury Percentage and which year reported the highest percentage of injuries?									
2. How many injuries were reported per age group every year?									
3. What was the average incident cost of males and females for all three years?									
4. What was the average incident cost per report type?									
5. How many injuries were reported by every department in three years?									
6. What is the number of injuries and average incident cost of each plant?									

# Dashboard and Visualizations:

![screencapture-file-C-Users-ADMIN-Documents-SafetyData-pdf-2023-08-02-16_21_10](https://github.com/rasikasalvi4801/Safety-Data-Analysis/assets/72073065/0c3142d3-a6d8-4f4d-8e54-2cb8de700bac)

# Insights:
1. As we can see from the dashboard, filters have been applied using the gender, shift and injury location.
2. 2020 had the highest percentage of injury consisting of 43% followed by 2021 with 39% and then by 2022 with only 18%. But the data consists of only half-year data of 2022(till June) so the percentage of 2022 can increase more till the year-end.
3. The 18-24 age group has 107 employees who are injured in these three years whereas 25-34 has 153 employees. The 35-49 age group has 139 employees and there are 119 employees who are injured in the 50+ age group.
4. 2020 had the highest number of injured employees from the 35-49 age group whereas 2021 had the 25-34 age group as the maximum number of injured employees. The 2022 year has incomplete data so cannot say which age is maximumly injured.
5. The total incident cost was $7,17,795 and the average incident cost for males was $1410 and for females, it was around $1200.
6. The average incident cost for medical claims and lost time was the maximum with $2683 and $2613 respectively.
7. In all three years, the shipping department had the maximum number of injuries followed by administration and maintenance.
8. The Montana plant had the max injuries but we can see that the maximum average injury cost is for the Florida plant.
9. Also from the dataset it is evident that day and night injuries were maximum with 179 and 177 whereas maybe due to lunchtime and slowing down day the afternoon injuries were comparatively less with the number being 161.

# Recommendations:
1. we can analyse why the injuries were so high in 2020 and then what measures were taken in 2021 to bring down that rate. So on the basis of that, we can bring down the rate even more.
2. As we can see the 50+ and 35-49 age group is mostly injured we should take certain precautions because this is a vulnerable age group and any injury can be fatal.
3. Shipping department should be analysed as to why many injuries are happening there. Is it because of some machinery which is broken or because of some tools?
4. Also Montana plant needs to check the machinery or equipment as most injuries were from that plant. Lowa plant can improve safety more as it has the least number of injuries.
5. The Montana plant even though had a high number of injuries had less incident cost. Therefore there might be a possibility that most of them are near misses or just first aid. But the Florida plant had high incident costs which indicates that majorly medical claims and time lost happened here which is not good. Hence the Florida plant has to be evaluated frequently.
6. Also suitable safety wear should be given to employees in respective plants for protecting their body parts. For eg. Lowa and Illinois plants had the most number of abdomen injuries which should be analysed and the employees should be given appropriate safety wear. 
