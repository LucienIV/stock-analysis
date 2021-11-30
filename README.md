# stock-analysis
# Analysis of Green Energy Stocks

## Overview of Project

The purpose of this project is to analyze the return on various green energy stocks to determine the best investment opportunities for interested parties.

## Results

The results for the designated stocks in 2017 and 2018 are as follows:

![image](https://user-images.githubusercontent.com/92831138/144082822-0ec903f9-3bde-4e11-9381-2c34ed75c635.png)
![image](https://user-images.githubusercontent.com/92831138/144082909-978f79d6-d725-4d63-9d83-1fc28aaf1f13.png)

All stocks other than TERP showed a positive return in 2017 but this trend did not hold true in 2018. In 2018 the only stocks to continue to show a positive return were ENPH and RUN. Based on this data it is difficult to recommend buying stock in any researched stock other than the two which continued to show a positive return for both analyzed years.

The runtimes for the original script for each year are as follows:

![Original Code Runtime 2017](https://user-images.githubusercontent.com/92831138/144084059-b2d7792e-27c6-480d-8c9d-08d9b0876e48.PNG)
![Original Code Runtime 2018](https://user-images.githubusercontent.com/92831138/144084081-979fabe9-7b41-45df-9e61-f50a0599b817.PNG)

Likewise, the following are the runtimes for the refactored script:

![VBA_Challenge_2017](https://user-images.githubusercontent.com/92831138/144084187-2b01fa6a-f162-479f-a647-58c5857043dc.PNG)
![VBA_Challenge_2018](https://user-images.githubusercontent.com/92831138/144084201-e329f2f8-11d3-46f9-8c02-1df513c8e9b7.PNG)

As one can see, the refactored scripts run at least four times faster than the original scripts. In the case of running for 2018 the scripts run roughly eight times faster.

## Summary

Refactoring a scripts has both advantages and disadvantages. A clear advantage demonstrated by the results of this project is that the refactored scripts can run in a fraction of the time of the original scripts. Refactoring also removes some unneccesary elements from a script like redundant loops. Streamlining a script through refactoring can also make it easier to read for those who look at the script other than the original writer.

A disadvantage to refactoring that is not obvious at first blush is that one must know what they are trying to alter as well as how to streamline it. It is easy to say you want for a script to run more efficiently, but one must understand the initial script well enough to know where to trim the fat and what to move where. Depending on how often a script needs to be run and how much time can be saved by refactoring, it is entirely possible to spend way more time refactoring a script than you would save through the refactored script itself. 

At the end of the day refactoring can be incredibly beneficial if one has a clear plan in mind and understands their script. However, if this process becomes too complex or involved due to unfamiliarity or other factors it can become a timesink. For example, the author personally had difficulty with one aspect of this refactoring and took quite a while as well as assistance from a professor to identify and correct the issue. 
