# vba_challenge

## Overview of Project

Refactor VBA code for Stock analysis extract to identify best performing stock across years.

### Purpose

There are differnt ways to identify the best performing stock across years from the data in vba_challenge.xlsm extract. The purpose of this code is to identify the best performing stock by each year and also show the returns percentage by end of the year.

#### Results

*For Year 2017*

The below screenshot shows the total volume and returns by end of the year 2017 for each ticker. The total time it took after refactor is 0.156 sec compared to .53 seconds prior to code refactoring.
![](Resources/Stocks analysis for year 2017.png)

*For Year 2018*

The below screenshot shows the total volume and returns by end of the year 2018 for each ticker. The total time it took after refactor is 0.1406 sec compared to .49 seconds prior to code refactoring.
![](Resources/Stocks analysis for year 2018.png)

##### **Summary**

By refactoring the code we are able to produce the desire results by reading the data through once. Prior to refactoring we are reading the entire data for each ticker and so obviously consumed more time to generate the results. This will help to run the analysis faster even with more data.
