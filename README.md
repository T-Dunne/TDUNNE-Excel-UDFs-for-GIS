# SELATT

Excel functions for creating SQL queries from a range of values in Excel.

This is useful in GIS for taking a range of feature IDs or names (or anything) and generating an SQL query for use in Select By Attributes or definition queries.

E.g. If you have a column (col A) of ID numbers which you want to select in GIS you would write '=SELATT(A2:A4, "ID")' which would result in ' ID = '1' OR ID = '2' OR ID = '3' '.
If you need the values formatted as numbers then add TRUE to the function, '=SELATT(A2:A4, "ID", TRUE)' which results in ' ID = 1 OR ID = 2 OR ID = 3 '.

Functions other than SELATT produce variants of the above.
