# Stock Analysis with VBA & Excel

## Overview of Project

### Purpose
In this project, I was tasked with editing, or refactoring, the Stock Market dataset with VBA code to loop through all of the data at one time to collect an entire dataset.  Afterwards, I determined whether refactoring the code made the VBA script run quicker.  Finally, I sought to make the code more efficient by consolidating steps, using less memory, and improving the logical arguments of the code to make it more readable for future users to follow.

### Results: Executing Deliverable Requirements
1. Create a variable, tickerIndex, for the ticker index and set it equal to 0 before iterating over all rows.  This variable will be used to access the correct index across the different arrays in the next requirement.
```
For i = 0 To 11
       tickerIndex = tickers(i)
```
2. Create three output arrays: tickerVolumes, tickerStartingPrices, and tickerEndingPrices.  Set the data types to Long for tickerVolumes and Single for the other two.
```
Dim tickerVolumes As Long
Dim tickerStartingPrices As Single, tickerEndingPrices As Single
```
3. Create a for loop to initialize the tickerVolumes to 0. If the next row's ticker doesn't match, increase the tickerIndex.
```
''2a) Create a for loop to initialize the tickerVolumes to zero.
    'If the next row’s ticker doesn’t match, increase the tickerIndex.
       Worksheets(yearValue).Activate
       tickerVolumes = 0

       ''2b) Loop over all the rows in the spreadsheet.
       For j = 2 To RowCount

           ' If the next row’s ticker doesn’t match, increase the tickerIndex.
           If Cells(j, 1).Value = tickerIndex Then
```
## Summary

### What are the advantages and disadvantages of refactoring code?

#### Advantages

#### Disadvantages

#### Original VBA Script
