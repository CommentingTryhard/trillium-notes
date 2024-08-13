# Formulas
### **EXCEL FUNCTIONS - QUESTIONS & SOLUTIONS FOR REVISION**

**TODAY Function**  
_Description:_ Returns the current date.  
What is the current date?  
**Formula:** =TODAY()  
**Solution:** Displays the current date.

* * *

**LEFT Function**  
_Description:_ Extracts a specified number of characters from the left side of a text string.  
Extract the first 3 characters from the string "ExcelFunctions".  
**Formula:** =LEFT("ExcelFunctions", 3)  
**Solution:** "Exc"

Extract the first 4 characters from cell A1 if the length of the text is greater than 5, otherwise, return "Short".  
**Formula:** =IF(LEN(A1)>5, LEFT(A1, 4), "Short")  
**Solution:** Depends on the content of A1.

* * *

**LEN Function**  
_Description:_ Returns the number of characters in a text string.  
Find the length of the string "Excel".  
**Formula:** =LEN("Excel") #you can point to cell address   
**Solution:** 5

Check if the length of the text in cell A1 is even or odd.  
**Formula:** =IF(MOD(LEN(A1), 2)=0, "Even", "Odd")  
**Solution:** Depends on the content of A1.

* * *

**MID Function**  
_Description:_ Returns a specific number of characters from a text string, starting at the position you specify.  
Extract 4 characters from the 2nd position in the string "ExcelFunctions".  
**Formula:** =MID("ExcelFunctions", 2, 4)  
**Solution:** "xcel"

Extract 3 characters starting from the 5th character of the text in cell A1, if A1 contains more than 7 characters.  
**Formula:** =IF(LEN(A1)>7, MID(A1, 5, 3), "Too Short")  
**Solution:** Depends on the content of A1.

* * *

**RIGHT Function**  
_Description:_ Extracts a specified number of characters from the right side of a text string.  
Extract the last 3 characters from the string "ExcelFunctions".  
**Formula:** =RIGHT("ExcelFunctions", 3)  
**Solution:** "ons"

Extract the last 2 characters from cell A1 if the length of the text is greater than 3, otherwise return "Too Short".  
**Formula:** =IF(LEN(A1)>3, RIGHT(A1, 2), "Too Short")  
**Solution:** Depends on the content of A1.

* * *

**AND Function**  
_Description:_ Returns TRUE if all the arguments evaluate to TRUE.  
Check if the values in cells A1 and B1 are both greater than 10.  
**Formula:** =AND(A1>10, B1>10)  
**Solution:** TRUE or FALSE

Check if the value in cell A1 is between 5 and 15, and the value in cell B1 is between 20 and 30.  
**Formula:** =AND(A1>5, A1<15, B1>20, B1<30)  
**Solution:** TRUE or FALSE

* * *

**IF Function**  
_Description:_ Returns one value if a condition you specify evaluates to TRUE, and another value if it evaluates to FALSE.  
Return "Pass" if the value in cell A1 is greater than 50, otherwise return "Fail".  
**Formula:** =IF(A1>50, "Pass", "Fail")  
**Solution:** "Pass" or "Fail"

Return "High" if the value in cell A1 is greater than 80, "Medium" if it is between 50 and 80, and "Low" if it is less than 50.  
**Formula:** =IF(A1>80, "High", IF(A1>=50, "Medium", "Low"))  
**Solution:** "High", "Medium", or "Low"

* * *

**IFS Function**  
_Description:_ Checks whether one or more conditions are met and returns a value that corresponds to the first TRUE condition.  
Return "Excellent" if the value in cell A1 is greater than 90, "Good" if it is greater than 75, "Average" if it is greater than 50, and "Poor" otherwise.  
**Formula:** =IFS(A1>90, "Excellent", A1>75, "Good", A1>50, "Average", TRUE, "Poor")  
**Solution:** "Excellent", "Good", "Average", or "Poor"

* * *

**NOT Function**  
_Description:_ Reverses the logic of its argument.  
Return TRUE if the value in cell A1 is not greater than 10.  
**Formula:** =NOT(A1>10)  
**Solution:** TRUE or FALSE

Check if the value in cell A1 is not between 5 and 15.  
**Formula:** =NOT(AND(A1>5, A1<15))  
**Solution:** TRUE or FALSE

* * *

**OR Function**  
_Description:_ Returns TRUE if any argument evaluates to TRUE.  
Check if the value in cell A1 is greater than 10 or the value in cell B1 is greater than 20.  
**Formula:** =OR(A1>10, B1>20)  
**Solution:** TRUE or FALSE

Check if the value in cell A1 is either less than 5 or greater than 15.  
**Formula:** =OR(A1<5, A1>15)  
**Solution:** TRUE or FALSE

* * *

**HLOOKUP Function**  
_Description:_ Looks for a value in the top row of a table and returns the value in the same column from a row you specify.  
Look up the value 85 in the first row of the range A1

and return the corresponding value from the second row.

**Formula:** =HLOOKUP(85, A1:D2, 2, FALSE)

**Solution:** Depends on the content of A1

* * *

**VLOOKUP Function**  
_Description:_ Looks for a value in the first column of a table and returns the value in the same row from a column you specify.  
Look up the value 123 in the first column of the range A1

and return the corresponding value from the second column.

**Formula:** =VLOOKUP(123, A1:B10, 2, FALSE)

**Solution:** Depends on the content of A1

.

* * *

