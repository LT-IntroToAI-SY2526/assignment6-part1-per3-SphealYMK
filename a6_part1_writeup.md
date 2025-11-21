# Assignment 6 Part 1 - Writeup

**Name:** **Matthew Kupiec**
**Date:** _______________

---

## Part 1: Understanding Your Model

### Question 1: R² Score Interpretation
What does the R² score tell you about your model? What does it mean if R² is close to 1? What if it's close to 0?

**YOUR ANSWER: the r2 score tells me that my model has a really strong linear corelation. The farther from zero the stronger the linear relation, and vise verse for closer to 0**




---

### Question 2: Mean Squared Error (MSE)
What does the MSE (Mean Squared Error) mean in plain English? Why do you think we square the errors instead of just taking the average of the errors?

**YOUR ANSWER: A measure of the average of the squared differences between predicted values and actual values. It is used to evaluate the accuracy of predictive models. We should use this instead of just the average because, the MSE does a better job of indicating the quality of a models fit**




---

### Question 3: Model Reliability
Would you trust this model to predict a score for a student who studied 10 hours? Why or why not? Consider:
- What's the maximum hours in your dataset?
- What happens when you make predictions outside the range of your training data?

**YOUR ANSWER:I would maybe not trust it, as life happens, so it is almost guarenteed to vary, big and small. The max number of hours: 9.6. IF a prediction is outside of the range of the training data, the AI would strugle, or just be completely wrong**




---

## Part 2: Data Analysis

### Question 4: Relationship Description
Looking at your scatter plot, describe the relationship between hours studied and test scores. Is it:
- Strong or weak?
- Linear or non-linear?
- Positive or negative?

**YOUR ANSWER:Strong, linear, Positive**




---

### Question 5: Real-World Limitations
What are some real-world factors that could affect test scores that this model doesn't account for? List at least 3 factors.

**YOUR ANSWER:**
1. ACT scores
2. Physics
3. Skill-checks


---

## Part 3: Code Reflection

### Question 6: Train/Test Split
Why do we split our data into training and testing sets? What would happen if we trained and tested on the same data?

**YOUR ANSWER:It would only know how to do that one specific data set, and nothing else**




---

### Question 7: Most Challenging Part
What was the most challenging part of this assignment for you? How did you overcome it (or what help do you still need)?

**YOUR ANSWER:I had some errors, and still have some about 'Hours Studied' and some other weird Panda errors**




---

## Part 4: Extending Your Learning

### Question 8: Future Applications
Describe one real-world problem you could solve with linear regression. What would be your:
- **Feature (X):Yearly Taxes Payed** 
- **Target (Y):Yearly Salaru** 
- **Why this relationship might be linear:**
**Because one thing tends to effect the other**
**YOUR ANSWER:**

**(I was kinda in a rush torwards the end)**


---

## Grading Checklist (for your reference)

Before submitting, make sure you have:
- [ ] Completed all functions in `a6_part1.py`
- [ ] Generated and saved `scatter_plot.png`
- [ ] Generated and saved `predictions_plot.png`
- [ ] Answered all questions in this writeup with thoughtful responses
- [ ] Pushed all files to GitHub (code, plots, and this writeup)

---

## Optional: Extra Credit (+2 points)

If you want to challenge yourself, modify your code to:
1. Try different train/test split ratios (60/40, 70/30, 90/10)
2. Record the R² score for each split
3. Explain below which split ratio worked best and why you think that is

**YOUR ANSWER:**
