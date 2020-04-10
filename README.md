1. Introduction:
Python has gained a lot of traction in last decade and is getting very popular among testers also for automation testing, web scraping, security testing and automating other mundane tasks. In this multi part tutorial we will try to write automation scripts in Python using Selenium Webdriver.

2. Agenda:
This would be a multi part tutorial, in which we will write automation script for search and add to cart/ delete from cart functionality of amazon. We will then refactor our script as we evolve in our learning also. Final product that we are aiming here is automating search feature in Amazon using python unittest and for reporting HtmlTestRunner module. Precisely, following cases are being aimed at, for the purpose of automation.

3. Create Virtual Environments:
A virtual environment is a tool that helps to keep dependencies required by different projects separate by creating isolated python virtual environments for them.

4. Python Module used:
 - selenium -->pip install selenium
 - HtmlTestRunner -->pip install html-testRunner

5. WebDrivers are maintained under Drivers folder.

6. HTML reports are maintained under Reports folder.

7. Test case name: 
Amazon_AllTests.py

8. Command to execute the tests:
Since our python modeles are under venv folder so we need to first set the PythonPath followed by running the test with the below command.
 - set PYTHONPATH=./venv/Lib/site-packages;
 - python Amazon_AllTests.py -v
 
 Links:
 https://medium.com/@asheeshmisra29/web-automation-selenium-webdriver-and-python-getting-started-part-1-157be93049d7
