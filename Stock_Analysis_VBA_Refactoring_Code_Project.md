# An Analysis of Stock Data and Refactoring  VBA Code 

## Overview of Project
Steve, I'm pleased you have found the information I provided so far to be helpful. Now that you want to include the entire stock maket for 2017 and 2018 I beleive it will be important to 'refactor' the code to make it more efficient, user-friendly, take up less space on your harddrive and provide the data you need more quickly should you decide to add stocks for your parents to consider in the future. Afterall, we are talking about a large dataset that you want to analyize for your parent's decision.  I have completed my analysis and will provide details of my findings in the information below. I believe the time I have put in to organize, sort and anaylize the data has led to the discovery of stocks that will help make your parent's decision visually understandable and overall a profitable endeavor.
## Purpose
Just to recap, the purpose of this project is to provide you with actionable information from the stock market, years 2017 and 2018, that will be accurate today and flexible to receive future stock updates should want to add to their analysis. I have refactored the original code for an optimized interaction with the data. I believe the refactored code will be a more productive tool when guiding your parents toward stocks that have performed well in 2017 and 2018.
## Results of Stock Performance
### 2017
Let's take a look at the stock performance for 2017 by looking at the "All Stocks 2017" analysis: 
![All Stocks 2017](https://github.com/peteremiller/stock-analysis/blob/master/Resources/All%20Stocks%202017.png)

The 2017 stock analysis shows that the DQ stock performed well and was traded often to support your parent's claims and desires for a profitable investment. DQ was, in fact, the top performer of the selected stocks at 199.4% increase in return on investment. It was also closely followed by "SEDG" as anpther top perfrmer to consider from the 2017 results. 

### 2018
Let's look at the 2018 stock analysis and see if there are some comparisons that can be made:
![All Stocks 2018](https://github.com/peteremiller/stock-analysis/blob/master/Resources/All%20Stocks%202018.png)

The 2018 stock analysis shows a different picture of rhte top performers from 2017. The DQ stock has underperformed producing a -62.60% return on investment for 2018. Likewise, SEDG also posted a underperforming result of -7.75% (-7.8%) for 2018. It was the stock, RUN and ENPH, that provided the only positive return on investment of the analyzed stocks for 2018 with 83.95% and 81.92% respectively. It is also important to note that ENPH was the third best performing stock in 2017 per my analysis of 2017. 

## Results of Timing Performance for Executing the Analysis
### 2017
The time it took to perform the analysis for the 2017 stocks is captured in the pictures below. The first picture is of the original execution time and the second picture illustrates the refactored code performance time:
[2017 DQ Analysis](https://github.com/peteremiller/stock-analysis/blob/master/Resources/2017%20DQ%20Analysis.png)
[VBA_Challenge_2017](https://github.com/peteremiller/stock-analysis/blob/master/Resources/VBA_Challenge_2017.png)

In comparison, the refactored code execution time is better than the original code's execution performance. However, to the human eye the difference is very small in this dataset, but once the dataset is increased in any way the time between the two will continue to become greater. The time of 54020.66 for the original code and 86247.41 for the refactored code are efficient. The use of more sophisticated loops in the refactored code made better use of the resources available for the analysis.

### 2018
The time it took to perform the analysis for the 2018 stocks is captured in the pictures below. The first picture is of the original execution time and the second picture illustrates the refactored code performance time:
[2018 DQ Analysis](https://github.com/peteremiller/stock-analysis/blob/master/Resources/2018%20DQ%20Analysis.png)
[VBA_Challenge_2018](https://github.com/peteremiller/stock-analysis/blob/master/Resources/VBA_Challenge_2018.png)

For this analysis the results are the same as for 2017; the refactored code performed more efficiently than the the original code. The results for 2018 are better, in that, the execution time of the original code (54330.86) is closer to the refactored time (84319.84). It is possible the total volune of daily trades was less than in 2017 and that the total volume of trades for the year was  less as well. A deep dive into the data and additional analysis woulld be mnecessary to prove out my presumptions.


## Summary
1. What are the advantages or disadvantages of refactoring the code?
    A. I believe the advantage of refactoring the code begins with reducing some of the unnecessary lines of code. Creating loops, nested loops and if-Then statements seemed to give the refactored code a more robust performance. The pictures below demonstrate the refactored code is a more concise and effient way of coding.

    [All_Stocks_Analysis_original](https://github.com/peteremiller/stock-analysis/blob/master/Resources/All%20Stocks%20Analysis%20original.png)
    [All_Stocks_refactored](https://github.com/peteremiller/stock-analysis/blob/master/Resources/All%20Stocks%20refactored.png)
    
    By going back and refactoring the code I had another opportunity to visit areas of code that seem cumbersome or take several lines to execute. While some functions require a great deal of code to execute, I spent most of my time deciding what the relationship of the code is to the function being requested. That is, I had to be more intentional about how each function and value related to the line above and below.
    B. A disadvantage to refactoring the code was that the amount of time it took to execute the amalysis was not significant. While the code is more efficient there needs to be a lot of data to make a big time savings difference.  
    
2. How do these pros and cons apply to refactoring the original VBA script?
The original VBA script was taken straight from the guidelines provided. It worked regardless of my input. Yes, I had to make sure and copy it correctly into the macro, but I didn't create the code. Refactoring the code gave me a first-hand experience of trying to improve upon someone else's creation. I didn't create the original code but after watching the class Zoom videos again, googling problem areas, running msgBox and debugging what seemed like almost every line, the code was more efficient in almost every aspect. 

I beleive using the original code would do for most people who are not using huge datasets. The refactored code is more robust to handle larger datasets and a greater varity of stocks. Refactoring the column headings caused the most frustration in that I couldn't get 'Year' to change to 'Ticker' even with the help of a TA. I also encountered several times when rewriting the code I misspelled something that was correct to begin with or changed the varible to another letter in the midst of completing an array. In all, I learned infinitely more about the basics of being attentive to details and taking my time when refactoring someone else's code. 

kickstarter_analysis done

