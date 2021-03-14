# stock-analysis

Testing 

1. Overview of Project: Explain the purpose of this analysis.
### Analysis Overview
    In this analysis we are refactoring a workbook we have previously created for Steve. This new version of the report we will include a more robust dataset to include the entire stock market for the last couple of years. 

    The purpose of this project is to provide Steve a comprehensive report that allows him to see the performance of the entire                     stock market by year, so he can make better recommendation to his parents on where to invest their money. 


2. Results: Using images and examples of your code, compare the stock performance between 2017 and 2018, as well as the execution times of the original script and the refactored script.

## Stock Analysis
Afer running the analysis for both years we can immediately identify that 2017 had much better returns than 2018. In contrast to 2017, where all tickers had a positive return with the exception of one ticker (TERP), 2018 mostly had negative returns with the exception of *ENPH (+81.9%) and *RUN (+84.0%). 

In Steve's parents case, we can see that the DQ stock had a high positive return of +199.4% in 2017, but in 2018 we see a significant drop to -62.6%. 

## Refactoring Analyis
The first siginicant difference between the original and refactored script is the output of the data. 

In the original script, we decided to output the *ticker, totalVolume, and Return* variables after each ticker *for loop*. On the refactored script, we utilize *Arrays* to store the *ticker, *totalVolume, and Return* data to be called later via a final *for loop script.  

This refaction allowed us to improve times on the *2017* and *2018* analysis and make our report more efficient. For example: 

    ### Original Script - The analaysis for the years 2017 and 2018 took 1.71875 seconds to run on each.
    ### Refactored Script - The same analysis for years *2017* and *2018*





4. Summary: In a summary statement, address the following questions.
        3.1 What are the advantages or disadvantages of refactoring code?
        3.2 How do these pros and cons apply to refactoring the original VBA script?
