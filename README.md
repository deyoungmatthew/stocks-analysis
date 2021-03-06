# **Stocks Analysis**
## **Overview of the Project**

The purpose of the original project was to use provided stock ticker data, including ticker ID, trading volume, and beginning and ending prices.  We utlized this data to perform an analysys to determine which of the 12 "green energy" stocks were most profitable during these two calendar years.  The data was then provide for to Steve in an effort for him to assist his parents in determining the trends of these stocks for an investment strategy.  The purpose of this project was to refactor the code to make it more efficient.

## **Results**

The [images](https://github.com/deyoungmatthew/stocks-analysis/tree/main/Resources) of the results show the effective decrease in time as a result of refactoring the VBA code.  For example, there was a over a half second improvement in performance between the original code vs. the updated code when analyzing the 2017 data.  See the comparison images below.

**Original Code runtime for 2017 data**

![Original_Code_2017](https://user-images.githubusercontent.com/78942457/110199053-7615e180-7e24-11eb-99c8-801ce96ae4a5.PNG)


**Refactored Code runtime of 2017 data**

![VBA_Challenge_2017](https://user-images.githubusercontent.com/78942457/110198615-d5262700-7e21-11eb-837a-0fdfc09a6545.png)

 The same efficiency was observed when running the 2018 results:

**Original Code runtime for 2018 data**

![Original_Code_2018](https://user-images.githubusercontent.com/78942457/110199058-7b732c00-7e24-11eb-8892-abbb12b9f181.PNG)



**Refactored Code runtime of 2018 data**
![VBA_Challenge_2018](https://user-images.githubusercontent.com/78942457/110198716-79a86900-7e22-11eb-9bc8-b9c68d0e2ed8.png)

**The updated code should provide quicker results without loss of accuracy.**

## **Summary**

The advantages of refactored code cannot be understated.  A half second improvement on analyzing just over 3,000 rows of data is significant when considering that this code could be used for analyzing millions, or even tens of millions of lines of data from the stock market.  This would save a significant amount of time and could potentially avert large, costly investments in data processing equipment.

Refactoring is not without it's disadvantages.  While the code could potentially take less lines of actual code and save significant amounts of time analyzing large data sets, refactoring is more complex and potentially prone to mistakes.  There is a potential of larger investments of time up front to develop the code to make it run more efficiently.

In regards to the refactoring the original code for this particular project, if the client were only ever going to processing the same amount of data, refactoring might not be worth the up front cost of figuring out the coding.  However, if they expected to analyze much larger data sets, the refactoring is more than worth the up front costs of refactoring the original VBA code.
