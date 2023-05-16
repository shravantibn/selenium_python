# selenium_python
Web Automation - HTML Basics - Tags and Elements

Python libraries to help with automation such as Path, Selenium, XPath.
#
###
Python strftime cheatsheet

Link: https://strftime.org/

###
Preparing Script to Be Run Everyday

Convert py to executable file and schedule the file to execute at perticular time

1. pip install pyinstaller (install lib)
2. pyinstaller --onefile filename 
3. exec the file in dist folder
4. schedule the exec file: crontab -e  
0 9 * * * filepath (In insert mode and save)
(crontab.guru website for format e.g: 0 9 * * * "At 09:00")
5. Check the command crontab -l
