-Explain the purpose of the Test (what the original test exposed, and what your test expose)

The purpose of the test is to check if all the number plates will be recognized. 
In his test he shows information about : number of correct images, number of total images and the accuracy.
In my test we show all of the above and individual results of each test.


-Explain about Parameterized Tests in JUnit and how you have used it in this exercise.

Paramatized test is used to programaticly create multiple test instances from a single test giving difrent paramaters to the constructor,
in my case it enabled me to test all of the numberplates induvidualy from a few line of code  


-Explain the topic Data Driven Testing, and why it often makes a lot of sense to read test-data from a file.

The idea behind DDT is to check the behaviour of our functionality with the supplied data. There are no hard coded values and that means
it is easy to change thus proving if our logic works. 

-Your answers to the question; whether what you implemented was a Unit Test or a JUnit Test, 
the problems you might have discovered with the test and, your suggestions for ways this could have been fixed.
The steps you took to include Hamcrest matchers in the project, and the difference they made for the test.


JUnit is a guide line how to make our tests and run it ( its the runner). 
It is a JUnit test. 

I added the dependency in the pom file. 
Using Hamcrest made our failed results more readable.