**CEILING Function**  
_Description:_ Rounds a number up, away from zero, to the nearest multiple of significance.  
Round the value in cell A1 up to the nearest multiple of 5.  
**Formula:** =CEILING(A1, 5)  
**Solution:** Rounded value

* * *

**FLOOR Function**  
_Description:_ Rounds a number down, toward zero, to the nearest multiple of significance.  
Round the value in cell A1 down to the nearest multiple of 5.  
**Formula:** =FLOOR(A1, 5)  
**Solution:** Rounded value

* * *

**MOD Function**  
_Description:_ Returns the remainder after a number is divided by a divisor.  
Find the remainder when the value in cell A1 is divided by 3.  
**Formula:** =MOD(A1, 3)  
**Solution:** Remainder

* * *

**POWER Function**  
_Description:_ Returns the result of a number raised to a power.  
Calculate 2 raised to the power of 3.  
**Formula:** =POWER(2, 3)  
**Solution:** 8

* * *

**QUOTIENT Function**  
_Description:_ Returns the integer portion of a division.  
Find the integer portion of the division of 15 by 2.  
**Formula:** =QUOTIENT(15, 2)  
**Solution:** 7

* * *

**RAND Function**  
_Description:_ Returns a random number between 0 and 1.  
Generate a random number between 0 and 1.  
**Formula:** =RAND()  
**Solution:** Random number between 0 and 1

* * *

**RANDBETWEEN Function**  
_Description:_ Returns a random integer between the numbers you specify.  
Generate a random integer between 1 and 100.  
**Formula:** =RANDBETWEEN(1, 100)  
**Solution:** Random integer between 1 and 100

* * *

**ROUND Function**  
_Description:_ Rounds a number to a specified number of digits.  
Round the value in cell A1 to 2 decimal places.  
**Formula:** =ROUND(A1, 2)  
**Solution:** Rounded value

* * *

**SQRT Function**  
_Description:_ Returns the square root of a number.  
Find the square root of 16.  
**Formula:** =SQRT(16)  
**Solution:** 4

* * *

**SUM Function**  
_Description:_ Adds all the numbers in a range of cells.  
Calculate the sum of the values in cells A1 to A5.  
**Formula:** =SUM(A1:A5)  
**Solution:** Sum of values

* * *

**SUMIF** **Function**  
_Description:_ Adds the cells specified by a given condition or criteria.  
Calculate the sum of the values in cells A1 to A5 that are greater than 10.  
**Formula:** =SUMIF(A1:A5, ">10")  
**Solution:** Sum of values greater than 10

* * *

**AVERAGE Function**  
_Description:_ Returns the average (arithmetic mean) of the arguments.  
Calculate the average of the values in cells A1 to A5.  
**Formula:** =AVERAGE(A1:A5)  
**Solution:** Average of values

* * *

**COUNT Function**  
_Description:_ Counts the number of cells that contain numbers.  
Count the number of numeric values in cells A1 to A5.  
**Formula:** =COUNT(A1:A5)  
**Solution:** Count of numeric values

* * *

**COUNTA Function**  
_Description:_ Counts the number of cells that are not empty.  
Count the number of non-empty cells in the range A1 to A5.  
**Formula:** =COUNTA(A1:A5)  
**Solution:** Count of non-empty cells

* * *

**COUNTBLANK Function**  
_Description:_ Counts the number of empty cells in a specified range of cells.  
Count the number of empty cells in the range A1 to A5.  
**Formula:** =COUNTBLANK(A1:A5)  
**Solution:** Count of empty cells

* * *

**COUNTIF Function**  
_Description:_ Counts the number of cells within a range that meet the given condition.  
Count the number of cells in the range A1 to A5 that contain a value greater than 10.  
**Formula:** =COUNTIF(A1:A5, ">10")  
**Solution:** Count of cells greater than 10

* * *

**LARGE Function**  
_Description:_ Returns the k-th largest value in a data set.  
Find the 2nd largest value in the range A1 to A5.  
**Formula:** =LARGE(A1:A5, 2)  
**Solution:** 2nd largest value

* * *

**MAX Function**  
_Description:_ Returns the largest value in a set of values.  
Find the maximum value in the range A1 to A5.  
**Formula:** =MAX(A1:A5)  
**Solution:** Maximum value

* * *

**MEDIAN Function**  
_Description:_ Returns the median of the given numbers.  
Find the median of the values in cells A1 to A5.  
**Formula:** =MEDIAN(A1:A5)  
**Solution:** Median value

* * *

**MODE Function**  
_Description:_ Returns the most frequently occurring value in a data set.  
Find the most frequent value in the range A1 to A5.  
**Formula:** =MODE(A1:A5)  
**Solution:** Most frequent value

* * *

**SMALL Function**  
_Description:_ Returns the k-th smallest value in a data set.  
Find the 3rd smallest value in the range A1 to A5.  
**Formula:** =SMALL(A1:A5, 3)  
**Solution:** 3rd smallest value

* * *

**Relative and Absolute Referencing**  
_Description:_ Adjusts cell references in formulas based on the location of the formula in the worksheet.  
Multiply the value in cell A1 by the value in cell B1 and drag the formula down.  
**Formula:** =A1\*B1  
**Solution:** Product of values, adjust references as you drag down

Multiply the value in cell A1 by the value in cell B1, but keep the reference to cell B1 absolute.  
**Formula:** =A1\*$B$1  
**Solution:** Product of values, B1 remains constant as you drag down