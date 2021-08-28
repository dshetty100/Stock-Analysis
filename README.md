# Analysis of green-energy stocks dataset

## Overview of the Project
The purpose of this project was to assist Steve in analyzing green-energy stocks for their total daily volume (number of time it was traded) 
and return (performances) for the year 2017 and 2018. The purpose was also to compare the original code, that was written for the above analysis, with 
a refactored code and determine the performance between the two codes.
 
The analysis was performed using the green-energy stock data set which contained a list of ticker symbol and the daily volume for each stock for 2017 and 2018 in a tabulated form.


## Results

- It is observed from the analysis of stocks for the year 2017 that:
  1. All stocks reported a postive return, except for the the "TERP" stock, which had a negative return of -7.2%.
  2. The stock that showed the highest return was "DQ", and it had the lowest total daily volume among all stocks.

-It is observed from the analysis of stocks for the year 2018 that:
  1. Most stocks (including "DQ") had negative returns, except for the stocks "ENPH" and "RUN" which report a postive return of 81.9% and 84%, respectively. Both stocks also had the highest total daily volume. 
  2. The stock "DQ" was the poorest perfoming stock and had a return of -62.6%.
   
- It was also observed that the original code that was written to analyze the stock data took 0.719s  and 0.391 s to run for the year 2017 and 2018, respectively.

- The refactored code took less time to run the same analysis. The refactored code can be found here, github.com/dshetty100/Stock-Analysis 
  1. It took 0.391 s to run the refactored code for the year 2017. A screen shot of the performance result is as shown below.
  ![Figure 1](/resources/VBA_Challenge_2017.png)

  2. It took 0.101 s to run the refactored code for the year 2018. A screen shot of the performance result is as shown below.
  ![Figure 1](/resources/VBA_Challenge_2018.png)


## Summary
### The advantage of refactoring a code are several, such as, it helps find bugs in the code, makes program run faster and efficiently, easy to read, and enhance 
and maintain in the future. The disadvantage is that it does not add any new functionality, takes additional time, and could introduce new bugs into the program.

### In this analysis, using the refactored code allowed Steve to automate the analysis and reuse it with any stocks thereby reducing the chance of error.
It also decreased the time to run the analysis, since it needed to be done repeatedly. The disadvantage was that it took additional time to do the refactoring. The refactored code need to be debugged as well. 
