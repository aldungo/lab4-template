# Lab 4: Meal Cost Calculator with Tip and Tax

*Lab is always due the *eve* before the next one. If you attend lab on Tuesday, this is due on Monday. For Wednesday lab, it is due Tuesday.*
## Purpose

The owner of a restaurant wants to calculate the total cost of meals given different amounts the customer might tip. This program will emphasize the following concepts:

- Using cast operators to round to two decimal places
- Using if statements to select one of many options

---

## In-Class 4: Outfit Selector Based on Weather

To prepare for writing this software, let’s consider another case that will require conditional executions. The user wants to decide on outfits based on the weather. Make a request for the user to input a temperature and then check for the following conditions:

Example outputs:
- If the temperature is greater than 70, the user should wear something light.
```
Please enter the temperature outside: 75
It’s pretty warm outside. You should wear something light.
```
- If the temperature is greater than 60, the user should wear pants and a long sleeve shirt.
```
Please enter the temperature outside: 68
It’s starting to get colder. Perhaps you should wear pants and a long sleeve shirt.
```
- If the temperature is less than or equal to 60, the user should take a coat.
```
Please enter the temperature outside: 50
It’s pretty cold outside. Make sure you take your coat.
```


---

## Task

Create a new Java file titled `Tipping_FirstName_LastName.java` or `Lab4_FirstName_LastName.java`. You must include comments describing key parts of this program.

### Steps

1. Make sure the initial code of your application is prepared to write statements in the main method.
2. Declare a Scanner that accepts input from the keyboard.
3. Declare the following two variables and one constant:
   - A variable of type `double` that will hold the cost of the meal
   - A variable of type `int` that will hold the user’s selection for the amount to tip
   - A **constant** of type `double` that will hold a sales tax of 8.25% (as a decimal)
4. Include a prompt to the user to input the initial cost of the meal (before sales tax or tip). Use the appropriate method of the Scanner class to assign the user’s input to the appropriate variable.
5. Calculate the cost of the meal with the sales tax applied and assign the result back to the same variable that holds the cost of the meal. (There are two ways to calculate sales tax. Both methods are accepted but one is more concise than the other!)
6. Include a second prompt to the user to input their choice of how much to tip. Use the appropriate method of the Scanner class to assign the user’s input to the appropriate variable.
7. Use if statements to check which option the user chose.
   - If the user chose option 1, apply a 10% tip and assign the result back to the same variable that holds the cost of the meal.
   - If the user chose option 2, apply a 15% tip and assign the result back to the same variable that holds the cost of the meal.
   - If the user chose option 3, apply a 20% tip and assign the result back to the same variable that holds the cost of the meal.
8. Display the final cost to the user rounded to two decimal places. You must use the cast operator and appropriate math operations to round to two decimal places.

#### Example Program Flows

If the user enters 9.99 for the initial cost of the meal and chooses option 3 (20% tip):
```
Please enter the initial cost of the meal: 9.99
Please enter your choice for the tip (1 = 10%, 2 = 15%, 3 = 20%): 3
The final cost of the meal is $12.98
```
This is only ONE possible program run. Your code should correctly handle any reasonable meal cost and whichever tip option (1, 2, or 3) the user selects. We could list many more examples (e.g., 15.50 with a 10% tip, 23.75 with a 15% tip, 100.00 with a 20% tip, very small values like 1.00, or values with more than two decimals like 12.347), but part of growing as a programmer is designing and running your own test cases. Try these ideas:

1. Vary the meal cost (small, typical, large).
2. Try each tip option (1 = 10%, 2 = 15%, 3 = 20%).
3. Manually compute the expected result with a calculator and compare to your program.
4. Check your rounding: does a value like 12.345 round the way you expect after tax and tip?
5. (Stretch) What happens if the user types an unexpected option like 4? (You are not required to handle it this lab, but thinking about it builds good habits.)

Build confidence by creating a quick list/table of inputs and expected outputs, then running them. The more you practice validating your own work now, the easier larger programs will feel later. You've got this—experiment, observe, adjust, and learn!

---

## Grading Criteria

- Comments describing this program (5 points)
- Importing and declaring the Scanner (8 points)
- Each of the two variable declarations (3 points each, 6 points total)
- Constant declaration (4 points)
- Request for the user’s input for the initial cost of the meal (5 points)
- Calculation applying the sales tax (10 points)
- Request for the user’s input for the choice of tip (5 points)
- Determining the correct amount to tip and performing the correct calculation (36 points)
- Output of the final cost rounded to two decimal places (21 points)



## Commit Your Changes
### Step 1. Use VS Code's Source Control panel:
   - Click the Source Control icon in the left sidebar
   - Type a commit message describing your changes
   - Click "Commit" then "Sync Changes" to push your code

### Step 2: Verify Submission
After pushing your changes, visit your assignment repository on GitHub Classroom. Confirm that your latest code and commit message appear, and that your files are named correctly. 

### Step 3: Submit to Blackboard Assignment
Once you have verified your submission on GitHub Classroom, copy the URL of your assignment repository and submit this GitHub repository link to Blackboard as confirmation that you are DONE.

**InClass4.java (Participation points):**
Full credit is awarded for completing and submitting the in-class exercise, regardless of output or minor errors.

**Keep going!** By Lab 4, you’re advancing your skills and showing real growth in programming logic and problem-solving. You’ve moved beyond the basics—now is the time to challenge yourself, experiment, and refine your approach. Trust your abilities, keep practicing, and take pride in your progress. If you encounter obstacles, use them as opportunities to learn and improve. Each lab is a step forward in your journey to becoming a confident, independent programmer. Stay curious, keep asking questions, and celebrate how far you’ve come!

**Important:** Do NOT edit or tamper with any test files (such as Lab4Test.java or InClass4Test.java). These files are used for autograding and checking your work. In future labs, if test files appear to be modified, you may be contacted to verify the integrity of your submission.