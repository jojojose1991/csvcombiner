# CSVCombiner
Simple shell script to combine CSV files

# Description
This shell script can be used within a Linux machine to combine multiple CSV files quite simply. This single file script utilizes only basic Linux utilities and has no other dependencies.

Best run after placing the script in shared path like `/usr/local/bin`

# Usage
```
Usage: csvcombiner.sh [-h] [-x HEADER_ROWS] -o OUTPUT_FILE GLOB 
Concatenates multiple CSV files into a single file, with header row optionally specified
Options:
    h - Print this help menu and exit
    x - Total number of header rows to be copied. Default is 1.
    o - Output file for concatenated csv files
    
GLOB can be any file pattern as accepted by the ls command
```