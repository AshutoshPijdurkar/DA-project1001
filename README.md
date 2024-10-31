Road Accident Study (India, 2003–2016)
Project Background
India recorded the highest number of casualties on roads in the world. In 2016, India accounted for one-third of the global causalities in road accidents. However, the WHO estimates the number of road accident death in India to be much higher than the reported number at about double the number.
This project examines road accident data for the period 2003 to 2016 with the use of Python along with different data visualization and statistical techniques. The analysis has been made on the basis of different factors, including state-wise statistics, gender, time of occurrence, types of vehicles, lane configurations, and reasons for accidents

Project Objectives
The key objectives of this analysis are
To acquire insights into road accidents in India over a period of 13 years
Identify the trend of having states with the highest and lowest accident rates
Analyze accident causes, types of vehicles involved, lane structures, and safety accessory usage
Present the findings using graphs and statistical metrics for easy interpretation

Sources of data

The data files used for this analysis come from Indian government and WHO reports Below is the list of datasets used in this analysis
roadAccStats13-16.csv – Accidents per lakh population (State-Year-wise)
Details_of_road_accident_deaths_by_situation_state_2014.csv – Offender and victim deaths by gender and state
Persons_killed_due_to_Non-use_of_Safety_Device_2016.csv – Deaths due to non-use of safety accessories
datafile.xls – Total number of accidents from 2003 to 2016 per state
laneAccidents.csv – Accidents, injuries, and deaths by lane type (1, 2, 3, 4 lanes)
reasonOfAccident.csv – Accidents, injuries, and deaths by various reasons
typeOfVehicle.csv – Accidents and deaths by vehicle type.
timeOfOccurence.csv – Time of accident occurrence in Day/Night for both 2014 and 2016.

Python Libraries Used

The following Python libraries were used to do the analysis:
pandas: For data manipulation and cleaning.
numpy: For numerical operations.
matplotlib: For visualizing the data.
seaborn: For advanced data visualization.
xlsxwriter: To handle Excel file operations.

Project Workflow
Data Loading

Step 1 involved uploading the various CSV and Excel files into the Python environment. We used the pandas library to upload and analyze the datasets. A few of the datasets had to be cleaned for null values or inconsistencies.
Data Cleaning & Preprocessing
Dropped missing or irrelevant column
Ensured consistent naming conventions for state and year columns across datasets
Converted categorical variables into numeric where necessary (e.g., gender: Male=1, Female=2
Created new c alculated columns (e.g., accidents per lakh population

3. Exploratory Data Analysics
We have explored each dataset individually to understand the trends and patterns in road accidents.
Key Metrics and Insight
The percentage of road accidents and changes year over year
Mean accidents per lakh population for each year
States with most and least accident records
Gender split of offender and victim
Use of safety gears (helmet/seatbelt) in fatal accident
Number of accidents by road type and vehicle type
Accident break-up based on cause like error on part of driver, defect in vehicle, or bad road conditions.
4. Data Visualization
We used several graphs to make the data more legible, such as
Line graphs: For representing trends over time of accidents per state and year.
Bar graphs: For comparison of accident rates among different states, gender, and type of vehicles.
Pie graphs: To illustrate the distribution of day versus night accidents.
Stacked bar graphs: To visualize multi-dimensional data such as accidents by lane type and population.
5. Statistical Analysis
We have done the calculations in order to answer the t he key questions asked in the project:
Accident Percentage for every year.
Average accidents per lakh population.
Death numbers on account of no safety accessory
Lane types and accident causes
6. Findings & Analysis
Key findings from the study were:
Tamil Nadu and Uttar Pradesh registered the maximum accident percentage years after years
Offender and victim death percentage are relatively more for males

A large percentage of deaths occurred due to the failure to use safety devices, especially helmets and seatbelts
Single-lane roads were more fatal than the multi-lane roads
Driver errors, vehicle breakdowns, and road degradation were the most important contributors to accidents.

Overall Summary of Results

The Following Questions are Answered:
Percentage of road crashes in all the years: Time-series analysis of yearly percent change
Mean road accident per 1 lac population: A statistical calculation for average number of accidents yearly.
Highest and smallest numbers of accident states :States with the highest and least accident rates
The persons killed as offenders, according to gender: Separated data of gender.
Persons killed due to absence of helmet: Percentage and also divided into male or female victims.
Number of accidents per state 2003-2016: Time-series analysis
Number of accidents by number of lanes per lakh population Analysis of accidents for lane. 8-13. Accidents, injuries, fatalities for lane layouts: In depth analysis of severities of accidents. 14-26. Cause of accidents, weather, vehicle type: Visualization of cause factors along with statistical decompositions
Day vs Night accidents in 2014 and 2016: Comparison of accident counts by time of day
Project Organization
/data: raw data used in the analysis
/scripts: python scripts to load, clean, analyze, and visualize the data
/notebooks: Jupyter notebooks recording step-by-step process of the analysis
/visualizations: Graphs and charts generated in the course of the analysis
README.md: This document, summarizing and explaining in detail the project

Conclusion
This analysis provides a comprehensive look into road accidents in India from 2003 to 2016. With statistical techniques and visual presentations, we were able to gain insights on the influencing factors of road accidents and fatalities. This could be a basis upon which policymakers and researchers are trying to better road safety and reduce the numbers of people who will die in the future.
