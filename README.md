Question 1:
We create an instance of BrowserHelpers and store it inside a global variable. Also we store the chai variable inside a global variable.

Question 2:
First we create an instance of the FizzBuzz class, then we write tests for the instance in it blocks.

Question 3:
By using == you check if something is equal to something else. This is not strict.
By using === you check if something is equal to something else. This is also strict, it checks not only the equality of the two values, it compares the types of the two values too.



Question 4:
It is important to move 'number % 15 === 0' on top because we want to check if the number is divisible by 15 first. 
When we want to check the number 30 and 3 or 5 would be on top of the if statement the code would return either Fizz or Buzz and not FizzBuzz. Since the number 30 is divisible by both numbers 3 and 5, the test would be satisfied after the first if statement. It wouldn't move on to the else statement where we check if the number is divisible by 15 to return FizzBuzz.

Question 5:
Unit test tests the code, if it works.
Feature test tests the code from the perspective of a user on the website. From loading the website to using the elements on the website.

Question 6:
First the test initializes the browser and goes to our website. Then it should reload the page before each test. After that we tell the test to close our browser after the tests.

Question 7:
We tell the test what we expect the outcome to be.

Question 8:
First the document waits for the DOM's content to be loaded and then it looks for the button by id and we store it inside a variable. We also store the div to display the answer inside a variable. After that the document waits for the button to be clicked. We store the input value inside a variable and creae an instance of the FizzBuzz class. In the next step it checks the value and we store that in another variable. In the end we want the result div to be displayed.

Question 9:
For example the stylesheets of semantic ui are stored on many different servers. When we use it in html for our website we receive the information from many servers. If we have problems to receive the information from one specific server, then we will get the information from another server and our style will still be shown on our website.