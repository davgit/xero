xero
====

Small Automated Acceptance Test for Creating A New Repeating Invoice Function using the Xero Web Application

Minimum requirements:
- Eclipse or similar IDE
- Firefox

How to run automated acceptance test:
- Right-click on the 'nz.xero.com.specification' package and select 'Run As' -> 'JUnit Test'
- Once the the test has finish running it will generate a HTML file which it will print on the console tab and is generally located in the below location

C:\Users\<your-windows-username>\AppData\Local\Temp\concordion\nz\xero\com\specification\RepeatingInvoicePage.html

Future updates:
- Put all the test data in a properties file
- Encrypt password in data file
- Refactor page objects to remove xpath and cleaner
- Install screen shots extension for Concordion (http://concordion.org/extensions/ScreenshotExtension.html)
- Create a simple build script and use Ivy or similar dependency management tool