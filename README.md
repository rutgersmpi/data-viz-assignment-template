![](https://bloustein.rutgers.edu/wp-content/uploads/2017/05/Shield-RedTransparent.png | width=100)

# Lesson 0 R Programming Assignment


## Objectives
Develop a basic understanding of the R programming language and workflow of R programming for informatics applications.
Become familiar with the testing process in software development.

## Directions
Complete the R code in the file `assignment.R` contained within the `assignment` folder so that the variable `answer` contains the solution to the math problem 2 + 2. Ensure that your solution is a number.

## Submission
Submit your completed code via GitHub Classroom prior to the deadline. No late submissions will be accepted.

## Grading
You can earn up to 5 points for this assignment. Your submitted code will be automatically tested each time you commit changes to the file `assignment.R` using GitHub Actions. You can submit and grade your work as many times as you would like prior to the deadline.

### Grading your work on your local machine

A copy of the program used to grade your work is included, and can be run on your local machine so you can test your code prior to submission.

Ensure that you have the `{testthat}` package installed on your local machine by running `install.packages("testthat")`.

Then, from RStudio, and with this repository as your working directory, copy and paste the following line of R code to grade your assignment:

`testthat::test_file("tests/testthat/grade_assignment.R")`

The program will test your code and print any failures to the console. You'll need to ensure that your code passes each test in order to receive full credit for this assignment.