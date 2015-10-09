# Get Error Column Names in SSIS
A sample package showing how to get Error Column Names.

It reads a flat file (Accts.txt) and tries convert a decimal value into a date, causing errors, and thus the Errors.txt file is created with the error column name and description.

### Usage
* Change the `ffRoot` variable to the directory where you've cloned to
* Run it, and open Errors.txt to see the error column names/descriptions 