SQL Functions
-------------
String Function: TRIM()
-----------------------
Definition:
The TRIM() function removes leading and trailing spaces from a string.

Syntax: 
TRIM(string)

Parameter values:
string	--> Required. The string to remove leading and trailing spaces from

Example: 
SELECT TRIM('    This is the statement.    ') AS TrimmedString;

The Result:
This is the statements.
--------------------------------------------------------------------------------------

Numeric Function: TRUNCATE()
----------------------------
Definition:
The TRUNCATE() function truncates a number to the specified number of decimal places.

Syntax: 
TRUNCATE(number, decimals)

Parameter values:
number	    --> Required. The number to be truncated
decimals    --> Required. The number of decimal places to truncate to

Example: 
SELECT TRUNCATE(254.589654, 1);

The Result:
254.5
---------------------------------------------------------------------------------------

Advanced Function: BIN()
------------------------
Definition:
The BIN() function returns a binary representation of a number, as a string value.

Syntax: 
BIN(number)

Parameter values:
number	---> Required. A number

Example: 
SELECT BIN(10);

The Result:
1010
----------------------------------------------------------------------------------------

Date Function: TIME_FORMAT()
----------------------------
Definition:
The TIME_FORMAT() function formats a time by a specified format.

Syntax: 
TIME_FORMAT(time, format)

Parameter values:
time	--> Required. The time to be formatted
format	--> Required. The format to use. Can be one or a combination of the following:

Example: 
SELECT TIME_FORMAT("19:30:10", "%h %i %s %p");

The Result:
07 30 10 PM
