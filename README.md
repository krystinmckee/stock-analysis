# VBA Stocks Analysis
Module 2 

## Project Overview
The purpose of this project is to analyze the performance of select stocks to help inform investment decisions, as well as to provide Steve with a tool to **effectively** and **efficiently** analyze large sets of stock market data.

## Results
### Stock Performance
While nearly all of the analyzed stocks produced positive returns in the year 2017, the opposite is true for the year 2018.
In 2017, DQ and SEDG had the greatest returns (199.4% and 184.5% respectively), however the returns for both of these stocks were negative in 2018 (-62.6% and -7.8% respectively). 

**Key Takeaway:** Of the 12 stocks included in this analysis, two realized positive returns for both 2017 and 2018. "ENPH" provided the greatest overall return (129.5% in 2017 and 81.9% in 2018), followed by "RUN" (which returned 5.5% in 2017 and 84.0% in 2018). Notably, "RUN" is the only stock with positive returns whose rate of return increased from 2017 to 2018.


![Stock Performance 2017](https://github.com/krystinmckee/stock-analysis/blob/main/Resources/Stock_Performance_2017.png
)
![Stock Performance 2018](https://github.com/krystinmckee/stock-analysis/blob/main/Resources/Stock_Performance_2018.png
)

### Script Execution Time
Prior to refactoring the stock analysis script, the analysis took an average of 1.5 seconds to execute (1.35s when analyzing 2017 data and 1.65s when analyzing 2018 data). After refactoring the script, the execution time decreased by an average of 93%, running in approximately 0.1 seconds for 2017 data as well as for 2018 data. 

![Refactored Analysis Run-time 2017](https://github.com/krystinmckee/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png)
![Refactored Analysis Run-time 2018](https://github.com/krystinmckee/stock-analysis/blob/main/Resources/VBA_Challenge_2018.png)

## Summary
Efficiency is a clear advantage of refactoring code. By thoughtfully refactoring code, execution time can be greatly reduced, which is increasingly important as your datasets grow larger. One disadvantage to refactoring is that it is easy to introduce errors or break code that was previously running if you do not have a clear plan for executing your changes.

These pros and cons were apparent for me during this project. While it was challenging to refactor the code in a way that was both effective and more efficient, it certainly paid off in the end because the code is tremendously faster!

