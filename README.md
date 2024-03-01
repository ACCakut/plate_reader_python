# plate_reader_python
Some Python scripts to analyse OD growth curves from plate readers as those from Tecan.

## import_Tecan.py
Provides function import_Tecan_xlsx to extract OD values from Tecan i-control™ software saved in Excel spreadsheets and returns a nice pandas dataframe. Documentation is part of the code.
```
from import_Tecan import *
import_Tecan_xlsx("your-file.xlsx")
```
