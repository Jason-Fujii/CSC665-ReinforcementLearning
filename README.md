# CSC665-ReinforcementLearning

Jason Fujii
921019525


For Q1, the main chunk of code that I would like to talk about is the function, "computeMaxValue." I realized that runValueIteration would require
me to do almost every single thing that computeActionFromValues had to do except for the return datatype. I didn't want to rewrite logic or code,
so I decided to write this function. Basically, this function finds the action with the maximum Q Value and returns a (action, value) pair instead
of just the action. From here, I could use the tuple to give the max value to runValueIteration and the action to computeActionFrom Values.

For Q6, I just ended up following the same structure as q1. That means that I found the new QValues using the formula from lectures, updated the old
values to match the new values, then let the agent do the rest of the work. ComputeValueFromQValues and ComputeActionFromQValues were similar to 
computeActionFromValues and computeValueFromValues from q1, so I basically just followed the similar format

How Many Hours did you spend on this assignment?
  I think I ended up spending 8 - 10 hours on this assignment. From going back to the lecture slides and trying to figure out how to make the formulas
  work to playing around with the values in analysis.py, I spent a majority of time just fiddling around with certain values trying to make them work.
