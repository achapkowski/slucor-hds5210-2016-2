_SLUCOR HDS5210 - Programming for Health Data Science - 2016 Fall_

Week 1 (Aug 24) Exercises
===
_Gries Ch 1, 2_


#1 Get Setup for Class
---
There won't be anything to submit for #1, but the log files will show who has and hasn't gotten their accounts configured and will be able to connect to everything.

1. Signup for an account at https://education.github.com/pack/join
2. Sign-on to https://jupyter.slucor.net/hub/login using your new GitHub.com account
3. Create a new notebook called "week01-`username`" for the assignments below

Two Rules
---
1. All of your assignment notebooks should be named using the same consistent format: "week##-username".  You'll lose points if they aren't named correctly.
2. At the top of each notebook cell, include the problem number and title as a comment in your code.

#2 Processing in Python
---
In the first cell of your notebook, use a comment block to explain how Python evaluates the following expression when `x` has the value of 3.
```
x += x - x
```

#3 Average Heartrate
---
In the next cell of your homework notebook, compute the floating point average of the following numbers, using basic +, -, \*, / arithmetic, assign that to a variable named `average_heartrate`. Print that result to the notebook's output. Don't use lists or the average function, yet.

98, 87, 92, 90, 90, 91

#4 BMI
---
Create variables with the corresponding values from the table below, and using the variables to compute the corresponding body mass index (BMI). You can use any meaningful variable names you like. When you compute the BMI, assign a variable to it, and then print the result to the notebook's output.

* Weight in kilograms is 90.7
* Height in centimeters is 182

Note that a simple BMI calculation is weight in kilograms divided by the square of height in meters.

#5 Weight Loss
---
Assuming that someone doesn't change height over time, what is the approximate number of days it will take for someone to get from the BMI from #4 above to a supposed healthy BMI of 24.9, while losing weight at a rate of 0.75 kg per week.

As needed, use variables and multiple calculations to make your thought process visible in the code, rather than using the notebook simply as a calculator.  Make sure your final answer appears in the notebook's output.
