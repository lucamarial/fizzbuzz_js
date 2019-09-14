Question 1:


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