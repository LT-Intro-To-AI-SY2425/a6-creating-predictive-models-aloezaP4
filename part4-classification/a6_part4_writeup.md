# Part 4 - Classification Writeup

After completing `a6_part4.py` answer the following questions

## Questions to answer

1. Comment out the StandardScaler and re-run your test. How accurate is the model? Why is that?
0.61 This is because the data was not scaled and therefore skewed which causes the accuracy to be lower.

2. How accurate is the model with the StandardScaler? Is this model accurate enough for the given use case? Explain.
0.81 with the StandardScaler. I would say it is accurate enough for the given case as the number is close to 1.0.

3. Looking at the predicted and actual results, how did the model do? Was there a pattern to the inputs that the model was incorrect about?
Looking at the predicted vs actual, they seem to be correct most of the time. A pattern I see with the incorrect ones is that the third value is around -1.0202... 


4. Would a 34 year old Female who makes 56000 a year buy an SUV according to the model? Remember to scale the data before running it through the model.

The model guessed that she would not buy the suv.