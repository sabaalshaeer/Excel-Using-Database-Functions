# Excel-Using-Database-Functions
Calculate the total and average sales in the Northeast and Southeast where sales were less than $10,000.
    Select the Quarter 2 Sales worksheet.
    Verify that cell J2 is selected and type =DSUM(
    From the Formula Bar, select Insert Function.
    In the Function Arguments dialog box, in the Database text box, select Formulas→Use in Formula→Q2Sales.
    Press Tab, and in the Field text box, select or type H4 and press Tab.
    Note: Remember that the field is the column of data you wish to summarize. In the data file, you can also total any region.
    In the Criteria text box, select or type A1:H2 and select OK.
    Note: Advanced queries and database functions set up the criteria area in the same manner. The criteria area comprises at least three rows above the list with the headings from the list copied into row one. The following rows are used for the comparison criteria. Be sure to leave a blank row between the criteria area and the list.
    Verify that total sales for the Northeast and Southeast regions, only tallying days where the day's sales were less than $10,000, is $257,470.
    Select cell K2 and enter =DAVERAGE(Q2Sales,H4,A1:H2)
    Verify that the average total sales for the Northeast and Southeast regions, only tallying days where the day's sales were less than $10,000, is $64,368.

Edit the criteria to calculate the total and average sales for May.
    Select cells C2:D2 and press Delete.
    Select cell B2 and enter May
    If necessary, adjust the width of column J and verify the total and average sales for May.

