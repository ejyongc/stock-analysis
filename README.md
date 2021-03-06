# stock-analysis

### 1- Analysis Overview
In this analysis we are refactoring a script we have previously created for Steve to help his parents identify opportunities on the stock market. The new version of the script analyzes the same dataset on a more efficient way and it includes the entire stock market for the last couple of years.    

The purpose of this project is to provide Steve a comprehensive report that allows him to see the performance of the entire stock market by year, so he can make better recommendation to his parents on where they should be investing their money. 

### 2- Stock Analysis
Afer running the analysis for both years we can immediately identify that 2017 had much better returns than 2018. In contrast to 2017, where all tickers had a positive return with the exception of one ticker (TERP), 2018 mostly had negative returns with the exception of ENPH (+81.9%) and RUN (+84.0%). 

In Steve's parents case, we can identify that the DQ stock had a high positive return of +199.4% in 2017, but in 2018 we see a significant drop to -62.6%. This analysis could greately serve Steve's parents since now they might want to consider diversifying their portfolio in stocks with better returns. 

### 3- Refactoring Analyis 

#### 3.1- Output Script
The first siginicant difference between both scripts is how we coded the [Original Script Output](https://github.com/ejyongc/stock-analysis/blob/main/Resources/Output%20-%20Original%20Script.png)
and the [Refactored Script Output](https://github.com/ejyongc/stock-analysis/blob/main/Resources/Output%20-%20Refactored%20Script.png)

In the original script, we decided to output the *ticker, totalVolume, and Return* variables after the ticker *for loop*. On the refactored script, we utilize *Arrays* to store the *ticker, *totalVolume, and Return* calculated values, and later we call those variables via a *for loop* script. (screenshots below) 

##### Original script output
![image](https://github.com/ejyongc/stock-analysis/blob/main/Resources/Output%20-%20Original%20Script.png)

##### Refactored script output
![image](https://github.com/ejyongc/stock-analysis/blob/main/Resources/Output%20-%20Refactored%20Script.png)

#### 3.2- Report Efficiency
This refaction allowed us to improve the script run time on the *2017* and *2018* analysis and make our report more efficient. For example: 

##### Original Script 
The analaysis for the years 2017 and 2018 took 1.355469  seconds to run on each.

![image](https://github.com/ejyongc/stock-analysis/blob/main/Resources/2018%20Stock%20Analysis%20-%20Original%20Script.png)

##### Refactored Script
The same analysis for years *2017* and *2018* took 1.71875 to run on each. 

![image](https://github.com/ejyongc/stock-analysis/blob/main/Resources/VBA_Challenge_2018.png)
    
Althought is not a huge difference (0.183594 delta), the refactored script is more efficient and faster than the origial script since it utilizes a different method to display the outputs.

### 4- Summary & Conclussions 
As seen in this excercise, refactoring could be used to make the code more efficient and maintainable. When we refactrored the output of the script we were able to reduce the time that it takes to run the code.  

Although refactoring is a good practice that can make the code easier to understand and debug, the process of refactoring could take a long time and it could actually make the script more complex and confusing. In this specific case we spent several hours refactoring the code and we can see the immediate results in terms of efficiency.  On the long term, I believe the refactored script will be easier to update and modify if ever needed.
