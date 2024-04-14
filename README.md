## Practice - Upload DataFrame to Google Sheet
### Overview
This is a simple practice project aimed at connecting a Pandas DataFrame with Google Sheets and uploading it.

Firstly, we should enable the Google Sheets API and create credentials. Then, add a key to this credential, choosing the JSON key type. The key will be downloaded, completing the creation of the credential. We should place this JSON file in the same folder as app.py.

Next, add this credential account to a new Google Sheet to allow it to be shared, and note down the ID of this Google Sheet for updating the corresponding Python code.

By utilizing packages such as [gspread](https://pypi.org/project/gspread/), [google.oauth2.service_account module](https://google-auth.readthedocs.io/en/master/reference/google.oauth2.service_account.html), and [gspread_dataframe](https://pypi.org/project/gspread-dataframe/), we can obtain authorization for Google Sheets and successfully upload the Pandas DataFrame to Google Sheets.