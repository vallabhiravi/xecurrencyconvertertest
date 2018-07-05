# 'xecurrencyconvertertest' Acceptance Test Suite

XE currency converter acceptance testsuite is to test basic acceptance criterias for various input parameters entered in 3 basic fields available under ['XE Currency converter'](https://www.xe.com/currencyconverter/) header of the webportal. 
Each test result was matched against the 'XE Live Exchange Rates' table available in the same portal.

### Requirements for building test suite

- Intellij Idea
- Java 8
- Maven 3.3.9 or more
- Junit framework(4.12 is used)
- Related dependencies for Maven Java and compilation plugins
- Chrome browser 44 and driver 2.18

### Requirements for running test suite

- Java 8
- Maven 3.3.9 or more
- Junit framework(4.12 is used)
- Chrome driver placed in the zip file.
- Chrome browser 44 and driver 2.18

### Platforms

- Windows

### TestSuite execution process
1) Extract files from **"AcceptanceTestPackage.7z"** and place them in any of the folder structure ex: C:\XEAcceptancetestsuites
2) Create a folder named **"TestReports"** in *"C:"* Drive else create a different folder and update your reports directory path in the 2nd line of 'Execution.bat'.
3) Double click on the **Execution.bat** file to execute test scenarios.

### Test Reports
Basic report is generated under TestReports folder with the failures identified in the test suite.

Ex: Sample Test Report

**Total failures are listed below:**
currency_conversion_success_happypath [3] (acceptancechecks.XEConversionSuccessAT): Currency Converter values should match with daily rate **expected:<91067[.]>** but **was:<91067[]>**



	
