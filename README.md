# Lab-8_202001128
Unit Testing with JUnit

Name: Meghaben Rathwa

Student ID: 202001128

LAB : 08

1)I created new java project in eclipse IDE with name Lab and package mypackage

2)Then I created class named Boa inside mypackage and added code which was given in exercise

3)Then I created JUnit test file for  Boa class named BoaTest 

4)Then I modified the setup method to initialize the variables

5)Then I also implemented tests for the given two functions testIsHealthy() and testFitsInCage().


For testing the fitsInCage() function, there is no need to write tests for both jen and ken objects as the function is same for both and the output of test cases depends only whether the given length is greater than,less than or equal to actual length of object.The behavior will be similar in both cases.

6)Then I ran the JUnit test file and all the tests were passed . There were no red bars in output , as shown in figure

  From the figure we can see that two out of two test cases has been passed.

7)Then I added a new method to the class named Boa with name lenghtInInches() to get the length in inches.

As the length of the Boa was given in feet, to convert it into inches, I had multiplied given length with 12 and returned the value.

8)Then I wrote another test case for this new method and ran all the 3 test cases together.

Thus, all the test cases that have been written for the  Boa class and all the three methods that have been tested with required Junit test cases.


