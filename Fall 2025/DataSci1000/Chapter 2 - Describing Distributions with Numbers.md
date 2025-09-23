
Mean - Sum of values divided by total number of values
$\bar{x}$ is the mean of a specific sample set, it just means the mean of a sample
e.g. sample set of: 4, 21, 5, 22, 8, 11, 5
$\bar{x}$ = (4+21+5+22+8+11+5)/7

Mean is the "balance point" of a distribution, where the weight on each side of the mean is equal, the mean is sensitive to outliers, especially with smaller data sizes

Median - Is the midpoint of the distribution, 
- in data sets of even values, it is the average of the two middle values
- in data sets of odd values, the middle is the middle value

Mode - most frequent value(s) in a dataset
- for histograms, can be the most frequent bin/width
- defined as the local maximum
- consider relative frequency

A **measure** is called **resistant** (or robust) if its value does not change much when a small number of observations are significantly changed

Measuring Variability: The quartiles
Q1 - Median of lower half
- Does not include the median when data set is odd
- When even, ~~include all values in the assigned half~~ exclude the two values that make up the median
Q2 - Overall median
Q3 - Median of upper half
![[Screenshot 2025-09-16 at 12.08.21 PM.png]]
e.g. with dataset:
4 5 5 8 11 21 22

Q1 includes: 4 5 5
Q2 is 8
Q3 includes 11 21 22
Q1 is 5
Q3 is 21

Five Number Summary:
Includes, min, Q1,Q2,Q3, and max

Boxplot - A graphical representation of the five number summary
![[Screenshot 2025-09-16 at 12.18.48 PM.png]]

example where max is the same as Q3 on right
![[Screenshot 2025-09-16 at 12.20.17 PM.png]]

Interquartile Range:
- Difference between third and fist quartile
- IQR = Q3-Q1
"Inner Fence":
(Q1 - 1.5xIQR,Q3+1.5xIQR)
- basically the range that data should be with that is not considered an outlier
- Uses ranges between first and third quartile to create an area where you would expect most observations to be within, otherwise considering them an outlier

e.g. data set: 
5 6 7 ~~7.5 7.5~~ 8 8 8
min - 5
max - 8
q1 - 6
q2 - 7.5
q3 - 8
IQR = q3 - q1
	 =8-6
	 =2
Inner fence:
$(q1-1.5*IQR, q3+1.5*IQR)$
=(6-3, 8 + 3)
= (3,11)
Any value outside of this inner fence may be considered as a outlier

A modified boxplot uses the inner fence as the min and max values where the whiskers would lie.

**Variance and Standard Deviation:**
Deviation: $x_i-\bar{x}$
Squared Deviation :$(x_i-\bar{x})^2$
Variance:
$$
s^2 = \frac{\sum_{i=1}^{n} (x_i - \bar{x})^2}{n-1}
$$
Standard Deviation:
$s=\sqrt{Variance} = \sqrt{s^2} = \sqrt{\frac{\sum_{i=1}^{n} (x_i - \bar{x})^2}{n-1}}$
