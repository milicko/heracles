Tasks:
1. Find how to create and start application from embedded tomcat
2. Create application that will convert entered number to monetary form
3. Create UI tests using Selenium
4. Add javadoc and send report

Task 1 & 2:

This was a real challenge for me because I didn't do anything similar in my career. I was searching how to create application that I can start, create and test and I found that I can use embedded tomcat with jsp file where I can write javascript methods for my code.
The implementation was not a problem it took me one day to explore and implement methods for my application.

Task 3: 

Because I don't have experience in witting java script code I decided to test my app using Selenium, I have created little wrapper and I have for my tests and i have created module called money-converter-tests.
In that module I have methods that I need to test this application, methods are by POP design and all methods and tests have documentation. I have 17 tests for my application that are independent. Note that I run tests only on Chrome browser, but they will probably work on all other browsers. For automated test I needed half a day.

Task 4:
All done

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

How did your structure your code? (eg: is it structured in a testable way?) :
    - My code isn't structured in testable way because I didn't make applications at my previous job so I don't have expirience in writing javascript code
    
What did you test?
    - I tested basic functionality of the input fields, functionality of buttons, behaviour of alert dialog, main functionality of the app, converting valid and not valid numbers and combination of format button with clear button


How did you test the functionality? and the user interface?
    - I tested functionality with Selenium WebDriver

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

INSTRUCTIONS:
    
How to start app and automated tests:

0.  After checkouting project build project to get dependencies
1.  You need to download chromedriver for your OS and for your chrome version you can do that here http://chromedriver.chromium.org/downloads, after you find chromedriver for your OS and for your chrome download it and extract it on your machine
2.  Go to module money-converter-tests/src/main/java/base/BaseTest.java and change hardcoded path to chromedriver with path of your chromedriver
3.  Go to module money-converter-app/src/main/java/launch/Main.java and run main method to start tomcat (if you have some tomcat started on port 8080 you will need to kill that app), now the app is started
4.  Open browser and type localhost:8080 in order to go to the app
5.  To start automated tests tomcat with app needs to be started so you need to go to module money-converter-tests/src/tests and find tests in functionality and verification package to run them



Hope that you will not have any problem. If you have any problem please LMK. I didn't have more time to add some css or some more tests but I thing that with created tests basic functionality is covered.

Happy reviewing!
