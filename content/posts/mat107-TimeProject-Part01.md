---
title: MAT 107 Time Project 
date: 2022-04-09T10:35:40-04:00
tags: Statistics


---



**MAT107 Intro to Statistics Project**

Name<ins>&nbsp;Xianglin Huang&nbsp;</ins>  due by <ins>&nbsp;4/9/2022&nbsp;</ins>.     

***STEP 1: Data Collection***

How many minutes do you sit down and work with dedicated concentration on your homework without interruption? Look at the time when you start. If you stop working to look at a phone message, take a call or a break, stop the time and write it down. If you listen to music while you study, stop the time when you change the music station, find another song or anything other than making progress on your homework. Then start the time again when you get back to your homework, counting it as a separate homework session. 

Write down the number of minutes for each incident until you have 30 data points (including repeat times). For example (in minutes):  Monday 8, 10, 15, 32, Tuesday 2, 12, 45, Wednesday 10, 11, 11, 9, 15, 15, 65 etc. 
```
List 30 Data Values
Monday 13, 46, 67  
Tuesday 86, 54 , 70, 8, 11, 80, 39    
Wednesday 57, 2, 9, 8      
Thursday 9, 24, 13, 30, 27, 42, 17, 34, 41, 10, 22    
Friday 41, 22, 27
Saturday 12   
Sunday 60     
```   


***STEP 2: Organizing Data***

Construct a Grouped Frequency Distribution for the data you collected. Use 5 classes. 
Show work for Class Width Here
```
Highest:86      Lowest:2          
Class Width = (H - L)/number of class = (86 -2)/5 =84/5 =16.8 
set the Class Width as a whole number 17
```

|Class Limits|Class Boundaries| Frequency | Relative Frequency | Cumulative Frequency|
|:---:  |:---:  |:---:  |:---:  |:---:  |
|2 - 18 | 1.5 - 18.5 | 11 | 0.37 | 0.37|
|19 - 35|18.5 - 35.5|7|0.23|0.60|
|36 - 52|35.5 - 52.5|5|0.17|0.77
53 - 69|52.5 - 69.5|4|0.13|0.90
70 - 86|69.5 - 86.5|3|0.10|1.00


***STEP 3: Histogram***

Construct a histogram for your data set. Be sure to label the axes appropriately. Describe your histogram. 
{{< figure src="/images/histogram.png">}}

***STEP 4: More Descriptive Statistics***                   
```
2       8       8      9       9     10    11    12    13    13    
17    22     22    24    27    27    30     34    39    41    
41    42     46    54    57    60    67    70    80     86
```
A. Order your data points in the box above. 

B. Find the mean, median, and mode. Show work below and write final answer in box.

| <div style="width:100px">MEAN</div> |  <div style="width:100px">MEDIAN</div> | <div style="width:100px">MODE</div> | 
| :---: | :---: | :---: | 
| 32.7| 27 | 8, 9, 13, 22, 27, 41 |

<br>
C. Find the 5-number summary, and the IQR for your sample data[^1]. 

| <div style="width:80px">Minimum</div> |  <div style="width:80px">Q1</div> | <div style="width:80px">Q2</div> | <div style="width:80px">Q3</div> | <div style="width:80px">Maximum</div> | <div style="width:80px">IQR</div>|
| :---: | :---: | :---: | :---: | :---: | :---: |
| 2 | 12 | 27 | 46 | 86 | 34 |

<br>
D. Sketch a box plot, including the proper scale for the range of data. 
{{< figure src="/images/boxplot.png">}}

E. Identify extreme values in your data set using the outlier formulas. If you have no outliers, support that
 conclusion mathematically. 
```
IQR = Q3 - Q1 = 46 - 12 = 34;
Lower Outlier = Q1 - 1.5*IQR = 12 - 1.5*34 = - 39;
Upper Outlier = Q3 + 1.5*IQR = 46 + 1.5*34 = 97. 
The value which is lower than -39 or higher than 97 will be the outlier.
While the highest value is 86 and lowest value 2, there is no outlier in my data.
```

F. Write a brief Descriptive Statistical Summary and an Inferential Statistical Summary for your data. 

**Descriptive Statistical Summary:**
  The length of my records of uninterrupted study time varies from 2 minutes to 86 minutes, with an average of 32.7 minutes, a median of 27 minutes.

**Inferential Statistical Summary:**
  On average, I will be interrupted after focusing on studying for 32.7 minutes. 

***STEP 5: Conclusion***

A. State your average and calculate your standard deviation. Show work below. 
```
x = 32.7      S =  23.5
Calculated as :
  ƩX = x1 + x2 + … + x30 = 981
  ƩX2 = x12 + x22 + … + x302 = 48057 
  x  = ƩX / n = 981 / 30 =  32.7
  s2 = ( n*ƩX2 - (ƩX)2 ) / ( n*(n-1) ) = (30 * 48057 - 9812) / (30 * 29) = 479349 / 870 = 550.98
  s = 550.98 = 23.5
```
B. Label a normal curve for your data with mean and 3 standard deviations. 
{{< figure src="/images/normalcurve.png">}}
<center>-37.8&nbsp;&nbsp;&nbsp;&nbsp;-14.3&nbsp;&nbsp;&nbsp; &nbsp;9.2 &nbsp;&nbsp;&nbsp;&nbsp; 32.7&nbsp;&nbsp;&nbsp;&nbsp;56.2&nbsp;&nbsp;&nbsp;&nbsp;79.7&nbsp;&nbsp;&nbsp;&nbsp;103.2</center>
C. According to the Empirical Rule, between which two number of minutes would 95% of your data lie?

`between -14.3 and 79.7`

D. What would be a very unusually high number of minutes you would spend on your homework?

`80 or  86`

E. How many minutes correspond to a z-score of -1 in your data set? 
```
9.2 
z(9.2) = (9.2 -32.7)/23.5 = -1
```

F. Ask a couple of classmates about their mean & standard deviation. Briefly, discuss any comparisons and conclusions you have come to as a result of this project.   (online-only class students can discuss with friends and/or relatives about how often they are distracted from getting work done.) 
<center><strong>Uninterrupted Study Time</strong></center>
{{< figure src="/images/boxplot2.png">}}

*&nbsp;&nbsp;Both my husband and I think that the frequency distribution graph of my number of minutes spent on homework is right-skewed. The median (27 minutes) is less than the mean (32.7 minutes). I think the median is better to represent the tendency of my study time at home. Mostly, I will be interrupted in 27 minutes when I do my homework. Besides, my husband would prefer to work at his office rather than at home, because there are so many distractions in our house, such as the kid, the snacks, and the chores. I agree with him.*
