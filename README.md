# python-googlesheets-to-xlsx
![google sheets to xlsx](https://user-images.githubusercontent.com/24693129/74635026-d1b7f300-516d-11ea-9aa7-a54f4c4185f5.png)

Python script to download Google Sheets Data as an Excel .xlsx file.
Supports dowload of multiple sheets in one spreadsheet.



## Usage:
1. Set-up and add your `credentials.json` file to the same directory as this script (see Step 1 in https://developers.google.com/sheets/api/quickstart/go)  
2. Make sure that you have all the necesary Python 3 packages installed:
```
pip install gspread
pip install pandas
pip install oauth2client
```
3. In line 9 `downoalod_sheet()`, replace string with ID of the document that you want to download
![Screenshot 2020-02-17 at 10 16 43](https://user-images.githubusercontent.com/24693129/74635554-ef398c80-516e-11ea-94c1-66bad04d1abb.png)

4. Run Script and enjoy your .xlsx file

## Working example:
![Screenshot 2020-02-17 at 10 13 54](https://user-images.githubusercontent.com/24693129/74635234-455a0000-516e-11ea-8570-25f9ec2e5ddb.png)

