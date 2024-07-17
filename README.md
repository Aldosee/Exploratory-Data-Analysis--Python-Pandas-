# Ultra Marathon Analysis

## Project Overview

This project analyzes data from ultra marathon races to uncover insights into participants' characteristics, such as race length preferences, average speeds, and the relationship between age, gender, and performance. The analysis involves data cleansing, data manipulation, and various data analysis techniques to provide meaningful visualizations and insights

## Table of Contents
 - Project Overview
 - Dataset 
 - [Python Script](analysis.ipynb)
 - Data Cleansing
 - Data Manipulation
 - Data Analysis and Visualizations
    - Race Length Participation
    - Gender Distribution
    - Average Speed Distribution
    - Age vs. Speed Analysis
    - Gender and Speed Analysis
 - Tools Used


 ## Dataset
 - Source: [Dataset Source]
 - [Description: Briefly describe the dataset, including the key features and the data collection process.] 


 ## Data Cleansing
Data cleansing is a crucial step in preparing the dataset for analysis. In this project I performed the following data cleansing tasks:

 - Removing duplicates
 - Handling missing values
 - Correcting data types
 - Filtering outliers

 ## Data Manipulation
Data manipulation involves transforming the raw data into a format suitable for analysis. Key data manipulation steps in this project included:

 - Aggregating data based on race lengths and genders
 - Calculating average speeds and other statistics
 - Creating new features to enhance the analysis

## Analysis and Visualizations

### Race Length Participation
![Race_length](assets\Race_Length.png)


Description: 
 - The bar chart illustrates the count of participants in ultra marathon races of two different lengths: 50 kilometers (km) and 50 miles (mi).
 - The bar for the 50km races is significantly taller indicating a much higher number of participants approximately 20,000 and 50mi races is shorter indicating fewer participants around 5,000. 
 - This suggests that more runners participate in 50km ultra marathon races compared to 50mi races possibly due to the shorter distance being more accessible or less intimidating for runners.

### Gender Distribution
![Gender](assets\Gender.png)
   
Description: 
 - 50km Races: The total number of participants is around 14,000. A majority of the participants are male (M), represented by the blue portion of the bar with roughly 8,000 participants. The remaining participants are female (F), represented by the gray portion with around 6,000 participants.

 - 50mi Races: The total number of participants is around 4,000. Again, the majority of participants are male with roughly 3,000 participants. Female participants are fewer with around 1,000 participants.

 - In both race lengths, male participants outnumber female participants. However, the overall trend of higher participation in 50km races compared to 50mi races is consistent across both genders. The 50km races attract more runners both male and female compared to the longer 50mi races.

### Average Speed Distribution
![Speed](assets\Speed.png)
   
Description: 
  - The histogram shows the distribution of athletes' average speeds in ultra marathon races with most athletes having an average speed between 5 and 8 units peaking around 6-7 units and fewer athletes achieving speeds outside this range.

### Age vs. Speed Analysis
![Gender&Speed](assets\Gender_and_Speed.png)
    
Description: 
 - The violin plot compares the distribution of average   speeds between male and female athletes in 50km and 50mi ultra marathon races. Both race lengths show that male (blue) and female (orange) athletes have similar median speeds with males having a slightly wider distribution of speeds. The plots also reveal that the distribution of speeds for both genders is more spread out in the 50km races compared to the 50mi races suggesting more variability in speeds for the shorter distance race.

### Gender and Speed Analysis
![Age_vs_speed](assets\Age_vs_speed.png)
    
Description: 
 - The scatter plot depicts the relationship between athletes' ages and their average speeds in ultra marathon races with data points colored by gender (blue for males and orange for females). Both genders show a slight negative correlation between age and average speed indicating that as age increases the average speed tends to decrease. The plot also shows that while male runners are generally spread across a wider range of speeds while female runners tend to have a more concentrated distribution of average speeds.

## Tools Used
This project utilized the following tools and libraries:

 - Python: Programming language used for data analysis
 - Pandas: For data manipulation and analysis
 - NumPy: For numerical operations
 - Matplotlib: For creating static visualizations
 - Seaborn: For statistical data visualization
 - Jupyter Notebook: For interactive coding and visualization

