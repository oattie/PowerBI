# CALCULATE 

Calculate function, a function which can modify a filter context, is the most powerful function used in most of reports found in Power BI. Mastering calculate function would tremendously
give you benefit and flexibiliy when dealing with complex scenarios.


Before learning about calculate, there is a very important concept we should learn about DAX.
When we refer to a table in a data model, and because DAX use VertiPaq as a memory database, we should think an entity/table as a set of columns,
and not as the whole table. Each column is saparated from each other.

When you have a date slicer in a report, the filter is applied to the date column (not the whole table) but because of the date column is part of the dimdate table for example.
The dimdate table will too have the filter effect. Ultimately, a single filter works on a column at a time.

Multipe filters work together as an equivalent of AND operation and together they are called a filter context.



