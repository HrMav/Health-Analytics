## SCENARIOS
Describing Data with Graphs and Numerical Measures

## Scenario 1

**RBC Counts:** The red blood cell count
of a healthy person was measured on each of
15 days. The number recorded is measured in 106 cells
per microliter (uL).

5.4 5.2 5.0 5.2 5.5
5.3 5.4 5.2 5.1 5.3
5.3 4.9 5.4 5.2 5.2

a. Use an appropriate graph to describe the data.
b. Describe the shape and location of the red blood cell
counts.
c. If the person’s red blood cell count is measured
today as 5.7  106/L, would you consider
this unusual? What conclusions might you
draw?

**Answer 1**

a. Use an appropriate graph to describe the data.

For describing the distribution of data, a histogram is a commonly used visualization. A boxplot can also be used to describe the spread and central tendency of the data.
The histogram on the left shows the distribution of the red blood cell counts. Most of the counts seem to cluster around the 5.2 to 5.3 range. The boxplot on the right provides a summary of the data's spread and central tendency. 
The median (central line in the box) is around 5.3, with the interquartile range (the height of the box) spanning from roughly 5.2 to 5.4.

b. Describe the shape and location of the red blood cell counts.

From the histogram, we can provide a description of the shape and location of the data. The shape refers to the overall distribution (e.g., whether it's symmetric, skewed, etc.), and the location typically refers to the central tendency (e.g., mean, median).
The mean red blood cell count is 5.24×10^6 cells/L and the median is 5.2×10^6 cells/L. This indicates that the central location of the data is around these values.
As for the shape, the histogram suggests a roughly symmetric distribution, with a slight left skewness given that there's a minor tail on the left side.

c. To determine if the value 5.7×10^6 cells/L is unusual, we can calculate the standard deviation of the data and see how many standard deviations away from the mean this value lies. 
If it's more than 2 standard deviations away, it's typically considered unusual in many contexts.
The standard deviation of the red blood cell count data is approximately 0.154×10^6 cells/L. The value is roughly 2.99 standard deviations away from the mean.

Given that the value is nearly 3 standard deviations away from the mean, it would be considered unusual in most statistical contexts. 
A value lying more than 2 standard deviations away from the mean is often considered to be an outlier or atypical. Therefore, a red blood cell count of 5.7×10^6 cells/L 
might indicate some anomaly or change in the person's health, and it would be advisable to consult with a medical professional for a proper assessment.​

## Scenario 2

**Pulse Rates:** A group of 50 biomedical
students recorded their pulse rates by
counting the number of beats for 30 seconds and
multiplying by 2.

80 70 88 70 84 66 84 82 66 42
52 72 90 70 96 84 96 86 62 78
60 82 88 54 66 66 80 88 56 104
84 84 60 84 88 58 72 84 68 74
84 72 62 90 72 84 72 110 100 58

a.Draw a stem and leaf plot to describe the data,
splitting each stem into two lines.

b. Construct a relative frequency histogram for the
data.

c. Write a short paragraph describing the distribution
of the student pulse rates.

**Answer 2**

The decimal point is 1 digit(s) to the right of the |

   4 | 2
   4 | 
   5 | 24
   5 | 688
   6 | 0022
   6 | 66668
   7 | 000222224
   7 | 8
   8 | 0022444444444
   8 | 68888
   9 | 00
   9 | 66
  10 | 04
  10 | 
  11 | 0

The pulse rates of the 50 biomedical students ranged from a low of 42 to a high of 110. The median pulse rate was 79, indicating that half of the students had pulse rates below this value and half above. The average pulse rate among the students was approximately 76.44. The middle 50% of the students had pulse rates that fell between 66 (1st quartile) and 84 (3rd quartile), giving an interquartile range (IQR) of 18.

The histogram of the pulse rates showed the distribution of these values among the students. From the histogram, it can be seen that the distribution has a slight right skew, with more students having pulse rates on the lower side of the average. There might be a few outliers or extreme values on the higher side, as indicated by the maximum value of 110.

## Scenario 3

**Breathing Rates:** Is your breathing rate normal? Actually, there is no standard breathing rate for humans. It can vary from as low as 4 breaths per
minute to as high as 70 or 75 for a person engaged in strenuous exercise. Suppose that the resting breathing rates for college-age students have a relative frequency
distribution that is mound-shaped, with a mean equal to 12 and a standard deviation of 2.3 breaths per minute.
What fraction of all students would have breathingrates in the following intervals?

a. 9.7 to 14.3 breaths per minute
b. 7.4 to 16.6 breaths per minute
c. More than 18.9 or less than 5.1 breaths per minute

**Answer 3**

a. 9.7 to 14.3 breaths per minute
To determine the fraction of students with breathing rates in the interval 9.7 to 14.3 breaths per minute, we'll find the z-scores for both 9.7 and 14.3, then use the CDF to find the probability 
between these z-scores.
Approximately 68% of students have breathing rates between 9.7 and 14.3 breaths per minute.

b. 7.4 to 16.6 breaths per minute
Similarly, for the interval 7.4 to 16.6 breaths per minute, we'll find the z-scores for both 7.4 and 16.6 and then use the CDF.
About 95% of students have breathing rates between 7.4 and 16.6 breaths per minute.

c. More than 18.9 or less than 5.1 breaths per minute
For this part, we'll find the z-scores for 18.9 and 5.1. Then, we'll use the CDF to determine the probabilities for values greater than 18.9 and less than 5.1, and sum the two probabilities.
Only a small fraction (5%) of students would have breathing rates more than 18.9 or less than 5.1 breaths per minute.

These percentages stem from the properties of the standard normal distribution:

About 68% of the data falls within one standard deviation of the mean.
About 95% falls within two standard deviations.
About 99.7% falls within three standard deviations.

## Scenario 4

**Armspan and Height:** Leonardo da Vinci (1452–1519) drew a sketch of a man, indicating that a person’s armspan (measuring across
the back with arms outstretched to make a “T”) is roughly equal to the person’s height. To test this claim, we measured eight people with the following results:

Person 1 2 3 4
Armspan (inches) 68 62.25 65 69.5
Height (inches) 69 62 65 70

Person 5 6 7 8
Armspan (inches) 68 69 62 60.25
Height (inches) 67 67 63 62

![Leo](https://github.com/HrMav/Health-Analytics-Statistics-Inferences-R/assets/132946730/5b9a3e78-5032-44a5-8157-3f5e58911351)

a. Draw a scatterplot for armspan and height. Use the same scale on both the horizontal and vertical axes. Describe the relationship between the two variables.

b. Calculate the correlation coefficient relating armspan and height. 

c. If you were to calculate the regression line for predicting height based on a person’s armspan, how would you estimate the slope of this line?

d. Find the regression line relating armspan to a person’s height. 

e. If a person has an armspan of 62 inches, what would you predict the person’s height to be?

**Answer 4**

a. Draw a scatterplot for armspan and height.
We'll start by plotting the scatterplot of armspan against height and ensuring that we use the same scale for both axes. This will help us visually assess the relationship between the two variables.
The scatterplot shows a positive linear relationship between armspan and height. As armspan increases, height tends to increase, and vice versa.

b. Calculate the correlation coefficient relating armspan and height.
The correlation coefficient (r) quantifies the strength and direction of the linear relationship between two variables. We'll compute this for the given data.
The correlation coefficient relating armspan and height is 0.9459924. This indicates a strong positive linear relationship between the two variables, suggesting that as one's armspan increases, 
their height tends to increase proportionally.

c. Estimate the slope of the regression line.
The formula for the slope (b) of the regression line in simple linear regression is:
b =  r x sy / sx

where, r = correlation coefficient
sy = standard deviation of the dependent variable (height in this case)
sx = standard deviation of the independent variable (armspan in this case)

The estimated slope of the regression line is 0.8153215. This means that for each one-inch increase in armspan, we expect the height to increase by approximately 
0.815 inches, on average.

d. Find the regression line relating armspan to a person’s height.
The regression equation is given by: y = a + bx
where, y = predicted value of dependent variable (height)
a =  y-intercept
b = slope
x =  independent variable (armspan)

The regression line relating armspan to a person’s height is given by:
Height = 12.22144 + 0.8153215 × Armspan

e. If a person has an armspan of 62 inches, what would you predict the person’s height to be?
We'll plug the armspan value of 62 inches into the regression equation to predict the height.

If a person has an armspan of 62 inches, the predicted height would be approximately 63.8 inches.

The strong positive correlation of 0.946 and the regression line further supports the idea that a person's armspan is closely related to their height. 
The regression line gives us a tool to predict a person's height based on their armspan, and the predicted height for an armspan of 62 inches aligns closely with Leonardo da Vinci's claim.

In conclusion, the data suggests that Leonardo da Vinci's claim that a person's armspan is roughly equal to their height holds true for this sample of individuals, as indicated by 
the strong positive correlation and the regression line.

## Scenario 5

Soccer Injuries During the inaugural season of Major League Soccer in the United States, the medical teams documented 256 injuries that caused a loss of
participation time to the player. The results of this investigation, reported in The American Journal of Sports Medicine, is shown in the table.3

Severity Practice (P) Game (G) Total
Minor (A) 66 88 154
Moderate (B) 23 44 67
Major (C) 12 23 35
Total 101 155 256

If one individual is drawn at random from this group of 256 soccer players, find the following probabilities:
a. P(A) b. P(G) c. P(A \bigcup\ G)
d. P(G|A) e. P(G|B) f. P(G|C)
g. P(C|P) h. P(B^c^ )
