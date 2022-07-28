# R-course-assignments
**QUESTION 1**

Hypothesis testing with R: Simulate data x from rnorm(n = 50; mean = 0; sd = 2) and
y from rnorm(n = 50; mean = 2 + 1.5x; sd = 10) using set.seed(4). Fit a linear
regression of y on x using y = a + bx + e

(a) Plot the data and add the fitted line.

(b) Extract the p-value attached to the estimator b from summary(). This is the
p-value according to the null hypothesis that b = 0. Given the significance level 
= 0:05, are you going to reject the null hypothesis? 

(c) Repeat this exercise by generating another set of data. Keep the same structure
of the data generating process but use set.seed(200). What is your p-value and
what’s your decision on the null hypothesis?

(d) Read this article and discuss the limitations of the classical hypothesis testing.

(e) Read this article and discuss how prevalent p-hacking is in science.




**QUESTION 2**

R programming: Suppose we have two separate bags of balls. Bag A has N number of
balls in it, some white some black but we don’t know how many of each color. Bag B
has Kw white ball(s) and Kb black ball(s). You draw R number of balls from Bag A
and move them to Bag B. Then, you draw T balls sequentially from Bag B. Suppose
the sequence of the these balls turns out to be [S1; S2; : : : ; ST ]. We are interested in
the composition of balls in Bag A. List your hypotheses and count up all the ways the
observed data can happen. Which hypothesis would you believe more?

(a) Write a code to to calculate the number of ways the observed sequence [S1; S2; : : : ; ST ]
can happen for each hypothesis. Your function should work for any value of
N;Kw;Kb;R; T and for any sequence of balls [S1; S2; : : : ; ST ]. [R coding only]

(b) Which hypothesis is most likely when N = 20;Kw = 10;Kb = 10;R = 5 and the
observed sequence is [W;B;B;W;B;W].
