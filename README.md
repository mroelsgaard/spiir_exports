# spiir_exporter
Tool to import csv-files from mine.spiir.dk into a Pandas dataframe, and furthermore re-export them into a Google Sheets document with gspread and gspread_dataframe.

* Pandas (https://pandas.pydata.org/)
* gspread (https://docs.gspread.org/en/v5.4.0/)
* gspread-dataframe (https://pypi.org/project/gspread-dataframe/)

# Usage
Create a json-file with your authentication token, follow this: https://docs.gspread.org/en/v5.4.0/oauth2.html#enable-api-access-for-a-project

Download a CSV of all entries with "Avanceret eksport" through mine.spiir.dk (here: https://mine.spiir.dk/Profile/ExportAllPostingsToCsv). Edit the paths of the ipynb's appropriately and run it.
