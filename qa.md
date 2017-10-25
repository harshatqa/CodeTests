# SignalPath, LLC.
## QA Engineer Code Assessment

Please rank each of the following tools, languages and frameworks on a 4 point scale, where 1 = "I’ve been paid to write production-quality code with it." and 4 = "I could write the equivalent of a Hello World web application if I had a tutorial."
* JQuery--4
* Python--4
* Cucumber--4
* Scala--4
* Selenium--4
* Puppet--4
* Rspec
* Node.js--4
* Ruby--4
* Watir
* Java  --4
* Jenkins
* Chef--4

1.  SignalPath has bought a new vending machine and it is going to be under heavy usage (we love snacks). You have been nominated to test it and make sure it is up to the task. How would you approach this?
Answer:- I will check if the machine is testable once plugged-in(Adhocking), then I will use following test cases (for example few)
TC1. Determine what kind of coins or Dollar bills machine accepts.

TC2. Determine whether machine return change if inserted more money 
         then required for an item.
TC3. Determine machine response if inserted less money then required 
         for item
TC4. Determine machine accept paper bills as well.
TC5. Determine min amount that machine accepts
TC6. Find out if machine accepts coins when there is no item      
        available.find out response when coin box is full.
TC7. Find out response when items available in machine…

TC8. Check user wants to have more then one item in one transaction ( should get insert cash or use credit card message from machine.

TC9. Check if the machine dispensing right item.

TC10. Check if user can cancel the transaction
TC 11. Check if user insert fake currency.


2.  Create two test cases for Twitter’s authentication functionality.

Answers : TC1. Verify logging twitter with blank username and password
          TC2: Verify logging with username and blankpassword
          TC3. Verify logging with password and username field balnk 
          TC4. Verify logging with incorrect credentials
          TC5. Verify logging with correct credentials.





3.  Using any tool of your choice, create an automated test for one of the two test cases from the previous question (Twitter); or if your scripting knowledge is limited, discuss how you would go about testing the test case using automation.

Answer: I will create test suite for above twitter authentication, for example if I leave user name and password fields  blank in the automatation test script that means when executing the test script test is fails and execution paused on the authentication page.
when user write correct credentials in automated  test script execution will further moves to landing page


4.  Suppose you have a web site with two form elements on it: a multi-line textarea and button that says “multiply”. The expected behavior is that when you click “multiply” all of the numbers written in the textarea are multiplied together and written next to the textarea. For instance, if the textarea has the numbers 5, 7, 11 then the output will be 385. Identify all the test cases that you would need to write. (You do not actually need to write the detailed steps for every test case, just the summary.)

Answer: determine clicking multiply button with  inputs(empty, alphabets, alphanumeric, special characters, negative numbers, decimals, whole numbers). Incase if there is limit then I will check boundary values ( acceptable number range) 



