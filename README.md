# Stock-Analysis with VBA

## Overview of the Project

We are assiting Steve with automating the analysis of stock data in VBA so that he is able to provide guidance to his parents on what stocks to purchase.

## Results

Prior to refactoring the code, the time to execute was 0.125 for 2017 and 0.1015625 in 2018. The 2017 data took a bit longer to run than the 2018 data. 
After refactoring the code, teh VBA script did run a lot faster for both 2017 & 2018. (See Images Below)

![VBA_Challenge_2017](https://github.com/eburneo/Stock-Analysis/blob/main/Resources/VBA_Challenge_2017.png) ![VBA_Challenge_2018](https://github.com/eburneo/Stock-Analysis/blob/main/Resources/VBA_Challenge_2018.png)

![Refactored VBA_Challenge_2017](https://github.com/eburneo/Stock-Analysis/blob/main/Resources/Refactored%20VBA_Challenge_2017.png) ![Refactored VBA_CHallenge_2018](https://github.com/eburneo/Stock-Analysis/blob/main/Resources/Refactored%20VBA_Challenge_2018.png)


## Summary

### What are some advantaes or disadvantages for refactoring code?

Advantages:
- One objective of code refactoring is to make it more efficient. 
- The logic of the code can be improvded and make it easier for future users to read it.
- If you are working with a large data, it will use less memory

Disadvantages:
- If not refactored properly, the funcationality of the code could be changed
- New bugs can be introduced causing the  script not to work properly

How do these pros and cons apply to refactoring the original VBA script?

Refactoring our VBA script improved the run times overall. The code was successfully refctored without changing the output from the original VBA script. The data we worked was not too large, however there was still improvement by removing a loop. When working with larger data sets, refactoring code can significantly improve the spead of the script.

![2017 Stock Data](https://github.com/eburneo/Stock-Analysis/blob/main/Resources/2017%20Stock%20Data.png) ![2018 Stock Data](https://github.com/eburneo/Stock-Analysis/blob/main/Resources/2018%20Stock%20Data.png)

