java c
CO 327 Winter 2025: Assignment 1 problems 
Due: Wednesday January 15, 11:59pm EST 
Assignment problems. 
A1-1. LP formulation and Gurobi 
The Let It Grow company is preparing to sell plant fertilizers for the spring and fall seasons. There are three main components of a fertilizer: nitrogen, phosphorous and potassium. A fertilizer often has a NPK rating consists of three numbers a−b−c, representing the percent-age of nitrogen, phosphorous and potassium in the fertilizer, respectively. For example, in 1 kilogram of a fertilizer with NPK rating of 20 − 10 − 5, there are 200 grams of nitrogen, 100 grams of phosphorous, and 50 grams of potassium. The remainder of the fertilizer consists of materials that are freely available (e.g. water, soil, etc.).
Let It Grow wants to make 7 different types of fertilizers that are designed for different purposes. Their NPK ratings and their selling price are listed in the following table.

The company has a limited supply of the three chemicals: 3000 kilograms of nitrogen, 1000 kilograms of phosphorous, and 1500 kilograms of potassium. The goal is to maximize the total value of the fertilizers that are produced.
(a) Formulate this problem as a linear program. Make sure you clearly explain your vari-ables, objective function and constraints.
(b) Using Gurobi, implement the linear program from part (a) and solve it. Include the program you input into the s代 写CO 327 Winter 2025: Assignment 1 problemsR
代做程序编程语言oftware, and the output that includes the optimal solution and optimal value. State separately the optimal solution and value to the word problem.
(c) Suppose the company is testing different prices for all purpose fertilizers. Experiment with Gurobi to see how does the optimal solution vary according to changes in the price of all purpose fertilizers. For each possible optimal solution, write down the range of possible prices that result in that solution. You do not need to be exact on the prices, though they should be pretty close. Include some work on how you have determined the solutions.
(Hint: The attribute “obj” for a variable can be useful. If v represents the variables of your model, then v[0].obj = 5 sets the coefficient of the variable at index 0 in the objective function to 5.)
A1-2. Review: Duality and complementary slackness 
(a) Let (P) be the following linear program.

Write down the dual (D) of (P) using y as the vector of dual variables. (No justifications required.)
(b) Write down all the complementary slackness conditions for (P) and (D).
(c) Let ¯x = (3, 0, −2, 0, 7)T. Use the Complementary Slackness Theorem to prove that ¯x is optimal for (P). In particular, you need to determine a possible optimal solution for (D).
(d) Use the Weak Duality Theorem to give an alternate proof that ¯x from part (c) is optimal for (P).



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
