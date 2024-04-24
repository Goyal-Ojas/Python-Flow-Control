# Python-Flow-Control

Objectives

The purpose of this checkpoint is to give you practice with using flow control. However, it will implement lessons learned in prior chapters as well.

Background

You are a medical researcher running a study on a new drug. You are screening potential participants and you need to make sure you identify any outliers. In particular, you want to flag anyone who is outside the typical ranges of tall/short or light/heavy. Therefore, write a simple routine to determine if a potential participant is eligible based on.

Weight Height Sex

Requirements

Collect these three data points through user input() boxes. Men within 62 inches and 80 inches tall and between 150 and 280 lbs are needed for this study. Women between 59 and 71 inches and 100 and 180 lbs are needed for this study. Create flow logic to determine whether an inputted patient is within the thresholds. If they are an outlier, print a message indicating they are not eligible and tell them which thresholds they did not meet. Create as many if/elif/else statements as you need to accomplish this task. For example, the table below indicates potential inputs and outputs:

Entered inputs:               Output:

Sex   Weight   Height

Male     220        81         Participant is too tall

Male     149        62         Participant is too light

Female 170        58        Participant is too short

Female 140        68        Participant qualifies for the study

In order to analyze data, we need to handle the many possible ways that these data could be entered. For example, sex could be entered into a textbox as "female", "f", "Female", 0, 1, "Male", "Man", "woman", or it could be mispelled. Use some combination of if/elif/else statements (including "or" and/or "and" criteria) and/or string formatting (e.g. converting case or examining only the first letter) to handle as many possibilities as you can think of to handle every type of input.

To keep this simple, you do not need to validate that the user enters numeric inputs for weight and height. You can assume they will enter acceptable values.

There are many different ways to complete these requirements. You are not being tested to see if you use a particular method. Your code simply needs to meet the requirements above with only one exception. You must find a way to use each of the following commands in your solution: if, else, and elif
