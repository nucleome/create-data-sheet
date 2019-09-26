# create-data-sheet
Create data sheet for nucleome browser from 4DN metadata table

# Usage
* Download metadata TSV from 4DN data portal and download files.
![Download metadata](download_data.png)
* Run create-data-sheet.

`python create-data-sheet.py -i <metadata_table> -o <output_name> -d <data directory>`
* Paste generated .tsv to your Google Sheets.
* Launch nucleome browser.
